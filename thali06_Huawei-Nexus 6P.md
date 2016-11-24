#### Test 950476159fe9405_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-24 05:21:56.262  5569  5611 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,--------- beginning of system
11-24 05:21:56.434   924  3817 I ActivityManager: Killing 5262:org.codeaurora.ims/1001 (adj 15): empty #17
11-24 05:21:56.639  5569  5621 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
11-24 05:21:56.662  3930  4959 I Icing   : Indexing F030E08B5368E93E2F43DEEC3A6B244C622F15EE from com.google.android.googlequicksearchbox
11-24 05:21:56.678  3930  3930 I ConfigFetchService: fetch service done; releasing wakelock
11-24 05:21:56.679  3930  3930 I ConfigFetchService: stopping self
11-24 05:21:56.709  5619  5619 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-24 05:21:56.712  5619  5619 D AndroidRuntime: CheckJNI is OFF
11-24 05:21:56.734  5619  5619 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-24 05:21:56.743  3930  4959 I Icing   : Indexing done F030E08B5368E93E2F43DEEC3A6B244C622F15EE
11-24 05:21:56.763  5619  5619 I Radio-JNI: register_android_hardware_Radio DONE
11-24 05:21:56.778  5619  5619 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-24 05:21:56.778  5569  5621 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
11-24 05:21:56.781   924  3817 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-24 05:21:56.808   924  3817 I ActivityManager: Start proc 5635:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-24 05:21:56.809  5569  5621 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
11-24 05:21:56.829  5619  5619 D AndroidRuntime: Shutting down VM
,11-24 05:21:57.139   924  3606 I WindowManager: Screenshot max retries 4 of Token{fec27f3 ActivityRecord{5ea7a62 u0 com.test.thalitest/.MainActivity t10}} appWin=Window{58cf3ba u0 Starting com.test.thalitest} drawState=2
,11-24 05:21:57.227  5635  5635 I CordovaLog: Changing log level to DEBUG(3)
,11-24 05:21:57.228  5635  5635 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-24 05:21:57.228  5635  5635 D CordovaActivity: CordovaActivity.onCreate()
,11-24 05:21:57.233  5635  5635 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-24 05:21:57.266  5635  5635 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-24 05:21:57.328  5635  5635 I LibraryLoader: Time to load native libraries: 53 ms (timestamps 9805-9858)
,11-24 05:21:57.328  5635  5635 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-24 05:21:57.364  5635  5635 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {e54e3de}
11-24 05:21:57.364  5635  5635 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-24 05:21:57.365  5635  5635 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-24 05:21:57.368  5635  5635 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-24 05:21:57.369  5635  5635 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-24 05:21:57.404  5635  5635 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-24 05:21:57.424  5635  5635 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-24 05:21:57.424  5635  5635 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-24 05:21:57.424  5635  5635 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-24 05:21:57.424  5635  5635 I Adreno  : Build Date                       : 12/06/15
11-24 05:21:57.424  5635  5635 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-24 05:21:57.424  5635  5635 I Adreno  : Local Branch                     : mybranch17112971
11-24 05:21:57.424  5635  5635 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-24 05:21:57.424  5635  5635 I Adreno  : Remote Branch                    : NONE
11-24 05:21:57.424  5635  5635 I Adreno  : Reconstruct Branch               : NOTHING
,11-24 05:21:57.470   924   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5684b5e:true
,11-24 05:21:57.496   406   406 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[26211]" dev="sockfs" ino=26211 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 05:21:57.496   406   406 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[26211]" dev="sockfs" ino=26211 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 05:21:57.507  5635  5635 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-24 05:21:57.514  5635  5635 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-24 05:21:57.517  5635  5635 D PluginManager: init()
,11-24 05:21:57.520  5635  5635 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-24 05:21:57.545  5635  5635 D CordovaActivity: Started the activity.
,11-24 05:21:57.545  5635  5635 D CordovaActivity: Resumed the activity.
,11-24 05:21:57.546   406   406 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33598]" dev="sockfs" ino=33598 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 05:21:57.546   406   406 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33598]" dev="sockfs" ino=33598 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-24 05:21:57.549  5635  5672 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-24 05:21:57.552  3828  3828 W Binder_9: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[30001]" dev="sockfs" ino=30001 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 05:21:57.556  5635  5635 D CordovaActivity: Paused the activity.
11-24 05:21:57.552  3828  3828 W Binder_9: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[30001]" dev="sockfs" ino=30001 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 05:21:57.558  5635  5659 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-24 05:21:57.582  5635  5672 I OpenGLRenderer: Initialized EGL, version 1.4
,11-24 05:21:57.593  5635  5635 D CordovaActivity: Stopped the activity.
,11-24 05:21:57.665   924   943 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +521ms (total +870ms)
,11-24 05:21:57.685  5635  5635 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-24 05:21:57.695  5635  5635 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5635
,11-24 05:21:57.791  5635  5635 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-24 05:21:58.129  5635  5675 D jxcore_app_log: JniHelper::setJavaVM(0xf553c000), pthread_self() = -579073744
,11-24 05:21:58.148  5635  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-24 05:21:58.148  5635  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-24 05:21:58.148  5635  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-24 05:21:58.148  5635  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-24 05:21:58.148  5635  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
11-24 05:21:58.149  5635  5675 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9f9fd77 added. We now have 1 listener(s)
11-24 05:21:58.158  5635  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,11-24 05:21:58.160  5635  5675 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-24 05:21:58.162  5635  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 05:21:58.162  5635  5675 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 05:21:58.169  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-24 05:21:58.169  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-24 05:21:58.169  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-24 05:21:58.169  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
11-24 05:21:58.169  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-24 05:21:58.169  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-24 05:21:58.169  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-24 05:21:58.169  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-24 05:21:58.169  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-24 05:21:58.169  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-24 05:21:58.169  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-24 05:21:58.169  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-24 05:21:58.169  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-24 05:21:58.169  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-24 05:21:58.169  5635  5675 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e02c102 added. We now have 1 listener(s)
11-24 05:21:58.170  5635  5675 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 05:21:58.176   924  2986 D WifiService: New client listening to asynchronous messages
,11-24 05:21:58.177  5635  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 05:21:58.177  5635  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-24 05:21:58.178  5635  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-24 05:21:58.178  5635  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-24 05:21:58.178  5635  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-24 05:21:58.178  5635  5675 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-24 05:21:58.178  5635  5675 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-24 05:21:58.181  5635  5675 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-24 05:21:58.202  5635  5635 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-24 05:21:58.211  5635  5635 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,11-24 05:21:58.212  5635  5635 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-24 05:21:58.660   924  2980 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 05:21:58.726  5635  5644 I art     : Background sticky concurrent mark sweep GC freed 73375(7MB) AllocSpace objects, 15(760KB) LOS objects, 22% free, 25MB/32MB, paused 1.161ms total 164.770ms
,11-24 05:21:59.455  5635  5644 I art     : Background partial concurrent mark sweep GC freed 60787(6MB) AllocSpace objects, 3(1492KB) LOS objects, 36% free, 27MB/43MB, paused 1.583ms total 104.348ms
,11-24 05:21:59.590  5635  5681 W jxcore-log: Initializing JXcore engine
11-24 05:21:59.590  5635  5681 W jxcore-log: JXcore engine is ready
,11-24 05:21:59.612  5681  5681 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=13015 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-24 05:21:59.612  5681  5681 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[15556]" dev="sockfs" ino=15556 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-24 05:21:59.612  5681  5681 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-24 05:21:59.612  5681  5681 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[33570]" dev="sockfs" ino=33570 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-24 05:21:59.623  5635  5681 W jxcore-log: Starting JXcore engine
,11-24 05:21:59.673  5635  5681 W jxcore-log: Platform android
11-24 05:21:59.673  5635  5681 W jxcore-log: 
,11-24 05:21:59.673  5635  5681 W jxcore-log: Process ARCH arm
11-24 05:21:59.673  5635  5681 W jxcore-log: 
,11-24 05:21:59.859  5635  5681 I jxcore-log: JXcore Cordova bridge is ready!
11-24 05:21:59.859  5635  5681 I jxcore-log: 
11-24 05:21:59.859  5635  5681 W jxcore-log: JXcore engine is started
,11-24 05:21:59.864  5635  5675 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-24 05:21:59.869  5635  5635 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,11-24 05:21:59.870  5635  5635 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-24 05:22:00.942   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 05:22:01.686  3589  3589 I ConfigService: onDestroy
,11-24 05:22:01.943   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 05:22:02.944   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 05:22:03.945   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 05:22:04.946   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 05:22:05.946   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 05:22:09.549  5635  5681 I jxcore-log: 2016-11-24 10:22:09 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-24 05:22:09.549  5635  5681 I jxcore-log: 
,11-24 05:22:09.551  5635  5681 I jxcore-log: 2016-11-24 10:22:09 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-24 05:22:09.551  5635  5681 I jxcore-log: 
,11-24 05:22:09.555  5635  5681 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-24 05:22:09.556  5635  5681 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 05:22:09.556  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 05:22:09.556  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 05:22:09.556  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 05:22:09.556  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 05:22:09.556  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 05:22:09.556  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 05:22:09.556  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 05:22:09.556  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 05:22:09.557  5635  5681 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 05:22:09.560  5635  5681 I jxcore-log: 2016-11-24 10:22:09 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-24 05:22:09.560  5635  5681 I jxcore-log: 
11-24 05:22:09.561  5635  5681 I jxcore-log: 2016-11-24 10:22:09 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-24 05:22:09.561  5635  5681 I jxcore-log: 
,11-24 05:22:09.808  5635  5681 I jxcore-log: 2016-11-24 10:22:09 - DEBUG UnitTest_app: 'Running unit tests'
11-24 05:22:09.808  5635  5681 I jxcore-log: 
11-24 05:22:09.809  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 05:22:09.809  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cde1adf added. We now have 2 listener(s)
11-24 05:22:09.810  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 05:22:09.810  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 05:22:09.810  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 05:22:09.810  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 05:22:09.810  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3b932c added. We now have 2 listener(s)
,11-24 05:22:09.810  5635  5681 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 05:22:09.811  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 05:22:09.814  5635  5681 D executeNativeTests: Running unit tests
,11-24 05:22:09.856  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 05:22:09.856  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4239265 added. We now have 3 listener(s)
11-24 05:22:09.857  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 05:22:09.857  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-24 05:22:09.857  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 05:22:09.857  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 05:22:09.857  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a added. We now have 3 listener(s)
11-24 05:22:09.857  5635  5681 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 05:22:09.857  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 05:22:09.859  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 05:22:09.859  5635  5681 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-24 05:22:09.859  5635  5681 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-24 05:22:09.859  5635  5681 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 05:22:09.860  5635  5681 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-24 05:22:09.860  5635  5681 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-24 05:22:09.860  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 05:22:09.860  5635  5681 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 05:22:09.860  5635  5681 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 05:22:09.860  5635  5681 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 05:22:09.860  5635  5681 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 05:22:09.861  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 05:22:09.861  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 05:22:09.861  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:22:09.861  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:22:09.861  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 05:22:09.861  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4239265 removed from the list
11-24 05:22:09.861  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:09.861  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a removed from the list
11-24 05:22:09.861  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
11-24 05:22:09.861  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:09.862  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:09.862  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:09.862  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:09.862  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:09.862  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 05:22:09.862  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 05:22:09.862  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:09.862  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:09.863  5635  5681 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-24 05:22:09.863  5635  5681 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 05:22:09.864  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 05:22:09.864  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 05:22:09.864  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:22:09.864  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:22:09.864  5635  5681 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4239265 not in the list
11-24 05:22:09.864  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:09.864  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:09.864  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
11-24 05:22:09.864  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:09.864  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:09.864  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:09.864  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:09.864  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:09.864  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 05:22:09.865  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 05:22:09.865  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:09.865  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:09.867  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-24 05:22:09.867  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-24 05:22:09.867  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-24 05:22:09.867  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-24 05:22:09.867  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-24 05:22:09.867  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-24 05:22:09.867  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-24 05:22:09.867  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-24 05:22:09.867  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-24 05:22:09.867  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-24 05:22:09.867  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,11-24 05:22:09.867  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-24 05:22:09.867  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-24 05:22:09.867  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-24 05:22:09.867  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-24 05:22:09.867  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-24 05:22:09.867  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-24 05:22:09.867  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-24 05:22:09.867  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-24 05:22:09.867  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-24 05:22:09.867  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,11-24 05:22:09.867  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-24 05:22:09.867  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-24 05:22:09.867  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-24 05:22:09.868  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-24 05:22:09.868  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-24 05:22:09.868  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-24 05:22:09.868  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-24 05:22:09.868  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
,11-24 05:22:09.868  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-24 05:22:09.868  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-24 05:22:09.868  5635  5681 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 05:22:09.868  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 05:22:09.868  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 05:22:09.868  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:22:09.868  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 05:22:09.868  5635  5681 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4239265 not in the list
11-24 05:22:09.868  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:09.868  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:09.868  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
11-24 05:22:09.868  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:09.868  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:09.869  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:09.869  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:09.869  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:09.869  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 05:22:09.869  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 05:22:09.869  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:09.869  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:09.869  5635  5681 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-24 05:22:09.870  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-24 05:22:09.870  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-24 05:22:09.878  5635  5681 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 05:22:09.878  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 05:22:09.878  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 05:22:09.878  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 05:22:09.878  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 05:22:09.878  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 05:22:09.878  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 05:22:09.878  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 05:22:09.878  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 05:22:09.879  5635  5681 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 05:22:09.879  5635  5681 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 05:22:09.879  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 05:22:09.879  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 05:22:09.879  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,11-24 05:22:09.879  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 05:22:09.879  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 05:22:09.881  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 05:22:09.881  5635  5681 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 05:22:09.881  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 05:22:09.882  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 05:22:09.885  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:09.885  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-24 05:22:09.885  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 05:22:09.886  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 05:22:09.886  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 05:22:09.886  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 05:22:09.887  5635  5681 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-24 05:22:09.888  5635  5681 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-24 05:22:09.888  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:09.888  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 05:22:09.889  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 05:22:09.889  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 05:22:09.889  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 05:22:09.889  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:09.889  5635  5681 D BluetoothAdapter: STATE_ON
11-24 05:22:09.891  4628  4643 D BtGatt.GattService: registerClient() - UUID=2512e577-b683-4452-afe1-22d75d13e0d4
,11-24 05:22:09.892  4628  4702 D BtGatt.GattService: onClientRegistered() - UUID=2512e577-b683-4452-afe1-22d75d13e0d4, clientIf=5
11-24 05:22:09.893  5635  5646 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 05:22:09.894  4628  4858 D BtGatt.GattService: start scan with filters
,11-24 05:22:09.898  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-24 05:22:09.898  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:09.898  4628  4707 D BtGatt.ScanManager: handling starting scan
11-24 05:22:09.898  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 05:22:09.898  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:09.899  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 05:22:09.899  5635  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 05:22:09.899  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-24 05:22:09.899  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-24 05:22:09.899  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 05:22:09.899  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 05:22:09.899  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 05:22:09.899  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 05:22:09.899  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:09.900  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 05:22:09.900  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 05:22:09.900  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:09.900  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 05:22:09.901  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:09.901  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:09.901  4628  4707 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32cd051
11-24 05:22:09.901  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 05:22:09.901  5635  5681 I io.jxcore.node.ConnectionHelper: start: OK
11-24 05:22:09.903  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 05:22:09.903  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 05:22:09.903  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 05:22:09.904  5635  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-24 05:22:09.908  4628  4702 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-24 05:22:09.908  4628  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:22:09.909  4628  4707 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-24 05:22:09.914  4628  4702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 05:22:09.914  4628  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 05:22:09.914  4628  4707 D BtGatt.ScanManager: Starting BLE batch scan
11-24 05:22:09.915  4628  4707 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 05:22:09.924  4628  4702 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-24 05:22:09.924  4628  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 05:22:09.929  4628  4702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 05:22:09.929  4628  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 05:22:10.405  5635  5635 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-24 05:22:10.405  5635  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 05:22:10.405  5635  5635 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 05:22:14.905  5635  5681 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 05:22:14.905  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 05:22:14.906  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 05:22:14.906  5635  5681 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 05:22:14.906  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 05:22:14.906  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:22:14.906  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 05:22:14.906  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 05:22:14.907  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:14.907  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-24 05:22:14.907  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 05:22:14.907  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:14.908  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:14.908  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:14.908  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-24 05:22:14.908  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:14.909  5635  5681 D BluetoothAdapter: STATE_ON
,11-24 05:22:14.910  4628  4858 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-24 05:22:14.910  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-24 05:22:14.912  4628  4707 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 05:22:14.912  5635  5681 D BluetoothAdapter: STATE_ON
,11-24 05:22:14.914  4628  4641 D BtGatt.GattService: stopScan() - queue size =1
11-24 05:22:14.916  4628  4858 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-24 05:22:14.917  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 05:22:14.917  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:14.917  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-24 05:22:14.917  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:14.918  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:14.918  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:14.918  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:14.919  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 05:22:14.920  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:14.920  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:14.920  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:14.920  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 05:22:14.920  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-24 05:22:14.930  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-24 05:22:14.930  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:14.931  4628  4628 D BtGatt.ScanManager: awakened up at time 97461
,11-24 05:22:14.965  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:14.965  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 05:22:14.965  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:14.966  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:14.966  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:22:14.966  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 05:22:14.966  5635  5681 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 05:22:14.966  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-24 05:22:14.966  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 05:22:14.966  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:22:14.966  5635  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 05:22:14.966  5635  5681 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4239265 not in the list
,11-24 05:22:14.966  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 05:22:14.966  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 05:22:14.966  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 05:22:14.966  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 05:22:14.966  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 05:22:14.966  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 05:22:14.967  5635  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 05:22:14.967  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 05:22:14.967  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 05:22:14.966  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:14.968  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 05:22:14.968  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 05:22:14.968  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:14.969  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
11-24 05:22:14.969  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 05:22:14.969  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-24 05:22:14.977  4628  4702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=6
11-24 05:22:14.977  4628  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:22:14.978  4628  4702 D BtGatt.GattService: current time is 97508237778
11-24 05:22:14.978  4628  4702 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -74, 97, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 71, -122, -77, 84, 69, -12, 1, -128, -72, 77, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -71, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -68, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -71, 84, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -67, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-24 05:22:14.980  4628  4702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
,11-24 05:22:14.980  4628  4702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-24 05:22:14.981  4628  4702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-24 05:22:14.981  4628  4702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-24 05:22:14.981  4628  4702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-24 05:22:14.981  4628  4702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-24 05:22:14.987  4628  4702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 05:22:14.988  4628  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 05:22:14.988  4628  4707 D BtGatt.ScanManager: stopping BLe Batch
,11-24 05:22:14.993  4628  4702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 05:22:14.993  4628  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:22:14.993  4628  4707 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 05:22:14.999  4628  4702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 05:22:14.999  4628  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 05:22:15.052  4839  4880 D Finsky  : [180] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-24 05:22:15.054  4839  4839 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-24 05:22:15.056   924  3817 I ActivityManager: Killing 5275:com.android.settings/1000 (adj 15): empty #17
,11-24 05:22:15.467  5635  5635 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 05:22:18.800   924  5396 D NetlinkSocketObserver: NeighborEvent{elapsedMs=101330, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-24 05:22:19.971  5635  5681 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-24 05:22:19.977  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-24 05:22:19.978  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-24 05:22:19.991  5635  5681 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 05:22:19.991  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 05:22:19.991  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 05:22:19.991  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 05:22:19.991  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 05:22:19.991  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 05:22:19.991  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 05:22:19.991  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 05:22:19.991  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 05:22:19.993  5635  5681 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 05:22:19.993  5635  5681 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 05:22:19.994  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 05:22:19.994  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 05:22:19.994  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 05:22:19.994  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 05:22:19.994  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 05:22:19.997  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 05:22:19.998  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 05:22:19.998  5635  5681 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 05:22:19.998  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 05:22:20.000  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 05:22:20.003  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:20.003  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-24 05:22:20.004  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 05:22:20.004  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 05:22:20.004  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 05:22:20.008  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:20.008  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 05:22:20.008  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 05:22:20.008  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 05:22:20.008  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 05:22:20.008  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.009  5635  5681 D BluetoothAdapter: STATE_ON
,11-24 05:22:20.011  4628  4643 D BtGatt.GattService: registerClient() - UUID=5b05c75e-f15b-43f8-a4fc-5a3f4138377a
11-24 05:22:20.012  4628  4702 D BtGatt.GattService: onClientRegistered() - UUID=5b05c75e-f15b-43f8-a4fc-5a3f4138377a, clientIf=5
,11-24 05:22:20.012  5635  5646 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 05:22:20.012  4628  4838 D BtGatt.GattService: start scan with filters
11-24 05:22:20.015  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 05:22:20.016  4628  4707 D BtGatt.ScanManager: handling starting scan
,11-24 05:22:20.016  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:20.016  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 05:22:20.016  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.016  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 05:22:20.016  5635  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 05:22:20.016  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-24 05:22:20.016  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 05:22:20.016  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 05:22:20.017  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 05:22:20.017  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 05:22:20.017  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 05:22:20.017  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 05:22:20.018  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-24 05:22:20.018  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.021  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.021  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 05:22:20.021  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.021  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.021  5635  5681 I io.jxcore.node.ConnectionHelper: start: OK
11-24 05:22:20.022  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 05:22:20.023  4628  4702 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 05:22:20.023  4628  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:22:20.024  4628  4707 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 05:22:20.025  5635  5681 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 05:22:20.025  5635  5681 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-24 05:22:20.025  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 05:22:20.025  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 05:22:20.025  5635  5681 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 05:22:20.025  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 05:22:20.025  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:22:20.025  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 05:22:20.027  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 05:22:20.027  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 05:22:20.027  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 05:22:20.028  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 05:22:20.028  5635  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 05:22:20.028  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.028  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 05:22:20.028  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 05:22:20.028  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.028  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
1,1-24 05:22:20.028  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.028  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 05:22:20.028  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.029  5635  5681 D BluetoothAdapter: STATE_ON
11-24 05:22:20.029  4628  4838 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 05:22:20.030  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 05:22:20.030  5635  5681 D BluetoothAdapter: STATE_ON
11-24 05:22:20.031  4628  4643 D BtGatt.GattService: stopScan() - queue size =1
11-24 05:22:20.031  4628  4702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 05:22:20.031  4628  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:22:20.031  4628  4707 D BtGatt.ScanManager: Starting BLE batch scan
11-24 05:22:20.031  4628  4707 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 05:22:20.032  4628  4858 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 05:22:20.032  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 05:22:20.033  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.033  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 05:22:20.033  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.033  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.033  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.033  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.033  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 05:22:20.033  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.033  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.033  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.033  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 05:22:20.033  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 05:22:20.034  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 05:22:20.034  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.036  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.036  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 05:22:20.036  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.036  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.036  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:22:20.036  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 05:22:20.036  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 05:22:20.036  5635  5681 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 05:22:20.036  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 05:22:20.036  5635  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 05:22:20.036  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:22:20.036  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 05:22:20.036  5635  5681 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4239265 not in the list
11-24 05:22:20.036  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:20.036  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 05:22:20.036  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 05:22:20.036  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:20.036  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
11-24 05:22:20.036  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 05:22:20.036  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 05:22:20.036  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 05:22:20.037  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 05:22:20.037  5635  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 05:22:20.037  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 05:22:20.037  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 05:22:20.038  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 05:22:20.038  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 05:22:20.038  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 05:22:20.039  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.039  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.040  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.040  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.040  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.040  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 05:22:20.040  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 05:22:20.040  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:20.041  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:20.041  5635  5681 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-24 05:22:20.043  4628  4702 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 05:22:20.043  4628  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:22:20.043  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 05:22:20.043  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-24 05:22:20.049  4628  4702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 05:22:20.049  4628  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:22:20.051  4628  4707 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 05:22:20.054  5635  5681 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 05:22:20.054  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 05:22:20.054  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 05:22:20.054  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 05:22:20.054  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 05:22:20.054  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 05:22:20.054  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 05:22:20.054  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 05:22:20.054  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 05:22:20.055  5635  5681 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 05:22:20.055  4628  4702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 05:22:20.055  4628  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:22:20.056  5635  5681 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 05:22:20.056  4628  4702 E BtGatt.ContextMap: Context not found for ID 5
11-24 05:22:20.056  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 05:22:20.056  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 05:22:20.056  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 05:22:20.056  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 05:22:20.056  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 05:22:20.058  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 05:22:20.059  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 05:22:20.059  5635  5681 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 05:22:20.059  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 05:22:20.063  4628  4702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 05:22:20.063  4628  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:22:20.063  4628  4707 D BtGatt.ScanManager: stopping BLe Batch
11-24 05:22:20.063  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.063  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 05:22:20.064  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 05:22:20.064  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 05:22:20.064  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 05:22:20.063  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 05:22:20.067  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.067  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 05:22:20.067  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 05:22:20.067  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 05:22:20.068  4628  4702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 05:22:20.068  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 05:22:20.068  4628  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:22:20.068  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.068  4628  4707 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 05:22:20.068  5635  5681 D BluetoothAdapter: STATE_ON
11-24 05:22:20.071  4628  4643 D BtGatt.GattService: registerClient() - UUID=ffdc8a3b-2c5a-47c0-9978-805a2b655cfa
11-24 05:22:20.071  4628  4702 D BtGatt.GattService: onClientRegistered() - UUID=ffdc8a3b-2c5a-47c0-9978-805a2b655cfa, clientIf=5
11-24 05:22:20.072  5635  5646 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 05:22:20.072  4628  4858 D BtGatt.GattService: start scan with filters
11-24 05:22:20.072  4628  4702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 05:22:20.072  4628  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:22:20.074  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 05:22:20.074  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.074  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 05:22:20.074  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.074  4628  4707 D BtGatt.ScanManager: handling starting scan
11-24 05:22:20.074  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 05:22:20.075  5635  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 05:22:20.075  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 05:22:20.075  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 05:22:20.075  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 05:22:20.075  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 05:22:20.075  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 05:22:20.075  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 05:22:20.075  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 05:22:20.076  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 05:22:20.076  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.078  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.078  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 05:22:20.078  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.078  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:20.078  5635  5681 I io.jxcore.node.ConnectionHelper: start: OK
11-24 05:22:20.078  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 05:22:20.080  4628  4702 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 05:22:20.080  4628  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:22:20.080  4628  4707 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 05:22:20.080  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 05:22:20.080  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 05:22:20.080  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 05:22:20.080  5635  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 05:22:20.084  4628  4702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 05:22:20.084  4628  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:22:20.084  4628  4707 D BtGatt.ScanManager: Starting BLE batch scan
11-24 05:22:20.085  4628  4707 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 05:22:20.092  4628  4702 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 05:22:20.092  4628  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:22:20.097  4628  4702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 05:22:20.097  4628  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 05:22:20.581  5635  5635 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-24 05:22:20.582  5635  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 05:22:20.582  5635  5635 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 05:22:25.079  5635  5681 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 05:22:25.079  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-24 05:22:25.079  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 05:22:25.080  5635  5681 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 05:22:25.080  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-24 05:22:25.080  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:22:25.080  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-24 05:22:25.080  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 05:22:25.080  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:25.081  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-24 05:22:25.081  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 05:22:25.081  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:25.081  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:25.081  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:25.082  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 05:22:25.082  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:25.084  5635  5681 D BluetoothAdapter: STATE_ON
11-24 05:22:25.085  4628  4641 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 05:22:25.085  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-24 05:22:25.087  4628  4707 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 05:22:25.087  5635  5681 D BluetoothAdapter: STATE_ON
11-24 05:22:25.089  4628  4838 D BtGatt.GattService: stopScan() - queue size =1
,11-24 05:22:25.092  4628  4858 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-24 05:22:25.092  4628  4628 D BtGatt.ScanManager: awakened up at time 107622
11-24 05:22:25.093  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 05:22:25.093  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:25.094  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 05:22:25.094  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:25.094  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:25.094  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:25.095  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:25.095  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 05:22:25.095  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:25.095  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:25.095  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:25.095  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 05:22:25.096  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-24 05:22:25.098   924   935 I ActivityManager: Killing 5073:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-24 05:22:25.127  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 05:22:25.127  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:25.129  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:25.129  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 05:22:25.129  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:25.130  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:25.130  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-24 05:22:25.130  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 05:22:25.130  5635  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 05:22:25.130  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 05:22:25.130  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 05:22:25.130  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-24 05:22:25.130  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 05:22:25.130  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 05:22:25.130  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 05:22:25.130  5635  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 05:22:25.130  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 05:22:25.130  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-24 05:22:25.131  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 05:22:25.132  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 05:22:25.132  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-24 05:22:25.140  4628  4702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
11-24 05:22:25.140  4628  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:22:25.140  4628  4702 D BtGatt.GattService: current time is 107670408895
,11-24 05:22:25.140  4628  4702 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -70, 78, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 81, 34, 97, 112, -14, -5, 1, -128, -72, 69, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -75, 86, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 71, -122, -77, 84, 69, -12, 1, -128, -81, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-24 05:22:25.140  4628  4702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-24 05:22:25.140  4628  4702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-24 05:22:25.141  4628  4702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-24 05:22:25.141  4628  4702 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-24 05:22:25.141  4628  4702 E BtGatt.ContextMap: Context not found for ID 5
,11-24 05:22:25.147  4628  4702 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-24 05:22:25.147  4628  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:22:25.147  4628  4707 D BtGatt.ScanManager: stopping BLe Batch
,11-24 05:22:25.153  4628  4702 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 05:22:25.153  4628  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:22:25.153  4628  4707 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 05:22:25.158  4628  4702 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 05:22:25.158  4628  4702 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 05:22:25.632  5635  5635 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
11-24 05:22:25.632  5635  5635 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 05:22:25.632  5635  5635 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 05:22:30.131  5635  5681 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 05:22:30.131  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 05:22:30.131  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 05:22:30.132  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 05:22:30.132  5635  5681 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 05:22:30.132  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 05:22:30.132  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 05:22:30.132  5635  5681 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4239265 not in the list
11-24 05:22:30.132  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:30.133  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:30.133  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 05:22:30.133  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 05:22:30.136  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.138  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:30.141  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:30.141  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:30.142  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:30.142  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 05:22:30.142  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 05:22:30.142  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:30.142  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:30.144  5635  5681 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-24 05:22:30.145  5635  5681 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 05:22:30.145  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 05:22:30.146  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 05:22:30.146  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:22:30.146  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:22:30.146  5635  5681 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4239265 not in the list
11-24 05:22:30.147  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:30.147  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:30.147  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
11-24 05:22:30.147  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:30.147  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.151  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.151  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.151  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.151  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 05:22:30.151  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 05:22:30.151  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:30.151  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
,11-24 05:22:30.152  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-24 05:22:30.153  5635  5681 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 05:22:30.153  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 05:22:30.153  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 05:22:30.153  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:22:30.153  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:22:30.153  5635  5681 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4239265 not in the list
11-24 05:22:30.153  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:30.153  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:30.153  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
11-24 05:22:30.153  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:30.154  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.155  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.155  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.155  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.155  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 05:22:30.155  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 05:22:30.155  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:30.155  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:30.156  5635  5681 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-24 05:22:30.156  5635  5681 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 05:22:30.156  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 05:22:30.157  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 05:22:30.157  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:22:30.157  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:22:30.157  5635  5681 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4239265 not in the list
11-24 05:22:30.157  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:30.157  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:30.157  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
11-24 05:22:30.157  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:30.157  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.159  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.160  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.160  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:30.160  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 05:22:30.160  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 05:22:30.160  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:30.160  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:30.161  5635  5681 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-24 05:22:30.161  5635  5681 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 05:22:30.161  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 05:22:30.161  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 05:22:30.161  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:22:30.161  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:22:30.161  5635  5681 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4239265 not in the list
11-24 05:22:30.161  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:30.161  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:30.162  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
11-24 05:22:30.162  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.162  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.163  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.163  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:30.163  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:30.163  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 05:22:30.164  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 05:22:30.164  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:30.164  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
,11-24 05:22:30.164  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 05:22:30.165  5635  5681 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-24 05:22:30.165  5635  5681 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 05:22:30.165  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 05:22:30.165  5635  5681 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 05:22:30.165  5635  5681 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 05:22:30.165  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 05:22:30.165  5635  5681 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 05:22:30.165  5635  5681 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 05:22:30.165  5635  5681 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 05:22:30.166  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 05:22:30.166  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 05:22:30.166  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:22:30.166  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:22:30.166  5635  5681 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4239265 not in the list
11-24 05:22:30.166  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:30.166  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:30.166  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
11-24 05:22:30.166  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.166  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.168  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:30.168  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.168  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.168  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 05:22:30.168  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 05:22:30.168  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:30.168  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:30.169  5635  5681 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 05:22:30.169  5635  5681 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-24 05:22:30.169  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-24 05:22:30.173  5635  5681 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 05:22:30.173  5635  5681 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-24 05:22:30.173  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-24 05:22:30.173  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-24 05:22:30.173  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-24 05:22:30.173  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-24 05:22:30.174  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-24 05:22:30.174  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-24 05:22:30.174  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-24 05:22:30.174  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-24 05:22:30.174  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-24 05:22:30.174  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-24 05:22:30.174  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-24 05:22:30.174  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-24 05:22:30.174  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-24 05:22:30.174  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-24 05:22:30.174  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-24 05:22:30.174  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-24 05:22:30.174  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name,> 26:1610:1610:1610:1610:1610]
11-24 05:22:30.174  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-24 05:22:30.174  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-24 05:22:30.174  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-24 05:22:30.175  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-24 05:22:30.175  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-24 05:22:30.175  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-24 05:22:30.175  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-24 05:22:30.175  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-24 05:22:30.175  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-24 05:22:30.175  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-24 05:22:30.175  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-24 05:22:30.175  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-24 05:22:30.175  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-24 05:22:30.175  5635  5681 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-24 05:22:30.176  5635  5681 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 05:22:30.176  5635  5681 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-24 05:22:30.176  5635  5681 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-24 05:22:30.176  5635  5681 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 05:22:30.176  5635  5681 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-24 05:22:30.176  5635  5681 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 05:22:30.176  5635  5681 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 05:22:30.176  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
11-24 05:22:30.180  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-24 05:22:30.180  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-24 05:22:30.180  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-24 05:22:30.181  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,11-24 05:22:30.181  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-24 05:22:30.181  5635  5681 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-24 05:22:30.181  5635  5681 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 05:22:30.182  5635  5681 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-24 05:22:30.182  5635  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
11-24 05:22:30.182  5635  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-24 05:22:30.182  5635  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-24 05:22:30.182  5635  5684 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
,11-24 05:22:30.183  5635  5681 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 05:22:30.183  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 05:22:30.183  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 05:22:30.183  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:22:30.183  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:22:30.183  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-24 05:22:30.184  5635  5681 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4239265 not in the list
,11-24 05:22:30.184  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:30.184  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:30.184  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
11-24 05:22:30.184  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.184  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.185  5635  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
,11-24 05:22:30.185  5635  5684 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-24 05:22:30.185  5635  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-24 05:22:30.185  5635  5684 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 05:22:30.185  5635  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
11-24 05:22:30.185  5635  5685 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
11-24 05:22:30.185  4858  4858 W Binder_4: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[32614]" dev="sockfs" ino=32614 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 05:22:30.185  4858  4858 W Binder_4: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[32614]" dev="sockfs" ino=32614 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 05:22:30.186  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:30.186  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.186  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.186  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 05:22:30.186  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 05:22:30.186  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:30.187  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:30.188  5635  5681 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-24 05:22:30.188  5635  5681 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 05:22:30.188  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 05:22:30.188  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 05:22:30.189  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:22:30.189  5635  5684 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
11-24 05:22:30.189  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:22:30.189  5635  5681 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4239265 not in the list
11-24 05:22:30.189  5635  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-24 05:22:30.189  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:30.189  5635  5684 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
11-24 05:22:30.189  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:30.189  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
11-24 05:22:30.189  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:30.189  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.192  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.192  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.193  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.193  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 05:22:30.193  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 05:22:30.193  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:30.193  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:30.194  5635  5681 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-24 05:22:30.194  5635  5681 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 05:22:30.194  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 05:22:30.194  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 05:22:30.194  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:22:30.194  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:22:30.194  5635  5681 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4239265 not in the list
11-24 05:22:30.194  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:30.194  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:30.194  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
11-24 05:22:30.194  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.195  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.196  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:30.196  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.196  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.196  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 05:22:30.196  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 05:22:30.197  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:30.197  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:30.197  5635  5681 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-24 05:22:30.197  5635  5681 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-24 05:22:30.197  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 05:22:30.198  5635  5681 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
,11-24 05:22:30.198  5635  5681 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-24 05:22:30.198  5635  5681 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-24 05:22:30.198  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 05:22:30.198  5635  5681 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-24 05:22:30.198  5635  5681 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-24 05:22:30.198  5635  5681 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-24 05:22:30.198  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 05:22:30.198  5635  5681 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-24 05:22:30.198  5635  5681 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 05:22:30.198  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 05:22:30.198  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 05:22:30.198  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:22:30.198  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:22:30.198  5635  5681 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4239265 not in the list
11-24 05:22:30.198  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:30.198  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:30.198  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
11-24 05:22:30.198  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.199  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.200  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:30.200  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.200  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:30.200  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 05:22:30.200  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 05:22:30.200  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:30.200  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:30.201  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:22:30.201  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:22:30.201  5635  5681 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4239265 not in the list
,11-24 05:22:30.201  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:30.201  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:30.201  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 05:22:30.947   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 05:22:30.948   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 05:22:35.202  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 05:22:35.202  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:35.202  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:22:35.202  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:22:35.203  5635  5681 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4239265 not in the list
,11-24 05:22:35.203  5635  5681 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 05:22:35.203  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 05:22:35.203  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 05:22:35.204  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:22:35.204  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:22:35.204  5635  5681 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4239265 not in the list
,11-24 05:22:35.204  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:35.204  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:35.205  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
11-24 05:22:35.205  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:35.205  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:35.209  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:35.209  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:35.209  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:35.209  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 05:22:35.210  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 05:22:35.210  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:35.210  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
,11-24 05:22:35.214  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-24 05:22:35.214  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 05:22:35.215  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-24 05:22:35.220  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-24 05:22:35.222  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-24 05:22:35.222  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-24 05:22:35.223  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-24 05:22:35.223  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-24 05:22:35.223  5635  5635 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-24 05:22:35.223  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-24 05:22:35.224  5635  5686 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-24 05:22:35.224  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:22:35.224  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-24 05:22:35.224  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-24 05:22:35.225  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-24 05:22:35.225  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 05:22:35.226  5635  5686 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 05:22:35.226  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-24 05:22:35.226  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-24 05:22:35.226  5635  5681 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4239265 not in the list
,11-24 05:22:35.226  5635  5635 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-24 05:22:35.226  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:35.226  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 05:22:35.227  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:35.227  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 05:22:35.227  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-24 05:22:35.227  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:35.230  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:35.226  4643  4643 W Binder_2: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[33647]" dev="sockfs" ino=33647 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 05:22:35.230  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 05:22:35.230  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:35.230  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:35.231  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:35.231  5635  5686 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-24 05:22:35.231  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 05:22:35.231  5635  5686 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-24 05:22:35.231  5635  5681 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 05:22:35.231  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 05:22:35.231  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 05:22:35.231  5635  5686 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-24 05:22:35.231  5635  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 05:22:35.231  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 05:22:35.231  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 05:22:35.232  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-24 05:22:35.232  5635  5681 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4239265 not in the list
11-24 05:22:35.232  5635  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-24 05:22:35.232  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:35.232  5635  5635 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 05:22:35.232  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
,11-24 05:22:35.232  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
11-24 05:22:35.229  4643  4643 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[33647]" dev="sockfs" ino=33647 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-24 05:22:35.232  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:35.232  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:35.235  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:35.235  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:35.235  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:35.235  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-24 05:22:35.235  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 05:22:35.235  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 05:22:35.236  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:35.238  5635  5681 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-24 05:22:35.238  5635  5681 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-24 05:22:35.238  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 05:22:35.239  5635  5681 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-24 05:22:35.239  5635  5681 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 05:22:35.240  5635  5681 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 05:22:35.241  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 05:22:35.241  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 05:22:35.241  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:22:35.241  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:22:35.241  5635  5681 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4239265 not in the list
,11-24 05:22:35.241  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:35.242  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:35.242  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
11-24 05:22:35.242  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:35.242  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:35.246  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:35.246  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:35.246  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:35.246  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 05:22:35.246  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 05:22:35.246  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:35.246  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
,11-24 05:22:35.251  5635  5681 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 05:22:35.251  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 05:22:35.251  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 05:22:35.251  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:22:35.252  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:22:35.252  5635  5681 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4239265 not in the list
11-24 05:22:35.252  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 05:22:35.252  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:35.252  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
11-24 05:22:35.252  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:35.252  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:35.253  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:35.254  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:35.254  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:35.254  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 05:22:35.254  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 05:22:35.254  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:35.254  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
,11-24 05:22:35.255  5635  5681 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 05:22:35.255  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 05:22:35.255  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 05:22:35.255  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:22:35.255  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:22:35.255  5635  5681 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4239265 not in the list
,11-24 05:22:35.255  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:35.255  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:35.255  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
11-24 05:22:35.255  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:35.256  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:35.258  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:35.258  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:22:35.258  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:22:35.258  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 05:22:35.258  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 05:22:35.258  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:22:35.258  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8de4b3a not in the list
11-24 05:22:35.259  5635  5681 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-24 05:22:35.259  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-24 05:22:35.260  5635  5681 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-24 05:22:35.260  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 05:22:35.260  5635  5681 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,11-24 05:22:35.260  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-24 05:22:35.262  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-24 05:22:35.262  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-24 05:22:35.263  5635  5681 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-24 05:22:35.263  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-24 05:22:35.263  5635  5681 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-24 05:22:35.263  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-24 05:22:35.263  5635  5681 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-24 05:22:35.263  5635  5681 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-24 05:22:35.264  5635  5681 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-24 05:22:35.264  5635  5681 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-24 05:22:35.264  5635  5681 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-24 05:22:35.264  5635  5681 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
,11-24 05:22:35.264  5635  5681 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-24 05:22:35.265  5635  5681 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-24 05:22:35.265  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 05:22:35.266  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4339ddb added. We now have 3 listener(s)
11-24 05:22:35.266  5635  5681 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 05:22:35.267  5635  5681 D BluetoothAdapter: enable(): BT is already enabled..!
,11-24 05:22:35.268   924  3828 D WifiService: setWifiEnabled: true pid=5635, uid=10077
11-24 05:22:35.268   924  3828 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 05:22:35.315  4628  4833 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-24 05:22:35.315  4628  4836 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-24 05:22:35.732  5635  5635 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 05:22:35.949   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 05:22:36.950   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 05:22:37.951   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 05:22:38.668   924  2980 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 05:22:38.951   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 05:22:39.952   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 05:22:40.273  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 05:22:40.274  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6752078 added. We now have 4 listener(s)
,11-24 05:22:40.274  5635  5681 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 05:22:40.287  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 05:22:40.287  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6752078 removed from the list
11-24 05:22:40.287  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 05:22:40.289  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 05:22:40.290  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4939351 added. We now have 4 listener(s)
11-24 05:22:40.290  5635  5681 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 05:22:40.294  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 05:22:40.294  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@4939351 removed from the list
11-24 05:22:40.294  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 05:22:40.296  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 05:22:40.296  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b5e97b6 added. We now have 4 listener(s)
11-24 05:22:40.296  5635  5681 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 05:22:40.301   924  3828 D WifiService: setWifiEnabled: false pid=5635, uid=10077
11-24 05:22:40.302   924  3828 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 05:22:40.311   924  2980 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-24 05:22:40.312   924  2980 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-24 05:22:40.312   924  2980 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 05:22:40.312   924  2980 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 05:22:40.318  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-24 05:22:40.318  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-24 05:22:40.318  4628  4698 D BluetoothAdapterState: Current state: ON, message: 23
11-24 05:22:40.319  4628  4698 D BluetoothAdapterProperties: Setting state to 13
11-24 05:22:40.319  4628  4698 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-24 05:22:40.320  4628  4698 D BluetoothAdapterProperties: onBluetoothDisable()
11-24 05:22:40.321  4628  4698 I BluetoothAdapterState: Entering PendingCommandState
,11-24 05:22:40.325  4628  4702 D BluetoothAdapterProperties: Scan Mode:20
,11-24 05:22:40.327   507   917 D CommandListener: Clearing all IP addresses on wlan0
11-24 05:22:40.328  4628  4698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-24 05:22:40.330  4628  4628 D BluetoothMapService: onReceive
11-24 05:22:40.330  5635  5681 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 05:22:40.330  4628  4628 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 05:22:40.330  5635  5681 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 05:22:40.330  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 05:22:40.330  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 05:22:40.330  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 05:22:40.330  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 05:22:40.330  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 05:22:40.330  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 05:22:40.330  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 05:22:40.330  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 05:22:40.330  4628  4628 D BluetoothMapService: STATE_TURNING_OFF
,11-24 05:22:40.330  4628  4628 D BluetoothMapService: MAP Service closeService in
11-24 05:22:40.330  4628  4628 D BluetoothMapMasInstance0: MAP Service shutdown
11-24 05:22:40.330  4628  4628 D ObexServerSockets0: shutdown(block = true)
11-24 05:22:40.330  5635  5681 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 05:22:40.331  5635  5681 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 05:22:40.331  5635  5681 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 05:22:40.333  4628  4860 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-24 05:22:40.333   924  5397 D DhcpClient: Clearing IP address
11-24 05:22:40.334  4628  4628 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 05:22:40.334  4628  4836 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-24 05:22:40.334  4628  4861 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-24 05:22:40.335  4628  4628 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 05:22:40.335   507   917 D CommandListener: Setting iface cfg
11-24 05:22:40.336  4628  4628 I BtOppRfcommListener: stopping Accept Thread
11-24 05:22:40.336  4628  5331 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-24 05:22:40.336  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 05:22:40.339   924  5398 D DhcpClient: Receive thread stopped
11-24 05:22:40.339  4628  5331 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-24 05:22:40.341  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 05:22:40.341  3589  5451 V NativeCrypto: Read error: ssl=0x7f87ef7a00: I/O error during system call, Connection timed out
,11-24 05:22:40.344  3589  5451 V NativeCrypto: SSL shutdown failed: ssl=0x7f87ef7a00: I/O error during system call, Broken pipe
,11-24 05:22:40.344  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 05:22:40.345   924  3172 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-24 05:22:40.345   924  5395 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-24 05:22:40.347  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 05:22:40.348   924  5395 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-24 05:22:40.348   924  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,11-24 05:22:40.348   924  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-24 05:22:40.350   924  2987 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-24 05:22:40.356   924   938 I ActivityManager: Start proc 5691:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-24 05:22:40.358  4628  4628 D HeadsetService: Received stop request...Stopping profile...
,11-24 05:22:40.359   924  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-24 05:22:40.359   924  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-24 05:22:40.363   924   924 D BluetoothHeadset: Proxy object disconnected
11-24 05:22:40.363   924   924 D BluetoothHeadset: Proxy object disconnected
11-24 05:22:40.363   924   924 D BluetoothHeadset: Proxy object disconnected
11-24 05:22:40.363  3143  3154 D BluetoothHeadset: Proxy object disconnected
11-24 05:22:40.363  3143  3143 D HeadsetProfile: Bluetooth service disconnected
11-24 05:22:40.364  3792  3818 D BluetoothHeadset: Proxy object disconnected
11-24 05:22:40.364   533   533 E Parcel  : Reading a NULL string not supported here.
,11-24 05:22:40.365   924  2987 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-24 05:22:40.366   924   924 D RttService: SCAN_AVAILABLE : 1
11-24 05:22:40.366   924  3095 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-24 05:22:40.367  3755  3912 W QCNEJ   : |CORE| network lost: 100
11-24 05:22:40.367  4628  4628 D A2dpService: Received stop request...Stopping profile...
11-24 05:22:40.368  3755  3912 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-24 05:22:40.368  4628  4853 D A2dpStateMachine: Exit Disconnected: -1
11-24 05:22:40.369   924   924 D BluetoothA2dp: Proxy object disconnected
11-24 05:22:40.370  4628  4628 D HidService: Received stop request...Stopping profile...
,11-24 05:22:40.370  4628  4628 D HidService: Stopping Bluetooth HidService
,11-24 05:22:40.372  4628  4628 V BluetoothAdapterState: isTurningOff()=true
11-24 05:22:40.373  4628  4628 V BluetoothAdapterState: isTurningOn()=false
11-24 05:22:40.373  4628  4628 V BluetoothAdapterState: isBleTurningOn()=false
11-24 05:22:40.373  4628  4628 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 05:22:40.373  4628  4628 D HealthService: Received stop request...Stopping profile...
11-24 05:22:40.374   924  2980 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-24 05:22:40.375  3143  3143 D BluetoothA2dp: Proxy object disconnected
,11-24 05:22:40.375  3143  3143 D BluetoothInputDevice: Proxy object disconnected
11-24 05:22:40.375  3143  3143 D HidProfile: Bluetooth service disconnected
11-24 05:22:40.376  4628  4628 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-24 05:22:40.376  4628  4628 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,11-24 05:22:40.376  4628  4702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-24 05:22:40.376  4628  4833 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 05:22:40.376  4628  4628 D PanService: Received stop request...Stopping profile...
11-24 05:22:40.377  4628  4833 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 05:22:40.377  4628  4833 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 05:22:40.378  4628  4702 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-24 05:22:40.379  4628  4628 D BluetoothMapService: Received stop request...Stopping profile...
11-24 05:22:40.380  4628  4628 D BluetoothMapService: stop()
11-24 05:22:40.380  4628  4628 D BluetoothMapAppObserver: deinitObservers()
11-24 05:22:40.380  4628  4628 D BluetoothMapAppObserver: removeReceiver()
11-24 05:22:40.382  4628  4628 D SapService: Received stop request...Stopping profile...
11-24 05:22:40.382  4628  4628 V SapService: stop()
11-24 05:22:40.383  4628  4628 V BluetoothAdapterState: isTurningOff()=true
,11-24 05:22:40.383  4628  4628 V BluetoothAdapterState: isTurningOn()=false
11-24 05:22:40.383  4628  4628 V BluetoothAdapterState: isBleTurningOn()=false
11-24 05:22:40.383  4628  4628 V BluetoothAdapterState: isBleTurningOff()=false
11-24 05:22:40.384  4628  4628 V BluetoothAdapterState: isTurningOff()=true
11-24 05:22:40.384  4628  4628 V BluetoothAdapterState: isTurningOn()=false
11-24 05:22:40.384  4628  4628 V BluetoothAdapterState: isBleTurningOn()=false
11-24 05:22:40.384  4628  4628 V BluetoothAdapterState: isBleTurningOff()=false
11-24 05:22:40.385  4628  4628 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-24 05:22:40.385  4628  4628 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-24 05:22:40.385  4628  4628 V BluetoothAdapterState: isTurningOff()=true
,11-24 05:22:40.385  4628  4628 V BluetoothAdapterState: isTurningOn()=false
11-24 05:22:40.385  4628  4628 V BluetoothAdapterState: isBleTurningOn()=false
11-24 05:22:40.385  4628  4628 V BluetoothAdapterState: isBleTurningOff()=false
11-24 05:22:40.385  4628  4628 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-24 05:22:40.385  4628  4628 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-24 05:22:40.386  4628  4628 V BluetoothAdapterState: isTurningOff()=true
11-24 05:22:40.386  4628  4628 V BluetoothAdapterState: isTurningOn()=false
11-24 05:22:40.386  4628  4628 V BluetoothAdapterState: isBleTurningOn()=false
11-24 05:22:40.386  4628  4628 V BluetoothAdapterState: isBleTurningOff()=false
11-24 05:22:40.386  4628  4702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 05:22:40.386  4628  4702 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 05:22:40.386  4628  4833 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 05:22:40.386  4628  4702 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-24 05:22:40.386  4628  4628 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-24 05:22:40.386  4628  4833 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 05:22:40.386  4628  4628 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-24 05:22:40.387  4628  4833 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 05:22:40.387  4628  4833 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 05:22:40.387  4628  4833 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 05:22:40.387  4628  4833 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 05:22:40.387  4628  4628 D BluetoothMapService: MAP Service closeService in
11-24 05:22:40.387  4628  4628 V BluetoothAdapterState: isTurningOff()=true
11-24 05:22:40.387  4628  4628 V BluetoothAdapterState: isTurningOn()=false
11-24 05:22:40.387  4628  4628 V BluetoothAdapterState: isBleTurningOn()=false
11-24 05:22:40.387  4628  4628 V BluetoothAdapterState: isBleTurningOff()=false
11-24 05:22:40.388  4628  4628 D BluetoothMapService: cleanup()
11-24 05:22:40.388  4628  4628 D BluetoothMapService: MAP Service closeService in
11-24 05:22:40.388  4628  4628 V BluetoothAdapterState: isTurningOff()=true
,11-24 05:22:40.388  4628  4628 V BluetoothAdapterState: isTurningOn()=false
11-24 05:22:40.388  4628  4628 V BluetoothAdapterState: isBleTurningOn()=false
11-24 05:22:40.388  4628  4628 V BluetoothAdapterState: isBleTurningOff()=false
11-24 05:22:40.388  4628  4698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-24 05:22:40.388  4628  4698 D BluetoothAdapterProperties: Setting state to 15
11-24 05:22:40.388  4628  4698 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-24 05:22:40.389  4628  4698 I BluetoothAdapterState: Entering BleOnState
11-24 05:22:40.389   924   942 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 05:22:40.389   924   942 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 05:22:40.389  3143  3156 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 05:22:40.389   924  2980 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 05:22:40.390  3143  3143 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 05:22:40.390  3143  3143 D PanProfile: Bluetooth service disconnected
11-24 05:22:40.390  3143  3143 D BluetoothMap: Proxy object disconnected
11-24 05:22:40.390  3792  3818 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 05:22:40.390  3143  3143 D MapProfile: Bluetooth service disconnected
11-24 05:22:40.390  3143  3983 D BluetoothPan: onBluetoothStateChange on: false
11-24 05:22:40.391  3143  3154 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-24 05:22:40.392  3143  3156 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 05:22:40.392  3143  3983 D BluetoothMap: onBluetoothStateChange: up=false
11-24 05:22:40.393  3143  3154 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 05:22:40.393   924   942 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 05:22:40.394   924   942 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 05:22:40.394  4628  4698 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-24 05:22:40.395  4628  4698 D BluetoothAdapterProperties: Setting state to 16
11-24 05:22:40.395  4628  4698 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-24 05:22:40.395  4628  4698 D BluetoothAdapterProperties: onBleDisable
11-24 05:22:40.395  4628  4698 I BluetoothAdapterState: Entering PendingCommandState
11-24 05:22:40.395  4628  4699 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-24 05:22:40.397  4628  4833 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-24 05:22:40.397  4628  4833 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-24 05:22:40.397  4628  4702 D BluetoothAdapterProperties: Scan Mode:20
,11-24 05:22:40.399  5635  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 05:22:40.399  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 05:22:40.399  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 05:22:40.399  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 05:22:40.399  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 05:22:40.399  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 05:22:40.399  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 05:22:40.399  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 05:22:40.399  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 05:22:40.399  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 05:22:40.400  5635  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 05:22:40.400  5635  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 05:22:40.401  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 05:22:40.415   507   917 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 05:22:40.426  5691  5691 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-24 05:22:40.432   507   917 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 05:22:40.432   507   917 D CommandListener: Clearing all IP addresses on wlan0
11-24 05:22:40.433   507   917 D TetherController: Setting IP forward enable = 0
,11-24 05:22:40.434   924  2987 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,11-24 05:22:40.435   924  2980 D DhcpClient: doQuit
,11-24 05:22:40.435   924  2987 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-24 05:22:40.435   924  2980 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-24 05:22:40.436   924  5397 D DhcpClient: onQuitting
11-24 05:22:40.437  3461  3461 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-24 05:22:40.437   924   942 D Tethering: MasterInitialState.processMessage what=3
,11-24 05:22:40.440  5302  5302 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@dd406aa and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-24 05:22:40.440  5635  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 05:22:40.440  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 05:22:40.440  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 05:22:40.440  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 05:22:40.440  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 05:22:40.440  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 05:22:40.440  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 05:22:40.440  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 05:22:40.440  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 05:22:40.440  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 05:22:40.441  5635  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 05:22:40.441  5635  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 05:22:40.444  5061  5085 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-24 05:22:40.444  5061  5085 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 05:22:40.444  5061  5085 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-24 05:22:40.444  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 05:22:40.444  5061  5085 E SarControlService: no key has been found,reset the power
11-24 05:22:40.447  5061  5098 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 05:22:40.447  5061  5098 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 05:22:40.447  5061  5098 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 05:22:40.447  5086  5086 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 05:22:40.448  5086  5086 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-24 05:22:40.448  5061  5098 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-24 05:22:40.449  5061  5098 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 05:22:40.449  5061  5098 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 05:22:40.449  5086  5086 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 05:22:40.449  5086  5086 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-24 05:22:40.460  3461  3461 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-24 05:22:40.460  5691  5691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 05:22:40.461  5086  5100 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@46ef660 HexData = [00000000ea03000000000000ffffffff]
11-24 05:22:40.461  5086  5100 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 05:22:40.461  5086  5100 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-24 05:22:40.461  5086  5086 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 05:22:40.462  5061  5071 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-24 05:22:40.464  5086  5100 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@46ef660 HexData = [00000000eb03000000000000ffffffff]
11-24 05:22:40.464  5086  5100 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 05:22:40.464  5086  5100 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-24 05:22:40.465  5086  5086 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 05:22:40.465  5061  5072 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-24 05:22:40.468   924   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3a74ed2:true
,11-24 05:22:40.470  3461  3461 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-24 05:22:40.470  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 05:22:40.485  3461  3461 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-24 05:22:40.488   924  3606 I ActivityManager: Start proc 5720:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-24 05:22:40.494  5691  5691 D LocalBluetoothProfileManager: Adding local MAP profile
,11-24 05:22:40.499  5691  5691 D BluetoothMap: Create BluetoothMap proxy object
,11-24 05:22:40.499  3461  3461 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-24 05:22:40.502   507   917 E Netd    : netlink response contains error (No such file or directory)
,11-24 05:22:40.504   507   917 D TetherController: Setting IP forward enable = 0
11-24 05:22:40.504   924  2987 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-24 05:22:40.504   924  2987 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-24 05:22:40.505  5691  5691 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-24 05:22:40.518  5691  5691 D DockEventReceiver: finishStartingService: stopping service
,11-24 05:22:40.526   924  3828 I ActivityManager: Killing 5000:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-24 05:22:40.541  5720  5720 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-24 05:22:40.601  4628  4702 I bt_hci  : shut_down
,11-24 05:22:40.603  5035  5035 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 05:22:40.603   924  2980 D wifi    : In wifi stop Hal
11-24 05:22:40.603   924  2980 D wifi    : halHandle = 0x7f8640de00, mVM = 0x7fa2a8d140, mCls = 0x100a02
11-24 05:22:40.603   924  3460 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-24 05:22:40.603   924  3460 D WifiHAL : Got a signal to exit!!!
11-24 05:22:40.603   924  3460 I WifiHAL : Exit wifi_event_loop
11-24 05:22:40.604   924  2980 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
,11-24 05:22:40.604   924  2980 E WifiHAL : Event processing terminated
11-24 05:22:40.604  4098  4233 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 05:22:40.604   924  2980 D wifi    : In wifi cleaned up handler
11-24 05:22:40.605   924  2980 I WifiHAL : Internal cleanup completed
11-24 05:22:40.605  4628  4710 D bt_hwcfg: hw_epilog_process
,11-24 05:22:40.605  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 05:22:40.606  4628  4710 I bt_vendor: low_power_mode_cb
,11-24 05:22:40.608  4628  4710 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-24 05:22:40.608  4628  4710 I bt_vendor: epilog_cb
11-24 05:22:40.608  4628  4710 I bt_hci  : epilog_finished_callback
,11-24 05:22:40.611  4628  4702 I bt_hci_h4: hal_close
,11-24 05:22:40.612  4628  4702 I bt_userial_vendor: device fd = 54 close
,11-24 05:22:40.625   924  3460 D wifi    : set interface wlan0 flags (DOWN)
,11-24 05:22:40.625   924  2980 D WifiNative-HAL: HAL event thread stopped successfully
,11-24 05:22:40.712  5720  5720 D StrictMode: StrictMode policy violation; ~duration=88 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-24 05:22:40.712  5720  5720 D StrictMode: StrictMode policy violation; ~duration=87 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 05:22:40.712  5720  5720 D StrictMode: StrictMode policy violation; ~duration=86 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.,a.a(PG:244)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 05:22:40.712  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-24 05:22:40.713  5720  5720 D StrictMode: StrictMode policy violation; ~duration=85 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 05:22:40.713  5720  5720 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at com.google.r.e.b(PG:170)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 05:22:40.713  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-24 05:22:40.720  4628  4699 D bt_stack_manager: event_shut_down_stack finished.
11-24 05:22:40.721  4628  4698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-24 05:22:40.721  5720  5720 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 05:22:40.721  5720  5720 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at com.google.r.k.d(PG:583)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at com.google.r.e.b(PG:170)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 05:22:40.721  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 05:22:40.722  5720  5720 D StrictMode: StrictMode policy violation; ~duration=63 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 05:22:40.722  5720  5720 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 05:22:40.722  5720  5720 D StrictM,ode: 	at java.io.File.doAccess(File.java:281)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 05:22:40.722  5720  5720 D StrictMode: StrictMode policy violation; ~duration=62 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 05:22:40.722  5720  5720 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at android.app.ActivityThread.-wrap1,(ActivityThread.java)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 05:22:40.722  5720  5720 D StrictMode: StrictMode policy violation; ~duration=61 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 05:22:40.722  5720  5720 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 05:22:40.722  5720  5720 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 05:22:40.723  4628  4698 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-24 05:22:40.723  4628  4628 D BtGatt.DebugUtils: handleDebugAction() action=null
11-24 05:22:40.723  4628  4628 D BtGatt.GattService: Received stop request...Stopping profile...
11-24 05:22:40.723  4628  4628 D BtGatt.GattService: stop()
11-24 05:22:40.723  4628  4628 D BtGatt.AdvertiseManager: advertise clients cleared
11-24 05:22:40.728  4628  4628 V BluetoothAdapterState: isTurningOff()=false
11-24 05:22:40.728  4628  4628 V BluetoothAdapterState: isTurningOn()=false
11-24 05:22:40.728  4628  4628 V BluetoothAdapterState: isBleTurningOn()=false
11-24 05:22:40.728  4628  4628 V BluetoothAdapterState: isBleTurningOff()=true
11-24 05:22:40.728  4628  4698 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-24 05:22:40.728  4628  4698 D BluetoothAdapterProperties: Setting state to 10
11-24 05:22:40.728  4628  4698 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-24 05:22:40.729  4628  4698 I BluetoothAdapterState: Entering OffState
11-24 05:22:40.729  5691  5691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 05:22:40.729   924   942 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-24 05:22:40.736  4628  4628 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-24 05:22:40.736  4628  4628 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-24 05:22:40.736  4628  4628 I BluetoothServiceJni: cleanupNative: return from cleanup
11-24 05:22:40.737  4628  4699 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-24 05:22:40.748  4628  4699 D bt_stack_manager: event_clean_up_stack finished.
11-24 05:22:40.754  4628  4628 I art     : System.exit called, status: 0
11-24 05:22:40.754  4628  4628 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-24 05:22:40.768  5691  5691 D DockEventReceiver: finishStartingService: stopping service
11-24 05:22:40.769   924  3606 I ActivityManager: Killing 5425:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-24 05:22:40.807   924  3817 I ActivityManager: Process com.android.bluetooth (pid 4628) has died
,11-24 05:22:40.810  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 05:22:40.821   924  3140 I ActivityManager: Start proc 5755:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,11-24 05:22:40.827   924   942 D Tethering: InitialState.processMessage what=4
,11-24 05:22:40.832   924   942 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-24 05:22:40.891  5755  5755 D AdapterServiceConfig: Adding HeadsetService
,11-24 05:22:40.891  5755  5755 D AdapterServiceConfig: Adding A2dpService
11-24 05:22:40.891  5755  5755 D AdapterServiceConfig: Adding HidService
11-24 05:22:40.891  5755  5755 D AdapterServiceConfig: Adding HealthService
11-24 05:22:40.891  5755  5755 D AdapterServiceConfig: Adding PanService
11-24 05:22:40.891  5755  5755 D AdapterServiceConfig: Adding GattService
,11-24 05:22:40.891  5755  5755 D AdapterServiceConfig: Adding BluetoothMapService
11-24 05:22:40.892  5755  5755 D AdapterServiceConfig: Adding SapService
,11-24 05:22:40.897   924  3828 I ActivityManager: Killing 5438:com.android.chrome/u0a39 (adj 15): empty #17
,11-24 05:22:40.927  3930  3930 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-24 05:22:40.930  3930  3930 D SystemUpdateService: onCreate
11-24 05:22:40.934  3930  3930 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 05:22:40.943  3930  3930 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-24 05:22:40.945  3930  5423 I iu.UploadsManager: num queued entries: 0
,11-24 05:22:40.952   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 05:22:40.955  3930  5767 I SystemUpdateService: active receiver: enabled
,11-24 05:22:40.960  3930  5423 I iu.UploadsManager: num updated entries: 0
11-24 05:22:40.961  3930  5423 I iu.SyncManager: NEXT; no task
11-24 05:22:40.963  3930  3930 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-24 05:22:40.964  3930  3930 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-24 05:22:40.971  3930  5767 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-24 05:22:40.973  3930  5767 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-24 05:22:40.973  3930  5767 I SystemUpdateService: now status is 0 (complete)
11-24 05:22:40.973  3930  5767 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 05:22:40.973  3930  5767 I SystemUpdateService: file has been verified
11-24 05:22:40.973  3930  5767 I SystemUpdateService: OTA package size = 21989297
11-24 05:22:40.976   924  3140 I ActivityManager: Start proc 5769:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
11-24 05:22:40.993  3930  5767 I SystemUpdateService: showing system update notification
,11-24 05:22:41.007  5769  5769 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-24 05:22:41.010  5769  5769 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 05:22:41.020  5769  5769 D SprintDMHelper: simOperator: 
,11-24 05:22:41.020  5769  5769 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 05:22:41.032   924  3605 I ActivityManager: Start proc 5781:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-24 05:22:41.036  3930  3930 D SystemUpdateService: onDestroy
,11-24 05:22:41.039   924  3605 I ActivityManager: Killing 5457:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,11-24 05:22:41.138  5035  5795 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-24 05:22:41.146   924  3172 I ActivityManager: Start proc 5796:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,11-24 05:22:41.149   924  3140 I ActivityManager: Killing 5302:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-24 05:22:41.176  5720  5748 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-24 05:22:41.207  5796  5796 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,11-24 05:22:41.227   924   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@228c783:true
,11-24 05:22:41.400   924  3606 I ActivityManager: Killing 5503:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-24 05:22:41.432   924  3169 I ActivityManager: Start proc 5810:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-24 05:22:41.462  5810  5810 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-24 05:22:41.469   924  3169 I ActivityManager: Killing 4712:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-24 05:22:45.335   924  3833 D WifiService: setWifiEnabled: true pid=5635, uid=10077
11-24 05:22:45.335   924  3833 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 05:22:45.345   507   917 D SoftapController: Softap fwReload - Ok
,11-24 05:22:45.350   507   917 D CommandListener: Setting iface cfg
11-24 05:22:45.351   507   917 D CommandListener: Trying to bring down wlan0
11-24 05:22:45.352   507   917 D CommandListener: Clearing all IP addresses on wlan0
,11-24 05:22:45.359   924  2980 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 05:22:45.933   924  2980 D wifi    : set interface wlan0 flags (UP)
,11-24 05:22:45.938   924  2980 I WifiHAL : Initializing wifi
11-24 05:22:45.938   924  2980 I WifiHAL : Creating socket
,11-24 05:22:45.939   924   942 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-24 05:22:45.943   924  2980 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-24 05:22:45.943   924  2980 D wifi    : Did set static halHandle = 0x7f8640de00
11-24 05:22:45.943   924  2980 D wifi    : halHandle = 0x7f8640de00, mVM = 0x7fa2a8d140, mCls = 0x1862
11-24 05:22:45.943   924  2980 D wifi    : array field set
11-24 05:22:45.944   924  2980 I WifiNative-HAL: interface[0] = wlan0
11-24 05:22:45.946   924  5828 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547713244672
11-24 05:22:45.947   924  5828 D wifi    : waitForHalEvents called, vm = 0x7fa2a8d140, obj = 0x1862, env = 0x7f88df8380
,11-24 05:22:45.953   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 05:22:46.029  5829  5829 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-24 05:22:46.048   924  2980 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
11-24 05:22:46.050  5829  5829 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 05:22:46.050  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 05:22:46.102  5829  5829 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 05:22:46.102  5829  5829 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-24 05:22:46.117   924  2980 D WifiConfigStore: Loading config and enabling all networks 
,11-24 05:22:46.119  5635  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 05:22:46.119  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 05:22:46.119  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 05:22:46.119  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 05:22:46.119  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 05:22:46.119  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 05:22:46.119  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 05:22:46.119  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 05:22:46.119  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 05:22:46.119  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 05:22:46.119  5635  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 05:22:46.119  5635  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 05:22:46.133   924  2980 D WifiConfigStore: loaded 0 passpoint configs
,11-24 05:22:46.134   924  2980 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,11-24 05:22:46.134   924  2980 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-24 05:22:46.136   924  2980 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-24 05:22:46.137   924  2980 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-24 05:22:46.137   924  2980 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-24 05:22:46.137   924  2980 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-24 05:22:46.137   924  2980 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-24 05:22:46.141   924  2980 D WifiNative-HAL: Setting external_sim to 1
,11-24 05:22:46.141  5035  5035 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 05:22:46.142   924  2980 D wifi    : setting dfs flag to true, 0x7f8643caa0
,11-24 05:22:46.142   924  2980 D WifiStateMachine: Setting OUI to DA-A1-19
11-24 05:22:46.142   924  2980 D wifi    : setting scan oui 0x7f8643caa0
11-24 05:22:46.142   924  2980 D WifiHAL : Sending mac address OUI
,11-24 05:22:46.147   924  2980 E native  : do suspend false
,11-24 05:22:46.153   924  2980 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-24 05:22:46.154   507   917 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-24 05:22:46.154   924   924 D RttService: SCAN_AVAILABLE : 3
11-24 05:22:46.154   924  3095 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-24 05:22:46.155   507   917 D CommandListener: Setting iface cfg
,11-24 05:22:46.158   924  2964 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '128 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 128 Failed to set address (No such device)'
,11-24 05:22:46.158   924  2964 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-24 05:22:46.167   924  2964 D WifiNative-HAL: p2pGetDeviceAddress
,11-24 05:22:46.171   924  2964 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
11-24 05:22:46.171   924   940 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=128701 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=13 mControllerEnergyUsed=49 }
,11-24 05:22:46.954   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 05:22:47.955   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 05:22:48.958   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 05:22:49.225  5829  5829 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 05:22:49.236  5829  5829 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 05:22:49.277   924  2980 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-24 05:22:49.279   924  2980 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-24 05:22:49.279   924  2980 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 05:22:49.291   924  2980 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-24 05:22:49.325   924  2980 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-24 05:22:49.328  5829  5829 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-24 05:22:49.761  5829  5829 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-24 05:22:49.804  5829  5829 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-24 05:22:49.804  5829  5829 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-24 05:22:49.814   924  2980 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 05:22:49.815   924  2980 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-24 05:22:49.815   924  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-24 05:22:49.834   924  2980 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 05:22:49.847   507   917 D CommandListener: Setting iface cfg
,11-24 05:22:49.852   924  2980 D WifiStateMachine: Start Dhcp Watchdog 2
,11-24 05:22:49.857   924  5837 D DhcpClient: Receive thread started
,11-24 05:22:49.861   924  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 05:22:49.861   924  2980 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-24 05:22:49.861   924  2987 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-24 05:22:49.941   924  2980 E native  : do suspend false
,11-24 05:22:49.951   924  5836 D DhcpClient: Broadcasting DHCPDISCOVER
,11-24 05:22:49.958   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 05:22:49.964   924  5837 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172709, domain null
,11-24 05:22:49.964   924  5836 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172709 seconds
,11-24 05:22:49.966   924  5836 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-24 05:22:49.977   924  5837 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-24 05:22:49.978   924  5836 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-24 05:22:49.980   507   917 D CommandListener: Setting iface cfg
,11-24 05:22:49.984   924  2980 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-24 05:22:49.987   924  5836 D DhcpClient: Scheduling renewal in 86399s
,11-24 05:22:49.997   924  2980 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-24 05:22:49.997   924  2980 D WifiConfigStore: No blacklist allowed without epno enabled
,11-24 05:22:49.999   924  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-24 05:22:50.004   924  2980 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-24 05:22:50.006   924  2987 D ConnectivityService: Adding iface wlan0 to network 101
,11-24 05:22:50.048   924  2987 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-24 05:22:50.048   924  2987 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-24 05:22:50.053   924  2987 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-24 05:22:50.057   924  2987 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
11-24 05:22:50.058   924  2987 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-24 05:22:50.064   924  2987 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 05:22:50.067   924  2987 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-24 05:22:50.068   924  2987 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-24 05:22:50.068   924  2987 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-24 05:22:50.068   924  2987 D ConnectivityService:    accepting network in place of null
11-24 05:22:50.068   924  2980 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-24 05:22:50.068   924  2980 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 05:22:50.068   924  2987 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 05:22:50.083   924  5835 D NetlinkSocketObserver: NeighborEvent{elapsedMs=132613, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 05:22:50.090   507   917 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 05:22:50.111   507   917 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 05:22:50.114   924  2987 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-24 05:22:50.115   924  2987 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-24 05:22:50.115  3755  3912 W QCNEJ   : |CORE| network available: 101
,11-24 05:22:50.116   924  2987 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-24 05:22:50.116   924   942 D Tethering: MasterInitialState.processMessage what=3
11-24 05:22:50.117  3755  3912 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-24 05:22:50.121  3755  3912 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-24 05:22:50.121  3755  3912 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-24 05:22:50.122  5635  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 05:22:50.122  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 05:22:50.122  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 05:22:50.122  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 05:22:50.122  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 05:22:50.122  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 05:22:50.122  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 05:22:50.122  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 05:22:50.122  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 05:22:50.122  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 05:22:50.122  5635  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 05:22:50.122  5635  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 05:22:50.129  5061  5085 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-24 05:22:50.129  5061  5085 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 05:22:50.129  5061  5085 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-24 05:22:50.129  5061  5085 E SarControlService: no key has been found,reset the power
11-24 05:22:50.129  5061  5098 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 05:22:50.129  5061  5098 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 05:22:50.130  5061  5098 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,11-24 05:22:50.130  5086  5086 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 05:22:50.130  5086  5086 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 05:22:50.131  5061  5098 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 05:22:50.131  5061  5098 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 05:22:50.131  5061  5098 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 05:22:50.132  5086  5086 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 05:22:50.132  5086  5086 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 05:22:50.134  3930  3930 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-24 05:22:50.137  3930  3930 D SystemUpdateService: onCreate
,11-24 05:22:50.139  5086  5100 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@46ef660 HexData = [00000000ec03000000000000ffffffff]
,11-24 05:22:50.139  5086  5100 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 05:22:50.139  5086  5100 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-24 05:22:50.139  5086  5086 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 05:22:50.139  5061  5071 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-24 05:22:50.143  3930  3930 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 05:22:50.146  5086  5100 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@46ef660 HexData = [00000000ed03000000000000ffffffff]
11-24 05:22:50.146  5086  5100 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 05:22:50.146  5086  5100 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,11-24 05:22:50.147  5086  5086 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 05:22:50.147  5061  5072 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-24 05:22:50.151  3930  3930 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-24 05:22:50.154  3930  5423 I iu.UploadsManager: num queued entries: 0
,11-24 05:22:50.154  3930  5423 I iu.UploadsManager: num updated entries: 0
11-24 05:22:50.154   924  5834 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-24 05:22:50.154  3930  5423 I iu.SyncManager: NEXT; no task
,11-24 05:22:50.163  3930  3930 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 05:22:50.164  3930  3930 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 05:22:50.166  5769  5769 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 05:22:50.169  5769  5769 D SprintDMHelper: simOperator: 
11-24 05:22:50.169  5769  5769 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 05:22:50.177  3930  5847 I SystemUpdateService: active receiver: enabled
,11-24 05:22:50.205   924  5834 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Nov 2016 10:22:50 GMT], X-Android-Received-Millis=[1479982970205], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479982970180]}
,11-24 05:22:50.206   924  2987 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-24 05:22:50.207   924  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-24 05:22:50.207   924  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 05:22:50.208   924  2987 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-24 05:22:50.209  3930  5847 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 05:22:50.212  3930  5847 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-24 05:22:50.212  3930  5847 I SystemUpdateService: now status is 0 (complete)
11-24 05:22:50.212  3930  5847 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-24 05:22:50.212  3930  5847 I SystemUpdateService: file has been verified
11-24 05:22:50.212  3930  5847 I SystemUpdateService: OTA package size = 21989297
,11-24 05:22:50.218  3930  5847 I SystemUpdateService: showing system update notification
,11-24 05:22:50.229  3930  3930 D SystemUpdateService: onDestroy
,11-24 05:22:50.281  5035  5852 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-24 05:22:50.344   924  3172 D WifiService: setWifiEnabled: false pid=5635, uid=10077
,11-24 05:22:50.344   924  3172 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 05:22:50.347   924  2980 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-24 05:22:50.348   924  2980 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-24 05:22:50.348   924  2980 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 05:22:50.348   924  2980 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 05:22:50.364   924  5836 D DhcpClient: Clearing IP address
11-24 05:22:50.364   507   917 D CommandListener: Clearing all IP addresses on wlan0
,11-24 05:22:50.366   507   917 D CommandListener: Setting iface cfg
,11-24 05:22:50.369  3589  5857 V NativeCrypto: Read error: ssl=0x7f87ef7a00: I/O error during system call, Connection timed out
,11-24 05:22:50.369  3589  5857 V NativeCrypto: SSL shutdown failed: ssl=0x7f87ef7a00: I/O error during system call, Broken pipe
,11-24 05:22:50.377   924  3172 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
11-24 05:22:50.378   924  5834 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
,11-24 05:22:50.378   924  5834 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-24 05:22:50.383   924  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-24 05:22:50.385   924  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-24 05:22:50.387   533   533 E Parcel  : Reading a NULL string not supported here.
11-24 05:22:50.390   924  5834 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:81d::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
11-24 05:22:50.391   924  2987 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
11-24 05:22:50.391   924   924 D RttService: SCAN_AVAILABLE : 1
11-24 05:22:50.392   924  3095 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-24 05:22:50.393  3755  3912 W QCNEJ   : |CORE| network lost: 101
11-24 05:22:50.393  3755  3912 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-24 05:22:50.396   924  2980 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-24 05:22:50.397   924  5837 D DhcpClient: Receive thread stopped
,11-24 05:22:50.400   924  2980 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 05:22:50.417   507   917 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 05:22:50.440   507   917 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-24 05:22:50.441   507   917 D CommandListener: Clearing all IP addresses on wlan0
11-24 05:22:50.441   924  2987 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-24 05:22:50.441   924  2987 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-24 05:22:50.443   924   942 D Tethering: MasterInitialState.processMessage what=3
,11-24 05:22:50.445  5635  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 05:22:50.445  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 05:22:50.445  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 05:22:50.445  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 05:22:50.445  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 05:22:50.445  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 05:22:50.445  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 05:22:50.445  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 05:22:50.445  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 05:22:50.445  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 05:22:50.445  5635  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 05:22:50.445  5635  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 05:22:50.448   924  2980 D DhcpClient: doQuit
11-24 05:22:50.449   924  2980 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-24 05:22:50.449   924  5836 D DhcpClient: onQuitting
11-24 05:22:50.449  5829  5829 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-24 05:22:50.453  5635  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 05:22:50.453  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 05:22:50.453  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 05:22:50.453  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 05:22:50.453  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 05:22:50.453  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 05:22:50.453  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 05:22:50.453  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 05:22:50.453  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 05:22:50.453  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 05:22:50.453  5635  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 05:22:50.454  5635  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 05:22:50.454  5061  5085 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-24 05:22:50.454  5061  5085 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 05:22:50.454  5061  5085 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-24 05:22:50.454  5061  5085 E SarControlService: no key has been found,reset the power
11-24 05:22:50.454  5061  5098 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,11-24 05:22:50.454  5061  5098 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 05:22:50.454  5061  5098 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 05:22:50.455  5086  5086 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 05:22:50.455  5086  5086 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-24 05:22:50.457  5061  5098 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 05:22:50.457  5061  5098 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 05:22:50.458  5061  5098 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 05:22:50.458  3930  3930 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-24 05:22:50.461  3930  3930 D SystemUpdateService: onCreate
11-24 05:22:50.463  5086  5100 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@46ef660 HexData = [00000000ee03000000000000ffffffff]
11-24 05:22:50.463  5086  5100 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 05:22:50.464  5086  5100 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-24 05:22:50.464  5086  5086 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 05:22:50.464  5086  5086 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 05:22:50.467  3930  3930 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-24 05:22:50.467  5829  5829 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-24 05:22:50.469  5086  5086 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 05:22:50.469  5061  5072 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-24 05:22:50.472  5829  5829 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-24 05:22:50.473  3930  5867 I SystemUpdateService: active receiver: enabled
,11-24 05:22:50.476  5086  5100 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@46ef660 HexData = [00000000ef03000000000000ffffffff]
11-24 05:22:50.476  5086  5100 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 05:22:50.476  5086  5100 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-24 05:22:50.477  5086  5086 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 05:22:50.477  5061  5071 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-24 05:22:50.480  3930  3930 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-24 05:22:50.485  3930  5423 I iu.UploadsManager: num queued entries: 0
11-24 05:22:50.485  3930  5423 I iu.UploadsManager: num updated entries: 0
11-24 05:22:50.486  3930  5423 I iu.SyncManager: NEXT; no task
11-24 05:22:50.488  3930  3930 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-24 05:22:50.489  3930  3930 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-24 05:22:50.491  5769  5769 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 05:22:50.496  5769  5769 D SprintDMHelper: simOperator: 
11-24 05:22:50.496  5769  5769 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 05:22:50.498  3930  5867 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 05:22:50.504   507   917 E Netd    : netlink response contains error (No such file or directory)
,11-24 05:22:50.506   924  2987 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-24 05:22:50.506   924  2987 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-24 05:22:50.507  5829  5829 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-24 05:22:50.509  5035  5871 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-24 05:22:50.514  3930  5867 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-24 05:22:50.514  3930  5867 I SystemUpdateService: now status is 0 (complete)
,11-24 05:22:50.517  5829  5829 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-24 05:22:50.517  3930  5867 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 05:22:50.517  3930  5867 I SystemUpdateService: file has been verified
11-24 05:22:50.517  3930  5867 I SystemUpdateService: OTA package size = 21989297
,11-24 05:22:50.527  3930  5867 I SystemUpdateService: showing system update notification
,11-24 05:22:50.535  3930  3930 D SystemUpdateService: onDestroy
,11-24 05:22:50.621   924  2980 D wifi    : In wifi stop Hal
11-24 05:22:50.621   924  2980 D wifi    : halHandle = 0x7f8640de00, mVM = 0x7fa2a8d140, mCls = 0x1862
11-24 05:22:50.622  5035  5035 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 05:22:50.623  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 05:22:50.623   924  5828 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-24 05:22:50.623   924  5828 D WifiHAL : Got a signal to exit!!!
11-24 05:22:50.624   924  5828 I WifiHAL : Exit wifi_event_loop
11-24 05:22:50.624   924  2980 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-24 05:22:50.624   924  2980 E WifiHAL : Event processing terminated
11-24 05:22:50.625   924  2980 D wifi    : In wifi cleaned up handler
,11-24 05:22:50.625   924  2980 I WifiHAL : Internal cleanup completed
,11-24 05:22:50.629  4098  4233 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 05:22:50.649   924  5828 D wifi    : set interface wlan0 flags (DOWN)
,11-24 05:22:50.649   924  2980 D WifiNative-HAL: HAL event thread stopped successfully
,11-24 05:22:50.856   924   942 D Tethering: InitialState.processMessage what=4
,11-24 05:22:50.862   924   942 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-24 05:22:50.959   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 05:22:51.116   924  2987 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-24 05:22:55.388   924   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5ae6097:true
,11-24 05:22:55.390  5755  5755 D BluetoothAdapterState: make() - Creating AdapterState
,11-24 05:22:55.395  5755  5755 I bt_bluedroid: init
,11-24 05:22:55.395  5755  5873 I BluetoothAdapterState: Entering OffState
,11-24 05:22:55.399  5755  5874 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-24 05:22:55.399  5755  5874 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-24 05:22:55.399  5755  5874 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-24 05:22:55.399  5755  5874 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-24 05:22:55.401  5755  5755 I bt_bluedroid: get_profile_interface socket
,11-24 05:22:55.403  5755  5755 I bt_bluedroid: get_profile_interface sdp
,11-24 05:22:55.404  5755  5877 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
11-24 05:22:55.406  5755  5877 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 05:22:55.411  5755  5766 I bt_bluedroid: config_hci_snoop_log
,11-24 05:22:55.413   924   942 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-24 05:22:55.419  5755  5873 D BluetoothAdapterState: Current state: OFF, message: 0
,11-24 05:22:55.419  5755  5873 D BluetoothAdapterProperties: Setting state to 14
11-24 05:22:55.419  5755  5873 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-24 05:22:55.421  5755  5873 D BluetoothBondStateMachine: make
,11-24 05:22:55.423  5755  5878 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-24 05:22:55.427  5755  5873 I BluetoothAdapterState: Entering PendingCommandState
,11-24 05:22:55.428  5755  5755 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-24 05:22:55.431  5755  5755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32cd051
,11-24 05:22:55.432  5755  5755 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-24 05:22:55.433  5755  5755 D BtGatt.GattService: Received start request. Starting profile...
,11-24 05:22:55.433  5755  5755 D BtGatt.GattService: start()
11-24 05:22:55.433  5755  5755 I bt_bluedroid: get_profile_interface gatt
,11-24 05:22:55.434  5755  5755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32cd051
11-24 05:22:55.434  5755  5755 D BtGatt.AdvertiseManager: advertise manager created
,11-24 05:22:55.441  5755  5755 V BluetoothAdapterState: isTurningOff()=false
,11-24 05:22:55.441  5755  5755 V BluetoothAdapterState: isTurningOn()=false
11-24 05:22:55.441  5755  5755 V BluetoothAdapterState: isBleTurningOn()=true
11-24 05:22:55.441  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
11-24 05:22:55.441  5755  5873 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-24 05:22:55.443  5755  5873 I bt_bluedroid: bt_bluedroid
,11-24 05:22:55.443  5755  5874 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-24 05:22:55.443  5755  5874 I bt_hci  : start_up
,11-24 05:22:55.449  5755  5874 I bt_vendor: alloc value 0xf4178871
11-24 05:22:55.449  5755  5874 I bt_vendor: init
,11-24 05:22:55.449  5755  5874 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-24 05:22:55.449  5755  5874 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-24 05:22:55.563  5755  5874 D bt_hci  : start_up starting async portion
11-24 05:22:55.564  5755  5881 I bt_hci  : event_finish_startup
11-24 05:22:55.564  5755  5881 I bt_hci_h4: hal_open
11-24 05:22:55.564  5755  5881 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-24 05:22:55.562  5882  5882 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 05:22:55.568  5755  5881 I bt_userial_vendor: device fd = 54 open
,11-24 05:22:55.583  5755  5881 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 05:22:55.586  5755  5881 D bt_hwcfg: Chipset BCM4358A3
,11-24 05:22:55.586  5755  5881 D bt_hwcfg: Target name = [BCM4358A3]
11-24 05:22:55.587  5755  5881 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-24 05:22:55.990  5755  5881 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-24 05:22:55.990  5755  5881 D bt_hwcfg: Settlement delay -- 100 ms
,11-24 05:22:55.990  5755  5881 I bt_hwcfg: Setting fw settlement delay to 100 
,11-24 05:22:56.124  5755  5881 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 05:22:56.125  5755  5881 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,11-24 05:22:56.127  5755  5881 I bt_hwcfg: vendor lib fwcfg completed
,11-24 05:22:56.127  5755  5881 I bt_vendor: firmware callback
,11-24 05:22:56.127  5755  5881 I bt_hci  : firmware_config_callback
,11-24 05:22:56.137  5755  5884 I bt_btu  : btu_task pending for preload complete event
,11-24 05:22:56.137  5755  5884 I bt_btu_task: Bluetooth chip preload is complete
11-24 05:22:56.137  5755  5884 I bt_btu  : btu_task received preload complete event
,11-24 05:22:56.143  5755  5884 I         : BTE_InitTraceLevels -- TRC_HCI
,11-24 05:22:56.143  5755  5884 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-24 05:22:56.143  5755  5884 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-24 05:22:56.144  5755  5884 I         : BTE_InitTraceLevels -- TRC_AVDT
11-24 05:22:56.144  5755  5884 I         : BTE_InitTraceLevels -- TRC_AVRC
11-24 05:22:56.144  5755  5884 I         : BTE_InitTraceLevels -- TRC_A2D
11-24 05:22:56.144  5755  5884 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-24 05:22:56.144  5755  5884 I         : BTE_InitTraceLevels -- TRC_BTM
11-24 05:22:56.144  5755  5884 I         : BTE_InitTraceLevels -- TRC_GAP
11-24 05:22:56.144  5755  5884 I         : BTE_InitTraceLevels -- TRC_PAN
11-24 05:22:56.144  5755  5884 I         : BTE_InitTraceLevels -- TRC_SDP
,11-24 05:22:56.144  5755  5884 I         : BTE_InitTraceLevels -- TRC_GATT
11-24 05:22:56.144  5755  5884 I         : BTE_InitTraceLevels -- TRC_SMP
11-24 05:22:56.144  5755  5884 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-24 05:22:56.145  5755  5884 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-24 05:22:56.225  5755  5884 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf40f6549
11-24 05:22:56.226  5755  5884 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf40f6549 
,11-24 05:22:56.237  5755  5877 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-24 05:22:56.239  5755  5877 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-24 05:22:56.240  5755  5877 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-24 05:22:56.242  5755  5877 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 05:22:56.245  5755  5877 D BluetoothAdapterProperties: Scan Mode:20
,11-24 05:22:56.245  5755  5877 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-24 05:22:56.246  5755  5877 D bt_hci  : do_postload posting postload work item
,11-24 05:22:56.246  5755  5881 I bt_hci  : event_postload
,11-24 05:22:56.246  5755  5881 I bt_vendor: sco_config_cb
,11-24 05:22:56.246  5755  5881 I bt_hci  : sco_config_callback postload finished.
11-24 05:22:56.251  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 05:22:56.254  5755  5877 D bt_bte_conf: Device ID record 1 : primary
,11-24 05:22:56.254  5755  5877 D bt_bte_conf:   vendorId            = 000f
11-24 05:22:56.254  5755  5877 D bt_bte_conf:   vendorIdSource      = 0001
11-24 05:22:56.254  5755  5877 D bt_bte_conf:   product             = 1200
11-24 05:22:56.254  5755  5881 I bt_vendor: low_power_mode_cb
11-24 05:22:56.254  5755  5877 D bt_bte_conf:   version             = 1436
11-24 05:22:56.254  5755  5877 D bt_bte_conf:   clientExecutableURL = 
11-24 05:22:56.255  5755  5877 D bt_bte_conf:   serviceDescription  = 
11-24 05:22:56.255  5755  5877 D bt_bte_conf:   documentationURL    = 
,11-24 05:22:56.255  5755  5877 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-24 05:22:56.255  5755  5874 D bt_stack_manager: event_start_up_stack finished
11-24 05:22:56.256  5755  5873 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-24 05:22:56.257  5755  5873 D BluetoothAdapterProperties: Setting state to 15
11-24 05:22:56.257  5755  5873 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-24 05:22:56.258  5755  5873 I BluetoothAdapterState: Entering BleOnState
,11-24 05:22:56.265  5755  5873 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-24 05:22:56.266  5755  5873 D BluetoothAdapterProperties: Setting state to 11
11-24 05:22:56.266  5755  5873 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-24 05:22:56.274  5755  5755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32cd051
,11-24 05:22:56.275  5755  5755 D HeadsetService: Received start request. Starting profile...
,11-24 05:22:56.277  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 05:22:56.282  5755  5755 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-24 05:22:56.282  5755  5755 D HeadsetStateMachine: make
,11-24 05:22:56.289  5755  5873 I BluetoothAdapterState: Entering PendingCommandState
,11-24 05:22:56.292  5755  5755 D HeadsetStateMachine: max_hf_connections = 1
11-24 05:22:56.293  5755  5755 I bt_bluedroid: get_profile_interface handsfree
,11-24 05:22:56.293  5755  5877 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,11-24 05:22:56.293  5755  5877 E bt_btif : btif_hf_upstreams_evt: Invalid index -1
,11-24 05:22:56.296  5755  5755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32cd051
,11-24 05:22:56.297  5755  5755 D A2dpService: Received start request. Starting profile...
,11-24 05:22:56.298  5755  5755 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-24 05:22:56.298  5755  5755 I bt_bluedroid: get_profile_interface avrcp
,11-24 05:22:56.303  5755  5755 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-24 05:22:56.304  5755  5755 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-24 05:22:56.304  5755  5755 D A2dpStateMachine: make
,11-24 05:22:56.305  5755  5755 I bt_bluedroid: get_profile_interface a2dp
11-24 05:22:56.305  5755  5877 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-24 05:22:56.307  5755  5892 D A2dpStateMachine: Enter Disconnected: -2
,11-24 05:22:56.307  5755  5755 I BluetoothHidServiceJni: classInitNative: succeeds
,11-24 05:22:56.308  5755  5755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32cd051
,11-24 05:22:56.309  5755  5755 D HidService: Received start request. Starting profile...
,11-24 05:22:56.309  5691  5691 D BluetoothInputDevice: Proxy object connected
11-24 05:22:56.309  5755  5755 I bt_bluedroid: get_profile_interface hidhost
11-24 05:22:56.309  5755  5755 D HidService: setHidService(): set to: null
,11-24 05:22:56.310  5755  5877 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf40d756d
11-24 05:22:56.310  5691  5691 D HidProfile: Bluetooth service connected
11-24 05:22:56.310  5755  5877 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-24 05:22:56.311  5755  5755 I BluetoothHealthServiceJni: classInitNative: succeeds
11-24 05:22:56.312  5755  5755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32cd051
,11-24 05:22:56.312  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 05:22:56.312  5755  5755 D HealthService: Received start request. Starting profile...
11-24 05:22:56.314  5755  5755 I bt_bluedroid: get_profile_interface health
,11-24 05:22:56.315  5755  5755 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-24 05:22:56.315  5755  5755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32cd051
,11-24 05:22:56.316  5691  5691 D BluetoothPan: BluetoothPAN Proxy object connected
,11-24 05:22:56.317  5755  5755 D PanService: Received start request. Starting profile...
11-24 05:22:56.317  5755  5755 D BluetoothPanServiceJni: initializeNative(L110): pan
11-24 05:22:56.317  5755  5755 I bt_bluedroid: get_profile_interface pan
11-24 05:22:56.317  5691  5691 D PanProfile: Bluetooth service connected
11-24 05:22:56.317  5755  5877 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-24 05:22:56.319  5755  5755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32cd051
,11-24 05:22:56.320  5755  5755 D BluetoothMapService: Received start request. Starting profile...
,11-24 05:22:56.321  5755  5755 D BluetoothMapService: start()
11-24 05:22:56.323  5755  5755 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-24 05:22:56.324  5755  5755 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-24 05:22:56.324  5755  5755 D BluetoothMapAppObserver: createReceiver()
11-24 05:22:56.325  5755  5755 D BluetoothMapAppObserver: initObservers()
11-24 05:22:56.325  5755  5755 D BluetoothMapAppObserver: getEnabledAccountItems()
11-24 05:22:56.330  5691  5691 D BluetoothMap: Proxy object connected
,11-24 05:22:56.330  5691  5691 D MapProfile: Bluetooth service connected
11-24 05:22:56.330  5691  5691 D BluetoothMap: getConnectedDevices()
11-24 05:22:56.331  5691  5691 D BluetoothMap: Bluetooth is Not enabled
11-24 05:22:56.332  5755  5755 V SapService: SapBinder()
11-24 05:22:56.332  5755  5755 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32cd051
,11-24 05:22:56.333  5755  5755 D SapService: Received start request. Starting profile...
,11-24 05:22:56.333  5755  5755 V SapService: start()
11-24 05:22:56.335  5755  5755 V BluetoothAdapterState: isTurningOff()=false
11-24 05:22:56.336  5755  5755 V BluetoothAdapterState: isTurningOn()=true
11-24 05:22:56.336  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
11-24 05:22:56.336  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
11-24 05:22:56.336  5755  5890 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-24 05:22:56.336  5755  5755 V BluetoothAdapterState: isTurningOff()=false
11-24 05:22:56.336  5755  5755 V BluetoothAdapterState: isTurningOn()=true
11-24 05:22:56.336  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
11-24 05:22:56.336  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
11-24 05:22:56.336  5755  5755 V BluetoothAdapterState: isTurningOff()=false
11-24 05:22:56.336  5755  5755 V BluetoothAdapterState: isTurningOn()=true
11-24 05:22:56.336  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
11-24 05:22:56.336  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
11-24 05:22:56.336  5755  5755 V BluetoothAdapterState: isTurningOff()=false
11-24 05:22:56.336  5755  5755 V BluetoothAdapterState: isTurningOn()=true
,11-24 05:22:56.336  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
11-24 05:22:56.337  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
11-24 05:22:56.337  5755  5755 V BluetoothAdapterState: isTurningOff()=false
11-24 05:22:56.337  5755  5755 V BluetoothAdapterState: isTurningOn()=true
11-24 05:22:56.337  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
11-24 05:22:56.337  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
11-24 05:22:56.337  5755  5755 V BluetoothAdapterState: isTurningOff()=false
11-24 05:22:56.337  5755  5755 V BluetoothAdapterState: isTurningOn()=true
11-24 05:22:56.337  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
11-24 05:22:56.337  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 05:22:56.338  5755  5755 V BluetoothAdapterState: isTurningOff()=false
11-24 05:22:56.338  5755  5755 V BluetoothAdapterState: isTurningOn()=true
11-24 05:22:56.338  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
11-24 05:22:56.338  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
11-24 05:22:56.338  5755  5873 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-24 05:22:56.338  5755  5873 D BluetoothAdapterProperties: ScanMode =  20
11-24 05:22:56.338  5755  5873 D BluetoothAdapterProperties: State =  11
,11-24 05:22:56.339  5755  5877 D BluetoothAdapterProperties: Scan Mode:21
11-24 05:22:56.340  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
,11-24 05:22:56.340  5755  5877 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 05:22:56.340  5755  5873 D BluetoothAdapterProperties: Setting state to 12
11-24 05:22:56.340  5755  5873 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-24 05:22:56.340   924   942 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 05:22:56.340   924   942 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 05:22:56.341  3143  3983 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 05:22:56.341  5755  5873 I BluetoothAdapterState: Entering OnState
,11-24 05:22:56.344  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 05:22:56.344  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 05:22:56.344  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 05:22:56.344  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 05:22:56.344  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 05:22:56.344  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 05:22:56.344  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 05:22:56.344  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 05:22:56.344  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 05:22:56.344  3792  3819 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 05:22:56.345  3143  3156 D BluetoothPan: onBluetoothStateChange on: true
11-24 05:22:56.346  5635  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 05:22:56.347  3143  3143 D BluetoothPan: BluetoothPAN Proxy object connected
,11-24 05:22:56.347  3143  3143 D PanProfile: Bluetooth service connected
,11-24 05:22:56.347  3143  3384 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-24 05:22:56.348  3143  3143 D BluetoothInputDevice: Proxy object connected
11-24 05:22:56.349  3143  3983 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 05:22:56.349  3143  3143 D HidProfile: Bluetooth service connected
,11-24 05:22:56.349  5691  5709 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 05:22:56.350  3143  3156 D BluetoothMap: onBluetoothStateChange: up=true
,11-24 05:22:56.351  3143  3143 D BluetoothMap: Proxy object connected
,11-24 05:22:56.351  5691  5705 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 05:22:56.352  5755  5755 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 05:22:56.352  3143  3143 D MapProfile: Bluetooth service connected
11-24 05:22:56.352  3143  3143 D BluetoothMap: getConnectedDevices()
11-24 05:22:56.352  5755  5755 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-24 05:22:56.353  5691  5709 D BluetoothPan: onBluetoothStateChange on: true
,11-24 05:22:56.353  3143  3154 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-24 05:22:56.353  5755  5755 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 05:22:56.355   924   942 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 05:22:56.355  5755  5755 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 05:22:56.356  5691  5705 D BluetoothMap: onBluetoothStateChange: up=true
11-24 05:22:56.356   924   942 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 05:22:56.356  5755  5755 D ObexServerSockets: Succeed to create listening sockets 
,11-24 05:22:56.356  5755  5755 D ObexServerSockets0: startAccept()
11-24 05:22:56.356  5755  5755 D ObexServerSockets0: prepareForNewConnect()
,11-24 05:22:56.357   924   924 I Telecom : BluetoothPhoneService: queryPhoneState
11-24 05:22:56.357  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-24 05:22:56.358  5755  5755 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,11-24 05:22:56.358  5755  5755 D BluetoothSdpJni: SDP Create record success - handle: 0
11-24 05:22:56.359  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 05:22:56.359  5755  5897 D ObexServerSockets0: Accepting socket connection...
11-24 05:22:56.360   924   924 D BluetoothA2dp: Proxy object connected
11-24 05:22:56.360  5755  5898 D ObexServerSockets0: Accepting socket connection...
,11-24 05:22:56.360  5755  5755 D BluetoothMapService: onReceive
11-24 05:22:56.360  5755  5755 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 05:22:56.361  5755  5755 D BluetoothMapService: STATE_ON
,11-24 05:22:56.361  3143  3143 D BluetoothA2dp: Proxy object connected
,11-24 05:22:56.363  5755  5900 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 05:22:56.363  5691  5691 D LocalBluetoothProfileManager: Adding local A2DP profile
11-24 05:22:56.364  5755  5900 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-24 05:22:56.364  5755  5900 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-24 05:22:56.367  5691  5691 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-24 05:22:56.375  5691  5691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 05:22:56.378  5691  5691 D BluetoothA2dp: Proxy object connected
,11-24 05:22:56.381  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 05:22:56.383  5691  5691 D DockEventReceiver: finishStartingService: stopping service
,11-24 05:22:56.388  3143  3143 D BluetoothPbap: Proxy object connected
,11-24 05:22:56.388  3143  3143 D PbapServerProfile: Bluetooth service connected
,11-24 05:22:56.389  5691  5691 D BluetoothPbap: Proxy object connected
11-24 05:22:56.389  5691  5691 D PbapServerProfile: Bluetooth service connected
11-24 05:22:56.390  5755  5755 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 05:22:56.390  5755  5755 D ObexServerSockets0: prepareForNewConnect()
,11-24 05:22:56.400  5755  5904 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 05:22:56.409  5755  5908 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 05:22:56.410  5755  5908 I BtOppRfcommListener: Accept thread started.
,11-24 05:22:56.442   924   924 D BluetoothHeadset: Proxy object connected
,11-24 05:22:56.442   924   924 D BluetoothHeadset: Proxy object connected
11-24 05:22:56.442   924   924 D BluetoothHeadset: Proxy object connected
11-24 05:22:56.442  3143  3156 D BluetoothHeadset: Proxy object connected
11-24 05:22:56.442  3143  3143 D HeadsetProfile: Bluetooth service connected
11-24 05:22:56.443  3792  4023 D BluetoothHeadset: Proxy object connected
,11-24 05:22:56.446  3792  3818 D BluetoothHeadset: Proxy object connected
,11-24 05:22:56.449  3143  3384 D BluetoothHeadset: Proxy object connected
11-24 05:22:56.449  3143  3143 D HeadsetProfile: Bluetooth service connected
,11-24 05:22:56.456   924   942 D BluetoothHeadset: Proxy object connected
,11-24 05:22:56.472  5691  5705 D BluetoothHeadset: Proxy object connected
,11-24 05:22:56.473  5691  5691 D HeadsetProfile: Bluetooth service connected
,11-24 05:22:58.076   924  2987 D ConnectivityService: handlePromptUnvalidated 101
,11-24 05:23:00.362  5755  5873 D BluetoothAdapterState: Current state: ON, message: 23
,11-24 05:23:00.362  5755  5873 D BluetoothAdapterProperties: Setting state to 13
,11-24 05:23:00.362  5755  5873 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-24 05:23:00.364  5755  5873 D BluetoothAdapterProperties: onBluetoothDisable()
,11-24 05:23:00.365  5755  5873 I BluetoothAdapterState: Entering PendingCommandState
,11-24 05:23:00.373  5755  5755 D BluetoothMapService: onReceive
,11-24 05:23:00.374  5755  5755 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 05:23:00.374  5755  5755 D BluetoothMapService: STATE_TURNING_OFF
,11-24 05:23:00.375  5755  5755 D BluetoothMapService: MAP Service closeService in
11-24 05:23:00.375  5755  5755 D BluetoothMapMasInstance0: MAP Service shutdown
11-24 05:23:00.375  5755  5755 D ObexServerSockets0: shutdown(block = true)
11-24 05:23:00.376  5755  5897 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
,11-24 05:23:00.380  5755  5755 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 05:23:00.380  5755  5755 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 05:23:00.381  5755  5898 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-24 05:23:00.379  5755  5877 D BluetoothAdapterProperties: Scan Mode:20
11-24 05:23:00.381  5635  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 05:23:00.381  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 05:23:00.381  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 05:23:00.381  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 05:23:00.381  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 05:23:00.381  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 05:23:00.381  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 05:23:00.381  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 05:23:00.381  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 05:23:00.381  5635  5635 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 05:23:00.381  5755  5873 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-24 05:23:00.382  5691  5691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 05:23:00.382  5755  5886 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-24 05:23:00.384  5755  5755 I BtOppRfcommListener: stopping Accept Thread
,11-24 05:23:00.385  5755  5908 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-24 05:23:00.385  5755  5908 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-24 05:23:00.388  5635  5635 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 05:23:00.388  5635  5635 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 05:23:00.389  5755  5755 D HeadsetService: Received stop request...Stopping profile...
11-24 05:23:00.391   924   924 D BluetoothHeadset: Proxy object disconnected
11-24 05:23:00.391  5691  5705 D BluetoothHeadset: Proxy object disconnected
,11-24 05:23:00.392   924   924 D BluetoothHeadset: Proxy object disconnected
11-24 05:23:00.392   924   924 D BluetoothHeadset: Proxy object disconnected
11-24 05:23:00.392  3143  3384 D BluetoothHeadset: Proxy object disconnected
,11-24 05:23:00.393  3792  3819 D BluetoothHeadset: Proxy object disconnected
11-24 05:23:00.393  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 05:23:00.394  5755  5755 D A2dpService: Received stop request...Stopping profile...
11-24 05:23:00.394  5755  5892 D A2dpStateMachine: Exit Disconnected: -1
11-24 05:23:00.396  5755  5755 V BluetoothAdapterState: isTurningOff()=true
11-24 05:23:00.396  5755  5755 V BluetoothAdapterState: isTurningOn()=false
11-24 05:23:00.397  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
11-24 05:23:00.397  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
11-24 05:23:00.399   924   924 D BluetoothA2dp: Proxy object disconnected
11-24 05:23:00.401  3143  3143 D HeadsetProfile: Bluetooth service disconnected
,11-24 05:23:00.401  3143  3143 D BluetoothA2dp: Proxy object disconnected
11-24 05:23:00.402  5755  5755 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-24 05:23:00.402  5755  5755 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-24 05:23:00.402  5755  5877 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-24 05:23:00.402  5755  5884 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 05:23:00.403  5755  5884 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 05:23:00.403  5755  5884 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 05:23:00.403  5755  5877 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-24 05:23:00.403  5755  5755 D HidService: Received stop request...Stopping profile...
11-24 05:23:00.403  5755  5755 D HidService: Stopping Bluetooth HidService
11-24 05:23:00.404  3143  3143 D BluetoothInputDevice: Proxy object disconnected
11-24 05:23:00.404  3143  3143 D HidProfile: Bluetooth service disconnected
11-24 05:23:00.405  5691  5691 D DockEventReceiver: finishStartingService: stopping service
11-24 05:23:00.405  5691  5691 D HeadsetProfile: Bluetooth service disconnected
11-24 05:23:00.406  5691  5691 D BluetoothA2dp: Proxy object disconnected
11-24 05:23:00.406  5755  5755 D HealthService: Received stop request...Stopping profile...
11-24 05:23:00.407  5691  5691 D BluetoothInputDevice: Proxy object disconnected
11-24 05:23:00.407  5691  5691 D HidProfile: Bluetooth service disconnected
11-24 05:23:00.408  5755  5755 V BluetoothAdapterState: isTurningOff()=true
11-24 05:23:00.408  5755  5755 V BluetoothAdapterState: isTurningOn()=false
11-24 05:23:00.408  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
11-24 05:23:00.408  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 05:23:00.410  5755  5884 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 05:23:00.411  5755  5884 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 05:23:00.411  5755  5884 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 05:23:00.411  5755  5884 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-24 05:23:00.411  5755  5884 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-24 05:23:00.411  5755  5884 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 05:23:00.411  5755  5755 D PanService: Received stop request...Stopping profile...
11-24 05:23:00.411  5755  5877 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-24 05:23:00.412  5691  5691 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 05:23:00.412  5691  5691 D PanProfile: Bluetooth service disconnected
11-24 05:23:00.414  3143  3143 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 05:23:00.414  3143  3143 D PanProfile: Bluetooth service disconnected
,11-24 05:23:00.414  5755  5755 D BluetoothMapService: Received stop request...Stopping profile...
11-24 05:23:00.414  5755  5755 D BluetoothMapService: stop()
11-24 05:23:00.415  5755  5755 D BluetoothMapAppObserver: deinitObservers()
11-24 05:23:00.416  5755  5755 D BluetoothMapAppObserver: removeReceiver()
11-24 05:23:00.417  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 05:23:00.418  5691  5691 D BluetoothMap: Proxy object disconnected
11-24 05:23:00.418  5691  5691 D MapProfile: Bluetooth service disconnected
11-24 05:23:00.419  3143  3143 D BluetoothMap: Proxy object disconnected
11-24 05:23:00.419  3143  3143 D MapProfile: Bluetooth service disconnected
11-24 05:23:00.420  5755  5755 D SapService: Received stop request...Stopping profile...
,11-24 05:23:00.420  5755  5755 V SapService: stop()
11-24 05:23:00.421  5755  5755 V BluetoothAdapterState: isTurningOff()=true
11-24 05:23:00.421  5755  5755 V BluetoothAdapterState: isTurningOn()=false
11-24 05:23:00.421  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
11-24 05:23:00.421  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
11-24 05:23:00.421  5755  5755 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-24 05:23:00.422  5755  5755 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-24 05:23:00.422  5755  5877 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-24 05:23:00.422  5755  5755 V BluetoothAdapterState: isTurningOff()=true
11-24 05:23:00.422  5755  5755 V BluetoothAdapterState: isTurningOn()=false
11-24 05:23:00.422  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
11-24 05:23:00.422  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
11-24 05:23:00.422  5755  5755 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-24 05:23:00.422  5755  5755 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-24 05:23:00.422  5755  5877 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-24 05:23:00.423  5755  5755 V BluetoothAdapterState: isTurningOff()=true
,11-24 05:23:00.423  5755  5755 V BluetoothAdapterState: isTurningOn()=false
11-24 05:23:00.423  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
11-24 05:23:00.423  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
11-24 05:23:00.423  5755  5755 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-24 05:23:00.423  5755  5755 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-24 05:23:00.425  3143  3143 D BluetoothPbap: Proxy object disconnected
11-24 05:23:00.425  3143  3143 D PbapServerProfile: Bluetooth service disconnected
,11-24 05:23:00.426  5755  5755 D BluetoothMapService: MAP Service closeService in
,11-24 05:23:00.426  5755  5755 V BluetoothAdapterState: isTurningOff()=true
11-24 05:23:00.426  5755  5755 V BluetoothAdapterState: isTurningOn()=false
11-24 05:23:00.426  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
11-24 05:23:00.426  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
11-24 05:23:00.429  5755  5755 D BluetoothMapService: cleanup()
11-24 05:23:00.429  5755  5755 D BluetoothMapService: MAP Service closeService in
11-24 05:23:00.429  5691  5691 D BluetoothPbap: Proxy object disconnected
,11-24 05:23:00.429  5691  5691 D PbapServerProfile: Bluetooth service disconnected
11-24 05:23:00.429  5755  5755 V BluetoothAdapterState: isTurningOff()=true
11-24 05:23:00.430  5755  5755 V BluetoothAdapterState: isTurningOn()=false
11-24 05:23:00.430  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
11-24 05:23:00.430  5755  5755 V BluetoothAdapterState: isBleTurningOff()=false
11-24 05:23:00.430  5755  5873 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
,11-24 05:23:00.430  5755  5873 D BluetoothAdapterProperties: Setting state to 15
11-24 05:23:00.431  5755  5873 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,11-24 05:23:00.432  5755  5873 I BluetoothAdapterState: Entering BleOnState
11-24 05:23:00.432   924   942 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 05:23:00.432  5691  5709 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 05:23:00.437   924   942 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 05:23:00.437  5691  5705 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 05:23:00.437  3143  3154 D BluetoothPbap: onBluetoothStateChange: up=false
,11-24 05:23:00.438  3792  4023 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 05:23:00.446  3143  3156 D BluetoothPan: onBluetoothStateChange on: false
11-24 05:23:00.447  3143  3384 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-24 05:23:00.447  3143  3983 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 05:23:00.448  5691  5709 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-24 05:23:00.449  3143  3154 D BluetoothMap: onBluetoothStateChange: up=false
,11-24 05:23:00.451  5691  5705 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 05:23:00.452  5691  5709 D BluetoothPan: onBluetoothStateChange on: false
11-24 05:23:00.452  3143  3156 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 05:23:00.453   924   942 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 05:23:00.453  5691  5705 D BluetoothMap: onBluetoothStateChange: up=false
11-24 05:23:00.454   924   942 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 05:23:00.454  5755  5873 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-24 05:23:00.454  5755  5873 D BluetoothAdapterProperties: Setting state to 16
11-24 05:23:00.454  5755  5873 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-24 05:23:00.455  5755  5873 D BluetoothAdapterProperties: onBleDisable
11-24 05:23:00.455  5755  5873 I BluetoothAdapterState: Entering PendingCommandState
11-24 05:23:00.455  5755  5874 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-24 05:23:00.456  5755  5877 D BluetoothAdapterProperties: Scan Mode:20
,11-24 05:23:00.458  5755  5884 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,11-24 05:23:00.458  5755  5884 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-24 05:23:00.461  5691  5691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 05:23:00.463  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 05:23:00.465  5635  5635 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 05:23:00.468  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 05:23:00.470  5691  5691 D DockEventReceiver: finishStartingService: stopping service
,11-24 05:23:00.677  5755  5877 I bt_hci  : shut_down
,11-24 05:23:00.687  5755  5881 D bt_hwcfg: hw_epilog_process
,11-24 05:23:00.687  5755  5881 I bt_vendor: low_power_mode_cb
,11-24 05:23:00.690  5755  5881 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-24 05:23:00.691  5755  5881 I bt_vendor: epilog_cb
,11-24 05:23:00.691  5755  5881 I bt_hci  : epilog_finished_callback
,11-24 05:23:00.696  5755  5877 I bt_hci_h4: hal_close
,11-24 05:23:00.697  5755  5877 I bt_userial_vendor: device fd = 54 close
,11-24 05:23:00.813  5755  5874 D bt_stack_manager: event_shut_down_stack finished.
,11-24 05:23:00.814  5755  5873 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-24 05:23:00.818  5755  5873 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-24 05:23:00.818  5755  5755 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-24 05:23:00.819  5755  5755 D BtGatt.GattService: Received stop request...Stopping profile...
11-24 05:23:00.820  5755  5755 D BtGatt.GattService: stop()
,11-24 05:23:00.820  5755  5755 D BtGatt.AdvertiseManager: advertise clients cleared
11-24 05:23:00.824  5755  5755 V BluetoothAdapterState: isTurningOff()=false
,11-24 05:23:00.824  5755  5755 V BluetoothAdapterState: isTurningOn()=false
11-24 05:23:00.824  5755  5755 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 05:23:00.824  5755  5755 V BluetoothAdapterState: isBleTurningOff()=true
11-24 05:23:00.824  5755  5873 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-24 05:23:00.825  5755  5873 D BluetoothAdapterProperties: Setting state to 10
,11-24 05:23:00.825  5755  5873 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-24 05:23:00.826  5755  5873 I BluetoothAdapterState: Entering OffState
11-24 05:23:00.827   924   942 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-24 05:23:00.841  5755  5755 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-24 05:23:00.841  5755  5755 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-24 05:23:00.841  5755  5755 I BluetoothServiceJni: cleanupNative: return from cleanup
11-24 05:23:00.842  5755  5874 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-24 05:23:00.852  5755  5755 I art     : System.exit called, status: 0
,11-24 05:23:00.853  5755  5755 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-24 05:23:00.881   924  3172 I ActivityManager: Process com.android.bluetooth (pid 5755) has died
,11-24 05:23:00.960   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 05:23:01.961   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 05:23:02.962   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 05:23:03.962   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 05:23:04.964   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 05:23:05.360  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 05:23:05.360  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 05:23:05.366  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 05:23:05.366  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b5e97b6 removed from the list
11-24 05:23:05.366  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
11-24 05:23:05.369  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 05:23:05.369  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c2d138d added. We now have 4 listener(s)
,11-24 05:23:05.369  5635  5681 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 05:23:05.372  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:23:05.372  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c2d138d removed from the list
,11-24 05:23:05.373  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
11-24 05:23:05.375  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 05:23:05.375  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7347942 added. We now have 4 listener(s)
,11-24 05:23:05.375  5635  5681 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 05:23:05.964   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-24 05:23:10.386  5635  5681 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 05:23:10.424   924   942 I ActivityManager: Start proc 5918:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-24 05:23:10.516  5918  5918 D AdapterServiceConfig: Adding HeadsetService
,11-24 05:23:10.516  5918  5918 D AdapterServiceConfig: Adding A2dpService
11-24 05:23:10.516  5918  5918 D AdapterServiceConfig: Adding HidService
11-24 05:23:10.516  5918  5918 D AdapterServiceConfig: Adding HealthService
11-24 05:23:10.516  5918  5918 D AdapterServiceConfig: Adding PanService
,11-24 05:23:10.517  5918  5918 D AdapterServiceConfig: Adding GattService
,11-24 05:23:10.517  5918  5918 D AdapterServiceConfig: Adding BluetoothMapService
11-24 05:23:10.517  5918  5918 D AdapterServiceConfig: Adding SapService
,11-24 05:23:10.527   924   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a852344:true
11-24 05:23:10.528  5918  5918 D BluetoothAdapterState: make() - Creating AdapterState
,11-24 05:23:10.531  5918  5918 I bt_bluedroid: init
,11-24 05:23:10.531  5918  5930 I BluetoothAdapterState: Entering OffState
,11-24 05:23:10.534  5918  5931 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-24 05:23:10.534  5918  5931 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-24 05:23:10.534  5918  5931 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-24 05:23:10.534  5918  5931 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-24 05:23:10.535  5918  5918 I bt_bluedroid: get_profile_interface socket
,11-24 05:23:10.538  5918  5934 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-24 05:23:10.538  5918  5918 I bt_bluedroid: get_profile_interface sdp
11-24 05:23:10.539  5918  5934 D BluetoothAdapterProperties: Name is: Nexus 6P
11-24 05:23:10.542  5918  5929 I bt_bluedroid: config_hci_snoop_log
,11-24 05:23:10.543   924   942 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-24 05:23:10.547  5918  5930 D BluetoothAdapterState: Current state: OFF, message: 0
,11-24 05:23:10.547  5918  5930 D BluetoothAdapterProperties: Setting state to 14
11-24 05:23:10.548  5918  5930 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-24 05:23:10.549  5918  5930 D BluetoothBondStateMachine: make
11-24 05:23:10.550  5918  5935 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-24 05:23:10.552  5918  5930 I BluetoothAdapterState: Entering PendingCommandState
,11-24 05:23:10.554  5918  5918 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-24 05:23:10.555  5918  5918 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32cd051
11-24 05:23:10.556  5918  5918 D BtGatt.DebugUtils: handleDebugAction() action=null
11-24 05:23:10.557  5918  5918 D BtGatt.GattService: Received start request. Starting profile...
,11-24 05:23:10.557  5918  5918 D BtGatt.GattService: start()
,11-24 05:23:10.557  5918  5918 I bt_bluedroid: get_profile_interface gatt
11-24 05:23:10.558  5918  5918 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32cd051
11-24 05:23:10.558  5918  5918 D BtGatt.AdvertiseManager: advertise manager created
,11-24 05:23:10.563  5918  5918 V BluetoothAdapterState: isTurningOff()=false
11-24 05:23:10.563  5918  5918 V BluetoothAdapterState: isTurningOn()=false
11-24 05:23:10.563  5918  5918 V BluetoothAdapterState: isBleTurningOn()=true
,11-24 05:23:10.563  5918  5918 V BluetoothAdapterState: isBleTurningOff()=false
11-24 05:23:10.564  5918  5930 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-24 05:23:10.565  5918  5930 I bt_bluedroid: bt_bluedroid
,11-24 05:23:10.565  5918  5931 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-24 05:23:10.565  5918  5931 I bt_hci  : start_up
,11-24 05:23:10.570  5918  5931 I bt_vendor: alloc value 0xf41f7871
,11-24 05:23:10.570  5918  5931 I bt_vendor: init
11-24 05:23:10.570  5918  5931 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-24 05:23:10.570  5918  5931 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-24 05:23:10.680  5918  5931 D bt_hci  : start_up starting async portion
,11-24 05:23:10.680  5918  5938 I bt_hci  : event_finish_startup
11-24 05:23:10.681  5918  5938 I bt_hci_h4: hal_open
11-24 05:23:10.681  5918  5938 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-24 05:23:10.683  5918  5938 I bt_userial_vendor: device fd = 54 open
11-24 05:23:10.679  5939  5939 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 05:23:10.698  5918  5938 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 05:23:10.700  5918  5938 D bt_hwcfg: Chipset BCM4358A3
11-24 05:23:10.700  5918  5938 D bt_hwcfg: Target name = [BCM4358A3]
11-24 05:23:10.701  5918  5938 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-24 05:23:11.209  5918  5938 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-24 05:23:11.209  5918  5938 D bt_hwcfg: Settlement delay -- 100 ms
11-24 05:23:11.209  5918  5938 I bt_hwcfg: Setting fw settlement delay to 100 
,11-24 05:23:11.344  5918  5938 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-24 05:23:11.344  5918  5938 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
11-24 05:23:11.346  5918  5938 I bt_hwcfg: vendor lib fwcfg completed
11-24 05:23:11.346  5918  5938 I bt_vendor: firmware callback
11-24 05:23:11.346  5918  5938 I bt_hci  : firmware_config_callback
,11-24 05:23:11.356  5918  5941 I bt_btu  : btu_task pending for preload complete event
,11-24 05:23:11.356  5918  5941 I bt_btu_task: Bluetooth chip preload is complete
,11-24 05:23:11.357  5918  5941 I bt_btu  : btu_task received preload complete event
,11-24 05:23:11.363  5918  5941 I         : BTE_InitTraceLevels -- TRC_HCI
,11-24 05:23:11.363  5918  5941 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-24 05:23:11.364  5918  5941 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-24 05:23:11.364  5918  5941 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-24 05:23:11.364  5918  5941 I         : BTE_InitTraceLevels -- TRC_AVRC
11-24 05:23:11.364  5918  5941 I         : BTE_InitTraceLevels -- TRC_A2D
,11-24 05:23:11.364  5918  5941 I         : BTE_InitTraceLevels -- TRC_BNEP
11-24 05:23:11.364  5918  5941 I         : BTE_InitTraceLevels -- TRC_BTM
,11-24 05:23:11.364  5918  5941 I         : BTE_InitTraceLevels -- TRC_GAP
11-24 05:23:11.364  5918  5941 I         : BTE_InitTraceLevels -- TRC_PAN
11-24 05:23:11.365  5918  5941 I         : BTE_InitTraceLevels -- TRC_SDP
11-24 05:23:11.365  5918  5941 I         : BTE_InitTraceLevels -- TRC_GATT
,11-24 05:23:11.365  5918  5941 I         : BTE_InitTraceLevels -- TRC_SMP
11-24 05:23:11.365  5918  5941 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-24 05:23:11.365  5918  5941 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-24 05:23:11.457  5918  5941 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4175549
,11-24 05:23:11.457  5918  5941 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4175549 
,11-24 05:23:11.470  5918  5934 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-24 05:23:11.472  5918  5934 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-24 05:23:11.473  5918  5934 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-24 05:23:11.475  5918  5934 D BluetoothAdapterProperties: Name is: Nexus 6P
11-24 05:23:11.477  5918  5934 D BluetoothAdapterProperties: Scan Mode:20
,11-24 05:23:11.478  5918  5934 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-24 05:23:11.478  5918  5934 D bt_hci  : do_postload posting postload work item
,11-24 05:23:11.478  5918  5938 I bt_hci  : event_postload
11-24 05:23:11.478  5918  5938 I bt_vendor: sco_config_cb
,11-24 05:23:11.478  5918  5938 I bt_hci  : sco_config_callback postload finished.
,11-24 05:23:11.482  5918  5934 D bt_bte_conf: Device ID record 1 : primary
11-24 05:23:11.482  5918  5934 D bt_bte_conf:   vendorId            = 000f
11-24 05:23:11.482  5918  5934 D bt_bte_conf:   vendorIdSource      = 0001
11-24 05:23:11.482  5918  5934 D bt_bte_conf:   product             = 1200
11-24 05:23:11.482  5918  5934 D bt_bte_conf:   version             = 1436
11-24 05:23:11.482  5918  5934 D bt_bte_conf:   clientExecutableURL = 
11-24 05:23:11.482  5918  5934 D bt_bte_conf:   serviceDescription  = 
11-24 05:23:11.482  5918  5934 D bt_bte_conf:   documentationURL    = 
11-24 05:23:11.482  5918  5934 D bt_bte_conf: bte_load_did_conf no section named DID2.
,11-24 05:23:11.483  5918  5931 D bt_stack_manager: event_start_up_stack finished
11-24 05:23:11.483  5918  5930 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-24 05:23:11.484  5918  5930 D BluetoothAdapterProperties: Setting state to 15
11-24 05:23:11.484  5918  5930 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-24 05:23:11.485  5918  5930 I BluetoothAdapterState: Entering BleOnState
11-24 05:23:11.490  5918  5938 I bt_vendor: low_power_mode_cb
11-24 05:23:11.490  5918  5930 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-24 05:23:11.490  5918  5930 D BluetoothAdapterProperties: Setting state to 11
11-24 05:23:11.490  5918  5930 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-24 05:23:11.498  5918  5918 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32cd051
,11-24 05:23:11.501  5918  5918 D HeadsetService: Received start request. Starting profile...
,11-24 05:23:11.504  5918  5918 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-24 05:23:11.504  5918  5918 D HeadsetStateMachine: make
,11-24 05:23:11.519  5918  5918 D HeadsetStateMachine: max_hf_connections = 1
,11-24 05:23:11.519  5918  5918 I bt_bluedroid: get_profile_interface handsfree
11-24 05:23:11.519  5918  5934 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-24 05:23:11.519  5918  5934 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-24 05:23:11.524  5918  5918 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32cd051
,11-24 05:23:11.527  5918  5930 I BluetoothAdapterState: Entering PendingCommandState
,11-24 05:23:11.528  5918  5918 D A2dpService: Received start request. Starting profile...
,11-24 05:23:11.529  5918  5918 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-24 05:23:11.529  5918  5918 I bt_bluedroid: get_profile_interface avrcp
,11-24 05:23:11.535  5918  5918 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-24 05:23:11.536  5918  5918 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-24 05:23:11.536  5918  5918 D A2dpStateMachine: make
11-24 05:23:11.537  5918  5918 I bt_bluedroid: get_profile_interface a2dp
,11-24 05:23:11.537  5918  5934 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-24 05:23:11.539  5918  5948 D A2dpStateMachine: Enter Disconnected: -2
,11-24 05:23:11.541  5918  5918 I BluetoothHidServiceJni: classInitNative: succeeds
11-24 05:23:11.541  5918  5918 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32cd051
11-24 05:23:11.542  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 05:23:11.542  5918  5918 D HidService: Received start request. Starting profile...
11-24 05:23:11.543  5918  5918 I bt_bluedroid: get_profile_interface hidhost
11-24 05:23:11.543  5918  5918 D HidService: setHidService(): set to: null
11-24 05:23:11.543  5918  5934 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf415656d
11-24 05:23:11.543  5918  5934 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,11-24 05:23:11.543  5918  5918 I BluetoothHealthServiceJni: classInitNative: succeeds
11-24 05:23:11.544  5918  5918 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32cd051
11-24 05:23:11.544  5918  5918 D HealthService: Received start request. Starting profile...
,11-24 05:23:11.546  5918  5918 I bt_bluedroid: get_profile_interface health
,11-24 05:23:11.551  5918  5918 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-24 05:23:11.551  5918  5918 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32cd051
,11-24 05:23:11.552  5918  5918 D PanService: Received start request. Starting profile...
11-24 05:23:11.552  5918  5918 D BluetoothPanServiceJni: initializeNative(L110): pan
,11-24 05:23:11.552  5918  5918 I bt_bluedroid: get_profile_interface pan
11-24 05:23:11.553  5918  5934 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-24 05:23:11.554  5918  5918 V BluetoothAdapterState: isTurningOff()=false
11-24 05:23:11.554  5918  5918 V BluetoothAdapterState: isTurningOn()=true
11-24 05:23:11.554  5918  5918 V BluetoothAdapterState: isBleTurningOn()=false
11-24 05:23:11.554  5918  5918 V BluetoothAdapterState: isBleTurningOff()=false
11-24 05:23:11.554  5918  5946 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-24 05:23:11.555  5918  5918 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32cd051
11-24 05:23:11.556  5918  5918 D BluetoothMapService: Received start request. Starting profile...
11-24 05:23:11.556  5918  5918 D BluetoothMapService: start()
11-24 05:23:11.558  5918  5918 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-24 05:23:11.559  5918  5918 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-24 05:23:11.559  5918  5918 D BluetoothMapAppObserver: createReceiver()
11-24 05:23:11.561  5918  5918 D BluetoothMapAppObserver: initObservers()
11-24 05:23:11.561  5918  5918 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-24 05:23:11.564  5918  5918 V SapService: SapBinder()
,11-24 05:23:11.564  5918  5918 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32cd051
,11-24 05:23:11.566  5918  5918 D SapService: Received start request. Starting profile...
11-24 05:23:11.566  5918  5918 V SapService: start()
11-24 05:23:11.567  5918  5918 V BluetoothAdapterState: isTurningOff()=false
,11-24 05:23:11.567  5918  5918 V BluetoothAdapterState: isTurningOn()=true
11-24 05:23:11.567  5918  5918 V BluetoothAdapterState: isBleTurningOn()=false
11-24 05:23:11.567  5918  5918 V BluetoothAdapterState: isBleTurningOff()=false
11-24 05:23:11.567  5918  5918 V BluetoothAdapterState: isTurningOff()=false
11-24 05:23:11.567  5918  5918 V BluetoothAdapterState: isTurningOn()=true
11-24 05:23:11.567  5918  5918 V BluetoothAdapterState: isBleTurningOn()=false
11-24 05:23:11.567  5918  5918 V BluetoothAdapterState: isBleTurningOff()=false
11-24 05:23:11.568  5918  5918 V BluetoothAdapterState: isTurningOff()=false
11-24 05:23:11.568  5918  5918 V BluetoothAdapterState: isTurningOn()=true
11-24 05:23:11.568  5918  5918 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 05:23:11.568  5918  5918 V BluetoothAdapterState: isBleTurningOff()=false
11-24 05:23:11.568  5918  5918 V BluetoothAdapterState: isTurningOff()=false
11-24 05:23:11.568  5918  5918 V BluetoothAdapterState: isTurningOn()=true
11-24 05:23:11.568  5918  5918 V BluetoothAdapterState: isBleTurningOn()=false
11-24 05:23:11.568  5918  5918 V BluetoothAdapterState: isBleTurningOff()=false
11-24 05:23:11.568  5918  5918 V BluetoothAdapterState: isTurningOff()=false
11-24 05:23:11.568  5918  5918 V BluetoothAdapterState: isTurningOn()=true
,11-24 05:23:11.568  5918  5918 V BluetoothAdapterState: isBleTurningOn()=false
11-24 05:23:11.568  5918  5918 V BluetoothAdapterState: isBleTurningOff()=false
11-24 05:23:11.569  5918  5918 V BluetoothAdapterState: isTurningOff()=false
11-24 05:23:11.569  5918  5918 V BluetoothAdapterState: isTurningOn()=true
11-24 05:23:11.569  5918  5918 V BluetoothAdapterState: isBleTurningOn()=false
11-24 05:23:11.569  5918  5918 V BluetoothAdapterState: isBleTurningOff()=false
11-24 05:23:11.569  5918  5930 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
,11-24 05:23:11.570  5918  5930 D BluetoothAdapterProperties: ScanMode =  20
11-24 05:23:11.570  5918  5930 D BluetoothAdapterProperties: State =  11
11-24 05:23:11.570  5918  5930 D BluetoothAdapterProperties: Setting state to 12
,11-24 05:23:11.570  5918  5930 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-24 05:23:11.570  5918  5930 I BluetoothAdapterState: Entering OnState
11-24 05:23:11.570   924   942 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 05:23:11.571  5691  5709 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-24 05:23:11.571  5918  5934 D BluetoothAdapterProperties: Scan Mode:21
11-24 05:23:11.573  5918  5934 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 05:23:11.575   924   942 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 05:23:11.575  5691  5705 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 05:23:11.576  3143  3154 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 05:23:11.579  3792  4023 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 05:23:11.580  3143  3384 D BluetoothPan: onBluetoothStateChange on: true
,11-24 05:23:11.580  5691  5691 D BluetoothA2dp: Proxy object connected
,11-24 05:23:11.582  3143  3983 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 05:23:11.582  3143  3143 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 05:23:11.582  3143  3143 D PanProfile: Bluetooth service connected
,11-24 05:23:11.583  3143  3384 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 05:23:11.584  3143  3143 D BluetoothInputDevice: Proxy object connected
11-24 05:23:11.584  5691  5709 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 05:23:11.584  5918  5918 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 05:23:11.584  3143  3143 D HidProfile: Bluetooth service connected
,11-24 05:23:11.584  5918  5918 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-24 05:23:11.585  5918  5918 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 05:23:11.586  3143  3983 D BluetoothMap: onBluetoothStateChange: up=true
,11-24 05:23:11.586  5918  5918 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 05:23:11.588  5691  5705 D BluetoothPbap: onBluetoothStateChange: up=true
,11-24 05:23:11.588  5918  5918 D ObexServerSockets: Succeed to create listening sockets 
11-24 05:23:11.588  5918  5918 D ObexServerSockets0: startAccept()
11-24 05:23:11.588  5918  5918 D ObexServerSockets0: prepareForNewConnect()
11-24 05:23:11.589  5691  5709 D BluetoothPan: onBluetoothStateChange on: true
11-24 05:23:11.590  5918  5918 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-24 05:23:11.590  5918  5918 D BluetoothSdpJni: SDP Create record success - handle: 0
11-24 05:23:11.591  3143  3384 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 05:23:11.591  5918  5955 D ObexServerSockets0: Accepting socket connection...
11-24 05:23:11.591  5918  5956 D ObexServerSockets0: Accepting socket connection...
,11-24 05:23:11.592  3143  3143 D BluetoothMap: Proxy object connected
11-24 05:23:11.592  3143  3143 D MapProfile: Bluetooth service connected
11-24 05:23:11.592  3143  3143 D BluetoothMap: getConnectedDevices()
11-24 05:23:11.592   924   942 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 05:23:11.593   924   924 D BluetoothA2dp: Proxy object connected
11-24 05:23:11.593  5691  5705 D BluetoothMap: onBluetoothStateChange: up=true
11-24 05:23:11.593  3143  3143 D BluetoothA2dp: Proxy object connected
11-24 05:23:11.594   924   942 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 05:23:11.595  5691  5691 D BluetoothInputDevice: Proxy object connected
,11-24 05:23:11.595  5691  5691 D HidProfile: Bluetooth service connected
11-24 05:23:11.596  5918  5918 D BluetoothMapService: onReceive
11-24 05:23:11.596  5918  5918 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 05:23:11.596  5918  5918 D BluetoothMapService: STATE_ON
11-24 05:23:11.597   924   924 I Telecom : BluetoothPhoneService: queryPhoneState
11-24 05:23:11.598  5691  5691 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 05:23:11.598  5691  5691 D PanProfile: Bluetooth service connected
11-24 05:23:11.598  5691  5691 D BluetoothMap: Proxy object connected
11-24 05:23:11.598  5691  5691 D MapProfile: Bluetooth service connected
11-24 05:23:11.598  5691  5691 D BluetoothMap: getConnectedDevices()
11-24 05:23:11.600  5918  5958 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 05:23:11.603  5918  5958 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-24 05:23:11.603  5918  5958 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-24 05:23:11.604  5691  5691 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 05:23:11.610  3589  3589 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 05:23:11.611  5691  5691 D DockEventReceiver: finishStartingService: stopping service
,11-24 05:23:11.619  3143  3143 D BluetoothPbap: Proxy object connected
,11-24 05:23:11.619  3143  3143 D PbapServerProfile: Bluetooth service connected
,11-24 05:23:11.622  5691  5691 D BluetoothPbap: Proxy object connected
,11-24 05:23:11.622  5691  5691 D PbapServerProfile: Bluetooth service connected
,11-24 05:23:11.625  5918  5918 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-24 05:23:11.625  5918  5918 D ObexServerSockets0: prepareForNewConnect()
,11-24 05:23:11.629  5918  5962 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 05:23:11.643  5918  5966 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 05:23:11.644  5918  5966 I BtOppRfcommListener: Accept thread started.
,11-24 05:23:11.673   924   924 D BluetoothHeadset: Proxy object connected
,11-24 05:23:11.673  5691  5954 D BluetoothHeadset: Proxy object connected
,11-24 05:23:11.674   924   924 D BluetoothHeadset: Proxy object connected
11-24 05:23:11.674   924   924 D BluetoothHeadset: Proxy object connected
11-24 05:23:11.674  3143  3154 D BluetoothHeadset: Proxy object connected
11-24 05:23:11.674  3143  3143 D HeadsetProfile: Bluetooth service connected
11-24 05:23:11.675  3792  3818 D BluetoothHeadset: Proxy object connected
11-24 05:23:11.675   924   942 D BluetoothHeadset: Proxy object connected
,11-24 05:23:11.676  5691  5709 D BluetoothHeadset: Proxy object connected
11-24 05:23:11.677  5691  5691 D HeadsetProfile: Bluetooth service connected
11-24 05:23:11.678  5691  5691 D HeadsetProfile: Bluetooth service connected
11-24 05:23:11.680  3792  3819 D BluetoothHeadset: Proxy object connected
,11-24 05:23:11.684  3143  3156 D BluetoothHeadset: Proxy object connected
,11-24 05:23:11.685  3143  3143 D HeadsetProfile: Bluetooth service connected
,11-24 05:23:11.695   924   942 D BluetoothHeadset: Proxy object connected
,11-24 05:23:15.401  5635  5681 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 05:23:15.401  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 05:23:15.401  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 05:23:15.401  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 05:23:15.401  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 05:23:15.401  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 05:23:15.401  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 05:23:15.401  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 05:23:15.401  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 05:23:15.407  5635  5681 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 05:23:15.408  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 05:23:15.408  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7347942 removed from the list
11-24 05:23:15.408  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 05:23:15.410  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 05:23:15.410  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@955ed53 added. We now have 4 listener(s)
11-24 05:23:15.410  5635  5681 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 05:23:15.414   924   935 D WifiService: setWifiEnabled: false pid=5635, uid=10077
11-24 05:23:15.414   924   935 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 05:23:20.423  5635  5681 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 05:23:20.425   924  3817 D WifiService: setWifiEnabled: true pid=5635, uid=10077
,11-24 05:23:20.425   924  3817 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 05:23:20.434   507   917 D SoftapController: Softap fwReload - Ok
,11-24 05:23:20.438   507   917 D CommandListener: Setting iface cfg
,11-24 05:23:20.439   507   917 D CommandListener: Trying to bring down wlan0
11-24 05:23:20.440   507   917 D CommandListener: Clearing all IP addresses on wlan0
11-24 05:23:20.444   924  2980 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 05:23:20.966   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 05:23:21.130   924  2980 D wifi    : set interface wlan0 flags (UP)
,11-24 05:23:21.130   924  2980 I WifiHAL : Initializing wifi
11-24 05:23:21.131   924  2980 I WifiHAL : Creating socket
,11-24 05:23:21.136   924   942 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-24 05:23:21.138   924  2980 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-24 05:23:21.138   924  2980 D wifi    : Did set static halHandle = 0x7f8640de00
11-24 05:23:21.138   924  2980 D wifi    : halHandle = 0x7f8640de00, mVM = 0x7fa2a8d140, mCls = 0x2016b2
11-24 05:23:21.138   924  2980 D wifi    : array field set
,11-24 05:23:21.139   924  2980 I WifiNative-HAL: interface[0] = wlan0
11-24 05:23:21.141   924  5971 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547713244672
11-24 05:23:21.141   924  5971 D wifi    : waitForHalEvents called, vm = 0x7fa2a8d140, obj = 0x2016b2, env = 0x7f88df9d00
,11-24 05:23:21.200  5972  5972 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-24 05:23:21.222  5972  5972 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 05:23:21.243   924  2980 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-24 05:23:21.245  5972  5972 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-24 05:23:21.245  5972  5972 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-24 05:23:21.265   924  2980 D WifiConfigStore: Loading config and enabling all networks 
,11-24 05:23:21.284   924  2980 D WifiConfigStore: loaded 0 passpoint configs
11-24 05:23:21.285   924  2980 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
11-24 05:23:21.285   924  2980 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-24 05:23:21.286   924  2980 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-24 05:23:21.286   924  2980 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-24 05:23:21.286   924  2980 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-24 05:23:21.286   924  2980 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-24 05:23:21.287   924  2980 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-24 05:23:21.289   924  2980 D WifiNative-HAL: Setting external_sim to 1
,11-24 05:23:21.289   924  2980 D wifi    : setting dfs flag to true, 0x7f8643c680
11-24 05:23:21.289  5035  5035 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 05:23:21.289   924  2980 D WifiStateMachine: Setting OUI to DA-A1-19
11-24 05:23:21.289   924  2980 D wifi    : setting scan oui 0x7f8643c680
,11-24 05:23:21.289   924  2980 D WifiHAL : Sending mac address OUI
,11-24 05:23:21.293   924  2980 E native  : do suspend false
,11-24 05:23:21.303   924  2980 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-24 05:23:21.303   924   924 D RttService: SCAN_AVAILABLE : 3
11-24 05:23:21.303   924  3095 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-24 05:23:21.308   507   917 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-24 05:23:21.310   507   917 D CommandListener: Setting iface cfg
,11-24 05:23:21.312   924  2964 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '161 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 161 Failed to set address (No such device)'
11-24 05:23:21.313   924  2964 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-24 05:23:21.318   924  2964 D WifiNative-HAL: p2pGetDeviceAddress
,11-24 05:23:21.324   924  2964 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-24 05:23:21.324   924   940 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=163854 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,11-24 05:23:21.968   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 05:23:22.970   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 05:23:23.971   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 05:23:24.388  5972  5972 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 05:23:24.396  5972  5972 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 05:23:24.401  5972  5972 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 05:23:24.428   924  2980 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-24 05:23:24.429   924  2980 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-24 05:23:24.429   924  2980 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 05:23:24.438   924  2980 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-24 05:23:24.467   924  2980 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-24 05:23:24.470  5972  5972 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-24 05:23:24.889  5972  5972 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-24 05:23:24.924  5972  5972 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-24 05:23:24.925  5972  5972 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-24 05:23:24.934   924  2980 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-24 05:23:24.935   924  2980 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-24 05:23:24.935   924  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-24 05:23:24.949   924  2980 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 05:23:24.960   507   917 D CommandListener: Setting iface cfg
,11-24 05:23:24.966   924  2980 D WifiStateMachine: Start Dhcp Watchdog 3
,11-24 05:23:24.972   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 05:23:24.975   924  5977 D DhcpClient: Receive thread started
11-24 05:23:24.976   924  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-24 05:23:24.976   924  2980 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-24 05:23:24.976   924  2987 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-24 05:23:25.057   924  2980 E native  : do suspend false
,11-24 05:23:25.071   924  5976 D DhcpClient: Broadcasting DHCPDISCOVER
,11-24 05:23:25.085   924  5977 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,11-24 05:23:25.085   924  5976 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,11-24 05:23:25.089   924  5976 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-24 05:23:25.101   924  5977 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-24 05:23:25.102   924  5976 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-24 05:23:25.107   507   917 D CommandListener: Setting iface cfg
,11-24 05:23:25.111   924  2980 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-24 05:23:25.118   924  5976 D DhcpClient: Scheduling renewal in 86399s
,11-24 05:23:25.130   924  2980 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-24 05:23:25.133   924  2980 D WifiConfigStore: No blacklist allowed without epno enabled
11-24 05:23:25.136   924  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-24 05:23:25.138   924  2987 D ConnectivityService: Adding iface wlan0 to network 102
11-24 05:23:25.147   924  2980 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-24 05:23:25.189   924  2987 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-24 05:23:25.189   924  2987 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-24 05:23:25.197   924  2987 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-24 05:23:25.200   924  2987 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-24 05:23:25.201   924  2987 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-24 05:23:25.210   924  2987 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 05:23:25.214   924  2987 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-24 05:23:25.214   924  2987 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
,11-24 05:23:25.214   924  2980 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-24 05:23:25.214   924  2980 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 05:23:25.214   924  2987 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-24 05:23:25.214   924  2987 D ConnectivityService:    accepting network in place of null
,11-24 05:23:25.215   924  2987 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 05:23:25.225   924  5975 D NetlinkSocketObserver: NeighborEvent{elapsedMs=167755, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 05:23:25.236   507   917 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 05:23:25.257   507   917 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 05:23:25.260   924  2987 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-24 05:23:25.260  3755  3912 W QCNEJ   : |CORE| network available: 102
11-24 05:23:25.260   924  2987 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-24 05:23:25.261   924  2987 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-24 05:23:25.262   924   942 D Tethering: MasterInitialState.processMessage what=3
11-24 05:23:25.264  3755  3912 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-24 05:23:25.267  3755  3912 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-24 05:23:25.267  3755  3912 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-24 05:23:25.272  3930  3930 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-24 05:23:25.274  5061  5085 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-24 05:23:25.274  5061  5085 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 05:23:25.274  5061  5085 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-24 05:23:25.274  5061  5085 E SarControlService: no key has been found,reset the power
11-24 05:23:25.275  5061  5098 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 05:23:25.275  5061  5098 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 05:23:25.275  5061  5098 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 05:23:25.275  5086  5086 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 05:23:25.275  5086  5086 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-24 05:23:25.276  5061  5098 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 05:23:25.276  5061  5098 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 05:23:25.276  5061  5098 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-24 05:23:25.277  5086  5086 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 05:23:25.277  5086  5086 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 05:23:25.281  3930  3930 D SystemUpdateService: onCreate
,11-24 05:23:25.283  5086  5100 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@46ef660 HexData = [00000000f003000000000000ffffffff]
11-24 05:23:25.284  5086  5100 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 05:23:25.284  5086  5100 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
11-24 05:23:25.284  5086  5086 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 05:23:25.284  5061  5072 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-24 05:23:25.286  5086  5100 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@46ef660 HexData = [00000000f103000000000000ffffffff]
,11-24 05:23:25.286  5086  5100 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 05:23:25.286  5086  5100 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-24 05:23:25.286  5086  5086 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 05:23:25.287  5061  5071 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-24 05:23:25.289  3930  3930 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-24 05:23:25.291   924  5974 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-24 05:23:25.297  3930  5987 I SystemUpdateService: active receiver: enabled
,11-24 05:23:25.300  3930  5987 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 05:23:25.302  3930  5987 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-24 05:23:25.302  3930  5987 I SystemUpdateService: now status is 0 (complete)
11-24 05:23:25.302  3930  5987 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 05:23:25.302  3930  5987 I SystemUpdateService: file has been verified
11-24 05:23:25.302  3930  5987 I SystemUpdateService: OTA package size = 21989297
,11-24 05:23:25.318  3930  3930 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-24 05:23:25.320  3930  5423 I iu.UploadsManager: num queued entries: 0
,11-24 05:23:25.321  3930  5423 I iu.UploadsManager: num updated entries: 0
,11-24 05:23:25.321  3930  5423 I iu.SyncManager: NEXT; no task
,11-24 05:23:25.331  3930  3930 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 05:23:25.332  3930  3930 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 05:23:25.333  3930  5987 I SystemUpdateService: showing system update notification
,11-24 05:23:25.335  5769  5769 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 05:23:25.341   924  5974 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Nov 2016 10:23:25 GMT], X-Android-Received-Millis=[1479983005340], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479983005316]}
,11-24 05:23:25.341   924  2987 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-24 05:23:25.341   924  2987 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,11-24 05:23:25.341   924  2987 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-24 05:23:25.342   924  2987 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-24 05:23:25.348  5769  5769 D SprintDMHelper: simOperator: 
11-24 05:23:25.349  5769  5769 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 05:23:25.386  3589  5998 I VacuumService: Vacuum at: now=1479983005386 tag=VacuumService
,11-24 05:23:25.401  3930  3930 D SystemUpdateService: onDestroy
,11-24 05:23:25.412  3589  6001 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-24 05:23:25.437  5635  5681 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 05:23:25.437  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 05:23:25.437  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 05:23:25.437  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 05:23:25.437  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 05:23:25.437  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 05:23:25.437  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 05:23:25.437  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 05:23:25.437  5635  5681 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 05:23:25.439  5635  5681 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 05:23:25.439  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:23:25.439  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@955ed53 removed from the list
11-24 05:23:25.439  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 05:23:25.442  5635  5681 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-24 05:23:25.442  5635  5681 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-24 05:23:25.444  5635  5681 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@63bed24 Bundle[{}]
11-24 05:23:25.444  5635  5681 I io.jxcore.node.LifeCycleMonitor: start: OK
11-24 05:23:25.444  5635  5681 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-24 05:23:25.444  3589  5999 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
11-24 05:23:25.445  5635  5681 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-24 05:23:25.445  5635  5681 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-24 05:23:25.446  5635  5681 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-24 05:23:25.447  5635  5681 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-24 05:23:25.447  3589  5999 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-24 05:23:25.452  5635  5681 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 168)
,11-24 05:23:25.453  5635  5681 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,11-24 05:23:25.453  5635  5681 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
11-24 05:23:25.455  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 05:23:25.455  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9178690 added. We now have 3 listener(s)
11-24 05:23:25.456  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 05:23:25.456  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-24 05:23:25.456  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 05:23:25.456  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 05:23:25.456  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d645b89 added. We now have 4 listener(s)
11-24 05:23:25.456  5635  5681 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 05:23:25.457  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 05:23:25.457  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 05:23:25.457  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c94e78e added. We now have 4 listener(s)
,11-24 05:23:25.459  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 05:23:25.459  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 05:23:25.459  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 05:23:25.459  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 05:23:25.459  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc80baf added. We now have 5 listener(s)
11-24 05:23:25.459  5635  5681 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 05:23:25.459  5635  5681 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 05:23:25.459  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 05:23:25.459  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 05:23:25.459  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:23:25.459  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:23:25.460  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 05:23:25.460  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9178690 removed from the list
11-24 05:23:25.460  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:23:25.460  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d645b89 removed from the list
11-24 05:23:25.460  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
11-24 05:23:25.460  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.460  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:23:25.461  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.462  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.462  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.462  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 05:23:25.462  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 05:23:25.462  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:23:25.462  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d645b89 not in the list
11-24 05:23:25.462  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.462  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:23:25.463  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:23:25.464  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.464  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.464  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 05:23:25.464  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 05:23:25.464  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 05:23:25.464  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@fc80baf removed from the list
11-24 05:23:25.464  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:23:25.464  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:23:25.464  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 05:23:25.464  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c94e78e removed from the list
,11-24 05:23:25.465  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 05:23:25.465  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4167bbc added. We now have 3 listener(s)
,11-24 05:23:25.467  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-24 05:23:25.467  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 05:23:25.467  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 05:23:25.467  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 05:23:25.467  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ae2745 added. We now have 4 listener(s)
11-24 05:23:25.467  5635  5681 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 05:23:25.468  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 05:23:25.469  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 05:23:25.469  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7bee9a added. We now have 4 listener(s)
,11-24 05:23:25.471  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-24 05:23:25.471  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 05:23:25.471  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 05:23:25.471  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 05:23:25.471  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@893b3cb added. We now have 5 listener(s)
11-24 05:23:25.472  5635  5681 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 05:23:25.472  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 05:23:25.472  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 05:23:25.472  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 05:23:25.472  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 05:23:25.472  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-24 05:23:25.474  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 05:23:25.476  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-24 05:23:25.476  5635  5681 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 05:23:25.476  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 05:23:25.479  5035  5994 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-24 05:23:25.481  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.481  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 05:23:25.481  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-24 05:23:25.482  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 05:23:25.482  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 05:23:25.484  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:23:25.484  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 05:23:25.484  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 05:23:25.484  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 05:23:25.484  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 05:23:25.484  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.485  5635  5681 D BluetoothAdapter: STATE_ON
11-24 05:23:25.487  5918  5957 D BtGatt.GattService: registerClient() - UUID=b3f18e3b-8c00-4d0c-9b00-ff9dbbf31c67
,11-24 05:23:25.487  5918  5934 D BtGatt.GattService: onClientRegistered() - UUID=b3f18e3b-8c00-4d0c-9b00-ff9dbbf31c67, clientIf=5
,11-24 05:23:25.488  5635  5645 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 05:23:25.489  5918  5929 D BtGatt.GattService: start scan with filters
,11-24 05:23:25.492  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 05:23:25.492  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.492  5918  5937 D BtGatt.ScanManager: handling starting scan
11-24 05:23:25.492  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-24 05:23:25.492  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.492  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-24 05:23:25.492  5635  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 05:23:25.492  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.492  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 05:23:25.492  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 05:23:25.493  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.493  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,11-24 05:23:25.493  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.493  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.493  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 05:23:25.493  5918  5937 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@32cd051
11-24 05:23:25.494  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.496  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.496  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-24 05:23:25.496  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.496  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.496  5635  5681 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-24 05:23:25.496  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.497  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 05:23:25.497  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 05:23:25.497  5635  5681 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 05:23:25.497  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 05:23:25.497  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:23:25.497  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 05:23:25.498  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.498  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.498  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.498  5635  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 05:23:25.498  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 05:23:25.498  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.498  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 05:23:25.499  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 05:23:25.499  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.499  3589  5999 W Uploader:  no longer exists, so no auth token.
11-24 05:23:25.499  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.499  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.499  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 05:23:25.499  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.499  5635  5681 D BluetoothAdapter: STATE_ON
11-24 05:23:25.500  5918  5929 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 05:23:25.500  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 05:23:25.500  5918  5934 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 ,05:23:25.500  5918  5934 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:23:25.501  5635  5681 D BluetoothAdapter: STATE_ON
11-24 05:23:25.501  5918  5937 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-24 05:23:25.501  5918  5928 D BtGatt.GattService: stopScan() - queue size =1
,11-24 05:23:25.502  5918  5957 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 05:23:25.502  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 05:23:25.502  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.502  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 05:23:25.502  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.503  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.503  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:23:25.503  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.503  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 05:23:25.503  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.503  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.503  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.503  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 05:23:25.503  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 05:23:25.504  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 05:23:25.504  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.506  5918  5934 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 05:23:25.506  5918  5934 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 05:23:25.506  5918  5937 D BtGatt.ScanManager: Starting BLE batch scan
11-24 05:23:25.506  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.506  5918  5937 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 05:23:25.506  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 05:23:25.507  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.507  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.507  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 05:23:25.507  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 05:23:25.507  5635  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 05:23:25.507  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-24 05:23:25.507  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 05:23:25.507  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 05:23:25.507  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.507  3589  6001 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
11-24 05:23:25.507  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.507  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.507  5635  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 05:23:25.507  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.507  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-24 05:23:25.509  5635  5681 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 05:23:25.509  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.509  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.509  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 05:23:25.509  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 05:23:25.509  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.509  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 05:23:25.509  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:23:25.509  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 05:23:25.509  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4167bbc removed from the list
11-24 05:23:25.509  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:23:25.509  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ae2745 removed from the list
11-24 05:23:25.509  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
11-24 05:23:25.509  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.509  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.510  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.510  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.510  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:23:25.510  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 05:23:25.510  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 05:23:25.510  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:23:25.511  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6ae2745 not in the list
11-24 05:23:25.511  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.511  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.511  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.512  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.512  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.512  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 05:23:25.512  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 05:23:25.512  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:23:25.512  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@893b3cb removed from the list
11-24 05:23:25.512  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:23:25.512  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:23:25.512  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-24 05:23:25.512  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c7bee9a removed from the list
11-24 05:23:25.513  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 05:23:25.513  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f188654 added. We now have 3 listener(s)
11-24 05:23:25.514  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 05:23:25.514  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 05:23:25.514  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 05:23:25.514  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 05:23:25.514  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f56f9fd added. We now have 4 listener(s)
11-24 05:23:25.514  5635  5681 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 05:23:25.515  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 05:23:25.517  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 05:23:25.517  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee1b6f2 added. We now have 4 listener(s)
11-24 05:23:25.518  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 05:23:25.518  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 05:23:25.518  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 05:23:25.518  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 05:23:25.518  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d04d143 added. We now have 5 listener(s)
11-24 05:23:25.518  5635  5681 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 05:23:25.518  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 05:23:25.519  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 05:23:25.519  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 05:23:25.519  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 05:23:25.519  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 05:23:25.519  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-24 05:23:25.519  5918  5934 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 05:23:25.519  5918  5934 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:23:25.520  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 05:23:25.523  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-24 05:23:25.523  5635  5681 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 05:23:25.523  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-24 05:23:25.524  5918  5934 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-24 05:23:25.525  5918  5934 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 05:23:25.525  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.525  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-24 05:23:25.526  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-24 05:23:25.526  5918  5937 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 05:23:25.526  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 05:23:25.526  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 05:23:25.529  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:23:25.529  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 05:23:25.529  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 05:23:25.529  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 05:23:25.530  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 05:23:25.530  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:23:25.531  5918  5934 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 05:23:25.531  5635  5681 D BluetoothAdapter: STATE_ON
11-24 05:23:25.531  5918  5934 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:23:25.531  5918  5934 E BtGatt.ContextMap: Context not found for ID 5
,11-24 05:23:25.533  5918  5928 D BtGatt.GattService: registerClient() - UUID=1437eb75-4193-44c9-994c-11141a149799
11-24 05:23:25.533  5918  5934 D BtGatt.GattService: onClientRegistered() - UUID=1437eb75-4193-44c9-994c-11141a149799, clientIf=5
,11-24 05:23:25.533  5635  5645 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 05:23:25.534  5918  5953 D BtGatt.GattService: start scan with filters
11-24 05:23:25.536  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-24 05:23:25.537  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.537  5918  5934 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 05:23:25.537  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 05:23:25.537  5918  5934 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:23:25.537  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:23:25.537  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 05:23:25.537  5918  5937 D BtGatt.ScanManager: stopping BLe Batch
11-24 05:23:25.537  5635  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 05:23:25.537  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.537  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-24 05:23:25.537  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 05:23:25.537  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.537  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.537  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.538  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.538  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 05:23:25.538  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:23:25.540  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:23:25.540  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 05:23:25.540  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.540  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.541  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.541  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 05:23:25.541  5635  5681 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-24 05:23:25.541  5635  5681 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 05:23:25.541  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 05:23:25.541  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 05:23:25.541  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:23:25.541  5635  5681 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 05:23:25.541  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 05:23:25.541  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:23:25.541  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 05:23:25.541  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@f188654 removed from the list
11-24 05:23:25.541  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:23:25.541  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f56f9fd removed from the list
11-24 05:23:25.541  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
11-24 05:23:25.541  5635  5681 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-24 05:23:25.541  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 05:23:25.541  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.541  5635  5681 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-24 05:23:25.541  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-24 05:23:25.541  5635  5681 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 05:23:25.541  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 05:23:25.541  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.542  5918  5934 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 05:23:25.542  5918  5934 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:23:25.542  5918  5937 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 05:23:25.542  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.542  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.542  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.542  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.542  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.542  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 05:23:25.542  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 05:23:25.542  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.542  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:23:25.543  5635  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 05:23:25.543  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@f56f9fd not in the list
11-24 05:23:25.543  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 05:23:25.543  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.543  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 05:23:25.543  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 05:23:25.543  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.543  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.543  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:,23:25.543  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 05:23:25.543  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.544  5635  5681 D BluetoothAdapter: STATE_ON
11-24 05:23:25.544  5918  5928 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 05:23:25.545  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 05:23:25.546  5918  5934 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 05:23:25.546  5918  5934 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:23:25.546  5635  5681 D BluetoothAdapter: STATE_ON
11-24 05:23:25.546  5918  5957 D BtGatt.GattService: stopScan() - queue size =0
11-24 05:23:25.547  5918  5953 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 05:23:25.547  5918  5937 D BtGatt.ScanManager: handling starting scan
11-24 05:23:25.547  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 05:23:25.547  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.547  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 05:23:25.547  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.547  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.548  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.548  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.548  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-24 05:23:25.548  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.548  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.548  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.548  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 05:23:25.548  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 05:23:25.548  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-24 05:23:25.549  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:23:25.550  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.550  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 05:23:25.550  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.550  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.550  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 05:23:25.550  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 05:23:25.550  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 05:23:25.550  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 05:23:25.550  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d04d143 removed from the list
11-24 05:23:25.550  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:23:25.550  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 05:23:25.550  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:23:25.551  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 05:23:25.551  5635  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 05:23:25.551  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ee1b6f2 removed from the list
11-24 05:23:25.551  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-24 05:23:25.551  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 05:23:25.551  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 05:23:25.551  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.551  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.551  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.551  5635  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 05:23:25.551  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.551  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.551  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 05:23:25.551  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ece4bec added. We now have 3 listener(s)
11-24 05:23:25.552  5918  5934 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 05:23:25.552  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.552  5918  5934 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:23:25.552  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.552  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.552  5918  5937 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 05:23:25.552  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 05:23:25.552  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-24 05:23:25.552  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 05:23:25.552  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 05:23:25.552  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d806bb5 added. We now have 4 listener(s)
11-24 05:23:25.552  5635  5681 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 05:23:25.553  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 05:23:25.554  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 05:23:25.554  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37d324a added. We now have 4 listener(s)
11-24 05:23:25.555  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 05:23:25.555  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 05:23:25.555  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 05:23:25.555  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 05:23:25.555  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd25bb added. We now have 5 listener(s)
11-24 05:23:25.555  5635  5681 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 05:23:25.555  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 05:23:25.555  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 05:23:25.555  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 05:23:25.555  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 05:23:25.556  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-24 05:23:25.556  5918  5934 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 05:23:25.556  5918  5934 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:23:25.556  5918  5937 D BtGatt.ScanManager: Starting BLE batch scan
11-24 05:23:25.556  5918  5937 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 05:23:25.557  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 05:23:25.559  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-24 05:23:25.559  5635  5681 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 05:23:25.559  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-24 05:23:25.562  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:23:25.562  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 05:23:25.563  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 05:23:25.563  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 05:23:25.563  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 05:23:25.565  5918  5934 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-24 05:23:25.565  5918  5934 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 05:23:25.566  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.566  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-24 05:23:25.566  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 05:23:25.566  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 05:23:25.566  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 05:23:25.566  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.567  5635  5681 D BluetoothAdapter: STATE_ON
,11-24 05:23:25.570  5918  5934 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-24 05:23:25.570  5918  5934 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 05:23:25.571  5918  5929 D BtGatt.GattService: registerClient() - UUID=7b8116ee-8981-4500-a1db-f50992b96519
11-24 05:23:25.571  5918  5934 D BtGatt.GattService: onClientRegistered() - UUID=7b8116ee-8981-4500-a1db-f50992b96519, clientIf=5
,11-24 05:23:25.572  5635  5645 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 05:23:25.572  5918  5953 D BtGatt.GattService: start scan with filters
11-24 05:23:25.574  5918  5937 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 05:23:25.574  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 05:23:25.574  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.574  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 05:23:25.574  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.574  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 05:23:25.575  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 05:23:25.575  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.576  5635  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 05:23:25.576  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.576  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 05:23:25.576  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 05:23:25.576  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.576  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.576  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-24 05:23:25.576  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.577  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.577  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.577  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.577  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-24 05:23:25.578  5918  5934 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 05:23:25.578  5918  5934 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 05:23:25.580  5635  5681 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 05:23:25.580  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.580  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 05:23:25.580  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 05:23:25.580  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 05:23:25.580  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:23:25.580  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.580  5635  5681 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-24 05:23:25.580  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 05:23:25.580  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.580  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:23:25.580  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 05:23:25.581  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ece4bec removed from the list
11-24 05:23:25.581  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.581  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:23:25.581  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d806bb5 removed from the list
11-24 05:23:25.581  5635  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 05:23:25.581  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
11-24 05:23:25.581  5635  5681 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 05:23:25.581  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 05:23:25.581  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:23:25.581  5635  5681 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-24 05:23:25.581  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-24 05:23:25.581  5635  5681 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 05:23:25.581  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 05:23:25.581  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.582  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.582  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.582  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.582  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 05:23:25.582  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 05:23:25.582  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:23:25.582  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d806bb5 not in the list
11-24 05:23:25.582  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-24 05:23:25.582  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.582  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 05:23:25.582  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 05:23:25.582  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.582  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.582  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.582  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 05:23:25.582  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.583  5635  5681 D BluetoothAdapter: STATE_ON
,11-24 05:23:25.584  5918  5957 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 05:23:25.584  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 05:23:25.584  5918  5934 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 05:23:25.584  5918  5934 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:23:25.584  5918  5937 D BtGatt.ScanManager: stopping BLe Batch
11-24 05:23:25.585  5635  5681 D BluetoothAdapter: STATE_ON
11-24 05:23:25.585  5918  5929 D BtGatt.GattService: stopScan() - queue size =0
11-24 05:23:25.586  5918  5928 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 05:23:25.586  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 05:23:25.586  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:23:25.586  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 05:23:25.587  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.587  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.587  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.587  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.587  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 05:23:25.587  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.587  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.587  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.587  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 05:23:25.587  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 05:23:25.588  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 05:23:25.588  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.588  5918  5934 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 05:23:25.588  5918  5934 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:23:25.589  5918  5937 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 05:23:25.589  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 05:23:25.589  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 05:23:25.590  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.590  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.590  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 05:23:25.590  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 05:23:25.590  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:23:25.590  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 05:23:25.590  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd25bb removed from the list
11-24 05:23:25.590  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 05:23:25.590  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 05:23:25.590  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:23:25.590  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 05:23:25.590  5635  5635 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 05:23:25.590  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@37d324a removed from the list
11-24 05:23:25.590  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.590  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 05:23:25.590  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 05:23:25.590  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-24 05:23:25.590  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.590  5635  5635 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.590  5635  5635 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 05:23:25.590  5635  5635 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.590  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.591  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 05:23:25.591  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8942c84 added. We now have 3 listener(s)
11-24 05:23:25.591  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.591  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.591  5635  5635 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 05:23:25.592  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-24 05:23:25.592  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 05:23:25.592  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 05:23:25.592  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 05:23:25.593  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ebf5c6d added. We now have 4 listener(s)
11-24 05:23:25.593  5635  5681 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 05:23:25.593  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 05:23:25.594  5918  5934 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 05:23:25.594  5918  5934 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 05:23:25.595  5918  5937 D BtGatt.ScanManager: handling starting scan
11-24 05:23:25.595  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 05:23:25.595  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef1c0a2 added. We now have 4 listener(s)
11-24 05:23:25.597  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 05:23:25.597  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 05:23:25.597  5635  5681 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 05:23:25.597  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 05:23:25.597  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ec9133 added. We now have 5 listener(s)
11-24 05:23:25.597  5635  5681 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 05:23:25.597  5635  5681 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 05:23:25.597  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 05:23:25.597  5635  5681 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 05:23:25.597  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:23:25.597  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:23:25.598  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 05:23:25.598  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8942c84 removed from the list
11-24 05:23:25.598  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:23:25.598  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ebf5c6d removed from the list
11-24 05:23:25.598  5635  5681 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 05:23:25.598  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.598  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.599  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.599  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.599  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.599  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 05:23:25.599  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 05:23:25.599  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:23:25.599  5635  5681 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ebf5c6d not in the list
,11-24 05:23:25.599  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.599  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.599  5918  5934 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 05:23:25.599  5918  5934 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:23:25.599  5918  5937 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 05:23:25.600  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.600  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.600  5635  5681 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 05:23:25.600  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 05:23:25.600  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 05:23:25.600  5635  5681 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 05:23:25.600  5635  5681 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4ec9133 removed from the list
11-24 05:23:25.600  5635  5681 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 05:23:25.600  5635  5681 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 05:23:25.600  5635  5681 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 05:23:25.601  5635  5681 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ef1c0a2 removed from the list
11-24 05:23:25.601  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-24 05:23:25.602  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
,11-24 05:23:25.602  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-24 05:23:25.602  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 05:23:25.602  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-24 05:23:25.602  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 05:23:25.604  5918  5934 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 05:23:25.604  5918  5934 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:23:25.604  5918  5937 D BtGatt.ScanManager: Starting BLE batch scan
11-24 05:23:25.604  5918  5937 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 05:23:25.612  5918  5934 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-24 05:23:25.612  5918  5934 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 05:23:25.617  5918  5934 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-24 05:23:25.617  5918  5934 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 05:23:25.618  5918  5937 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 05:23:25.622  5918  5934 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 05:23:25.622  5918  5934 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:23:25.622  5918  5934 E BtGatt.ContextMap: Context not found for ID 5
,11-24 05:23:25.627  5918  5934 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 05:23:25.627  5918  5934 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 05:23:25.627  5918  5937 D BtGatt.ScanManager: stopping BLe Batch
,11-24 05:23:25.632  5918  5934 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 05:23:25.632  5918  5934 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 05:23:25.632  5918  5937 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 05:23:25.636  5918  5934 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 05:23:25.636  5918  5934 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 05:23:25.777  3589  6004 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 05:23:25.972   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 05:23:25.996  3589  6001 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 05:23:26.008  5635  5635 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 05:23:26.051  5635  5635 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 05:23:26.052  3589  5999 W Uploader:  no longer exists, so no auth token.
,11-24 05:23:26.062  3589  6004 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 05:23:26.091  5635  5635 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 05:23:26.151  3589  6001 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 05:23:26.673  3589  3589 I SQLiteConnectionPool: The connection pool for /data/user/0/com.google.android.gms/databases/phenotype.db has been closed but there are still 1 connections in use.  They will be closed as they are released back to the pool.
,11-24 05:23:26.676  3589  6003 E ClearcutLoggerIntentService: attempt to re-open an already-closed object: SQLiteDatabase: /data/user/0/com.google.android.gms/databases/phenotype.db
11-24 05:23:26.676  3589  6003 E ClearcutLoggerIntentService: java.lang.IllegalStateException: attempt to re-open an already-closed object: SQLiteDatabase: /data/user/0/com.google.android.gms/databases/phenotype.db
11-24 05:23:26.676  3589  6003 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteClosable.acquireReference(SQLiteClosable.java:55)
11-24 05:23:26.676  3589  6003 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:520)
11-24 05:23:26.676  3589  6003 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:143)
11-24 05:23:26.676  3589  6003 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
11-24 05:23:26.676  3589  6003 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
11-24 05:23:26.676  3589  6003 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
11-24 05:23:26.676  3589  6003 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
11-24 05:23:26.676  3589  6003 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
11-24 05:23:26.676  3589  6003 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,11-24 05:23:27.772  5635  6009 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 05:23:27.772  5635  6009 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 05:23:28.573  5635  6009 W !!      : call onHalfStreamCopied
,11-24 05:23:28.573  5635  6009 I testCopyDataAndClose: closing input stream
,11-24 05:23:29.346  5635  6009 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 177, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 05:23:29.346  5635  6009 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 05:23:29.346  5635  6009 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 05:23:29.346  5635  6009 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 05:23:29.346  5635  6009 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-24 05:23:29.346  5635  6009 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 05:23:29.346  5635  6009 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-24 05:23:29.346  5635  6009 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 05:23:29.346  5635  6009 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-24 05:23:29.346  5635  6009 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 05:23:29.346  5635  6009 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-24 05:23:33.172  5635  6010 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-24 05:23:33.172  5635  6010 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 05:23:33.219   924  2987 D ConnectivityService: handlePromptUnvalidated 102
,11-24 05:23:35.172  5635  5681 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 180. Connection data: Peer properties: [null null].
11-24 05:23:35.172  5635  5681 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 05:23:35.173  5635  5681 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 180, name: My test thread name)
,11-24 05:23:35.257  5635  6010 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-24 05:23:35.257  5635  6010 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-24 05:23:35.257  5635  6010 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,11-24 05:23:35.322  5635  6011 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 05:23:35.322  5635  6011 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 05:23:36.328   924  2980 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 12 -> obsolete
,11-24 05:23:36.948  5635  6011 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 182, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 05:23:36.948  5635  6011 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 05:23:36.948  5635  6011 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 05:23:36.948  5635  6011 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 05:23:36.948  5635  6011 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 05:23:36.948  5635  6011 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 05:23:36.948  5635  6011 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-24 05:23:36.948  5635  6011 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 05:23:36.948  5635  6011 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-24 05:23:36.948  5635  6011 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 05:23:36.948  5635  6011 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-24 05:23:40.717  5635  6012 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-24 05:23:40.717  5635  6012 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 05:23:40.718  5635  6012 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 184, thread name: My test thread name). Connection data: Peer properties: [null null].
11-24 05:23:40.718  5635  6012 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 05:23:40.718  5635  6012 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 05:23:40.718  5635  6012 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 05:23:40.718  5635  6012 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-24 05:23:40.718  5635  6012 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 05:23:40.718  5635  6012 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-24 05:23:40.718  5635  6012 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 05:23:40.718  5635  6012 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-24 05:23:40.719  5635  6012 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-24 05:23:40.719  5635  6012 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-24 05:23:40.720  5635  5681 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-24 05:23:40.723  5635  6013 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-24 05:23:40.723  5635  6013 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 05:23:40.724  5635  6013 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 188, thread name: My test thread name): Test exception.
11-24 05:23:40.724  5635  6013 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-24 05:23:40.724  5635  6013 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-24 05:23:40.724  5635  6013 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-24 05:23:40.724  5635  6013 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-24 05:23:40.724  5635  6013 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-24 05:23:40.729  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-24 05:23:40.729  5635  5681 I jxcore-log: 
11-24 05:23:40.730  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG UnitTest_app: 'Number of passed tests:  81'
11-24 05:23:40.730  5635  5681 I jxcore-log: 
11-24 05:23:40.730  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG UnitTest_app: 'Number of failed tests:  1'
11-24 05:23:40.730  5635  5681 I jxcore-log: 
,11-24 05:23:40.730  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-24 05:23:40.730  5635  5681 I jxcore-log: 
11-24 05:23:40.731  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG UnitTest_app: 'Total duration:  90871'
11-24 05:23:40.731  5635  5681 I jxcore-log: 
11-24 05:23:40.732  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG UnitTest_app: 'Failures: 
11-24 05:23:40.732  5635  5681 I jxcore-log:  mDiscoveryManager1 state should not be NOT_STARTED
11-24 05:23:40.732  5635  5681 I jxcore-log: Expected: is not <NOT_STARTED>
11-24 05:23:40.732  5635  5681 I jxcore-log:      but: was <NOT_STARTED>
11-24 05:23:40.732  5635  5681 I jxcore-log: '
11-24 05:23:40.732  5635  5681 I jxcore-log: 
11-24 05:23:40.732  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-24 05:23:40.732  5635  5681 I jxcore-log: 
,11-24 05:23:40.733  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-24 05:23:40.733  5635  5681 I jxcore-log: 
,11-24 05:23:40.736  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 05:23:40.736  5635  5681 I jxcore-log: 
11-24 05:23:40.737  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 05:23:40.737  5635  5681 I jxcore-log: 
11-24 05:23:40.737  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-24 05:23:40.737  5635  5681 I jxcore-log: 
11-24 05:23:40.738  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-24 05:23:40.738  5635  5681 I jxcore-log: 
11-24 05:23:40.738  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 05:23:40.738  5635  5681 I jxcore-log: 
11-24 05:23:40.738  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 05:23:40.738  5635  5681 I jxcore-log: 
11-24 05:23:40.739  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 05:23:40.739  5635  5681 I jxcore-log: 
11-24 05:23:40.739  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 05:23:40.739  5635  5681 I jxcore-log: 
11-24 05:23:40.739  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 05:23:40.739  5635  5681 I jxcore-log: 
,11-24 05:23:40.740  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-24 05:23:40.740  5635  5681 I jxcore-log: 
11-24 05:23:40.740  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-24 05:23:40.740  5635  5681 I jxcore-log: 
11-24 05:23:40.740  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 05:23:40.740  5635  5681 I jxcore-log: 
11-24 05:23:40.740  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 05:23:40.740  5635  5681 I jxcore-log: 
,11-24 05:23:40.740  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 05:23:40.740  5635  5681 I jxcore-log: 
11-24 05:23:40.741  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 05:23:40.741  5635  5681 I jxcore-log: 
11-24 05:23:40.741  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 05:23:40.741  5635  5681 I jxcore-log: 
,11-24 05:23:40.741  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 05:23:40.741  5635  5681 I jxcore-log: 
,11-24 05:23:40.741  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 05:23:40.741  5635  5681 I jxcore-log: 
,11-24 05:23:40.742  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 05:23:40.742  5635  5681 I jxcore-log: 
11-24 05:23:40.742  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 05:23:40.742  5635  5681 I jxcore-log: 
11-24 05:23:40.742  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 05:23:40.742  5635  5681 I jxcore-log: 
11-24 05:23:40.742  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 05:23:40.742  5635  5681 I jxcore-log: 
11-24 05:23:40.744  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 05:23:40.744  5635  5681 I jxcore-log: 
,11-24 05:23:40.744  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-24 05:23:40.744  5635  5681 I jxcore-log: 
11-24 05:23:40.745  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 05:23:40.745  5635  5681 I jxcore-log: 
11-24 05:23:40.745  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-24 05:23:40.745  5635  5681 I jxcore-log: 
11-24 05:23:40.745  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 05:23:40.745  5635  5681 I jxcore-log: 
11-24 05:23:40.745  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 05:23:40.745  5635  5681 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-24 05:23:40.745  5635  5681 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-24 05:23:40.745  5635  5681 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-24 05:23:40.746  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 05:23:40.746  5635  5681 I jxcore-log: 
11-24 05:23:40.746  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 05:23:40.746  5635  5681 I jxcore-log: 
11-24 05:23:40.746  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 05:23:40.746  5635  5681 I jxcore-log: 
11-24 05:23:40.746  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 05:23:40.746  5635  5681 I jxcore-log: 
11-24 05:23:40.747  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 05:23:40.747  5635  5681 I jxcore-log: 
11-24 05:23:40.747  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 05:23:40.747  5635  5681 I jxcore-log: 
,11-24 05:23:40.752  5635  5635 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
11-24 05:23:40.752  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-24 05:23:40.752  5635  5681 I jxcore-log: 
,11-24 05:23:40.752  5635  5635 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
11-24 05:23:40.752  5635  5681 I jxcore-log: 2016-11-24 10:23:40 - WARN testUtils: 'myNameCallback not set!'
11-24 05:23:40.752  5635  5681 I jxcore-log: 
,11-24 05:23:42.817  5635  5681 I jxcore-log: 2016-11-24 10:23:42 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-24 05:23:42.817  5635  5681 I jxcore-log: 
,11-24 05:23:42.819  5635  5681 I jxcore-log: 2016-11-24 10:23:42 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-24 05:23:42.819  5635  5681 I jxcore-log: 
,11-24 05:23:43.168  5635  5681 I jxcore-log: 2016-11-24 10:23:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-24 05:23:43.168  5635  5681 I jxcore-log: 
,11-24 05:23:43.177  5635  5681 I jxcore-log: 2016-11-24 10:23:43 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-24 05:23:43.177  5635  5681 I jxcore-log: 
,11-24 05:23:44.294  5635  5681 I jxcore-log: 2016-11-24 10:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-24 05:23:44.294  5635  5681 I jxcore-log: 
,11-24 05:23:44.489  5635  5681 I jxcore-log: 2016-11-24 10:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-24 05:23:44.489  5635  5681 I jxcore-log: 
,11-24 05:23:44.494  5635  5681 I jxcore-log: 2016-11-24 10:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-24 05:23:44.494  5635  5681 I jxcore-log: 
,11-24 05:23:44.499  5635  5681 I jxcore-log: 2016-11-24 10:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-24 05:23:44.499  5635  5681 I jxcore-log: 
,11-24 05:23:44.986  5635  5681 I jxcore-log: 2016-11-24 10:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-24 05:23:44.986  5635  5681 I jxcore-log: 
,11-24 05:23:45.031  5635  5681 I jxcore-log: 2016-11-24 10:23:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-24 05:23:45.031  5635  5681 I jxcore-log: 
,11-24 05:23:45.044  5635  5681 I jxcore-log: 2016-11-24 10:23:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-24 05:23:45.044  5635  5681 I jxcore-log: 
,11-24 05:23:45.048  5635  5681 I jxcore-log: 2016-11-24 10:23:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-24 05:23:45.048  5635  5681 I jxcore-log: 
,11-24 05:23:45.320  5635  5681 I jxcore-log: 2016-11-24 10:23:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-24 05:23:45.320  5635  5681 I jxcore-log: 
,11-24 05:23:45.449  5635  5681 I jxcore-log: 2016-11-24 10:23:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-24 05:23:45.449  5635  5681 I jxcore-log: 
,11-24 05:23:45.823  5635  5681 I jxcore-log: 2016-11-24 10:23:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-24 05:23:45.823  5635  5681 I jxcore-log: 
,11-24 05:23:45.832  5635  5681 I jxcore-log: 2016-11-24 10:23:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-24 05:23:45.832  5635  5681 I jxcore-log: 
,11-24 05:23:45.835  5635  5681 I jxcore-log: 2016-11-24 10:23:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-24 05:23:45.835  5635  5681 I jxcore-log: 
,11-24 05:23:45.841  5635  5681 I jxcore-log: 2016-11-24 10:23:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-24 05:23:45.841  5635  5681 I jxcore-log: 
,11-24 05:23:45.846  5635  5681 I jxcore-log: 2016-11-24 10:23:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-24 05:23:45.846  5635  5681 I jxcore-log: 
,11-24 05:23:45.874  5635  5681 I jxcore-log: 2016-11-24 10:23:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-24 05:23:45.874  5635  5681 I jxcore-log: 
,11-24 05:23:45.910  5635  5681 I jxcore-log: 2016-11-24 10:23:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-24 05:23:45.910  5635  5681 I jxcore-log: 
,11-24 05:23:45.917  5635  5681 I jxcore-log: 2016-11-24 10:23:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-24 05:23:45.917  5635  5681 I jxcore-log: 
,11-24 05:23:45.924  5635  5681 I jxcore-log: 2016-11-24 10:23:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-24 05:23:45.924  5635  5681 I jxcore-log: 
,11-24 05:23:45.939  5635  5681 I jxcore-log: 2016-11-24 10:23:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-24 05:23:45.939  5635  5681 I jxcore-log: 
,11-24 05:23:45.955  5635  5681 I jxcore-log: 2016-11-24 10:23:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-24 05:23:45.955  5635  5681 I jxcore-log: 
,11-24 05:23:45.961  5635  5681 I jxcore-log: 2016-11-24 10:23:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-24 05:23:45.961  5635  5681 I jxcore-log: 
,11-24 05:23:45.966  5635  5681 I jxcore-log: 2016-11-24 10:23:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-24 05:23:45.966  5635  5681 I jxcore-log: 
,11-24 05:23:45.973   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 05:23:45.979  5635  5681 I jxcore-log: 2016-11-24 10:23:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-24 05:23:45.979  5635  5681 I jxcore-log: 
,11-24 05:23:45.996  5635  5681 I jxcore-log: 2016-11-24 10:23:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-24 05:23:45.996  5635  5681 I jxcore-log: 
,11-24 05:23:46.011  5635  5681 I jxcore-log: 2016-11-24 10:23:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-24 05:23:46.011  5635  5681 I jxcore-log: 
,11-24 05:23:46.021  5635  5681 I jxcore-log: 2016-11-24 10:23:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-24 05:23:46.021  5635  5681 I jxcore-log: 
,11-24 05:23:46.034  5635  5681 I jxcore-log: 2016-11-24 10:23:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-24 05:23:46.034  5635  5681 I jxcore-log: 
,11-24 05:23:46.044  5635  5681 I jxcore-log: 2016-11-24 10:23:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-24 05:23:46.044  5635  5681 I jxcore-log: 
,11-24 05:23:46.057  5635  5681 I jxcore-log: 2016-11-24 10:23:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-24 05:23:46.057  5635  5681 I jxcore-log: 
,11-24 05:23:46.067  5635  5681 I jxcore-log: 2016-11-24 10:23:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-24 05:23:46.067  5635  5681 I jxcore-log: 
,11-24 05:23:46.074  5635  5681 I jxcore-log: 2016-11-24 10:23:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-24 05:23:46.074  5635  5681 I jxcore-log: 
,11-24 05:23:46.096  5635  5681 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-24 05:23:46.097  5635  5681 I jxcore-log: 2016-11-24 10:23:46 - INFO testUtils: 'BLE multiple advertisement supported'
11-24 05:23:46.097  5635  5681 I jxcore-log: 
,11-24 05:23:46.130  5635  5681 I jxcore-log: 2016-11-24 10:23:46 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-24 05:23:46.130  5635  5681 I jxcore-log: 
,11-24 05:23:46.465  5635  5681 I jxcore-log: 2016-11-24 10:23:46 - DEBUG CoordinatedClient: 'connected to the test server'
11-24 05:23:46.465  5635  5681 I jxcore-log: 
,11-24 05:23:46.765  5635  5681 I jxcore-log: 2016-11-24 10:23:46 - ERROR CoordinatedClient: 'device disqualified from the test server, reason: 'Native unit tests failed''
11-24 05:23:46.765  5635  5681 I jxcore-log: 
,11-24 05:23:46.768  5635  5681 I jxcore-log: 2016-11-24 10:23:46 - DEBUG CoordinatedClient: 'test client failed'
11-24 05:23:46.768  5635  5681 I jxcore-log: 
,11-24 05:23:46.773  5635  5681 I jxcore-log: 2016-11-24 10:23:46 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-24 05:23:46.773  5635  5681 I jxcore-log: 
,11-24 05:23:46.780  5635  5681 I jxcore-log: 2016-11-24 10:23:46 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: Test client failed: Native unit tests failed', stack: 'CoordinatedClient.prototype._disqualify/<@/data/data/com.test.thalitest/files/www/jxcore/lib/CoordinatedClient.js:190:20
11-24 05:23:46.780  5635  5681 I jxcore-log: tryCatcher@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/util.js:16:16
11-24 05:23:46.780  5635  5681 I jxcore-log: module.exports/Promise.prototype._settlePromiseFromHandler@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:510:13
11-24 05:23:46.780  5635  5681 I jxcore-log: module.exports/Promise.prototype._settlePromise@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:567:13
11-24 05:23:46.780  5635  5681 I jxcore-log: module.exports/Promise.prototype._settlePromise0@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:612:5
11-24 05:23:46.780  5635  5681 I jxcore-log: module.exports/Promise.prototype._settlePromises@/data/data/com.test.thalitest/files/www/jxcore/node_modules/bluebird/js/release/promise.js:691:13''
11-24 05:23:46.780  5635  5681 I jxcore-log: 
,11-24 05:23:46.781  5635  5681 I jxcore-log: 2016-11-24 10:23:46 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-24 05:23:46.781  5635  5681 I jxcore-log: 
,11-24 05:23:46.974   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 05:23:47.361  6022  6022 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-24 05:23:47.383  6022  6022 D AndroidRuntime: CheckJNI is OFF
,11-24 05:23:47.412  6022  6022 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-24 05:23:47.444  6022  6022 I Radio-JNI: register_android_hardware_Radio DONE
,11-24 05:23:47.460  6022  6022 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-24 05:23:47.474   924   938 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
11-24 05:23:47.475   924   938 I ActivityManager: Killing 5635:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-24 05:23:47.565   924  3606 D GraphicsStats: Buffer count: 2
11-24 05:23:47.565   924  3833 I WindowState: WIN DEATH: Window{36c480e u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-24 05:23:47.566   924  2986 D WifiService: Client connection lost with reason: 4
,11-24 05:23:47.610   924   938 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-24 05:23:47.611   924   938 W PackageManager: Package com.test.thalitest is missing; assuming frozen
11-24 05:23:47.612   924   938 E ActivityManager: Failure starting process com.test.thalitest
11-24 05:23:47.612   924   938 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-24 05:23:47.612   924   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-24 05:23:47.612   924   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-24 05:23:47.612   924   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-24 05:23:47.612   924   938 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-24 05:23:47.612   924   938 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-24 05:23:47.612   924   938 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-24 05:23:47.612   924   938 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-24 05:23:47.612   924   938 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-24 05:23:47.612   924   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-24 05:23:47.612   924   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-24 05:23:47.612   924   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-24 05:23:47.612   924   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-24 05:23:47.612   924   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-24 05:23:47.612   924   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-24 05:23:47.612   924   938 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 05:23:47.612   924   938 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-24 05:23:47.612   924   938 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 05:23:47.612   924   938 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-24 05:23:47.613   924   948 I art     : Starting a blocking GC Explicit
,11-24 05:23:47.614   924   938 I ActivityManager:   Force finishing activity ActivityRecord{5ea7a62 u0 com.test.thalitest/.MainActivity t10}
,11-24 05:23:47.619   924  3172 W ActivityManager: Spurious death for ProcessRecord{555f3d5 0:com.test.thalitest/u0a77}, curProc for 5635: null
,11-24 05:23:47.623   924   943 W WindowManager: Attempted to add application window with unknown token Token{fec27f3 ActivityRecord{5ea7a62 u0 com.test.thalitest/.MainActivity t10 f}}.  Aborting.
,11-24 05:23:47.623   924   943 W WindowManager: Token{fec27f3 ActivityRecord{5ea7a62 u0 com.test.thalitest/.MainActivity t10 f}} already running, starting window not displayed. Unable to add window -- token Token{fec27f3 ActivityRecord{5ea7a62 u0 com.test.thalitest/.MainActivity t10 f}} is not valid; is your activity running?
11-24 05:23:47.623   924   943 W WindowManager: view not successfully added to wm, removing view
11-24 05:23:47.624   924   943 W WindowManager: Exception when adding starting window
11-24 05:23:47.624   924   943 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{9823524 V.E...... R.....ID 0,0-0,0} not attached to window manager
11-24 05:23:47.624   924   943 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
11-24 05:23:47.624   924   943 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
11-24 05:23:47.624   924   943 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
11-24 05:23:47.624   924   943 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
11-24 05:23:47.624   924   943 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
11-24 05:23:47.624   924   943 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 05:23:47.624   924   943 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
11-24 05:23:47.624   924   943 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 05:23:47.624   924   943 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-24 05:23:47.695   924   948 I art     : Explicit concurrent mark sweep GC freed 52305(3MB) AllocSpace objects, 9(260KB) LOS objects, 33% free, 28MB/43MB, paused 1.663ms total 81.500ms
,11-24 05:23:47.716   924   948 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-24 05:23:47.719  6022  6022 I art     : System.exit called, status: 0
,11-24 05:23:47.719  6022  6022 I AndroidRuntime: VM exiting with result code 0.
,11-24 05:23:47.733   924   948 I ActivityManager: Start proc 6032:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
11-24 05:23:47.734   924   948 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-24 05:23:47.737   924   938 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-24 05:23:47.743  5918  5918 D BluetoothMapAppObserver: onReceive
,11-24 05:23:47.743  5918  5918 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-24 05:23:47.750   924  2950 I InputReader: Reconfiguring input devices.  changes=0x00000010
11-24 05:23:47.753  3678  3678 I Keyboard.Facilitator: resetDictionaries() : en_US
11-24 05:23:47.754  4098  4204 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-24 05:23:47.779  3678  6046 I Keyboard.Facilitator.DecoderInitializer: run()
,11-24 05:23:47.784  3409  6044 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-24 05:23:47.802  3792  3792 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-24 05:23:47.807   924   924 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-24 05:23:47.822  3678  6046 I Decoder : createOrResetDecoder
,11-24 05:23:47.819   313   313 W kworker/1:2: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 05:23:47.832   313   313 W kworker/1:2: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 05:23:47.845  3589  3589 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-24 05:23:47.845  3589  3589 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-24 05:23:47.859  3832  3939 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-24 05:23:47.856   313   313 W kworker/1:2: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 05:23:47.861  3589  3589 I ConfigService: onCreate
11-24 05:23:47.863  3930  6051 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-24 05:23:47.864  3930  6051 D AccountUtils: Clearing selected account for com.test.thalitest
,11-24 05:23:47.872   924   935 I ActivityManager: Start proc 6054:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
11-24 05:23:47.873  3832  3939 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-24 05:23:47.873  3832  3939 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3832
11-24 05:23:47.873  3832  3939 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-24 05:23:47.873  3832  3939 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-24 05:23:47.873  3832  3939 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-24 05:23:47.873  3832  3939 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-24 05:23:47.873  3832  3939 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-24 05:23:47.873  3832  3939 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-24 05:23:47.873  3832  3939 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-24 05:23:47.873  3832  3939 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-24 05:23:47.873  3832  3939 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-24 05:23:47.873  3832  3939 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-24 05:23:47.873  3832  3939 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 05:23:47.873  3832  3939 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-24 05:23:47.881   924  3605 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-24 05:23:47.881   924  6064 E DropBoxManagerService: Can't write: system_app_crash
11-24 05:23:47.881   924  6064 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop125.tmp: open failed: EROFS (Read-only file system)
11-24 05:23:47.881   924  6064 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 05:23:47.881   924  6064 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 05:23:47.881   924  6064 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 05:23:47.881   924  6064 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 05:23:47.881   924  6064 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 05:23:47.881   924  6064 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 05:23:47.881   924  6064 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 05:23:47.881   924  6064 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 05:23:47.881   924  6064 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 05:23:47.881   924  6064 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 05:23:47.881   924  6064 E DropBoxManagerService: 	... 5 more
,11-24 05:23:47.889  3832  3939 I Process : Sending signal. PID: 3832 SIG: 9
,11-24 05:23:47.895  3930  6051 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-24 05:23:47.905  3678  6046 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-24 05:23:47.920  3930  6051 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-24 05:23:47.920  3930  6051 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 05:23:47.920  3930  6051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 05:23:47.920  3930  6051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 05:23:47.920  3930  6051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 05:23:47.920  3930  6051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 05:23:47.920  3930  6051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 05:23:47.920  3930  6051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 05:23:47.920  3930  6051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 05:23:47.920  3930  6051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 05:23:47.920  3930  6051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 05:23:47.920  3930  6051 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 05:23:47.920  3930  6051 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 05:23:47.920  3930  6051 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 05:23:47.920  3930  6051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 05:23:47.920  3930  6051 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-24 05:23:47.920  3930  6051 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-24 05:23:47.920  3930  6051 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-24 05:23:47.920  3930  6051 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 05:23:47.920  3930  6051 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-24 05:23:47.920  3930  6051 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-24 05:23:47.920  3930  6051 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-24 05:23:47.920  3930  6051 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 05:23:47.920  3930  6051 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 05:23:47.920  3930  6051 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 05:23:47.920  3930  6051 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 05:23:47.920  3930  6051 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 05:23:47.920  3930  6051 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 05:23:47.920  3930  6051 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 05:23:47.920  3930  6051 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 05:23:47.920  3930  6051 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 05:23:47.920  3930  6051 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 05:23:47.920  3930  6051 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 05:23:47.920  3930  6051 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 05:23:47.920  3930  6051 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 05:23:47.920  3930  6051 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 05:23:47.920  3930  6051 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-24 05:23:47.920  3930  6051 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-24 05:23:47.920  3930  6051 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-24 05:23:47.920  3930  6051 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 05:23:47.920  3930  6051 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-24 05:23:47.920  3930  6051 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-24 05:23:47.975   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 05:23:47.986   924  2949 W InputDispatcher: channel 'd731ee6 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
,11-24 05:23:47.986   924  2949 E InputDispatcher: channel 'd731ee6 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
11-24 05:23:47.987   924  3140 D GraphicsStats: Buffer count: 1
11-24 05:23:47.987   924  3817 I WindowState: WIN DEATH: Window{d731ee6 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
11-24 05:23:47.988   924  3817 W InputDispatcher: Attempted to unregister already unregistered input channel 'd731ee6 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,11-24 05:23:48.004   924  3140 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3832) has died
11-24 05:23:48.006   924  3140 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,11-24 05:23:48.007   924  3140 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-24 05:23:48.021   924   938 I ActivityManager: Start proc 6072:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-24 05:23:48.066  6072  6072 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 05:23:48.066  6072  6072 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-24 05:23:48.066  6072  6072 D AndroidRuntime: Shutting down VM
,11-24 05:23:48.072  6072  6072 E AndroidRuntime: FATAL EXCEPTION: main
11-24 05:23:48.072  6072  6072 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6072
11-24 05:23:48.072  6072  6072 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-24 05:23:48.072  6072  6072 E AndroidRuntime: 	... 10 more
,11-24 05:23:48.074   924  3169 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-24 05:23:48.076  6072  6072 I Process : Sending signal. PID: 6072 SIG: 9
,11-24 05:23:48.090   924  3605 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6072) has died
11-24 05:23:48.092   924  3605 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-24 05:23:48.105   924   938 I ActivityManager: Start proc 6086:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-24 05:23:48.151  6086  6086 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 05:23:48.151  6086  6086 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-24 05:23:48.151  6086  6086 D AndroidRuntime: Shutting down VM
,11-24 05:23:48.157  6086  6086 E AndroidRuntime: FATAL EXCEPTION: main
11-24 05:23:48.157  6086  6086 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6086
11-24 05:23:48.157  6086  6086 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-24 05:23:48.157  6086  6086 E AndroidRuntime: 	... 10 more
11-24 05:23:48.160   924  3817 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-24 05:23:48.161  6086  6086 I Process : Sending signal. PID: 6086 SIG: 9
,11-24 05:23:48.207   924  3169 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6086) has died
,11-24 05:23:48.209   924  3169 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0

```
