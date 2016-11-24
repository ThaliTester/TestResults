#### Test 9501784151844b4_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-24 10:42:18.716  3635  5746 I VacuumService: Vacuum at: now=1480002138716 tag=VacuumService
,11-24 10:42:18.755  3635  5749 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
11-24 10:42:18.796  3635  5747 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
11-24 10:42:18.799  3635  5747 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
11-24 10:42:18.846  3635  5747 W Uploader:  no longer exists, so no auth token.
11-24 10:42:18.852  3635  5749 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
11-24 10:42:19.113  3635  5751 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
11-24 10:42:19.132  5752  5752 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-24 10:42:19.136  5752  5752 D AndroidRuntime: CheckJNI is OFF
11-24 10:42:19.159  5752  5752 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-24 10:42:19.191  5752  5752 I Radio-JNI: register_android_hardware_Radio DONE
11-24 10:42:19.208  5752  5752 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-24 10:42:19.213   925  3847 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-24 10:42:19.261   925  3847 I ActivityManager: Start proc 5766:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-24 10:42:19.274  5752  5752 D AndroidRuntime: Shutting down VM
,11-24 10:42:19.601   925  3901 I WindowManager: Screenshot max retries 4 of Token{96a292f ActivityRecord{c1f0b0e u0 com.test.thalitest/.MainActivity t10}} appWin=Window{4d56de6 u0 Starting com.test.thalitest} drawState=2
,11-24 10:42:19.623  3635  5749 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 10:42:19.690  5766  5766 I CordovaLog: Changing log level to DEBUG(3)
,11-24 10:42:19.690  5766  5766 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-24 10:42:19.690  5766  5766 D CordovaActivity: CordovaActivity.onCreate()
,11-24 10:42:19.691  3635  5747 W Uploader:  no longer exists, so no auth token.
,11-24 10:42:19.697  5766  5766 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-24 10:42:19.698  3635  5751 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 10:42:19.731  5766  5766 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-24 10:42:19.766  3635  5749 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 10:42:19.800  5766  5766 I LibraryLoader: Time to load native libraries: 65 ms (timestamps 209-274)
,11-24 10:42:19.800  5766  5766 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-24 10:42:19.841  5766  5766 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {525a465}
,11-24 10:42:19.843  5766  5766 I LibraryLoader: Expected native library version number "",actual native library version number "",
11-24 10:42:19.844  5766  5766 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-24 10:42:19.855  5766  5766 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-24 10:42:19.856  5766  5766 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-24 10:42:19.891  5766  5766 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-24 10:42:19.910  5766  5766 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-24 10:42:19.910  5766  5766 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-24 10:42:19.910  5766  5766 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-24 10:42:19.910  5766  5766 I Adreno  : Build Date                       : 12/06/15
11-24 10:42:19.910  5766  5766 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-24 10:42:19.910  5766  5766 I Adreno  : Local Branch                     : mybranch17112971
11-24 10:42:19.910  5766  5766 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-24 10:42:19.910  5766  5766 I Adreno  : Remote Branch                    : NONE
11-24 10:42:19.910  5766  5766 I Adreno  : Reconstruct Branch               : NOTHING
,11-24 10:42:19.957   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@ff3edca:true
,11-24 10:42:19.985   403   403 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[36163]" dev="sockfs" ino=36163 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 10:42:19.985   403   403 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[36163]" dev="sockfs" ino=36163 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 10:42:19.997  5766  5766 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-24 10:42:20.005  5766  5766 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-24 10:42:20.010  5766  5766 D PluginManager: init()
,11-24 10:42:20.012  5766  5766 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-24 10:42:20.028  5766  5766 D CordovaActivity: Started the activity.
11-24 10:42:20.028  5766  5766 D CordovaActivity: Resumed the activity.
,11-24 10:42:20.028   948   948 W Binder_3: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[35050]" dev="sockfs" ino=35050 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 10:42:20.031  5766  5804 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-24 10:42:20.028   948   948 W Binder_3: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[35050]" dev="sockfs" ino=35050 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 10:42:20.031   935   935 W Binder_1: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[31880]" dev="sockfs" ino=31880 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 10:42:20.035  5766  5766 D CordovaActivity: Paused the activity.
11-24 10:42:20.031   935   935 W Binder_1: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[31880]" dev="sockfs" ino=31880 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 10:42:20.037  5766  5791 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-24 10:42:20.057  5766  5804 I OpenGLRenderer: Initialized EGL, version 1.4
,11-24 10:42:20.073  5766  5766 D CordovaActivity: Stopped the activity.
,11-24 10:42:20.136   925   943 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +533ms (total +903ms)
,11-24 10:42:20.157  5766  5766 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-24 10:42:20.181  5766  5766 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5766
,11-24 10:42:20.309  5766  5766 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-24 10:42:20.421  5766  5806 D jxcore_app_log: JniHelper::setJavaVM(0xf523c000), pthread_self() = -581437136
,11-24 10:42:20.424  5766  5806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-24 10:42:20.424  5766  5806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-24 10:42:20.424  5766  5806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-24 10:42:20.424  5766  5806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-24 10:42:20.424  5766  5806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
11-24 10:42:20.424  5766  5806 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@525cf23 added. We now have 1 listener(s)
,11-24 10:42:20.427  5766  5806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
11-24 10:42:20.428  5766  5806 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-24 10:42:20.428  5766  5806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-24 10:42:20.428  5766  5806 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 10:42:20.430  5766  5806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-24 10:42:20.430  5766  5806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-24 10:42:20.430  5766  5806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-24 10:42:20.430  5766  5806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
11-24 10:42:20.430  5766  5806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-24 10:42:20.430  5766  5806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-24 10:42:20.430  5766  5806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-24 10:42:20.430  5766  5806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-24 10:42:20.430  5766  5806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-24 10:42:20.430  5766  5806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-24 10:42:20.430  5766  5806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-24 10:42:20.430  5766  5806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-24 10:42:20.430  5766  5806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-24 10:42:20.430  5766  5806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-24 10:42:20.430  5766  5806 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2f44f9e added. We now have 1 listener(s)
11-24 10:42:20.430  5766  5806 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 10:42:20.434   925  3038 D WifiService: New client listening to asynchronous messages
,11-24 10:42:20.435  5766  5806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 10:42:20.435  5766  5806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-24 10:42:20.436  5766  5806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-24 10:42:20.436  5766  5806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-24 10:42:20.436  5766  5806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-24 10:42:20.436  5766  5806 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-24 10:42:20.436  5766  5806 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-24 10:42:20.437  5766  5806 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-24 10:42:20.487  5766  5766 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-24 10:42:20.488  5766  5766 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
11-24 10:42:20.489  5766  5766 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-24 10:42:20.954  5766  5775 I art     : Background partial concurrent mark sweep GC freed 55188(6MB) AllocSpace objects, 3(2MB) LOS objects, 37% free, 26MB/42MB, paused 1.755ms total 112.557ms
,11-24 10:42:21.087  5766  5814 W jxcore-log: Initializing JXcore engine
,11-24 10:42:21.087  5766  5814 W jxcore-log: JXcore engine is ready
,11-24 10:42:21.108  5814  5814 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12530 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-24 10:42:21.108  5814  5814 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[13398]" dev="sockfs" ino=13398 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-24 10:42:21.108  5814  5814 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-24 10:42:21.108  5814  5814 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[35027]" dev="sockfs" ino=35027 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-24 10:42:21.118  5766  5814 W jxcore-log: Starting JXcore engine
,11-24 10:42:21.167  5766  5814 W jxcore-log: Platform android
11-24 10:42:21.167  5766  5814 W jxcore-log: 
,11-24 10:42:21.167  5766  5814 W jxcore-log: Process ARCH arm
11-24 10:42:21.167  5766  5814 W jxcore-log: 
,11-24 10:42:21.353  5766  5814 I jxcore-log: JXcore Cordova bridge is ready!
11-24 10:42:21.353  5766  5814 I jxcore-log: 
,11-24 10:42:21.354  5766  5814 W jxcore-log: JXcore engine is started
,11-24 10:42:21.360  5766  5806 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-24 10:42:21.367  5766  5766 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,11-24 10:42:21.368  5766  5766 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-24 10:42:23.602   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:42:23.870   925  5499 D NetlinkSocketObserver: NeighborEvent{elapsedMs=164343, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 10:42:24.603   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:42:25.604   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:42:26.605   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:42:27.606   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:42:28.607   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 10:42:31.156  5766  5814 I jxcore-log: 2016-11-24 15:42:31 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-24 10:42:31.156  5766  5814 I jxcore-log: 
,11-24 10:42:31.157  5766  5814 I jxcore-log: 2016-11-24 15:42:31 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-24 10:42:31.157  5766  5814 I jxcore-log: 
,11-24 10:42:31.162  5766  5814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-24 10:42:31.163  5766  5814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 10:42:31.163  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:42:31.163  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:42:31.163  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 10:42:31.163  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 10:42:31.163  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 10:42:31.163  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 10:42:31.163  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 10:42:31.163  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 10:42:31.164  5766  5814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 10:42:31.166  5766  5814 I jxcore-log: 2016-11-24 15:42:31 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-24 10:42:31.166  5766  5814 I jxcore-log: 
,11-24 10:42:31.167  5766  5814 I jxcore-log: 2016-11-24 15:42:31 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-24 10:42:31.167  5766  5814 I jxcore-log: 
,11-24 10:42:31.416  5766  5814 I jxcore-log: 2016-11-24 15:42:31 - DEBUG UnitTest_app: 'Running unit tests'
11-24 10:42:31.416  5766  5814 I jxcore-log: 
,11-24 10:42:31.416  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 10:42:31.416  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@84fd8da added. We now have 2 listener(s)
11-24 10:42:31.417  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 10:42:31.417  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 10:42:31.417  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 10:42:31.417  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 10:42:31.417  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@adf10b added. We now have 2 listener(s)
11-24 10:42:31.418  5766  5814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 10:42:31.418  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 10:42:31.419  5766  5814 D executeNativeTests: Running unit tests
,11-24 10:42:31.463  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 10:42:31.463  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24d5f18 added. We now have 3 listener(s)
11-24 10:42:31.464  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-24 10:42:31.464  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 10:42:31.464  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 10:42:31.464  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 10:42:31.464  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 added. We now have 3 listener(s)
11-24 10:42:31.464  5766  5814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 10:42:31.465  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 10:42:31.467  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 10:42:31.467  5766  5814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 10:42:31.468  5766  5814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 10:42:31.468  5766  5814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-24 10:42:31.468  5766  5814 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-24 10:42:31.469  5766  5814 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-24 10:42:31.469  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 10:42:31.469  5766  5814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-24 10:42:31.469  5766  5814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 10:42:31.469  5766  5814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 10:42:31.469  5766  5814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:42:31.469  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:42:31.469  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:42:31.469  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 10:42:31.470  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:42:31.470  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 10:42:31.470  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24d5f18 removed from the list
11-24 10:42:31.470  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:31.470  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 removed from the list
11-24 10:42:31.470  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:42:31.470  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:31.470  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:31.471  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:31.471  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:31.471  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:31.471  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:42:31.471  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:42:31.471  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:31.471  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:31.472  5766  5814 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-24 10:42:31.473  5766  5814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:42:31.473  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:42:31.473  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 10:42:31.473  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:42:31.473  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:42:31.473  5766  5814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24d5f18 not in the list
11-24 10:42:31.473  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:31.473  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
,11-24 10:42:31.473  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:42:31.473  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:31.473  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:31.474  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:31.474  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:31.474  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:31.474  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:42:31.474  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:42:31.474  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 10:42:31.474  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:31.477  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-24 10:42:31.477  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-24 10:42:31.477  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-24 10:42:31.477  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-24 10:42:31.477  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-24 10:42:31.477  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-24 10:42:31.477  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-24 10:42:31.477  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-24 10:42:31.477  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-24 10:42:31.477  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-24 10:42:31.477  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-24 10:42:31.477  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-24 10:42:31.477  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-24 10:42:31.477  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-24 10:42:31.477  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-24 10:42:31.477  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-24 10:42:31.478  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-24 10:42:31.478  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-24 10:42:31.478  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-24 10:42:31.478  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-24 10:42:31.478  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-24 10:42:31.478  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-24 10:42:31.478  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,11-24 10:42:31.478  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-24 10:42:31.478  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-24 10:42:31.478  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-24 10:42:31.478  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-24 10:42:31.478  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-24 10:42:31.478  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,11-24 10:42:31.478  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-24 10:42:31.478  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-24 10:42:31.478  5766  5814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:42:31.478  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:42:31.478  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:42:31.478  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:42:31.478  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 10:42:31.478  5766  5814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24d5f18 not in the list
11-24 10:42:31.478  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:31.478  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:31.478  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:42:31.479  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:31.479  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:31.479  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:31.479  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:31.479  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:31.479  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:42:31.480  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:42:31.480  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:31.480  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:31.480  5766  5814 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-24 10:42:31.481  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 10:42:31.481  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-24 10:42:31.490  5766  5814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 10:42:31.490  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:42:31.490  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:42:31.490  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 10:42:31.490  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 10:42:31.490  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 10:42:31.490  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 10:42:31.490  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 10:42:31.490  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 10:42:31.491  5766  5814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 10:42:31.491  5766  5814 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 10:42:31.491  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 10:42:31.491  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 10:42:31.491  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 10:42:31.491  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 10:42:31.492  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 10:42:31.494  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 10:42:31.494  5766  5814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 10:42:31.494  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 10:42:31.497  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:31.497  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-24 10:42:31.498  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 10:42:31.498  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 10:42:31.498  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 10:42:31.499  5766  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:42:31.501  5766  5814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-24 10:42:31.502  5766  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:42:31.503  5766  5814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-24 10:42:31.504  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:31.504  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-24 10:42:31.504  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 10:42:31.504  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 10:42:31.504  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 10:42:31.504  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:31.504  5766  5814 D BluetoothAdapter: STATE_ON
,11-24 10:42:31.507  4687  4899 D BtGatt.GattService: registerClient() - UUID=acb19574-a304-4122-a70c-82de17ce91eb
,11-24 10:42:31.510  4687  4755 D BtGatt.GattService: onClientRegistered() - UUID=acb19574-a304-4122-a70c-82de17ce91eb, clientIf=5
,11-24 10:42:31.511  5766  5777 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 10:42:31.515  4687  4700 D BtGatt.GattService: start scan with filters
,11-24 10:42:31.519  4687  4769 D BtGatt.ScanManager: handling starting scan
,11-24 10:42:31.519  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 10:42:31.519  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:31.519  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 10:42:31.520  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:31.520  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 10:42:31.520  5766  5766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 10:42:31.520  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 10:42:31.520  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-24 10:42:31.520  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 10:42:31.520  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 10:42:31.520  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 10:42:31.520  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:31.520  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 10:42:31.521  4687  4769 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f57f4
11-24 10:42:31.521  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 10:42:31.521  5766  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 10:42:31.521  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:31.521  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:31.521  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:31.521  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 10:42:31.522  5766  5814 I io.jxcore.node.ConnectionHelper: start: OK
11-24 10:42:31.524  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 10:42:31.525  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 10:42:31.525  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 10:42:31.525  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-24 10:42:31.525  5766  5766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-24 10:42:31.528  4687  4755 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 10:42:31.528  4687  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 10:42:31.529  4687  4769 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-24 10:42:31.536  4687  4755 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 10:42:31.536  4687  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 10:42:31.537  4687  4769 D BtGatt.ScanManager: Starting BLE batch scan
11-24 10:42:31.537  4687  4769 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 10:42:31.547  4687  4755 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 10:42:31.547  4687  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 10:42:31.553  4687  4755 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 10:42:31.553  4687  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 10:42:32.027  5766  5766 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-24 10:42:32.027  5766  5766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 10:42:32.028  5766  5766 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 10:42:36.527  5766  5814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 10:42:36.527  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 10:42:36.527  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 10:42:36.527  5766  5814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 10:42:36.527  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 10:42:36.527  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 10:42:36.528  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 10:42:36.528  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 10:42:36.528  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:36.528  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 10:42:36.528  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 10:42:36.529  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:36.529  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:36.529  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:36.529  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 10:42:36.529  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:36.530  5766  5814 D BluetoothAdapter: STATE_ON
11-24 10:42:36.531  4687  4699 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 10:42:36.531  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 10:42:36.532  5766  5814 D BluetoothAdapter: STATE_ON
,11-24 10:42:36.533  4687  4769 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 10:42:36.533  4687  4700 D BtGatt.GattService: stopScan() - queue size =1
11-24 10:42:36.534  4687  4699 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 10:42:36.534  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-24 10:42:36.534  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:36.534  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 10:42:36.534  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:36.535  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:36.535  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:36.535  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:36.535  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 10:42:36.536  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:36.536  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:36.536  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:36.536  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 10:42:36.536  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-24 10:42:36.537  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 10:42:36.537  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:36.539  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:36.539  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 10:42:36.539  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:36.539  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:36.539  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:42:36.539  5766  5814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-24 10:42:36.539  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 10:42:36.539  5766  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 10:42:36.539  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 10:42:36.540  5766  5814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24d5f18 not in the list
11-24 10:42:36.540  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:36.540  5766  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 10:42:36.540  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
,11-24 10:42:36.540  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:42:36.540  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 10:42:36.540  5766  5766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 10:42:36.540  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 10:42:36.540  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 10:42:36.541  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-24 10:42:36.541  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 10:42:36.541  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 10:42:36.541  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 10:42:36.541  5766  5766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 10:42:36.543  4687  4687 D BtGatt.ScanManager: awakened up at time 177017
,11-24 10:42:36.542  5766  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 10:42:36.543  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 10:42:36.546  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 10:42:36.546  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 10:42:36.547  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-24 10:42:36.568  4687  4755 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-24 10:42:36.568  4687  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:42:36.568  4687  4755 D BtGatt.GattService: current time is 177043142901
,11-24 10:42:36.569  4687  4755 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -72, 52, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -73, 65, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -71, 66, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -67, 66, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -72, 66, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -70, 64, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-24 10:42:36.572  4687  4755 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-24 10:42:36.573  4687  4755 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-24 10:42:36.573  4687  4755 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-24 10:42:36.574  4687  4755 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-24 10:42:36.574  4687  4755 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-24 10:42:36.574  4687  4755 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-24 10:42:36.583  4687  4755 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-24 10:42:36.583  4687  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 10:42:36.584  4687  4769 D BtGatt.ScanManager: stopping BLe Batch
,11-24 10:42:36.593  4687  4755 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 10:42:36.593  4687  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:42:36.593  4687  4769 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 10:42:36.601  4687  4755 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 10:42:36.601  4687  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 10:42:37.043  5766  5766 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 10:42:40.123   925  3037 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 10:42:41.542  5766  5814 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-24 10:42:41.548  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 10:42:41.548  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-24 10:42:41.562  5766  5814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 10:42:41.562  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:42:41.562  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:42:41.562  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 10:42:41.562  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 10:42:41.562  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 10:42:41.562  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 10:42:41.562  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 10:42:41.562  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 10:42:41.567  5766  5814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 10:42:41.567  5766  5814 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 10:42:41.567  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-24 10:42:41.567  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 10:42:41.568  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 10:42:41.568  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 10:42:41.568  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 10:42:41.572  5766  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:42:41.575  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-24 10:42:41.575  5766  5814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 10:42:41.575  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-24 10:42:41.578  5766  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:42:41.581  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:41.581  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-24 10:42:41.584  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-24 10:42:41.584  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 10:42:41.584  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 10:42:41.590  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:41.590  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 10:42:41.591  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 10:42:41.591  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 10:42:41.591  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 10:42:41.591  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.592  5766  5814 D BluetoothAdapter: STATE_ON
,11-24 10:42:41.594  4687  5441 D BtGatt.GattService: registerClient() - UUID=672c2427-1d51-4906-b866-234d7343e6c5
11-24 10:42:41.595  4687  4755 D BtGatt.GattService: onClientRegistered() - UUID=672c2427-1d51-4906-b866-234d7343e6c5, clientIf=5
11-24 10:42:41.596  5766  5776 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 10:42:41.596  4687  4907 D BtGatt.GattService: start scan with filters
,11-24 10:42:41.600  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 10:42:41.600  4687  4769 D BtGatt.ScanManager: handling starting scan
11-24 10:42:41.600  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:41.600  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 10:42:41.600  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:41.601  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-24 10:42:41.601  5766  5766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 10:42:41.601  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 10:42:41.601  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 10:42:41.601  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 10:42:41.601  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 10:42:41.601  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 10:42:41.601  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 10:42:41.601  5766  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-24 10:42:41.603  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 10:42:41.603  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.606  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.607  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 10:42:41.607  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.607  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.607  5766  5814 I io.jxcore.node.ConnectionHelper: start: OK
11-24 10:42:41.607  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 10:42:41.610  4687  4755 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-24 10:42:41.610  4687  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:42:41.610  4687  4769 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-24 10:42:41.611  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-24 10:42:41.611  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 10:42:41.611  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 10:42:41.611  5766  5766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 10:42:41.613  5766  5814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:42:41.613  5766  5814 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-24 10:42:41.613  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 10:42:41.613  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 10:42:41.613  5766  5814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 10:42:41.613  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 10:42:41.613  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:42:41.613  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 10:42:41.613  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 10:42:41.614  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.614  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 10:42:41.614  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 10:42:41.614  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.614  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.614  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.614  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-24 10:42:41.614  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.615  5766  5814 D BluetoothAdapter: STATE_ON
11-24 10:42:41.616  4687  4907 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 10:42:41.616  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 10:42:41.617  5766  5814 D BluetoothAdapter: STATE_ON
11-24 10:42:41.617  4687  5441 D BtGatt.GattService: stopScan() - queue size =1
11-24 10:42:41.618  4687  4755 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 10:42:41.618  4687  4899 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 10:42:41.618  4687  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:42:41.618  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 10:42:41.618  4687  4769 D BtGatt.ScanManager: Starting BLE batch scan
11-24 10:42:41.618  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.618  4687  4769 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 10:42:41.618  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 10:42:41.619  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.619  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:41.619  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:41.619  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.619  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 10:42:41.619  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.619  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.619  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.620  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 10:42:41.620  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 10:42:41.620  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 10:42:41.620  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.622  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.622  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 10:42:41.622  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.622  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.622  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:42:41.622  5766  5814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 10:42:41.622  5766  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 10:42:41.623  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 10:42:41.623  5766  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 10:42:41.623  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:42:41.623  5766  5766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 10:42:41.623  5766  5814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24d5f18 not in the list
11-24 10:42:41.623  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 10:42:41.623  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:41.623  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 10:42:41.623  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:41.623  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 10:42:41.623  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:42:41.623  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 10:42:41.623  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 10:42:41.623  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 10:42:41.623  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 10:42:41.623  5766  5766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 10:42:41.623  5766  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 10:42:41.624  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 10:42:41.625  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 10:42:41.625  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 10:42:41.626  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 10:42:41.626  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.626  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.629  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.629  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.629  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.629  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:42:41.629  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:42:41.629  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:41.629  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:41.630  5766  5814 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-24 10:42:41.631  4687  4755 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 10:42:41.631  4687  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:42:41.632  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 10:42:41.632  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-24 10:42:41.638  4687  4755 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 10:42:41.638  4687  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:42:41.638  5766  5814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 10:42:41.638  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:42:41.638  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:42:41.638  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 10:42:41.638  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 10:42:41.638  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 10:42:41.638  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 10:42:41.638  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 10:42:41.638  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 10:42:41.639  4687  4769 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 10:42:41.642  5766  5814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 10:42:41.642  5766  5814 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 10:42:41.643  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 10:42:41.643  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 10:42:41.643  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 10:42:41.643  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 10:42:41.643  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 10:42:41.646  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 10:42:41.646  5766  5814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 10:42:41.646  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 10:42:41.646  5766  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:42:41.649  4687  4755 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=1
,11-24 10:42:41.649  4687  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:42:41.650  5766  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 10:42:41.650  4687  4755 D BtGatt.GattService: current time is 182124461311
11-24 10:42:41.650  4687  4755 D BtGatt.GattService: Batch record : [71, -122, -77, 84, 69, -12, 1, -128, -83, 0, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-24 10:42:41.650  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.650  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 10:42:41.650  4687  4755 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-24 10:42:41.650  4687  4755 E BtGatt.ContextMap: Context not found for ID 5
11-24 10:42:41.650  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 10:42:41.651  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-24 10:42:41.651  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 10:42:41.654  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.654  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 10:42:41.654  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 10:42:41.654  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-24 10:42:41.654  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 10:42:41.655  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.655  5766  5814 D BluetoothAdapter: STATE_ON
11-24 10:42:41.656  4687  4755 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 10:42:41.657  4687  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:42:41.657  4687  4769 D BtGatt.ScanManager: stopping BLe Batch
,11-24 10:42:41.657  4687  4700 D BtGatt.GattService: registerClient() - UUID=aee819e7-3c66-400b-a3a3-40f922ca3806
,11-24 10:42:41.658  4687  4755 D BtGatt.GattService: onClientRegistered() - UUID=aee819e7-3c66-400b-a3a3-40f922ca3806, clientIf=5
11-24 10:42:41.658  5766  5776 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 10:42:41.659  4687  4899 D BtGatt.GattService: start scan with filters
,11-24 10:42:41.662  4687  4755 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 10:42:41.662  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 10:42:41.662  4687  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:42:41.662  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.662  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 10:42:41.662  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.662  4687  4769 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 10:42:41.662  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 10:42:41.662  5766  5766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 10:42:41.662  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 10:42:41.662  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 10:42:41.662  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 10:42:41.662  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 10:42:41.662  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 10:42:41.662  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 10:42:41.663  5766  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-24 10:42:41.663  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-24 10:42:41.663  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.667  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.667  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 10:42:41.667  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.667  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:41.667  5766  5814 I io.jxcore.node.ConnectionHelper: start: OK
11-24 10:42:41.667  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 10:42:41.667  4687  4755 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 10:42:41.667  4687  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:42:41.669  4687  4769 D BtGatt.ScanManager: handling starting scan
11-24 10:42:41.669  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-24 10:42:41.670  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 10:42:41.670  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 10:42:41.670  5766  5766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-24 10:42:41.675  4687  4755 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 10:42:41.675  4687  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:42:41.675  4687  4769 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-24 10:42:41.680  4687  4755 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-24 10:42:41.680  4687  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:42:41.680  4687  4769 D BtGatt.ScanManager: Starting BLE batch scan
11-24 10:42:41.680  4687  4769 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 10:42:41.688  4687  4755 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 10:42:41.688  4687  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 10:42:41.693  4687  4755 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 10:42:41.693  4687  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 10:42:42.171  5766  5766 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-24 10:42:42.171  5766  5766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 10:42:42.172  5766  5766 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 10:42:42.254   925  3042 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-24 10:42:42.258   925  3042 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,11-24 10:42:45.283   925  3042 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 10:42:45.291   925  3042 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,11-24 10:42:46.667  5766  5814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 10:42:46.668  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-24 10:42:46.668  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 10:42:46.668  5766  5814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 10:42:46.668  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 10:42:46.668  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 10:42:46.668  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 10:42:46.669  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 10:42:46.669  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:46.669  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 10:42:46.669  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 10:42:46.670  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:46.670  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:46.670  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:46.670  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-24 10:42:46.670  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:46.674  5766  5814 D BluetoothAdapter: STATE_ON
,11-24 10:42:46.675  4687  4899 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 10:42:46.676  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-24 10:42:46.677  5766  5814 D BluetoothAdapter: STATE_ON
11-24 10:42:46.677  4687  4769 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 10:42:46.679  4687  4699 D BtGatt.GattService: stopScan() - queue size =1
11-24 10:42:46.680  4687  5441 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 10:42:46.681  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 10:42:46.681  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:46.682  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-24 10:42:46.682  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:46.682  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:46.682  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:46.683  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:46.683  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 10:42:46.683  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:46.683  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:46.683  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:46.683  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 10:42:46.684  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 10:42:46.684  4687  4687 D BtGatt.ScanManager: awakened up at time 187159
11-24 10:42:46.685  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-24 10:42:46.685  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:46.688  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:46.688  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 10:42:46.689  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:46.689  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:46.689  5766  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 10:42:46.689  5766  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 10:42:46.689  5766  5766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 10:42:46.690  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 10:42:46.690  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-24 10:42:46.690  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 10:42:46.690  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 10:42:46.690  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 10:42:46.690  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 10:42:46.690  5766  5766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 10:42:46.691  5766  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
,11-24 10:42:46.691  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 10:42:46.693  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 10:42:46.693  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 10:42:46.693  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-24 10:42:46.708  4687  4755 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
,11-24 10:42:46.708  4687  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:42:46.708  4687  4755 D BtGatt.GattService: current time is 187183154049
11-24 10:42:46.709  4687  4755 D BtGatt.GattService: Batch record : [81, 34, 97, 112, -14, -5, 1, -128, -70, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -74, 89, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 37, -47, 14, -113, 116, -46, 1, -128, -75, 89, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 35, 97, 126, -92, 22, -56, 1, -128, -71, 88, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -72, 56, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -46, -4, -117, 6, 105, -37, 1, -128, -72, 67, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-24 10:42:46.709  4687  4755 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-24 10:42:46.709  4687  4755 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-24 10:42:46.710  4687  4755 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-24 10:42:46.710  4687  4755 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-24 10:42:46.710  4687  4755 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-24 10:42:46.710  4687  4755 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
,11-24 10:42:46.718  4687  4755 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-24 10:42:46.719  4687  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:42:46.719  4687  4769 D BtGatt.ScanManager: stopping BLe Batch
,11-24 10:42:46.727  4687  4755 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 10:42:46.727  4687  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:42:46.727  4687  4769 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 10:42:46.734  4687  4755 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 10:42:46.734  4687  4755 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 10:42:47.191  5766  5766 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 10:42:47.191  5766  5766 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 10:42:47.191  5766  5766 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 10:42:48.590   925  5499 D NetlinkSocketObserver: NeighborEvent{elapsedMs=189064, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-24 10:42:48.608   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:42:49.610   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:42:50.611   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:42:51.612   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:42:51.690  5766  5814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 10:42:51.691  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 10:42:51.691  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 10:42:51.691  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:42:51.691  5766  5814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-24 10:42:51.692  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 10:42:51.692  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:42:51.692  5766  5814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24d5f18 not in the list
11-24 10:42:51.692  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:51.693  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
,11-24 10:42:51.693  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:42:51.693  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 10:42:51.695  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.695  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:51.698  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.698  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.700  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.700  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 10:42:51.700  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 10:42:51.700  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:51.700  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:51.702  5766  5814 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-24 10:42:51.704  5766  5814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:42:51.704  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:42:51.704  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 10:42:51.705  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:42:51.705  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:42:51.705  5766  5814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24d5f18 not in the list
11-24 10:42:51.705  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:51.705  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:51.706  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:42:51.706  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.706  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:51.708  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:51.709  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.709  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.709  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:42:51.709  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:42:51.709  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:51.709  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:51.711  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-24 10:42:51.711  5766  5814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:42:51.711  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:42:51.711  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 10:42:51.711  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:42:51.711  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:42:51.711  5766  5814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24d5f18 not in the list
11-24 10:42:51.711  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:51.711  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:51.712  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:42:51.712  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.712  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:51.713  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.713  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.713  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.713  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:42:51.713  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:42:51.713  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:51.714  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:51.714  5766  5814 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-24 10:42:51.715  5766  5814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 10:42:51.715  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:42:51.715  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:42:51.715  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:42:51.715  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:42:51.715  5766  5814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24d5f18 not in the list
11-24 10:42:51.715  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:51.715  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:51.715  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:42:51.715  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.716  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:51.717  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.717  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.717  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:51.717  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:42:51.717  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:42:51.717  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 10:42:51.717  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:51.718  5766  5814 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-24 10:42:51.718  5766  5814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:42:51.718  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:42:51.718  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:42:51.719  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:42:51.719  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 10:42:51.719  5766  5814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24d5f18 not in the list
11-24 10:42:51.719  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:51.719  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:51.719  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:42:51.719  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.719  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:51.720  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.721  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.721  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.721  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:42:51.721  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:42:51.721  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:51.721  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
,11-24 10:42:51.722  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 10:42:51.722  5766  5814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 10:42:51.722  5766  5814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 10:42:51.722  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 10:42:51.722  5766  5814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 10:42:51.722  5766  5814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 10:42:51.723  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 10:42:51.723  5766  5814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 10:42:51.723  5766  5814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 10:42:51.723  5766  5814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:42:51.723  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 10:42:51.723  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:42:51.723  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:42:51.723  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:42:51.723  5766  5814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24d5f18 not in the list
11-24 10:42:51.723  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:51.723  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:51.723  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:42:51.724  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.724  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.726  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.726  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.726  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.726  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:42:51.726  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:42:51.726  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:51.726  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:51.727  5766  5814 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 10:42:51.727  5766  5814 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-24 10:42:51.727  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-24 10:42:51.731  5766  5814 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-24 10:42:51.731  5766  5814 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-24 10:42:51.731  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-24 10:42:51.731  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-24 10:42:51.731  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-24 10:42:51.731  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-24 10:42:51.731  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,11-24 10:42:51.731  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-24 10:42:51.731  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-24 10:42:51.731  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-24 10:42:51.731  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-24 10:42:51.732  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-24 10:42:51.732  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-24 10:42:51.732  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-24 10:42:51.732  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-24 10:42:51.732  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-24 10:42:51.732  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-24 10:42:51.732  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-24 10:42:51.732  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-24 10:42:51.732  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-24 10:42:51.732  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-24 10:42:51.732  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,11-24 10:42:51.732  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-24 10:42:51.733  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-24 10:42:51.733  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-24 10:42:51.733  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-24 10:42:51.733  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-24 10:42:51.733  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-24 10:42:51.733  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,11-24 10:42:51.733  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-24 10:42:51.733  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-24 10:42:51.733  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-24 10:42:51.734  5766  5814 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-24 10:42:51.734  5766  5814 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 10:42:51.734  5766  5814 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-24 10:42:51.734  5766  5814 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 10:42:51.734  5766  5814 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 10:42:51.734  5766  5814 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-24 10:42:51.734  5766  5814 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 10:42:51.734  5766  5814 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 10:42:51.734  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-24 10:42:51.739  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-24 10:42:51.740  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-24 10:42:51.740  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-24 10:42:51.742  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-24 10:42:51.742  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-24 10:42:51.742  5766  5814 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-24 10:42:51.742  5766  5816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
11-24 10:42:51.743  5766  5816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-24 10:42:51.743  5766  5814 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 10:42:51.743  5766  5816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-24 10:42:51.744  5766  5814 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-24 10:42:51.744  5766  5816 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-24 10:42:51.745  5766  5814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:42:51.745  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:42:51.745  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:42:51.745  4899  4899 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[35086]" dev="sockfs" ino=35086 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 10:42:51.745  4899  4899 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[35086]" dev="sockfs" ino=35086 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 10:42:51.745  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:42:51.745  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:42:51.746  5766  5816 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-24 10:42:51.746  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-24 10:42:51.746  5766  5816 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 10:42:51.747  5766  5814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24d5f18 not in the list
11-24 10:42:51.747  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:51.747  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:51.747  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:42:51.747  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.747  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.747  5766  5817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
11-24 10:42:51.747  5766  5817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-24 10:42:51.747  5766  5817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
11-24 10:42:51.747  5766  5817 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
11-24 10:42:51.748  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.748  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.748  5766  5816 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
11-24 10:42:51.748  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.748  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:42:51.748  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:42:51.748  5766  5816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-24 10:42:51.748  5766  5816 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
11-24 10:42:51.749  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:51.749  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:51.750  5766  5814 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-24 10:42:51.751  5766  5814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:42:51.751  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:42:51.751  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:42:51.751  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:42:51.751  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:42:51.751  5766  5814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24d5f18 not in the list
11-24 10:42:51.752  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:51.752  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:51.752  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:42:51.752  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.752  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.753  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.753  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.753  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.753  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:42:51.753  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:42:51.753  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:51.753  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:51.754  5766  5814 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-24 10:42:51.754  5766  5814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:42:51.754  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:42:51.754  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:42:51.755  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:42:51.755  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:42:51.755  5766  5814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24d5f18 not in the list
11-24 10:42:51.755  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:51.755  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:51.755  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:42:51.755  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.755  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.756  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.756  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.756  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.756  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:42:51.756  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:42:51.756  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:51.756  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:51.757  5766  5814 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-24 10:42:51.757  5766  5814 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-24 10:42:51.757  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 10:42:51.757  5766  5814 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-24 10:42:51.758  5766  5814 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-24 10:42:51.758  5766  5814 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-24 10:42:51.758  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 10:42:51.758  5766  5814 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-24 10:42:51.758  5766  5814 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-24 10:42:51.758  5766  5814 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-24 10:42:51.758  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 10:42:51.758  5766  5814 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-24 10:42:51.758  5766  5814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:42:51.758  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:42:51.758  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:42:51.758  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:42:51.758  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:42:51.758  5766  5814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24d5f18 not in the list
11-24 10:42:51.758  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:51.758  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:51.759  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:42:51.759  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.759  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.760  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.760  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.760  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:51.760  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:42:51.760  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:42:51.760  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:51.760  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:51.761  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:42:51.761  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:42:51.761  5766  5814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24d5f18 not in the list
11-24 10:42:51.761  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:51.761  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:51.761  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 10:42:52.614   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:42:53.614   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 10:42:56.762  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:56.762  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
,11-24 10:42:56.762  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:42:56.763  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:42:56.763  5766  5814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24d5f18 not in the list
11-24 10:42:56.763  5766  5814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:42:56.763  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 10:42:56.763  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:42:56.764  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:42:56.764  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:42:56.765  5766  5814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24d5f18 not in the list
,11-24 10:42:56.765  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:56.765  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:56.765  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:42:56.765  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:56.766  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:56.769  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:56.769  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:56.769  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:56.769  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:42:56.770  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:42:56.770  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:56.770  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
,11-24 10:42:56.774  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-24 10:42:56.776  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-24 10:42:56.776  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-24 10:42:56.781  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-24 10:42:56.782  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-24 10:42:56.782  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-24 10:42:56.782  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-24 10:42:56.782  5766  5818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-24 10:42:56.783  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-24 10:42:56.783  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-24 10:42:56.783  5766  5766 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-24 10:42:56.783  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 10:42:56.783  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-24 10:42:56.783  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-24 10:42:56.783  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-24 10:42:56.784  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 10:42:56.784  5766  5818 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 10:42:56.784  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-24 10:42:56.784  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-24 10:42:56.784  5766  5814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24d5f18 not in the list
11-24 10:42:56.784  5766  5766 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-24 10:42:56.784  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:56.784  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-24 10:42:56.785  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:56.785  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 10:42:56.785  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-24 10:42:56.785  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:56.785  4699  4699 W Binder_1: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[29467]" dev="sockfs" ino=29467 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-24 10:42:56.785  4699  4699 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[29467]" dev="sockfs" ino=29467 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 10:42:56.786  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:56.786  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 10:42:56.786  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:56.786  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:56.787  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:56.787  5766  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 10:42:56.787  5766  5814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:42:56.787  5766  5818 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-24 10:42:56.787  5766  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 10:42:56.787  5766  5818 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-24 10:42:56.787  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:42:56.787  5766  5766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 10:42:56.787  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:42:56.787  5766  5818 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-24 10:42:56.787  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:42:56.787  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-24 10:42:56.787  5766  5814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24d5f18 not in the list
11-24 10:42:56.787  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:56.787  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:56.787  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:42:56.787  5766  5766 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-24 10:42:56.787  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:56.787  5766  5766 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:42:56.787  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:56.789  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:56.789  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:56.789  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:56.789  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:42:56.789  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:42:56.789  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:56.789  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryMana,gerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:56.791  5766  5814 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-24 10:42:56.791  5766  5814 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-24 10:42:56.791  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 10:42:56.791  5766  5814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 10:42:56.791  5766  5814 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 10:42:56.792  5766  5814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:42:56.792  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:42:56.792  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:42:56.793  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:42:56.793  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:42:56.793  5766  5814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24d5f18 not in the list
11-24 10:42:56.793  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:56.793  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:56.793  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:42:56.793  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:56.793  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:56.795  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:56.795  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:56.795  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:56.795  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:42:56.795  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:42:56.795  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:56.795  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
,11-24 10:42:56.800  5766  5814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:42:56.800  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:42:56.800  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:42:56.800  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:42:56.800  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:42:56.800  5766  5814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24d5f18 not in the list
11-24 10:42:56.800  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:56.800  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:56.800  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:42:56.801  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:56.801  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:56.802  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:56.802  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:56.802  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:56.802  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:42:56.802  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:42:56.802  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:56.802  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
,11-24 10:42:56.803  5766  5814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 10:42:56.803  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:42:56.803  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:42:56.803  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:42:56.803  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:42:56.803  5766  5814 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24d5f18 not in the list
11-24 10:42:56.803  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 10:42:56.803  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:56.803  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:42:56.803  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:56.803  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:56.804  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:56.805  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:42:56.805  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:42:56.805  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:42:56.805  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:42:56.805  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:42:56.805  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@27afd71 not in the list
11-24 10:42:56.806  5766  5814 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-24 10:42:56.806  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 10:42:56.806  5766  5814 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-24 10:42:56.806  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 10:42:56.806  5766  5814 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-24 10:42:56.806  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-24 10:42:56.808  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-24 10:42:56.808  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-24 10:42:56.808  5766  5814 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-24 10:42:56.808  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-24 10:42:56.808  5766  5814 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-24 10:42:56.808  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-24 10:42:56.808  5766  5814 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-24 10:42:56.808  5766  5814 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-24 10:42:56.809  5766  5814 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,11-24 10:42:56.809  5766  5814 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-24 10:42:56.809  5766  5814 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-24 10:42:56.809  5766  5814 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-24 10:42:56.809  5766  5814 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-24 10:42:56.809  5766  5814 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-24 10:42:56.810  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 10:42:56.810  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@be37206 added. We now have 3 listener(s)
11-24 10:42:56.810  5766  5814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 10:42:56.813  5766  5814 D BluetoothAdapter: enable(): BT is already enabled..!
11-24 10:42:56.813   925  3849 D WifiService: setWifiEnabled: true pid=5766, uid=10077
,11-24 10:42:56.813   925  3849 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 10:42:56.874  4687  4891 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-24 10:42:56.875  4687  4897 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-24 10:42:57.287  5766  5766 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 10:43:00.125   925  3037 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 10:43:01.819  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 10:43:01.819  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@33990c7 added. We now have 4 listener(s)
,11-24 10:43:01.819  5766  5814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 10:43:01.832  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 10:43:01.832  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@33990c7 removed from the list
,11-24 10:43:01.832  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 10:43:01.834  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 10:43:01.834  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a8976f4 added. We now have 4 listener(s)
11-24 10:43:01.834  5766  5814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 10:43:01.838  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 10:43:01.839  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a8976f4 removed from the list
11-24 10:43:01.839  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:43:01.842  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 10:43:01.843  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37e2e1d added. We now have 4 listener(s)
,11-24 10:43:01.845  5766  5814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 10:43:01.850   925  3500 D WifiService: setWifiEnabled: false pid=5766, uid=10077
11-24 10:43:01.850   925  3500 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 10:43:01.856   925  3037 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-24 10:43:01.856   925  3037 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-24 10:43:01.856   925  3037 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 10:43:01.857   925  3037 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-24 10:43:01.862  4687  4748 D BluetoothAdapterState: Current state: ON, message: 23
11-24 10:43:01.862  4687  4748 D BluetoothAdapterProperties: Setting state to 13
11-24 10:43:01.862  4687  4748 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-24 10:43:01.864  4687  4748 D BluetoothAdapterProperties: onBluetoothDisable()
11-24 10:43:01.865  4687  4748 I BluetoothAdapterState: Entering PendingCommandState
11-24 10:43:01.865  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 10:43:01.866  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-24 10:43:01.866  4687  4755 D BluetoothAdapterProperties: Scan Mode:20
11-24 10:43:01.867  4687  4748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-24 10:43:01.871  4687  4687 D HeadsetService: Received stop request...Stopping profile...
11-24 10:43:01.872   925  5500 D DhcpClient: Clearing IP address
11-24 10:43:01.873   505   922 D CommandListener: Clearing all IP addresses on wlan0
11-24 10:43:01.873   925   925 D BluetoothHeadset: Proxy object disconnected
11-24 10:43:01.875  3846  4228 D BluetoothHeadset: Proxy object disconnected
,11-24 10:43:01.876   925   925 D BluetoothHeadset: Proxy object disconnected
11-24 10:43:01.877   925   925 D BluetoothHeadset: Proxy object disconnected
11-24 10:43:01.877  3205  5765 D BluetoothHeadset: Proxy object disconnected
11-24 10:43:01.878  4687  4687 V BluetoothAdapterState: isTurningOff()=true
11-24 10:43:01.878  4687  4687 V BluetoothAdapterState: isTurningOn()=false
11-24 10:43:01.878  4687  4687 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:01.878  4687  4687 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:43:01.878  5766  5814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 10:43:01.878  5766  5814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 10:43:01.878  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:43:01.878  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:43:01.878  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 10:43:01.878  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 10:43:01.878  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 10:43:01.878  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 10:43:01.878  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 10:43:01.878  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 10:43:01.880  3205  3205 D HeadsetProfile: Bluetooth service disconnected
11-24 10:43:01.881   505   922 D CommandListener: Setting iface cfg
11-24 10:43:01.881  5766  5814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 10:43:01.881  5766  5814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 10:43:01.882  5766  5814 D io.jxcore.node.ConnectivityMonitor: start: OK
,11-24 10:43:01.885  5766  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:43:01.886  3635  5555 V NativeCrypto: Read error: ssl=0x7f99870480: I/O error during system call, Connection timed out
11-24 10:43:01.889  3635  5555 V NativeCrypto: SSL shutdown failed: ssl=0x7f99870480: I/O error during system call, Broken pipe
,11-24 10:43:01.890  5766  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:43:01.891   925  3913 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,11-24 10:43:01.892   925  5498 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
,11-24 10:43:01.895  5766  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:43:01.896   925  5498 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-24 10:43:01.897   925  3042 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
11-24 10:43:01.897   925  3042 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-24 10:43:01.898   925   938 I ActivityManager: Start proc 5823:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-24 10:43:01.899   925  3042 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-24 10:43:01.902   925  3042 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-24 10:43:01.902   925  3042 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-24 10:43:01.905  4687  4687 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-24 10:43:01.905  4687  4687 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-24 10:43:01.905  4687  4755 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-24 10:43:01.906  4687  4891 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 10:43:01.906  4687  4891 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-24 10:43:01.906  4687  4687 D BluetoothMapService: onReceive
11-24 10:43:01.906  4687  4891 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 10:43:01.906  4687  4687 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 10:43:01.906  4687  4687 D BluetoothMapService: STATE_TURNING_OFF
11-24 10:43:01.906  4687  4755 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-24 10:43:01.906   533   533 E Parcel  : Reading a NULL string not supported here.
11-24 10:43:01.907  4687  4687 D A2dpService: Received stop request...Stopping profile...
11-24 10:43:01.907  4687  4902 D A2dpStateMachine: Exit Disconnected: -1
,11-24 10:43:01.909   925   925 D BluetoothA2dp: Proxy object disconnected
11-24 10:43:01.910  4687  4687 D HidService: Received stop request...Stopping profile...
11-24 10:43:01.910  4687  4687 D HidService: Stopping Bluetooth HidService
11-24 10:43:01.911  3205  3205 D BluetoothA2dp: Proxy object disconnected
11-24 10:43:01.912  4687  4687 D HealthService: Received stop request...Stopping profile...
11-24 10:43:01.912   925   925 D RttService: SCAN_AVAILABLE : 1
11-24 10:43:01.913  4687  4687 D BluetoothMapService: MAP Service closeService in
11-24 10:43:01.913  4687  4687 D BluetoothMapMasInstance0: MAP Service shutdown
11-24 10:43:01.913  4687  4687 D ObexServerSockets0: shutdown(block = true)
11-24 10:43:01.913   925  3145 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-24 10:43:01.914  4687  4687 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 10:43:01.914  4687  4926 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
,11-24 10:43:01.914  4687  4687 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 10:43:01.914  4687  4927 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-24 10:43:01.915  4687  4897 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-24 10:43:01.916  4687  4687 I BtOppRfcommListener: stopping Accept Thread
11-24 10:43:01.916  4687  5410 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-24 10:43:01.917  4687  5410 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-24 10:43:01.921   925  3042 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-24 10:43:01.922   925  3037 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-24 10:43:01.923  4687  4687 D PanService: Received stop request...Stopping profile...
11-24 10:43:01.923  3801  3965 W QCNEJ   : |CORE| network lost: 100
11-24 10:43:01.924   925  5501 D DhcpClient: Receive thread stopped
11-24 10:43:01.924  3801  3965 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-24 10:43:01.924  4687  4687 V BluetoothAdapterState: isTurningOff()=true
11-24 10:43:01.924  4687  4687 V BluetoothAdapterState: isTurningOn()=false
11-24 10:43:01.924  4687  4687 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:01.925  4687  4687 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 10:43:01.927  4687  4687 D BluetoothMapService: Received stop request...Stopping profile...
,11-24 10:43:01.927  4687  4687 D BluetoothMapService: stop()
11-24 10:43:01.927  4687  4687 D BluetoothMapAppObserver: deinitObservers()
11-24 10:43:01.927   925  3037 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 10:43:01.927  4687  4687 D BluetoothMapAppObserver: removeReceiver()
11-24 10:43:01.929  4687  4755 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-24 10:43:01.929  4687  4891 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 10:43:01.930  4687  4891 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 10:43:01.930  4687  4891 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 10:43:01.930  4687  4891 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 10:43:01.930  4687  4891 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-24 10:43:01.930  4687  4891 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 10:43:01.930  3205  3205 D BluetoothInputDevice: Proxy object disconnected
11-24 10:43:01.930  3205  3205 D HidProfile: Bluetooth service disconnected
11-24 10:43:01.930  4687  4687 D SapService: Received stop request...Stopping profile...
11-24 10:43:01.931  4687  4687 V SapService: stop()
11-24 10:43:01.931  3205  3205 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 10:43:01.932  4687  4687 V BluetoothAdapterState: isTurningOff()=true
,11-24 10:43:01.932  4687  4687 V BluetoothAdapterState: isTurningOn()=false
11-24 10:43:01.932  4687  4687 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:01.932  4687  4687 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:43:01.932  4687  4687 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-24 10:43:01.932  4687  4755 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-24 10:43:01.933  4687  4687 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-24 10:43:01.933  4687  4687 V BluetoothAdapterState: isTurningOff()=true
11-24 10:43:01.933  4687  4687 V BluetoothAdapterState: isTurningOn()=false
11-24 10:43:01.933  4687  4687 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:01.933  4687  4687 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:43:01.933  4687  4687 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-24 10:43:01.933  4687  4755 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-24 10:43:01.932  3205  3205 D PanProfile: Bluetooth service disconnected
11-24 10:43:01.934  4687  4687 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-24 10:43:01.934  3205  3205 D BluetoothMap: Proxy object disconnected
11-24 10:43:01.934  3205  3205 D MapProfile: Bluetooth service disconnected
,11-24 10:43:01.939  4687  4687 V BluetoothAdapterState: isTurningOff()=true
,11-24 10:43:01.939  4687  4687 V BluetoothAdapterState: isTurningOn()=false
11-24 10:43:01.939  4687  4687 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 10:43:01.939  4687  4687 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:43:01.940  4687  4687 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-24 10:43:01.940  4687  4687 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-24 10:43:01.940  4687  4687 D BluetoothMapService: MAP Service closeService in
,11-24 10:43:01.940  4687  4687 V BluetoothAdapterState: isTurningOff()=true
,11-24 10:43:01.941  4687  4687 V BluetoothAdapterState: isTurningOn()=false
11-24 10:43:01.941  4687  4687 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:01.941  4687  4687 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:43:01.941  4687  4687 D BluetoothMapService: cleanup()
11-24 10:43:01.941  4687  4687 D BluetoothMapService: MAP Service closeService in
11-24 10:43:01.941  4687  4687 V BluetoothAdapterState: isTurningOff()=true
11-24 10:43:01.941  4687  4687 V BluetoothAdapterState: isTurningOn()=false
11-24 10:43:01.941  4687  4687 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:01.941  4687  4687 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:43:01.941  4687  4748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-24 10:43:01.941  4687  4748 D BluetoothAdapterProperties: Setting state to 15
11-24 10:43:01.941  4687  4748 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-24 10:43:01.942  4687  4748 I BluetoothAdapterState: Entering BleOnState
11-24 10:43:01.942  3205  3219 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-24 10:43:01.943  3205  4072 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 10:43:01.943  3205  5765 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-24 10:43:01.944   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 10:43:01.944  3205  4067 D BluetoothPan: onBluetoothStateChange on: false
11-24 10:43:01.945   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 10:43:01.945  3846  3866 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 10:43:01.949   505   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-24 10:43:01.949  3205  3218 D BluetoothMap: onBluetoothStateChange: up=false
11-24 10:43:01.949   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 10:43:01.949   925   942 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 10:43:01.950  3205  3219 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 10:43:01.951  4687  4748 D BluetoothAdapterState: Current state: BLE ON, message: 20
,11-24 10:43:01.951  4687  4748 D BluetoothAdapterProperties: Setting state to 16
11-24 10:43:01.951  4687  4748 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-24 10:43:01.951  4687  4748 D BluetoothAdapterProperties: onBleDisable
11-24 10:43:01.952  4687  4748 I BluetoothAdapterState: Entering PendingCommandState
11-24 10:43:01.952  4687  4751 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-24 10:43:01.953  4687  4891 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-24 10:43:01.953  4687  4891 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 10:43:01.953  5766  5766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 10:43:01.954  5766  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 10:43:01.954  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:43:01.954  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:43:01.954  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 10:43:01.954  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 10:43:01.954  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 10:43:01.954  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 10:43:01.954  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 10:43:01.954  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 10:43:01.954  5766  5766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 10:43:01.954  5766  5766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 10:43:01.955  4687  4755 D BluetoothAdapterProperties: Scan Mode:20
11-24 10:43:01.957  5766  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:43:01.966  5823  5823 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-24 10:43:01.975   505   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-24 10:43:01.975   505   922 D CommandListener: Clearing all IP addresses on wlan0
11-24 10:43:01.976   505   922 D TetherController: Setting IP forward enable = 0
,11-24 10:43:01.976   925  3042 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,11-24 10:43:01.976   925  3042 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-24 10:43:01.977  5823  5823 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 10:43:01.979   925   942 D Tethering: MasterInitialState.processMessage what=3
11-24 10:43:01.980   925  3037 D DhcpClient: doQuit
11-24 10:43:01.980   925  3037 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-24 10:43:01.980  5766  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 10:43:01.981   925  5500 D DhcpClient: onQuitting
11-24 10:43:01.981  5396  5396 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@97bf50 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-24 10:43:01.982  3535  3535 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-24 10:43:01.983  5034  5034 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-24 10:43:01.986  5766  5766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 10:43:01.986  5766  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 10:43:01.986  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:43:01.986  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:43:01.986  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 10:43:01.986  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 10:43:01.986  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 10:43:01.986  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 10:43:01.986  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 10:43:01.986  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 10:43:01.986  5156  5179 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-24 10:43:01.986  5156  5179 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 10:43:01.986  5156  5179 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-24 10:43:01.986  5156  5179 E SarControlService: no key has been found,reset the power
11-24 10:43:01.986  5766  5766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 10:43:01.986  5766  5766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 10:43:01.986  5156  5193 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,11-24 10:43:01.986  5156  5193 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 10:43:01.987  5156  5193 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 10:43:01.987  5181  5181 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 10:43:01.987  5181  5181 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 10:43:01.989  5156  5193 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 10:43:01.989  5156  5193 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 10:43:01.989  5156  5193 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 10:43:01.990  5181  5181 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 10:43:01.991  5181  5181 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 10:43:01.993  5181  5195 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@8fef3b6 HexData = [00000000ea03000000000000ffffffff]
11-24 10:43:01.993  5181  5195 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-24 10:43:01.993  5181  5195 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-24 10:43:01.993  5181  5181 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 10:43:01.994  5156  5166 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-24 10:43:02.001  5181  5195 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@8fef3b6 HexData = [00000000eb03000000000000ffffffff]
11-24 10:43:02.001  5181  5195 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 10:43:02.001  5181  5195 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-24 10:43:02.002  5181  5181 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 10:43:02.002  5156  5167 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-24 10:43:02.003  3635  3635 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 10:43:02.006   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a78ee7e:true
,11-24 10:43:02.011  3535  3535 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-24 10:43:02.015  3535  3535 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-24 10:43:02.017   925   936 I ActivityManager: Start proc 5852:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-24 10:43:02.032   505   922 E Netd    : netlink response contains error (No such file or directory)
,11-24 10:43:02.033   505   922 D TetherController: Setting IP forward enable = 0
,11-24 10:43:02.034   925  3042 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-24 10:43:02.034   925  3042 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-24 10:43:02.040  5823  5823 D LocalBluetoothProfileManager: Adding local MAP profile
,11-24 10:43:02.044  5823  5823 D BluetoothMap: Create BluetoothMap proxy object
,11-24 10:43:02.053  3535  3535 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-24 10:43:02.057  5823  5823 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-24 10:43:02.064  5852  5852 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-24 10:43:02.070  3535  3535 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-24 10:43:02.077  5823  5823 D DockEventReceiver: finishStartingService: stopping service
,11-24 10:43:02.080   925  3847 I ActivityManager: Killing 5089:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-24 10:43:02.159  4687  4755 I bt_hci  : shut_down
,11-24 10:43:02.162  4687  4779 D bt_hwcfg: hw_epilog_process
,11-24 10:43:02.163  4687  4779 I bt_vendor: low_power_mode_cb
11-24 10:43:02.165  4687  4779 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-24 10:43:02.165  4687  4779 I bt_vendor: epilog_cb
11-24 10:43:02.165  4687  4779 I bt_hci  : epilog_finished_callback
,11-24 10:43:02.167  4687  4755 I bt_hci_h4: hal_close
,11-24 10:43:02.168  4687  4755 I bt_userial_vendor: device fd = 54 close
,11-24 10:43:02.174   925  3037 D wifi    : In wifi stop Hal
11-24 10:43:02.174   925  3037 D wifi    : halHandle = 0x7f87d91e00, mVM = 0x7fa438d140, mCls = 0x100a02
11-24 10:43:02.174   925  3533 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-24 10:43:02.174   925  3533 D WifiHAL : Got a signal to exit!!!
11-24 10:43:02.174   925  3533 I WifiHAL : Exit wifi_event_loop
11-24 10:43:02.175   925  3037 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-24 10:43:02.175   925  3037 E WifiHAL : Event processing terminated
11-24 10:43:02.175   925  3037 D wifi    : In wifi cleaned up handler
11-24 10:43:02.175   925  3037 I WifiHAL : Internal cleanup completed
11-24 10:43:02.176  5130  5130 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 10:43:02.177  5766  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 10:43:02.177  4179  4308 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 10:43:02.194   925  3533 D wifi    : set interface wlan0 flags (DOWN)
11-24 10:43:02.195   925  3037 D WifiNative-HAL: HAL event thread stopped successfully
,11-24 10:43:02.260  5852  5852 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-24 10:43:02.260  5852  5852 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 10:43:02.260  5852  5852 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 10:43:02.260  5852  5852 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.r.e.b(PG:170)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 10:43:02.260  5852  5852 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 10:43:02.261  5852  5852 D StrictMode: StrictMode policy violation; ~duration=102 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.r.k.d(PG:583)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.r.e.b(PG:170)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 10:43:02.261  5852  5852 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 10:43:02.261  5852  5852 D StrictMode: StrictMode policy violation; ~duration=67 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 10:43:02.261  5852  5852 D StrictMode: StrictMode policy violation; ~duration=66 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 10:43:02.261  5852  5852 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 10:43:02.267  5823  5823 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 10:43:02.276  3635  3635 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 10:43:02.278  5823  5823 D DockEventReceiver: finishStartingService: stopping service
11-24 10:43:02.282  4687  4751 D bt_stack_manager: event_shut_down_stack finished.
11-24 10:43:02.282   925  3499 I ActivityManager: Killing 5239:com.google.android.deskclock/u0a66 (adj 15): empty #17
11-24 10:43:02.282  4687  4748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-24 10:43:02.331  4687  4748 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-24 10:43:02.331  4687  4687 D BtGatt.DebugUtils: handleDebugAction() action=null
11-24 10:43:02.332  4687  4687 D BtGatt.GattService: Received stop request...Stopping profile...
11-24 10:43:02.332  4687  4687 D BtGatt.GattService: stop()
11-24 10:43:02.332  4687  4687 D BtGatt.AdvertiseManager: advertise clients cleared
,11-24 10:43:02.333  3927  3927 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-24 10:43:02.334  4687  4687 V BluetoothAdapterState: isTurningOff()=false
11-24 10:43:02.334  4687  4687 V BluetoothAdapterState: isTurningOn()=false
,11-24 10:43:02.334  4687  4687 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:02.334  4687  4687 V BluetoothAdapterState: isBleTurningOff()=true
11-24 10:43:02.334  4687  4748 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-24 10:43:02.335  4687  4748 D BluetoothAdapterProperties: Setting state to 10
11-24 10:43:02.335  4687  4748 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-24 10:43:02.335  4687  4748 I BluetoothAdapterState: Entering OffState
11-24 10:43:02.337  3927  3927 D SystemUpdateService: onCreate
,11-24 10:43:02.338   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
,11-24 10:43:02.345  4687  4687 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-24 10:43:02.345  4687  4687 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-24 10:43:02.345  4687  4687 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-24 10:43:02.346  4687  4751 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-24 10:43:02.347  3927  3927 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-24 10:43:02.354  4687  4687 I art     : System.exit called, status: 0
11-24 10:43:02.354  4687  4687 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-24 10:43:02.360  3927  3927 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-24 10:43:02.366  3927  5525 I iu.UploadsManager: num queued entries: 0
,11-24 10:43:02.367  3927  5525 I iu.UploadsManager: num updated entries: 0
11-24 10:43:02.367  3927  5525 I iu.SyncManager: NEXT; no task
,11-24 10:43:02.369  3927  3927 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 10:43:02.370  3927  3927 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 10:43:02.382   925  3913 I ActivityManager: Start proc 5889:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-24 10:43:02.382  3927  5886 I SystemUpdateService: active receiver: enabled
,11-24 10:43:02.397   925   942 D Tethering: InitialState.processMessage what=4
,11-24 10:43:02.400   925  3901 I ActivityManager: Process com.android.bluetooth (pid 4687) has died
,11-24 10:43:02.401   925   942 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-24 10:43:02.419  5889  5889 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-24 10:43:02.421  5889  5889 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 10:43:02.427  5889  5889 D SprintDMHelper: simOperator: 
,11-24 10:43:02.427  5889  5889 D SprintDMReceiver: Not Sprint UICC, don't do anything.
11-24 10:43:02.429  3927  5886 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 10:43:02.439   925  3849 I ActivityManager: Start proc 5901:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-24 10:43:02.440  3927  5886 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-24 10:43:02.440  3927  5886 I SystemUpdateService: now status is 0 (complete)
11-24 10:43:02.440  3927  5886 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 10:43:02.440  3927  5886 I SystemUpdateService: file has been verified
11-24 10:43:02.440  3927  5886 I SystemUpdateService: OTA package size = 21989297
,11-24 10:43:02.460  3927  5886 I SystemUpdateService: showing system update notification
,11-24 10:43:02.538  3927  3927 D SystemUpdateService: onDestroy
11-24 10:43:02.542   925  3287 I ActivityManager: Killing 5575:com.qualcomm.timeservice/1000 (adj 15): empty #17
,11-24 10:43:02.554  5130  5915 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-24 10:43:02.566   925  3287 I ActivityManager: Killing 5396:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-24 10:43:02.604   925  3287 I ActivityManager: Start proc 5916:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-24 10:43:02.642  5916  5916 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-24 10:43:02.653   925  3849 I ActivityManager: Killing 5621:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-24 10:43:02.723  5852  5878 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-24 10:43:02.732   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e271a63:true
,11-24 10:43:06.884   925  3847 D WifiService: setWifiEnabled: true pid=5766, uid=10077
,11-24 10:43:06.884   925  3847 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 10:43:06.897   505   922 D SoftapController: Softap fwReload - Ok
,11-24 10:43:06.903   505   922 D CommandListener: Setting iface cfg
,11-24 10:43:06.903   505   922 D CommandListener: Trying to bring down wlan0
,11-24 10:43:06.905   505   922 D CommandListener: Clearing all IP addresses on wlan0
,11-24 10:43:06.911   925  3037 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 10:43:07.477   925  3037 D wifi    : set interface wlan0 flags (UP)
11-24 10:43:07.480   925  3037 I WifiHAL : Initializing wifi
11-24 10:43:07.480   925  3037 I WifiHAL : Creating socket
,11-24 10:43:07.485   925   942 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-24 10:43:07.486   925  3037 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-24 10:43:07.486   925  3037 D wifi    : Did set static halHandle = 0x7f87d91e00
11-24 10:43:07.486   925  3037 D wifi    : halHandle = 0x7f87d91e00, mVM = 0x7fa438d140, mCls = 0x1952
11-24 10:43:07.486   925  3037 D wifi    : array field set
,11-24 10:43:07.486   925  3037 I WifiNative-HAL: interface[0] = wlan0
,11-24 10:43:07.488   925  5933 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547739999744
,11-24 10:43:07.488   925  5933 D wifi    : waitForHalEvents called, vm = 0x7fa438d140, obj = 0x1952, env = 0x7f8a12fe40
,11-24 10:43:07.491   925  3037 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-24 10:43:07.494  5766  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:43:07.550  5934  5934 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-24 10:43:07.566  5934  5934 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 10:43:07.575  5934  5934 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 10:43:07.575  5934  5934 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-24 10:43:07.587   925  3037 D WifiConfigStore: Loading config and enabling all networks 
,11-24 10:43:07.588  5766  5766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 10:43:07.588  5766  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 10:43:07.588  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:43:07.588  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:43:07.588  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 10:43:07.588  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 10:43:07.588  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 10:43:07.588  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 10:43:07.588  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 10:43:07.588  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 10:43:07.588  5766  5766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 10:43:07.588  5766  5766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 10:43:07.595   925  3037 D WifiConfigStore: loaded 0 passpoint configs
11-24 10:43:07.595   925  3037 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,11-24 10:43:07.595   925  3037 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-24 10:43:07.596   925  3037 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-24 10:43:07.597   925  3037 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-24 10:43:07.597   925  3037 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-24 10:43:07.597   925  3037 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-24 10:43:07.597   925  3037 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-24 10:43:07.599   925  3037 D WifiNative-HAL: Setting external_sim to 1
,11-24 10:43:07.599   925  3037 D wifi    : setting dfs flag to true, 0x7f8cd0e620
11-24 10:43:07.600   925  3037 D WifiStateMachine: Setting OUI to DA-A1-19
11-24 10:43:07.600   925  3037 D wifi    : setting scan oui 0x7f8cd0e620
11-24 10:43:07.600   925  3037 D WifiHAL : Sending mac address OUI
,11-24 10:43:07.600  5130  5130 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 10:43:07.603   925  3037 E native  : do suspend false
,11-24 10:43:07.610   925  3037 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-24 10:43:07.610   925   925 D RttService: SCAN_AVAILABLE : 3
,11-24 10:43:07.610   925  3145 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-24 10:43:07.610   505   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-24 10:43:07.611   505   922 D CommandListener: Setting iface cfg
,11-24 10:43:07.614   925  3036 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '128 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 128 Failed to set address (No such device)'
,11-24 10:43:07.614   925  3036 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-24 10:43:07.623   925  3036 D WifiNative-HAL: p2pGetDeviceAddress
,11-24 10:43:07.623   925  3036 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-24 10:43:07.628   925   940 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=208103 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,11-24 10:43:10.699  5934  5934 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 10:43:10.704  5934  5934 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 10:43:10.711  5934  5934 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 10:43:10.716  5934  5934 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 10:43:10.769   925  3037 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-24 10:43:10.770   925  3037 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-24 10:43:10.770   925  3037 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 10:43:10.782   925  3037 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-24 10:43:10.815   925  3037 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-24 10:43:10.817  5934  5934 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-24 10:43:11.242  5934  5934 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-24 10:43:11.270  5934  5934 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-24 10:43:11.271  5934  5934 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-24 10:43:11.284   925  3037 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 10:43:11.284   925  3037 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 10:43:11.284   925  3042 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-24 10:43:11.302   925  3037 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 10:43:11.313   505   922 D CommandListener: Setting iface cfg
,11-24 10:43:11.319   925  3037 D WifiStateMachine: Start Dhcp Watchdog 2
,11-24 10:43:11.325   925  5942 D DhcpClient: Receive thread started
,11-24 10:43:11.331   925  3042 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 10:43:11.331   925  3037 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-24 10:43:11.331   925  3042 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-24 10:43:11.411   925  3037 E native  : do suspend false
,11-24 10:43:11.426   925  5941 D DhcpClient: Broadcasting DHCPDISCOVER
,11-24 10:43:11.441   925  5942 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172628, domain null
,11-24 10:43:11.442   925  5941 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172628 seconds
,11-24 10:43:11.444   925  5941 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-24 10:43:11.459   925  5942 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-24 10:43:11.459   925  5941 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-24 10:43:11.462   505   922 D CommandListener: Setting iface cfg
,11-24 10:43:11.467   925  3037 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-24 10:43:11.473   925  5941 D DhcpClient: Scheduling renewal in 86399s
,11-24 10:43:11.484   925  3037 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-24 10:43:11.485   925  3037 D WifiConfigStore: No blacklist allowed without epno enabled
,11-24 10:43:11.486   925  3042 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-24 10:43:11.488   925  3042 D ConnectivityService: Adding iface wlan0 to network 101
11-24 10:43:11.495   925  3037 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-24 10:43:11.533   925  3042 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-24 10:43:11.534   925  3042 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-24 10:43:11.536   925  3042 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-24 10:43:11.537   925  3042 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-24 10:43:11.539   925  3042 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-24 10:43:11.552   925  3042 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 10:43:11.556   925  3042 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-24 10:43:11.556   925  3042 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-24 10:43:11.556   925  3042 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-24 10:43:11.556   925  3042 D ConnectivityService:    accepting network in place of null
11-24 10:43:11.556   925  3037 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-24 10:43:11.556   925  3037 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 10:43:11.557   925  3042 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -42]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 10:43:11.574   925  5940 D NetlinkSocketObserver: NeighborEvent{elapsedMs=212048, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 10:43:11.580   505   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 10:43:11.600   505   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 10:43:11.604   925  3042 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-24 10:43:11.604  3801  3965 W QCNEJ   : |CORE| network available: 101
,11-24 10:43:11.604   925  3042 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-24 10:43:11.606   925   942 D Tethering: MasterInitialState.processMessage what=3
11-24 10:43:11.606   925  3042 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-24 10:43:11.607  3801  3965 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-24 10:43:11.608  3801  3965 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-24 10:43:11.608  3801  3965 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-24 10:43:11.617  5766  5766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 10:43:11.617  5766  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 10:43:11.617  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:43:11.617  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:43:11.617  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 10:43:11.617  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 10:43:11.617  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 10:43:11.617  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 10:43:11.617  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 10:43:11.617  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 10:43:11.617  5766  5766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 10:43:11.617  5766  5766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 10:43:11.623  5034  5034 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-24 10:43:11.625  5156  5179 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-24 10:43:11.625  5156  5179 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,11-24 10:43:11.626  5156  5179 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
,11-24 10:43:11.626  5156  5179 E SarControlService: no key has been found,reset the power
11-24 10:43:11.626  5156  5193 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 10:43:11.626  5156  5193 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,11-24 10:43:11.636  3927  3927 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-24 10:43:11.643   925  5939 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-24 10:43:11.643  3927  3927 D SystemUpdateService: onCreate
,11-24 10:43:11.626  5156  5193 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 10:43:11.648  5181  5181 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 10:43:11.648  5181  5181 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 10:43:11.650  5156  5193 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 10:43:11.650  5156  5193 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 10:43:11.650  5156  5193 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 10:43:11.650  5181  5181 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 10:43:11.650  5181  5181 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 10:43:11.651  3927  3927 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 10:43:11.655  5181  5195 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@8fef3b6 HexData = [00000000ec03000000000000ffffffff]
11-24 10:43:11.655  5181  5195 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 10:43:11.655  5181  5195 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-24 10:43:11.655  5181  5181 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 10:43:11.656  5156  5166 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-24 10:43:11.657  5181  5195 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@8fef3b6 HexData = [00000000ed03000000000000ffffffff]
11-24 10:43:11.657  5181  5195 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 10:43:11.657  5181  5195 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,11-24 10:43:11.658  5181  5181 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 10:43:11.658  5156  5167 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-24 10:43:11.662  3927  3927 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-24 10:43:11.669  3927  5525 I iu.UploadsManager: num queued entries: 0
,11-24 10:43:11.669  3927  5525 I iu.UploadsManager: num updated entries: 0
11-24 10:43:11.670  3927  5525 I iu.SyncManager: NEXT; no task
,11-24 10:43:11.673  3927  5952 I SystemUpdateService: active receiver: enabled
,11-24 10:43:11.674  3927  3927 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 10:43:11.676  3927  3927 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 10:43:11.678  5889  5889 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-24 10:43:11.681  5889  5889 D SprintDMHelper: simOperator: 
11-24 10:43:11.681  5889  5889 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 10:43:11.698   925  5939 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Nov 2016 15:43:11 GMT], X-Android-Received-Millis=[1480002191697], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480002191670]}
11-24 10:43:11.698   925  3042 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-24 10:43:11.698   925  3042 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-24 10:43:11.698   925  3042 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-24 10:43:11.699   925  3042 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-24 10:43:11.705  3927  5952 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 10:43:11.720  3927  5952 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-24 10:43:11.720  3927  5952 I SystemUpdateService: now status is 0 (complete)
11-24 10:43:11.720  3927  5952 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 10:43:11.720  3927  5952 I SystemUpdateService: file has been verified
11-24 10:43:11.720  3927  5952 I SystemUpdateService: OTA package size = 21989297
,11-24 10:43:11.726  3927  5952 I SystemUpdateService: showing system update notification
,11-24 10:43:11.740  3927  3927 D SystemUpdateService: onDestroy
,11-24 10:43:11.785  5130  5957 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-24 10:43:11.897   925   935 D WifiService: setWifiEnabled: false pid=5766, uid=10077
,11-24 10:43:11.898   925   935 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 10:43:11.905   925  3037 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-24 10:43:11.905   925  3037 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-24 10:43:11.906   925  3037 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 10:43:11.906   925  3037 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 10:43:11.920   925  5941 D DhcpClient: Clearing IP address
11-24 10:43:11.920   505   922 D CommandListener: Clearing all IP addresses on wlan0
,11-24 10:43:11.926   505   922 D CommandListener: Setting iface cfg
,11-24 10:43:11.937  3635  5962 V NativeCrypto: Read error: ssl=0x7fa2b9b400: I/O error during system call, Connection timed out
,11-24 10:43:11.940  3635  5962 V NativeCrypto: SSL shutdown failed: ssl=0x7fa2b9b400: I/O error during system call, Broken pipe
,11-24 10:43:11.942   925  3042 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-24 10:43:11.942   925  3042 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-24 10:43:11.949   925  3042 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,11-24 10:43:11.951   533   533 E Parcel  : Reading a NULL string not supported here.
11-24 10:43:11.952  3801  3965 W QCNEJ   : |CORE| network lost: 101
,11-24 10:43:11.952  3801  3965 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-24 10:43:11.954   925   925 D RttService: SCAN_AVAILABLE : 1
11-24 10:43:11.954   925  3145 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,11-24 10:43:11.956   925  3037 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-24 10:43:11.959   925  5942 D DhcpClient: Receive thread stopped
11-24 10:43:11.960   925  3037 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 10:43:11.975   505   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 10:43:11.995   505   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 10:43:11.996   925  3042 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-24 10:43:11.996   925  3042 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-24 10:43:11.996   505   922 D CommandListener: Clearing all IP addresses on wlan0
,11-24 10:43:11.998   925   942 D Tethering: MasterInitialState.processMessage what=3
11-24 10:43:12.000  5766  5766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 10:43:12.000  5766  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 10:43:12.000  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:43:12.000  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:43:12.000  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 10:43:12.000  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 10:43:12.000  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 10:43:12.000  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 10:43:12.000  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 10:43:12.000  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 10:43:12.000  5766  5766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 10:43:12.000  5766  5766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 10:43:12.000   925  3037 D DhcpClient: doQuit
11-24 10:43:12.001   925  5941 D DhcpClient: onQuitting
,11-24 10:43:12.001   925  3037 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-24 10:43:12.001  5934  5934 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-24 10:43:12.005  5766  5766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 10:43:12.005  5766  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 10:43:12.005  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:43:12.005  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:43:12.005  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 10:43:12.005  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 10:43:12.005  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 10:43:12.005  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 10:43:12.005  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 10:43:12.005  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 10:43:12.005  5766  5766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 10:43:12.005  5766  5766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 10:43:12.010  5034  5034 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-24 10:43:12.014  3927  3927 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-24 10:43:12.016  5156  5179 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-24 10:43:12.016  5156  5179 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 10:43:12.016  5156  5179 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-24 10:43:12.016  5156  5179 E SarControlService: no key has been found,reset the power
11-24 10:43:12.016  5156  5193 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 10:43:12.016  5156  5193 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 10:43:12.016  5156  5193 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 10:43:12.017  5181  5181 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 10:43:12.017  5181  5181 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 10:43:12.018  5156  5193 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 10:43:12.018  5156  5193 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 10:43:12.018  5156  5193 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 10:43:12.019  5181  5181 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 10:43:12.019  5181  5181 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 10:43:12.019  5934  5934 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-24 10:43:12.022  3927  3927 D SystemUpdateService: onCreate
,11-24 10:43:12.023  5181  5195 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@8fef3b6 HexData = [00000000ee03000000000000ffffffff]
11-24 10:43:12.024  5181  5195 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 10:43:12.024  5181  5195 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-24 10:43:12.024  5181  5181 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 10:43:12.024  5156  5167 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-24 10:43:12.027  5934  5934 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-24 10:43:12.027  5181  5195 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@8fef3b6 HexData = [00000000ef03000000000000ffffffff]
11-24 10:43:12.027  5181  5195 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 10:43:12.027  5181  5195 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-24 10:43:12.028  5181  5181 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 10:43:12.029  5156  5166 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-24 10:43:12.029  3927  3927 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 10:43:12.033  3927  5973 I SystemUpdateService: active receiver: enabled
,11-24 10:43:12.037  3927  3927 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-24 10:43:12.042  3927  5525 I iu.UploadsManager: num queued entries: 0
,11-24 10:43:12.042  3927  5525 I iu.UploadsManager: num updated entries: 0
11-24 10:43:12.043  3927  5525 I iu.SyncManager: NEXT; no task
,11-24 10:43:12.046  3927  3927 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 10:43:12.047  3927  3927 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 10:43:12.049  5889  5889 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 10:43:12.052   505   922 E Netd    : netlink response contains error (No such file or directory)
11-24 10:43:12.053   925  3042 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-24 10:43:12.053  5889  5889 D SprintDMHelper: simOperator: 
11-24 10:43:12.053  5889  5889 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 10:43:12.056  5934  5934 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-24 10:43:12.061  3927  5973 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 10:43:12.065  5130  5976 I Babel   : connection state changed from CONNECTED to DISCONNECTED
11-24 10:43:12.066  5934  5934 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-24 10:43:12.070  3927  5973 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-24 10:43:12.072  3927  5973 I SystemUpdateService: now status is 0 (complete)
,11-24 10:43:12.072  3927  5973 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 10:43:12.072  3927  5973 I SystemUpdateService: file has been verified
,11-24 10:43:12.076  3927  5973 I SystemUpdateService: OTA package size = 21989297
,11-24 10:43:12.084  3927  5973 I SystemUpdateService: showing system update notification
,11-24 10:43:12.093  3927  3927 D SystemUpdateService: onDestroy
,11-24 10:43:12.167   925  3037 D wifi    : In wifi stop Hal
,11-24 10:43:12.168   925  3037 D wifi    : halHandle = 0x7f87d91e00, mVM = 0x7fa438d140, mCls = 0x1952
,11-24 10:43:12.168   925  5933 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-24 10:43:12.168   925  5933 D WifiHAL : Got a signal to exit!!!
11-24 10:43:12.168   925  5933 I WifiHAL : Exit wifi_event_loop
11-24 10:43:12.168   925  3037 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-24 10:43:12.168   925  3037 E WifiHAL : Event processing terminated
11-24 10:43:12.168   925  3037 D wifi    : In wifi cleaned up handler
11-24 10:43:12.168   925  3037 I WifiHAL : Internal cleanup completed
11-24 10:43:12.169  5130  5130 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 10:43:12.172  4179  4308 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 10:43:12.172  5766  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:43:12.196   925  5933 D wifi    : set interface wlan0 flags (DOWN)
,11-24 10:43:12.197   925  3037 D WifiNative-HAL: HAL event thread stopped successfully
,11-24 10:43:12.402   925   942 D Tethering: InitialState.processMessage what=4
,11-24 10:43:12.409   925   942 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-24 10:43:12.606   925  3042 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-24 10:43:16.945   925   942 I ActivityManager: Start proc 5978:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-24 10:43:17.033  5978  5978 D AdapterServiceConfig: Adding HeadsetService
11-24 10:43:17.033  5978  5978 D AdapterServiceConfig: Adding A2dpService
11-24 10:43:17.033  5978  5978 D AdapterServiceConfig: Adding HidService
11-24 10:43:17.033  5978  5978 D AdapterServiceConfig: Adding HealthService
11-24 10:43:17.033  5978  5978 D AdapterServiceConfig: Adding PanService
11-24 10:43:17.034  5978  5978 D AdapterServiceConfig: Adding GattService
11-24 10:43:17.034  5978  5978 D AdapterServiceConfig: Adding BluetoothMapService
,11-24 10:43:17.034  5978  5978 D AdapterServiceConfig: Adding SapService
,11-24 10:43:17.045   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b648376:true
,11-24 10:43:17.046  5978  5978 D BluetoothAdapterState: make() - Creating AdapterState
,11-24 10:43:17.048  5978  5978 I bt_bluedroid: init
,11-24 10:43:17.048  5978  5990 I BluetoothAdapterState: Entering OffState
,11-24 10:43:17.050  5978  5991 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-24 10:43:17.051  5978  5991 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-24 10:43:17.051  5978  5991 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-24 10:43:17.051  5978  5991 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-24 10:43:17.051  5978  5978 I bt_bluedroid: get_profile_interface socket
,11-24 10:43:17.053  5978  5978 I bt_bluedroid: get_profile_interface sdp
,11-24 10:43:17.053  5978  5994 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-24 10:43:17.055  5978  5994 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 10:43:17.058  5978  5989 I bt_bluedroid: config_hci_snoop_log
,11-24 10:43:17.059   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
11-24 10:43:17.063  5978  5990 D BluetoothAdapterState: Current state: OFF, message: 0
11-24 10:43:17.064  5978  5990 D BluetoothAdapterProperties: Setting state to 14
11-24 10:43:17.064  5978  5990 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-24 10:43:17.065  5978  5990 D BluetoothBondStateMachine: make
,11-24 10:43:17.067  5978  5995 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-24 10:43:17.070  5978  5990 I BluetoothAdapterState: Entering PendingCommandState
,11-24 10:43:17.071  5978  5978 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-24 10:43:17.073  5978  5978 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f57f4
,11-24 10:43:17.074  5978  5978 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-24 10:43:17.074  5978  5978 D BtGatt.GattService: Received start request. Starting profile...
11-24 10:43:17.074  5978  5978 D BtGatt.GattService: start()
11-24 10:43:17.074  5978  5978 I bt_bluedroid: get_profile_interface gatt
,11-24 10:43:17.075  5978  5978 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f57f4
11-24 10:43:17.075  5978  5978 D BtGatt.AdvertiseManager: advertise manager created
,11-24 10:43:17.080  5978  5978 V BluetoothAdapterState: isTurningOff()=false
,11-24 10:43:17.081  5978  5978 V BluetoothAdapterState: isTurningOn()=false
11-24 10:43:17.081  5978  5978 V BluetoothAdapterState: isBleTurningOn()=true
11-24 10:43:17.081  5978  5978 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:43:17.081  5978  5990 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-24 10:43:17.082  5978  5990 I bt_bluedroid: bt_bluedroid
,11-24 10:43:17.083  5978  5991 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-24 10:43:17.083  5978  5991 I bt_hci  : start_up
,11-24 10:43:17.088  5978  5991 I bt_vendor: alloc value 0xf3eff871
,11-24 10:43:17.088  5978  5991 I bt_vendor: init
11-24 10:43:17.088  5978  5991 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-24 10:43:17.088  5978  5991 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-24 10:43:17.199  5978  5991 D bt_hci  : start_up starting async portion
11-24 10:43:17.199  5978  5998 I bt_hci  : event_finish_startup
11-24 10:43:17.199  5978  5998 I bt_hci_h4: hal_open
,11-24 10:43:17.200  5978  5998 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-24 10:43:17.202  5978  5998 I bt_userial_vendor: device fd = 54 open
,11-24 10:43:17.198  5999  5999 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 10:43:17.216  5978  5998 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 10:43:17.219  5978  5998 D bt_hwcfg: Chipset BCM4358A3
,11-24 10:43:17.219  5978  5998 D bt_hwcfg: Target name = [BCM4358A3]
,11-24 10:43:17.220  5978  5998 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-24 10:43:17.620  5978  5998 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-24 10:43:17.620  5978  5998 D bt_hwcfg: Settlement delay -- 100 ms
,11-24 10:43:17.620  5978  5998 I bt_hwcfg: Setting fw settlement delay to 100 
,11-24 10:43:17.755  5978  5998 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 10:43:17.755  5978  5998 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,11-24 10:43:17.757  5978  5998 I bt_hwcfg: vendor lib fwcfg completed
,11-24 10:43:17.757  5978  5998 I bt_vendor: firmware callback
,11-24 10:43:17.757  5978  5998 I bt_hci  : firmware_config_callback
,11-24 10:43:17.766  5978  6001 I bt_btu  : btu_task pending for preload complete event
,11-24 10:43:17.766  5978  6001 I bt_btu_task: Bluetooth chip preload is complete
11-24 10:43:17.766  5978  6001 I bt_btu  : btu_task received preload complete event
,11-24 10:43:17.773  5978  6001 I         : BTE_InitTraceLevels -- TRC_HCI
,11-24 10:43:17.773  5978  6001 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-24 10:43:17.774  5978  6001 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-24 10:43:17.774  5978  6001 I         : BTE_InitTraceLevels -- TRC_AVDT
11-24 10:43:17.774  5978  6001 I         : BTE_InitTraceLevels -- TRC_AVRC
11-24 10:43:17.774  5978  6001 I         : BTE_InitTraceLevels -- TRC_A2D
11-24 10:43:17.774  5978  6001 I         : BTE_InitTraceLevels -- TRC_BNEP
11-24 10:43:17.774  5978  6001 I         : BTE_InitTraceLevels -- TRC_BTM
11-24 10:43:17.774  5978  6001 I         : BTE_InitTraceLevels -- TRC_GAP
11-24 10:43:17.774  5978  6001 I         : BTE_InitTraceLevels -- TRC_PAN
11-24 10:43:17.775  5978  6001 I         : BTE_InitTraceLevels -- TRC_SDP
11-24 10:43:17.775  5978  6001 I         : BTE_InitTraceLevels -- TRC_GATT
11-24 10:43:17.775  5978  6001 I         : BTE_InitTraceLevels -- TRC_SMP
11-24 10:43:17.775  5978  6001 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-24 10:43:17.775  5978  6001 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-24 10:43:17.859  5978  6001 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3e7d549
11-24 10:43:17.859  5978  6001 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3e7d549 
,11-24 10:43:17.872  5978  5994 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-24 10:43:17.874  5978  5994 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-24 10:43:17.874  5978  5994 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
11-24 10:43:17.877  5978  5994 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 10:43:17.882  5978  5994 D BluetoothAdapterProperties: Scan Mode:20
11-24 10:43:17.883  5978  5994 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-24 10:43:17.883  5978  5994 D bt_hci  : do_postload posting postload work item
11-24 10:43:17.884  5978  5998 I bt_hci  : event_postload
,11-24 10:43:17.884  5978  5998 I bt_vendor: sco_config_cb
,11-24 10:43:17.884  5978  5998 I bt_hci  : sco_config_callback postload finished.
,11-24 10:43:17.885  5766  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:43:17.888  5978  5994 D bt_bte_conf: Device ID record 1 : primary
,11-24 10:43:17.888  5978  5994 D bt_bte_conf:   vendorId            = 000f
11-24 10:43:17.888  5978  5994 D bt_bte_conf:   vendorIdSource      = 0001
11-24 10:43:17.889  5978  5994 D bt_bte_conf:   product             = 1200
,11-24 10:43:17.889  5978  5994 D bt_bte_conf:   version             = 1436
,11-24 10:43:17.889  5978  5994 D bt_bte_conf:   clientExecutableURL = 
11-24 10:43:17.889  5978  5994 D bt_bte_conf:   serviceDescription  = 
11-24 10:43:17.889  5978  5994 D bt_bte_conf:   documentationURL    = 
11-24 10:43:17.889  5978  5994 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-24 10:43:17.889  5978  5991 D bt_stack_manager: event_start_up_stack finished
,11-24 10:43:17.891  5978  5990 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-24 10:43:17.891  5978  5990 D BluetoothAdapterProperties: Setting state to 15
11-24 10:43:17.891  5978  5990 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,11-24 10:43:17.892  5978  5990 I BluetoothAdapterState: Entering BleOnState
11-24 10:43:17.893  5978  5998 I bt_vendor: low_power_mode_cb
,11-24 10:43:17.898  5978  5990 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-24 10:43:17.898  5978  5990 D BluetoothAdapterProperties: Setting state to 11
,11-24 10:43:17.898  5978  5990 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-24 10:43:17.903  5978  5978 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f57f4
,11-24 10:43:17.905  5978  5978 D HeadsetService: Received start request. Starting profile...
,11-24 10:43:17.908  5978  5978 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-24 10:43:17.908  5978  5978 D HeadsetStateMachine: make
11-24 10:43:17.910  5766  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 10:43:17.918  5978  5990 I BluetoothAdapterState: Entering PendingCommandState
,11-24 10:43:17.923  5978  5978 D HeadsetStateMachine: max_hf_connections = 1
,11-24 10:43:17.923  5978  5978 I bt_bluedroid: get_profile_interface handsfree
11-24 10:43:17.923  5978  5994 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-24 10:43:17.923  5978  5994 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,11-24 10:43:17.927  5978  5978 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f57f4
,11-24 10:43:17.927  5978  5978 D A2dpService: Received start request. Starting profile...
,11-24 10:43:17.928  5978  5978 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-24 10:43:17.928  5978  5978 I bt_bluedroid: get_profile_interface avrcp
,11-24 10:43:17.934  5978  5978 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-24 10:43:17.934  5978  5978 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-24 10:43:17.934  5978  5978 D A2dpStateMachine: make
11-24 10:43:17.935  5978  5978 I bt_bluedroid: get_profile_interface a2dp
,11-24 10:43:17.936  5978  5994 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-24 10:43:17.937  5978  6010 D A2dpStateMachine: Enter Disconnected: -2
,11-24 10:43:17.938  5978  5978 I BluetoothHidServiceJni: classInitNative: succeeds
11-24 10:43:17.938  5978  5978 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f57f4
,11-24 10:43:17.940  5978  5978 D HidService: Received start request. Starting profile...
11-24 10:43:17.940  5823  5823 D BluetoothInputDevice: Proxy object connected
11-24 10:43:17.940  5978  5978 I bt_bluedroid: get_profile_interface hidhost
,11-24 10:43:17.940  5978  5978 D HidService: setHidService(): set to: null
11-24 10:43:17.940  5978  5994 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3e5e56d
11-24 10:43:17.940  5978  5994 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,11-24 10:43:17.941  5823  5823 D HidProfile: Bluetooth service connected
11-24 10:43:17.942  5978  5978 I BluetoothHealthServiceJni: classInitNative: succeeds
11-24 10:43:17.942  5978  5978 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f57f4
11-24 10:43:17.943  5978  5978 D HealthService: Received start request. Starting profile...
11-24 10:43:17.943  3635  3635 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 10:43:17.944  5978  5978 I bt_bluedroid: get_profile_interface health
,11-24 10:43:17.945  5978  5978 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-24 10:43:17.946  5978  5978 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f57f4
,11-24 10:43:17.947  5823  5823 D BluetoothPan: BluetoothPAN Proxy object connected
,11-24 10:43:17.947  5978  5978 D PanService: Received start request. Starting profile...
11-24 10:43:17.947  5978  5978 D BluetoothPanServiceJni: initializeNative(L110): pan
11-24 10:43:17.947  5978  5978 I bt_bluedroid: get_profile_interface pan
11-24 10:43:17.947  5978  5994 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-24 10:43:17.947  5823  5823 D PanProfile: Bluetooth service connected
,11-24 10:43:17.949  5978  5978 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f57f4
,11-24 10:43:17.951  5978  5978 D BluetoothMapService: Received start request. Starting profile...
,11-24 10:43:17.951  5978  5978 D BluetoothMapService: start()
11-24 10:43:17.951  5823  5823 D BluetoothMap: Proxy object connected
11-24 10:43:17.951  5823  5823 D MapProfile: Bluetooth service connected
11-24 10:43:17.952  5823  5823 D BluetoothMap: getConnectedDevices()
11-24 10:43:17.952  5823  5823 D BluetoothMap: Bluetooth is Not enabled
,11-24 10:43:17.953  5978  5978 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-24 10:43:17.954  5978  5978 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-24 10:43:17.954  5978  5978 D BluetoothMapAppObserver: createReceiver()
,11-24 10:43:17.956  5978  5978 D BluetoothMapAppObserver: initObservers()
11-24 10:43:17.956  5978  5978 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-24 10:43:17.961  5978  5978 V SapService: SapBinder()
11-24 10:43:17.961  5978  5978 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f57f4
11-24 10:43:17.962  5978  5978 D SapService: Received start request. Starting profile...
11-24 10:43:17.962  5978  5978 V SapService: start()
,11-24 10:43:17.965  5978  5978 V BluetoothAdapterState: isTurningOff()=false
,11-24 10:43:17.965  5978  5978 V BluetoothAdapterState: isTurningOn()=true
11-24 10:43:17.965  5978  5978 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:17.965  5978  6008 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-24 10:43:17.965  5978  5978 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:43:17.965  5978  5978 V BluetoothAdapterState: isTurningOff()=false
11-24 10:43:17.966  5978  5978 V BluetoothAdapterState: isTurningOn()=true
,11-24 10:43:17.966  5978  5978 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:17.966  5978  5978 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:43:17.966  5978  5978 V BluetoothAdapterState: isTurningOff()=false
11-24 10:43:17.966  5978  5978 V BluetoothAdapterState: isTurningOn()=true
11-24 10:43:17.966  5978  5978 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:17.966  5978  5978 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 10:43:17.967  5978  5978 V BluetoothAdapterState: isTurningOff()=false
11-24 10:43:17.967  5978  5978 V BluetoothAdapterState: isTurningOn()=true
11-24 10:43:17.967  5978  5978 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:17.967  5978  5978 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:43:17.967  5978  5978 V BluetoothAdapterState: isTurningOff()=false
11-24 10:43:17.967  5978  5978 V BluetoothAdapterState: isTurningOn()=true
,11-24 10:43:17.967  5978  5978 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:17.967  5978  5978 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:43:17.968  5978  5978 V BluetoothAdapterState: isTurningOff()=false
11-24 10:43:17.968  5978  5978 V BluetoothAdapterState: isTurningOn()=true
11-24 10:43:17.968  5978  5978 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:17.968  5978  5978 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 10:43:17.969  5978  5978 V BluetoothAdapterState: isTurningOff()=false
11-24 10:43:17.969  5978  5978 V BluetoothAdapterState: isTurningOn()=true
11-24 10:43:17.969  5978  5978 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:17.969  5978  5978 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 10:43:17.969  5978  5990 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-24 10:43:17.969  5978  5990 D BluetoothAdapterProperties: ScanMode =  20
11-24 10:43:17.969  5978  5990 D BluetoothAdapterProperties: State =  11
,11-24 10:43:17.970  5978  5990 D BluetoothAdapterProperties: Setting state to 12
11-24 10:43:17.970  5978  5990 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-24 10:43:17.970  5978  5990 I BluetoothAdapterState: Entering OnState
11-24 10:43:17.970  5823  5837 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 10:43:17.971  5823  5838 D BluetoothPan: onBluetoothStateChange on: true
,11-24 10:43:17.971  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-24 10:43:17.971  3205  4067 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 10:43:17.971  5978  5994 D BluetoothAdapterProperties: Scan Mode:21
11-24 10:43:17.972  5978  5994 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 10:43:17.973  3205  5765 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 10:43:17.973  3205  3205 D BluetoothInputDevice: Proxy object connected
11-24 10:43:17.973  3205  3205 D HidProfile: Bluetooth service connected
11-24 10:43:17.974  5823  5833 D BluetoothPbap: onBluetoothStateChange: up=true
,11-24 10:43:17.975  5766  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 10:43:17.975  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:43:17.975  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:43:17.975  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 10:43:17.975  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 10:43:17.975  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 10:43:17.975  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 10:43:17.975  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 10:43:17.975  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 10:43:17.976  3205  3219 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-24 10:43:17.976  5766  5766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 10:43:17.978   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 10:43:17.978  3205  3205 D BluetoothA2dp: Proxy object connected
,11-24 10:43:17.980  3205  4067 D BluetoothPan: onBluetoothStateChange on: true
,11-24 10:43:17.980  5978  5978 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 10:43:17.981  5978  5978 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-24 10:43:17.982   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 10:43:17.982  3205  3205 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 10:43:17.982  3205  3205 D PanProfile: Bluetooth service connected
11-24 10:43:17.982  3846  3866 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 10:43:17.982  5978  5978 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 10:43:17.982  3205  3219 D BluetoothMap: onBluetoothStateChange: up=true
,11-24 10:43:17.984  5978  5978 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 10:43:17.985  3205  3205 D BluetoothMap: Proxy object connected
11-24 10:43:17.985  3205  3205 D MapProfile: Bluetooth service connected
11-24 10:43:17.985  5823  5837 D BluetoothMap: onBluetoothStateChange: up=true
,11-24 10:43:17.985  3205  3205 D BluetoothMap: getConnectedDevices()
11-24 10:43:17.985  5978  5978 D ObexServerSockets: Succeed to create listening sockets 
,11-24 10:43:17.985  5978  5978 D ObexServerSockets0: startAccept()
,11-24 10:43:17.985  5978  5978 D ObexServerSockets0: prepareForNewConnect()
11-24 10:43:17.987   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 10:43:17.987   925   942 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 10:43:17.987  5978  5978 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-24 10:43:17.987  5978  5978 D BluetoothSdpJni: SDP Create record success - handle: 0
11-24 10:43:17.988   925   925 D BluetoothA2dp: Proxy object connected
11-24 10:43:17.988  5978  6016 D ObexServerSockets0: Accepting socket connection...
,11-24 10:43:17.988  3205  4072 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 10:43:17.988  5978  6015 D ObexServerSockets0: Accepting socket connection...
,11-24 10:43:17.991  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-24 10:43:17.992  5978  5978 D BluetoothMapService: onReceive
11-24 10:43:17.992  5978  5978 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 10:43:17.992  5978  5978 D BluetoothMapService: STATE_ON
11-24 10:43:17.993  5766  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 10:43:17.993   925   925 I Telecom : BluetoothPhoneService: queryPhoneState
,11-24 10:43:17.994  5978  6017 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 10:43:17.994  5823  5823 D LocalBluetoothProfileManager: Adding local A2DP profile
11-24 10:43:17.995  5978  6017 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-24 10:43:17.995  5978  6017 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-24 10:43:17.999  5823  5823 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-24 10:43:18.005  5823  5823 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 10:43:18.007  5823  5823 D BluetoothA2dp: Proxy object connected
,11-24 10:43:18.010  3635  3635 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 10:43:18.014  5823  5823 D DockEventReceiver: finishStartingService: stopping service
,11-24 10:43:18.017  5978  5978 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-24 10:43:18.017  5978  5978 D ObexServerSockets0: prepareForNewConnect()
11-24 10:43:18.018  3205  3205 D BluetoothPbap: Proxy object connected
11-24 10:43:18.018  3205  3205 D PbapServerProfile: Bluetooth service connected
,11-24 10:43:18.022  5823  5823 D BluetoothPbap: Proxy object connected
,11-24 10:43:18.022  5823  5823 D PbapServerProfile: Bluetooth service connected
,11-24 10:43:18.025  5978  6021 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 10:43:18.038  5978  6025 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 10:43:18.040  5978  6025 I BtOppRfcommListener: Accept thread started.
,11-24 10:43:18.075   925   925 D BluetoothHeadset: Proxy object connected
,11-24 10:43:18.075  3846  3865 D BluetoothHeadset: Proxy object connected
11-24 10:43:18.075   925   925 D BluetoothHeadset: Proxy object connected
11-24 10:43:18.075   925   925 D BluetoothHeadset: Proxy object connected
,11-24 10:43:18.076  3205  4072 D BluetoothHeadset: Proxy object connected
11-24 10:43:18.076  3205  3205 D HeadsetProfile: Bluetooth service connected
,11-24 10:43:18.078   925   942 D BluetoothHeadset: Proxy object connected
,11-24 10:43:18.081   925   942 D BluetoothHeadset: Proxy object connected
,11-24 10:43:18.082  3846  4228 D BluetoothHeadset: Proxy object connected
,11-24 10:43:18.087   925   942 D BluetoothHeadset: Proxy object connected
,11-24 10:43:18.102  5823  5838 D BluetoothHeadset: Proxy object connected
,11-24 10:43:18.103  5823  5823 D HeadsetProfile: Bluetooth service connected
,11-24 10:43:18.615   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 10:43:18.615   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 10:43:19.563   925  3042 D ConnectivityService: handlePromptUnvalidated 101
,11-24 10:43:21.921  5978  5990 D BluetoothAdapterState: Current state: ON, message: 23
,11-24 10:43:21.921  5978  5990 D BluetoothAdapterProperties: Setting state to 13
,11-24 10:43:21.921  5978  5990 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-24 10:43:21.923  5978  5990 D BluetoothAdapterProperties: onBluetoothDisable()
,11-24 10:43:21.925  5978  5990 I BluetoothAdapterState: Entering PendingCommandState
,11-24 10:43:21.929  5978  5978 D BluetoothMapService: onReceive
11-24 10:43:21.929  5978  5978 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 10:43:21.929  5978  5978 D BluetoothMapService: STATE_TURNING_OFF
11-24 10:43:21.930  5978  5978 D BluetoothMapService: MAP Service closeService in
11-24 10:43:21.930  5978  5978 D BluetoothMapMasInstance0: MAP Service shutdown
11-24 10:43:21.930  5978  5978 D ObexServerSockets0: shutdown(block = true)
11-24 10:43:21.931  5978  5978 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 10:43:21.931  5978  6015 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-24 10:43:21.931  5978  5978 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 10:43:21.932  5978  6016 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-24 10:43:21.932  5978  6003 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-24 10:43:21.933  5978  5994 D BluetoothAdapterProperties: Scan Mode:20
11-24 10:43:21.933  5978  5990 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-24 10:43:21.935  5823  5823 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 10:43:21.936  5978  5978 I BtOppRfcommListener: stopping Accept Thread
11-24 10:43:21.936  5978  6025 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-24 10:43:21.937  5766  5766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 10:43:21.937  5766  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 10:43:21.937  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:43:21.937  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:43:21.937  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 10:43:21.937  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 10:43:21.937  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 10:43:21.937  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 10:43:21.937  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 10:43:21.937  5766  5766 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 10:43:21.937  5978  6025 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-24 10:43:21.939  5766  5766 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 10:43:21.939  5766  5766 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 10:43:21.942  5978  5978 D HeadsetService: Received stop request...Stopping profile...
11-24 10:43:21.943  5766  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:43:21.946   925   925 D BluetoothHeadset: Proxy object disconnected
,11-24 10:43:21.947  3846  4229 D BluetoothHeadset: Proxy object disconnected
11-24 10:43:21.947   925   925 D BluetoothHeadset: Proxy object disconnected
11-24 10:43:21.947   925   925 D BluetoothHeadset: Proxy object disconnected
11-24 10:43:21.948  5823  5837 D BluetoothHeadset: Proxy object disconnected
11-24 10:43:21.948  5978  5978 D A2dpService: Received stop request...Stopping profile...
,11-24 10:43:21.949  5978  6010 D A2dpStateMachine: Exit Disconnected: -1
11-24 10:43:21.949  3205  3218 D BluetoothHeadset: Proxy object disconnected
11-24 10:43:21.951   925   925 D BluetoothA2dp: Proxy object disconnected
,11-24 10:43:21.951  5978  5978 D HidService: Received stop request...Stopping profile...
11-24 10:43:21.952  5978  5978 D HidService: Stopping Bluetooth HidService
,11-24 10:43:21.953  5823  5823 D DockEventReceiver: finishStartingService: stopping service
11-24 10:43:21.954  5823  5823 D HeadsetProfile: Bluetooth service disconnected
11-24 10:43:21.955  5823  5823 D BluetoothA2dp: Proxy object disconnected
11-24 10:43:21.955  5823  5823 D BluetoothInputDevice: Proxy object disconnected
11-24 10:43:21.955  5823  5823 D HidProfile: Bluetooth service disconnected
,11-24 10:43:21.957  5978  5978 D HealthService: Received stop request...Stopping profile...
,11-24 10:43:21.959  3635  3635 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 10:43:21.959  3205  3205 D HeadsetProfile: Bluetooth service disconnected
11-24 10:43:21.960  3205  3205 D BluetoothA2dp: Proxy object disconnected
11-24 10:43:21.960  3205  3205 D BluetoothInputDevice: Proxy object disconnected
,11-24 10:43:21.960  3205  3205 D HidProfile: Bluetooth service disconnected
,11-24 10:43:21.960  5978  5978 D PanService: Received stop request...Stopping profile...
11-24 10:43:21.961  3205  3205 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-24 10:43:21.961  3205  3205 D PanProfile: Bluetooth service disconnected
11-24 10:43:21.962  5978  5978 V BluetoothAdapterState: isTurningOff()=true
11-24 10:43:21.962  5978  5978 V BluetoothAdapterState: isTurningOn()=false
,11-24 10:43:21.962  5978  5978 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:21.962  5978  5978 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:43:21.962  5823  5823 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 10:43:21.962  5823  5823 D PanProfile: Bluetooth service disconnected
,11-24 10:43:21.964  5978  5978 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-24 10:43:21.964  5978  5978 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-24 10:43:21.964  5978  5994 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-24 10:43:21.964  5978  6001 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 10:43:21.964  5978  6001 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-24 10:43:21.964  5978  6001 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 10:43:21.964  5978  5994 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-24 10:43:21.965  5978  5978 D BluetoothMapService: Received stop request...Stopping profile...
11-24 10:43:21.965  5978  5978 D BluetoothMapService: stop()
11-24 10:43:21.965  5978  5978 D BluetoothMapAppObserver: deinitObservers()
11-24 10:43:21.965  5978  5978 D BluetoothMapAppObserver: removeReceiver()
11-24 10:43:21.967  5978  5978 V BluetoothAdapterState: isTurningOff()=true
11-24 10:43:21.967  5978  5978 V BluetoothAdapterState: isTurningOn()=false
11-24 10:43:21.967  5978  5978 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:21.967  5978  5978 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:43:21.967  3205  3205 D BluetoothMap: Proxy object disconnected
11-24 10:43:21.968  3205  3205 D MapProfile: Bluetooth service disconnected
11-24 10:43:21.969  5823  5823 D BluetoothMap: Proxy object disconnected
11-24 10:43:21.969  5823  5823 D MapProfile: Bluetooth service disconnected
,11-24 10:43:21.973  5978  6001 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-24 10:43:21.973  5978  6001 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 10:43:21.973  5978  5994 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-24 10:43:21.973  5978  6001 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 10:43:21.974  5978  6001 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 10:43:21.974  5978  6001 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 10:43:21.974  5978  5978 D SapService: Received stop request...Stopping profile...
11-24 10:43:21.974  5978  6001 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 10:43:21.974  5978  5978 V SapService: stop()
,11-24 10:43:21.975  5978  5978 V BluetoothAdapterState: isTurningOff()=true
,11-24 10:43:21.975  5978  5978 V BluetoothAdapterState: isTurningOn()=false
11-24 10:43:21.975  5978  5978 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:21.975  5978  5978 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:43:21.975  5978  5978 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-24 10:43:21.975  5978  5978 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-24 10:43:21.976  5978  5994 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 10:43:21.977  3205  3205 D BluetoothPbap: Proxy object disconnected
11-24 10:43:21.977  3205  3205 D PbapServerProfile: Bluetooth service disconnected
,11-24 10:43:21.978  5978  5978 V BluetoothAdapterState: isTurningOff()=true
,11-24 10:43:21.978  5978  5978 V BluetoothAdapterState: isTurningOn()=false
11-24 10:43:21.978  5978  5978 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:21.978  5978  5978 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:43:21.978  5978  5978 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-24 10:43:21.978  5978  5994 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,11-24 10:43:21.979  5823  5823 D BluetoothPbap: Proxy object disconnected
,11-24 10:43:21.979  5823  5823 D PbapServerProfile: Bluetooth service disconnected
11-24 10:43:21.979  5978  5978 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-24 10:43:21.979  5978  5978 V BluetoothAdapterState: isTurningOff()=true
11-24 10:43:21.979  5978  5978 V BluetoothAdapterState: isTurningOn()=false
11-24 10:43:21.979  5978  5978 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:21.979  5978  5978 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:43:21.980  5978  5978 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-24 10:43:21.980  5978  5978 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-24 10:43:21.981  5978  5978 D BluetoothMapService: MAP Service closeService in
,11-24 10:43:21.981  5978  5978 V BluetoothAdapterState: isTurningOff()=true
11-24 10:43:21.981  5978  5978 V BluetoothAdapterState: isTurningOn()=false
11-24 10:43:21.981  5978  5978 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:21.981  5978  5978 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:43:21.981  5978  5978 D BluetoothMapService: cleanup()
11-24 10:43:21.981  5978  5978 D BluetoothMapService: MAP Service closeService in
11-24 10:43:21.981  5978  5978 V BluetoothAdapterState: isTurningOff()=true
,11-24 10:43:21.981  5978  5978 V BluetoothAdapterState: isTurningOn()=false
11-24 10:43:21.981  5978  5978 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:21.981  5978  5978 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:43:21.982  5978  5990 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-24 10:43:21.983  5978  5990 D BluetoothAdapterProperties: Setting state to 15
11-24 10:43:21.983  5978  5990 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-24 10:43:21.983  5978  5990 I BluetoothAdapterState: Entering BleOnState
,11-24 10:43:21.989  5823  5837 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-24 10:43:21.991  5823  5838 D BluetoothPan: onBluetoothStateChange on: false
11-24 10:43:21.991  3205  4067 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-24 10:43:21.993  3205  5765 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 10:43:21.993  5823  5833 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 10:43:21.993  5823  5837 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 10:43:21.994  3205  3219 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 10:43:21.994   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 10:43:21.994  5823  5838 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 10:43:21.995  3205  3218 D BluetoothPan: onBluetoothStateChange on: false
11-24 10:43:21.995   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 10:43:21.995  3846  3866 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 10:43:21.996  3205  4072 D BluetoothMap: onBluetoothStateChange: up=false
,11-24 10:43:21.996  5823  5833 D BluetoothMap: onBluetoothStateChange: up=false
11-24 10:43:21.996   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 10:43:21.997   925   942 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 10:43:21.997  3205  4067 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 10:43:21.997  5978  5990 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-24 10:43:21.997  5978  5990 D BluetoothAdapterProperties: Setting state to 16
,11-24 10:43:21.997  5978  5990 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-24 10:43:21.998  5978  5990 D BluetoothAdapterProperties: onBleDisable
11-24 10:43:21.998  5978  5990 I BluetoothAdapterState: Entering PendingCommandState
11-24 10:43:21.999  5978  5991 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-24 10:43:21.999  5978  6001 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-24 10:43:21.999  5978  6001 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 10:43:22.000  5978  5994 D BluetoothAdapterProperties: Scan Mode:20
11-24 10:43:22.001  5823  5823 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 10:43:22.002  5766  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:43:22.005  5766  5766 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:43:22.008  3635  3635 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 10:43:22.012  5823  5823 D DockEventReceiver: finishStartingService: stopping service
,11-24 10:43:22.215  5978  5994 I bt_hci  : shut_down
,11-24 10:43:22.226  5978  5998 D bt_hwcfg: hw_epilog_process
,11-24 10:43:22.226  5978  5998 I bt_vendor: low_power_mode_cb
,11-24 10:43:22.230  5978  5998 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-24 10:43:22.230  5978  5998 I bt_vendor: epilog_cb
11-24 10:43:22.230  5978  5998 I bt_hci  : epilog_finished_callback
,11-24 10:43:22.237  5978  5994 I bt_hci_h4: hal_close
,11-24 10:43:22.238  5978  5994 I bt_userial_vendor: device fd = 54 close
,11-24 10:43:22.359  5978  5991 D bt_stack_manager: event_shut_down_stack finished.
,11-24 10:43:22.360  5978  5990 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-24 10:43:22.364  5978  5990 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-24 10:43:22.365  5978  5978 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-24 10:43:22.366  5978  5978 D BtGatt.GattService: Received stop request...Stopping profile...
,11-24 10:43:22.366  5978  5978 D BtGatt.GattService: stop()
,11-24 10:43:22.366  5978  5978 D BtGatt.AdvertiseManager: advertise clients cleared
,11-24 10:43:22.370  5978  5978 V BluetoothAdapterState: isTurningOff()=false
11-24 10:43:22.370  5978  5978 V BluetoothAdapterState: isTurningOn()=false
11-24 10:43:22.370  5978  5978 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:22.370  5978  5978 V BluetoothAdapterState: isBleTurningOff()=true
,11-24 10:43:22.371  5978  5990 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-24 10:43:22.371  5978  5990 D BluetoothAdapterProperties: Setting state to 10
11-24 10:43:22.371  5978  5990 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-24 10:43:22.372  5978  5990 I BluetoothAdapterState: Entering OffState
11-24 10:43:22.373   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-24 10:43:22.387  5978  5978 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-24 10:43:22.387  5978  5978 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-24 10:43:22.387  5978  5978 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-24 10:43:22.390  5978  5991 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-24 10:43:22.397  5978  5978 I art     : System.exit called, status: 0
,11-24 10:43:22.397  5978  5978 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-24 10:43:22.426   925  3901 I ActivityManager: Process com.android.bluetooth (pid 5978) has died
,11-24 10:43:26.918  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:43:26.919  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-24 10:43:26.926  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 10:43:26.926  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@37e2e1d removed from the list
,11-24 10:43:26.926  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 10:43:26.928  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 10:43:26.929  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d410e60 added. We now have 4 listener(s)
,11-24 10:43:26.929  5766  5814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 10:43:26.931  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 10:43:26.931  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d410e60 removed from the list
,11-24 10:43:26.931  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 10:43:26.934  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 10:43:26.934  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5548f19 added. We now have 4 listener(s)
11-24 10:43:26.934  5766  5814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 10:43:28.617   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:43:29.618   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:43:30.619   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:43:31.621   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:43:31.944  5766  5814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:43:31.977   925   942 I ActivityManager: Start proc 6033:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-24 10:43:32.060  6033  6033 D AdapterServiceConfig: Adding HeadsetService
,11-24 10:43:32.060  6033  6033 D AdapterServiceConfig: Adding A2dpService
11-24 10:43:32.061  6033  6033 D AdapterServiceConfig: Adding HidService
11-24 10:43:32.061  6033  6033 D AdapterServiceConfig: Adding HealthService
11-24 10:43:32.061  6033  6033 D AdapterServiceConfig: Adding PanService
11-24 10:43:32.061  6033  6033 D AdapterServiceConfig: Adding GattService
11-24 10:43:32.061  6033  6033 D AdapterServiceConfig: Adding BluetoothMapService
11-24 10:43:32.061  6033  6033 D AdapterServiceConfig: Adding SapService
,11-24 10:43:32.072   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a699937:true
,11-24 10:43:32.072  6033  6033 D BluetoothAdapterState: make() - Creating AdapterState
,11-24 10:43:32.075  6033  6033 I bt_bluedroid: init
,11-24 10:43:32.076  6033  6045 I BluetoothAdapterState: Entering OffState
,11-24 10:43:32.078  6033  6046 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-24 10:43:32.078  6033  6046 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-24 10:43:32.078  6033  6046 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-24 10:43:32.078  6033  6046 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-24 10:43:32.079  6033  6033 I bt_bluedroid: get_profile_interface socket
,11-24 10:43:32.081  6033  6049 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-24 10:43:32.082  6033  6033 I bt_bluedroid: get_profile_interface sdp
11-24 10:43:32.083  6033  6049 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 10:43:32.087  6033  6044 I bt_bluedroid: config_hci_snoop_log
,11-24 10:43:32.089   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-24 10:43:32.093  6033  6045 D BluetoothAdapterState: Current state: OFF, message: 0
11-24 10:43:32.093  6033  6045 D BluetoothAdapterProperties: Setting state to 14
11-24 10:43:32.093  6033  6045 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-24 10:43:32.095  6033  6045 D BluetoothBondStateMachine: make
,11-24 10:43:32.097  6033  6050 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-24 10:43:32.100  6033  6045 I BluetoothAdapterState: Entering PendingCommandState
,11-24 10:43:32.101  6033  6033 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-24 10:43:32.104  6033  6033 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f57f4
,11-24 10:43:32.104  6033  6033 D BtGatt.DebugUtils: handleDebugAction() action=null
11-24 10:43:32.105  6033  6033 D BtGatt.GattService: Received start request. Starting profile...
11-24 10:43:32.105  6033  6033 D BtGatt.GattService: start()
11-24 10:43:32.105  6033  6033 I bt_bluedroid: get_profile_interface gatt
,11-24 10:43:32.106  6033  6033 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f57f4
11-24 10:43:32.106  6033  6033 D BtGatt.AdvertiseManager: advertise manager created
,11-24 10:43:32.112  6033  6033 V BluetoothAdapterState: isTurningOff()=false
11-24 10:43:32.112  6033  6033 V BluetoothAdapterState: isTurningOn()=false
11-24 10:43:32.112  6033  6033 V BluetoothAdapterState: isBleTurningOn()=true
,11-24 10:43:32.112  6033  6033 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 10:43:32.113  6033  6045 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
11-24 10:43:32.114  6033  6045 I bt_bluedroid: bt_bluedroid
11-24 10:43:32.114  6033  6046 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-24 10:43:32.114  6033  6046 I bt_hci  : start_up
,11-24 10:43:32.120  6033  6046 I bt_vendor: alloc value 0xf3eff871
,11-24 10:43:32.120  6033  6046 I bt_vendor: init
11-24 10:43:32.120  6033  6046 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-24 10:43:32.120  6033  6046 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-24 10:43:32.229  6033  6046 D bt_hci  : start_up starting async portion
11-24 10:43:32.230  6033  6053 I bt_hci  : event_finish_startup
11-24 10:43:32.230  6033  6053 I bt_hci_h4: hal_open
,11-24 10:43:32.230  6033  6053 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-24 10:43:32.228  6054  6054 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 10:43:32.233  6033  6053 I bt_userial_vendor: device fd = 54 open
,11-24 10:43:32.249  6033  6053 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 10:43:32.253  6033  6053 D bt_hwcfg: Chipset BCM4358A3
,11-24 10:43:32.254  6033  6053 D bt_hwcfg: Target name = [BCM4358A3]
11-24 10:43:32.254  6033  6053 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-24 10:43:32.623   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:43:32.769  6033  6053 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-24 10:43:32.770  6033  6053 D bt_hwcfg: Settlement delay -- 100 ms
,11-24 10:43:32.770  6033  6053 I bt_hwcfg: Setting fw settlement delay to 100 
,11-24 10:43:32.905  6033  6053 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 10:43:32.905  6033  6053 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,11-24 10:43:32.907  6033  6053 I bt_hwcfg: vendor lib fwcfg completed
,11-24 10:43:32.907  6033  6053 I bt_vendor: firmware callback
,11-24 10:43:32.907  6033  6053 I bt_hci  : firmware_config_callback
,11-24 10:43:32.920  6033  6056 I bt_btu  : btu_task pending for preload complete event
,11-24 10:43:32.920  6033  6056 I bt_btu_task: Bluetooth chip preload is complete
11-24 10:43:32.920  6033  6056 I bt_btu  : btu_task received preload complete event
,11-24 10:43:32.929  6033  6056 I         : BTE_InitTraceLevels -- TRC_HCI
,11-24 10:43:32.929  6033  6056 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-24 10:43:32.929  6033  6056 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-24 10:43:32.929  6033  6056 I         : BTE_InitTraceLevels -- TRC_AVDT
11-24 10:43:32.929  6033  6056 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-24 10:43:32.930  6033  6056 I         : BTE_InitTraceLevels -- TRC_A2D
11-24 10:43:32.930  6033  6056 I         : BTE_InitTraceLevels -- TRC_BNEP
11-24 10:43:32.930  6033  6056 I         : BTE_InitTraceLevels -- TRC_BTM
11-24 10:43:32.930  6033  6056 I         : BTE_InitTraceLevels -- TRC_GAP
11-24 10:43:32.930  6033  6056 I         : BTE_InitTraceLevels -- TRC_PAN
11-24 10:43:32.930  6033  6056 I         : BTE_InitTraceLevels -- TRC_SDP
,11-24 10:43:32.930  6033  6056 I         : BTE_InitTraceLevels -- TRC_GATT
11-24 10:43:32.930  6033  6056 I         : BTE_InitTraceLevels -- TRC_SMP
11-24 10:43:32.930  6033  6056 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-24 10:43:32.930  6033  6056 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-24 10:43:33.030  6033  6056 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3e7d549
,11-24 10:43:33.030  6033  6056 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3e7d549 
,11-24 10:43:33.056  6033  6049 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-24 10:43:33.059  6033  6049 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 10:43:33.060  6033  6049 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-24 10:43:33.063  6033  6049 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 10:43:33.068  6033  6049 D BluetoothAdapterProperties: Scan Mode:20
,11-24 10:43:33.068  6033  6049 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 10:43:33.068  6033  6049 D bt_hci  : do_postload posting postload work item
,11-24 10:43:33.069  6033  6053 I bt_hci  : event_postload
,11-24 10:43:33.069  6033  6053 I bt_vendor: sco_config_cb
11-24 10:43:33.069  6033  6053 I bt_hci  : sco_config_callback postload finished.
11-24 10:43:33.071  6033  6049 D bt_bte_conf: Device ID record 1 : primary
11-24 10:43:33.071  6033  6049 D bt_bte_conf:   vendorId            = 000f
11-24 10:43:33.071  6033  6049 D bt_bte_conf:   vendorIdSource      = 0001
,11-24 10:43:33.071  6033  6049 D bt_bte_conf:   product             = 1200
11-24 10:43:33.071  6033  6049 D bt_bte_conf:   version             = 1436
11-24 10:43:33.071  6033  6049 D bt_bte_conf:   clientExecutableURL = 
11-24 10:43:33.071  6033  6049 D bt_bte_conf:   serviceDescription  = 
11-24 10:43:33.071  6033  6049 D bt_bte_conf:   documentationURL    = 
,11-24 10:43:33.071  6033  6049 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-24 10:43:33.072  6033  6046 D bt_stack_manager: event_start_up_stack finished
11-24 10:43:33.072  6033  6045 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-24 10:43:33.073  6033  6045 D BluetoothAdapterProperties: Setting state to 15
11-24 10:43:33.073  6033  6045 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-24 10:43:33.075  6033  6045 I BluetoothAdapterState: Entering BleOnState
,11-24 10:43:33.079  6033  6053 I bt_vendor: low_power_mode_cb
11-24 10:43:33.079  6033  6045 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-24 10:43:33.080  6033  6045 D BluetoothAdapterProperties: Setting state to 11
,11-24 10:43:33.081  6033  6045 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-24 10:43:33.089  6033  6033 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f57f4
,11-24 10:43:33.090  6033  6033 D HeadsetService: Received start request. Starting profile...
,11-24 10:43:33.093  6033  6033 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-24 10:43:33.093  6033  6033 D HeadsetStateMachine: make
,11-24 10:43:33.103  6033  6033 D HeadsetStateMachine: max_hf_connections = 1
,11-24 10:43:33.103  6033  6033 I bt_bluedroid: get_profile_interface handsfree
11-24 10:43:33.103  6033  6049 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-24 10:43:33.104  6033  6045 I BluetoothAdapterState: Entering PendingCommandState
,11-24 10:43:33.106  6033  6049 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-24 10:43:33.108  6033  6033 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f57f4
,11-24 10:43:33.109  3635  3635 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 10:43:33.110  6033  6033 D A2dpService: Received start request. Starting profile...
11-24 10:43:33.110  6033  6033 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-24 10:43:33.111  6033  6033 I bt_bluedroid: get_profile_interface avrcp
,11-24 10:43:33.116  6033  6033 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-24 10:43:33.117  6033  6033 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-24 10:43:33.117  6033  6033 D A2dpStateMachine: make
,11-24 10:43:33.118  6033  6033 I bt_bluedroid: get_profile_interface a2dp
,11-24 10:43:33.119  6033  6049 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-24 10:43:33.120  6033  6063 D A2dpStateMachine: Enter Disconnected: -2
11-24 10:43:33.121  6033  6033 I BluetoothHidServiceJni: classInitNative: succeeds
11-24 10:43:33.121  6033  6033 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f57f4
,11-24 10:43:33.123  6033  6033 D HidService: Received start request. Starting profile...
,11-24 10:43:33.123  6033  6033 I bt_bluedroid: get_profile_interface hidhost
11-24 10:43:33.123  6033  6049 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3e5e56d
11-24 10:43:33.123  6033  6033 D HidService: setHidService(): set to: null
11-24 10:43:33.123  6033  6049 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-24 10:43:33.123  6033  6033 I BluetoothHealthServiceJni: classInitNative: succeeds
11-24 10:43:33.124  6033  6033 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f57f4
11-24 10:43:33.125  6033  6033 D HealthService: Received start request. Starting profile...
,11-24 10:43:33.126  6033  6033 I bt_bluedroid: get_profile_interface health
11-24 10:43:33.127  6033  6033 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-24 10:43:33.128  6033  6033 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f57f4
,11-24 10:43:33.129  6033  6033 D PanService: Received start request. Starting profile...
11-24 10:43:33.129  6033  6033 D BluetoothPanServiceJni: initializeNative(L110): pan
11-24 10:43:33.129  6033  6033 I bt_bluedroid: get_profile_interface pan
11-24 10:43:33.130  6033  6049 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-24 10:43:33.133  6033  6033 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f57f4
,11-24 10:43:33.134  6033  6033 D BluetoothMapService: Received start request. Starting profile...
11-24 10:43:33.134  6033  6033 D BluetoothMapService: start()
,11-24 10:43:33.137  6033  6033 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-24 10:43:33.138  6033  6033 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-24 10:43:33.138  6033  6033 D BluetoothMapAppObserver: createReceiver()
,11-24 10:43:33.139  6033  6033 D BluetoothMapAppObserver: initObservers()
11-24 10:43:33.139  6033  6033 D BluetoothMapAppObserver: getEnabledAccountItems()
11-24 10:43:33.145  6033  6033 V SapService: SapBinder()
11-24 10:43:33.145  6033  6033 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f57f4
,11-24 10:43:33.146  6033  6033 D SapService: Received start request. Starting profile...
11-24 10:43:33.146  6033  6033 V SapService: start()
11-24 10:43:33.147  6033  6033 V BluetoothAdapterState: isTurningOff()=false
11-24 10:43:33.147  6033  6033 V BluetoothAdapterState: isTurningOn()=true
11-24 10:43:33.147  6033  6033 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:33.147  6033  6033 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:43:33.147  6033  6061 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-24 10:43:33.148  6033  6033 V BluetoothAdapterState: isTurningOff()=false
11-24 10:43:33.148  6033  6033 V BluetoothAdapterState: isTurningOn()=true
11-24 10:43:33.148  6033  6033 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:33.148  6033  6033 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:43:33.148  6033  6033 V BluetoothAdapterState: isTurningOff()=false
,11-24 10:43:33.148  6033  6033 V BluetoothAdapterState: isTurningOn()=true
11-24 10:43:33.148  6033  6033 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:33.148  6033  6033 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:43:33.148  6033  6033 V BluetoothAdapterState: isTurningOff()=false
11-24 10:43:33.148  6033  6033 V BluetoothAdapterState: isTurningOn()=true
11-24 10:43:33.148  6033  6033 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:33.148  6033  6033 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:43:33.149  6033  6033 V BluetoothAdapterState: isTurningOff()=false
11-24 10:43:33.149  6033  6033 V BluetoothAdapterState: isTurningOn()=true
11-24 10:43:33.149  6033  6033 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:33.149  6033  6033 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:43:33.149  6033  6033 V BluetoothAdapterState: isTurningOff()=false
11-24 10:43:33.149  6033  6033 V BluetoothAdapterState: isTurningOn()=true
11-24 10:43:33.149  6033  6033 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:33.149  6033  6033 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 10:43:33.150  6033  6033 V BluetoothAdapterState: isTurningOff()=false
11-24 10:43:33.150  6033  6033 V BluetoothAdapterState: isTurningOn()=true
11-24 10:43:33.150  6033  6033 V BluetoothAdapterState: isBleTurningOn()=false
11-24 10:43:33.150  6033  6033 V BluetoothAdapterState: isBleTurningOff()=false
11-24 10:43:33.150  6033  6045 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-24 10:43:33.150  6033  6045 D BluetoothAdapterProperties: ScanMode =  20
11-24 10:43:33.150  6033  6045 D BluetoothAdapterProperties: State =  11
11-24 10:43:33.150  6033  6045 D BluetoothAdapterProperties: Setting state to 12
11-24 10:43:33.150  6033  6045 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-24 10:43:33.151  6033  6045 I BluetoothAdapterState: Entering OnState
11-24 10:43:33.151  5823  5833 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 10:43:33.153  6033  6049 D BluetoothAdapterProperties: Scan Mode:21
11-24 10:43:33.153  6033  6049 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-24 10:43:33.155  5823  5838 D BluetoothPan: onBluetoothStateChange on: true
,11-24 10:43:33.157  3205  4067 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 10:43:33.159  3205  5765 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 10:43:33.159  3205  3205 D BluetoothInputDevice: Proxy object connected
,11-24 10:43:33.159  3205  3205 D HidProfile: Bluetooth service connected
11-24 10:43:33.159  5823  5837 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 10:43:33.161  5823  5838 D BluetoothPbap: onBluetoothStateChange: up=true
,11-24 10:43:33.162  3205  3218 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-24 10:43:33.164  6033  6033 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 10:43:33.164   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 10:43:33.164  3205  3205 D BluetoothA2dp: Proxy object connected
11-24 10:43:33.164  5823  5837 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 10:43:33.164  6033  6033 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-24 10:43:33.165  5823  5823 D BluetoothInputDevice: Proxy object connected
11-24 10:43:33.165  5823  5823 D HidProfile: Bluetooth service connected
11-24 10:43:33.166  3205  4067 D BluetoothPan: onBluetoothStateChange on: true
11-24 10:43:33.166  6033  6033 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 10:43:33.169  5823  5823 D BluetoothPan: BluetoothPAN Proxy object connected
,11-24 10:43:33.169  5823  5823 D PanProfile: Bluetooth service connected
11-24 10:43:33.169  5823  5823 D BluetoothA2dp: Proxy object connected
11-24 10:43:33.169   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 10:43:33.170  3846  3866 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 10:43:33.170  3205  3205 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 10:43:33.170  3205  3205 D PanProfile: Bluetooth service connected
11-24 10:43:33.170  3205  3219 D BluetoothMap: onBluetoothStateChange: up=true
11-24 10:43:33.171  6033  6033 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 10:43:33.172  5823  5838 D BluetoothMap: onBluetoothStateChange: up=true
,11-24 10:43:33.173  6033  6033 D ObexServerSockets: Succeed to create listening sockets 
,11-24 10:43:33.173  6033  6033 D ObexServerSockets0: startAccept()
11-24 10:43:33.173  6033  6033 D ObexServerSockets0: prepareForNewConnect()
11-24 10:43:33.174   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 10:43:33.174   925   942 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 10:43:33.175   925   925 D BluetoothA2dp: Proxy object connected
11-24 10:43:33.175  3205  4067 D BluetoothPbap: onBluetoothStateChange: up=true
,11-24 10:43:33.176  6033  6033 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-24 10:43:33.176  6033  6033 D BluetoothSdpJni: SDP Create record success - handle: 0
11-24 10:43:33.177  6033  6069 D ObexServerSockets0: Accepting socket connection...
11-24 10:43:33.177  6033  6070 D ObexServerSockets0: Accepting socket connection...
,11-24 10:43:33.179  3205  3205 D BluetoothMap: Proxy object connected
11-24 10:43:33.179  3205  3205 D MapProfile: Bluetooth service connected
11-24 10:43:33.179  3205  3205 D BluetoothMap: getConnectedDevices()
,11-24 10:43:33.179   925   925 I Telecom : BluetoothPhoneService: queryPhoneState
11-24 10:43:33.179  6033  6033 D BluetoothMapService: onReceive
11-24 10:43:33.179  6033  6033 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 10:43:33.180  6033  6033 D BluetoothMapService: STATE_ON
,11-24 10:43:33.182  6033  6072 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 10:43:33.184  5823  5823 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 10:43:33.184  6033  6072 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-24 10:43:33.184  6033  6072 D BluetoothSdpJni: SDP Create record success - handle: 1
11-24 10:43:33.186  5823  5823 D BluetoothMap: Proxy object connected
11-24 10:43:33.186  5823  5823 D MapProfile: Bluetooth service connected
11-24 10:43:33.186  5823  5823 D BluetoothMap: getConnectedDevices()
,11-24 10:43:33.191  3635  3635 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 10:43:33.195  5823  5823 D DockEventReceiver: finishStartingService: stopping service
,11-24 10:43:33.197  5823  5823 D BluetoothPbap: Proxy object connected
11-24 10:43:33.197  5823  5823 D PbapServerProfile: Bluetooth service connected
,11-24 10:43:33.203  6033  6076 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 10:43:33.208  3205  3205 D BluetoothPbap: Proxy object connected
,11-24 10:43:33.208  3205  3205 D PbapServerProfile: Bluetooth service connected
,11-24 10:43:33.218  6033  6033 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-24 10:43:33.218  6033  6033 D ObexServerSockets0: prepareForNewConnect()
,11-24 10:43:33.222  6033  6080 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 10:43:33.224  6033  6080 I BtOppRfcommListener: Accept thread started.
,11-24 10:43:33.261   925   925 D BluetoothHeadset: Proxy object connected
,11-24 10:43:33.261  3846  3865 D BluetoothHeadset: Proxy object connected
11-24 10:43:33.262   925   925 D BluetoothHeadset: Proxy object connected
11-24 10:43:33.262   925   925 D BluetoothHeadset: Proxy object connected
,11-24 10:43:33.262  5823  5833 D BluetoothHeadset: Proxy object connected
,11-24 10:43:33.263  3205  4072 D BluetoothHeadset: Proxy object connected
11-24 10:43:33.263  3205  3205 D HeadsetProfile: Bluetooth service connected
11-24 10:43:33.264  5823  5823 D HeadsetProfile: Bluetooth service connected
11-24 10:43:33.265   925   942 D BluetoothHeadset: Proxy object connected
11-24 10:43:33.265  5823  5838 D BluetoothHeadset: Proxy object connected
11-24 10:43:33.266  5823  5823 D HeadsetProfile: Bluetooth service connected
,11-24 10:43:33.270   925   942 D BluetoothHeadset: Proxy object connected
,11-24 10:43:33.270  3846  4228 D BluetoothHeadset: Proxy object connected
,11-24 10:43:33.274   925   942 D BluetoothHeadset: Proxy object connected
,11-24 10:43:33.624   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 10:43:36.960  5766  5814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 10:43:36.960  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:43:36.960  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:43:36.960  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 10:43:36.960  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 10:43:36.960  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 10:43:36.960  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 10:43:36.960  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 10:43:36.960  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 10:43:36.966  5766  5814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 10:43:36.968  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:43:36.969  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5548f19 removed from the list
11-24 10:43:36.969  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 10:43:36.971  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 10:43:36.971  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ef0bbde added. We now have 4 listener(s)
,11-24 10:43:36.971  5766  5814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 10:43:36.975   925  3287 D WifiService: setWifiEnabled: false pid=5766, uid=10077
,11-24 10:43:36.975   925  3287 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 10:43:38.625   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:43:39.626   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:43:40.627   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:43:41.629   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:43:41.986  5766  5814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 10:43:41.987   925  3913 D WifiService: setWifiEnabled: true pid=5766, uid=10077
11-24 10:43:41.987   925  3913 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 10:43:41.995   505   922 D SoftapController: Softap fwReload - Ok
,11-24 10:43:42.000   505   922 D CommandListener: Setting iface cfg
11-24 10:43:42.001   505   922 D CommandListener: Trying to bring down wlan0
,11-24 10:43:42.005   505   922 D CommandListener: Clearing all IP addresses on wlan0
,11-24 10:43:42.011   925  3037 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 10:43:42.630   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:43:42.696   925  3037 D wifi    : set interface wlan0 flags (UP)
,11-24 10:43:42.696   925  3037 I WifiHAL : Initializing wifi
11-24 10:43:42.697   925  3037 I WifiHAL : Creating socket
,11-24 10:43:42.704   925  3037 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-24 10:43:42.704   925  3037 D wifi    : Did set static halHandle = 0x7f87d91e00
11-24 10:43:42.705   925  3037 D wifi    : halHandle = 0x7f87d91e00, mVM = 0x7fa438d140, mCls = 0x2015fe
11-24 10:43:42.705   925  3037 D wifi    : array field set
11-24 10:43:42.705   925  3037 I WifiNative-HAL: interface[0] = wlan0
11-24 10:43:42.706   925   942 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-24 10:43:42.710   925  6085 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547739999744
,11-24 10:43:42.710   925  6085 D wifi    : waitForHalEvents called, vm = 0x7fa438d140, obj = 0x2015fe, env = 0x7f8a131040
,11-24 10:43:42.769  6086  6086 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-24 10:43:42.791  6086  6086 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 10:43:42.800  6086  6086 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 10:43:42.800  6086  6086 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-24 10:43:42.809   925  3037 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-24 10:43:42.821   925  3037 D WifiConfigStore: Loading config and enabling all networks 
,11-24 10:43:42.838   925  3037 D WifiConfigStore: loaded 0 passpoint configs
,11-24 10:43:42.838   925  3037 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
11-24 10:43:42.839   925  3037 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-24 10:43:42.840   925  3037 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-24 10:43:42.841   925  3037 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-24 10:43:42.841   925  3037 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-24 10:43:42.841   925  3037 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-24 10:43:42.841   925  3037 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-24 10:43:42.845   925  3037 D WifiNative-HAL: Setting external_sim to 1
,11-24 10:43:42.845  5130  5130 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 10:43:42.845   925  3037 D wifi    : setting dfs flag to true, 0x7f88eb4e40
11-24 10:43:42.846   925  3037 D WifiStateMachine: Setting OUI to DA-A1-19
11-24 10:43:42.846   925  3037 D wifi    : setting scan oui 0x7f88eb4e40
11-24 10:43:42.846   925  3037 D WifiHAL : Sending mac address OUI
,11-24 10:43:42.850   925  3037 E native  : do suspend false
,11-24 10:43:42.858   925  3037 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-24 10:43:42.859   505   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-24 10:43:42.859   925   925 D RttService: SCAN_AVAILABLE : 3
11-24 10:43:42.859   925  3145 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-24 10:43:42.861   505   922 D CommandListener: Setting iface cfg
,11-24 10:43:42.865   925  3036 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '161 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 161 Failed to set address (No such device)'
11-24 10:43:42.865   925  3036 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-24 10:43:42.879   925   940 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=243353 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,11-24 10:43:42.880   925  3036 D WifiNative-HAL: p2pGetDeviceAddress
,11-24 10:43:42.881   925  3036 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-24 10:43:43.633   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 10:43:45.969  6086  6086 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 10:43:45.978  6086  6086 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 10:43:45.984  6086  6086 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 10:43:45.990  6086  6086 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 10:43:46.020   925  3037 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-24 10:43:46.021   925  3037 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-24 10:43:46.021   925  3037 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 10:43:46.031   925  3037 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-24 10:43:46.065   925  3037 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-24 10:43:46.067  6086  6086 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-24 10:43:46.511  6086  6086 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-24 10:43:46.553  6086  6086 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-24 10:43:46.554  6086  6086 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-24 10:43:46.566   925  3037 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 10:43:46.567   925  3037 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-24 10:43:46.567   925  3042 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-24 10:43:46.583   925  3037 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 10:43:46.595   505   922 D CommandListener: Setting iface cfg
,11-24 10:43:46.600   925  3037 D WifiStateMachine: Start Dhcp Watchdog 3
,11-24 10:43:46.606   925  6091 D DhcpClient: Receive thread started
,11-24 10:43:46.611   925  3037 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-24 10:43:46.612   925  3042 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-24 10:43:46.612   925  3042 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-24 10:43:46.693   925  3037 E native  : do suspend false
,11-24 10:43:46.706   925  6090 D DhcpClient: Broadcasting DHCPDISCOVER
,11-24 10:43:46.718   925  6091 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,11-24 10:43:46.719   925  6090 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,11-24 10:43:46.721   925  6090 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-24 10:43:46.734   925  6091 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-24 10:43:46.735   925  6090 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-24 10:43:46.739   505   922 D CommandListener: Setting iface cfg
11-24 10:43:46.743   925  3037 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-24 10:43:46.747   925  6090 D DhcpClient: Scheduling renewal in 86399s
,11-24 10:43:46.755   925  3037 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-24 10:43:46.757   925  3037 D WifiConfigStore: No blacklist allowed without epno enabled
11-24 10:43:46.758   925  3042 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-24 10:43:46.760   925  3042 D ConnectivityService: Adding iface wlan0 to network 102
,11-24 10:43:46.767   925  3037 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-24 10:43:46.812   925  3042 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-24 10:43:46.812   925  3042 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-24 10:43:46.815   925  3042 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-24 10:43:46.819   925  3042 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-24 10:43:46.823   925  3042 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-24 10:43:46.829   925  3042 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 10:43:46.833   925  3042 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-24 10:43:46.833   925  3042 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-24 10:43:46.833   925  3042 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-24 10:43:46.833   925  3042 D ConnectivityService:    accepting network in place of null
,11-24 10:43:46.833   925  3037 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-24 10:43:46.833   925  3037 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 10:43:46.834   925  3042 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 10:43:46.843   925  6089 D NetlinkSocketObserver: NeighborEvent{elapsedMs=247317, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 10:43:46.857   505   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 10:43:46.880   505   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 10:43:46.885   925  3042 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
11-24 10:43:46.885   925  3042 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-24 10:43:46.885  3801  3965 W QCNEJ   : |CORE| network available: 102
,11-24 10:43:46.887   925  3042 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,11-24 10:43:46.887  3801  3965 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-24 10:43:46.888   925   942 D Tethering: MasterInitialState.processMessage what=3
11-24 10:43:46.889  3801  3965 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-24 10:43:46.889  3801  3965 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-24 10:43:46.898  5156  5179 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-24 10:43:46.898  5156  5179 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 10:43:46.898  5156  5179 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-24 10:43:46.899  5156  5179 E SarControlService: no key has been found,reset the power
,11-24 10:43:46.899  5156  5193 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,11-24 10:43:46.899  5156  5193 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 10:43:46.899  5156  5193 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 10:43:46.900  5181  5181 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 10:43:46.900  5181  5181 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 10:43:46.904  5156  5193 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 10:43:46.904  5156  5193 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 10:43:46.904  5156  5193 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 10:43:46.905  5181  5181 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 10:43:46.905  5181  5181 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-24 10:43:46.907  5034  5034 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-24 10:43:46.910  3927  3927 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-24 10:43:46.913  5181  5195 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@8fef3b6 HexData = [00000000f003000000000000ffffffff]
11-24 10:43:46.913  5181  5195 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 10:43:46.913  5181  5195 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
11-24 10:43:46.914  3927  3927 D SystemUpdateService: onCreate
11-24 10:43:46.914  5181  5181 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 10:43:46.914  5156  5167 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-24 10:43:46.919  3927  3927 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-24 10:43:46.920  5181  5195 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@8fef3b6 HexData = [00000000f103000000000000ffffffff]
,11-24 10:43:46.920  5181  5195 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 10:43:46.920  5181  5195 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-24 10:43:46.921  5181  5181 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-24 10:43:46.921  5156  5166 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-24 10:43:46.922   925  6088 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-24 10:43:46.931  3927  3927 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-24 10:43:46.937  3927  5525 I iu.UploadsManager: num queued entries: 0
,11-24 10:43:46.937  3927  5525 I iu.UploadsManager: num updated entries: 0
,11-24 10:43:46.938  3927  5525 I iu.SyncManager: NEXT; no task
,11-24 10:43:46.941  3927  6101 I SystemUpdateService: active receiver: enabled
,11-24 10:43:46.944  3927  3927 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 10:43:46.946  3927  3927 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 10:43:46.948  5889  5889 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 10:43:46.952  5889  5889 D SprintDMHelper: simOperator: 
11-24 10:43:46.952  5889  5889 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 10:43:46.973  3927  6101 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 10:43:46.974   925  6088 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Nov 2016 15:43:46 GMT], X-Android-Received-Millis=[1480002226973], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480002226946]}
,11-24 10:43:46.974   925  3042 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-24 10:43:46.974   925  3042 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-24 10:43:46.974   925  3042 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 10:43:46.975   925  3042 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-24 10:43:46.987  3927  6101 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-24 10:43:46.987  3927  6101 I SystemUpdateService: now status is 0 (complete)
11-24 10:43:46.987  3927  6101 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 10:43:46.987  3927  6101 I SystemUpdateService: file has been verified
11-24 10:43:46.987  3927  6101 I SystemUpdateService: OTA package size = 21989297
,11-24 10:43:46.993  3927  6101 I SystemUpdateService: showing system update notification
,11-24 10:43:47.000  5766  5814 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 10:43:47.000  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 10:43:47.000  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 10:43:47.000  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 10:43:47.000  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 10:43:47.000  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 10:43:47.000  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 10:43:47.000  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 10:43:47.000  5766  5814 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 10:43:47.002  5766  5814 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 10:43:47.002  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:43:47.002  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ef0bbde removed from the list
11-24 10:43:47.002  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:43:47.005  5766  5814 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-24 10:43:47.005  5766  5814 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-24 10:43:47.006  3927  3927 D SystemUpdateService: onDestroy
,11-24 10:43:47.008  5766  5814 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a688763 Bundle[{}]
,11-24 10:43:47.009  5766  5814 I io.jxcore.node.LifeCycleMonitor: start: OK
11-24 10:43:47.009  5766  5814 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-24 10:43:47.009  5766  5814 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-24 10:43:47.010  5766  5814 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-24 10:43:47.010  5766  5814 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-24 10:43:47.011  5766  5814 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-24 10:43:47.017  5766  5814 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 168)
,11-24 10:43:47.018  5766  5814 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-24 10:43:47.018  5766  5814 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,11-24 10:43:47.020  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 10:43:47.020  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171d1bf added. We now have 3 listener(s)
,11-24 10:43:47.021  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-24 10:43:47.022  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 10:43:47.022  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 10:43:47.022  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 10:43:47.022  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@418b08c added. We now have 4 listener(s)
11-24 10:43:47.022  5766  5814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 10:43:47.023  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 10:43:47.024  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 10:43:47.024  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9603d5 added. We now have 4 listener(s)
,11-24 10:43:47.025  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-24 10:43:47.026  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 10:43:47.026  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 10:43:47.026  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 10:43:47.026  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc8b7ea added. We now have 5 listener(s)
11-24 10:43:47.026  5766  5814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 10:43:47.026  5766  5814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 10:43:47.026  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:43:47.026  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:43:47.026  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:43:47.027  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:43:47.027  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 10:43:47.027  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@171d1bf removed from the list
11-24 10:43:47.027  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:43:47.027  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@418b08c removed from the list
11-24 10:43:47.027  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 10:43:47.027  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.027  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:43:47.029  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:43:47.029  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.029  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.029  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:43:47.029  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:43:47.029  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:43:47.029  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@418b08c not in the list
11-24 10:43:47.029  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.029  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:43:47.031  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:43:47.031  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.031  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.031  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:43:47.031  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:43:47.031  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:43:47.031  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@cc8b7ea removed from the list
11-24 10:43:47.031  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:43:47.031  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:43:47.031  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 10:43:47.032  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c9603d5 removed from the list
,11-24 10:43:47.032  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 10:43:47.032  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27bcadb added. We now have 3 listener(s)
,11-24 10:43:47.034  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 10:43:47.034  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 10:43:47.034  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 10:43:47.034  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 10:43:47.034  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e64978 added. We now have 4 listener(s)
11-24 10:43:47.034  5766  5814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 10:43:47.035  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 10:43:47.036  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 10:43:47.036  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5400851 added. We now have 4 listener(s)
11-24 10:43:47.037  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 10:43:47.037  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-24 10:43:47.037  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 10:43:47.037  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 10:43:47.037  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7268b6 added. We now have 5 listener(s)
11-24 10:43:47.037  5766  5814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 10:43:47.037  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 10:43:47.037  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 10:43:47.037  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 10:43:47.038  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 10:43:47.038  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-24 10:43:47.039  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 10:43:47.040  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-24 10:43:47.040  5766  5814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 10:43:47.040  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-24 10:43:47.042  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:43:47.042  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 10:43:47.043  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 10:43:47.043  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 10:43:47.043  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 10:43:47.045  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:43:47.045  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 10:43:47.045  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 10:43:47.045  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 10:43:47.045  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 10:43:47.045  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:43:47.046  5766  5814 D BluetoothAdapter: STATE_ON
,11-24 10:43:47.047  6033  6043 D BtGatt.GattService: registerClient() - UUID=17f2451e-8dbd-45b2-b497-8f9899c1379f
,11-24 10:43:47.048  6033  6049 D BtGatt.GattService: onClientRegistered() - UUID=17f2451e-8dbd-45b2-b497-8f9899c1379f, clientIf=5
,11-24 10:43:47.048  5766  5777 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 10:43:47.049  6033  6068 D BtGatt.GattService: start scan with filters
,11-24 10:43:47.051  6033  6052 D BtGatt.ScanManager: handling starting scan
11-24 10:43:47.052  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 10:43:47.052  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.052  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-24 10:43:47.052  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.052  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 10:43:47.052  5766  5766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 10:43:47.052  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-24 10:43:47.052  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 10:43:47.052  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 10:43:47.052  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.052  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.053  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.053  6033  6052 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@c9f57f4
11-24 10:43:47.053  5766  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.053  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 10:43:47.053  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:43:47.054  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:43:47.054  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 10:43:47.054  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.054  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.054  5766  5814 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-24 10:43:47.054  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 10:43:47.054  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.054  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 10:43:47.055  5766  5814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 10:43:47.055  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 10:43:47.055  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:43:47.055  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-24 10:43:47.059  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.060  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.060  6033  6049 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 10:43:47.060  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.060  6033  6049 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:43:47.060  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 10:43:47.060  5766  5766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-24 10:43:47.060  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.060  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 10:43:47.060  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 10:43:47.060  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.060  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.060  6033  6052 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 10:43:47.060  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.060  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 10:43:47.060  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.061  5766  5814 D BluetoothAdapter: STATE_ON
11-24 10:43:47.061  6033  6068 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 10:43:47.061  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 10:43:47.061  5766  5814 D BluetoothAdapter: STATE_ON
11-24 10:43:47.062  6033  6071 D BtGatt.GattService: stopScan() - queue size =1
,11-24 10:43:47.064  6033  6049 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-24 10:43:47.064  6033  6049 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:43:47.065  6033  6052 D BtGatt.ScanManager: Starting BLE batch scan
,11-24 10:43:47.065  6033  6052 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 10:43:47.065  6033  6043 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 10:43:47.066  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 10:43:47.066  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.066  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 10:43:47.066  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.066  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:43:47.066  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.066  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.066  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 10:43:47.066  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.066  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.066  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.066  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 10:43:47.066  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-24 10:43:47.067  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 10:43:47.067  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:43:47.068  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:43:47.068  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 10:43:47.068  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.068  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.068  5766  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 10:43:47.068  5766  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 10:43:47.069  5766  5766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 10:43:47.069  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.069  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 10:43:47.069  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 10:43:47.069  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-24 10:43:47.069  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.069  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.069  5766  5766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 10:43:47.070  5766  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.070  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.070  5766  5814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:43:47.070  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:43:47.070  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:43:47.070  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:43:47.070  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:43:47.070  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-24 10:43:47.071  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@27bcadb removed from the list
11-24 10:43:47.071  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:43:47.071  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e64978 removed from the list
11-24 10:43:47.071  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:43:47.071  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.071  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.071  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.071  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.071  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.072  6033  6049 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 10:43:47.072  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.073  6033  6049 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 10:43:47.073  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.073  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.073  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:43:47.073  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:43:47.073  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 10:43:47.073  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6e64978 not in the list
,11-24 10:43:47.073  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.073  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.074  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.074  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.074  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.074  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:43:47.074  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:43:47.074  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:43:47.074  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e7268b6 removed from the list
11-24 10:43:47.074  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:43:47.074  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:43:47.074  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 10:43:47.074  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5400851 removed from the list
,11-24 10:43:47.075  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 10:43:47.075  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8d6ba53 added. We now have 3 listener(s)
11-24 10:43:47.076  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 10:43:47.076  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 10:43:47.076  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 10:43:47.076  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 10:43:47.076  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f64cf90 added. We now have 4 listener(s)
11-24 10:43:47.076  5766  5814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 10:43:47.077  6033  6049 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 10:43:47.077  6033  6049 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 10:43:47.077  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 10:43:47.078  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 10:43:47.078  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e8a7089 added. We now have 4 listener(s)
11-24 10:43:47.078  6033  6052 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 10:43:47.079  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-24 10:43:47.079  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-24 10:43:47.079  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 10:43:47.079  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 10:43:47.080  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@231d88e added. We now have 5 listener(s)
11-24 10:43:47.080  5766  5814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 10:43:47.080  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 10:43:47.080  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 10:43:47.080  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 10:43:47.080  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 10:43:47.080  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 10:43:47.081  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-24 10:43:47.082  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 10:43:47.082  6033  6049 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 10:43:47.082  6033  6049 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:43:47.083  6033  6049 E BtGatt.ContextMap: Context not found for ID 5
11-24 10:43:47.084  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 10:43:47.084  5766  5814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 10:43:47.084  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-24 10:43:47.088  6033  6049 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-24 10:43:47.088  6033  6049 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:43:47.088  6033  6052 D BtGatt.ScanManager: stopping BLe Batch
,11-24 10:43:47.090  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:43:47.090  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 10:43:47.091  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-24 10:43:47.091  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 10:43:47.091  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 10:43:47.091  5130  6106 I Babel   : connection state changed from DISCONNECTED to CONNECTED
11-24 10:43:47.092  6033  6049 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 10:43:47.092  6033  6049 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:43:47.092  6033  6052 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 10:43:47.094  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:43:47.094  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-24 10:43:47.094  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-24 10:43:47.094  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 10:43:47.094  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 10:43:47.094  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.096  5766  5814 D BluetoothAdapter: STATE_ON
11-24 10:43:47.097  6033  6049 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 10:43:47.097  6033  6049 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:43:47.098  6033  6068 D BtGatt.GattService: registerClient() - UUID=46572750-e865-481c-bf8e-36e3fa29f561
11-24 10:43:47.098  6033  6049 D BtGatt.GattService: onClientRegistered() - UUID=46572750-e865-481c-bf8e-36e3fa29f561, clientIf=5
,11-24 10:43:47.099  5766  5777 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 10:43:47.099  6033  6071 D BtGatt.GattService: start scan with filters
11-24 10:43:47.100  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 10:43:47.100  6033  6052 D BtGatt.ScanManager: handling starting scan
,11-24 10:43:47.100  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.101  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-24 10:43:47.101  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.101  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 10:43:47.101  5766  5766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 10:43:47.101  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.101  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 10:43:47.101  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 10:43:47.101  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.101  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.101  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.101  5766  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-24 10:43:47.102  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 10:43:47.102  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:43:47.104  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:43:47.104  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 10:43:47.104  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.104  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.104  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.104  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 10:43:47.104  5766  5814 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-24 10:43:47.104  5766  5814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:43:47.104  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:43:47.104  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:43:47.105  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 10:43:47.105  5766  5814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 10:43:47.105  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 10:43:47.105  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:43:47.105  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 10:43:47.105  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8d6ba53 removed from the list
11-24 10:43:47.105  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:43:47.105  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f64cf90 removed from the list
11-24 10:43:47.105  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:43:47.105  5766  5814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 10:43:47.105  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 10:43:47.105  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-24 10:43:47.105  5766  5814 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-24 10:43:47.106  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.106  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.106  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.106  5766  5766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 10:43:47.108  6033  6049 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 10:43:47.108  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-24 10:43:47.108  6033  6049 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:43:47.108  5766  5814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 10:43:47.108  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-24 10:43:47.108  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.108  6033  6052 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 10:43:47.109  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.109  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.109  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.109  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:43:47.109  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:43:47.109  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:43:47.109  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f64cf90 not in the list
11-24 10:43:47.109  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 10:43:47.109  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.109  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 10:43:47.109  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 10:43:47.109  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.109  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.109  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.109  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 10:43:47.109  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.110  5766  5814 D BluetoothAdapter: STATE_ON
11-24 10:43:47.110  6033  6044 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 10:43:47.110  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 10:43:47.111  5766  5814 D BluetoothAdapter: STATE_ON
11-24 10:43:47.111  6033  6071 D BtGatt.GattService: stopScan() - queue size =1
11-24 10:43:47.112  6033  6044 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 10:43:47.112  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 10:43:47.112  6033  6049 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 10:43:47.112  6033  6049 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:43:47.112  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.112  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 10:43:47.112  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.112  6033  6052 D BtGatt.ScanManager: Starting BLE batch scan
11-24 ,10:43:47.112  6033  6052 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 10:43:47.112  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.112  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.112  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.112  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 10:43:47.112  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.112  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.112  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.112  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 10:43:47.112  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 10:43:47.113  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 10:43:47.113  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.114  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.114  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 10:43:47.114  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.114  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.114  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:43:47.114  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:43:47.114  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:43:47.114  5766  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 10:43:47.114  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@231d88e removed from the list
11-24 10:43:47.115  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:43:47.115  5766  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 10:43:47.115  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:43:47.115  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 10:43:47.115  5766  5766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 10:43:47.115  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e8a7089 removed from the li,st
11-24 10:43:47.115  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.115  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 10:43:47.115  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 10:43:47.115  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.115  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.115  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.115  5766  5766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 10:43:47.115  5766  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.115  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.115  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 10:43:47.115  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c120cb added. We now have 3 listener(s)
11-24 10:43:47.116  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 10:43:47.116  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.116  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 10:43:47.116  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 10:43:47.116  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.116  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.116  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 10:43:47.117  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@93b00a8 added. We now have 4 listener(s)
11-24 10:43:47.117  5766  5814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 10:43:47.117  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 10:43:47.117  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 10:43:47.117  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@242a7c1 added. We now have 4 listener(s)
11-24 10:43:47.118  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 10:43:47.118  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 10:43:47.118  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 10:43:47.118  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 10:43:47.119  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c46b66 added. We now have 5 listener(s)
11-24 10:43:47.119  5766  5814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 10:43:47.119  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 10:43:47.119  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 10:43:47.119  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 10:43:47.119  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 10:43:47.119  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-24 10:43:47.120  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 10:43:47.120  6033  6049 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 10:43:47.121  6033  6049 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:43:47.121  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 10:43:47.121  5766  5814 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 10:43:47.121  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 10:43:47.124  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.124  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 10:43:47.125  6033  6049 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 10:43:47.125  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 10:43:47.125  6033  6049 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:43:47.125  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 10:43:47.125  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 10:43:47.126  6033  6052 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 10:43:47.127  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.127  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 10:43:47.127  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 10:43:47.127  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 10:43:47.127  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 10:43:47.127  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.128  5766  5814 D BluetoothAdapter: STATE_ON
11-24 10:43:47.129  6033  6044 D BtGatt.GattService: registerClient() - UUID=f2f4afff-2caf-40ba-9ffa-b18433158c1e
11-24 10:43:47.130  6033  6049 D BtGatt.GattService: onClientRegistered() - UUID=f2f4afff-2caf-40ba-9ffa-b18433158c1e, clientIf=5
11-24 10:43:47.130  6033  6049 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 10:43:47.130  6033  6049 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:43:47.130  5766  5777 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 10:43:47.130  6033  6043 D BtGatt.GattService: start scan with filters
11-24 10:43:47.135  6033  6049 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 10:43:47.135  6033  6049 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:43:47.135  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 10:43:47.135  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.135  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 10:43:47.135  6033  6052 D BtGatt.ScanManager: stopping BLe Batch
11-24 10:43:47.136  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.136  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 10:43:47.136  5766  5766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 10:43:47.136  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.136  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 10:43:47.136  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 10:43:47.136  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.136  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.136  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.136  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.136  5766  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.137  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 10:43:47.137  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.139  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.139  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 10:43:47.139  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.139  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.139  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.140  6033  6049 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 10:43:47.140  6033  6049 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:43:47.140  6033  6052 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 10:43:47.142  5766  5814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:43:47.142  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:43:47.142  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:43:47.142  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:43:47.142  5766  5814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 10:43:47.142  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 10:43:47.142  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:43:47.142  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 10:43:47.143  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c120cb removed from the list
11-24 10:43:47.143  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:43:47.143  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@93b00a8 removed from the list
11-24 10:43:47.143  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:43:47.143  5766  5814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 10:43:47.143  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 10:43:47.143  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.143  5766  5814 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-24 10:43:47.143  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-24 10:43:47.143  5766  5814 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 10:43:47.143  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 10:43:47.143  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.144  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.144  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.144  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.144  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.144  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.144  5766  5766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 10:43:47.144  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.144  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:43:47.144  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:43:47.144  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:43:47.144  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@93b00a8 not in the list
11-24 10:43:47.144  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 10:43:47.144  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.144  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 10:43:47.144  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 10:43:47.144  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.144  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.144  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.144  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 10:43:47.144  6033  6049 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 10:43:47.144  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.144  6033  6049 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:43:47.145  5766  5814 D BluetoothAdapter: STATE_ON
11-24 10:43:47.145  6033  6068 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 10:43:47.145  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 10:43:47.146  6033  6052 D BtGatt.ScanManager: handling starting scan
11-24 10:43:47.146  5766  5814 D BluetoothAdapter: STATE_ON
11-24 10:43:47.146  6033  6044 D BtGatt.GattService: stopScan() - queue size =0
11-24 10:43:47.147  6033  6068 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 10:43:47.147  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 10:43:47.147  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.147  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 10:43:47.147  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.147  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.147  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.147  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.147  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 10:43:47.147  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.147  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.147  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.147  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 10:43:47.148  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-24 10:43:47.148  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 10:43:47.148  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.149  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.149  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 10:43:47.149  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.149  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.149  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:43:47.150  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:43:47.150  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:43:47.150  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5c46b66 removed from the list
11-24 10:43:47.150  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:43:47.150  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:43:47.150  5766  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 10:43:47.150  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 10:43:47.150  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@242a7c1 removed from the list
11-24 10:43:47.150  5766  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 10:43:47.150  5766  5766 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 10:43:47.150  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.150  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 10:43:47.150  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 10:43:47.150  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.150  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.150  5766  5766 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.150  5766  5766 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 10:43:47.150  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 10:43:47.150  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8d2de43 added. We now have 3 listener(s)
11-24 10:43:47.150  5766  5766 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.150  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.151  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.151  6033  6049 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 10:43:47.151  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.151  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 10:43:47.151  6033  6049 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:43:47.151  5766  5766 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 10:43:47.151  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 10:43:47.151  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 10:43:47.152  6033  6052 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 10:43:47.152  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 10:43:47.152  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c533cc0 added. We now have 4 listener(s)
11-24 10:43:47.152  5766  5814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 10:43:47.153  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 10:43:47.154  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 10:43:47.154  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8738df9 added. We now have 4 listener(s)
11-24 10:43:47.155  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 10:43:47.155  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 10:43:47.155  5766  5814 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 10:43:47.155  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 10:43:47.155  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60b813e added. We now have 5 listener(s)
11-24 10:43:47.155  5766  5814 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 10:43:47.155  5766  5814 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 10:43:47.155  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:43:47.155  5766  5814 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 10:43:47.156  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:43:47.156  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:43:47.156  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 10:43:47.156  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8d2de43 removed from the list
11-24 10:43:47.156  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:43:47.156  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c533cc0 removed from the list
11-24 10:43:47.156  6033  6049 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 10:43:47.156  5766  5814 D io.jxcore.node.ConnectivityMonitor: stop
11-24 10:43:47.156  6033  6049 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:43:47.156  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.156  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.156  6033  6052 D BtGatt.ScanManager: Starting BLE batch scan
11-24 10:43:47.156  6033  6052 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 10:43:47.157  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.157  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.157  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.157  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:43:47.157  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:43:47.157  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:43:47.157  5766  5814 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c533cc0 not in the list
11-24 10:43:47.157  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.157  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.158  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.158  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.158  5766  5814 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 10:43:47.158  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 10:43:47.158  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 10:43:47.158  5766  5814 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 10:43:47.159  5766  5814 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@60b813e removed from the list
11-24 10:43:47.159  5766  5814 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 10:43:47.159  5766  5814 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 10:43:47.159  5766  5814 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 10:43:47.159  5766  5814 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8738df9 removed from the list
11-24 10:43:47.159  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-24 10:43:47.159  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-24 10:43:47.159  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-24 10:43:47.160  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 10:43:47.160  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-24 10:43:47.160  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 10:43:47.165  6033  6049 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 10:43:47.165  6033  6049 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:43:47.169  6033  6049 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 10:43:47.169  6033  6049 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:43:47.170  6033  6052 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 10:43:47.173  6033  6049 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 10:43:47.173  6033  6049 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:43:47.173  6033  6049 E BtGatt.ContextMap: Context not found for ID 5
11-24 10:43:47.178  6033  6049 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 10:43:47.178  6033  6049 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:43:47.178  6033  6052 D BtGatt.ScanManager: stopping BLe Batch
11-24 10:43:47.183  6033  6049 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 10:43:47.183  6033  6049 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 10:43:47.183  6033  6052 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 10:43:47.187  6033  6049 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 10:43:47.187  6033  6049 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 10:43:47.570  5766  5766 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 10:43:47.616  5766  5766 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 10:43:47.651  5766  5766 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 10:43:49.313  5766  6113 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 10:43:49.313  5766  6113 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 10:43:50.122  5766  6113 W !!      : call onHalfStreamCopied
,11-24 10:43:50.123  5766  6113 I testCopyDataAndClose: closing input stream
,11-24 10:43:50.900  5766  6113 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 177, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 10:43:50.900  5766  6113 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 10:43:50.900  5766  6113 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 10:43:50.900  5766  6113 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 10:43:50.900  5766  6113 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 10:43:50.900  5766  6113 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 10:43:50.900  5766  6113 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-24 10:43:50.901  5766  6113 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 10:43:50.901  5766  6113 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-24 10:43:50.901  5766  6113 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 10:43:50.901  5766  6113 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-24 10:43:53.634   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:43:54.635   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:43:54.693  5766  6114 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-24 10:43:54.693  5766  6114 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 10:43:54.838   925  3042 D ConnectivityService: handlePromptUnvalidated 102
,11-24 10:43:55.637   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:43:56.638   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:43:56.693  5766  5814 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 180. Connection data: Peer properties: [null null].
11-24 10:43:56.693  5766  5814 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 10:43:56.693  5766  5814 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 180, name: My test thread name)
,11-24 10:43:56.740  5766  6114 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-24 10:43:56.740  5766  6114 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-24 10:43:56.740  5766  6114 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 132 and the total number of bytes written 132
,11-24 10:43:56.841  5766  6115 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 10:43:56.841  5766  6115 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 10:43:57.639   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:43:57.881   925  3037 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 15, 16 -> obsolete
,11-24 10:43:58.482  5766  6115 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 182, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 10:43:58.482  5766  6115 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 10:43:58.482  5766  6115 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 10:43:58.482  5766  6115 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 10:43:58.482  5766  6115 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 10:43:58.483  5766  6115 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 10:43:58.483  5766  6115 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-24 10:43:58.483  5766  6115 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 10:43:58.483  5766  6115 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-24 10:43:58.483  5766  6115 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 10:43:58.483  5766  6115 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-24 10:43:58.640   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-24 10:44:02.339  5766  6116 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-24 10:44:02.339  5766  6116 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 10:44:02.339  5766  6116 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 184, thread name: My test thread name). Connection data: Peer properties: [null null].
11-24 10:44:02.339  5766  6116 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 10:44:02.339  5766  6116 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 10:44:02.339  5766  6116 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 10:44:02.340  5766  6116 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 10:44:02.340  5766  6116 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 10:44:02.340  5766  6116 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-24 10:44:02.340  5766  6116 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 10:44:02.340  5766  6116 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-24 10:44:02.340  5766  6116 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-24 10:44:02.340  5766  6116 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-24 10:44:02.342  5766  5814 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-24 10:44:02.345  5766  6117 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-24 10:44:02.345  5766  6117 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 10:44:02.345  5766  6117 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 188, thread name: My test thread name): Test exception.
11-24 10:44:02.346  5766  6117 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-24 10:44:02.346  5766  6117 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-24 10:44:02.346  5766  6117 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
,11-24 10:44:02.346  5766  6117 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-24 10:44:02.346  5766  6117 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-24 10:44:02.351  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-24 10:44:02.351  5766  5814 I jxcore-log: 
,11-24 10:44:02.351  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-24 10:44:02.351  5766  5814 I jxcore-log: 
11-24 10:44:02.351  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-24 10:44:02.351  5766  5814 I jxcore-log: 
11-24 10:44:02.352  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-24 10:44:02.352  5766  5814 I jxcore-log: 
,11-24 10:44:02.352  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG UnitTest_app: 'Total duration:  90885'
11-24 10:44:02.352  5766  5814 I jxcore-log: 
11-24 10:44:02.355  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-24 10:44:02.355  5766  5814 I jxcore-log: 
,11-24 10:44:02.359  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 10:44:02.359  5766  5814 I jxcore-log: 
11-24 10:44:02.360  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 10:44:02.360  5766  5814 I jxcore-log: 
11-24 10:44:02.360  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-24 10:44:02.360  5766  5814 I jxcore-log: 
11-24 10:44:02.360  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-24 10:44:02.360  5766  5814 I jxcore-log: 
11-24 10:44:02.361  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 10:44:02.361  5766  5814 I jxcore-log: 
11-24 10:44:02.361  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 10:44:02.361  5766  5814 I jxcore-log: 
11-24 10:44:02.361  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 10:44:02.361  5766  5814 I jxcore-log: 
11-24 10:44:02.361  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 10:44:02.361  5766  5814 I jxcore-log: 
11-24 10:44:02.362  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 10:44:02.362  5766  5814 I jxcore-log: 
,11-24 10:44:02.362  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-24 10:44:02.362  5766  5814 I jxcore-log: 
11-24 10:44:02.362  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-24 10:44:02.362  5766  5814 I jxcore-log: 
11-24 10:44:02.363  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 10:44:02.363  5766  5814 I jxcore-log: 
11-24 10:44:02.363  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 10:44:02.363  5766  5814 I jxcore-log: 
11-24 10:44:02.363  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 10:44:02.363  5766  5814 I jxcore-log: 
11-24 10:44:02.363  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 10:44:02.363  5766  5814 I jxcore-log: 
11-24 10:44:02.363  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 10:44:02.363  5766  5814 I jxcore-log: 
11-24 10:44:02.364  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 10:44:02.364  5766  5814 I jxcore-log: 
11-24 10:44:02.364  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 10:44:02.364  5766  5814 I jxcore-log: 
11-24 10:44:02.364  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 10:44:02.364  5766  5814 I jxcore-log: 
11-24 10:44:02.364  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 10:44:02.364  5766  5814 I jxcore-log: 
,11-24 10:44:02.365  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 10:44:02.365  5766  5814 I jxcore-log: 
11-24 10:44:02.365  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 10:44:02.365  5766  5814 I jxcore-log: 
11-24 10:44:02.365  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 10:44:02.365  5766  5814 I jxcore-log: 
11-24 10:44:02.366  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-24 10:44:02.366  5766  5814 I jxcore-log: 
,11-24 10:44:02.367  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 10:44:02.367  5766  5814 I jxcore-log: 
11-24 10:44:02.367  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-24 10:44:02.367  5766  5814 I jxcore-log: 
11-24 10:44:02.368  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 10:44:02.368  5766  5814 I jxcore-log: 
,11-24 10:44:02.368  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 10:44:02.368  5766  5814 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-24 10:44:02.368  5766  5814 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 10:44:02.368  5766  5814 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-24 10:44:02.369  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 10:44:02.369  5766  5814 I jxcore-log: 
11-24 10:44:02.369  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 10:44:02.369  5766  5814 I jxcore-log: 
11-24 10:44:02.369  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 10:44:02.369  5766  5814 I jxcore-log: 
,11-24 10:44:02.369  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 10:44:02.369  5766  5814 I jxcore-log: 
11-24 10:44:02.370  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 10:44:02.370  5766  5814 I jxcore-log: 
11-24 10:44:02.370  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 10:44:02.370  5766  5814 I jxcore-log: 
,11-24 10:44:02.375  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-24 10:44:02.375  5766  5814 I jxcore-log: 
11-24 10:44:02.375  5766  5814 I jxcore-log: 2016-11-24 15:44:02 - WARN testUtils: 'myNameCallback not set!'
11-24 10:44:02.375  5766  5814 I jxcore-log: 
,11-24 10:44:02.376  5766  5766 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
11-24 10:44:02.376  5766  5766 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-24 10:44:04.478  5766  5814 I jxcore-log: 2016-11-24 15:44:04 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-24 10:44:04.478  5766  5814 I jxcore-log: 
,11-24 10:44:04.479  5766  5814 I jxcore-log: 2016-11-24 15:44:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-24 10:44:04.479  5766  5814 I jxcore-log: 
,11-24 10:44:04.835  5766  5814 I jxcore-log: 2016-11-24 15:44:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-24 10:44:04.835  5766  5814 I jxcore-log: 
,11-24 10:44:04.849  5766  5814 I jxcore-log: 2016-11-24 15:44:04 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-24 10:44:04.849  5766  5814 I jxcore-log: 
,11-24 10:44:05.976  5766  5814 I jxcore-log: 2016-11-24 15:44:05 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-24 10:44:05.976  5766  5814 I jxcore-log: 
,11-24 10:44:06.171  5766  5814 I jxcore-log: 2016-11-24 15:44:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-24 10:44:06.171  5766  5814 I jxcore-log: 
,11-24 10:44:06.177  5766  5814 I jxcore-log: 2016-11-24 15:44:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-24 10:44:06.177  5766  5814 I jxcore-log: 
,11-24 10:44:06.181  5766  5814 I jxcore-log: 2016-11-24 15:44:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-24 10:44:06.181  5766  5814 I jxcore-log: 
,11-24 10:44:06.672  5766  5814 I jxcore-log: 2016-11-24 15:44:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-24 10:44:06.672  5766  5814 I jxcore-log: 
,11-24 10:44:06.717  5766  5814 I jxcore-log: 2016-11-24 15:44:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-24 10:44:06.717  5766  5814 I jxcore-log: 
,11-24 10:44:06.731  5766  5814 I jxcore-log: 2016-11-24 15:44:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-24 10:44:06.731  5766  5814 I jxcore-log: 
,11-24 10:44:06.735  5766  5814 I jxcore-log: 2016-11-24 15:44:06 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-24 10:44:06.735  5766  5814 I jxcore-log: 
,11-24 10:44:07.009  5766  5814 I jxcore-log: 2016-11-24 15:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-24 10:44:07.009  5766  5814 I jxcore-log: 
,11-24 10:44:07.140  5766  5814 I jxcore-log: 2016-11-24 15:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-24 10:44:07.140  5766  5814 I jxcore-log: 
,11-24 10:44:07.515  5766  5814 I jxcore-log: 2016-11-24 15:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-24 10:44:07.515  5766  5814 I jxcore-log: 
,11-24 10:44:07.524  5766  5814 I jxcore-log: 2016-11-24 15:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-24 10:44:07.524  5766  5814 I jxcore-log: 
,11-24 10:44:07.528  5766  5814 I jxcore-log: 2016-11-24 15:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-24 10:44:07.528  5766  5814 I jxcore-log: 
,11-24 10:44:07.533  5766  5814 I jxcore-log: 2016-11-24 15:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-24 10:44:07.533  5766  5814 I jxcore-log: 
,11-24 10:44:07.538  5766  5814 I jxcore-log: 2016-11-24 15:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-24 10:44:07.538  5766  5814 I jxcore-log: 
,11-24 10:44:07.566  5766  5814 I jxcore-log: 2016-11-24 15:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-24 10:44:07.566  5766  5814 I jxcore-log: 
,11-24 10:44:07.602  5766  5814 I jxcore-log: 2016-11-24 15:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-24 10:44:07.602  5766  5814 I jxcore-log: 
,11-24 10:44:07.609  5766  5814 I jxcore-log: 2016-11-24 15:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-24 10:44:07.609  5766  5814 I jxcore-log: 
,11-24 10:44:07.616  5766  5814 I jxcore-log: 2016-11-24 15:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-24 10:44:07.616  5766  5814 I jxcore-log: 
,11-24 10:44:07.631  5766  5814 I jxcore-log: 2016-11-24 15:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-24 10:44:07.631  5766  5814 I jxcore-log: 
,11-24 10:44:07.647  5766  5814 I jxcore-log: 2016-11-24 15:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-24 10:44:07.647  5766  5814 I jxcore-log: 
,11-24 10:44:07.653  5766  5814 I jxcore-log: 2016-11-24 15:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-24 10:44:07.653  5766  5814 I jxcore-log: 
,11-24 10:44:07.658  5766  5814 I jxcore-log: 2016-11-24 15:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-24 10:44:07.658  5766  5814 I jxcore-log: 
,11-24 10:44:07.671  5766  5814 I jxcore-log: 2016-11-24 15:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-24 10:44:07.671  5766  5814 I jxcore-log: 
,11-24 10:44:07.689  5766  5814 I jxcore-log: 2016-11-24 15:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-24 10:44:07.689  5766  5814 I jxcore-log: 
,11-24 10:44:07.704  5766  5814 I jxcore-log: 2016-11-24 15:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-24 10:44:07.704  5766  5814 I jxcore-log: 
,11-24 10:44:07.714  5766  5814 I jxcore-log: 2016-11-24 15:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-24 10:44:07.714  5766  5814 I jxcore-log: 
,11-24 10:44:07.727  5766  5814 I jxcore-log: 2016-11-24 15:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-24 10:44:07.727  5766  5814 I jxcore-log: 
,11-24 10:44:07.737  5766  5814 I jxcore-log: 2016-11-24 15:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-24 10:44:07.737  5766  5814 I jxcore-log: 
,11-24 10:44:07.751  5766  5814 I jxcore-log: 2016-11-24 15:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-24 10:44:07.751  5766  5814 I jxcore-log: 
,11-24 10:44:07.761  5766  5814 I jxcore-log: 2016-11-24 15:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-24 10:44:07.761  5766  5814 I jxcore-log: 
,11-24 10:44:07.768  5766  5814 I jxcore-log: 2016-11-24 15:44:07 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-24 10:44:07.768  5766  5814 I jxcore-log: 
,11-24 10:44:07.788  5766  5814 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-24 10:44:07.789  5766  5814 I jxcore-log: 2016-11-24 15:44:07 - INFO testUtils: 'BLE multiple advertisement supported'
11-24 10:44:07.789  5766  5814 I jxcore-log: 
,11-24 10:44:07.819  5766  5814 I jxcore-log: 2016-11-24 15:44:07 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-24 10:44:07.819  5766  5814 I jxcore-log: 
,11-24 10:44:08.027  5766  5814 I jxcore-log: 2016-11-24 15:44:08 - DEBUG CoordinatedClient: 'connected to the test server'
11-24 10:44:08.027  5766  5814 I jxcore-log: 
,11-24 10:44:13.641   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:44:14.642   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:44:15.644   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:44:16.645   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:44:17.646   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:44:18.647   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 10:44:26.816   925  3037 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 10:44:38.648   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:44:39.650   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:44:40.651   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:44:41.652   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:44:42.653   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:44:43.654   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 10:45:01.034   925   938 I ActivityManager: Start proc 6127:com.google.android.deskclock/u0a66 for broadcast com.google.android.deskclock/com.android.alarmclock.DigitalAppWidgetProvider
,11-24 10:45:01.086  6127  6127 W System  : ClassLoader referenced unknown path: /system/app/PrebuiltDeskClockGoogle/lib/arm64
,11-24 10:45:01.110  6127  6127 I GAv4    : Google Analytics 7.8.95 is starting up. To enable debug logging on a device run:
11-24 10:45:01.110  6127  6127 I GAv4    :   adb shell setprop log.tag.GAv4 DEBUG
11-24 10:45:01.110  6127  6127 I GAv4    :   adb logcat -s GAv4
,11-24 10:45:01.124  6127  6127 W GAv4    : AnalyticsReceiver is not registered or is disabled. Register the receiver for reliable dispatching on non-Google Play devices. See http://goo.gl/8Rd3yj for instructions.
,11-24 10:45:01.130  6127  6127 W GAv4    : CampaignTrackingReceiver is not registered, not exported or is disabled. Installation campaign tracking is not possible. See http://goo.gl/8Rd3yj for instructions.
,11-24 10:45:01.145  6127  6142 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,11-24 10:45:01.218   925  3849 I ActivityManager: Killing 4771:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-24 10:45:06.822   925  3037 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 10:45:08.654   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 10:45:08.655   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 10:45:23.656   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:45:24.658   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:45:25.659   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:45:26.661   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:45:26.823   925  3037 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 10:45:27.662   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:45:28.663   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 10:45:33.664   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:45:34.666   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:45:35.667   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:45:36.669   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:45:37.670   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:45:38.671   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 10:45:48.673   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:45:49.674   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:45:50.676   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:45:51.677   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:45:52.678   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:45:53.679   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-24 10:46:06.828   925  3037 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 10:46:08.680   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:46:09.681   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:46:10.682   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:46:11.683   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:46:12.685   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:46:13.685   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 10:46:26.832   925  3037 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 10:46:33.686   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:46:34.688   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:46:35.689   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:46:36.690   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:46:37.691   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 10:46:38.692   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 10:46:46.835   925  3037 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 10:47:03.693   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 10:47:03.693   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 10:47:19.917  5766  5814 I jxcore-log: 2016-11-24 15:47:19 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-24 10:47:19.917  5766  5814 I jxcore-log: 
,11-24 10:47:20.249  5766  5814 I jxcore-log: 2016-11-24 15:47:20 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 10:47:20.249  5766  5814 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 10:47:20.249  5766  5814 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 10:47:20.249  5766  5814 I jxcore-log: emit@events.js:82:1
11-24 10:47:20.249  5766  5814 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 10:47:20.249  5766  5814 I jxcore-log: emit@events.js:82:1''
11-24 10:47:20.249  5766  5814 I jxcore-log: 
11-24 10:47:20.250  5766  5814 I jxcore-log: 2016-11-24 15:47:20 - DEBUG CoordinatedClient: 'test client failed'
11-24 10:47:20.250  5766  5814 I jxcore-log: 
,11-24 10:47:20.261  5766  5814 I jxcore-log: 2016-11-24 15:47:20 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 10:47:20.261  5766  5814 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 10:47:20.261  5766  5814 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 10:47:20.261  5766  5814 I jxcore-log: emit@events.js:82:1
11-24 10:47:20.261  5766  5814 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 10:47:20.261  5766  5814 I jxcore-log: emit@events.js:82:1''
11-24 10:47:20.261  5766  5814 I jxcore-log: 
,11-24 10:47:20.263  5766  5814 I jxcore-log: 2016-11-24 15:47:20 - DEBUG CoordinatedClient: 'test client failed'
11-24 10:47:20.263  5766  5814 I jxcore-log: 
,11-24 10:47:20.267  5766  5814 I jxcore-log: 2016-11-24 15:47:20 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 10:47:20.267  5766  5814 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 10:47:20.267  5766  5814 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 10:47:20.267  5766  5814 I jxcore-log: emit@events.js:82:1
11-24 10:47:20.267  5766  5814 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 10:47:20.267  5766  5814 I jxcore-log: emit@events.js:82:1''
11-24 10:47:20.267  5766  5814 I jxcore-log: 
11-24 10:47:20.267  5766  5814 I jxcore-log: 2016-11-24 15:47:20 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-24 10:47:20.267  5766  5814 I jxcore-log: 
,11-24 10:47:20.885  6144  6144 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-24 10:47:20.890  6144  6144 D AndroidRuntime: CheckJNI is OFF
,11-24 10:47:20.923  6144  6144 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-24 10:47:20.958  6144  6144 I Radio-JNI: register_android_hardware_Radio DONE
,11-24 10:47:20.975  6144  6144 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-24 10:47:20.985   925   938 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-24 10:47:20.986   925   938 I ActivityManager: Killing 5766:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-24 10:47:21.081   925  3499 I WindowState: WIN DEATH: Window{64b5d7a u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-24 10:47:21.081   925  3895 D GraphicsStats: Buffer count: 2
,11-24 10:47:21.082   925  3038 D WifiService: Client connection lost with reason: 4
,11-24 10:47:21.121   925   938 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-24 10:47:21.121   925   938 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,11-24 10:47:21.123   925   938 E ActivityManager: Failure starting process com.test.thalitest
11-24 10:47:21.123   925   938 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-24 10:47:21.123   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-24 10:47:21.123   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-24 10:47:21.123   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-24 10:47:21.123   925   938 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-24 10:47:21.123   925   938 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-24 10:47:21.123   925   938 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-24 10:47:21.123   925   938 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-24 10:47:21.123   925   938 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-24 10:47:21.123   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-24 10:47:21.123   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-24 10:47:21.123   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-24 10:47:21.123   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-24 10:47:21.123   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-24 10:47:21.123   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-24 10:47:21.123   925   938 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 10:47:21.123   925   938 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-24 10:47:21.123   925   938 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 10:47:21.123   925   938 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-24 10:47:21.124   925   938 I ActivityManager:   Force finishing activity ActivityRecord{c1f0b0e u0 com.test.thalitest/.MainActivity t10}
11-24 10:47:21.124   925   950 I art     : Starting a blocking GC Explicit
,11-24 10:47:21.130   925  3204 W ActivityManager: Spurious death for ProcessRecord{ace66c1 0:com.test.thalitest/u0a77}, curProc for 5766: null
,11-24 10:47:21.134   925   943 W WindowManager: Attempted to add application window with unknown token Token{96a292f ActivityRecord{c1f0b0e u0 com.test.thalitest/.MainActivity t10 f}}.  Aborting.
,11-24 10:47:21.134   925   943 W WindowManager: Token{96a292f ActivityRecord{c1f0b0e u0 com.test.thalitest/.MainActivity t10 f}} already running, starting window not displayed. Unable to add window -- token Token{96a292f ActivityRecord{c1f0b0e u0 com.test.thalitest/.MainActivity t10 f}} is not valid; is your activity running?
11-24 10:47:21.134   925   943 W WindowManager: view not successfully added to wm, removing view
11-24 10:47:21.135   925   943 W WindowManager: Exception when adding starting window
11-24 10:47:21.135   925   943 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{faf7c0 V.E...... R.....ID 0,0-0,0} not attached to window manager
11-24 10:47:21.135   925   943 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
11-24 10:47:21.135   925   943 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
11-24 10:47:21.135   925   943 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
11-24 10:47:21.135   925   943 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
11-24 10:47:21.135   925   943 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
11-24 10:47:21.135   925   943 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 10:47:21.135   925   943 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
11-24 10:47:21.135   925   943 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 10:47:21.135   925   943 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-24 10:47:21.219   925   950 I art     : Explicit concurrent mark sweep GC freed 112041(8MB) AllocSpace objects, 68(2MB) LOS objects, 33% free, 29MB/44MB, paused 1.536ms total 94.575ms
,11-24 10:47:21.241   925   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-24 10:47:21.245  6144  6144 I art     : System.exit called, status: 0
11-24 10:47:21.245  6144  6144 I AndroidRuntime: VM exiting with result code 0.
,11-24 10:47:21.266   925   950 I ActivityManager: Start proc 6154:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,11-24 10:47:21.266   925   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-24 10:47:21.270   925   938 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-24 10:47:21.273  6033  6033 D BluetoothMapAppObserver: onReceive
11-24 10:47:21.273  6033  6033 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-24 10:47:21.278  4179  4265 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-24 10:47:21.279  3751  3751 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-24 10:47:21.285   925  3029 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-24 10:47:21.306  3751  6164 I Keyboard.Facilitator.DecoderInitializer: run()
,11-24 10:47:21.308  3478  6167 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-24 10:47:21.323  3751  6164 I Decoder : createOrResetDecoder
,11-24 10:47:21.337  3846  3846 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-24 10:47:21.351  4624  4624 W kworker/1:3: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 10:47:21.358  4624  4624 W kworker/1:3: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 10:47:21.369  3635  3635 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
11-24 10:47:21.369  3635  3635 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-24 10:47:21.374   925   925 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-24 10:47:21.371  4624  4624 W kworker/1:3: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 10:47:21.384  3867  4018 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
11-24 10:47:21.385   925   937 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,11-24 10:47:21.385   925   937 E PackageManager: Failed to write settings, restoring backup
11-24 10:47:21.385   925   937 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
11-24 10:47:21.385   925   937 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
11-24 10:47:21.385   925   937 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
11-24 10:47:21.385   925   937 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-24 10:47:21.385   925   937 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-24 10:47:21.385   925   937 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 10:47:21.385   925   937 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-24 10:47:21.385   925   937 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 10:47:21.388   925   938 E DropBoxManagerService: Can't write: system_server_wtf
11-24 10:47:21.388   925   938 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
11-24 10:47:21.388   925   938 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 10:47:21.388   925   938 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 10:47:21.388   925   938 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 10:47:21.388   925   938 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 10:47:21.388   925   938 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 10:47:21.388   925   938 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 10:47:21.388   925   938 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
11-24 10:47:21.388   925   938 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
11-24 10:47:21.388   925   938 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
11-24 10:47:21.388   925   938 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
11-24 10:47:21.388   925   938 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-24 10:47:21.388   925   938 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
11-24 10:47:21.388   925   938 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 10:47:21.388   925   938 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-24 10:47:21.388   925   938 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 10:47:21.388   925   938 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 10:47:21.388   925   938 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 10:47:21.388   925   938 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 10:47:21.388   925   938 E DropBoxManagerService: 	... 13 more
,11-24 10:47:21.402   925  3499 I ActivityManager: Start proc 6173:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
--------- beginning of crash
11-24 10:47:21.402  3867  4018 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-24 10:47:21.402  3867  4018 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3867
11-24 10:47:21.402  3867  4018 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-24 10:47:21.402  3867  4018 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-24 10:47:21.402  3867  4018 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-24 10:47:21.402  3867  4018 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-24 10:47:21.402  3867  4018 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-24 10:47:21.402  3867  4018 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-24 10:47:21.402  3867  4018 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-24 10:47:21.402  3867  4018 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-24 10:47:21.402  3867  4018 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-24 10:47:21.402  3867  4018 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-24 10:47:21.402  3867  4018 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 10:47:21.402  3867  4018 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-24 10:47:21.406  3478  3509 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,11-24 10:47:21.407  3635  3635 I ConfigService: onCreate
,11-24 10:47:21.408  3927  6183 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
11-24 10:47:21.408  3927  6183 D AccountUtils: Clearing selected account for com.test.thalitest
11-24 10:47:21.412   925  6185 E DropBoxManagerService: Can't write: system_app_crash
11-24 10:47:21.412   925  6185 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop127.tmp: open failed: EROFS (Read-only file system)
11-24 10:47:21.412   925  6185 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 10:47:21.412   925  6185 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 10:47:21.412   925  6185 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 10:47:21.412   925  6185 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 10:47:21.412   925  6185 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 10:47:21.412   925  6185 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 10:47:21.412   925  6185 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 10:47:21.412   925  6185 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 10:47:21.412   925  6185 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 10:47:21.412   925  6185 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 10:47:21.412   925  6185 E DropBoxManagerService: 	... 5 more
11-24 10:47:21.413   925  3901 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-24 10:47:21.414  3635  6184 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
11-24 10:47:21.414  3635  6184 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 10:47:21.414  3635  6184 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 10:47:21.414  3635  6184 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 10:47:21.414  3635  6184 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 10:47:21.414  3635  6184 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 10:47:21.414  3635  6184 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 10:47:21.414  3635  6184 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 10:47:21.414  3635  6184 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 10:47:21.414  3635  6184 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 10:47:21.414  3635  6184 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 10:47:21.414  3635  6184 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 10:47:21.414  3635  6184 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 10:47:21.414  3635  6184 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 10:47:21.414  3635  6184 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-24 10:47:21.414  3635  6184 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-24 10:47:21.414  3635  6184 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-24 10:47:21.414  3635  6184 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
11-24 10:47:21.414  3635  6184 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
11-24 10:47:21.414  3635  6184 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 10:47:21.414  3635  6184 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 10:47:21.414  3635  6184 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 10:47:21.414  3635  6184 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 10:47:21.414  3635  6184 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 10:47:21.414  3635  6184 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 10:47:21.414  3635  6184 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 10:47:21.414  3635  6184 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 10:47:21.414  3635  6184 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 10:47:21.414  3635  6184 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 10:47:21.414  3635  6184 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 10:47:21.414  3635  6184 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 10:47:21.414  3635  6184 E SQLiteOpenHelper:, 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 10:47:21.414  3635  6184 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-24 10:47:21.414  3635  6184 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-24 10:47:21.414  3635  6184 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-24 10:47:21.414  3635  6184 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
11-24 10:47:21.416  3635  6184 W SQLiteOpenHelper: Opened config.db in read-only mode
11-24 10:47:21.417  3867  4018 I Process : Sending signal. PID: 3867 SIG: 9
,11-24 10:47:21.436  3751  6164 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-24 10:47:21.467  3478  3509 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
11-24 10:47:21.467  3478  3509 E AndroidRuntime: Process: android.process.acore, PID: 3478
11-24 10:47:21.467  3478  3509 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-24 10:47:21.467  3478  3509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-24 10:47:21.467  3478  3509 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
11-24 10:47:21.467  3478  3509 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
11-24 10:47:21.467  3478  3509 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
11-24 10:47:21.467  3478  3509 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
11-24 10:47:21.467  3478  3509 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
11-24 10:47:21.467  3478  3509 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:391)
11-24 10:47:21.467  3478  3509 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
11-24 10:47:21.467  3478  3509 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
11-24 10:47:21.467  3478  3509 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
11-24 10:47:21.467  3478  3509 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 10:47:21.467  3478  3509 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 10:47:21.467  3478  3509 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-24 10:47:21.470   925  6190 E DropBoxManagerService: Can't write: system_app_crash
11-24 10:47:21.470   925  6190 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop128.tmp: open failed: EROFS (Read-only file system)
11-24 10:47:21.470   925  6190 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 10:47:21.470   925  6190 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 10:47:21.470   925  6190 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 10:47:21.470   925  6190 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 10:47:21.470   925  6190 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 10:47:21.470   925  6190 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 10:47:21.470   925  6190 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 10:47:21.470   925  6190 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 10:47:21.470   925  6190 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 10:47:21.470   925  6190 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 10:47:21.470   925  6190 E DropBoxManagerService: 	... 5 more
,11-24 10:47:21.474  3478  6167 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,11-24 10:47:21.475  3478  6167 I Process : Sending signal. PID: 3478 SIG: 9
,11-24 10:47:21.505   925  3028 W InputDispatcher: channel '801d658 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,11-24 10:47:21.505   925  3028 E InputDispatcher: channel '801d658 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
11-24 10:47:21.505   925  3895 D GraphicsStats: Buffer count: 1
11-24 10:47:21.505   925  3913 I WindowState: WIN DEATH: Window{801d658 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
11-24 10:47:21.505   925  3913 W InputDispatcher: Attempted to unregister already unregistered input channel '801d658 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,11-24 10:47:21.521   925  3895 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3867) has died
,11-24 10:47:21.522   925  3895 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
11-24 10:47:21.523   925  3895 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-24 10:47:21.532   925  3847 I ActivityManager: Process android.process.acore (pid 3478) has died
,11-24 10:47:21.532   925  3847 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,11-24 10:47:21.545   925   938 I ActivityManager: Start proc 6192:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-24 10:47:21.585  6192  6192 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 10:47:21.585  6192  6192 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-24 10:47:21.586  6192  6192 D AndroidRuntime: Shutting down VM
,11-24 10:47:21.592  6192  6192 E AndroidRuntime: FATAL EXCEPTION: main
11-24 10:47:21.592  6192  6192 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6192
11-24 10:47:21.592  6192  6192 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-24 10:47:21.592  6192  6192 E AndroidRuntime: 	... 10 more
11-24 10:47:21.595   925  3499 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-24 10:47:21.595   925  6205 E DropBoxManagerService: Can't write: system_app_crash
11-24 10:47:21.595   925  6205 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop129.tmp: open failed: EROFS (Read-only file system)
11-24 10:47:21.595   925  6205 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 10:47:21.595   925  6205 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 10:47:21.595   925  6205 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 10:47:21.595   925  6205 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 10:47:21.595   925  6205 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 10:47:21.595   925  6205 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 10:47:21.595   925  6205 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 10:47:21.595   925  6205 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 10:47:21.595   925  6205 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 10:47:21.595   925  6205 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 10:47:21.595   925  6205 E DropBoxManagerService: 	... 5 more
11-24 10:47:21.596  6192  6192 I Process : Sending signal. PID: 6192 SIG: 9
,11-24 10:47:21.630   925  3204 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6192) has died
,11-24 10:47:21.631   925  3204 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-24 10:47:21.645   925   938 I ActivityManager: Start proc 6206:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-24 10:47:21.695  6206  6206 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 10:47:21.695  6206  6206 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-24 10:47:21.696  6206  6206 D AndroidRuntime: Shutting down VM
,11-24 10:47:21.702  6206  6206 E AndroidRuntime: FATAL EXCEPTION: main
11-24 10:47:21.702  6206  6206 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6206
11-24 10:47:21.702  6206  6206 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-24 10:47:21.702  6206  6206 E AndroidRuntime: 	... 10 more
,11-24 10:47:21.705   925   936 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-24 10:47:21.705   925  6218 E DropBoxManagerService: Can't write: system_app_crash
11-24 10:47:21.705   925  6218 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
11-24 10:47:21.705   925  6218 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 10:47:21.705   925  6218 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 10:47:21.705   925  6218 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 10:47:21.705   925  6218 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 10:47:21.705   925  6218 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 10:47:21.705   925  6218 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 10:47:21.705   925  6218 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 10:47:21.705   925  6218 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 10:47:21.705   925  6218 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 10:47:21.705   925  6218 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 10:47:21.705   925  6218 E DropBoxManagerService: 	... 5 more
11-24 10:47:21.706  6206  6206 I Process : Sending signal. PID: 6206 SIG: 9
,11-24 10:47:21.721   925  3901 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6206) has died
,11-24 10:47:21.722   925  3901 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-24 10:47:21.736   925   938 I ActivityManager: Start proc 6219:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-24 10:47:21.749   382   479 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
