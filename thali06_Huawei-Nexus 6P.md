#### Test 9418709436e67d1_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-24 12:14:34.034  5599  5639 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,--------- beginning of system
11-24 12:14:34.201   925  3882 I ActivityManager: Killing 5080:com.google.android.apps.maps/u0a58 (adj 15): empty #17
11-24 12:14:34.380  5599  5649 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
11-24 12:14:34.409  3893  4958 I Icing   : Indexing F030E08B5368E93E2F43DEEC3A6B244C622F15EE from com.google.android.googlequicksearchbox
11-24 12:14:34.442  3893  3893 I ConfigFetchService: fetch service done; releasing wakelock
11-24 12:14:34.444  3893  3893 I ConfigFetchService: stopping self
11-24 12:14:34.463  5646  5646 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-24 12:14:34.466  5646  5646 D AndroidRuntime: CheckJNI is OFF
11-24 12:14:34.489  5646  5646 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-24 12:14:34.499  3893  4958 I Icing   : Indexing done F030E08B5368E93E2F43DEEC3A6B244C622F15EE
11-24 12:14:34.514  5646  5646 I Radio-JNI: register_android_hardware_Radio DONE
11-24 12:14:34.523  5599  5649 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
11-24 12:14:34.529  5646  5646 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-24 12:14:34.533   925  3846 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-24 12:14:34.555  5599  5649 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
11-24 12:14:34.563   925  3846 I ActivityManager: Start proc 5664:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-24 12:14:34.579  5646  5646 D AndroidRuntime: Shutting down VM
,11-24 12:14:34.890   925  5184 I WindowManager: Screenshot max retries 4 of Token{f9b89b6 ActivityRecord{4c50d51 u0 com.test.thalitest/.MainActivity t10}} appWin=Window{f0b1589 u0 Starting com.test.thalitest} drawState=2
,11-24 12:14:34.971  5664  5664 I CordovaLog: Changing log level to DEBUG(3)
,11-24 12:14:34.972  5664  5664 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-24 12:14:34.972  5664  5664 D CordovaActivity: CordovaActivity.onCreate()
,11-24 12:14:34.978  5664  5664 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-24 12:14:35.011  5664  5664 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-24 12:14:35.076  5664  5664 I LibraryLoader: Time to load native libraries: 55 ms (timestamps 400-455)
11-24 12:14:35.076  5664  5664 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-24 12:14:35.112  5664  5664 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {ba15a14}
,11-24 12:14:35.113  5664  5664 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-24 12:14:35.113  5664  5664 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-24 12:14:35.119  5664  5664 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-24 12:14:35.120  5664  5664 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-24 12:14:35.165  5664  5664 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-24 12:14:35.187  5664  5664 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-24 12:14:35.187  5664  5664 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-24 12:14:35.187  5664  5664 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-24 12:14:35.187  5664  5664 I Adreno  : Build Date                       : 12/06/15
11-24 12:14:35.187  5664  5664 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-24 12:14:35.187  5664  5664 I Adreno  : Local Branch                     : mybranch17112971
11-24 12:14:35.187  5664  5664 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-24 12:14:35.187  5664  5664 I Adreno  : Remote Branch                    : NONE
11-24 12:14:35.187  5664  5664 I Adreno  : Reconstruct Branch               : NOTHING
,11-24 12:14:35.243   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@12093fd:true
,11-24 12:14:35.285   407   407 W Binder_2: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[26188]" dev="sockfs" ino=26188 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-24 12:14:35.285   407   407 W Binder_2: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[26188]" dev="sockfs" ino=26188 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 12:14:35.303  5664  5664 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-24 12:14:35.316  5664  5664 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-24 12:14:35.322  5664  5664 D PluginManager: init()
,11-24 12:14:35.325  5664  5664 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-24 12:14:35.352  5664  5664 D CordovaActivity: Started the activity.
,11-24 12:14:35.352  5664  5664 D CordovaActivity: Resumed the activity.
,11-24 12:14:35.351   403   403 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[33174]" dev="sockfs" ino=33174 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 12:14:35.357  5664  5701 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-24 12:14:35.351   403   403 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[33174]" dev="sockfs" ino=33174 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-24 12:14:35.358  3899  3899 W Binder_B: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[26198]" dev="sockfs" ino=26198 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-24 12:14:35.358  3899  3899 W Binder_B: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[26198]" dev="sockfs" ino=26198 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-24 12:14:35.362  5664  5664 D CordovaActivity: Paused the activity.
,11-24 12:14:35.365  5664  5688 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-24 12:14:35.393  5664  5701 I OpenGLRenderer: Initialized EGL, version 1.4
,11-24 12:14:35.408  5664  5664 D CordovaActivity: Stopped the activity.
,11-24 12:14:35.476   925   943 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +582ms (total +930ms)
,11-24 12:14:35.492  5664  5664 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-24 12:14:35.501  5664  5664 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5664
,11-24 12:14:35.630  5664  5664 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-24 12:14:35.948  5664  5703 D jxcore_app_log: JniHelper::setJavaVM(0xf513c000), pthread_self() = -583796432
,11-24 12:14:35.955  5664  5703 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-24 12:14:35.955  5664  5703 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-24 12:14:35.955  5664  5703 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-24 12:14:35.955  5664  5703 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-24 12:14:35.955  5664  5703 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-24 12:14:35.956  5664  5703 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@554caca added. We now have 1 listener(s)
,11-24 12:14:35.960  5664  5703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,11-24 12:14:35.961  5664  5703 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-24 12:14:35.964  5664  5703 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-24 12:14:35.965  5664  5703 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 12:14:35.970  5664  5703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-24 12:14:35.970  5664  5703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-24 12:14:35.970  5664  5703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-24 12:14:35.970  5664  5703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
11-24 12:14:35.970  5664  5703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-24 12:14:35.970  5664  5703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-24 12:14:35.970  5664  5703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-24 12:14:35.970  5664  5703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-24 12:14:35.970  5664  5703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-24 12:14:35.970  5664  5703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-24 12:14:35.970  5664  5703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-24 12:14:35.970  5664  5703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-24 12:14:35.970  5664  5703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-24 12:14:35.970  5664  5703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-24 12:14:35.970  5664  5703 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@585e0b1 added. We now have 1 listener(s)
11-24 12:14:35.970  5664  5703 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 12:14:35.977   925  2990 D WifiService: New client listening to asynchronous messages
,11-24 12:14:35.978  5664  5703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 12:14:35.978  5664  5703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,11-24 12:14:35.979  5664  5703 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-24 12:14:35.979  5664  5703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-24 12:14:35.979  5664  5703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,11-24 12:14:35.979  5664  5703 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,11-24 12:14:35.979  5664  5703 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-24 12:14:35.981  5664  5703 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-24 12:14:36.029  5664  5664 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-24 12:14:36.030  5664  5664 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
11-24 12:14:36.030  5664  5664 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-24 12:14:36.153   925  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 12:14:36.416  5664  5673 I art     : Background sticky concurrent mark sweep GC freed 74228(7MB) AllocSpace objects, 15(760KB) LOS objects, 22% free, 25MB/32MB, paused 1.456ms total 256.783ms
,11-24 12:14:37.449  5664  5673 I art     : Background partial concurrent mark sweep GC freed 61673(7MB) AllocSpace objects, 3(1492KB) LOS objects, 36% free, 27MB/43MB, paused 1.227ms total 107.146ms
,11-24 12:14:37.572  5664  5711 W jxcore-log: Initializing JXcore engine
11-24 12:14:37.572  5664  5711 W jxcore-log: JXcore engine is ready
,11-24 12:14:37.595  5711  5711 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11535 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-24 12:14:37.595  5711  5711 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[15396]" dev="sockfs" ino=15396 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-24 12:14:37.595  5711  5711 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5964 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-24 12:14:37.595  5711  5711 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[31166]" dev="sockfs" ino=31166 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-24 12:14:37.605  5664  5711 W jxcore-log: Starting JXcore engine
,11-24 12:14:37.654  5664  5711 W jxcore-log: Platform android
11-24 12:14:37.654  5664  5711 W jxcore-log: 
,11-24 12:14:37.654  5664  5711 W jxcore-log: Process ARCH arm
11-24 12:14:37.654  5664  5711 W jxcore-log: 
,11-24 12:14:37.836  5664  5711 I jxcore-log: JXcore Cordova bridge is ready!
11-24 12:14:37.836  5664  5711 I jxcore-log: 
,11-24 12:14:37.837  5664  5711 W jxcore-log: JXcore engine is started
,11-24 12:14:37.846  5664  5703 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-24 12:14:37.855  5664  5664 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,11-24 12:14:37.855  5664  5664 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-24 12:14:39.211   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:14:39.453  3596  3596 I ConfigService: onDestroy
,11-24 12:14:40.212   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:14:41.216   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:14:42.219   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:14:43.220   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:14:44.221   591   591 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 12:14:47.526  5664  5711 I jxcore-log: 2016-11-24 17:14:47 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-24 12:14:47.526  5664  5711 I jxcore-log: 
,11-24 12:14:47.528  5664  5711 I jxcore-log: 2016-11-24 17:14:47 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-24 12:14:47.528  5664  5711 I jxcore-log: 
,11-24 12:14:47.535  5664  5711 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-24 12:14:47.535  5664  5711 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 12:14:47.535  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:14:47.535  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:14:47.535  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 12:14:47.535  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 12:14:47.535  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 12:14:47.535  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 12:14:47.535  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 12:14:47.535  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 12:14:47.537  5664  5711 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 12:14:47.539  5664  5711 I jxcore-log: 2016-11-24 17:14:47 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-24 12:14:47.539  5664  5711 I jxcore-log: 
11-24 12:14:47.540  5664  5711 I jxcore-log: 2016-11-24 17:14:47 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-24 12:14:47.540  5664  5711 I jxcore-log: 
,11-24 12:14:47.779  5664  5711 I jxcore-log: 2016-11-24 17:14:47 - DEBUG UnitTest_app: 'Running unit tests'
11-24 12:14:47.779  5664  5711 I jxcore-log: 
,11-24 12:14:47.779  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 12:14:47.780  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c2e24dd added. We now have 2 listener(s)
,11-24 12:14:47.780  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 12:14:47.780  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 12:14:47.780  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 12:14:47.780  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 12:14:47.780  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ecf3852 added. We now have 2 listener(s)
11-24 12:14:47.780  5664  5711 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 12:14:47.781  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 12:14:47.783  5664  5711 D executeNativeTests: Running unit tests
,11-24 12:14:47.820  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 12:14:47.820  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a91f13 added. We now have 3 listener(s)
,11-24 12:14:47.820  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 12:14:47.820  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 12:14:47.820  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 12:14:47.820  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 12:14:47.820  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 added. We now have 3 listener(s)
11-24 12:14:47.821  5664  5711 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 12:14:47.821  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 12:14:47.822  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-24 12:14:47.823  5664  5711 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 12:14:47.823  5664  5711 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 12:14:47.823  5664  5711 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 12:14:47.823  5664  5711 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-24 12:14:47.823  5664  5711 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-24 12:14:47.823  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 12:14:47.824  5664  5711 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 12:14:47.824  5664  5711 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 12:14:47.824  5664  5711 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 12:14:47.824  5664  5711 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:14:47.824  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:14:47.824  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:14:47.824  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:14:47.824  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:14:47.824  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 12:14:47.824  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a91f13 removed from the list
11-24 12:14:47.824  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:14:47.825  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 removed from the list
11-24 12:14:47.825  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:14:47.825  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:47.825  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:47.825  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:14:47.825  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:47.825  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:47.825  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:14:47.825  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:14:47.825  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:14:47.826  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:14:47.826  5664  5711 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
,11-24 12:14:47.827  5664  5711 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:14:47.827  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:14:47.827  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:14:47.827  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:14:47.827  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:14:47.827  5664  5711 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a91f13 not in the list
11-24 12:14:47.827  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:14:47.827  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:14:47.827  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:14:47.827  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:47.827  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:14:47.829  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:14:47.829  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:47.829  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:47.829  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:14:47.829  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:14:47.829  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:14:47.829  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
,11-24 12:14:47.832  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-24 12:14:47.832  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-24 12:14:47.832  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-24 12:14:47.832  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-24 12:14:47.832  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-24 12:14:47.832  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-24 12:14:47.832  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-24 12:14:47.832  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-24 12:14:47.833  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-24 12:14:47.833  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-24 12:14:47.833  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-24 12:14:47.833  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-24 12:14:47.833  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,11-24 12:14:47.833  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-24 12:14:47.833  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-24 12:14:47.833  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-24 12:14:47.833  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-24 12:14:47.833  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-24 12:14:47.833  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-24 12:14:47.833  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-24 12:14:47.833  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-24 12:14:47.833  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-24 12:14:47.833  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,11-24 12:14:47.833  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-24 12:14:47.833  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-24 12:14:47.833  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-24 12:14:47.833  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-24 12:14:47.833  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-24 12:14:47.833  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-24 12:14:47.833  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-24 12:14:47.833  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-24 12:14:47.833  5664  5711 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:14:47.833  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 12:14:47.833  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:14:47.833  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:14:47.833  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:14:47.834  5664  5711 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a91f13 not in the list
11-24 12:14:47.834  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:14:47.834  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:14:47.834  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:14:47.834  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:47.834  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:47.834  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:47.834  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:47.834  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:47.834  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:14:47.834  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:14:47.835  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:14:47.835  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:14:47.835  5664  5711 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-24 12:14:47.836  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 12:14:47.837  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-24 12:14:47.841  5664  5711 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 12:14:47.841  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:14:47.841  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:14:47.841  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 12:14:47.841  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 12:14:47.841  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 12:14:47.841  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 12:14:47.841  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 12:14:47.841  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 12:14:47.842  5664  5711 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 12:14:47.842  5664  5711 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 12:14:47.843  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 12:14:47.843  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 12:14:47.843  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 12:14:47.843  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 12:14:47.843  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 12:14:47.844  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 12:14:47.846  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 12:14:47.846  5664  5711 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 12:14:47.846  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 12:14:47.846  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 12:14:47.848  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:14:47.848  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-24 12:14:47.849  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 12:14:47.850  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 12:14:47.850  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 12:14:47.851  5664  5711 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-24 12:14:47.852  5664  5711 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
,11-24 12:14:47.854  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:14:47.854  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 12:14:47.854  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 12:14:47.854  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 12:14:47.854  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 12:14:47.854  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:47.855  5664  5711 D BluetoothAdapter: STATE_ON
,11-24 12:14:47.858  4630  4859 D BtGatt.GattService: registerClient() - UUID=bb3739df-9212-41c6-8a88-a6618daaa148
,11-24 12:14:47.859  4630  4704 D BtGatt.GattService: onClientRegistered() - UUID=bb3739df-9212-41c6-8a88-a6618daaa148, clientIf=5
,11-24 12:14:47.859  5664  5675 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 12:14:47.860  4630  4645 D BtGatt.GattService: start scan with filters
,11-24 12:14:47.863  4630  4709 D BtGatt.ScanManager: handling starting scan
11-24 12:14:47.863  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 12:14:47.863  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:47.864  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 12:14:47.864  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:14:47.864  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 12:14:47.864  5664  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 12:14:47.864  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 12:14:47.864  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 12:14:47.864  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 12:14:47.864  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-24 12:14:47.864  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 12:14:47.864  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 12:14:47.864  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:47.865  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 12:14:47.865  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 12:14:47.865  4630  4709 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
11-24 12:14:47.866  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:47.866  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 12:14:47.867  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:47.867  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:14:47.867  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 12:14:47.867  5664  5711 I io.jxcore.node.ConnectionHelper: start: OK
,11-24 12:14:47.871  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-24 12:14:47.871  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 12:14:47.871  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 12:14:47.871  5664  5664 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 12:14:47.872  4630  4704 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 12:14:47.872  4630  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:14:47.872  4630  4709 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-24 12:14:47.877  4630  4704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 12:14:47.877  4630  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:14:47.877  4630  4709 D BtGatt.ScanManager: Starting BLE batch scan
11-24 12:14:47.878  4630  4709 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 12:14:47.886  4630  4704 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 12:14:47.886  4630  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:14:47.890  4630  4704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-24 12:14:47.890  4630  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:14:47.896  4848  4883 D Finsky  : [180] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-24 12:14:47.897  4848  4848 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-24 12:14:47.899   925  5184 I ActivityManager: Killing 5440:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-24 12:14:48.373  5664  5664 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-24 12:14:48.373  5664  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 12:14:48.373  5664  5664 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 12:14:52.873  5664  5711 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 12:14:52.873  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 12:14:52.873  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 12:14:52.874  5664  5711 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-24 12:14:52.874  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 12:14:52.874  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:14:52.874  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 12:14:52.874  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-24 12:14:52.874  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:14:52.874  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-24 12:14:52.875  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-24 12:14:52.875  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:52.875  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:14:52.876  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:52.876  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 12:14:52.876  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:52.878  5664  5711 D BluetoothAdapter: STATE_ON
11-24 12:14:52.879  4630  4840 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 12:14:52.880  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 12:14:52.880  4630  4709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 12:14:52.882  5664  5711 D BluetoothAdapter: STATE_ON
,11-24 12:14:52.885  4630  4645 D BtGatt.GattService: stopScan() - queue size =1
11-24 12:14:52.887  4630  4840 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 12:14:52.888  4630  4630 D BtGatt.ScanManager: awakened up at time 98267
11-24 12:14:52.888  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 12:14:52.888  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:14:52.888  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 12:14:52.889  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:52.889  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:52.889  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:52.890  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:52.890  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 12:14:52.891  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:52.891  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:52.891  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:14:52.891  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 12:14:52.892  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 12:14:52.895  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 12:14:52.895  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:14:52.904  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:14:52.904  4630  4704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=3
,11-24 12:14:52.904  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 12:14:52.904  4630  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:14:52.904  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:14:52.905  4630  4704 D BtGatt.GattService: current time is 98284589889
11-24 12:14:52.905  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:52.905  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:14:52.905  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-24 12:14:52.905  5664  5711 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 12:14:52.905  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-24 12:14:52.905  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 12:14:52.905  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:14:52.905  4630  4704 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -72, 93, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -46, -4, -117, 6, 105, -37, 1, -128, -69, 73, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 116, -43, -111, -91, -20, -29, 1, -128, -66, 70, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-24 12:14:52.905  5664  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 12:14:52.905  5664  5711 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a91f13 not in the list
11-24 12:14:52.905  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 12:14:52.905  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 12:14:52.906  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 12:14:52.906  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:14:52.906  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 12:14:52.906  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:14:52.906  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 12:14:52.906  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-24 12:14:52.906  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-24 12:14:52.906  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 12:14:52.906  5664  5664 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 12:14:52.906  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 12:14:52.907  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 12:14:52.909  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-24 12:14:52.909  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 12:14:52.909  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 12:14:52.910  4630  4704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-24 12:14:52.912  4630  4704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-24 12:14:52.912  4630  4704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-24 12:14:52.919  4630  4704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 12:14:52.919  4630  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:14:52.919  4630  4709 D BtGatt.ScanManager: stopping BLe Batch
,11-24 12:14:52.927  4630  4704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 12:14:52.927  4630  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:14:52.927  4630  4709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 12:14:52.933  4630  4704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 12:14:52.933  4630  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:14:53.408  5664  5664 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 12:14:57.908  5664  5711 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-24 12:14:57.916  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-24 12:14:57.917  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-24 12:14:57.931  5664  5711 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 12:14:57.931  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:14:57.931  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:14:57.931  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 12:14:57.931  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 12:14:57.931  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 12:14:57.931  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 12:14:57.931  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 12:14:57.931  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-24 12:14:57.935  5664  5711 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 12:14:57.936  5664  5711 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 12:14:57.936  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 12:14:57.936  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 12:14:57.936  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 12:14:57.936  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-24 12:14:57.937  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 12:14:57.942  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 12:14:57.944  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 12:14:57.945  5664  5711 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,11-24 12:14:57.945  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 12:14:57.948  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 12:14:57.952  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:14:57.952  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 12:14:57.954  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 12:14:57.954  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 12:14:57.954  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 12:14:57.959  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:14:57.959  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 12:14:57.960  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-24 12:14:57.960  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 12:14:57.960  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-24 12:14:57.960  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:57.961  5664  5711 D BluetoothAdapter: STATE_ON
,11-24 12:14:57.965  4630  4858 D BtGatt.GattService: registerClient() - UUID=467d4a58-27fa-4fbf-ba43-d644561d2938
,11-24 12:14:57.966  4630  4704 D BtGatt.GattService: onClientRegistered() - UUID=467d4a58-27fa-4fbf-ba43-d644561d2938, clientIf=5
,11-24 12:14:57.967  5664  5675 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 12:14:57.967  4630  4645 D BtGatt.GattService: start scan with filters
,11-24 12:14:57.971  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 12:14:57.971  4630  4709 D BtGatt.ScanManager: handling starting scan
11-24 12:14:57.972  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:57.972  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 12:14:57.972  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:57.972  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 12:14:57.972  5664  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 12:14:57.972  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 12:14:57.972  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 12:14:57.972  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 12:14:57.972  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 12:14:57.972  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 12:14:57.973  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 12:14:57.973  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 12:14:57.974  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 12:14:57.974  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:14:57.978  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:57.978  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 12:14:57.978  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:57.978  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:57.978  5664  5711 I io.jxcore.node.ConnectionHelper: start: OK
11-24 12:14:57.978  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 12:14:57.982  4630  4704 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 12:14:57.982  5664  5711 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:14:57.982  4630  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:14:57.982  5664  5711 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-24 12:14:57.982  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 12:14:57.982  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 12:14:57.982  5664  5711 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 12:14:57.982  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 12:14:57.983  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:14:57.983  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 12:14:57.983  4630  4709 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 12:14:57.986  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 12:14:57.987  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 12:14:57.987  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 12:14:57.987  5664  5664 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 12:14:57.987  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 12:14:57.987  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:57.987  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 12:14:57.987  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 12:14:57.987  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:57.988  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:57.988  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:57.988  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 12:14:57.988  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:57.989  5664  5711 D BluetoothAdapter: STATE_ON
11-24 12:14:57.989  4630  4643 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 12:14:57.990  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 12:14:57.991  5664  5711 D BluetoothAdapter: STATE_ON
11-24 12:14:57.992  4630  4704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 12:14:57.992  4630  4858 D BtGatt.GattService: stopScan() - queue size =1
11-24 12:14:57.992  4630  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:14:57.992  4630  4709 D BtGatt.ScanManager: Starting BLE batch scan
11-24 12:14:57.992  4630  4709 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 12:14:57.994  4630  4859 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 12:14:57.995  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 12:14:57.995  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:57.995  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 12:14:57.995  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:57.995  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:57.995  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:57.996  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:57.996  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 12:14:57.996  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:57.996  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:57.996  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:57.996  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 12:14:57.996  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 12:14:57.997  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 12:14:57.997  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:58.000  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:58.001  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 12:14:58.001  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:58.001  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:58.001  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:14:58.001  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 12:14:58.001  5664  5711 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 12:14:58.001  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 12:14:58.001  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 12:14:58.001  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:14:58.001  5664  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 12:14:58.001  5664  5711 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a91f13 not in the list
11-24 12:14:58.001  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:14:58.001  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 12:14:58.001  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:14:58.001  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 12:14:58.001  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:14:58.001  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 12:14:58.001  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 12:14:58.001  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 12:14:58.002  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 12:14:58.002  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 12:14:58.002  5664  5664 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 12:14:58.002  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 12:14:58.002  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 12:14:58.004  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 12:14:58.004  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 12:14:58.004  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 12:14:58.005  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:58.005  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:58.005  4630  4704 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 12:14:58.005  4630  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:14:58.006  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:58.006  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:58.006  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:58.006  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:14:58.006  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:14:58.006  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:14:58.007  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:14:58.007  5664  5711 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-24 12:14:58.010  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 12:14:58.010  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-24 12:14:58.012  4630  4704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 12:14:58.012  4630  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:14:58.013  4630  4709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 12:14:58.016  5664  5711 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 12:14:58.016  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:14:58.016  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:14:58.016  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 12:14:58.016  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 12:14:58.016  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 12:14:58.016  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 12:14:58.016  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 12:14:58.016  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 12:14:58.019  4630  4704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 12:14:58.019  5664  5711 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-24 12:14:58.019  4630  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:14:58.019  5664  5711 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 12:14:58.019  4630  4704 E BtGatt.ContextMap: Context not found for ID 5
11-24 12:14:58.019  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 12:14:58.019  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 12:14:58.019  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 12:14:58.020  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 12:14:58.020  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 12:14:58.022  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 12:14:58.023  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 12:14:58.023  5664  5711 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 12:14:58.023  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-24 12:14:58.025  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 12:14:58.026  4630  4704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 12:14:58.027  4630  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:14:58.027  4630  4709 D BtGatt.ScanManager: stopping BLe Batch
11-24 12:14:58.028  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:58.028  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 12:14:58.028  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 12:14:58.028  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 12:14:58.028  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-24 12:14:58.031  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:58.031  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 12:14:58.032  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 12:14:58.032  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 12:14:58.032  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 12:14:58.032  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:58.032  4630  4704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 12:14:58.032  4630  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:14:58.032  4630  4709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 12:14:58.032  5664  5711 D BluetoothAdapter: STATE_ON
11-24 12:14:58.035  4630  4859 D BtGatt.GattService: registerClient() - UUID=f2339a24-957a-4887-ba99-891dbe058ced
11-24 12:14:58.036  4630  4704 D BtGatt.GattService: onClientRegistered() - UUID=f2339a24-957a-4887-ba99-891dbe058ced, clientIf=5
11-24 12:14:58.037  5664  5675 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 12:14:58.037  4630  4643 D BtGatt.GattService: start scan with filters
11-24 12:14:58.038  4630  4704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 12:14:58.038  4630  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:14:58.040  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 12:14:58.040  4630  4709 D BtGatt.ScanManager: handling starting scan
11-24 12:14:58.040  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:58.040  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 12:14:58.040  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:58.040  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 12:14:58.040  5664  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 12:14:58.040  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 12:14:58.041  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 12:14:58.041  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 12:14:58.041  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 12:14:58.041  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 12:14:58.041  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 12:14:58.041  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 12:14:58.042  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 12:14:58.042  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:58.044  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:58.044  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 12:14:58.044  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:58.045  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:14:58.045  5664  5711 I io.jxcore.node.ConnectionHelper: start: OK
11-24 12:14:58.045  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 12:14:58.048  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 12:14:58.048  4630  4704 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 12:14:58.048  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 12:14:58.048  4630  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:14:58.048  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 12:14:58.048  5664  5664 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 12:14:58.048  4630  4709 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 12:14:58.053  4630  4704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 12:14:58.053  4630  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:14:58.054  4630  4709 D BtGatt.ScanManager: Starting BLE batch scan
11-24 12:14:58.054  4630  4709 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 12:14:58.062  4630  4704 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-24 12:14:58.062  4630  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:14:58.067  4630  4704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 12:14:58.067  4630  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:14:58.549  5664  5664 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-24 12:14:58.550  5664  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-24 12:14:58.550  5664  5664 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 12:14:59.355   925  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 12:14:59.359   925  2991 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,11-24 12:15:00.010   925   925 I ActivityManager: Killing 5452:com.android.chrome/u0a39 (adj 15): empty #17
,11-24 12:15:02.381   925  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-24 12:15:02.387   925  2991 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,11-24 12:15:03.045  5664  5711 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 12:15:03.046  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 12:15:03.046  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 12:15:03.046  5664  5711 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 12:15:03.046  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-24 12:15:03.046  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:15:03.047  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-24 12:15:03.047  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-24 12:15:03.047  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:03.047  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 12:15:03.047  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-24 12:15:03.048  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:15:03.048  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:15:03.048  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:03.048  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 12:15:03.049  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:03.051  5664  5711 D BluetoothAdapter: STATE_ON
11-24 12:15:03.051  4630  4858 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 12:15:03.052  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 12:15:03.053  4630  4709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 12:15:03.054  5664  5711 D BluetoothAdapter: STATE_ON
11-24 12:15:03.055  4630  4645 D BtGatt.GattService: stopScan() - queue size =1
,11-24 12:15:03.057  4630  4840 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 12:15:03.059  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 12:15:03.061  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:03.061  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,11-24 12:15:03.061  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:03.061  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:03.062  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:03.062  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:03.062  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 12:15:03.062  4630  4630 D BtGatt.ScanManager: awakened up at time 108441
11-24 12:15:03.062  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:03.062  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:03.062  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:03.063  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 12:15:03.063  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-24 12:15:03.068  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-24 12:15:03.068  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:03.070  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:03.070  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 12:15:03.070  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:03.070  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:03.071  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-24 12:15:03.071  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 12:15:03.071  5664  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 12:15:03.071  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-24 12:15:03.071  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 12:15:03.071  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 12:15:03.072  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-24 12:15:03.072  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 12:15:03.072  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 12:15:03.072  5664  5664 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-24 12:15:03.072  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 12:15:03.072  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 12:15:03.075  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 12:15:03.075  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 12:15:03.075  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-24 12:15:03.088  4630  4704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=4
11-24 12:15:03.088  4630  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:15:03.089  4630  4704 D BtGatt.GattService: current time is 108468492314
11-24 12:15:03.089  4630  4704 D BtGatt.GattService: Batch record : [-46, -4, -117, 6, 105, -37, 1, -128, -70, 82, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -72, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 81, 34, 97, 112, -14, -5, 1, -128, -70, 75, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 116, -43, -111, -91, -20, -29, 1, -128, -67, 74, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-24 12:15:03.089  4630  4704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-24 12:15:03.089  4630  4704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-24 12:15:03.090  4630  4704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
,11-24 12:15:03.090  4630  4704 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-24 12:15:03.090  4630  4704 E BtGatt.ContextMap: Context not found for ID 5
,11-24 12:15:03.097  4630  4704 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 12:15:03.097  4630  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:15:03.097  4630  4709 D BtGatt.ScanManager: stopping BLe Batch
,11-24 12:15:03.103  4630  4704 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 12:15:03.103  4630  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:15:03.103  4630  4709 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 12:15:03.110  4630  4704 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 12:15:03.111  4630  4704 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:15:03.574  5664  5664 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 12:15:03.574  5664  5664 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:15:03.574  5664  5664 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 12:15:08.072  5664  5711 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 12:15:08.073  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 12:15:08.073  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 12:15:08.073  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 12:15:08.073  5664  5711 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 12:15:08.074  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-24 12:15:08.074  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 12:15:08.074  5664  5711 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a91f13 not in the list
,11-24 12:15:08.074  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 12:15:08.074  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
,11-24 12:15:08.074  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 12:15:08.075  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-24 12:15:08.079  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.079  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.083  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:15:08.084  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.084  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.085  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:15:08.085  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 12:15:08.085  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:08.086  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:15:08.088  5664  5711 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-24 12:15:08.092  5664  5711 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 12:15:08.092  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:15:08.092  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:15:08.092  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:15:08.092  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:15:08.093  5664  5711 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a91f13 not in the list
,11-24 12:15:08.093  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:08.093  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:15:08.093  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:15:08.093  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.093  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:15:08.095  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.095  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:15:08.095  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.095  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:15:08.095  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:15:08.095  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:08.095  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:15:08.096  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-24 12:15:08.097  5664  5711 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:15:08.097  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 12:15:08.097  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:15:08.097  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:15:08.097  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:15:08.097  5664  5711 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a91f13 not in the list
11-24 12:15:08.097  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:08.097  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
,11-24 12:15:08.097  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:15:08.097  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.098  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.099  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.099  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.100  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:15:08.100  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:15:08.100  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:15:08.100  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:08.100  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
,11-24 12:15:08.101  5664  5711 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-24 12:15:08.101  5664  5711 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:15:08.101  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:15:08.101  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 12:15:08.101  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:15:08.101  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:15:08.101  5664  5711 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a91f13 not in the list
11-24 12:15:08.101  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:08.102  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:15:08.102  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:15:08.102  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.102  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.103  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:15:08.103  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:15:08.104  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.104  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:15:08.104  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:15:08.104  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:08.104  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:15:08.105  5664  5711 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
,11-24 12:15:08.105  5664  5711 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:15:08.105  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:15:08.105  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:15:08.105  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:15:08.105  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:15:08.105  5664  5711 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a91f13 not in the list
11-24 12:15:08.105  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:08.105  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
,11-24 12:15:08.105  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:15:08.106  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.106  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.108  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.108  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.108  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.108  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:15:08.108  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:15:08.108  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:08.108  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:15:08.109  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,11-24 12:15:08.109  5664  5711 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 12:15:08.109  5664  5711 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 12:15:08.109  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 12:15:08.110  5664  5711 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 12:15:08.110  5664  5711 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 12:15:08.110  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-24 12:15:08.110  5664  5711 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 12:15:08.110  5664  5711 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-24 12:15:08.111   925  5410 D NetlinkSocketObserver: NeighborEvent{elapsedMs=113490, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-24 12:15:08.110  5664  5711 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:15:08.111  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:15:08.111  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 12:15:08.111  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:15:08.111  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:15:08.111  5664  5711 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a91f13 not in the list
11-24 12:15:08.111  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:08.111  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:15:08.111  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:15:08.112  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.112  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.113  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.113  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.113  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.113  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:15:08.114  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 12:15:08.114  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:08.114  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:15:08.115  5664  5711 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 12:15:08.115  5664  5711 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-24 12:15:08.115  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-24 12:15:08.118  5664  5711 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 12:15:08.119  5664  5711 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-24 12:15:08.119  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-24 12:15:08.119  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-24 12:15:08.119  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-24 12:15:08.119  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-24 12:15:08.119  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-24 12:15:08.119  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-24 12:15:08.119  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-24 12:15:08.119  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-24 12:15:08.119  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-24 12:15:08.119  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-24 12:15:08.119  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-24 12:15:08.119  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-24 12:15:08.119  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-24 12:15:08.119  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-24 12:15:08.119  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-24 12:15:08.119  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-24 12:15:08.119  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-24 12:15:08.119  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,11-24 12:15:08.120  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-24 12:15:08.120  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-24 12:15:08.120  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-24 12:15:08.120  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-24 12:15:08.120  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-24 12:15:08.120  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-24 12:15:08.120  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-24 12:15:08.120  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-24 12:15:08.120  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-24 12:15:08.120  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-24 12:15:08.120  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
,11-24 12:15:08.120  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-24 12:15:08.120  5664  5711 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-24 12:15:08.121  5664  5711 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 12:15:08.121  5664  5711 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-24 12:15:08.121  5664  5711 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 12:15:08.121  5664  5711 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 12:15:08.121  5664  5711 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-24 12:15:08.121  5664  5711 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 12:15:08.121  5664  5711 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-24 12:15:08.121  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-24 12:15:08.125  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-24 12:15:08.126  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-24 12:15:08.126  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-24 12:15:08.127  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-24 12:15:08.127  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-24 12:15:08.127  5664  5711 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
,11-24 12:15:08.127  5664  5711 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-24 12:15:08.127  5664  5711 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-24 12:15:08.128  5664  5714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
,11-24 12:15:08.128  5664  5711 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:15:08.128  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:15:08.128  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:15:08.128  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:15:08.128  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:15:08.129  5664  5714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-24 12:15:08.129  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-24 12:15:08.129  5664  5714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-24 12:15:08.129  5664  5714 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-24 12:15:08.130  5664  5711 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a91f13 not in the list
,11-24 12:15:08.130  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:08.130  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:15:08.130  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:15:08.130  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.130  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:15:08.132  5664  5715 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
11-24 12:15:08.132  5664  5715 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-24 12:15:08.132  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:15:08.132  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:15:08.133  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.133  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:15:08.133  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:15:08.133  5664  5714 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-24 12:15:08.131  4643  4643 W Binder_1: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[33256]" dev="sockfs" ino=33256 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 12:15:08.133  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:08.131  4643  4643 W Binder_1: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[33256]" dev="sockfs" ino=33256 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-24 12:15:08.133  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:15:08.133  5664  5714 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 12:15:08.134  5664  5711 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-24 12:15:08.134  5664  5711 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:15:08.134  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:15:08.134  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:15:08.134  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 12:15:08.135  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:15:08.135  5664  5711 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a91f13 not in the list
11-24 12:15:08.135  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:08.135  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:15:08.135  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:15:08.135  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.135  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.136  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.136  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:15:08.136  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.136  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:15:08.136  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:15:08.136  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:08.136  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:15:08.137  5664  5711 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-24 12:15:08.138  5664  5711 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:15:08.138  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:15:08.138  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:15:08.138  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 12:15:08.138  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:15:08.138  5664  5711 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a91f13 not in the list
11-24 12:15:08.138  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:08.138  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:15:08.138  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:15:08.138  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.138  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:15:08.140  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.140  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.140  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:15:08.140  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:15:08.140  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:15:08.140  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:08.140  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:15:08.141  5664  5711 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-24 12:15:08.141  5664  5711 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-24 12:15:08.141  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 12:15:08.141  5664  5711 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-24 12:15:08.141  5664  5711 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-24 12:15:08.141  5664  5711 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
,11-24 12:15:08.141  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 12:15:08.141  5664  5711 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-24 12:15:08.141  5664  5711 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-24 12:15:08.141  5664  5711 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-24 12:15:08.142  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 12:15:08.142  5664  5711 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-24 12:15:08.142  5664  5711 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:15:08.142  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 12:15:08.142  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:15:08.142  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:15:08.142  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:15:08.142  5664  5711 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a91f13 not in the list
11-24 12:15:08.142  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:08.142  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:15:08.142  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:15:08.142  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.142  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.143  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:15:08.143  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.144  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:08.144  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:15:08.144  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:15:08.144  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:08.144  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:15:08.144  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:15:08.144  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:15:08.144  5664  5711 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a91f13 not in the list
,11-24 12:15:08.144  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:08.144  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:15:08.144  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 12:15:09.222   591   591 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
11-24 12:15:09.222   591   591 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 12:15:13.145  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 12:15:13.146  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:15:13.146  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:15:13.146  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:15:13.146  5664  5711 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a91f13 not in the list
,11-24 12:15:13.146  5664  5711 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:15:13.147  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:15:13.147  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:15:13.147  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 12:15:13.147  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:15:13.148  5664  5711 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a91f13 not in the list
11-24 12:15:13.148  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:13.148  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
,11-24 12:15:13.148  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:15:13.148  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:13.149  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:15:13.153  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:13.153  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:15:13.153  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:13.154  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:15:13.154  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:15:13.154  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 12:15:13.154  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
,11-24 12:15:13.158  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-24 12:15:13.159  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 12:15:13.160  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-24 12:15:13.165  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-24 12:15:13.167  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-24 12:15:13.167  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-24 12:15:13.168  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-24 12:15:13.168  5664  5716 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-24 12:15:13.168  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-24 12:15:13.168  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-24 12:15:13.168  5664  5664 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-24 12:15:13.169  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-24 12:15:13.169  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-24 12:15:13.169  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-24 12:15:13.169  5664  5716 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 12:15:13.169  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-24 12:15:13.170  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 12:15:13.171  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-24 12:15:13.171  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-24 12:15:13.171  5664  5711 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a91f13 not in the list
11-24 12:15:13.171  5664  5664 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-24 12:15:13.171  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:13.171  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-24 12:15:13.172  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:13.172  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 12:15:13.172  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 12:15:13.172  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:15:13.168  4643  4643 W Binder_1: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32146]" dev="sockfs" ino=32146 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 12:15:13.168  4643  4643 W Binder_1: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32146]" dev="sockfs" ino=32146 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-24 12:15:13.174  5664  5716 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-24 12:15:13.174  5664  5716 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-24 12:15:13.174  5664  5716 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-24 12:15:13.177  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:13.177  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 12:15:13.178  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:13.178  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:15:13.178  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
,11-24 12:15:13.179  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 12:15:13.179  5664  5711 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:15:13.179  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 12:15:13.179  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 12:15:13.179  5664  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-24 12:15:13.179  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:15:13.180  5664  5664 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:15:13.180  5664  5664 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-24 12:15:13.180  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:15:13.180  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:15:13.181  5664  5711 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a91f13 not in the list
11-24 12:15:13.181  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:13.181  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
,11-24 12:15:13.181  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:15:13.181  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:13.182  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:13.183  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:13.184  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:15:13.184  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:13.184  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:15:13.184  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:15:13.184  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:13.184  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:15:13.186  5664  5711 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,11-24 12:15:13.186  5664  5711 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-24 12:15:13.186  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-24 12:15:13.187  5664  5711 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-24 12:15:13.187  5664  5711 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-24 12:15:13.188  5664  5711 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:15:13.188  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:15:13.188  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:15:13.188  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:15:13.188  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:15:13.188  5664  5711 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a91f13 not in the list
,11-24 12:15:13.188  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 12:15:13.189  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
,11-24 12:15:13.189  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:15:13.190  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:13.190  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:13.195  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:13.195  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:13.195  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:15:13.196  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:15:13.196  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:15:13.196  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:13.196  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
,11-24 12:15:13.204  5664  5711 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 12:15:13.204  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:15:13.204  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:15:13.204  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:15:13.204  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:15:13.205  5664  5711 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a91f13 not in the list
,11-24 12:15:13.205  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:13.205  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:15:13.205  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:15:13.205  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:13.205  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:13.206  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:15:13.206  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:13.206  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:13.206  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:15:13.206  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:15:13.206  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:13.206  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
,11-24 12:15:13.208  5664  5711 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-24 12:15:13.208  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:15:13.208  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:15:13.208  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:15:13.208  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:15:13.208  5664  5711 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8a91f13 not in the list
11-24 12:15:13.208  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 12:15:13.208  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:15:13.208  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:15:13.208  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:13.208  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:13.210  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:13.210  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:15:13.210  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:15:13.210  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:15:13.210  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:15:13.210  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:13.210  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32c3550 not in the list
11-24 12:15:13.212  5664  5711 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-24 12:15:13.212  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
,11-24 12:15:13.212  5664  5711 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-24 12:15:13.212  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-24 12:15:13.212  5664  5711 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-24 12:15:13.212  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-24 12:15:13.214  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-24 12:15:13.214  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,11-24 12:15:13.214  5664  5711 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-24 12:15:13.215  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-24 12:15:13.215  5664  5711 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-24 12:15:13.215  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-24 12:15:13.215  5664  5711 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-24 12:15:13.215  5664  5711 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-24 12:15:13.215  5664  5711 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,11-24 12:15:13.215  5664  5711 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-24 12:15:13.216  5664  5711 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-24 12:15:13.216  5664  5711 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-24 12:15:13.216  5664  5711 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-24 12:15:13.216  5664  5711 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-24 12:15:13.217  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 12:15:13.217  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@79490b9 added. We now have 3 listener(s)
,11-24 12:15:13.217  5664  5711 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 12:15:13.219  5664  5711 D BluetoothAdapter: enable(): BT is already enabled..!
11-24 12:15:13.220   925  3855 D WifiService: setWifiEnabled: true pid=5664, uid=10077
11-24 12:15:13.220   925  3855 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 12:15:13.263  4630  4833 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-24 12:15:13.264  4630  4838 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
11-24 12:15:13.264  5664  5714 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-24 12:15:13.264  5664  5714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-24 12:15:13.264  5664  5714 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
,11-24 12:15:13.681  5664  5664 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 12:15:14.223   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:15:15.224   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:15:16.159   925  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 12:15:16.225   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:15:17.226   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:15:18.226  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 12:15:18.227  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6702cfe added. We now have 4 listener(s)
11-24 12:15:18.227  5664  5711 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 12:15:18.227   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:15:18.239  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 12:15:18.240  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6702cfe removed from the list
11-24 12:15:18.240  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 12:15:18.243  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 12:15:18.243  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5ecbc5f added. We now have 4 listener(s)
11-24 12:15:18.244  5664  5711 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 12:15:18.246  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 12:15:18.246  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@5ecbc5f removed from the list
11-24 12:15:18.246  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 12:15:18.248  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 12:15:18.248  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7ab56ac added. We now have 4 listener(s)
11-24 12:15:18.248  5664  5711 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 12:15:18.252   925  3882 D WifiService: setWifiEnabled: false pid=5664, uid=10077
11-24 12:15:18.252   925  3882 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 12:15:18.256   925  2989 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-24 12:15:18.256   925  2989 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-24 12:15:18.257   925  2989 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 12:15:18.257   925  2989 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-24 12:15:18.262  4630  4700 D BluetoothAdapterState: Current state: ON, message: 23
,11-24 12:15:18.262  4630  4700 D BluetoothAdapterProperties: Setting state to 13
,11-24 12:15:18.262  4630  4700 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-24 12:15:18.263  4630  4700 D BluetoothAdapterProperties: onBluetoothDisable()
,11-24 12:15:18.265  4630  4700 I BluetoothAdapterState: Entering PendingCommandState
,11-24 12:15:18.265  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-24 12:15:18.265  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-24 12:15:18.270  4630  4630 D BluetoothMapService: onReceive
11-24 12:15:18.270  4630  4630 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 12:15:18.270  4630  4630 D BluetoothMapService: STATE_TURNING_OFF
11-24 12:15:18.270  4630  4630 D BluetoothMapService: MAP Service closeService in
,11-24 12:15:18.271  4630  4630 D BluetoothMapMasInstance0: MAP Service shutdown
11-24 12:15:18.271  4630  4630 D ObexServerSockets0: shutdown(block = true)
11-24 12:15:18.271  4630  4630 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 12:15:18.272  4630  4838 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-24 12:15:18.272  4630  4630 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-24 12:15:18.272  4630  4863 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-24 12:15:18.273  4630  4862 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-24 12:15:18.277  4630  4630 I BtOppRfcommListener: stopping Accept Thread
11-24 12:15:18.278   925  5411 D DhcpClient: Clearing IP address
11-24 12:15:18.278  4630  5348 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-24 12:15:18.279  4630  5348 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-24 12:15:18.279   506   919 D CommandListener: Clearing all IP addresses on wlan0
,11-24 12:15:18.287   925   938 I ActivityManager: Start proc 5720:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-24 12:15:18.288  4630  4704 D BluetoothAdapterProperties: Scan Mode:20
11-24 12:15:18.288   506   919 D CommandListener: Setting iface cfg
,11-24 12:15:18.289  4630  4700 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-24 12:15:18.293  5664  5711 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 12:15:18.293  5664  5711 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-24 12:15:18.293  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:15:18.293  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:15:18.293  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 12:15:18.293  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 12:15:18.293  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 12:15:18.293  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 12:15:18.293  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 12:15:18.293  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 12:15:18.294  3596  5465 V NativeCrypto: Read error: ssl=0x7f69ed2380: I/O error during system call, Connection timed out
11-24 12:15:18.296  4630  4630 D HeadsetService: Received stop request...Stopping profile...
11-24 12:15:18.296  3596  5465 V NativeCrypto: SSL shutdown failed: ssl=0x7f69ed2380: I/O error during system call, Broken pipe
,11-24 12:15:18.297  5664  5711 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 12:15:18.298  5664  5711 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 12:15:18.298  5664  5711 D io.jxcore.node.ConnectivityMonitor: start: OK
11-24 12:15:18.299   925   925 D BluetoothHeadset: Proxy object disconnected
11-24 12:15:18.299   925   925 D BluetoothHeadset: Proxy object disconnected
11-24 12:15:18.299  3826  4149 D BluetoothHeadset: Proxy object disconnected
11-24 12:15:18.299   925   925 D BluetoothHeadset: Proxy object disconnected
11-24 12:15:18.299  4630  4630 D A2dpService: Received stop request...Stopping profile...
11-24 12:15:18.299  3145  3158 D BluetoothHeadset: Proxy object disconnected
11-24 12:15:18.300  4630  4843 D A2dpStateMachine: Exit Disconnected: -1
,11-24 12:15:18.301  4630  4630 V BluetoothAdapterState: isTurningOff()=true
11-24 12:15:18.301   925   925 D BluetoothA2dp: Proxy object disconnected
11-24 12:15:18.301  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 12:15:18.302  4630  4630 V BluetoothAdapterState: isTurningOn()=false
11-24 12:15:18.302  4630  4630 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:15:18.302  4630  4630 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:15:18.303   925  3846 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-24 12:15:18.303  4630  4630 D HidService: Received stop request...Stopping profile...
,11-24 12:15:18.303  4630  4630 D HidService: Stopping Bluetooth HidService
,11-24 12:15:18.303   925  5409 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-24 12:15:18.305  4630  4630 D HealthService: Received stop request...Stopping profile...
11-24 12:15:18.305  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 12:15:18.306  3145  3145 D HeadsetProfile: Bluetooth service disconnected
,11-24 12:15:18.306  3145  3145 D BluetoothA2dp: Proxy object disconnected
11-24 12:15:18.306  3145  3145 D BluetoothInputDevice: Proxy object disconnected
11-24 12:15:18.306  3145  3145 D HidProfile: Bluetooth service disconnected
,11-24 12:15:18.307   925  2991 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-24 12:15:18.307   925  2991 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,11-24 12:15:18.310   925   925 D RttService: SCAN_AVAILABLE : 1
11-24 12:15:18.311   925  5409 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-24 12:15:18.311   589   589 E Parcel  : Reading a NULL string not supported here.
11-24 12:15:18.312   925  3097 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-24 12:15:18.313   925  2991 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-24 12:15:18.315  3775  3927 W QCNEJ   : |CORE| network lost: 100
11-24 12:15:18.315  3775  3927 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-24 12:15:18.317  4630  4630 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-24 12:15:18.317  4630  4630 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-24 12:15:18.317  4630  4833 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-24 12:15:18.317  4630  4833 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 12:15:18.317  4630  4833 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 12:15:18.318  4630  4704 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-24 12:15:18.318  4630  4704 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-24 12:15:18.318  4630  4630 D PanService: Received stop request...Stopping profile...
11-24 12:15:18.319  4630  4630 V BluetoothAdapterState: isTurningOff()=true
11-24 12:15:18.319  4630  4630 V BluetoothAdapterState: isTurningOn()=false
11-24 12:15:18.319  4630  4630 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:15:18.319  4630  4630 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:15:18.320  4630  4833 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 12:15:18.321  4630  4833 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 12:15:18.321  4630  4833 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
,11-24 12:15:18.321  4630  4833 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 12:15:18.321  4630  4833 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 12:15:18.321  4630  4833 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 12:15:18.321  4630  4704 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-24 12:15:18.324  4630  4630 D BluetoothMapService: Received stop request...Stopping profile...
11-24 12:15:18.324  4630  4630 D BluetoothMapService: stop()
11-24 12:15:18.325  4630  4630 D BluetoothMapAppObserver: deinitObservers()
11-24 12:15:18.325  4630  4630 D BluetoothMapAppObserver: removeReceiver()
11-24 12:15:18.327  4630  4630 D SapService: Received stop request...Stopping profile...
11-24 12:15:18.327  4630  4630 V SapService: stop()
,11-24 12:15:18.327   925  5412 D DhcpClient: Receive thread stopped
,11-24 12:15:18.328  3145  3145 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-24 12:15:18.328  3145  3145 D PanProfile: Bluetooth service disconnected
11-24 12:15:18.329  3145  3145 D BluetoothMap: Proxy object disconnected
11-24 12:15:18.329  3145  3145 D MapProfile: Bluetooth service disconnected
11-24 12:15:18.333  4630  4630 V BluetoothAdapterState: isTurningOff()=true
11-24 12:15:18.333  4630  4630 V BluetoothAdapterState: isTurningOn()=false
11-24 12:15:18.333  4630  4630 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:15:18.333  4630  4630 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:15:18.333  4630  4630 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-24 12:15:18.333  4630  4630 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-24 12:15:18.334  4630  4704 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-24 12:15:18.334  4630  4630 V BluetoothAdapterState: isTurningOff()=true
11-24 12:15:18.334  4630  4630 V BluetoothAdapterState: isTurningOn()=false
11-24 12:15:18.334  4630  4630 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:15:18.334  4630  4630 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:15:18.334  4630  4630 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-24 12:15:18.334  4630  4704 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-24 12:15:18.334  4630  4630 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-24 12:15:18.335  4630  4630 V BluetoothAdapterState: isTurningOff()=true
11-24 12:15:18.335  4630  4630 V BluetoothAdapterState: isTurningOn()=false
11-24 12:15:18.335  4630  4630 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 12:15:18.335  4630  4630 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:15:18.335  4630  4630 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-24 12:15:18.335  4630  4630 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-24 12:15:18.336  4630  4630 D BluetoothMapService: MAP Service closeService in
11-24 12:15:18.336  4630  4630 V BluetoothAdapterState: isTurningOff()=true
11-24 12:15:18.336  4630  4630 V BluetoothAdapterState: isTurningOn()=false
11-24 12:15:18.336  4630  4630 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:15:18.336  4630  4630 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:15:18.336  4630  4630 D BluetoothMapService: cleanup()
,11-24 12:15:18.336  4630  4630 D BluetoothMapService: MAP Service closeService in
11-24 12:15:18.336  4630  4630 V BluetoothAdapterState: isTurningOff()=true
11-24 12:15:18.336  4630  4630 V BluetoothAdapterState: isTurningOn()=false
11-24 12:15:18.337  4630  4630 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:15:18.337  4630  4630 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:15:18.337   925  2989 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-24 12:15:18.337  4630  4700 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-24 12:15:18.337  4630  4700 D BluetoothAdapterProperties: Setting state to 15
11-24 12:15:18.337  4630  4700 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-24 12:15:18.338   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 12:15:18.338  3145  3156 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-24 12:15:18.338   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 12:15:18.339  3145  4009 D BluetoothPan: onBluetoothStateChange on: false
11-24 12:15:18.339  4630  4700 I BluetoothAdapterState: Entering BleOnState
11-24 12:15:18.340  3145  3158 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 12:15:18.344   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 12:15:18.344  3145  3156 D BluetoothMap: onBluetoothStateChange: up=false
11-24 12:15:18.345  3145  4009 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-24 12:15:18.345  3826  4149 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 12:15:18.345   925  2989 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 12:15:18.346  3145  3158 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 12:15:18.346   925   942 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 12:15:18.347  4630  4700 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-24 12:15:18.347  4630  4700 D BluetoothAdapterProperties: Setting state to 16
11-24 12:15:18.347  4630  4700 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-24 12:15:18.347  4630  4700 D BluetoothAdapterProperties: onBleDisable
11-24 12:15:18.348  4630  4700 I BluetoothAdapterState: Entering PendingCommandState
11-24 12:15:18.348  4630  4701 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-24 12:15:18.349  4630  4833 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
,11-24 12:15:18.349  4630  4833 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 12:15:18.350  4630  4704 D BluetoothAdapterProperties: Scan Mode:20
11-24 12:15:18.352  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 12:15:18.352  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 12:15:18.352  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:15:18.352  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:15:18.352  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 12:15:18.352  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 12:15:18.352  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 12:15:18.352  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 12:15:18.352  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 12:15:18.352  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 12:15:18.353  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 12:15:18.353  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 12:15:18.355  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 12:15:18.359   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 12:15:18.364  5720  5720 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-24 12:15:18.376  5720  5720 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 12:15:18.381   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5e3c281:true
,11-24 12:15:18.384  3596  3596 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 12:15:18.386   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 12:15:18.387   506   919 D CommandListener: Clearing all IP addresses on wlan0
,11-24 12:15:18.387   925  2991 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-24 12:15:18.387   925  2991 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-24 12:15:18.388   506   919 D TetherController: Setting IP forward enable = 0
,11-24 12:15:18.397   925  3899 I ActivityManager: Start proc 5742:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-24 12:15:18.398   925  2989 D DhcpClient: doQuit
,11-24 12:15:18.399   925  2989 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 12:15:18.399   925  5411 D DhcpClient: onQuitting
11-24 12:15:18.400  3454  3454 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-24 12:15:18.403   925   942 D Tethering: MasterInitialState.processMessage what=3
,11-24 12:15:18.406  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 12:15:18.406  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 12:15:18.406  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:15:18.406  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:15:18.406  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 12:15:18.406  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 12:15:18.406  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 12:15:18.406  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 12:15:18.406  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 12:15:18.406  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 12:15:18.407  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 12:15:18.407  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 12:15:18.408  5318  5318 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@a94d7ef and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
11-24 12:15:18.408  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 12:15:18.409  3978  3978 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
11-24 12:15:18.415  5068  5092 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-24 12:15:18.416  5068  5092 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 12:15:18.416  5068  5092 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
,11-24 12:15:18.416  5068  5092 E SarControlService: no key has been found,reset the power
11-24 12:15:18.416  5068  5105 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 12:15:18.417  5068  5105 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 12:15:18.417  5068  5105 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 12:15:18.417  5093  5093 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-24 12:15:18.418  5093  5093 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 12:15:18.419  5068  5105 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 12:15:18.419  5068  5105 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 12:15:18.419  5068  5105 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 12:15:18.420  5093  5093 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 12:15:18.421  5093  5093 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 12:15:18.430  3454  3454 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-24 12:15:18.430  5093  5107 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@26ed00d HexData = [00000000ea03000000000000ffffffff]
11-24 12:15:18.431  5093  5107 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 12:15:18.431  5093  5107 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-24 12:15:18.433  5093  5093 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 12:15:18.433  5068  5079 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-24 12:15:18.436  3454  3454 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-24 12:15:18.437  5093  5107 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@26ed00d HexData = [00000000eb03000000000000ffffffff]
11-24 12:15:18.437  5093  5107 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 12:15:18.437  5093  5107 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-24 12:15:18.438  5093  5093 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 12:15:18.438  5068  5078 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-24 12:15:18.444  5720  5720 D LocalBluetoothProfileManager: Adding local MAP profile
11-24 12:15:18.446  5720  5720 D BluetoothMap: Create BluetoothMap proxy object
11-24 12:15:18.455  5742  5742 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
11-24 12:15:18.462  5720  5720 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-24 12:15:18.468   506   919 E Netd    : netlink response contains error (No such file or directory)
,11-24 12:15:18.469   506   919 D TetherController: Setting IP forward enable = 0
11-24 12:15:18.470   925  2991 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-24 12:15:18.477  3454  3454 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-24 12:15:18.481  5720  5720 D DockEventReceiver: finishStartingService: stopping service
,11-24 12:15:18.484   925  3846 I ActivityManager: Killing 4977:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-24 12:15:18.510  3454  3454 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-24 12:15:18.553  4630  4704 I bt_hci  : shut_down
,11-24 12:15:18.557  4630  4710 D bt_hwcfg: hw_epilog_process
,11-24 12:15:18.557  4630  4710 I bt_vendor: low_power_mode_cb
,11-24 12:15:18.560  4630  4710 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-24 12:15:18.560  4630  4710 I bt_vendor: epilog_cb
11-24 12:15:18.560  4630  4710 I bt_hci  : epilog_finished_callback
,11-24 12:15:18.562  4630  4704 I bt_hci_h4: hal_close
,11-24 12:15:18.563  4630  4704 I bt_userial_vendor: device fd = 54 close
,11-24 12:15:18.613   925  2989 D wifi    : In wifi stop Hal
,11-24 12:15:18.613  5040  5040 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 12:15:18.613   925  2989 D wifi    : halHandle = 0x7f68784080, mVM = 0x7f84e0d140, mCls = 0x100a02
11-24 12:15:18.614   925  3453 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-24 12:15:18.614   925  3453 D WifiHAL : Got a signal to exit!!!
11-24 12:15:18.614   925  3453 I WifiHAL : Exit wifi_event_loop
11-24 12:15:18.615   925  2989 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
,11-24 12:15:18.615   925  2989 E WifiHAL : Event processing terminated
11-24 12:15:18.615   925  2989 D wifi    : In wifi cleaned up handler
11-24 12:15:18.615   925  2989 I WifiHAL : Internal cleanup completed
11-24 12:15:18.616  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 12:15:18.616  4115  4241 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 12:15:18.651   925  3453 D wifi    : set interface wlan0 flags (DOWN)
,11-24 12:15:18.652   925  2989 D WifiNative-HAL: HAL event thread stopped successfully
,11-24 12:15:18.653  5742  5742 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-24 12:15:18.653  5742  5742 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 12:15:18.653  5742  5742 D StrictMode: StrictMode policy violation; ~duration=113 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 12:15:18.653  5742  5742 D StrictMode: StrictMode policy violation; ~duration=112 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.r.e.b(PG:170)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 12:15:18.653  5742  5742 D StrictMode: StrictMode policy violation; ~duration=105 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.r.k.d(PG:583)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.r.e.b(PG:170)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 12:15:18.653  5742  5742 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 12:15:18.653  5742  5742 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at java.io.File.exists(File.java:361)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 12:15:18.653  5742  5742 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 12:15:18.653  5742  5742 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 12:15:18.658  5720  5720 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 12:15:18.663  3596  3596 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 12:15:18.680   925  3846 I ActivityManager: Start proc 5781:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
11-24 12:15:18.682  5720  5720 D DockEventReceiver: finishStartingService: stopping service
11-24 12:15:18.683   925  3142 I ActivityManager: Killing 5485:com.qualcomm.timeservice/1000 (adj 15): empty #17
,11-24 12:15:18.722  4630  4701 D bt_stack_manager: event_shut_down_stack finished.
11-24 12:15:18.722  4630  4700 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-24 12:15:18.724  4630  4700 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-24 12:15:18.724  4630  4630 D BtGatt.DebugUtils: handleDebugAction() action=null
11-24 12:15:18.724  4630  4630 D BtGatt.GattService: Received stop request...Stopping profile...
11-24 12:15:18.724  4630  4630 D BtGatt.GattService: stop()
11-24 12:15:18.724  4630  4630 D BtGatt.AdvertiseManager: advertise clients cleared
11-24 12:15:18.726  4630  4630 V BluetoothAdapterState: isTurningOff()=false
11-24 12:15:18.726  4630  4630 V BluetoothAdapterState: isTurningOn()=false
11-24 12:15:18.726  4630  4630 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:15:18.726  4630  4630 V BluetoothAdapterState: isBleTurningOff()=true
11-24 12:15:18.726  4630  4700 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-24 12:15:18.726  4630  4700 D BluetoothAdapterProperties: Setting state to 10
11-24 12:15:18.726  4630  4700 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-24 12:15:18.727  4630  4700 I BluetoothAdapterState: Entering OffState
11-24 12:15:18.727   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-24 12:15:18.732  4630  4630 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-24 12:15:18.732  4630  4630 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-24 12:15:18.732  4630  4630 I BluetoothServiceJni: cleanupNative: return from cleanup
11-24 12:15:18.733  4630  4701 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-24 12:15:18.740  5781  5781 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-24 12:15:18.744  4630  4701 D bt_stack_manager: event_clean_up_stack finished.
,11-24 12:15:18.745  4630  4630 I art     : System.exit called, status: 0
11-24 12:15:18.745  4630  4630 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-24 12:15:18.756   925   936 I ActivityManager: Killing 5469:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,11-24 12:15:18.778  3893  3893 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-24 12:15:18.784  3893  3893 D SystemUpdateService: onCreate
,11-24 12:15:18.787  3893  3893 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 12:15:18.789   925  3142 I ActivityManager: Process com.android.bluetooth (pid 4630) has died
,11-24 12:15:18.796  3893  3893 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-24 12:15:18.801  3893  5437 I iu.UploadsManager: num queued entries: 0
,11-24 12:15:18.801  3893  5437 I iu.UploadsManager: num updated entries: 0
,11-24 12:15:18.802  3893  5437 I iu.SyncManager: NEXT; no task
,11-24 12:15:18.815  3893  3893 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 12:15:18.817  3893  3893 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 12:15:18.820  3893  5797 I SystemUpdateService: active receiver: enabled
,11-24 12:15:18.826  3893  5797 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 12:15:18.828   925   936 I ActivityManager: Start proc 5799:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-24 12:15:18.833  3893  5797 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-24 12:15:18.834  3893  5797 I SystemUpdateService: now status is 0 (complete)
11-24 12:15:18.834  3893  5797 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 12:15:18.834  3893  5797 I SystemUpdateService: file has been verified
11-24 12:15:18.835  3893  5797 I SystemUpdateService: OTA package size = 21989297
,11-24 12:15:18.854   925   942 D Tethering: InitialState.processMessage what=4
,11-24 12:15:18.857   925   942 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-24 12:15:18.869  5799  5799 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-24 12:15:18.872  5799  5799 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 12:15:18.885  5799  5799 D SprintDMHelper: simOperator: 
,11-24 12:15:18.885  5799  5799 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 12:15:18.887  3893  5797 I SystemUpdateService: showing system update notification
,11-24 12:15:18.897   925  3917 I ActivityManager: Start proc 5812:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-24 12:15:18.953  3893  3893 D SystemUpdateService: onDestroy
,11-24 12:15:18.954   925  3427 I ActivityManager: Killing 5318:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-24 12:15:19.008  5040  5826 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-24 12:15:19.014   925  5184 I ActivityManager: Start proc 5827:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,11-24 12:15:19.016   925  3426 I ActivityManager: Killing 4714:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-24 12:15:19.069  5827  5827 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,11-24 12:15:19.227   591   591 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 12:15:19.257   925  3426 I ActivityManager: Killing 5534:com.android.defcontainer/u0a7 (adj 15): empty #17
,11-24 12:15:19.285  5742  5775 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-24 12:15:19.337   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5509561:true
,11-24 12:15:23.300   925  5184 D WifiService: setWifiEnabled: true pid=5664, uid=10077
,11-24 12:15:23.301   925  5184 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 12:15:23.308   506   919 D SoftapController: Softap fwReload - Ok
,11-24 12:15:23.314   506   919 D CommandListener: Setting iface cfg
11-24 12:15:23.315   506   919 D CommandListener: Trying to bring down wlan0
,11-24 12:15:23.316   506   919 D CommandListener: Clearing all IP addresses on wlan0
,11-24 12:15:23.322   925  2989 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 12:15:23.889   925  2989 D wifi    : set interface wlan0 flags (UP)
,11-24 12:15:23.892   925  2989 I WifiHAL : Initializing wifi
11-24 12:15:23.892   925  2989 I WifiHAL : Creating socket
11-24 12:15:23.893   925   942 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-24 12:15:23.899   925  2989 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-24 12:15:23.899   925  2989 D wifi    : Did set static halHandle = 0x7f68784080
11-24 12:15:23.899   925  2989 D wifi    : halHandle = 0x7f68784080, mVM = 0x7f84e0d140, mCls = 0x18e2
,11-24 12:15:23.899   925  2989 D wifi    : array field set
,11-24 12:15:23.900   925  2989 I WifiNative-HAL: interface[0] = wlan0
11-24 12:15:23.901   925  5846 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547213557888
11-24 12:15:23.901   925  5846 D wifi    : waitForHalEvents called, vm = 0x7f84e0d140, obj = 0x18e2, env = 0x7f687ed780
,11-24 12:15:23.969  5847  5847 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-24 12:15:23.985  5847  5847 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 12:15:23.993  5847  5847 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 12:15:23.993  5847  5847 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-24 12:15:24.001   925  2989 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-24 12:15:24.005  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 12:15:24.005  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 12:15:24.005  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:15:24.005  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:15:24.005  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 12:15:24.005  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 12:15:24.005  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 12:15:24.005  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 12:15:24.005  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 12:15:24.005  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 12:15:24.005  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 12:15:24.005  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 12:15:24.005   925  2989 D WifiConfigStore: Loading config and enabling all networks 
11-24 12:15:24.007  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 12:15:24.013   925  2989 D WifiConfigStore: loaded 0 passpoint configs
11-24 12:15:24.013   925  2989 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
11-24 12:15:24.014   925  2989 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-24 12:15:24.014   925  2989 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-24 12:15:24.015   925  2989 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-24 12:15:24.015   925  2989 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-24 12:15:24.015   925  2989 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-24 12:15:24.015   925  2989 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-24 12:15:24.018   925  2989 D WifiNative-HAL: Setting external_sim to 1
,11-24 12:15:24.018   925  2989 D wifi    : setting dfs flag to true, 0x7f6cb12680
,11-24 12:15:24.018  5040  5040 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 12:15:24.018   925  2989 D WifiStateMachine: Setting OUI to DA-A1-19
,11-24 12:15:24.018   925  2989 D wifi    : setting scan oui 0x7f6cb12680
11-24 12:15:24.018   925  2989 D WifiHAL : Sending mac address OUI
,11-24 12:15:24.021   925  2989 E native  : do suspend false
,11-24 12:15:24.027   925  2989 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-24 12:15:24.028   925   925 D RttService: SCAN_AVAILABLE : 3
11-24 12:15:24.028   925  3097 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-24 12:15:24.032   506   919 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-24 12:15:24.033   506   919 D CommandListener: Setting iface cfg
,11-24 12:15:24.036   925  2988 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '128 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 128 Failed to set address (No such device)'
11-24 12:15:24.036   925  2988 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-24 12:15:24.041   925  2988 D WifiNative-HAL: p2pGetDeviceAddress
11-24 12:15:24.041   925  2988 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-24 12:15:24.046   925   940 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=129426 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=14 mControllerEnergyUsed=53 }
,11-24 12:15:24.228   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:15:25.229   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:15:26.230   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:15:27.087  5847  5847 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 12:15:27.091  5847  5847 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 12:15:27.096  5847  5847 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 12:15:27.145   925  2989 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-24 12:15:27.146   925  2989 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-24 12:15:27.146   925  2989 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 12:15:27.158   925  2989 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-24 12:15:27.193   925  2989 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-24 12:15:27.195  5847  5847 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-24 12:15:27.231   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:15:27.617  5847  5847 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-24 12:15:27.658  5847  5847 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-24 12:15:27.659  5847  5847 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-24 12:15:27.667   925  2989 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 12:15:27.668   925  2989 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-24 12:15:27.668   925  2991 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-24 12:15:27.686   925  2989 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 12:15:27.696   506   919 D CommandListener: Setting iface cfg
,11-24 12:15:27.702   925  2989 D WifiStateMachine: Start Dhcp Watchdog 2
,11-24 12:15:27.709   925  5855 D DhcpClient: Receive thread started
,11-24 12:15:27.713   925  2989 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-24 12:15:27.714   925  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-24 12:15:27.714   925  2991 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-24 12:15:27.794   925  2989 E native  : do suspend false
,11-24 12:15:27.809   925  5854 D DhcpClient: Broadcasting DHCPDISCOVER
,11-24 12:15:27.824   925  5855 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172708, domain null
,11-24 12:15:27.824   925  5854 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172708 seconds
,11-24 12:15:27.826   925  5854 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-24 12:15:27.850   925  5855 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
11-24 12:15:27.851   925  5854 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-24 12:15:27.853   506   919 D CommandListener: Setting iface cfg
,11-24 12:15:27.858   925  2989 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-24 12:15:27.863   925  5854 D DhcpClient: Scheduling renewal in 86399s
,11-24 12:15:27.874   925  2989 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-24 12:15:27.875   925  2989 D WifiConfigStore: No blacklist allowed without epno enabled
,11-24 12:15:27.877   925  2991 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-24 12:15:27.879   925  2991 D ConnectivityService: Adding iface wlan0 to network 101
,11-24 12:15:27.885   925  2989 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-24 12:15:27.927   925  2991 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-24 12:15:27.928   925  2991 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-24 12:15:27.930   925  2991 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-24 12:15:27.933   925  2991 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-24 12:15:27.935   925  2991 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-24 12:15:27.943   925  2991 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 12:15:27.947   925  2991 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-24 12:15:27.948   925  2991 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-24 12:15:27.948   925  2991 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-24 12:15:27.948   925  2991 D ConnectivityService:    accepting network in place of null
11-24 12:15:27.948   925  2989 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-24 12:15:27.948   925  2989 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 12:15:27.948   925  2991 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -41]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 12:15:27.966   925  5853 D NetlinkSocketObserver: NeighborEvent{elapsedMs=133345, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 12:15:27.973   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 12:15:27.995   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 12:15:27.998   925  2991 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-24 12:15:27.998  3775  3927 W QCNEJ   : |CORE| network available: 101
11-24 12:15:27.998   925  2991 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-24 12:15:28.000   925  2991 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-24 12:15:28.000   925   942 D Tethering: MasterInitialState.processMessage what=3
11-24 12:15:28.003  3775  3927 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-24 12:15:28.004  3775  3927 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-24 12:15:28.004  3775  3927 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-24 12:15:28.006  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 12:15:28.006  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 12:15:28.006  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:15:28.006  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:15:28.006  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 12:15:28.006  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 12:15:28.006  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-24 12:15:28.006  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-24 12:15:28.006  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-24 12:15:28.006  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-24 12:15:28.006  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 12:15:28.006  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-24 12:15:28.011  5068  5092 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-24 12:15:28.011  5068  5092 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 12:15:28.011  5068  5092 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-24 12:15:28.011  5068  5092 E SarControlService: no key has been found,reset the power
11-24 12:15:28.011  5068  5105 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 12:15:28.011  5068  5105 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 12:15:28.012  5068  5105 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-24 12:15:28.012  5093  5093 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 12:15:28.012  5093  5093 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 12:15:28.016  3978  3978 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-24 12:15:28.017  5068  5105 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 12:15:28.017  5068  5105 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-24 12:15:28.019  5068  5105 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-24 12:15:28.019  3893  3893 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-24 12:15:28.023  5093  5107 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@26ed00d HexData = [00000000ec03000000000000ffffffff]
11-24 12:15:28.023  5093  5107 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 12:15:28.023  5093  5107 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-24 12:15:28.023  5093  5093 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-24 12:15:28.024  5068  5079 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-24 12:15:28.024  3893  3893 D SystemUpdateService: onCreate
11-24 12:15:28.026  5093  5093 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 12:15:28.026  5093  5093 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-24 12:15:28.028  5093  5107 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@26ed00d HexData = [00000000ed03000000000000ffffffff]
,11-24 12:15:28.028  5093  5107 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 12:15:28.028  5093  5107 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
11-24 12:15:28.029  5093  5093 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 12:15:28.029  5068  5078 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-24 12:15:28.032  3893  3893 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 12:15:28.036   925  5852 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-24 12:15:28.042  3893  3893 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-24 12:15:28.050  3893  5437 I iu.UploadsManager: num queued entries: 0
,11-24 12:15:28.052  3893  3893 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 12:15:28.053  3893  3893 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 12:15:28.055  5799  5799 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-24 12:15:28.058  5799  5799 D SprintDMHelper: simOperator: 
11-24 12:15:28.058  5799  5799 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 12:15:28.068  3893  5867 I SystemUpdateService: active receiver: enabled
,11-24 12:15:28.071  3893  5437 I iu.UploadsManager: num updated entries: 0
,11-24 12:15:28.083  3893  5437 I iu.SyncManager: NEXT; no task
,11-24 12:15:28.094  3893  5867 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 12:15:28.100   925  5852 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Nov 2016 17:15:28 GMT], X-Android-Received-Millis=[1480007728099], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480007728068]}
,11-24 12:15:28.100   925  2991 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-24 12:15:28.100   925  2991 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-24 12:15:28.100   925  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-24 12:15:28.102   925  2991 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-24 12:15:28.102  3893  5867 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-24 12:15:28.102  3893  5867 I SystemUpdateService: now status is 0 (complete)
11-24 12:15:28.102  3893  5867 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 12:15:28.102  3893  5867 I SystemUpdateService: file has been verified
,11-24 12:15:28.102  3893  5867 I SystemUpdateService: OTA package size = 21989297
,11-24 12:15:28.108  3893  5867 I SystemUpdateService: showing system update notification
,11-24 12:15:28.121  3893  3893 D SystemUpdateService: onDestroy
,11-24 12:15:28.164  5040  5872 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-24 12:15:28.232   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:15:28.306   925  3426 D WifiService: setWifiEnabled: false pid=5664, uid=10077
11-24 12:15:28.306   925  3426 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 12:15:28.314   925  2989 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-24 12:15:28.314   925  2989 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-24 12:15:28.314   925  2989 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 12:15:28.315   925  2989 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 12:15:28.332   925  5854 D DhcpClient: Clearing IP address
,11-24 12:15:28.332   506   919 D CommandListener: Clearing all IP addresses on wlan0
11-24 12:15:28.334   506   919 D CommandListener: Setting iface cfg
11-24 12:15:28.336  3596  5878 V NativeCrypto: Read error: ssl=0x7f83619c00: I/O error during system call, Connection timed out
11-24 12:15:28.337  3596  5878 V NativeCrypto: SSL shutdown failed: ssl=0x7f83619c00: I/O error during system call, Broken pipe
,11-24 12:15:28.339   925  3855 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
,11-24 12:15:28.339   925  5852 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
11-24 12:15:28.340   925  5852 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
,11-24 12:15:28.348   925  2991 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-24 12:15:28.348   925  2991 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-24 12:15:28.350   925  5852 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:81d::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,11-24 12:15:28.353   925  2991 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,11-24 12:15:28.354   589   589 E Parcel  : Reading a NULL string not supported here.
,11-24 12:15:28.355   925   925 D RttService: SCAN_AVAILABLE : 1
11-24 12:15:28.355  3775  3927 W QCNEJ   : |CORE| network lost: 101
11-24 12:15:28.355   925  3097 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-24 12:15:28.355  3775  3927 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-24 12:15:28.358   925  2989 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-24 12:15:28.360   925  2989 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-24 12:15:28.367   925  5855 D DhcpClient: Receive thread stopped
,11-24 12:15:28.376   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 12:15:28.397   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 12:15:28.397   506   919 D CommandListener: Clearing all IP addresses on wlan0
11-24 12:15:28.397   925  2991 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-24 12:15:28.398   925  2991 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-24 12:15:28.399   925   942 D Tethering: MasterInitialState.processMessage what=3
11-24 12:15:28.402  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 12:15:28.402  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 12:15:28.402  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:15:28.402  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:15:28.402  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 12:15:28.402  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 12:15:28.402  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 12:15:28.402  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 12:15:28.402  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 12:15:28.402  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 12:15:28.402  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 12:15:28.402  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 12:15:28.405   925  2989 D DhcpClient: doQuit
,11-24 12:15:28.405   925  2989 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-24 12:15:28.405   925  5854 D DhcpClient: onQuitting
11-24 12:15:28.406  5847  5847 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-24 12:15:28.403  3978  3978 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-24 12:15:28.409  5068  5092 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-24 12:15:28.409  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 12:15:28.409  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 12:15:28.409  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:15:28.409  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:15:28.409  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 12:15:28.409  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 12:15:28.409  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 12:15:28.409  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 12:15:28.409  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 12:15:28.409  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 12:15:28.409  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 12:15:28.409  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 12:15:28.410  3893  3893 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-24 12:15:28.409  5068  5092 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 12:15:28.411  5068  5092 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-24 12:15:28.411  5068  5092 E SarControlService: no key has been found,reset the power
11-24 12:15:28.412  5068  5105 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-24 12:15:28.412  5068  5105 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 12:15:28.412  5068  5105 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,11-24 12:15:28.412  5093  5093 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 12:15:28.412  5093  5093 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 12:15:28.413  5068  5105 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 12:15:28.413  5068  5105 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 12:15:28.414  5068  5105 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 12:15:28.414  5093  5093 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 12:15:28.414  5093  5093 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-24 12:15:28.417  3893  3893 D SystemUpdateService: onCreate
11-24 12:15:28.418  5093  5107 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@26ed00d HexData = [00000000ee03000000000000ffffffff]
,11-24 12:15:28.418  5093  5107 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 12:15:28.418  5093  5107 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-24 12:15:28.418  5093  5093 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 12:15:28.419  5068  5078 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-24 12:15:28.420  5847  5847 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-24 12:15:28.421  5093  5107 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@26ed00d HexData = [00000000ef03000000000000ffffffff]
11-24 12:15:28.421  5093  5107 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 12:15:28.421  5093  5107 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-24 12:15:28.421  5093  5093 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 12:15:28.422  5068  5079 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-24 12:15:28.423  5847  5847 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-24 12:15:28.423  3893  3893 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 12:15:28.428  3893  5886 I SystemUpdateService: active receiver: enabled
,11-24 12:15:28.434  3893  3893 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-24 12:15:28.439  3893  5437 I iu.UploadsManager: num queued entries: 0
,11-24 12:15:28.439  3893  5437 I iu.UploadsManager: num updated entries: 0
11-24 12:15:28.440  3893  5437 I iu.SyncManager: NEXT; no task
11-24 12:15:28.440  3893  5886 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 12:15:28.442  3893  3893 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 12:15:28.444  3893  3893 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 12:15:28.445  5799  5799 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 12:15:28.449  5799  5799 D SprintDMHelper: simOperator: 
,11-24 12:15:28.449  5799  5799 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 12:15:28.452  3893  5886 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-24 12:15:28.453  5847  5847 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-24 12:15:28.456  5847  5847 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-24 12:15:28.452  3893  5886 I SystemUpdateService: now status is 0 (complete)
11-24 12:15:28.456  3893  5886 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 12:15:28.456  3893  5886 I SystemUpdateService: file has been verified
11-24 12:15:28.457   506   919 E Netd    : netlink response contains error (No such file or directory)
11-24 12:15:28.457  3893  5886 I SystemUpdateService: OTA package size = 21989297
11-24 12:15:28.458   925  2991 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-24 12:15:28.459   925  2991 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-24 12:15:28.461  5040  5890 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-24 12:15:28.479  3893  5886 I SystemUpdateService: showing system update notification
,11-24 12:15:28.487  3893  3893 D SystemUpdateService: onDestroy
,11-24 12:15:28.557   925  2989 D wifi    : In wifi stop Hal
,11-24 12:15:28.557   925  2989 D wifi    : halHandle = 0x7f68784080, mVM = 0x7f84e0d140, mCls = 0x18e2
11-24 12:15:28.558  5040  5040 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-24 12:15:28.559  4115  4241 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 12:15:28.559  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 12:15:28.559   925  5846 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-24 12:15:28.561   925  5846 D WifiHAL : Got a signal to exit!!!
11-24 12:15:28.561   925  5846 I WifiHAL : Exit wifi_event_loop
,11-24 12:15:28.561   925  2989 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-24 12:15:28.561   925  2989 E WifiHAL : Event processing terminated
11-24 12:15:28.561   925  2989 D wifi    : In wifi cleaned up handler
11-24 12:15:28.561   925  2989 I WifiHAL : Internal cleanup completed
,11-24 12:15:28.582   925  5846 D wifi    : set interface wlan0 flags (DOWN)
,11-24 12:15:28.583   925  2989 D WifiNative-HAL: HAL event thread stopped successfully
,11-24 12:15:28.789   925   942 D Tethering: InitialState.processMessage what=4
,11-24 12:15:28.796   925   942 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-24 12:15:28.999   925  2991 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-24 12:15:29.232   591   591 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 12:15:33.348   925   942 I ActivityManager: Start proc 5894:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-24 12:15:33.450  5894  5894 D AdapterServiceConfig: Adding HeadsetService
,11-24 12:15:33.450  5894  5894 D AdapterServiceConfig: Adding A2dpService
,11-24 12:15:33.450  5894  5894 D AdapterServiceConfig: Adding HidService
,11-24 12:15:33.451  5894  5894 D AdapterServiceConfig: Adding HealthService
11-24 12:15:33.451  5894  5894 D AdapterServiceConfig: Adding PanService
11-24 12:15:33.451  5894  5894 D AdapterServiceConfig: Adding GattService
11-24 12:15:33.451  5894  5894 D AdapterServiceConfig: Adding BluetoothMapService
11-24 12:15:33.451  5894  5894 D AdapterServiceConfig: Adding SapService
,11-24 12:15:33.466   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@11a3cc:true
,11-24 12:15:33.467  5894  5894 D BluetoothAdapterState: make() - Creating AdapterState
,11-24 12:15:33.470  5894  5894 I bt_bluedroid: init
,11-24 12:15:33.470  5894  5906 I BluetoothAdapterState: Entering OffState
,11-24 12:15:33.473  5894  5907 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-24 12:15:33.473  5894  5907 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-24 12:15:33.473  5894  5907 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-24 12:15:33.473  5894  5907 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-24 12:15:33.474  5894  5894 I bt_bluedroid: get_profile_interface socket
,11-24 12:15:33.475  5894  5910 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-24 12:15:33.475  5894  5894 I bt_bluedroid: get_profile_interface sdp
11-24 12:15:33.477  5894  5910 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 12:15:33.480  5894  5905 I bt_bluedroid: config_hci_snoop_log
,11-24 12:15:33.481   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
11-24 12:15:33.485  5894  5906 D BluetoothAdapterState: Current state: OFF, message: 0
11-24 12:15:33.485  5894  5906 D BluetoothAdapterProperties: Setting state to 14
11-24 12:15:33.485  5894  5906 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-24 12:15:33.487  5894  5906 D BluetoothBondStateMachine: make
,11-24 12:15:33.489  5894  5911 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-24 12:15:33.491  5894  5906 I BluetoothAdapterState: Entering PendingCommandState
,11-24 12:15:33.492  5894  5894 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-24 12:15:33.494  5894  5894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
,11-24 12:15:33.495  5894  5894 D BtGatt.DebugUtils: handleDebugAction() action=null
11-24 12:15:33.495  5894  5894 D BtGatt.GattService: Received start request. Starting profile...
,11-24 12:15:33.496  5894  5894 D BtGatt.GattService: start()
11-24 12:15:33.496  5894  5894 I bt_bluedroid: get_profile_interface gatt
,11-24 12:15:33.497  5894  5894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
11-24 12:15:33.497  5894  5894 D BtGatt.AdvertiseManager: advertise manager created
,11-24 12:15:33.502  5894  5894 V BluetoothAdapterState: isTurningOff()=false
11-24 12:15:33.502  5894  5894 V BluetoothAdapterState: isTurningOn()=false
11-24 12:15:33.502  5894  5894 V BluetoothAdapterState: isBleTurningOn()=true
11-24 12:15:33.502  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:15:33.503  5894  5906 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-24 12:15:33.504  5894  5906 I bt_bluedroid: bt_bluedroid
,11-24 12:15:33.504  5894  5907 D bt_stack_manager: event_start_up_stack is bringing up the stack.
11-24 12:15:33.504  5894  5907 I bt_hci  : start_up
,11-24 12:15:33.509  5894  5907 I bt_vendor: alloc value 0xf3e11871
,11-24 12:15:33.509  5894  5907 I bt_vendor: init
11-24 12:15:33.509  5894  5907 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-24 12:15:33.509  5894  5907 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-24 12:15:33.620  5894  5907 D bt_hci  : start_up starting async portion
,11-24 12:15:33.621  5894  5914 I bt_hci  : event_finish_startup
11-24 12:15:33.621  5894  5914 I bt_hci_h4: hal_open
11-24 12:15:33.621  5894  5914 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-24 12:15:33.625  5894  5914 I bt_userial_vendor: device fd = 54 open
,11-24 12:15:33.618  5915  5915 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 12:15:33.639  5894  5914 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 12:15:33.642  5894  5914 D bt_hwcfg: Chipset BCM4358A3
,11-24 12:15:33.642  5894  5914 D bt_hwcfg: Target name = [BCM4358A3]
11-24 12:15:33.642  5894  5914 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-24 12:15:34.040  5894  5914 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-24 12:15:34.040  5894  5914 D bt_hwcfg: Settlement delay -- 100 ms
11-24 12:15:34.040  5894  5914 I bt_hwcfg: Setting fw settlement delay to 100 
,11-24 12:15:34.176  5894  5914 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-24 12:15:34.176  5894  5914 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
11-24 12:15:34.177  5894  5914 I bt_hwcfg: vendor lib fwcfg completed
11-24 12:15:34.178  5894  5914 I bt_vendor: firmware callback
11-24 12:15:34.178  5894  5914 I bt_hci  : firmware_config_callback
,11-24 12:15:34.186  5894  5917 I bt_btu  : btu_task pending for preload complete event
,11-24 12:15:34.186  5894  5917 I bt_btu_task: Bluetooth chip preload is complete
11-24 12:15:34.186  5894  5917 I bt_btu  : btu_task received preload complete event
,11-24 12:15:34.193  5894  5917 I         : BTE_InitTraceLevels -- TRC_HCI
,11-24 12:15:34.193  5894  5917 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-24 12:15:34.193  5894  5917 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-24 12:15:34.193  5894  5917 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-24 12:15:34.193  5894  5917 I         : BTE_InitTraceLevels -- TRC_AVRC
11-24 12:15:34.194  5894  5917 I         : BTE_InitTraceLevels -- TRC_A2D
11-24 12:15:34.194  5894  5917 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-24 12:15:34.194  5894  5917 I         : BTE_InitTraceLevels -- TRC_BTM
11-24 12:15:34.194  5894  5917 I         : BTE_InitTraceLevels -- TRC_GAP
11-24 12:15:34.194  5894  5917 I         : BTE_InitTraceLevels -- TRC_PAN
,11-24 12:15:34.194  5894  5917 I         : BTE_InitTraceLevels -- TRC_SDP
11-24 12:15:34.194  5894  5917 I         : BTE_InitTraceLevels -- TRC_GATT
11-24 12:15:34.194  5894  5917 I         : BTE_InitTraceLevels -- TRC_SMP
11-24 12:15:34.194  5894  5917 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-24 12:15:34.195  5894  5917 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-24 12:15:34.280  5894  5917 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3d8f549
,11-24 12:15:34.280  5894  5917 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3d8f549 
,11-24 12:15:34.300  5894  5910 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-24 12:15:34.302  5894  5910 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-24 12:15:34.302  5894  5910 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-24 12:15:34.305  5894  5910 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 12:15:34.307  5894  5910 D BluetoothAdapterProperties: Scan Mode:20
11-24 12:15:34.308  5894  5910 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 12:15:34.308  5894  5910 D bt_hci  : do_postload posting postload work item
11-24 12:15:34.309  5894  5914 I bt_hci  : event_postload
11-24 12:15:34.309  5894  5914 I bt_vendor: sco_config_cb
11-24 12:15:34.309  5894  5914 I bt_hci  : sco_config_callback postload finished.
,11-24 12:15:34.311  5894  5910 D bt_bte_conf: Device ID record 1 : primary
,11-24 12:15:34.311  5894  5910 D bt_bte_conf:   vendorId            = 000f
11-24 12:15:34.311  5894  5910 D bt_bte_conf:   vendorIdSource      = 0001
,11-24 12:15:34.311  5894  5910 D bt_bte_conf:   product             = 1200
11-24 12:15:34.312  5894  5910 D bt_bte_conf:   version             = 1436
,11-24 12:15:34.312  5894  5910 D bt_bte_conf:   clientExecutableURL = 
11-24 12:15:34.312  5894  5910 D bt_bte_conf:   serviceDescription  = 
11-24 12:15:34.312  5894  5910 D bt_bte_conf:   documentationURL    = 
11-24 12:15:34.312  5894  5910 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-24 12:15:34.312  5894  5907 D bt_stack_manager: event_start_up_stack finished
,11-24 12:15:34.313  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 12:15:34.314  5894  5906 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-24 12:15:34.314  5894  5906 D BluetoothAdapterProperties: Setting state to 15
11-24 12:15:34.314  5894  5906 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-24 12:15:34.316  5894  5906 I BluetoothAdapterState: Entering BleOnState
,11-24 12:15:34.320  5894  5914 I bt_vendor: low_power_mode_cb
,11-24 12:15:34.321  5894  5906 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-24 12:15:34.321  5894  5906 D BluetoothAdapterProperties: Setting state to 11
11-24 12:15:34.321  5894  5906 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
11-24 12:15:34.327  5894  5894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
,11-24 12:15:34.328  5894  5894 D HeadsetService: Received start request. Starting profile...
11-24 12:15:34.332  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 12:15:34.333  5894  5894 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-24 12:15:34.334  5894  5894 D HeadsetStateMachine: make
,11-24 12:15:34.343  5894  5906 I BluetoothAdapterState: Entering PendingCommandState
,11-24 12:15:34.346  5894  5894 D HeadsetStateMachine: max_hf_connections = 1
11-24 12:15:34.346  5894  5894 I bt_bluedroid: get_profile_interface handsfree
11-24 12:15:34.346  5894  5910 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-24 12:15:34.347  5894  5910 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-24 12:15:34.350  5894  5894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
,11-24 12:15:34.351  5894  5894 D A2dpService: Received start request. Starting profile...
,11-24 12:15:34.352  5894  5894 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-24 12:15:34.352  5894  5894 I bt_bluedroid: get_profile_interface avrcp
,11-24 12:15:34.359  5894  5894 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-24 12:15:34.359  5894  5894 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-24 12:15:34.359  5894  5894 D A2dpStateMachine: make
11-24 12:15:34.361  5894  5894 I bt_bluedroid: get_profile_interface a2dp
,11-24 12:15:34.362  5894  5910 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-24 12:15:34.364  5894  5925 D A2dpStateMachine: Enter Disconnected: -2
,11-24 12:15:34.364  5894  5894 I BluetoothHidServiceJni: classInitNative: succeeds
,11-24 12:15:34.365  5894  5894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
,11-24 12:15:34.367  5720  5720 D BluetoothInputDevice: Proxy object connected
11-24 12:15:34.367  5720  5720 D HidProfile: Bluetooth service connected
11-24 12:15:34.369  5894  5894 D HidService: Received start request. Starting profile...
11-24 12:15:34.369  5894  5894 I bt_bluedroid: get_profile_interface hidhost
11-24 12:15:34.369  5894  5894 D HidService: setHidService(): set to: null
11-24 12:15:34.369  5894  5910 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d7056d
11-24 12:15:34.370  5894  5910 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-24 12:15:34.370  5894  5894 I BluetoothHealthServiceJni: classInitNative: succeeds
11-24 12:15:34.371  5894  5894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
11-24 12:15:34.371  5894  5894 D HealthService: Received start request. Starting profile...
11-24 12:15:34.373  5894  5894 I bt_bluedroid: get_profile_interface health
,11-24 12:15:34.374  5894  5894 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-24 12:15:34.375  5894  5894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
11-24 12:15:34.376  5720  5720 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 12:15:34.376  5894  5894 D PanService: Received start request. Starting profile...
11-24 12:15:34.376  5720  5720 D PanProfile: Bluetooth service connected
11-24 12:15:34.376  5894  5894 D BluetoothPanServiceJni: initializeNative(L110): pan
11-24 12:15:34.377  5894  5894 I bt_bluedroid: get_profile_interface pan
11-24 12:15:34.377  5894  5910 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-24 12:15:34.383  5894  5894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
,11-24 12:15:34.385  5720  5720 D BluetoothMap: Proxy object connected
,11-24 12:15:34.385  3596  3596 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 12:15:34.385  5720  5720 D MapProfile: Bluetooth service connected
11-24 12:15:34.386  5720  5720 D BluetoothMap: getConnectedDevices()
11-24 12:15:34.386  5720  5720 D BluetoothMap: Bluetooth is Not enabled
11-24 12:15:34.386  5894  5894 D BluetoothMapService: Received start request. Starting profile...
11-24 12:15:34.386  5894  5894 D BluetoothMapService: start()
,11-24 12:15:34.389  5894  5894 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-24 12:15:34.390  5894  5894 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,11-24 12:15:34.390  5894  5894 D BluetoothMapAppObserver: createReceiver()
11-24 12:15:34.391  5894  5894 D BluetoothMapAppObserver: initObservers()
11-24 12:15:34.391  5894  5894 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-24 12:15:34.398  5894  5894 V SapService: SapBinder()
,11-24 12:15:34.398  5894  5894 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
,11-24 12:15:34.399  5894  5894 D SapService: Received start request. Starting profile...
,11-24 12:15:34.399  5894  5894 V SapService: start()
,11-24 12:15:34.402  5894  5894 V BluetoothAdapterState: isTurningOff()=false
,11-24 12:15:34.402  5894  5894 V BluetoothAdapterState: isTurningOn()=true
11-24 12:15:34.402  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:15:34.402  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:15:34.403  5894  5894 V BluetoothAdapterState: isTurningOff()=false
11-24 12:15:34.403  5894  5894 V BluetoothAdapterState: isTurningOn()=true
,11-24 12:15:34.403  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:15:34.403  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:15:34.403  5894  5923 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-24 12:15:34.403  5894  5894 V BluetoothAdapterState: isTurningOff()=false
11-24 12:15:34.403  5894  5894 V BluetoothAdapterState: isTurningOn()=true
11-24 12:15:34.403  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:15:34.403  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 12:15:34.403  5894  5894 V BluetoothAdapterState: isTurningOff()=false
11-24 12:15:34.403  5894  5894 V BluetoothAdapterState: isTurningOn()=true
11-24 12:15:34.403  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:15:34.403  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:15:34.404  5894  5894 V BluetoothAdapterState: isTurningOff()=false
11-24 12:15:34.404  5894  5894 V BluetoothAdapterState: isTurningOn()=true
11-24 12:15:34.404  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 12:15:34.404  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:15:34.404  5894  5894 V BluetoothAdapterState: isTurningOff()=false
11-24 12:15:34.404  5894  5894 V BluetoothAdapterState: isTurningOn()=true
11-24 12:15:34.404  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 12:15:34.404  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:15:34.405  5894  5894 V BluetoothAdapterState: isTurningOff()=false
11-24 12:15:34.405  5894  5894 V BluetoothAdapterState: isTurningOn()=true
11-24 12:15:34.405  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:15:34.406  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 12:15:34.406  5894  5906 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-24 12:15:34.406  5894  5906 D BluetoothAdapterProperties: ScanMode =  20
11-24 12:15:34.406  5894  5906 D BluetoothAdapterProperties: State =  11
11-24 12:15:34.409  5894  5910 D BluetoothAdapterProperties: Scan Mode:21
11-24 12:15:34.409  5894  5906 D BluetoothAdapterProperties: Setting state to 12
11-24 12:15:34.409  5894  5906 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-24 12:15:34.409  5894  5910 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-24 12:15:34.410   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 12:15:34.410  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-24 12:15:34.411  3145  3156 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 12:15:34.411  5894  5906 I BluetoothAdapterState: Entering OnState
11-24 12:15:34.413  3145  3145 D BluetoothInputDevice: Proxy object connected
11-24 12:15:34.413  3145  3145 D HidProfile: Bluetooth service connected
11-24 12:15:34.414   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 12:15:34.414  5720  5731 D BluetoothMap: onBluetoothStateChange: up=true
11-24 12:15:34.414  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 12:15:34.414  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:15:34.414  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:15:34.414  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 12:15:34.414  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 12:15:34.414  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 12:15:34.414  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 12:15:34.414  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 12:15:34.414  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 12:15:34.414  5720  5733 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 12:15:34.415  3145  3158 D BluetoothPan: onBluetoothStateChange on: true
11-24 12:15:34.416  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 12:15:34.416  3145  3145 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 12:15:34.416  3145  5856 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 12:15:34.416  3145  3145 D PanProfile: Bluetooth service connected
,11-24 12:15:34.418  5894  5894 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-24 12:15:34.418  5720  5731 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 12:15:34.418  5894  5894 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-24 12:15:34.419   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 12:15:34.420  3145  3156 D BluetoothMap: onBluetoothStateChange: up=true
11-24 12:15:34.420  5894  5894 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 12:15:34.422  3145  4009 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 12:15:34.422  3145  3145 D BluetoothMap: Proxy object connected
11-24 12:15:34.422  3145  3145 D MapProfile: Bluetooth service connected
,11-24 12:15:34.422  5894  5894 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 12:15:34.422  3145  3145 D BluetoothMap: getConnectedDevices()
11-24 12:15:34.422  3826  4149 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 12:15:34.423  5720  5733 D BluetoothPan: onBluetoothStateChange on: true
11-24 12:15:34.423  5894  5894 D ObexServerSockets: Succeed to create listening sockets 
11-24 12:15:34.423  5894  5894 D ObexServerSockets0: startAccept()
11-24 12:15:34.423  5894  5894 D ObexServerSockets0: prepareForNewConnect()
11-24 12:15:34.423  3145  5856 D BluetoothPbap: onBluetoothStateChange: up=true
,11-24 12:15:34.425   925   942 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 12:15:34.425  5894  5894 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-24 12:15:34.425  5894  5894 D BluetoothSdpJni: SDP Create record success - handle: 0
11-24 12:15:34.426  5894  5930 D ObexServerSockets0: Accepting socket connection...
11-24 12:15:34.426  5894  5931 D ObexServerSockets0: Accepting socket connection...
11-24 12:15:34.427   925   925 I Telecom : BluetoothPhoneService: queryPhoneState
11-24 12:15:34.427  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-24 12:15:34.429   925   925 D BluetoothA2dp: Proxy object connected
11-24 12:15:34.430  5894  5894 D BluetoothMapService: onReceive
11-24 12:15:34.430  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 12:15:34.430  5894  5894 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 12:15:34.430  3145  3145 D BluetoothA2dp: Proxy object connected
11-24 12:15:34.431  5894  5894 D BluetoothMapService: STATE_ON
,11-24 12:15:34.431  5720  5720 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-24 12:15:34.434  5720  5720 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-24 12:15:34.435  5894  5933 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 12:15:34.436  5894  5933 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-24 12:15:34.436  5894  5933 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-24 12:15:34.441  5720  5720 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 12:15:34.442  5720  5720 D BluetoothA2dp: Proxy object connected
,11-24 12:15:34.447  3596  3596 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 12:15:34.448  5720  5720 D DockEventReceiver: finishStartingService: stopping service
,11-24 12:15:34.453  3145  3145 D BluetoothPbap: Proxy object connected
11-24 12:15:34.453  3145  3145 D PbapServerProfile: Bluetooth service connected
11-24 12:15:34.453  5720  5720 D BluetoothPbap: Proxy object connected
11-24 12:15:34.454  5720  5720 D PbapServerProfile: Bluetooth service connected
,11-24 12:15:34.454  5894  5894 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 12:15:34.454  5894  5894 D ObexServerSockets0: prepareForNewConnect()
,11-24 12:15:34.462  5894  5937 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 12:15:34.477  5894  5941 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 12:15:34.478  5894  5941 I BtOppRfcommListener: Accept thread started.
,11-24 12:15:34.511   925   925 D BluetoothHeadset: Proxy object connected
,11-24 12:15:34.511   925   925 D BluetoothHeadset: Proxy object connected
11-24 12:15:34.511  3826  4022 D BluetoothHeadset: Proxy object connected
11-24 12:15:34.511   925   925 D BluetoothHeadset: Proxy object connected
11-24 12:15:34.512  3145  3158 D BluetoothHeadset: Proxy object connected
,11-24 12:15:34.512  3145  3145 D HeadsetProfile: Bluetooth service connected
,11-24 12:15:34.514   925   942 D BluetoothHeadset: Proxy object connected
,11-24 12:15:34.520   925   942 D BluetoothHeadset: Proxy object connected
,11-24 12:15:34.522  3145  4009 D BluetoothHeadset: Proxy object connected
11-24 12:15:34.522  3145  3145 D HeadsetProfile: Bluetooth service connected
,11-24 12:15:34.523  3826  3847 D BluetoothHeadset: Proxy object connected
,11-24 12:15:34.537  5720  5733 D BluetoothHeadset: Proxy object connected
,11-24 12:15:34.538  5720  5720 D HeadsetProfile: Bluetooth service connected
,11-24 12:15:35.955   925  2991 D ConnectivityService: handlePromptUnvalidated 101
,11-24 12:15:38.324  5894  5906 D BluetoothAdapterState: Current state: ON, message: 23
,11-24 12:15:38.324  5894  5906 D BluetoothAdapterProperties: Setting state to 13
11-24 12:15:38.324  5894  5906 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-24 12:15:38.326  5894  5906 D BluetoothAdapterProperties: onBluetoothDisable()
,11-24 12:15:38.328  5894  5906 I BluetoothAdapterState: Entering PendingCommandState
,11-24 12:15:38.331  5894  5894 D BluetoothMapService: onReceive
11-24 12:15:38.332  5894  5894 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 12:15:38.332  5894  5894 D BluetoothMapService: STATE_TURNING_OFF
11-24 12:15:38.333  5894  5894 D BluetoothMapService: MAP Service closeService in
11-24 12:15:38.333  5894  5894 D BluetoothMapMasInstance0: MAP Service shutdown
,11-24 12:15:38.333  5894  5894 D ObexServerSockets0: shutdown(block = true)
,11-24 12:15:38.334  5894  5930 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-24 12:15:38.339  5894  5894 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-24 12:15:38.340  5894  5919 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-24 12:15:38.340  5894  5931 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-24 12:15:38.341  5894  5910 D BluetoothAdapterProperties: Scan Mode:20
11-24 12:15:38.340  5894  5894 D ObexServerSockets0: shutdown called from another thread - interrupt().
,11-24 12:15:38.342  5894  5906 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-24 12:15:38.345  5720  5720 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 12:15:38.345  5894  5894 I BtOppRfcommListener: stopping Accept Thread
11-24 12:15:38.346  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-24 12:15:38.346  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 12:15:38.346  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:15:38.346  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:15:38.346  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 12:15:38.346  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-24 12:15:38.346  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 12:15:38.346  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 12:15:38.346  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 12:15:38.346  5664  5664 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-24 12:15:38.348  5664  5664 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-24 12:15:38.348  5664  5664 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-24 12:15:38.350  5894  5941 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-24 12:15:38.350  5894  5941 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-24 12:15:38.354  5894  5894 D HeadsetService: Received stop request...Stopping profile...
,11-24 12:15:38.355  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 12:15:38.356   925   925 D BluetoothHeadset: Proxy object disconnected
11-24 12:15:38.356   925   925 D BluetoothHeadset: Proxy object disconnected
11-24 12:15:38.357  5720  5720 D DockEventReceiver: finishStartingService: stopping service
,11-24 12:15:38.357  3826  3845 D BluetoothHeadset: Proxy object disconnected
11-24 12:15:38.357   925   925 D BluetoothHeadset: Proxy object disconnected
11-24 12:15:38.358  5720  5731 D BluetoothHeadset: Proxy object disconnected
11-24 12:15:38.359  3145  4009 D BluetoothHeadset: Proxy object disconnected
11-24 12:15:38.361  5720  5720 D HeadsetProfile: Bluetooth service disconnected
11-24 12:15:38.362  3596  3596 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 12:15:38.363  5894  5894 D A2dpService: Received stop request...Stopping profile...
11-24 12:15:38.363  5894  5925 D A2dpStateMachine: Exit Disconnected: -1
11-24 12:15:38.366   925   925 D BluetoothA2dp: Proxy object disconnected
11-24 12:15:38.367  5720  5720 D BluetoothA2dp: Proxy object disconnected
11-24 12:15:38.368  3145  3145 D HeadsetProfile: Bluetooth service disconnected
11-24 12:15:38.368  3145  3145 D BluetoothA2dp: Proxy object disconnected
11-24 12:15:38.368  5894  5894 V BluetoothAdapterState: isTurningOff()=true
11-24 12:15:38.368  5894  5894 V BluetoothAdapterState: isTurningOn()=false
11-24 12:15:38.368  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:15:38.368  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 12:15:38.371  5894  5894 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-24 12:15:38.371  5894  5894 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,11-24 12:15:38.371  5894  5917 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 12:15:38.371  5894  5917 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 12:15:38.371  5894  5917 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 12:15:38.372  5894  5910 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-24 12:15:38.372  5894  5910 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-24 12:15:38.372  5894  5894 D HidService: Received stop request...Stopping profile...
11-24 12:15:38.372  5894  5894 D HidService: Stopping Bluetooth HidService
,11-24 12:15:38.373  3145  3145 D BluetoothInputDevice: Proxy object disconnected
11-24 12:15:38.373  3145  3145 D HidProfile: Bluetooth service disconnected
11-24 12:15:38.376  3145  3145 D BluetoothPbap: Proxy object disconnected
11-24 12:15:38.377  3145  3145 D PbapServerProfile: Bluetooth service disconnected
,11-24 12:15:38.378  5720  5720 D BluetoothInputDevice: Proxy object disconnected
,11-24 12:15:38.378  5720  5720 D HidProfile: Bluetooth service disconnected
11-24 12:15:38.378  5894  5894 D HealthService: Received stop request...Stopping profile...
11-24 12:15:38.378  5720  5720 D BluetoothPbap: Proxy object disconnected
11-24 12:15:38.378  5720  5720 D PbapServerProfile: Bluetooth service disconnected
,11-24 12:15:38.381  5894  5894 D PanService: Received stop request...Stopping profile...
11-24 12:15:38.381  3145  3145 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-24 12:15:38.381  3145  3145 D PanProfile: Bluetooth service disconnected
11-24 12:15:38.382  5894  5894 D BluetoothMapService: Received stop request...Stopping profile...
11-24 12:15:38.382  5894  5894 D BluetoothMapService: stop()
11-24 12:15:38.382  5720  5720 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-24 12:15:38.382  5720  5720 D PanProfile: Bluetooth service disconnected
11-24 12:15:38.383  5894  5894 D BluetoothMapAppObserver: deinitObservers()
11-24 12:15:38.383  5894  5894 D BluetoothMapAppObserver: removeReceiver()
11-24 12:15:38.384  3145  3145 D BluetoothMap: Proxy object disconnected
11-24 12:15:38.384  3145  3145 D MapProfile: Bluetooth service disconnected
11-24 12:15:38.384  5894  5894 V BluetoothAdapterState: isTurningOff()=true
11-24 12:15:38.384  5894  5894 V BluetoothAdapterState: isTurningOn()=false
11-24 12:15:38.384  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:15:38.384  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:15:38.384  5894  5894 D SapService: Received stop request...Stopping profile...
11-24 12:15:38.384  5720  5720 D BluetoothMap: Proxy object disconnected
11-24 12:15:38.385  5894  5894 V SapService: stop()
11-24 12:15:38.385  5720  5720 D MapProfile: Bluetooth service disconnected
,11-24 12:15:38.387  5894  5894 V BluetoothAdapterState: isTurningOff()=true
,11-24 12:15:38.387  5894  5894 V BluetoothAdapterState: isTurningOn()=false
11-24 12:15:38.388  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:15:38.388  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:15:38.388  5894  5910 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-24 12:15:38.388  5894  5917 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 12:15:38.388  5894  5894 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-24 12:15:38.388  5894  5917 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 12:15:38.388  5894  5894 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,11-24 12:15:38.388  5894  5917 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 12:15:38.388  5894  5910 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-24 12:15:38.388  5894  5917 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 12:15:38.388  5894  5917 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-24 12:15:38.388  5894  5917 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-24 12:15:38.388  5894  5894 V BluetoothAdapterState: isTurningOff()=true
11-24 12:15:38.388  5894  5894 V BluetoothAdapterState: isTurningOn()=false
11-24 12:15:38.388  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:15:38.388  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:15:38.388  5894  5894 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-24 12:15:38.389  5894  5910 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,11-24 12:15:38.389  5894  5894 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-24 12:15:38.390  5894  5894 V BluetoothAdapterState: isTurningOff()=true
11-24 12:15:38.390  5894  5894 V BluetoothAdapterState: isTurningOn()=false
11-24 12:15:38.390  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:15:38.390  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:15:38.390  5894  5894 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-24 12:15:38.390  5894  5894 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-24 12:15:38.394  5894  5894 D BluetoothMapService: MAP Service closeService in
11-24 12:15:38.394  5894  5894 V BluetoothAdapterState: isTurningOff()=true
11-24 12:15:38.394  5894  5894 V BluetoothAdapterState: isTurningOn()=false
,11-24 12:15:38.394  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:15:38.394  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:15:38.394  5894  5894 D BluetoothMapService: cleanup()
11-24 12:15:38.394  5894  5894 D BluetoothMapService: MAP Service closeService in
11-24 12:15:38.395  5894  5894 V BluetoothAdapterState: isTurningOff()=true
11-24 12:15:38.395  5894  5894 V BluetoothAdapterState: isTurningOn()=false
11-24 12:15:38.395  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:15:38.395  5894  5894 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:15:38.395  5894  5906 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-24 12:15:38.395  5894  5906 D BluetoothAdapterProperties: Setting state to 15
11-24 12:15:38.395  5894  5906 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-24 12:15:38.395  5894  5906 I BluetoothAdapterState: Entering BleOnState
11-24 12:15:38.395   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 12:15:38.396  3145  3156 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-24 12:15:38.396   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-24 12:15:38.398  5720  5731 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 12:15:38.398  5720  5733 D BluetoothMap: onBluetoothStateChange: up=false
11-24 12:15:38.398  5720  5731 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-24 12:15:38.399  3145  4009 D BluetoothPan: onBluetoothStateChange on: false
11-24 12:15:38.399  3145  5856 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 12:15:38.400  5720  5733 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 12:15:38.401  5720  5731 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 12:15:38.401   925   942 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 12:15:38.401  3145  4009 D BluetoothMap: onBluetoothStateChange: up=false
,11-24 12:15:38.402  3145  5856 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 12:15:38.403  3826  4149 D BluetoothHeadset: onBluetoothStateChange: up=false
11-24 12:15:38.403  5720  5733 D BluetoothPan: onBluetoothStateChange on: false
11-24 12:15:38.404  3145  3158 D BluetoothPbap: onBluetoothStateChange: up=false
11-24 12:15:38.404   925   942 D BluetoothA2dp: onBluetoothStateChange: up=false
11-24 12:15:38.405  5894  5906 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-24 12:15:38.405  5894  5906 D BluetoothAdapterProperties: Setting state to 16
11-24 12:15:38.405  5894  5906 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-24 12:15:38.405  5894  5906 D BluetoothAdapterProperties: onBleDisable
11-24 12:15:38.406  5894  5906 I BluetoothAdapterState: Entering PendingCommandState
11-24 12:15:38.406  5894  5907 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-24 12:15:38.408  5720  5720 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-24 12:15:38.408  5894  5917 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-24 12:15:38.408  5894  5917 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-24 12:15:38.409  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 12:15:38.411  5894  5910 D BluetoothAdapterProperties: Scan Mode:20
,11-24 12:15:38.414  5664  5664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-24 12:15:38.415  3596  3596 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 12:15:38.415  5720  5720 D DockEventReceiver: finishStartingService: stopping service
,11-24 12:15:38.625  5894  5910 I bt_hci  : shut_down
,11-24 12:15:38.636  5894  5914 D bt_hwcfg: hw_epilog_process
,11-24 12:15:38.636  5894  5914 I bt_vendor: low_power_mode_cb
,11-24 12:15:38.639  5894  5914 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-24 12:15:38.640  5894  5914 I bt_vendor: epilog_cb
,11-24 12:15:38.640  5894  5914 I bt_hci  : epilog_finished_callback
,11-24 12:15:38.646  5894  5910 I bt_hci_h4: hal_close
,11-24 12:15:38.647  5894  5910 I bt_userial_vendor: device fd = 54 close
,11-24 12:15:38.771  5894  5907 D bt_stack_manager: event_shut_down_stack finished.
,11-24 12:15:38.771  5894  5906 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-24 12:15:38.776  5894  5894 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-24 12:15:38.776  5894  5906 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-24 12:15:38.776  5894  5894 D BtGatt.GattService: Received stop request...Stopping profile...
11-24 12:15:38.777  5894  5894 D BtGatt.GattService: stop()
11-24 12:15:38.777  5894  5894 D BtGatt.AdvertiseManager: advertise clients cleared
,11-24 12:15:38.781  5894  5894 V BluetoothAdapterState: isTurningOff()=false
,11-24 12:15:38.781  5894  5894 V BluetoothAdapterState: isTurningOn()=false
11-24 12:15:38.781  5894  5894 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 12:15:38.781  5894  5894 V BluetoothAdapterState: isBleTurningOff()=true
,11-24 12:15:38.782  5894  5906 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-24 12:15:38.782  5894  5906 D BluetoothAdapterProperties: Setting state to 10
,11-24 12:15:38.782  5894  5906 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-24 12:15:38.783  5894  5906 I BluetoothAdapterState: Entering OffState
11-24 12:15:38.785   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-24 12:15:38.795  5894  5894 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-24 12:15:38.796  5894  5894 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-24 12:15:38.796  5894  5894 I BluetoothServiceJni: cleanupNative: return from cleanup
11-24 12:15:38.798  5894  5907 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-24 12:15:38.803  5894  5894 I art     : System.exit called, status: 0
,11-24 12:15:38.803  5894  5894 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-24 12:15:38.848   925  3170 I ActivityManager: Process com.android.bluetooth (pid 5894) has died
,11-24 12:15:39.233   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:15:40.234   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:15:41.235   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:15:42.236   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:15:43.237   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:15:43.324  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 12:15:43.324  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-24 12:15:43.330  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 12:15:43.330  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@7ab56ac removed from the list
,11-24 12:15:43.331  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:15:43.332  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 12:15:43.333  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8cabf7b added. We now have 4 listener(s)
11-24 12:15:43.333  5664  5711 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 12:15:43.334  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:15:43.334  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8cabf7b removed from the list
11-24 12:15:43.334  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 12:15:43.336  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 12:15:43.336  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8cd3198 added. We now have 4 listener(s)
11-24 12:15:43.336  5664  5711 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 12:15:44.237   591   591 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-24 12:15:48.346  5664  5711 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 12:15:48.382   925   942 I ActivityManager: Start proc 5949:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-24 12:15:48.480  5949  5949 D AdapterServiceConfig: Adding HeadsetService
,11-24 12:15:48.481  5949  5949 D AdapterServiceConfig: Adding A2dpService
11-24 12:15:48.481  5949  5949 D AdapterServiceConfig: Adding HidService
,11-24 12:15:48.481  5949  5949 D AdapterServiceConfig: Adding HealthService
11-24 12:15:48.481  5949  5949 D AdapterServiceConfig: Adding PanService
11-24 12:15:48.481  5949  5949 D AdapterServiceConfig: Adding GattService
,11-24 12:15:48.481  5949  5949 D AdapterServiceConfig: Adding BluetoothMapService
11-24 12:15:48.482  5949  5949 D AdapterServiceConfig: Adding SapService
,11-24 12:15:48.492   925   942 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e775fd5:true
11-24 12:15:48.492  5949  5949 D BluetoothAdapterState: make() - Creating AdapterState
,11-24 12:15:48.495  5949  5949 I bt_bluedroid: init
,11-24 12:15:48.495  5949  5961 I BluetoothAdapterState: Entering OffState
,11-24 12:15:48.498  5949  5962 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-24 12:15:48.498  5949  5962 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-24 12:15:48.498  5949  5962 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-24 12:15:48.498  5949  5962 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-24 12:15:48.499  5949  5949 I bt_bluedroid: get_profile_interface socket
,11-24 12:15:48.500  5949  5965 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-24 12:15:48.501  5949  5949 I bt_bluedroid: get_profile_interface sdp
11-24 12:15:48.502  5949  5965 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 12:15:48.505  5949  5960 I bt_bluedroid: config_hci_snoop_log
,11-24 12:15:48.506   925   942 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
11-24 12:15:48.510  5949  5961 D BluetoothAdapterState: Current state: OFF, message: 0
11-24 12:15:48.510  5949  5961 D BluetoothAdapterProperties: Setting state to 14
11-24 12:15:48.510  5949  5961 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-24 12:15:48.512  5949  5961 D BluetoothBondStateMachine: make
,11-24 12:15:48.514  5949  5966 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-24 12:15:48.516  5949  5961 I BluetoothAdapterState: Entering PendingCommandState
,11-24 12:15:48.517  5949  5949 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-24 12:15:48.520  5949  5949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
11-24 12:15:48.520  5949  5949 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-24 12:15:48.521  5949  5949 D BtGatt.GattService: Received start request. Starting profile...
,11-24 12:15:48.521  5949  5949 D BtGatt.GattService: start()
11-24 12:15:48.521  5949  5949 I bt_bluedroid: get_profile_interface gatt
11-24 12:15:48.522  5949  5949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
11-24 12:15:48.522  5949  5949 D BtGatt.AdvertiseManager: advertise manager created
,11-24 12:15:48.529  5949  5949 V BluetoothAdapterState: isTurningOff()=false
,11-24 12:15:48.529  5949  5949 V BluetoothAdapterState: isTurningOn()=false
11-24 12:15:48.529  5949  5949 V BluetoothAdapterState: isBleTurningOn()=true
11-24 12:15:48.529  5949  5949 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:15:48.529  5949  5961 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-24 12:15:48.530  5949  5961 I bt_bluedroid: bt_bluedroid
11-24 12:15:48.530  5949  5962 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-24 12:15:48.531  5949  5962 I bt_hci  : start_up
,11-24 12:15:48.535  5949  5962 I bt_vendor: alloc value 0xf3e11871
11-24 12:15:48.535  5949  5962 I bt_vendor: init
11-24 12:15:48.535  5949  5962 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-24 12:15:48.535  5949  5962 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-24 12:15:48.645  5949  5962 D bt_hci  : start_up starting async portion
11-24 12:15:48.645  5949  5969 I bt_hci  : event_finish_startup
,11-24 12:15:48.645  5949  5969 I bt_hci_h4: hal_open
11-24 12:15:48.645  5949  5969 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-24 12:15:48.641  5970  5970 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 12:15:48.648  5949  5969 I bt_userial_vendor: device fd = 54 open
,11-24 12:15:48.662  5949  5969 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-24 12:15:48.665  5949  5969 D bt_hwcfg: Chipset BCM4358A3
,11-24 12:15:48.665  5949  5969 D bt_hwcfg: Target name = [BCM4358A3]
11-24 12:15:48.665  5949  5969 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-24 12:15:49.189  5949  5969 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-24 12:15:49.190  5949  5969 D bt_hwcfg: Settlement delay -- 100 ms
11-24 12:15:49.190  5949  5969 I bt_hwcfg: Setting fw settlement delay to 100 
,11-24 12:15:49.324  5949  5969 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-24 12:15:49.325  5949  5969 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
11-24 12:15:49.326  5949  5969 I bt_hwcfg: vendor lib fwcfg completed
11-24 12:15:49.327  5949  5969 I bt_vendor: firmware callback
11-24 12:15:49.327  5949  5969 I bt_hci  : firmware_config_callback
,11-24 12:15:49.336  5949  5972 I bt_btu  : btu_task pending for preload complete event
11-24 12:15:49.336  5949  5972 I bt_btu_task: Bluetooth chip preload is complete
,11-24 12:15:49.336  5949  5972 I bt_btu  : btu_task received preload complete event
,11-24 12:15:49.344  5949  5972 I         : BTE_InitTraceLevels -- TRC_HCI
,11-24 12:15:49.344  5949  5972 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-24 12:15:49.344  5949  5972 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-24 12:15:49.344  5949  5972 I         : BTE_InitTraceLevels -- TRC_AVDT
11-24 12:15:49.344  5949  5972 I         : BTE_InitTraceLevels -- TRC_AVRC
11-24 12:15:49.344  5949  5972 I         : BTE_InitTraceLevels -- TRC_A2D
,11-24 12:15:49.344  5949  5972 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-24 12:15:49.344  5949  5972 I         : BTE_InitTraceLevels -- TRC_BTM
,11-24 12:15:49.345  5949  5972 I         : BTE_InitTraceLevels -- TRC_GAP
,11-24 12:15:49.345  5949  5972 I         : BTE_InitTraceLevels -- TRC_PAN
11-24 12:15:49.345  5949  5972 I         : BTE_InitTraceLevels -- TRC_SDP
11-24 12:15:49.345  5949  5972 I         : BTE_InitTraceLevels -- TRC_GATT
11-24 12:15:49.345  5949  5972 I         : BTE_InitTraceLevels -- TRC_SMP
11-24 12:15:49.345  5949  5972 I         : BTE_InitTraceLevels -- TRC_BTAPP
,11-24 12:15:49.345  5949  5972 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-24 12:15:49.439  5949  5972 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3d8f549
11-24 12:15:49.439  5949  5972 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3d8f549 
,11-24 12:15:49.459  5949  5965 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-24 12:15:49.462  5949  5965 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-24 12:15:49.462  5949  5965 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-24 12:15:49.465  5949  5965 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-24 12:15:49.468  5949  5965 D BluetoothAdapterProperties: Scan Mode:20
,11-24 12:15:49.468  5949  5965 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-24 12:15:49.469  5949  5965 D bt_hci  : do_postload posting postload work item
,11-24 12:15:49.469  5949  5969 I bt_hci  : event_postload
11-24 12:15:49.469  5949  5969 I bt_vendor: sco_config_cb
,11-24 12:15:49.469  5949  5969 I bt_hci  : sco_config_callback postload finished.
,11-24 12:15:49.473  5949  5965 D bt_bte_conf: Device ID record 1 : primary
11-24 12:15:49.473  5949  5965 D bt_bte_conf:   vendorId            = 000f
11-24 12:15:49.473  5949  5965 D bt_bte_conf:   vendorIdSource      = 0001
11-24 12:15:49.473  5949  5965 D bt_bte_conf:   product             = 1200
,11-24 12:15:49.473  5949  5965 D bt_bte_conf:   version             = 1436
11-24 12:15:49.474  5949  5965 D bt_bte_conf:   clientExecutableURL = 
11-24 12:15:49.474  5949  5965 D bt_bte_conf:   serviceDescription  = 
11-24 12:15:49.474  5949  5965 D bt_bte_conf:   documentationURL    = 
11-24 12:15:49.474  5949  5965 D bt_bte_conf: bte_load_did_conf no section named DID2.
,11-24 12:15:49.474  5949  5962 D bt_stack_manager: event_start_up_stack finished
11-24 12:15:49.475  5949  5961 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-24 12:15:49.476  5949  5961 D BluetoothAdapterProperties: Setting state to 15
11-24 12:15:49.476  5949  5961 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-24 12:15:49.478  5949  5961 I BluetoothAdapterState: Entering BleOnState
,11-24 12:15:49.479  5949  5969 I bt_vendor: low_power_mode_cb
,11-24 12:15:49.486  5949  5961 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-24 12:15:49.486  5949  5961 D BluetoothAdapterProperties: Setting state to 11
11-24 12:15:49.486  5949  5961 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-24 12:15:49.492  5949  5949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
,11-24 12:15:49.493  5949  5949 D HeadsetService: Received start request. Starting profile...
11-24 12:15:49.496  5949  5949 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-24 12:15:49.497  5949  5949 D HeadsetStateMachine: make
,11-24 12:15:49.509  5949  5961 I BluetoothAdapterState: Entering PendingCommandState
,11-24 12:15:49.510  5949  5949 D HeadsetStateMachine: max_hf_connections = 1
,11-24 12:15:49.510  5949  5949 I bt_bluedroid: get_profile_interface handsfree
,11-24 12:15:49.510  5949  5965 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,11-24 12:15:49.511  5949  5965 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-24 12:15:49.516  5949  5949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
,11-24 12:15:49.516  5949  5949 D A2dpService: Received start request. Starting profile...
,11-24 12:15:49.517  5949  5949 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-24 12:15:49.518  5949  5949 I bt_bluedroid: get_profile_interface avrcp
,11-24 12:15:49.525  5949  5949 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-24 12:15:49.525  5949  5949 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-24 12:15:49.525  5949  5949 D A2dpStateMachine: make
11-24 12:15:49.526  5949  5949 I bt_bluedroid: get_profile_interface a2dp
,11-24 12:15:49.527  5949  5965 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-24 12:15:49.528  5949  5980 D A2dpStateMachine: Enter Disconnected: -2
11-24 12:15:49.528  5949  5949 I BluetoothHidServiceJni: classInitNative: succeeds
11-24 12:15:49.529  5949  5949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
11-24 12:15:49.530  5949  5949 D HidService: Received start request. Starting profile...
11-24 12:15:49.530  5949  5949 I bt_bluedroid: get_profile_interface hidhost
11-24 12:15:49.530  5949  5949 D HidService: setHidService(): set to: null
11-24 12:15:49.530  5949  5965 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3d7056d
11-24 12:15:49.530  5949  5949 I BluetoothHealthServiceJni: classInitNative: succeeds
11-24 12:15:49.531  5949  5965 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-24 12:15:49.531  5949  5949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
11-24 12:15:49.531  5949  5949 D HealthService: Received start request. Starting profile...
,11-24 12:15:49.533  5949  5949 I bt_bluedroid: get_profile_interface health
11-24 12:15:49.533  5949  5949 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-24 12:15:49.534  5949  5949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
,11-24 12:15:49.535  5949  5949 D PanService: Received start request. Starting profile...
11-24 12:15:49.535  5949  5949 D BluetoothPanServiceJni: initializeNative(L110): pan
11-24 12:15:49.535  5949  5949 I bt_bluedroid: get_profile_interface pan
11-24 12:15:49.536  5949  5965 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-24 12:15:49.540  5949  5949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
,11-24 12:15:49.540  5949  5949 D BluetoothMapService: Received start request. Starting profile...
11-24 12:15:49.541  5949  5949 D BluetoothMapService: start()
11-24 12:15:49.542  3596  3596 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-24 12:15:49.543  5949  5949 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-24 12:15:49.544  5949  5949 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-24 12:15:49.544  5949  5949 D BluetoothMapAppObserver: createReceiver()
,11-24 12:15:49.545  5949  5949 D BluetoothMapAppObserver: initObservers()
11-24 12:15:49.545  5949  5949 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-24 12:15:49.550  5949  5949 V SapService: SapBinder()
11-24 12:15:49.550  5949  5949 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
,11-24 12:15:49.551  5949  5949 D SapService: Received start request. Starting profile...
11-24 12:15:49.551  5949  5949 V SapService: start()
,11-24 12:15:49.552  5949  5949 V BluetoothAdapterState: isTurningOff()=false
,11-24 12:15:49.552  5949  5949 V BluetoothAdapterState: isTurningOn()=true
11-24 12:15:49.552  5949  5949 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:15:49.552  5949  5949 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:15:49.552  5949  5949 V BluetoothAdapterState: isTurningOff()=false
11-24 12:15:49.552  5949  5949 V BluetoothAdapterState: isTurningOn()=true
11-24 12:15:49.552  5949  5949 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:15:49.552  5949  5949 V BluetoothAdapterState: isBleTurningOff()=false
,11-24 12:15:49.552  5949  5949 V BluetoothAdapterState: isTurningOff()=false
11-24 12:15:49.552  5949  5977 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-24 12:15:49.553  5949  5949 V BluetoothAdapterState: isTurningOn()=true
11-24 12:15:49.553  5949  5949 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:15:49.553  5949  5949 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:15:49.553  5949  5949 V BluetoothAdapterState: isTurningOff()=false
11-24 12:15:49.553  5949  5949 V BluetoothAdapterState: isTurningOn()=true
11-24 12:15:49.553  5949  5949 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 12:15:49.553  5949  5949 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:15:49.553  5949  5949 V BluetoothAdapterState: isTurningOff()=false
11-24 12:15:49.553  5949  5949 V BluetoothAdapterState: isTurningOn()=true
11-24 12:15:49.553  5949  5949 V BluetoothAdapterState: isBleTurningOn()=false
,11-24 12:15:49.553  5949  5949 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:15:49.553  5949  5949 V BluetoothAdapterState: isTurningOff()=false
11-24 12:15:49.553  5949  5949 V BluetoothAdapterState: isTurningOn()=true
11-24 12:15:49.553  5949  5949 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:15:49.553  5949  5949 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:15:49.554  5949  5949 V BluetoothAdapterState: isTurningOff()=false
11-24 12:15:49.554  5949  5949 V BluetoothAdapterState: isTurningOn()=true
11-24 12:15:49.554  5949  5949 V BluetoothAdapterState: isBleTurningOn()=false
11-24 12:15:49.554  5949  5949 V BluetoothAdapterState: isBleTurningOff()=false
11-24 12:15:49.554  5949  5961 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-24 12:15:49.554  5949  5961 D BluetoothAdapterProperties: ScanMode =  20
11-24 12:15:49.554  5949  5961 D BluetoothAdapterProperties: State =  11
11-24 12:15:49.555  5949  5965 D BluetoothAdapterProperties: Scan Mode:21
11-24 12:15:49.555  5949  5961 D BluetoothAdapterProperties: Setting state to 12
,11-24 12:15:49.555  5949  5961 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-24 12:15:49.555  5949  5965 D BluetoothAdapterProperties: Discoverable Timeout:120
11-24 12:15:49.556   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 12:15:49.556  3145  5856 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-24 12:15:49.556  5949  5961 I BluetoothAdapterState: Entering OnState
11-24 12:15:49.559  3145  3145 D BluetoothInputDevice: Proxy object connected
11-24 12:15:49.559  3145  3145 D HidProfile: Bluetooth service connected
11-24 12:15:49.559   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 12:15:49.560  5720  5731 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-24 12:15:49.560  5720  5733 D BluetoothMap: onBluetoothStateChange: up=true
,11-24 12:15:49.562  5720  5731 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-24 12:15:49.564  3145  4009 D BluetoothPan: onBluetoothStateChange on: true
11-24 12:15:49.566  3145  3158 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 12:15:49.566  3145  3145 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 12:15:49.566  3145  3145 D PanProfile: Bluetooth service connected
11-24 12:15:49.568  5720  5733 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 12:15:49.568  5949  5949 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-24 12:15:49.568  3145  3145 D BluetoothA2dp: Proxy object connected
,11-24 12:15:49.569  5949  5949 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-24 12:15:49.569  5720  5731 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 12:15:49.569  5949  5949 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 12:15:49.570   925   942 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 12:15:49.570  5949  5949 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 12:15:49.571  3145  5856 D BluetoothMap: onBluetoothStateChange: up=true
,11-24 12:15:49.571  5949  5949 D ObexServerSockets: Succeed to create listening sockets 
11-24 12:15:49.572  5949  5949 D ObexServerSockets0: startAccept()
11-24 12:15:49.572  5949  5949 D ObexServerSockets0: prepareForNewConnect()
11-24 12:15:49.572  3145  5856 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 12:15:49.572  3145  3145 D BluetoothMap: Proxy object connected
11-24 12:15:49.572  3145  3145 D MapProfile: Bluetooth service connected
,11-24 12:15:49.572  3145  3145 D BluetoothMap: getConnectedDevices()
11-24 12:15:49.572  5720  5720 D BluetoothMap: Proxy object connected
11-24 12:15:49.572  5720  5720 D MapProfile: Bluetooth service connected
11-24 12:15:49.573  5720  5720 D BluetoothMap: getConnectedDevices()
11-24 12:15:49.573  3826  4022 D BluetoothHeadset: onBluetoothStateChange: up=true
11-24 12:15:49.573  5949  5949 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-24 12:15:49.573  5949  5949 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-24 12:15:49.575  5720  5720 D BluetoothInputDevice: Proxy object connected
,11-24 12:15:49.575  5720  5720 D HidProfile: Bluetooth service connected
11-24 12:15:49.576  5949  5987 D ObexServerSockets0: Accepting socket connection...
,11-24 12:15:49.577  5720  5733 D BluetoothPan: onBluetoothStateChange on: true
11-24 12:15:49.578  5949  5986 D ObexServerSockets0: Accepting socket connection...
11-24 12:15:49.577  5720  5720 D BluetoothA2dp: Proxy object connected
,11-24 12:15:49.579  3145  4009 D BluetoothPbap: onBluetoothStateChange: up=true
11-24 12:15:49.580   925   942 D BluetoothA2dp: onBluetoothStateChange: up=true
11-24 12:15:49.581   925   925 D BluetoothA2dp: Proxy object connected
11-24 12:15:49.582  5949  5949 D BluetoothMapService: onReceive
,11-24 12:15:49.582  5949  5949 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-24 12:15:49.582  5949  5949 D BluetoothMapService: STATE_ON
11-24 12:15:49.583  5720  5720 D BluetoothPan: BluetoothPAN Proxy object connected
11-24 12:15:49.583  5720  5720 D PanProfile: Bluetooth service connected
11-24 12:15:49.584   925   925 I Telecom : BluetoothPhoneService: queryPhoneState
,11-24 12:15:49.585  5949  5989 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-24 12:15:49.587  5949  5989 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-24 12:15:49.587  5949  5989 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-24 12:15:49.588  5720  5720 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-24 12:15:49.593  3596  3596 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-24 12:15:49.594  5720  5720 D DockEventReceiver: finishStartingService: stopping service
,11-24 12:15:49.604  5720  5720 D BluetoothPbap: Proxy object connected
,11-24 12:15:49.604  5720  5720 D PbapServerProfile: Bluetooth service connected
11-24 12:15:49.604  3145  3145 D BluetoothPbap: Proxy object connected
11-24 12:15:49.604  3145  3145 D PbapServerProfile: Bluetooth service connected
,11-24 12:15:49.611  5949  5993 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 12:15:49.619  5949  5949 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-24 12:15:49.619  5949  5949 D ObexServerSockets0: prepareForNewConnect()
,11-24 12:15:49.624  5949  5997 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-24 12:15:49.625  5949  5997 I BtOppRfcommListener: Accept thread started.
,11-24 12:15:49.657   925   925 D BluetoothHeadset: Proxy object connected
11-24 12:15:49.658   925   925 D BluetoothHeadset: Proxy object connected
11-24 12:15:49.658  3826  3847 D BluetoothHeadset: Proxy object connected
11-24 12:15:49.658   925   925 D BluetoothHeadset: Proxy object connected
11-24 12:15:49.658  5720  5985 D BluetoothHeadset: Proxy object connected
11-24 12:15:49.659  3145  3156 D BluetoothHeadset: Proxy object connected
,11-24 12:15:49.659  3145  3145 D HeadsetProfile: Bluetooth service connected
11-24 12:15:49.660  5720  5720 D HeadsetProfile: Bluetooth service connected
11-24 12:15:49.660   925   942 D BluetoothHeadset: Proxy object connected
11-24 12:15:49.661  5720  5731 D BluetoothHeadset: Proxy object connected
,11-24 12:15:49.662  5720  5720 D HeadsetProfile: Bluetooth service connected
,11-24 12:15:49.671   925   942 D BluetoothHeadset: Proxy object connected
,11-24 12:15:49.673  3145  3158 D BluetoothHeadset: Proxy object connected
11-24 12:15:49.673  3145  3145 D HeadsetProfile: Bluetooth service connected
11-24 12:15:49.673  3826  3845 D BluetoothHeadset: Proxy object connected
,11-24 12:15:53.364  5664  5711 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 12:15:53.364  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:15:53.364  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:15:53.364  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-24 12:15:53.364  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 12:15:53.364  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 12:15:53.364  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 12:15:53.364  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 12:15:53.364  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 12:15:53.369  5664  5711 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 12:15:53.370  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-24 12:15:53.370  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@8cd3198 removed from the list
,11-24 12:15:53.370  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:15:53.372  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 12:15:53.372  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@80a9df1 added. We now have 4 listener(s)
,11-24 12:15:53.372  5664  5711 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 12:15:53.376   925  3917 D WifiService: setWifiEnabled: false pid=5664, uid=10077
11-24 12:15:53.376   925  3917 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 12:15:58.387  5664  5711 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-24 12:15:58.389   925  3170 D WifiService: setWifiEnabled: true pid=5664, uid=10077
,11-24 12:15:58.389   925  3170 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-24 12:15:58.397   506   919 D SoftapController: Softap fwReload - Ok
,11-24 12:15:58.402   506   919 D CommandListener: Setting iface cfg
,11-24 12:15:58.402   506   919 D CommandListener: Trying to bring down wlan0
11-24 12:15:58.404   506   919 D CommandListener: Clearing all IP addresses on wlan0
,11-24 12:15:58.409   925  2989 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-24 12:15:59.076   925  2989 D wifi    : set interface wlan0 flags (UP)
11-24 12:15:59.077   925  2989 I WifiHAL : Initializing wifi
11-24 12:15:59.077   925  2989 I WifiHAL : Creating socket
,11-24 12:15:59.084   925  2989 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-24 12:15:59.084   925  2989 D wifi    : Did set static halHandle = 0x7f68784080
11-24 12:15:59.084   925  2989 D wifi    : halHandle = 0x7f68784080, mVM = 0x7f84e0d140, mCls = 0x10177e
11-24 12:15:59.085   925  2989 D wifi    : array field set
11-24 12:15:59.085   925  2989 I WifiNative-HAL: interface[0] = wlan0
11-24 12:15:59.087   925  6002 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547213557888
11-24 12:15:59.087   925  6002 D wifi    : waitForHalEvents called, vm = 0x7f84e0d140, obj = 0x10177e, env = 0x7f6aeea9c0
11-24 12:15:59.087   925   942 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-24 12:15:59.148  6003  6003 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-24 12:15:59.169  6003  6003 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-24 12:15:59.188   925  2989 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
11-24 12:15:59.189   925  2989 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-24 12:15:59.197  6003  6003 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-24 12:15:59.197  6003  6003 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-24 12:15:59.238   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:16:00.206   925  2989 D WifiConfigStore: Loading config and enabling all networks 
,11-24 12:16:00.222   925  2989 D WifiConfigStore: loaded 0 passpoint configs
11-24 12:16:00.223   925  2989 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
11-24 12:16:00.223   925  2989 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-24 12:16:00.225   925  2989 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-24 12:16:00.227   925  2989 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-24 12:16:00.227   925  2989 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,11-24 12:16:00.227   925  2989 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-24 12:16:00.227   925  2989 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-24 12:16:00.232   925  2989 D WifiNative-HAL: Setting external_sim to 1
,11-24 12:16:00.232  5040  5040 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-24 12:16:00.232   925  2989 D wifi    : setting dfs flag to true, 0x7f6cb12520
11-24 12:16:00.233   925  2989 D WifiStateMachine: Setting OUI to DA-A1-19
11-24 12:16:00.234   925  2989 D wifi    : setting scan oui 0x7f6cb12520
,11-24 12:16:00.234   925  2989 D WifiHAL : Sending mac address OUI
,11-24 12:16:00.238   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:16:00.239   925  2989 E native  : do suspend false
,11-24 12:16:00.250   925  2989 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-24 12:16:00.250   506   919 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-24 12:16:00.251   506   919 D CommandListener: Setting iface cfg
11-24 12:16:00.252   925   925 D RttService: SCAN_AVAILABLE : 3
11-24 12:16:00.252   925  3097 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-24 12:16:00.257   925  2988 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '161 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 161 Failed to set address (No such device)'
,11-24 12:16:00.257   925  2988 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-24 12:16:00.269   925  2988 D WifiNative-HAL: p2pGetDeviceAddress
,11-24 12:16:00.270   925  2988 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-24 12:16:00.277   925   940 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=165656 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=20 mControllerEnergyUsed=76 }
,11-24 12:16:01.240   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:16:02.241   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:16:03.242   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:16:03.350  6003  6003 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 12:16:03.362  6003  6003 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 12:16:03.368  6003  6003 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 12:16:03.373  6003  6003 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-24 12:16:03.401   925  2989 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-24 12:16:03.402   925  2989 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-24 12:16:03.402   925  2989 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-24 12:16:03.402  5664  5711 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-24 12:16:03.402  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-24 12:16:03.402  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-24 12:16:03.402  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-24 12:16:03.402  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-24 12:16:03.402  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-24 12:16:03.402  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-24 12:16:03.402  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-24 12:16:03.402  5664  5711 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-24 12:16:03.407  5664  5711 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-24 12:16:03.408  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:16:03.408  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@80a9df1 removed from the list
11-24 12:16:03.408  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 12:16:03.412  5664  5711 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-24 12:16:03.412  5664  5711 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-24 12:16:03.414   925  2989 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
11-24 12:16:03.414  5664  5711 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@f77040a Bundle[{}]
11-24 12:16:03.415  5664  5711 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-24 12:16:03.415  5664  5711 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-24 12:16:03.415  5664  5711 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-24 12:16:03.416  5664  5711 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-24 12:16:03.416  5664  5711 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-24 12:16:03.416  5664  5711 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-24 12:16:03.423  5664  5711 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,11-24 12:16:03.424  5664  5711 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-24 12:16:03.424  5664  5711 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 170)
,11-24 12:16:03.426  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 12:16:03.426  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20addd6 added. We now have 3 listener(s)
,11-24 12:16:03.428  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-24 12:16:03.428  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 12:16:03.428  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 12:16:03.428  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 12:16:03.428  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7bbd857 added. We now have 4 listener(s)
11-24 12:16:03.428  5664  5711 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 12:16:03.429  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 12:16:03.430  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 12:16:03.430  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12fcf44 added. We now have 4 listener(s)
,11-24 12:16:03.432  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 12:16:03.432  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 12:16:03.432  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 12:16:03.432  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 12:16:03.432  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@51a282d added. We now have 5 listener(s)
11-24 12:16:03.432  5664  5711 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-24 12:16:03.433  5664  5711 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:16:03.433  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:16:03.433  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:16:03.433  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:16:03.433  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:16:03.433  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 12:16:03.433  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@20addd6 removed from the list
11-24 12:16:03.433  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:16:03.434  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7bbd857 removed from the list
11-24 12:16:03.434  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:16:03.434  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:16:03.434  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:16:03.436  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.436  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.436  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.436  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:16:03.436  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:16:03.436  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:16:03.436  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7bbd857 not in the list
11-24 12:16:03.436  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.437  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:16:03.438  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.438  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.438  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.438  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:16:03.438  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:16:03.438  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:16:03.438  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@51a282d removed from the list
,11-24 12:16:03.438  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:16:03.439  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:16:03.439  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 12:16:03.439  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@12fcf44 removed from the list
11-24 12:16:03.439  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-24 12:16:03.440  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42f0162 added. We now have 3 listener(s)
,11-24 12:16:03.441  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 12:16:03.441  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 12:16:03.441  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 12:16:03.441  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 12:16:03.441  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3ba2f3 added. We now have 4 listener(s)
11-24 12:16:03.441  5664  5711 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 12:16:03.442  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-24 12:16:03.443  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 12:16:03.443  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fc9bb0 added. We now have 4 listener(s)
,11-24 12:16:03.443  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 12:16:03.444  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 12:16:03.444  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 12:16:03.444  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 12:16:03.444  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1e1a29 added. We now have 5 listener(s)
11-24 12:16:03.444  5664  5711 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 12:16:03.444  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 12:16:03.444  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 12:16:03.444  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 12:16:03.444  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 12:16:03.444  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-24 12:16:03.445  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 12:16:03.447  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-24 12:16:03.447  5664  5711 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 12:16:03.447  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-24 12:16:03.449  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:16:03.449  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-24 12:16:03.449  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 12:16:03.449  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 12:16:03.450  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 12:16:03.451   925  2989 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
11-24 12:16:03.452  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.452  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 12:16:03.452  6003  6003 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-24 12:16:03.452  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 12:16:03.452  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 12:16:03.452  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 12:16:03.452  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.453  5664  5711 D BluetoothAdapter: STATE_ON
11-24 12:16:03.455  5949  5978 D BtGatt.GattService: registerClient() - UUID=461e5f8c-030c-4e10-8d15-cbbbf980ee7d
,11-24 12:16:03.455  5949  5965 D BtGatt.GattService: onClientRegistered() - UUID=461e5f8c-030c-4e10-8d15-cbbbf980ee7d, clientIf=5
11-24 12:16:03.456  5664  5675 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-24 12:16:03.457  5949  5960 D BtGatt.GattService: start scan with filters
,11-24 12:16:03.460  5949  5968 D BtGatt.ScanManager: handling starting scan
,11-24 12:16:03.460  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 12:16:03.460  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.460  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 12:16:03.460  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.460  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 12:16:03.460  5664  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-24 12:16:03.461  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.461  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 12:16:03.461  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 12:16:03.461  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.461  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.461  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.461  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-24 12:16:03.461  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 12:16:03.461  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.461  5949  5968 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@b2ca15f
11-24 12:16:03.463  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.463  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 12:16:03.463  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:16:03.463  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.463  5664  5711 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-24 12:16:03.463  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-24 12:16:03.463  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-24 12:16:03.463  5664  5711 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 12:16:03.463  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 12:16:03.463  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 12:16:03.463  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-24 12:16:03.463  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-24 12:16:03.466  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.466  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.466  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.466  5664  5664 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 12:16:03.466  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 12:16:03.466  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.466  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 12:16:03.466  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 12:16:03.466  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.467  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.467  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:16:03.467  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 12:16:03.467  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.467  5664  5711 D BluetoothAdapter: STATE_ON
11-24 12:16:03.467  5949  5960 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-24 12:16:03.468  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 12:16:03.468  5664  5711 D BluetoothAdapter: STATE_ON
11-24 12:16:03.468  5949  5959 D BtGatt.GattService: stopScan() - queue size =1
,11-24 12:16:03.469  5949  5978 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 12:16:03.469  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 12:16:03.470  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.470  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 12:16:03.470  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.470  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.470  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.470  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.470  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 12:16:03.470  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-24 12:16:03.470  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.470  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.470  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 12:16:03.470  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 12:16:03.470  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 12:16:03.471  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.471  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.471  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 12:16:03.472  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.472  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:16:03.472  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 12:16:03.472  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 12:16:03.472  5949  5965 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 12:16:03.472  5664  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 12:16:03.472  5949  5965 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:16:03.472  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.472  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 12:16:03.472  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 12:16:03.472  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.472  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.472  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.472  5664  5664 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 12:16:03.472  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.472  5949  5968 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 12:16:03.472  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.473  5664  5711 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:16:03.473  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:16:03.473  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:16:03.473  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:16:03.473  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:16:03.473  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 12:16:03.473  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@42f0162 removed from the list
11-24 12:16:03.473  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:16:03.473  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3ba2f3 removed from the list
11-24 12:16:03.473  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
,11-24 12:16:03.473  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.473  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.473  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.474  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.474  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.474  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.474  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.474  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.474  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:16:03.474  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:16:03.475  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:16:03.475  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e3ba2f3 not in the list
11-24 12:16:03.475  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.475  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:16:03.476  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.477  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.477  5949  5965 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 12:16:03.477  5949  5965 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:16:03.477  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.477  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:16:03.477  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:16:03.477  5949  5968 D BtGatt.ScanManager: Starting BLE batch scan
11-24 12:16:03.477  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:16:03.477  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e1e1a29 removed from the list
,11-24 12:16:03.477  5949  5968 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-24 12:16:03.477  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:16:03.478  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:16:03.478  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 12:16:03.478  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@5fc9bb0 removed from the list
11-24 12:16:03.478  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 12:16:03.478  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8fb5aba added. We now have 3 listener(s)
11-24 12:16:03.479  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 12:16:03.479  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 12:16:03.479  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 12:16:03.479  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-24 12:16:03.479  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e867d6b added. We now have 4 listener(s)
11-24 12:16:03.479  5664  5711 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 12:16:03.480  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 12:16:03.480  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 12:16:03.480  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53c30c8 added. We now have 4 listener(s)
,11-24 12:16:03.481  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 12:16:03.481  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 12:16:03.481  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 12:16:03.481  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 12:16:03.481  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42de561 added. We now have 5 listener(s)
11-24 12:16:03.481  5664  5711 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 12:16:03.481  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 12:16:03.482  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 12:16:03.482  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 12:16:03.482  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 12:16:03.482  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 12:16:03.482  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-24 12:16:03.483  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-24 12:16:03.485  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 12:16:03.485  5664  5711 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 12:16:03.485  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-24 12:16:03.487  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:16:03.487  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-24 12:16:03.488  5949  5965 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 12:16:03.488  5949  5965 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:16:03.488  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-24 12:16:03.488  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 12:16:03.488  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 12:16:03.490  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:16:03.490  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 12:16:03.490  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 12:16:03.490  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-24 12:16:03.490  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 12:16:03.490  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.491  5664  5711 D BluetoothAdapter: STATE_ON
,11-24 12:16:03.492  5949  5965 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-24 12:16:03.492  5949  5965 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:16:03.492  5949  5959 D BtGatt.GattService: registerClient() - UUID=59998fd6-5aac-485d-9451-c53b4fc46f9c
,11-24 12:16:03.493  5949  5965 D BtGatt.GattService: onClientRegistered() - UUID=59998fd6-5aac-485d-9451-c53b4fc46f9c, clientIf=5
,11-24 12:16:03.494  5664  5811 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 12:16:03.494  5949  5978 D BtGatt.GattService: start scan with filters
11-24 12:16:03.494  5949  5968 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 12:16:03.497  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 12:16:03.497  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:16:03.497  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-24 12:16:03.497  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.497  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-24 12:16:03.497  5664  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 12:16:03.498  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.498  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 12:16:03.498  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 12:16:03.498  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.498  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.498  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.498  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.498  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 12:16:03.498  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.498  5949  5965 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 12:16:03.498  5949  5965 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:16:03.499  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.499  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 12:16:03.500  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.500  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.500  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 12:16:03.500  5664  5711 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-24 12:16:03.500  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.500  5664  5711 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:16:03.500  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 12:16:03.500  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:16:03.500  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:16:03.500  5664  5711 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 12:16:03.500  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 12:16:03.500  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:16:03.500  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 12:16:03.500  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8fb5aba removed from the list
11-24 12:16:03.500  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:16:03.500  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e867d6b removed from the list
11-24 12:16:03.500  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:16:03.500  5664  5711 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-24 12:16:03.500  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 12:16:03.501  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.501  5664  5711 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-24 12:16:03.501  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-24 12:16:03.501  5664  5711 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 12:16:03.501  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 12:16:03.501  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.501  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.501  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.501  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.502  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:16:03.502  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-24 12:16:03.502  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:16:03.502  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e867d6b not in the list
11-24 12:16:03.502  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.502  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.502  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.502  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.502  5664  5664 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 12:16:03.503  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 12:16:03.503  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.503  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 12:16:03.503  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 12:16:03.503  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.503  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.503  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.503  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 12:16:03.503  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.504  5664  5711 D BluetoothAdapter: STATE_ON
11-24 12:16:03.504  5949  5960 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 12:16:03.504  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 12:16:03.504  5949  5965 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 12:16:03.505  5949  5965 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:16:03.505  5664  5711 D BluetoothAdapter: STATE_ON
11-24 12:16:03.505  5949  5968 D BtGatt.ScanManager: stopping BLe Batch
,11-24 12:16:03.505  5949  5988 D BtGatt.GattService: stopScan() - queue size =0
11-24 12:16:03.505  5949  5978 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 12:16:03.506  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 12:16:03.506  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.506  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 12:16:03.506  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.506  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.506  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.506  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.506  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 12:16:03.506  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.506  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.506  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.506  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-24 12:16:03.506  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 12:16:03.507  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 12:16:03.508  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.508  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:16:03.508  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 12:16:03.508  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.508  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.508  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:16:03.509  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:16:03.509  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:16:03.509  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@42de561 removed from the list
11-24 12:16:03.509  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 12:16:03.509  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:16:03.509  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 12:16:03.509  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 12:16:03.509  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 12:16:03.509  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53c30c8 removed from the list
11-24 12:16:03.509  5664  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
,11-24 12:16:03.509  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.509  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 12:16:03.509  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 12:16:03.510  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.510  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-24 12:16:03.510  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.510  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 12:16:03.510  5664  5664 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 12:16:03.510  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21e8712 added. We now have 3 listener(s)
11-24 12:16:03.510  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.510  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.511  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 12:16:03.511  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 12:16:03.511  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-24 12:16:03.511  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 12:16:03.511  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e132ee3 added. We now have 4 listener(s)
11-24 12:16:03.511  5664  5711 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 12:16:03.511  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 12:16:03.511  5949  5965 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-24 12:16:03.511  5949  5965 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:16:03.511  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.511  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.512  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.512  5949  5968 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 12:16:03.512  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 12:16:03.512  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0650e0 added. We now have 4 listener(s)
,11-24 12:16:03.513  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 12:16:03.513  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 12:16:03.513  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 12:16:03.513  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 12:16:03.513  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@594df99 added. We now have 5 listener(s)
11-24 12:16:03.513  5664  5711 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 12:16:03.513  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 12:16:03.513  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-24 12:16:03.513  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-24 12:16:03.513  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-24 12:16:03.513  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-24 12:16:03.514  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-24 12:16:03.516  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-24 12:16:03.516  5664  5711 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-24 12:16:03.516  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-24 12:16:03.517  5949  5965 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 12:16:03.517  5949  5965 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:16:03.519  5949  5968 D BtGatt.ScanManager: handling starting scan
,11-24 12:16:03.519  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.519  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-24 12:16:03.521  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-24 12:16:03.521  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-24 12:16:03.521  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-24 12:16:03.524  5949  5965 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 12:16:03.524  5949  5965 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:16:03.524  5949  5968 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-24 12:16:03.525  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.525  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-24 12:16:03.525  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-24 12:16:03.525  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-24 12:16:03.525  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-24 12:16:03.525  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:16:03.526  5664  5711 D BluetoothAdapter: STATE_ON
,11-24 12:16:03.528  5949  5978 D BtGatt.GattService: registerClient() - UUID=f81f4f2e-c52d-420d-8d41-490b80da984f
,11-24 12:16:03.528  5949  5965 D BtGatt.GattService: onClientRegistered() - UUID=f81f4f2e-c52d-420d-8d41-490b80da984f, clientIf=5
,11-24 12:16:03.528  5664  5811 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-24 12:16:03.528  5949  5965 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-24 12:16:03.529  5949  5965 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:16:03.529  5949  5968 D BtGatt.ScanManager: Starting BLE batch scan
11-24 12:16:03.529  5949  5959 D BtGatt.GattService: start scan with filters
11-24 12:16:03.529  5949  5968 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 12:16:03.535  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-24 12:16:03.535  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.535  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-24 12:16:03.535  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.535  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-24 12:16:03.536  5664  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-24 12:16:03.536  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.536  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-24 12:16:03.536  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-24 12:16:03.536  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.536  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.536  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.536  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.536  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-24 12:16:03.536  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.537  5949  5965 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 12:16:03.537  5949  5965 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:16:03.538  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.538  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 12:16:03.538  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.538  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.538  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.539  5664  5711 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:16:03.539  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:16:03.540  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-24 12:16:03.540  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:16:03.540  5664  5711 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 12:16:03.540  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 12:16:03.540  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:16:03.540  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 12:16:03.540  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21e8712 removed from the list
11-24 12:16:03.540  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:16:03.540  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e132ee3 removed from the list
11-24 12:16:03.540  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:16:03.540  5664  5711 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 12:16:03.540  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 12:16:03.540  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:16:03.540  5664  5711 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-24 12:16:03.540  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-24 12:16:03.540  5664  5711 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-24 12:16:03.540  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-24 12:16:03.540  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.541  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.541  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.541  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.541  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.541  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:16:03.541  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.541  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:16:03.541  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:16:03.541  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:16:03.541  5664  5664 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-24 12:16:03.541  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@e132ee3 not in the list
11-24 12:16:03.541  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-24 12:16:03.541  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.541  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-24 12:16:03.541  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-24 12:16:03.541  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:16:03.541  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.542  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.542  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-24 12:16:03.542  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.542  5949  5965 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 12:16:03.542  5949  5965 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:16:03.542  5664  5711 D BluetoothAdapter: STATE_ON
11-24 12:16:03.542  5949  5959 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-24 12:16:03.542  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-24 12:16:03.543  5949  5968 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-24 12:16:03.543  5664  5711 D BluetoothAdapter: STATE_ON
11-24 12:16:03.544  5949  5978 D BtGatt.GattService: stopScan() - queue size =1
,11-24 12:16:03.544  5949  5960 D BtGatt.GattService: unregisterClient() - clientIf=5
11-24 12:16:03.544  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-24 12:16:03.544  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.544  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-24 12:16:03.544  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.544  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.545  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:16:03.545  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.545  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-24 12:16:03.545  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.545  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.545  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.545  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-24 12:16:03.545  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-24 12:16:03.545  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-24 12:16:03.545  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:16:03.546  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.546  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 12:16:03.546  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.546  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.546  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:16:03.546  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:16:03.546  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:16:03.546  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@594df99 removed from the list
11-24 12:16:03.547  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:16:03.547  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 12:16:03.547  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:16:03.547  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-24 12:16:03.547  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 12:16:03.547  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d0650e0 removed from the list
,11-24 12:16:03.547  5664  5664 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-24 12:16:03.547  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.547  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-24 12:16:03.547  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-24 12:16:03.547  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-24 12:16:03.547  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.547  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 12:16:03.547  5664  5664 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.547  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33fe66a added. We now have 3 listener(s)
11-24 12:16:03.547  5664  5664 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-24 12:16:03.547  5664  5664 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.547  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.548  5949  5965 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 12:16:03.548  5949  5965 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:16:03.548  5949  5965 E BtGatt.ContextMap: Context not found for ID 5
11-24 12:16:03.548  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-24 12:16:03.548  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 12:16:03.548  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 12:16:03.548  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 12:16:03.548  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a65975b added. We now have 4 listener(s)
11-24 12:16:03.548  5664  5711 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 12:16:03.549  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-24 12:16:03.549  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-24 12:16:03.549  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cc15bf8 added. We now have 4 listener(s)
11-24 12:16:03.549  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.549  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.549  5664  5664 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-24 12:16:03.550  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-24 12:16:03.550  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-24 12:16:03.550  5664  5711 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-24 12:16:03.550  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-24 12:16:03.550  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@229e8d1 added. We now have 5 listener(s)
11-24 12:16:03.550  5664  5711 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-24 12:16:03.550  5664  5711 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-24 12:16:03.550  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-24 12:16:03.550  5664  5711 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-24 12:16:03.551  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:16:03.551  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-24 12:16:03.551  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 12:16:03.551  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@33fe66a removed from the list
,11-24 12:16:03.551  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:16:03.551  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a65975b removed from the list
11-24 12:16:03.551  5664  5711 D io.jxcore.node.ConnectivityMonitor: stop
11-24 12:16:03.551  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.551  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.552  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.552  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.552  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.552  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:16:03.552  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:16:03.552  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:16:03.552  5664  5711 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@a65975b not in the list
11-24 12:16:03.552  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-24 12:16:03.552  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.553  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.553  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.553  5664  5711 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-24 12:16:03.553  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-24 12:16:03.553  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-24 12:16:03.553  5664  5711 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-24 12:16:03.553  5664  5711 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@229e8d1 removed from the list
11-24 12:16:03.553  5664  5711 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-24 12:16:03.553  5664  5711 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-24 12:16:03.553  5664  5711 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-24 12:16:03.553  5664  5711 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@cc15bf8 removed from the list
11-24 12:16:03.553  5949  5965 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 12:16:03.553  5949  5965 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:16:03.553  5949  5968 D BtGatt.ScanManager: stopping BLe Batch
11-24 12:16:03.554  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-24 12:16:03.554  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-24 12:16:03.554  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-24 12:16:03.554  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
,11-24 12:16:03.554  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-24 12:16:03.554  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-24 12:16:03.559  5949  5965 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 12:16:03.559  5949  5965 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:16:03.559  5949  5968 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 12:16:03.563  5949  5965 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 12:16:03.563  5949  5965 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:16:03.565  5949  5968 D BtGatt.ScanManager: handling starting scan
,11-24 12:16:03.570  5949  5965 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-24 12:16:03.570  5949  5965 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:16:03.570  5949  5968 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-24 12:16:03.575  5949  5965 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-24 12:16:03.575  5949  5965 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:16:03.575  5949  5968 D BtGatt.ScanManager: Starting BLE batch scan
11-24 12:16:03.575  5949  5968 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-24 12:16:03.583  5949  5965 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-24 12:16:03.583  5949  5965 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:16:03.588  5949  5965 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-24 12:16:03.588  5949  5965 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:16:03.589  5949  5968 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 12:16:03.594  5949  5965 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-24 12:16:03.594  5949  5965 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:16:03.594  5949  5965 E BtGatt.ContextMap: Context not found for ID 5
,11-24 12:16:03.600  5949  5965 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-24 12:16:03.600  5949  5965 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:16:03.600  5949  5968 D BtGatt.ScanManager: stopping BLe Batch
,11-24 12:16:03.605  5949  5965 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-24 12:16:03.605  5949  5965 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-24 12:16:03.605  5949  5968 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-24 12:16:03.610  5949  5965 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-24 12:16:03.610  5949  5965 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-24 12:16:03.880  6003  6003 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-24 12:16:03.916  6003  6003 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-24 12:16:03.917  6003  6003 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-24 12:16:03.929   925  2989 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 12:16:03.929   925  2989 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-24 12:16:03.929   925  2991 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-24 12:16:03.949   925  2989 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-24 12:16:03.965   506   919 D CommandListener: Setting iface cfg
,11-24 12:16:03.972   925  2989 D WifiStateMachine: Start Dhcp Watchdog 3
,11-24 12:16:03.974  5664  5664 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 12:16:03.980   925  6008 D DhcpClient: Receive thread started
,11-24 12:16:03.985   925  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 12:16:03.985   925  2989 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-24 12:16:03.985   925  2991 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-24 12:16:04.010  5664  5664 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 12:16:04.048  5664  5664 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-24 12:16:04.075   925  2989 E native  : do suspend false
,11-24 12:16:04.094   925  6007 D DhcpClient: Broadcasting DHCPDISCOVER
,11-24 12:16:04.113   925  6008 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172764, domain null
,11-24 12:16:04.115   925  6007 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172764 seconds
,11-24 12:16:04.117   925  6007 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-24 12:16:04.131   925  6008 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-24 12:16:04.132   925  6007 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-24 12:16:04.135   506   919 D CommandListener: Setting iface cfg
,11-24 12:16:04.141   925  2989 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-24 12:16:04.144   925  6007 D DhcpClient: Scheduling renewal in 86399s
,11-24 12:16:04.162   925  2989 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-24 12:16:04.162   925  2989 D WifiConfigStore: No blacklist allowed without epno enabled
11-24 12:16:04.163   925  2991 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-24 12:16:04.172   925  2991 D ConnectivityService: Adding iface wlan0 to network 102
11-24 12:16:04.176   925  2989 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-24 12:16:04.223   925  2991 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-24 12:16:04.223   925  2991 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-24 12:16:04.225   925  2991 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-24 12:16:04.228   925  2991 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-24 12:16:04.232   925  2991 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-24 12:16:04.241   925  2991 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 12:16:04.243   591   591 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 12:16:04.245   925  2991 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-24 12:16:04.246   925  2991 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-24 12:16:04.246   925  2991 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-24 12:16:04.246   925  2991 D ConnectivityService:    accepting network in place of null
11-24 12:16:04.246   925  2989 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-24 12:16:04.246   925  2989 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-24 12:16:04.247   925  2991 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -38]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-24 12:16:04.257   925  6006 D NetlinkSocketObserver: NeighborEvent{elapsedMs=169636, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-24 12:16:04.269   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 12:16:04.292   506   919 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-24 12:16:04.296   925  2991 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-24 12:16:04.296   925  2991 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-24 12:16:04.296  3775  3927 W QCNEJ   : |CORE| network available: 102
11-24 12:16:04.297   925  2991 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,11-24 12:16:04.299   925   942 D Tethering: MasterInitialState.processMessage what=3
,11-24 12:16:04.304  3775  3927 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-24 12:16:04.305  3775  3927 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-24 12:16:04.305  3775  3927 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-24 12:16:04.307  5068  5092 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-24 12:16:04.307  5068  5092 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-24 12:16:04.307  5068  5092 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-24 12:16:04.307  5068  5092 E SarControlService: no key has been found,reset the power
11-24 12:16:04.308  5068  5105 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,11-24 12:16:04.308  5068  5105 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-24 12:16:04.308  5068  5105 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,11-24 12:16:04.309  5093  5093 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 12:16:04.310  5093  5093 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-24 12:16:04.318  3893  3893 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-24 12:16:04.320  3978  3978 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-24 12:16:04.321   925  6005 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.22.110,2a00:1450:4001:81d::200e
11-24 12:16:04.323  5068  5105 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-24 12:16:04.323  5068  5105 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-24 12:16:04.323  5068  5105 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-24 12:16:04.324  5093  5107 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@26ed00d HexData = [00000000f003000000000000ffffffff]
11-24 12:16:04.324  5093  5107 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 12:16:04.324  5093  5107 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
,11-24 12:16:04.325  5093  5093 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-24 12:16:04.325  5093  5093 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-24 12:16:04.326  3893  3893 D SystemUpdateService: onCreate
11-24 12:16:04.327  5093  5093 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 12:16:04.328  5068  5078 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-24 12:16:04.333  5093  5107 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@26ed00d HexData = [00000000f103000000000000ffffffff]
11-24 12:16:04.333  5093  5107 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-24 12:16:04.333  5093  5107 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-24 12:16:04.334  5093  5093 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-24 12:16:04.334  5068  5079 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-24 12:16:04.334  3893  3893 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-24 12:16:04.352  3893  3893 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-24 12:16:04.357  3893  6018 I SystemUpdateService: active receiver: enabled
,11-24 12:16:04.365  3893  5437 I iu.UploadsManager: num queued entries: 0
,11-24 12:16:04.365  3893  5437 I iu.UploadsManager: num updated entries: 0
11-24 12:16:04.366  3893  5437 I iu.SyncManager: NEXT; no task
,11-24 12:16:04.367  3893  3893 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-24 12:16:04.368  3893  3893 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-24 12:16:04.370  5799  5799 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-24 12:16:04.373   925  6005 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 24 Nov 2016 17:16:04 GMT], X-Android-Received-Millis=[1480007764372], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480007764348]}
11-24 12:16:04.373   925  2991 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-24 12:16:04.373   925  2991 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-24 12:16:04.373   925  2991 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-24 12:16:04.374   925  2991 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-24 12:16:04.375  5799  5799 D SprintDMHelper: simOperator: 
11-24 12:16:04.375  5799  5799 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-24 12:16:04.398  3893  6018 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-24 12:16:04.408  3893  6018 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-24 12:16:04.408  3893  6018 I SystemUpdateService: now status is 0 (complete)
11-24 12:16:04.408  3893  6018 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-24 12:16:04.408  3893  6018 I SystemUpdateService: file has been verified
,11-24 12:16:04.408  3893  6018 I SystemUpdateService: OTA package size = 21989297
,11-24 12:16:04.429  3893  6018 I SystemUpdateService: showing system update notification
,11-24 12:16:04.437  3596  6029 I VacuumService: Vacuum at: now=1480007764437 tag=VacuumService
,11-24 12:16:04.443  3893  3893 D SystemUpdateService: onDestroy
,11-24 12:16:04.486  5040  6024 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-24 12:16:04.487  3596  6033 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-24 12:16:04.526  3596  6030 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-24 12:16:04.529  3596  6030 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-24 12:16:04.554  3596  6033 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 12:16:04.859  3596  6030 W Uploader:  no longer exists, so no auth token.
,11-24 12:16:04.867  3596  6036 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 12:16:04.928  3596  6033 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 12:16:05.137  3596  6036 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 12:16:05.195  3596  6030 W Uploader:  no longer exists, so no auth token.
,11-24 12:16:05.206  3596  6033 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 12:16:05.288  3596  6036 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-24 12:16:05.649  5664  6040 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 12:16:05.649  5664  6040 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 12:16:06.474  5664  6040 W !!      : call onHalfStreamCopied
,11-24 12:16:06.474  5664  6040 I testCopyDataAndClose: closing input stream
,11-24 12:16:07.260  5664  6040 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 178, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 12:16:07.260  5664  6040 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 12:16:07.260  5664  6040 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 12:16:07.260  5664  6040 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 12:16:07.260  5664  6040 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 12:16:07.260  5664  6040 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 12:16:07.260  5664  6040 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-24 12:16:07.260  5664  6040 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 12:16:07.260  5664  6040 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-24 12:16:07.260  5664  6040 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 178, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-24 12:16:07.260  5664  6040 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-24 12:16:11.416  5664  6042 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-24 12:16:11.416  5664  6042 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 12:16:12.252   925  2991 D ConnectivityService: handlePromptUnvalidated 102
,11-24 12:16:13.416  5664  5711 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 181. Connection data: Peer properties: [null null].
11-24 12:16:13.416  5664  5711 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 12:16:13.416  5664  5711 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 181, name: My test thread name)
,11-24 12:16:13.460  5664  6042 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-24 12:16:13.460  5664  6042 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 181, name: My test thread name). Connection data: Peer properties: [null null].
11-24 12:16:13.460  5664  6042 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 154 and the total number of bytes written 154
,11-24 12:16:13.552  5664  6043 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 12:16:13.552  5664  6043 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 12:16:15.166  5664  6043 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 183, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 12:16:15.166  5664  6043 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 12:16:15.166  5664  6043 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 12:16:15.166  5664  6043 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 12:16:15.167  5664  6043 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 12:16:15.167  5664  6043 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 12:16:15.167  5664  6043 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-24 12:16:15.167  5664  6043 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 12:16:15.167  5664  6043 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-24 12:16:15.167  5664  6043 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 183, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-24 12:16:15.167  5664  6043 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-24 12:16:15.268   925  2989 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 11, 12 -> obsolete
,11-24 12:16:18.891  5664  6044 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-24 12:16:18.891  5664  6044 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 12:16:18.891  5664  6044 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 185, thread name: My test thread name). Connection data: Peer properties: [null null].
11-24 12:16:18.891  5664  6044 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 12:16:18.891  5664  6044 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-24 12:16:18.891  5664  6044 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-24 12:16:18.891  5664  6044 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-24 12:16:18.891  5664  6044 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-24 12:16:18.892  5664  6044 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-24 12:16:18.892  5664  6044 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-24 12:16:18.892  5664  6044 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-24 12:16:18.892  5664  6044 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 185, name: My test thread name). Connection data: Peer properties: [null null].
11-24 12:16:18.892  5664  6044 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-24 12:16:18.894  5664  5711 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-24 12:16:18.896  5664  6045 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-24 12:16:18.896  5664  6045 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-24 12:16:18.897  5664  6045 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 189, thread name: My test thread name): Test exception.
11-24 12:16:18.897  5664  6045 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-24 12:16:18.897  5664  6045 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-24 12:16:18.898  5664  6045 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-24 12:16:18.898  5664  6045 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 189, name: My test thread name). Connection data: Peer properties: [null null].
11-24 12:16:18.898  5664  6045 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-24 12:16:18.903  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-24 12:16:18.903  5664  5711 I jxcore-log: 
11-24 12:16:18.903  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-24 12:16:18.903  5664  5711 I jxcore-log: 
11-24 12:16:18.904  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-24 12:16:18.904  5664  5711 I jxcore-log: 
,11-24 12:16:18.904  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-24 12:16:18.904  5664  5711 I jxcore-log: 
11-24 12:16:18.904  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG UnitTest_app: 'Total duration:  91081'
11-24 12:16:18.904  5664  5711 I jxcore-log: 
,11-24 12:16:18.906  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-24 12:16:18.906  5664  5711 I jxcore-log: 
,11-24 12:16:18.909  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 12:16:18.909  5664  5711 I jxcore-log: 
,11-24 12:16:18.910  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 12:16:18.910  5664  5711 I jxcore-log: 
11-24 12:16:18.911  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-24 12:16:18.911  5664  5711 I jxcore-log: 
11-24 12:16:18.911  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-24 12:16:18.911  5664  5711 I jxcore-log: 
,11-24 12:16:18.911  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 12:16:18.911  5664  5711 I jxcore-log: 
11-24 12:16:18.911  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 12:16:18.911  5664  5711 I jxcore-log: 
11-24 12:16:18.912  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 12:16:18.912  5664  5711 I jxcore-log: 
11-24 12:16:18.912  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 12:16:18.912  5664  5711 I jxcore-log: 
,11-24 12:16:18.912  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 12:16:18.912  5664  5711 I jxcore-log: 
11-24 12:16:18.913  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-24 12:16:18.913  5664  5711 I jxcore-log: 
11-24 12:16:18.913  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-24 12:16:18.913  5664  5711 I jxcore-log: 
11-24 12:16:18.913  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 12:16:18.913  5664  5711 I jxcore-log: 
,11-24 12:16:18.913  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 12:16:18.913  5664  5711 I jxcore-log: 
11-24 12:16:18.914  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 12:16:18.914  5664  5711 I jxcore-log: 
11-24 12:16:18.914  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 12:16:18.914  5664  5711 I jxcore-log: 
11-24 12:16:18.914  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 12:16:18.914  5664  5711 I jxcore-log: 
,11-24 12:16:18.914  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 12:16:18.914  5664  5711 I jxcore-log: 
11-24 12:16:18.914  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 12:16:18.914  5664  5711 I jxcore-log: 
11-24 12:16:18.915  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 12:16:18.915  5664  5711 I jxcore-log: 
11-24 12:16:18.915  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 12:16:18.915  5664  5711 I jxcore-log: 
,11-24 12:16:18.915  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-24 12:16:18.915  5664  5711 I jxcore-log: 
11-24 12:16:18.915  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-24 12:16:18.915  5664  5711 I jxcore-log: 
11-24 12:16:18.916  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 12:16:18.916  5664  5711 I jxcore-log: 
11-24 12:16:18.916  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-24 12:16:18.916  5664  5711 I jxcore-log: 
,11-24 12:16:18.918  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-24 12:16:18.918  5664  5711 I jxcore-log: 
11-24 12:16:18.918  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-24 12:16:18.918  5664  5711 I jxcore-log: 
11-24 12:16:18.918  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-24 12:16:18.918  5664  5711 I jxcore-log: 
11-24 12:16:18.918  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-24 12:16:18.918  5664  5711 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-24 12:16:18.919  5664  5711 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-24 12:16:18.919  5664  5711 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-24 12:16:18.919  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 12:16:18.919  5664  5711 I jxcore-log: 
11-24 12:16:18.919  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 12:16:18.919  5664  5711 I jxcore-log: 
11-24 12:16:18.919  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 12:16:18.919  5664  5711 I jxcore-log: 
,11-24 12:16:18.919  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 12:16:18.919  5664  5711 I jxcore-log: 
11-24 12:16:18.920  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-24 12:16:18.920  5664  5711 I jxcore-log: 
11-24 12:16:18.920  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-24 12:16:18.920  5664  5711 I jxcore-log: 
,11-24 12:16:18.925  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-24 12:16:18.925  5664  5711 I jxcore-log: 
,11-24 12:16:18.925  5664  5711 I jxcore-log: 2016-11-24 17:16:18 - WARN testUtils: 'myNameCallback not set!'
11-24 12:16:18.925  5664  5711 I jxcore-log: 
,11-24 12:16:18.930  5664  5664 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
11-24 12:16:18.930  5664  5664 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-24 12:16:20.976  5664  5711 I jxcore-log: 2016-11-24 17:16:20 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-24 12:16:20.976  5664  5711 I jxcore-log: 
,11-24 12:16:20.978  5664  5711 I jxcore-log: 2016-11-24 17:16:20 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-24 12:16:20.978  5664  5711 I jxcore-log: 
,11-24 12:16:21.317  5664  5711 I jxcore-log: 2016-11-24 17:16:21 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-24 12:16:21.317  5664  5711 I jxcore-log: 
,11-24 12:16:21.328  5664  5711 I jxcore-log: 2016-11-24 17:16:21 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-24 12:16:21.328  5664  5711 I jxcore-log: 
,11-24 12:16:22.440  5664  5711 I jxcore-log: 2016-11-24 17:16:22 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-24 12:16:22.440  5664  5711 I jxcore-log: 
,11-24 12:16:22.633  5664  5711 I jxcore-log: 2016-11-24 17:16:22 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-24 12:16:22.633  5664  5711 I jxcore-log: 
,11-24 12:16:22.639  5664  5711 I jxcore-log: 2016-11-24 17:16:22 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-24 12:16:22.639  5664  5711 I jxcore-log: 
,11-24 12:16:22.643  5664  5711 I jxcore-log: 2016-11-24 17:16:22 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-24 12:16:22.643  5664  5711 I jxcore-log: 
,11-24 12:16:23.128  5664  5711 I jxcore-log: 2016-11-24 17:16:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-24 12:16:23.128  5664  5711 I jxcore-log: 
,11-24 12:16:23.173  5664  5711 I jxcore-log: 2016-11-24 17:16:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-24 12:16:23.173  5664  5711 I jxcore-log: 
,11-24 12:16:23.186  5664  5711 I jxcore-log: 2016-11-24 17:16:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-24 12:16:23.186  5664  5711 I jxcore-log: 
,11-24 12:16:23.190  5664  5711 I jxcore-log: 2016-11-24 17:16:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-24 12:16:23.190  5664  5711 I jxcore-log: 
,11-24 12:16:23.461  5664  5711 I jxcore-log: 2016-11-24 17:16:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-24 12:16:23.461  5664  5711 I jxcore-log: 
,11-24 12:16:23.589  5664  5711 I jxcore-log: 2016-11-24 17:16:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-24 12:16:23.589  5664  5711 I jxcore-log: 
,11-24 12:16:23.968  5664  5711 I jxcore-log: 2016-11-24 17:16:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-24 12:16:23.968  5664  5711 I jxcore-log: 
,11-24 12:16:23.976  5664  5711 I jxcore-log: 2016-11-24 17:16:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-24 12:16:23.976  5664  5711 I jxcore-log: 
,11-24 12:16:23.980  5664  5711 I jxcore-log: 2016-11-24 17:16:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-24 12:16:23.980  5664  5711 I jxcore-log: 
,11-24 12:16:23.985  5664  5711 I jxcore-log: 2016-11-24 17:16:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-24 12:16:23.985  5664  5711 I jxcore-log: 
,11-24 12:16:23.991  5664  5711 I jxcore-log: 2016-11-24 17:16:23 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-24 12:16:23.991  5664  5711 I jxcore-log: 
,11-24 12:16:24.019  5664  5711 I jxcore-log: 2016-11-24 17:16:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-24 12:16:24.019  5664  5711 I jxcore-log: 
,11-24 12:16:24.054  5664  5711 I jxcore-log: 2016-11-24 17:16:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-24 12:16:24.054  5664  5711 I jxcore-log: 
,11-24 12:16:24.061  5664  5711 I jxcore-log: 2016-11-24 17:16:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-24 12:16:24.061  5664  5711 I jxcore-log: 
,11-24 12:16:24.068  5664  5711 I jxcore-log: 2016-11-24 17:16:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-24 12:16:24.068  5664  5711 I jxcore-log: 
,11-24 12:16:24.083  5664  5711 I jxcore-log: 2016-11-24 17:16:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-24 12:16:24.083  5664  5711 I jxcore-log: 
,11-24 12:16:24.099  5664  5711 I jxcore-log: 2016-11-24 17:16:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-24 12:16:24.099  5664  5711 I jxcore-log: 
,11-24 12:16:24.105  5664  5711 I jxcore-log: 2016-11-24 17:16:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-24 12:16:24.105  5664  5711 I jxcore-log: 
,11-24 12:16:24.110  5664  5711 I jxcore-log: 2016-11-24 17:16:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-24 12:16:24.110  5664  5711 I jxcore-log: 
,11-24 12:16:24.123  5664  5711 I jxcore-log: 2016-11-24 17:16:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-24 12:16:24.123  5664  5711 I jxcore-log: 
,11-24 12:16:24.140  5664  5711 I jxcore-log: 2016-11-24 17:16:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-24 12:16:24.140  5664  5711 I jxcore-log: 
,11-24 12:16:24.155  5664  5711 I jxcore-log: 2016-11-24 17:16:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-24 12:16:24.155  5664  5711 I jxcore-log: 
,11-24 12:16:24.165  5664  5711 I jxcore-log: 2016-11-24 17:16:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-24 12:16:24.165  5664  5711 I jxcore-log: 
,11-24 12:16:24.178  5664  5711 I jxcore-log: 2016-11-24 17:16:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-24 12:16:24.178  5664  5711 I jxcore-log: 
,11-24 12:16:24.188  5664  5711 I jxcore-log: 2016-11-24 17:16:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-24 12:16:24.188  5664  5711 I jxcore-log: 
,11-24 12:16:24.201  5664  5711 I jxcore-log: 2016-11-24 17:16:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-24 12:16:24.201  5664  5711 I jxcore-log: 
,11-24 12:16:24.211  5664  5711 I jxcore-log: 2016-11-24 17:16:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-24 12:16:24.211  5664  5711 I jxcore-log: 
,11-24 12:16:24.218  5664  5711 I jxcore-log: 2016-11-24 17:16:24 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-24 12:16:24.218  5664  5711 I jxcore-log: 
,11-24 12:16:24.246   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:16:24.253  5664  5711 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-24 12:16:24.254  5664  5711 I jxcore-log: 2016-11-24 17:16:24 - INFO testUtils: 'BLE multiple advertisement supported'
11-24 12:16:24.254  5664  5711 I jxcore-log: 
,11-24 12:16:24.287  5664  5711 I jxcore-log: 2016-11-24 17:16:24 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-24 12:16:24.287  5664  5711 I jxcore-log: 
,11-24 12:16:24.606  5664  5711 I jxcore-log: 2016-11-24 17:16:24 - DEBUG CoordinatedClient: 'connected to the test server'
11-24 12:16:24.606  5664  5711 I jxcore-log: 
,11-24 12:16:25.247   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:16:26.249   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:16:27.250   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:16:28.251   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:16:29.251   591   591 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 12:16:44.225   925  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 12:16:54.252   591   591 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 12:16:54.252   591   591 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 12:17:04.253   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:17:05.255   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:17:06.256   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:17:07.257   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:17:08.259   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:17:09.259   591   591 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 12:17:14.260   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:17:15.261   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:17:16.263   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:17:17.264   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:17:18.265   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:17:19.266   591   591 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 12:17:24.230   925  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 12:17:29.267   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:17:30.269   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:17:31.270   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:17:32.271   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:17:33.273   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:17:34.274   591   591 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-24 12:17:44.231   925  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 12:17:49.275   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:17:50.277   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:17:51.278   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:17:52.279   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:17:53.280   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:17:54.281   591   591 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 12:18:14.282   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:18:15.284   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:18:16.285   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:18:17.286   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:18:18.287   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:18:19.288   591   591 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 12:18:24.236   925  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 12:18:44.235   925  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 12:18:44.288   591   591 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 12:18:44.289   591   591 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 12:18:59.290   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:00.291   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:01.293   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:02.294   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:03.295   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:04.237   925  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 12:19:04.296   591   591 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-24 12:19:09.298   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:10.299   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:11.300   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:12.301   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:13.302   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:14.303   591   591 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-24 12:19:24.304   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:25.305   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:26.307   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:27.308   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:28.310   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:29.310   591   591 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-24 12:19:44.242   925  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 12:19:44.312   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:45.313   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:46.314   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:47.315   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:48.317   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:19:49.317   591   591 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-24 12:20:04.244   925  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 12:20:09.319   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:20:10.320   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:20:11.321   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:20:12.323   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:20:13.324   591   591 I ServiceManager: Waiting for service AtCmdFwd...
,11-24 12:20:14.325   591   591 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-24 12:20:24.255   925  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 12:20:39.326   591   591 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-24 12:20:39.326   591   591 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-24 12:20:44.258   925  2989 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-24 12:20:53.604  5664  5711 I jxcore-log: 2016-11-24 17:20:53 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-24 12:20:53.604  5664  5711 I jxcore-log: 
,11-24 12:20:53.841  5664  5711 I jxcore-log: 2016-11-24 17:20:53 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 12:20:53.841  5664  5711 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 12:20:53.841  5664  5711 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 12:20:53.841  5664  5711 I jxcore-log: emit@events.js:82:1
11-24 12:20:53.841  5664  5711 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 12:20:53.841  5664  5711 I jxcore-log: emit@events.js:82:1''
11-24 12:20:53.841  5664  5711 I jxcore-log: 
,11-24 12:20:53.843  5664  5711 I jxcore-log: 2016-11-24 17:20:53 - DEBUG CoordinatedClient: 'test client failed'
11-24 12:20:53.843  5664  5711 I jxcore-log: 
,11-24 12:20:53.855  5664  5711 I jxcore-log: 2016-11-24 17:20:53 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 12:20:53.855  5664  5711 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 12:20:53.855  5664  5711 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 12:20:53.855  5664  5711 I jxcore-log: emit@events.js:82:1
11-24 12:20:53.855  5664  5711 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 12:20:53.855  5664  5711 I jxcore-log: emit@events.js:82:1''
11-24 12:20:53.855  5664  5711 I jxcore-log: 
,11-24 12:20:53.856  5664  5711 I jxcore-log: 2016-11-24 17:20:53 - DEBUG CoordinatedClient: 'test client failed'
11-24 12:20:53.856  5664  5711 I jxcore-log: 
,11-24 12:20:53.861  5664  5711 I jxcore-log: 2016-11-24 17:20:53 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-24 12:20:53.861  5664  5711 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-24 12:20:53.861  5664  5711 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-24 12:20:53.861  5664  5711 I jxcore-log: emit@events.js:82:1
11-24 12:20:53.861  5664  5711 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-24 12:20:53.861  5664  5711 I jxcore-log: emit@events.js:82:1''
11-24 12:20:53.861  5664  5711 I jxcore-log: 
,11-24 12:20:53.862  5664  5711 I jxcore-log: 2016-11-24 17:20:53 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-24 12:20:53.862  5664  5711 I jxcore-log: 
,11-24 12:20:54.472  6056  6056 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<,
,11-24 12:20:54.495  6056  6056 D AndroidRuntime: CheckJNI is OFF
,11-24 12:20:54.518  6056  6056 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-24 12:20:54.549  6056  6056 I Radio-JNI: register_android_hardware_Radio DONE
,11-24 12:20:54.564  6056  6056 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-24 12:20:54.575   925   938 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-24 12:20:54.576   925   938 I ActivityManager: Killing 5664:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-24 12:20:54.689   925  3889 D GraphicsStats: Buffer count: 2
11-24 12:20:54.689   925  3170 I WindowState: WIN DEATH: Window{b23766d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-24 12:20:54.691   925  2990 D WifiService: Client connection lost with reason: 4
,11-24 12:20:54.707   925   949 I art     : Starting a blocking GC Explicit
,11-24 12:20:54.715   925   938 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-24 12:20:54.715   925   938 W PackageManager: Package com.test.thalitest is missing; assuming frozen
11-24 12:20:54.716   925   938 E ActivityManager: Failure starting process com.test.thalitest
11-24 12:20:54.716   925   938 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-24 12:20:54.716   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-24 12:20:54.716   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-24 12:20:54.716   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-24 12:20:54.716   925   938 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-24 12:20:54.716   925   938 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-24 12:20:54.716   925   938 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-24 12:20:54.716   925   938 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-24 12:20:54.716   925   938 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-24 12:20:54.716   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-24 12:20:54.716   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-24 12:20:54.716   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-24 12:20:54.716   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-24 12:20:54.716   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-24 12:20:54.716   925   938 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-24 12:20:54.716   925   938 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:20:54.716   925   938 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:20:54.716   925   938 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 12:20:54.716   925   938 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-24 12:20:54.716   925   938 I ActivityManager:   Force finishing activity ActivityRecord{4c50d51 u0 com.test.thalitest/.MainActivity t10}
,11-24 12:20:54.725   925  3917 W ActivityManager: Spurious death for ProcessRecord{9492172 0:com.test.thalitest/u0a77}, curProc for 5664: null
,11-24 12:20:54.728   925   943 W WindowManager: Attempted to add application window with unknown token Token{f9b89b6 ActivityRecord{4c50d51 u0 com.test.thalitest/.MainActivity t10 f}}.  Aborting.
,11-24 12:20:54.729   925   943 W WindowManager: Token{f9b89b6 ActivityRecord{4c50d51 u0 com.test.thalitest/.MainActivity t10 f}} already running, starting window not displayed. Unable to add window -- token Token{f9b89b6 ActivityRecord{4c50d51 u0 com.test.thalitest/.MainActivity t10 f}} is not valid; is your activity running?
11-24 12:20:54.729   925   943 W WindowManager: view not successfully added to wm, removing view
11-24 12:20:54.729   925   943 W WindowManager: Exception when adding starting window
11-24 12:20:54.729   925   943 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{58d0035 V.E...... R.....ID 0,0-0,0} not attached to window manager
11-24 12:20:54.729   925   943 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
11-24 12:20:54.729   925   943 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
11-24 12:20:54.729   925   943 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
11-24 12:20:54.729   925   943 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
11-24 12:20:54.729   925   943 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
11-24 12:20:54.729   925   943 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:20:54.729   925   943 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:20:54.729   925   943 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 12:20:54.729   925   943 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-24 12:20:54.802   925   949 I art     : Explicit concurrent mark sweep GC freed 134913(9MB) AllocSpace objects, 88(2MB) LOS objects, 33% free, 29MB/44MB, paused 1.538ms total 94.982ms
,11-24 12:20:54.822   925   949 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-24 12:20:54.825  6056  6056 I art     : System.exit called, status: 0
,11-24 12:20:54.825  6056  6056 I AndroidRuntime: VM exiting with result code 0.
,11-24 12:20:54.840   925   949 I ActivityManager: Start proc 6066:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
11-24 12:20:54.841   925   949 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-24 12:20:54.848   925   938 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-24 12:20:54.853  5949  5949 D BluetoothMapAppObserver: onReceive
,11-24 12:20:54.853  5949  5949 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-24 12:20:54.866  3674  3674 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-24 12:20:54.867  4115  4210 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
11-24 12:20:54.872   925  2954 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-24 12:20:54.888  3674  6078 I Keyboard.Facilitator.DecoderInitializer: run()
,11-24 12:20:54.897  3674  6078 I Decoder : createOrResetDecoder
,11-24 12:20:54.916  3826  3826 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-24 12:20:54.918    63    63 W kworker/2:2: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 12:20:54.921    63    63 W kworker/2:2: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 12:20:54.933  3412  3439 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,11-24 12:20:54.936  3596  3596 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
11-24 12:20:54.937  3596  3596 D AndroidRuntime: Shutting down VM
--------- beginning of crash
11-24 12:20:54.938  3596  3596 E AndroidRuntime: FATAL EXCEPTION: main
11-24 12:20:54.938  3596  3596 E AndroidRuntime: Process: com.google.process.gapps, PID: 3596
11-24 12:20:54.938  3596  3596 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-24 12:20:54.938  3596  3596 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
11-24 12:20:54.938  3596  3596 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
11-24 12:20:54.938  3596  3596 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
11-24 12:20:54.938  3596  3596 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:20:54.938  3596  3596 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:20:54.938  3596  3596 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 12:20:54.938  3596  3596 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 12:20:54.938  3596  3596 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 12:20:54.938  3596  3596 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 12:20:54.938  3596  3596 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-24 12:20:54.938  3596  3596 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-24 12:20:54.938  3596  3596 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-24 12:20:54.938  3596  3596 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-24 12:20:54.938  3596  3596 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-24 12:20:54.938  3596  3596 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-24 12:20:54.938  3596  3596 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
11-24 12:20:54.938  3596  3596 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
11-24 12:20:54.938  3596  3596 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
11-24 12:20:54.938  3596  3596 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
11-24 12:20:54.938  3596  3596 E AndroidRuntime: 	... 8 more
11-24 12:20:54.939   925   925 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-24 12:20:54.947  3596  3596 I Process : Sending signal. PID: 3596 SIG: 9
,11-24 12:20:54.945    63    63 W kworker/2:2: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-24 12:20:54.953  3850  3965 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
11-24 12:20:54.956   925   937 E PackageManager: Failed to write settings, restoring backup
11-24 12:20:54.956   925   937 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
11-24 12:20:54.956   925   937 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
11-24 12:20:54.956   925   937 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
11-24 12:20:54.956   925   937 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-24 12:20:54.956   925   937 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-24 12:20:54.956   925   937 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:20:54.956   925   937 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:20:54.956   925   937 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-24 12:20:54.958   925   938 E DropBoxManagerService: Can't write: system_server_wtf
11-24 12:20:54.958   925   938 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
11-24 12:20:54.958   925   938 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 12:20:54.958   925   938 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 12:20:54.958   925   938 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 12:20:54.958   925   938 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 12:20:54.958   925   938 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 12:20:54.958   925   938 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 12:20:54.958   925   938 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
11-24 12:20:54.958   925   938 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
11-24 12:20:54.958   925   938 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
11-24 12:20:54.958   925   938 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
11-24 12:20:54.958   925   938 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-24 12:20:54.958   925   938 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:20:54.958   925   938 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-24 12:20:54.958   925   938 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-24 12:20:54.958   925   938 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 12:20:54.958   925   938 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 12:20:54.958   925   938 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 12:20:54.958   925   938 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 12:20:54.958   925   938 E DropBoxManagerService: 	... 13 more
,11-24 12:20:54.962  3412  6081 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-24 12:20:54.969   925  3846 I ActivityManager: Start proc 6086:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,11-24 12:20:54.970  3850  3965 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-24 12:20:54.970  3850  3965 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3850
11-24 12:20:54.970  3850  3965 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-24 12:20:54.970  3850  3965 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-24 12:20:54.970  3850  3965 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-24 12:20:54.970  3850  3965 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-24 12:20:54.970  3850  3965 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-24 12:20:54.970  3850  3965 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-24 12:20:54.970  3850  3965 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-24 12:20:54.970  3850  3965 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-24 12:20:54.970  3850  3965 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-24 12:20:54.970  3850  3965 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-24 12:20:54.970  3850  3965 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:20:54.970  3850  3965 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-24 12:20:54.972   925  3882 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-24 12:20:54.972   925  6092 E DropBoxManagerService: Can't write: system_app_crash
11-24 12:20:54.972   925  6092 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop130.tmp: open failed: EROFS (Read-only file system)
11-24 12:20:54.972   925  6092 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 12:20:54.972   925  6092 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 12:20:54.972   925  6092 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 12:20:54.972   925  6092 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 12:20:54.972   925  6092 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 12:20:54.972   925  6092 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 12:20:54.972   925  6092 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 12:20:54.972   925  6092 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 12:20:54.972   925  6092 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 12:20:54.972   925  6092 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 12:20:54.972   925  6092 E DropBoxManagerService: 	... 5 more
,11-24 12:20:54.977  3850  3965 I Process : Sending signal. PID: 3850 SIG: 9
,11-24 12:20:54.981   925  2990 D WifiService: Client connection lost with reason: 4
11-24 12:20:54.981   925  3899 I ActivityManager: Process com.google.process.gapps (pid 3596) has died
,11-24 12:20:54.981   925  3899 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.tapandpay.hce.service.TpHceService in 1000ms
,11-24 12:20:54.981   925  3899 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 11000ms
,11-24 12:20:54.982   925  3899 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 21000ms
11-24 12:20:55.005   925  3427 I ActivityManager: Start proc 6100:com.google.process.gapps/u0a12 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,11-24 12:20:55.014  3412  3439 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
11-24 12:20:55.014  3412  3439 E AndroidRuntime: Process: android.process.acore, PID: 3412
11-24 12:20:55.014  3412  3439 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-24 12:20:55.014  3412  3439 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-24 12:20:55.014  3412  3439 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
11-24 12:20:55.014  3412  3439 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
11-24 12:20:55.014  3412  3439 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
11-24 12:20:55.014  3412  3439 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
11-24 12:20:55.014  3412  3439 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
11-24 12:20:55.014  3412  3439 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:391)
11-24 12:20:55.014  3412  3439 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
11-24 12:20:55.014  3412  3439 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
11-24 12:20:55.014  3412  3439 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
11-24 12:20:55.014  3412  3439 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:20:55.014  3412  3439 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:20:55.014  3412  3439 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-24 12:20:55.019   925  6112 E DropBoxManagerService: Can't write: system_app_crash
11-24 12:20:55.019   925  6112 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop131.tmp: open failed: EROFS (Read-only file system)
11-24 12:20:55.019   925  6112 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 12:20:55.019   925  6112 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 12:20:55.019   925  6112 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 12:20:55.019   925  6112 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 12:20:55.019   925  6112 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 12:20:55.019   925  6112 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 12:20:55.019   925  6112 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 12:20:55.019   925  6112 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 12:20:55.019   925  6112 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 12:20:55.019   925  6112 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 12:20:55.019   925  6112 E DropBoxManagerService: 	... 5 more
,11-24 12:20:55.062  3412  6081 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
11-24 12:20:55.062  3412  6081 I Process : Sending signal. PID: 3412 SIG: 9
,11-24 12:20:55.080   925  2953 W InputDispatcher: channel '4ec74b4 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Consumer closed input channel or an error occurred.  events=0x9
11-24 12:20:55.080   925  2953 E InputDispatcher: channel '4ec74b4 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)' ~ Channel is unrecoverably broken and will be disposed!
,11-24 12:20:55.081   925  3170 I WindowState: WIN DEATH: Window{4ec74b4 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
11-24 12:20:55.081   925  3917 D GraphicsStats: Buffer count: 1
11-24 12:20:55.081   925  3170 W InputDispatcher: Attempted to unregister already unregistered input channel '4ec74b4 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL (server)'
,11-24 12:20:55.092   925  3917 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3850) has died
,11-24 12:20:55.093   925  3917 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,11-24 12:20:55.094   925  3917 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-24 12:20:55.097   380   380 E lowmemorykiller: Error writing /proc/3412/oom_score_adj; errno=22
,11-24 12:20:55.110   925   938 I ActivityManager: Start proc 6114:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-24 12:20:55.143   925  3426 I ActivityManager: Process android.process.acore (pid 3412) has died
,11-24 12:20:55.143   925  3426 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
,11-24 12:20:55.157  6114  6114 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 12:20:55.157  6114  6114 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-24 12:20:55.158  6114  6114 D AndroidRuntime: Shutting down VM
,11-24 12:20:55.164  6114  6114 E AndroidRuntime: FATAL EXCEPTION: main
11-24 12:20:55.164  6114  6114 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6114
11-24 12:20:55.164  6114  6114 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-24 12:20:55.164  6114  6114 E AndroidRuntime: 	... 10 more
,11-24 12:20:55.167   925   936 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-24 12:20:55.167   925  6127 E DropBoxManagerService: Can't write: system_app_crash
11-24 12:20:55.167   925  6127 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop132.tmp: open failed: EROFS (Read-only file system)
11-24 12:20:55.167   925  6127 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 12:20:55.167   925  6127 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 12:20:55.167   925  6127 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 12:20:55.167   925  6127 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 12:20:55.167   925  6127 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 12:20:55.167   925  6127 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 12:20:55.167   925  6127 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 12:20:55.167   925  6127 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 12:20:55.167   925  6127 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 12:20:55.167   925  6127 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 12:20:55.167   925  6127 E DropBoxManagerService: 	... 5 more
,11-24 12:20:55.168  6114  6114 I Process : Sending signal. PID: 6114 SIG: 9
,11-24 12:20:55.182   925  3917 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6114) has died
,11-24 12:20:55.184   925  3917 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-24 12:20:55.198   925   938 I ActivityManager: Start proc 6128:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-24 12:20:55.247  6128  6128 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 12:20:55.247  6128  6128 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-24 12:20:55.248  6128  6128 D AndroidRuntime: Shutting down VM
,11-24 12:20:55.255  6128  6128 E AndroidRuntime: FATAL EXCEPTION: main
11-24 12:20:55.255  6128  6128 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 6128
11-24 12:20:55.255  6128  6128 E AndroidRuntime: java.lang.RuntimeException: Unable to get provider com.android.launcher3.LauncherProvider: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5161)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4753)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4693)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at android.content.ContentProvider.attachInfo(ContentP,rovider.java:1723)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5158)
11-24 12:20:55.255  6128  6128 E AndroidRuntime: 	... 10 more
,11-24 12:20:55.258   925   935 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
11-24 12:20:55.258   925  6140 E DropBoxManagerService: Can't write: system_app_crash
11-24 12:20:55.258   925  6140 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop133.tmp: open failed: EROFS (Read-only file system)
11-24 12:20:55.258   925  6140 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-24 12:20:55.258   925  6140 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-24 12:20:55.258   925  6140 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-24 12:20:55.258   925  6140 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-24 12:20:55.258   925  6140 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-24 12:20:55.258   925  6140 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-24 12:20:55.258   925  6140 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-24 12:20:55.258   925  6140 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-24 12:20:55.258   925  6140 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-24 12:20:55.258   925  6140 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-24 12:20:55.258   925  6140 E DropBoxManagerService: 	... 5 more
,11-24 12:20:55.259  6128  6128 I Process : Sending signal. PID: 6128 SIG: 9
,11-24 12:20:55.275   925  3427 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 6128) has died
,11-24 12:20:55.277   925  3427 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,11-24 12:20:55.292   925   938 I ActivityManager: Start proc 6141:com.google.android.googlequicksearchbox/u0a29 for activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL

```
