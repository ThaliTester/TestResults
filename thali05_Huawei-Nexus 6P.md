#### Test 94187094bea3271_thali05_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-17 11:22:03.489  5312  5357 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
11-17 11:22:03.536  5312  5357 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
11-17 11:22:03.564  5312  5357 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
11-17 11:22:03.672  3541  4799 I Icing   : Indexing F030E08B5368E93E2F43DEEC3A6B244C622F15EE from com.google.android.googlequicksearchbox
11-17 11:22:03.775  3541  4799 I Icing   : Indexing done F030E08B5368E93E2F43DEEC3A6B244C622F15EE
,11-17 11:22:04.717  5365  5365 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-17 11:22:04.723  5365  5365 D AndroidRuntime: CheckJNI is OFF
11-17 11:22:04.746  5365  5365 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-17 11:22:04.776  5365  5365 I Radio-JNI: register_android_hardware_Radio DONE
11-17 11:22:04.791  5365  5365 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
11-17 11:22:04.794   928   938 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-17 11:22:04.835   928   938 I ActivityManager: Start proc 5374:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-17 11:22:04.840  5365  5365 D AndroidRuntime: Shutting down VM
,11-17 11:22:05.177   928   939 I WindowManager: Screenshot max retries 4 of Token{bd3bf0f ActivityRecord{b3bcc6e u0 com.test.thalitest/.MainActivity t6}} appWin=Window{3dcfb46 u0 Starting com.test.thalitest} drawState=2
,11-17 11:22:05.262  5374  5374 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-17 11:22:05.290  5374  5374 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-17 11:22:05.356  5374  5374 I LibraryLoader: Time to load native libraries: 61 ms (timestamps 5394-5455)
,11-17 11:22:05.356  5374  5374 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-17 11:22:05.380  5374  5374 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {a562ff7}
,11-17 11:22:05.381  5374  5374 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-17 11:22:05.381  5374  5374 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-17 11:22:05.385  5374  5374 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-17 11:22:05.386  5374  5374 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-17 11:22:05.425  5374  5389 W chromium: [WARNING:dns_config_service_posix.cc(297)] Failed to read DnsConfig.
,11-17 11:22:05.430  5374  5374 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-17 11:22:05.439  5374  5374 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-17 11:22:05.439  5374  5374 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-17 11:22:05.439  5374  5374 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-17 11:22:05.439  5374  5374 I Adreno  : Build Date                       : 12/06/15
11-17 11:22:05.439  5374  5374 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-17 11:22:05.439  5374  5374 I Adreno  : Local Branch                     : mybranch17112971
11-17 11:22:05.439  5374  5374 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-17 11:22:05.439  5374  5374 I Adreno  : Remote Branch                    : NONE
11-17 11:22:05.439  5374  5374 I Adreno  : Reconstruct Branch               : NOTHING
,11-17 11:22:05.469   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d5e1615:true
,11-17 11:22:05.492   406   406 W Binder_1: type=1400 audit(0.0:99): avc: denied { ioctl } for path="socket:[22322]" dev="sockfs" ino=22322 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-17 11:22:05.492   406   406 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[22322]" dev="sockfs" ino=22322 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-17 11:22:05.503  5374  5374 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-17 11:22:05.511  5374  5374 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-17 11:22:05.532   406   406 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32409]" dev="sockfs" ino=32409 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-17 11:22:05.534  5374  5411 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
11-17 11:22:05.532   406   406 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32409]" dev="sockfs" ino=32409 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-17 11:22:05.535  3529  3529 W Binder_8: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[22326]" dev="sockfs" ino=22326 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-17 11:22:05.535  3529  3529 W Binder_8: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[22326]" dev="sockfs" ino=22326 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-17 11:22:05.541  5374  5398 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-17 11:22:05.568  5374  5411 I OpenGLRenderer: Initialized EGL, version 1.4
,11-17 11:22:05.625   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +446ms (total +814ms)
,11-17 11:22:05.649  5374  5374 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5374
,11-17 11:22:05.736  5374  5374 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,11-17 11:22:05.886  5374  5414 D jxcore_app_log: JniHelper::setJavaVM(0xf4e7c000), pthread_self() = -604243664
,11-17 11:22:05.891  5374  5414 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-17 11:22:05.891  5374  5414 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-17 11:22:05.891  5374  5414 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-17 11:22:05.891  5374  5414 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-17 11:22:05.891  5374  5414 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-17 11:22:05.891  5374  5414 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@efb0e45 added. We now have 1 listener(s)
,11-17 11:22:05.897  5374  5414 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,11-17 11:22:05.897  5374  5414 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-17 11:22:05.898  5374  5414 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-17 11:22:05.898  5374  5414 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-17 11:22:05.900  5374  5414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-17 11:22:05.900  5374  5414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-17 11:22:05.900  5374  5414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-17 11:22:05.900  5374  5414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
11-17 11:22:05.900  5374  5414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-17 11:22:05.900  5374  5414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-17 11:22:05.900  5374  5414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-17 11:22:05.900  5374  5414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-17 11:22:05.900  5374  5414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-17 11:22:05.900  5374  5414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-17 11:22:05.900  5374  5414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-17 11:22:05.900  5374  5414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-17 11:22:05.900  5374  5414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-17 11:22:05.900  5374  5414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-17 11:22:05.900  5374  5414 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4b0eaa8 added. We now have 1 listener(s)
11-17 11:22:05.900  5374  5414 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-17 11:22:05.905   928  2868 D WifiService: New client listening to asynchronous messages
,11-17 11:22:05.905  5374  5414 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-17 11:22:05.905  5374  5414 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-17 11:22:05.906  5374  5414 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 47
11-17 11:22:05.906  5374  5414 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-17 11:22:05.906  5374  5414 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-17 11:22:05.906  5374  5414 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,11-17 11:22:05.906  5374  5414 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 47
,11-17 11:22:05.907  5374  5414 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-17 11:22:06.003  5374  5374 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,11-17 11:22:06.555  5374  5420 W jxcore-log: Initializing JXcore engine
,11-17 11:22:06.556  5374  5420 W jxcore-log: JXcore engine is ready
,11-17 11:22:06.579  5420  5420 W Thread-53: type=1400 audit(0.0:105): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=5454 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-17 11:22:06.579  5420  5420 W Thread-53: type=1400 audit(0.0:106): avc: denied { ioctl } for path="socket:[16403]" dev="sockfs" ino=16403 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-17 11:22:06.579  5420  5420 W Thread-53: type=1400 audit(0.0:107): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=696 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-17 11:22:06.579  5420  5420 W Thread-53: type=1400 audit(0.0:108): avc: denied { ioctl } for path="socket:[32390]" dev="sockfs" ino=32390 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-17 11:22:06.588  5374  5420 W jxcore-log: Starting JXcore engine
,11-17 11:22:06.637  5374  5420 W jxcore-log: Platform android
11-17 11:22:06.637  5374  5420 W jxcore-log: 
,11-17 11:22:06.637  5374  5420 W jxcore-log: Process ARCH arm
11-17 11:22:06.637  5374  5420 W jxcore-log: 
,11-17 11:22:06.809  5374  5420 I jxcore-log: JXcore Cordova bridge is ready!
11-17 11:22:06.809  5374  5420 I jxcore-log: 
,11-17 11:22:06.809  5374  5420 W jxcore-log: JXcore engine is started
,11-17 11:22:06.823  5374  5414 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-17 11:22:06.827  5374  5374 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-17 11:22:07.402  3424  3424 I ConfigService: onDestroy
,11-17 11:22:16.612  5374  5420 I jxcore-log: 2016-11-17 16:22:16 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-17 11:22:16.612  5374  5420 I jxcore-log: 
,11-17 11:22:16.614  5374  5420 I jxcore-log: 2016-11-17 16:22:16 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-17 11:22:16.614  5374  5420 I jxcore-log: 
,11-17 11:22:16.616  5374  5420 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-17 11:22:16.616  5374  5420 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-17 11:22:16.616  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-17 11:22:16.616  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
11-17 11:22:16.616  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-17 11:22:16.616  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-17 11:22:16.616  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-17 11:22:16.616  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-17 11:22:16.616  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-17 11:22:16.616  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-17 11:22:16.617  5374  5420 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-17 11:22:16.617  5374  5420 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-17 11:22:16.618  5374  5420 I jxcore-log: 2016-11-17 16:22:16 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-17 11:22:16.618  5374  5420 I jxcore-log: 
11-17 11:22:16.619  5374  5420 I jxcore-log: 2016-11-17 16:22:16 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-17 11:22:16.619  5374  5420 I jxcore-log: 
,11-17 11:22:16.867  5374  5420 I jxcore-log: 2016-11-17 16:22:16 - DEBUG UnitTest_app: 'Running unit tests'
11-17 11:22:16.867  5374  5420 I jxcore-log: 
,11-17 11:22:16.868  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-17 11:22:16.868  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@10aaa04 added. We now have 2 listener(s)
,11-17 11:22:16.869  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-17 11:22:16.869  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-17 11:22:16.869  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-17 11:22:16.869  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-17 11:22:16.869  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@46fcbed added. We now have 2 listener(s)
11-17 11:22:16.869  5374  5420 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-17 11:22:16.870  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-17 11:22:16.871  5374  5420 D executeNativeTests: Running unit tests
,11-17 11:22:16.913  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-17 11:22:16.913  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8996fd2 added. We now have 3 listener(s)
,11-17 11:22:16.914  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-17 11:22:16.914  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-17 11:22:16.914  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-17 11:22:16.914  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-17 11:22:16.914  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 added. We now have 3 listener(s)
11-17 11:22:16.914  5374  5420 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-17 11:22:16.914  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-17 11:22:16.916  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-17 11:22:16.916  5374  5420 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-17 11:22:16.916  5374  5420 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-17 11:22:16.916  5374  5420 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-17 11:22:16.916  5374  5420 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-17 11:22:16.917  5374  5420 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-17 11:22:16.917  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-17 11:22:16.917  5374  5420 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-17 11:22:16.917  5374  5420 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-17 11:22:16.917  5374  5420 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-17 11:22:16.918  5374  5420 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-17 11:22:16.918  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-17 11:22:16.918  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-17 11:22:16.919  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 11:22:16.919  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:22:16.919  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-17 11:22:16.919  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8996fd2 removed from the list
11-17 11:22:16.919  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:16.919  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 removed from the list
,11-17 11:22:16.919  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
11-17 11:22:16.919  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:16.919  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:22:16.949  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:16.949  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:22:16.949  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:16.949  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-17 11:22:16.949  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-17 11:22:16.949  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:16.949  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:16.951  5374  5420 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-17 11:22:16.951  5374  5420 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-17 11:22:16.951  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-17 11:22:16.951  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-17 11:22:16.951  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 11:22:16.951  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:22:16.951  5374  5420 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8996fd2 not in the list
11-17 11:22:16.951  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:16.951  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
,11-17 11:22:16.951  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
11-17 11:22:16.951  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:16.952  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:16.952  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:16.952  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:16.952  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:16.952  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-17 11:22:16.952  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-17 11:22:16.952  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:16.952  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
,11-17 11:22:16.955  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-17 11:22:16.955  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-17 11:22:16.955  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-17 11:22:16.955  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-17 11:22:16.955  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
,11-17 11:22:16.955  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-17 11:22:16.955  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-17 11:22:16.955  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-17 11:22:16.955  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-17 11:22:16.955  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-17 11:22:16.955  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
,11-17 11:22:16.955  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-17 11:22:16.955  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-17 11:22:16.955  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-17 11:22:16.955  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-17 11:22:16.955  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-17 11:22:16.955  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-17 11:22:16.955  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,11-17 11:22:16.955  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-17 11:22:16.955  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-17 11:22:16.955  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-17 11:22:16.955  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-17 11:22:16.955  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-17 11:22:16.955  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-17 11:22:16.955  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,11-17 11:22:16.955  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-17 11:22:16.955  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-17 11:22:16.955  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-17 11:22:16.956  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-17 11:22:16.956  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-17 11:22:16.956  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-17 11:22:16.956  5374  5420 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-17 11:22:16.956  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-17 11:22:16.956  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-17 11:22:16.956  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 11:22:16.956  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:22:16.956  5374  5420 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8996fd2 not in the list
11-17 11:22:16.956  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:16.956  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:16.956  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
11-17 11:22:16.956  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:16.956  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:16.958  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:16.958  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:16.958  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:16.958  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-17 11:22:16.958  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-17 11:22:16.958  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:16.958  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:16.959  5374  5420 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-17 11:22:16.959  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-17 11:22:16.960  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-17 11:22:16.961  5374  5420 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-17 11:22:16.961  5374  5420 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-17 11:22:16.961  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-17 11:22:16.961  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
11-17 11:22:16.961  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-17 11:22:16.961  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-17 11:22:16.961  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-17 11:22:16.961  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-17 11:22:16.961  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-17 11:22:16.961  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-17 11:22:16.961  5374  5420 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-17 11:22:16.961  5374  5420 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-17 11:22:16.961  5374  5420 D io.jxcore.node.ConnectivityMonitor: start: OK
11-17 11:22:16.961  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-17 11:22:16.961  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-17 11:22:16.961  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-17 11:22:16.961  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-17 11:22:16.961  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-17 11:22:16.962  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
11-17 11:22:16.962  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:16.963  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:16.963  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
11-17 11:22:16.963  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:16.963  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:16.963  5374  5420 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
11-17 11:22:16.963  5374  5420 I io.jxcore.node.ConnectionHelper: start: OK
11-17 11:22:16.964  5374  5374 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,11-17 11:22:17.025  4697  4727 D Finsky  : [180] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
11-17 11:22:17.026  4697  4697 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-17 11:22:17.466  5374  5374 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-17 11:22:21.965  5374  5420 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-17 11:22:21.965  5374  5420 W org.thaliproject.p2p.btconnectorlib.DiscoveryManager: Bluetooth is not enabled so we could not check whether or not Bluetooth LE multiple advertisement is supported. However, Bluetooth LE is supported so we just *assume* this feature is supported too (which may not always be the case).
,11-17 11:22:21.967  5374  5420 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-17 11:22:21.968  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-17 11:22:21.968  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-17 11:22:21.968  5374  5420 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-17 11:22:21.968  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-17 11:22:21.968  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:22:21.968  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-17 11:22:21.968  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-17 11:22:21.968  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:22:21.969  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. WAITING_FOR_SERVICES_TO_BE_ENABLED
,11-17 11:22:21.969  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-17 11:22:21.969  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-17 11:22:21.970  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-17 11:22:21.971  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:22:21.971  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:21.971  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 11:22:21.971  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:21.972  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:21.972  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 11:22:21.972  5374  5420 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-17 11:22:21.972  5374  5374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-17 11:22:21.972  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-17 11:22:21.972  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:22:21.972  5374  5374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 11:22:21.972  5374  5420 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8996fd2 not in the list
11-17 11:22:21.973  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-17 11:22:21.973  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:21.973  5374  5374 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 11:22:21.973  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
11-17 11:22:21.973  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-17 11:22:21.974  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:21.974  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:21.975  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:21.975  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:21.975  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:22:21.975  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-17 11:22:21.975  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-17 11:22:21.975  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:21.975  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:21.977  5374  5420 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-17 11:22:21.978  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-17 11:22:21.979  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-17 11:22:21.981  5374  5420 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-17 11:22:21.981  5374  5420 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-17 11:22:21.981  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-17 11:22:21.981  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_RESOLVED
11-17 11:22:21.981  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-17 11:22:21.981  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-17 11:22:21.981  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-17 11:22:21.981  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-17 11:22:21.981  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-17 11:22:21.981  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-17 11:22:21.981  5374  5420 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-17 11:22:21.981  5374  5420 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-17 11:22:21.982  5374  5420 D io.jxcore.node.ConnectivityMonitor: start: OK
11-17 11:22:21.982  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-17 11:22:21.982  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-17 11:22:21.982  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-17 11:22:21.982  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-17 11:22:21.982  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-17 11:22:21.984  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Cannot start BLE based peer discovery, because Bluetooth is not enabled on the device
11-17 11:22:21.985  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:22:21.985  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:21.985  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
11-17 11:22:21.985  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:21.985  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:22:21.985  5374  5420 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
11-17 11:22:21.985  5374  5420 I io.jxcore.node.ConnectionHelper: start: OK
11-17 11:22:21.985  5374  5374 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false
,11-17 11:22:22.486  5374  5374 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-17 11:22:23.446   535   535 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-17 11:22:23.446   535   535 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-17 11:22:26.986  5374  5420 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-17 11:22:26.987  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: WAITING_FOR_SERVICES_TO_BE_ENABLED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-17 11:22:26.987  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-17 11:22:26.987  5374  5420 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-17 11:22:26.987  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-17 11:22:26.987  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:22:26.987  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-17 11:22:26.987  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-17 11:22:26.987  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:22:26.987  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. WAITING_FOR_SERVICES_TO_BE_ENABLED
11-17 11:22:26.987  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-17 11:22:26.988  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-17 11:22:26.988  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-17 11:22:26.988  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:22:26.989  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:26.989  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 11:22:26.989  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:26.989  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:22:26.990  5374  5374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 11:22:26.990  5374  5374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 11:22:26.990  5374  5374 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-17 11:22:27.491  5374  5374 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
11-17 11:22:27.491  5374  5374 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-17 11:22:27.491  5374  5374 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-17 11:22:28.448   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 11:22:29.449   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 11:22:30.451   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 11:22:31.452   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 11:22:31.991  5374  5420 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-17 11:22:31.992  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-17 11:22:31.992  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-17 11:22:31.992  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 11:22:31.992  5374  5420 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-17 11:22:31.992  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-17 11:22:31.992  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:22:31.993  5374  5420 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8996fd2 not in the list
11-17 11:22:31.993  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-17 11:22:31.993  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
,11-17 11:22:31.993  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
11-17 11:22:31.994  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-17 11:22:31.996  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:22:31.996  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:31.997  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:31.997  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:22:31.998  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:22:31.998  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-17 11:22:31.998  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-17 11:22:31.998  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-17 11:22:31.999  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:32.001  5374  5420 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-17 11:22:32.004  5374  5420 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-17 11:22:32.004  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-17 11:22:32.005  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-17 11:22:32.005  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 11:22:32.005  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:22:32.006  5374  5420 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8996fd2 not in the list
11-17 11:22:32.006  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:32.006  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
,11-17 11:22:32.006  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
11-17 11:22:32.007  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.007  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.008  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.009  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.009  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.010  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-17 11:22:32.010  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-17 11:22:32.010  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:32.010  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
,11-17 11:22:32.012  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-17 11:22:32.012  5374  5420 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-17 11:22:32.012  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-17 11:22:32.013  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-17 11:22:32.013  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 11:22:32.013  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:22:32.013  5374  5420 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8996fd2 not in the list
11-17 11:22:32.013  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-17 11:22:32.013  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:32.013  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
11-17 11:22:32.013  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.013  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:22:32.014  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.014  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.014  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.014  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-17 11:22:32.014  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-17 11:22:32.015  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:32.015  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:32.016  5374  5420 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
11-17 11:22:32.016  5374  5420 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-17 11:22:32.016  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-17 11:22:32.016  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-17 11:22:32.016  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 11:22:32.016  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:22:32.017  5374  5420 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8996fd2 not in the list
,11-17 11:22:32.017  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:32.017  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:32.017  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
,11-17 11:22:32.017  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.017  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.018  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.018  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.018  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.018  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-17 11:22:32.018  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-17 11:22:32.018  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:32.018  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:32.019  5374  5420 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-17 11:22:32.020  5374  5420 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-17 11:22:32.020  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-17 11:22:32.020  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-17 11:22:32.020  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 11:22:32.020  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:22:32.020  5374  5420 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8996fd2 not in the list
11-17 11:22:32.020  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-17 11:22:32.020  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:32.021  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
11-17 11:22:32.021  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.021  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.022  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.022  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.022  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.022  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-17 11:22:32.022  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-17 11:22:32.022  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:32.022  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:32.023  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-17 11:22:32.024  5374  5420 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-17 11:22:32.024  5374  5420 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-17 11:22:32.024  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-17 11:22:32.024  5374  5420 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-17 11:22:32.024  5374  5420 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-17 11:22:32.024  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-17 11:22:32.024  5374  5420 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-17 11:22:32.024  5374  5420 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-17 11:22:32.024  5374  5420 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-17 11:22:32.024  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-17 11:22:32.024  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-17 11:22:32.025  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 11:22:32.025  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:22:32.025  5374  5420 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8996fd2 not in the list
11-17 11:22:32.025  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:32.025  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:32.025  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
11-17 11:22:32.025  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.025  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:22:32.026  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.027  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.027  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.027  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-17 11:22:32.027  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-17 11:22:32.027  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:32.027  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:32.028  5374  5420 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-17 11:22:32.028  5374  5420 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
,11-17 11:22:32.028  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-17 11:22:32.032  5374  5420 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-17 11:22:32.032  5374  5420 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
,11-17 11:22:32.032  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-17 11:22:32.032  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-17 11:22:32.032  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-17 11:22:32.032  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-17 11:22:32.033  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-17 11:22:32.033  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-17 11:22:32.033  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-17 11:22:32.033  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,11-17 11:22:32.033  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-17 11:22:32.033  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-17 11:22:32.033  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,11-17 11:22:32.033  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-17 11:22:32.033  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-17 11:22:32.033  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-17 11:22:32.033  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-17 11:22:32.033  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-17 11:22:32.033  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-17 11:22:32.033  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,11-17 11:22:32.034  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-17 11:22:32.034  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,11-17 11:22:32.034  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-17 11:22:32.034  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-17 11:22:32.034  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-17 11:22:32.034  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-17 11:22:32.034  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-17 11:22:32.034  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-17 11:22:32.034  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,11-17 11:22:32.034  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-17 11:22:32.034  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-17 11:22:32.034  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-17 11:22:32.034  5374  5420 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-17 11:22:32.035  5374  5420 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-17 11:22:32.035  5374  5420 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-17 11:22:32.035  5374  5420 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,11-17 11:22:32.035  5374  5420 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-17 11:22:32.035  5374  5420 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-17 11:22:32.035  5374  5420 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-17 11:22:32.036  5374  5420 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-17 11:22:32.036  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-17 11:22:32.038  5374  5420 E BluetoothDevice: BT not enabled. Cannot get Remote Device name
,11-17 11:22:32.038  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,11-17 11:22:32.039  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-17 11:22:32.039  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
11-17 11:22:32.040  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-17 11:22:32.040  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-17 11:22:32.040  5374  5420 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-17 11:22:32.040  5374  5420 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-17 11:22:32.041  5374  5420 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-17 11:22:32.041  5374  5421 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 117)
,11-17 11:22:32.041  5374  5421 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-17 11:22:32.041  5374  5421 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-17 11:22:32.041  5374  5421 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-17 11:22:32.041  5374  5421 E BluetoothDevice: Bluetooth is not enabled
11-17 11:22:32.041  5374  5421 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: null
11-17 11:22:32.041  5374  5421 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Failed to connect (tried 1 time(s)): null (thread ID: 117)
11-17 11:22:32.042  5374  5421 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Maximum number of allowed retries (0) reached, giving up... (thread ID: 117)
11-17 11:22:32.042  5374  5421 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onConnectionFailed: Failed to connect (tried 1 time(s)): null (thread ID: 117)
11-17 11:22:32.042  5374  5420 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-17 11:22:32.042  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-17 11:22:32.042  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-17 11:22:32.042  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 11:22:32.042  5374  5421 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: removeAndShutdownBluetoothClientThread: Thread ID: 117
11-17 11:22:32.042  5374  5421 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdownBluetoothClientThread: Thread ID: 117
11-17 11:22:32.042  5374  5374 W org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnectionFailed: Failed to connect to peer [<no peer name> 00:11:22:33:44:55]: Failed to connect (tried 1 time(s)): null
11-17 11:22:32.043  5374  5374 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: Failed to connect (tried 1 time(s)): null
11-17 11:22:32.043  5374  5374 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-17 11:22:32.044  5374  5374 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-17 11:22:32.044  5374  5374 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-17 11:22:32.044  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false,
11-17 11:22:32.044  5374  5422 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 117
11-17 11:22:32.044  5374  5420 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8996fd2 not in the list
11-17 11:22:32.044  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-17 11:22:32.044  5374  5422 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-17 11:22:32.044  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:32.044  5374  5421 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-17 11:22:32.044  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
11-17 11:22:32.044  5374  5421 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 117)
11-17 11:22:32.044  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:22:32.044  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.045  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.045  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.045  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:22:32.045  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-17 11:22:32.045  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-17 11:22:32.045  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:32.045  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:32.046  5374  5420 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
,11-17 11:22:32.047  5374  5420 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-17 11:22:32.047  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-17 11:22:32.047  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-17 11:22:32.047  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 11:22:32.047  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:22:32.047  5374  5420 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8996fd2 not in the list
11-17 11:22:32.047  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-17 11:22:32.048  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:32.048  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
11-17 11:22:32.048  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.048  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.048  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.049  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.049  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.049  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-17 11:22:32.049  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-17 11:22:32.049  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:32.049  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:32.050  5374  5420 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-17 11:22:32.050  5374  5420 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-17 11:22:32.050  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-17 11:22:32.050  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-17 11:22:32.050  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 11:22:32.050  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-17 11:22:32.050  5374  5420 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8996fd2 not in the list
11-17 11:22:32.050  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:32.051  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:32.051  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
11-17 11:22:32.051  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.051  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.051  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.051  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.052  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:22:32.052  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-17 11:22:32.052  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-17 11:22:32.052  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:32.052  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:32.052  5374  5420 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-17 11:22:32.053  5374  5420 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-17 11:22:32.053  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-17 11:22:32.053  5374  5420 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-17 11:22:32.053  5374  5420 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,11-17 11:22:32.053  5374  5420 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-17 11:22:32.053  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-17 11:22:32.053  5374  5420 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-17 11:22:32.053  5374  5420 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-17 11:22:32.054  5374  5420 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-17 11:22:32.054  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-17 11:22:32.054  5374  5420 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-17 11:22:32.054  5374  5420 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-17 11:22:32.054  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-17 11:22:32.054  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-17 11:22:32.054  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 11:22:32.054  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:22:32.054  5374  5420 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8996fd2 not in the list
11-17 11:22:32.054  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:32.054  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:32.055  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
11-17 11:22:32.055  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:22:32.055  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.055  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.055  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.056  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:32.056  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-17 11:22:32.056  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-17 11:22:32.056  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:32.056  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
,11-17 11:22:32.056  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 11:22:32.057  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:22:32.057  5374  5420 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8996fd2 not in the list
,11-17 11:22:32.057  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:32.057  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:32.057  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
,11-17 11:22:32.454   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 11:22:33.455   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-17 11:22:37.058  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-17 11:22:37.058  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:37.058  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 11:22:37.058  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:22:37.058  5374  5420 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8996fd2 not in the list
11-17 11:22:37.059  5374  5420 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-17 11:22:37.059  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-17 11:22:37.059  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-17 11:22:37.059  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 11:22:37.059  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-17 11:22:37.060  5374  5420 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8996fd2 not in the list
11-17 11:22:37.060  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:37.060  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:37.060  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
11-17 11:22:37.060  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:22:37.061  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:22:37.062  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:22:37.062  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:37.062  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:37.062  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-17 11:22:37.062  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-17 11:22:37.063  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:37.063  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:37.066  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-17 11:22:37.067  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-17 11:22:37.067  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-17 11:22:37.071  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: Bluetooth disabled, waiting for it to be enabled...
,11-17 11:22:37.071  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  false
11-17 11:22:37.072  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> WAITING_FOR_SERVICES_TO_BE_ENABLED
11-17 11:22:37.072  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-17 11:22:37.073  5374  5374 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: WAITING_FOR_SERVICES_TO_BE_ENABLED
11-17 11:22:37.073  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 11:22:37.074  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
,11-17 11:22:37.074  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-17 11:22:37.075  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:22:37.075  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: WAITING_FOR_SERVICES_TO_BE_ENABLED -> NOT_STARTED
11-17 11:22:37.075  5374  5420 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8996fd2 not in the list
11-17 11:22:37.075  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:37.075  5374  5374 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-17 11:22:37.076  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-17 11:22:37.076  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:37.076  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-17 11:22:37.076  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-17 11:22:37.077  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:37.078  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:37.078  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 11:22:37.078  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:37.079  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:37.079  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:37.079  5374  5374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-17 11:22:37.079  5374  5420 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-17 11:22:37.079  5374  5374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 11:22:37.079  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-17 11:22:37.079  5374  5374 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 11:22:37.079  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-17 11:22:37.079  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 11:22:37.079  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:22:37.079  5374  5420 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8996fd2 not in the list
11-17 11:22:37.079  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:37.079  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:37.079  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
,11-17 11:22:37.080  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:37.080  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:37.080  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:37.080  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:37.081  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:37.081  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-17 11:22:37.081  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-17 11:22:37.081  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-17 11:22:37.081  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:37.081  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-17 11:22:37.082  5374  5420 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-17 11:22:37.082  5374  5420 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-17 11:22:37.082  5374  5420 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,11-17 11:22:37.082  5374  5420 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-17 11:22:37.082  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-17 11:22:37.082  5374  5420 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-17 11:22:37.082  5374  5420 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-17 11:22:37.082  5374  5420 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-17 11:22:37.083  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-17 11:22:37.083  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-17 11:22:37.083  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 11:22:37.084  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:22:37.084  5374  5420 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8996fd2 not in the list
,11-17 11:22:37.084  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:37.084  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:37.084  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
11-17 11:22:37.084  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:22:37.084  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:37.085  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:37.085  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:37.085  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:37.085  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-17 11:22:37.085  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-17 11:22:37.085  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:37.085  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:37.087  5374  5420 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-17 11:22:37.088  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-17 11:22:37.088  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-17 11:22:37.088  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-17 11:22:37.088  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:22:37.088  5374  5420 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8996fd2 not in the list
11-17 11:22:37.088  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:37.088  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
,11-17 11:22:37.088  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
11-17 11:22:37.088  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:37.088  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:22:37.089  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:37.089  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:37.089  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:37.089  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-17 11:22:37.090  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-17 11:22:37.090  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:37.090  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:37.090  5374  5420 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-17 11:22:37.091  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-17 11:22:37.091  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-17 11:22:37.091  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 11:22:37.091  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-17 11:22:37.091  5374  5420 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@8996fd2 not in the list
11-17 11:22:37.091  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:37.091  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:37.091  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
11-17 11:22:37.091  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:37.091  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:37.092  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:37.092  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:37.092  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:22:37.092  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-17 11:22:37.092  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-17 11:22:37.092  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:22:37.092  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7d2c8a3 not in the list
11-17 11:22:37.093  5374  5420 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-17 11:22:37.094  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-17 11:22:37.094  5374  5420 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-17 11:22:37.094  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-17 11:22:37.094  5374  5420 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-17 11:22:37.094  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-17 11:22:37.096  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-17 11:22:37.097  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
,11-17 11:22:37.099  5374  5420 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,11-17 11:22:37.099  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-17 11:22:37.099  5374  5420 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-17 11:22:37.099  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-17 11:22:37.099  5374  5420 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-17 11:22:37.099  5374  5420 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-17 11:22:37.099  5374  5420 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
11-17 11:22:37.100  5374  5420 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-17 11:22:37.100  5374  5420 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-17 11:22:37.100  5374  5420 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-17 11:22:37.100  5374  5420 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-17 11:22:37.100  5374  5420 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-17 11:22:37.101  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-17 11:22:37.101  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@dc6a91b added. We now have 3 listener(s)
11-17 11:22:37.101  5374  5420 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-17 11:22:37.103   928  3527 D WifiService: setWifiEnabled: true pid=5374, uid=10077
11-17 11:22:37.103   928  3527 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-17 11:22:37.107   507   922 D SoftapController: Softap fwReload - Ok
,11-17 11:22:37.111   507   922 D CommandListener: Setting iface cfg
,11-17 11:22:37.111   507   922 D CommandListener: Trying to bring down wlan0
11-17 11:22:37.112   507   922 D CommandListener: Clearing all IP addresses on wlan0
,11-17 11:22:37.115   928  2861 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-17 11:22:37.120   928   945 I ActivityManager: Start proc 5425:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-17 11:22:37.142   928  3529 I ActivityManager: Killing 5033:com.google.android.gm.exchange/u0a67 (adj 15): empty #17
,11-17 11:22:37.209  5425  5425 D AdapterServiceConfig: Adding HeadsetService
,11-17 11:22:37.210  5425  5425 D AdapterServiceConfig: Adding A2dpService
11-17 11:22:37.210  5425  5425 D AdapterServiceConfig: Adding HidService
11-17 11:22:37.210  5425  5425 D AdapterServiceConfig: Adding HealthService
11-17 11:22:37.210  5425  5425 D AdapterServiceConfig: Adding PanService
,11-17 11:22:37.210  5425  5425 D AdapterServiceConfig: Adding GattService
11-17 11:22:37.211  5425  5425 D AdapterServiceConfig: Adding BluetoothMapService
,11-17 11:22:37.211  5425  5425 D AdapterServiceConfig: Adding SapService
,11-17 11:22:37.232   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@f3cd365:true
,11-17 11:22:37.232  5425  5425 D BluetoothAdapterState: make() - Creating AdapterState
,11-17 11:22:37.235  5425  5425 I bt_bluedroid: init
,11-17 11:22:37.235  5425  5437 I BluetoothAdapterState: Entering OffState
,11-17 11:22:37.238  5425  5438 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-17 11:22:37.241  5425  5438 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,11-17 11:22:37.241  5425  5438 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-17 11:22:37.241  5425  5438 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-17 11:22:37.242  5425  5425 I bt_bluedroid: get_profile_interface socket
,11-17 11:22:37.244  5425  5441 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-17 11:22:37.244  5425  5425 I bt_bluedroid: get_profile_interface sdp
11-17 11:22:37.245  5425  5441 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-17 11:22:37.249  5425  5435 I bt_bluedroid: config_hci_snoop_log
,11-17 11:22:37.251   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
,11-17 11:22:37.254  5425  5437 D BluetoothAdapterState: Current state: OFF, message: 0
,11-17 11:22:37.254  5425  5437 D BluetoothAdapterProperties: Setting state to 14
11-17 11:22:37.254  5425  5437 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-17 11:22:37.256  5425  5437 D BluetoothBondStateMachine: make
,11-17 11:22:37.258  5425  5442 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-17 11:22:37.260  5425  5437 I BluetoothAdapterState: Entering PendingCommandState
,11-17 11:22:37.261  5425  5425 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-17 11:22:37.263  5425  5425 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f0c67ce
,11-17 11:22:37.264  5425  5425 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-17 11:22:37.265  5425  5425 D BtGatt.GattService: Received start request. Starting profile...
11-17 11:22:37.265  5425  5425 D BtGatt.GattService: start()
11-17 11:22:37.265  5425  5425 I bt_bluedroid: get_profile_interface gatt
,11-17 11:22:37.267  5425  5425 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f0c67ce
,11-17 11:22:37.267  5425  5425 D BtGatt.AdvertiseManager: advertise manager created
,11-17 11:22:37.272  5425  5425 V BluetoothAdapterState: isTurningOff()=false
,11-17 11:22:37.272  5425  5425 V BluetoothAdapterState: isTurningOn()=false
11-17 11:22:37.272  5425  5425 V BluetoothAdapterState: isBleTurningOn()=true
11-17 11:22:37.272  5425  5425 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:22:37.272  5425  5437 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-17 11:22:37.274  5425  5437 I bt_bluedroid: bt_bluedroid
,11-17 11:22:37.274  5425  5438 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-17 11:22:37.274  5425  5438 I bt_hci  : start_up
,11-17 11:22:37.281  5425  5438 I bt_vendor: alloc value 0xf3b57871
,11-17 11:22:37.281  5425  5438 I bt_vendor: init
11-17 11:22:37.281  5425  5438 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-17 11:22:37.281  5425  5438 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-17 11:22:37.390  5425  5438 D bt_hci  : start_up starting async portion
,11-17 11:22:37.390  5425  5445 I bt_hci  : event_finish_startup
11-17 11:22:37.390  5425  5445 I bt_hci_h4: hal_open
11-17 11:22:37.390  5425  5445 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-17 11:22:37.392  5425  5445 I bt_userial_vendor: device fd = 54 open
,11-17 11:22:37.389  5446  5446 W irq/448-msm_hs_: type=1400 audit(0.0:109): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-17 11:22:37.405  5425  5445 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-17 11:22:37.407  5425  5445 D bt_hwcfg: Chipset BCM4358A3
,11-17 11:22:37.407  5425  5445 D bt_hwcfg: Target name = [BCM4358A3]
11-17 11:22:37.407  5425  5445 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-17 11:22:37.580  5374  5374 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-17 11:22:37.780  5425  5445 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-17 11:22:37.781  5425  5445 D bt_hwcfg: Settlement delay -- 100 ms
,11-17 11:22:37.781  5425  5445 I bt_hwcfg: Setting fw settlement delay to 100 
,11-17 11:22:37.789   928  2861 D wifi    : set interface wlan0 flags (UP)
11-17 11:22:37.790   928  2861 I WifiHAL : Initializing wifi
,11-17 11:22:37.790   928  2861 I WifiHAL : Creating socket
,11-17 11:22:37.805   928  2861 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-17 11:22:37.805   928  2861 D wifi    : Did set static halHandle = 0x7f8e3b62e0
11-17 11:22:37.805   928  2861 D wifi    : halHandle = 0x7f8e3b62e0, mVM = 0x7fa4c0d140, mCls = 0x200f96
11-17 11:22:37.806   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-17 11:22:37.806   928  2861 D wifi    : array field set
11-17 11:22:37.807   928  2861 I WifiNative-HAL: interface[0] = wlan0
,11-17 11:22:37.809   928  5448 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547847103200
,11-17 11:22:37.810   928  5448 D wifi    : waitForHalEvents called, vm = 0x7fa4c0d140, obj = 0x200f96, env = 0x7f885b5f40
,11-17 11:22:37.882  5449  5449 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-17 11:22:37.904  5449  5449 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-17 11:22:37.905  5425  5445 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-17 11:22:37.906  5425  5445 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
11-17 11:22:37.907  5425  5445 I bt_hwcfg: vendor lib fwcfg completed
,11-17 11:22:37.907  5425  5445 I bt_vendor: firmware callback
11-17 11:22:37.907  5425  5445 I bt_hci  : firmware_config_callback
,11-17 11:22:37.911  5425  5450 I bt_btu  : btu_task pending for preload complete event
11-17 11:22:37.911  5425  5450 I bt_btu_task: Bluetooth chip preload is complete
11-17 11:22:37.911  5425  5450 I bt_btu  : btu_task received preload complete event
11-17 11:22:37.912   928  2861 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-17 11:22:37.918  5425  5450 I         : BTE_InitTraceLevels -- TRC_HCI
,11-17 11:22:37.918  5425  5450 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-17 11:22:37.918  5425  5450 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-17 11:22:37.918  5425  5450 I         : BTE_InitTraceLevels -- TRC_AVDT
11-17 11:22:37.918  5425  5450 I         : BTE_InitTraceLevels -- TRC_AVRC
11-17 11:22:37.918  5425  5450 I         : BTE_InitTraceLevels -- TRC_A2D
11-17 11:22:37.918  5425  5450 I         : BTE_InitTraceLevels -- TRC_BNEP
11-17 11:22:37.918  5425  5450 I         : BTE_InitTraceLevels -- TRC_BTM
11-17 11:22:37.918  5425  5450 I         : BTE_InitTraceLevels -- TRC_GAP
,11-17 11:22:37.918  5425  5450 I         : BTE_InitTraceLevels -- TRC_PAN
11-17 11:22:37.918  5425  5450 I         : BTE_InitTraceLevels -- TRC_SDP
11-17 11:22:37.918  5425  5450 I         : BTE_InitTraceLevels -- TRC_GATT
11-17 11:22:37.918  5425  5450 I         : BTE_InitTraceLevels -- TRC_SMP
11-17 11:22:37.918  5425  5450 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-17 11:22:37.918  5425  5450 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-17 11:22:37.928   928   941 I ActivityManager: Start proc 5452:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-17 11:22:37.933  5449  5449 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-17 11:22:37.933  5449  5449 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-17 11:22:37.952   928  2861 D WifiConfigStore: Loading config and enabling all networks 
,11-17 11:22:37.961  5452  5452 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-17 11:22:37.964   928  2861 D WifiConfigStore: loaded 0 passpoint configs
,11-17 11:22:37.964   928  2861 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,11-17 11:22:37.965   928  2861 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-17 11:22:37.967   928  2861 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-17 11:22:37.968   928  2861 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-17 11:22:37.968   928  2861 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-17 11:22:37.969   928  2861 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-17 11:22:37.969   928  3723 I ActivityManager: Killing 3388:com.google.android.gm/u0a68 (adj 15): empty #17
11-17 11:22:37.969   928  2861 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-17 11:22:37.990  5425  5450 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3ad5549
,11-17 11:22:37.990  5425  5450 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3ad5549 
,11-17 11:22:37.992   928  2861 D WifiNative-HAL: Setting external_sim to 1
,11-17 11:22:37.992   928  2861 D wifi    : setting dfs flag to true, 0x7f9a13ba80
11-17 11:22:37.993   928  2861 D WifiStateMachine: Setting OUI to DA-A1-19
,11-17 11:22:37.993   928  2861 D wifi    : setting scan oui 0x7f9a13ba80
11-17 11:22:37.993   928  2861 D WifiHAL : Sending mac address OUI
,11-17 11:22:37.996  4872  4872 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-17 11:22:38.004  5425  5441 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-17 11:22:38.005  5425  5441 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-17 11:22:38.005  5425  5441 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-17 11:22:38.006   928  2861 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-17 11:22:38.006   928   928 D RttService: SCAN_AVAILABLE : 3
11-17 11:22:38.006   507   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-17 11:22:38.006   928  2953 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-17 11:22:38.007  5425  5441 D BluetoothAdapterProperties: Name is: Nexus 6P
11-17 11:22:38.008   507   922 D CommandListener: Setting iface cfg
11-17 11:22:38.008  5425  5441 D BluetoothAdapterProperties: Scan Mode:20
11-17 11:22:38.008  5425  5441 D BluetoothAdapterProperties: Discoverable Timeout:120
11-17 11:22:38.009  5425  5441 D bt_hci  : do_postload posting postload work item
11-17 11:22:38.009  5425  5445 I bt_hci  : event_postload
,11-17 11:22:38.009  5425  5445 I bt_vendor: sco_config_cb
11-17 11:22:38.009  5425  5445 I bt_hci  : sco_config_callback postload finished.
,11-17 11:22:38.009   928  2849 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '96 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 96 Failed to set address (No such device)'
,11-17 11:22:38.009   928  2849 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
11-17 11:22:38.011  5425  5441 D bt_bte_conf: Device ID record 1 : primary
11-17 11:22:38.011  5425  5441 D bt_bte_conf:   vendorId            = 000f
11-17 11:22:38.011  5425  5441 D bt_bte_conf:   vendorIdSource      = 0001
11-17 11:22:38.011  5425  5441 D bt_bte_conf:   product             = 1200
11-17 11:22:38.011  5425  5441 D bt_bte_conf:   version             = 1436
,11-17 11:22:38.011  5425  5441 D bt_bte_conf:   clientExecutableURL = 
11-17 11:22:38.011  5425  5441 D bt_bte_conf:   serviceDescription  = 
11-17 11:22:38.011  5425  5441 D bt_bte_conf:   documentationURL    = 
11-17 11:22:38.011  5425  5441 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-17 11:22:38.011  5425  5438 D bt_stack_manager: event_start_up_stack finished
11-17 11:22:38.012  5425  5437 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-17 11:22:38.012  5425  5437 D BluetoothAdapterProperties: Setting state to 15
11-17 11:22:38.012  5425  5437 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-17 11:22:38.012  5425  5437 I BluetoothAdapterState: Entering BleOnState
11-17 11:22:38.015   928  2861 E native  : do suspend false
,11-17 11:22:38.018  5425  5445 I bt_vendor: low_power_mode_cb
,11-17 11:22:38.018  5425  5437 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-17 11:22:38.018  5425  5437 D BluetoothAdapterProperties: Setting state to 11
11-17 11:22:38.018  5425  5437 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-17 11:22:38.025   928  2861 D WifiConfigStore: No blacklist allowed without epno enabled
,11-17 11:22:38.033   928   941 I ActivityManager: Start proc 5472:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-17 11:22:38.035  5425  5425 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f0c67ce
,11-17 11:22:38.035  5425  5425 D HeadsetService: Received start request. Starting profile...
11-17 11:22:38.036   928  2849 D WifiNative-HAL: p2pGetDeviceAddress
11-17 11:22:38.036   928  2849 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
11-17 11:22:38.038  5425  5425 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-17 11:22:38.038  5425  5425 D HeadsetStateMachine: make
,11-17 11:22:38.043  5425  5437 I BluetoothAdapterState: Entering PendingCommandState
,11-17 11:22:38.049  5425  5425 D HeadsetStateMachine: max_hf_connections = 1
,11-17 11:22:38.049  5425  5425 I bt_bluedroid: get_profile_interface handsfree
11-17 11:22:38.049  5425  5441 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-17 11:22:38.049  5425  5441 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-17 11:22:38.052  5425  5425 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f0c67ce
,11-17 11:22:38.054  5425  5425 D A2dpService: Received start request. Starting profile...
,11-17 11:22:38.054  5425  5425 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-17 11:22:38.054  5425  5425 I bt_bluedroid: get_profile_interface avrcp
11-17 11:22:38.055   928   928 D BluetoothA2dp: Proxy object connected
,11-17 11:22:38.061  5425  5425 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-17 11:22:38.062  5425  5425 I BluetoothA2dpServiceJni: classInitNative: succeeds
,11-17 11:22:38.062  5425  5425 D A2dpStateMachine: make
11-17 11:22:38.063  5425  5425 I bt_bluedroid: get_profile_interface a2dp
,11-17 11:22:38.063  5425  5441 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-17 11:22:38.065  5425  5486 D A2dpStateMachine: Enter Disconnected: -2
,11-17 11:22:38.065  5425  5425 I BluetoothHidServiceJni: classInitNative: succeeds
,11-17 11:22:38.066  5425  5425 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f0c67ce
11-17 11:22:38.068  3019  3019 D BluetoothInputDevice: Proxy object connected
11-17 11:22:38.068  5425  5425 D HidService: Received start request. Starting profile...
11-17 11:22:38.068  5425  5425 I bt_bluedroid: get_profile_interface hidhost
11-17 11:22:38.068  3019  3019 D HidProfile: Bluetooth service connected
11-17 11:22:38.068  5425  5441 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ab656d
11-17 11:22:38.068  5425  5425 D HidService: setHidService(): set to: null
11-17 11:22:38.068  5425  5441 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
,11-17 11:22:38.069  5425  5425 I BluetoothHealthServiceJni: classInitNative: succeeds
11-17 11:22:38.070  5425  5425 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f0c67ce
11-17 11:22:38.070  5425  5425 D HealthService: Received start request. Starting profile...
11-17 11:22:38.072  5425  5425 I bt_bluedroid: get_profile_interface health
,11-17 11:22:38.072  5425  5425 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-17 11:22:38.073  5425  5425 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f0c67ce
,11-17 11:22:38.075  3019  3019 D BluetoothPan: BluetoothPAN Proxy object connected
11-17 11:22:38.075  3019  3019 D PanProfile: Bluetooth service connected
11-17 11:22:38.075  5425  5425 D PanService: Received start request. Starting profile...
11-17 11:22:38.075  5425  5425 D BluetoothPanServiceJni: initializeNative(L110): pan
11-17 11:22:38.075  5425  5425 I bt_bluedroid: get_profile_interface pan
,11-17 11:22:38.076  5425  5441 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-17 11:22:38.078  5425  5425 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f0c67ce
,11-17 11:22:38.079  5472  5472 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-17 11:22:38.079  5425  5425 D BluetoothMapService: Received start request. Starting profile...
11-17 11:22:38.080  5425  5425 D BluetoothMapService: start()
11-17 11:22:38.080  3019  3019 D BluetoothMap: Proxy object connected
11-17 11:22:38.080  3019  3019 D MapProfile: Bluetooth service connected
11-17 11:22:38.080  3019  3019 D BluetoothMap: getConnectedDevices()
11-17 11:22:38.081  3019  3019 D BluetoothMap: Bluetooth is Not enabled
11-17 11:22:38.082  5425  5425 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-17 11:22:38.083  5425  5425 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-17 11:22:38.083  5425  5425 D BluetoothMapAppObserver: createReceiver()
11-17 11:22:38.084  5425  5425 D BluetoothMapAppObserver: initObservers()
11-17 11:22:38.084  5425  5425 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-17 11:22:38.089  5425  5425 V SapService: SapBinder()
,11-17 11:22:38.090  5425  5425 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f0c67ce
,11-17 11:22:38.090  5425  5425 D SapService: Received start request. Starting profile...
11-17 11:22:38.090  5425  5425 V SapService: start()
,11-17 11:22:38.094  5425  5425 V BluetoothAdapterState: isTurningOff()=false
,11-17 11:22:38.094  5425  5425 V BluetoothAdapterState: isTurningOn()=true
11-17 11:22:38.094  5425  5425 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:22:38.094  5425  5425 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:22:38.095  5425  5478 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-17 11:22:38.095  5425  5425 V BluetoothAdapterState: isTurningOff()=false
,11-17 11:22:38.095  5425  5425 V BluetoothAdapterState: isTurningOn()=true
11-17 11:22:38.095  5425  5425 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:22:38.095  5425  5425 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:22:38.095  5425  5425 V BluetoothAdapterState: isTurningOff()=false
11-17 11:22:38.095  5425  5425 V BluetoothAdapterState: isTurningOn()=true
11-17 11:22:38.095  5425  5425 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:22:38.095  5425  5425 V BluetoothAdapterState: isBleTurningOff()=false
,11-17 11:22:38.095  5425  5425 V BluetoothAdapterState: isTurningOff()=false
11-17 11:22:38.095  5425  5425 V BluetoothAdapterState: isTurningOn()=true
11-17 11:22:38.096  5425  5425 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:22:38.096  5425  5425 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:22:38.096  5425  5425 V BluetoothAdapterState: isTurningOff()=false
11-17 11:22:38.096  5425  5425 V BluetoothAdapterState: isTurningOn()=true
11-17 11:22:38.096  5425  5425 V BluetoothAdapterState: isBleTurningOn()=false
,11-17 11:22:38.096  5425  5425 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:22:38.096  5425  5425 V BluetoothAdapterState: isTurningOff()=false
11-17 11:22:38.096  5425  5425 V BluetoothAdapterState: isTurningOn()=true
11-17 11:22:38.096  5425  5425 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:22:38.096  5425  5425 V BluetoothAdapterState: isBleTurningOff()=false
,11-17 11:22:38.097  5425  5425 V BluetoothAdapterState: isTurningOff()=false
11-17 11:22:38.097  5425  5425 V BluetoothAdapterState: isTurningOn()=true
11-17 11:22:38.097  5425  5425 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:22:38.098  5425  5425 V BluetoothAdapterState: isBleTurningOff()=false
,11-17 11:22:38.098  5425  5437 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-17 11:22:38.098  5425  5437 D BluetoothAdapterProperties: ScanMode =  20
11-17 11:22:38.098  5425  5437 D BluetoothAdapterProperties: State =  11
11-17 11:22:38.099  5425  5441 D BluetoothAdapterProperties: Scan Mode:21
11-17 11:22:38.099  5425  5437 D BluetoothAdapterProperties: Setting state to 12
11-17 11:22:38.099  5425  5441 D BluetoothAdapterProperties: Discoverable Timeout:120
11-17 11:22:38.099  5425  5437 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,11-17 11:22:38.100   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-17 11:22:38.100  5425  5437 I BluetoothAdapterState: Entering OnState
11-17 11:22:38.101  3019  3031 D BluetoothMap: onBluetoothStateChange: up=true
,11-17 11:22:38.102  3019  3030 D BluetoothPbap: onBluetoothStateChange: up=true
11-17 11:22:38.104  3019  3840 D BluetoothInputDevice: onBluetoothStateChange: up=true
,11-17 11:22:38.104  3656  3855 D BluetoothHeadset: onBluetoothStateChange: up=true
11-17 11:22:38.104   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-17 11:22:38.104   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-17 11:22:38.105  3019  3031 D BluetoothPan: onBluetoothStateChange on: true
11-17 11:22:38.105   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-17 11:22:38.105   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,11-17 11:22:38.106  5425  5425 D BluetoothMapService: onReceive
,11-17 11:22:38.106  5425  5425 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-17 11:22:38.106  5425  5425 D BluetoothMapService: STATE_ON
,11-17 11:22:38.110  5425  5425 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-17 11:22:38.110  3019  3247 D LocalBluetoothProfileManager: Adding local A2DP profile
11-17 11:22:38.110  5425  5425 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,11-17 11:22:38.112  5425  5425 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-17 11:22:38.112  5425  5491 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-17 11:22:38.114  3019  3019 D BluetoothA2dp: Proxy object connected
11-17 11:22:38.114  5425  5425 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-17 11:22:38.115  5425  5491 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-17 11:22:38.115  5425  5491 D BluetoothSdpJni: SDP Create record success - handle: 0
11-17 11:22:38.115  5425  5425 D ObexServerSockets: Succeed to create listening sockets 
11-17 11:22:38.115  5425  5425 D ObexServerSockets0: startAccept()
11-17 11:22:38.115  5425  5425 D ObexServerSockets0: prepareForNewConnect()
11-17 11:22:38.115  3019  3247 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-17 11:22:38.117  5425  5425 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
,11-17 11:22:38.117  5425  5425 D BluetoothSdpJni: SDP Create record success - handle: 1
11-17 11:22:38.117  5425  5495 D ObexServerSockets0: Accepting socket connection...
11-17 11:22:38.118  5425  5494 D ObexServerSockets0: Accepting socket connection...
,11-17 11:22:38.120   928  3711 I ActivityManager: Killing 5019:com.google.android.youtube/u0a75 (adj 15): empty #17
,11-17 11:22:38.127  5425  5425 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-17 11:22:38.127  5425  5425 D ObexServerSockets0: prepareForNewConnect()
,11-17 11:22:38.158  3424  3424 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-17 11:22:38.171   928  3529 I ActivityManager: Start proc 5497:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-17 11:22:38.201  5497  5497 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-17 11:22:38.201   928   945 D BluetoothHeadset: Proxy object connected
,11-17 11:22:38.204  3656  3856 D BluetoothHeadset: Proxy object connected
,11-17 11:22:38.205   928   945 D BluetoothHeadset: Proxy object connected
11-17 11:22:38.205   928   945 D BluetoothHeadset: Proxy object connected
,11-17 11:22:38.219  3019  3031 D BluetoothHeadset: Proxy object connected
11-17 11:22:38.220  3019  3019 D HeadsetProfile: Bluetooth service connected
,11-17 11:22:38.385  5497  5497 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at java.io.File.exists(File.java:361)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-17 11:22:38.385  5497  5497 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-17 11:22:38.385  5497  5497 D StrictMode: StrictMode policy violation; ~duration=118 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-17 11:22:38.385  5497  5497 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-17 11:22:38.386  5497  5497 D StrictMode: StrictMode policy violation; ~duration=117 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.r.e.b(PG:170)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-17 11:22:38.386  5497  5497 D StrictMode: StrictMode policy violation; ~duration=114 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.r.k.d(PG:583)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.r.e.b(PG:170)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-17 11:22:38.386  5497  5497 D StrictMode: StrictMode policy violation; ~duration=83 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at java.io.File.exists(File.java:361)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-17 11:22:38.386  5497  5497 D StrictMode: StrictMode policy violation; ~duration=82 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at java.io.File.exists(File.java:361)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-17 11:22:38.386  5497  5497 D StrictMode: StrictMode policy violation; ~duration=81 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-17 11:22:38.386  5497  5497 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-17 11:22:38.413  5472  5472 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-17 11:22:38.419   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f28369:true
,11-17 11:22:38.422  3424  3424 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-17 11:22:38.428  5472  5472 D LocalBluetoothProfileManager: Adding local A2DP profile
11-17 11:22:38.430  3019  3019 D BluetoothPbap: Proxy object connected
11-17 11:22:38.430  3019  3019 D PbapServerProfile: Bluetooth service connected
11-17 11:22:38.434  5472  5472 D LocalBluetoothProfileManager: Adding local HEADSET profile
11-17 11:22:38.441  5425  5526 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-17 11:22:38.456   535   535 I ServiceManager: Waiting for service AtCmdFwd...
11-17 11:22:38.457  5425  5530 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-17 11:22:38.459  5425  5530 I BtOppRfcommListener: Accept thread started.
,11-17 11:22:38.464  5472  5472 D LocalBluetoothProfileManager: Adding local MAP profile
,11-17 11:22:38.465  5472  5472 D BluetoothMap: Create BluetoothMap proxy object
,11-17 11:22:38.478  5472  5472 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-17 11:22:38.482  5472  5472 D DockEventReceiver: finishStartingService: stopping service
,11-17 11:22:38.482  5472  5472 D BluetoothA2dp: Proxy object connected
,11-17 11:22:38.485  5472  5472 D BluetoothInputDevice: Proxy object connected
,11-17 11:22:38.486  5472  5472 D HidProfile: Bluetooth service connected
,11-17 11:22:38.487  5472  5472 D BluetoothPan: BluetoothPAN Proxy object connected
,11-17 11:22:38.488  5472  5472 D PanProfile: Bluetooth service connected
,11-17 11:22:38.488  5472  5472 D BluetoothMap: Proxy object connected
11-17 11:22:38.488  5472  5472 D MapProfile: Bluetooth service connected
11-17 11:22:38.488  5472  5472 D BluetoothMap: getConnectedDevices()
,11-17 11:22:38.490  5472  5472 D BluetoothPbap: Proxy object connected
11-17 11:22:38.491  5472  5472 D PbapServerProfile: Bluetooth service connected
,11-17 11:22:38.492   928  3438 I ActivityManager: Killing 5110:org.codeaurora.ims/1001 (adj 15): empty #17
,11-17 11:22:38.538  5472  5484 D BluetoothHeadset: Proxy object connected
,11-17 11:22:38.539  5472  5472 D HeadsetProfile: Bluetooth service connected
,11-17 11:22:38.659  5497  5516 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-17 11:22:38.672   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4ab364d:true
,11-17 11:22:39.457   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 11:22:39.630  5449  5449 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-17 11:22:39.634  5449  5449 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-17 11:22:39.640  5449  5449 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-17 11:22:39.720   928  2861 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-17 11:22:39.722   928  2861 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-17 11:22:39.722   928  2861 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-17 11:22:39.737   928  2861 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-17 11:22:39.773   928  2861 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-17 11:22:39.776  5449  5449 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-17 11:22:40.202  5449  5449 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-17 11:22:40.228  5449  5449 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
11-17 11:22:40.228  5449  5449 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-17 11:22:40.236   928  2861 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-17 11:22:40.236   928  2861 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-17 11:22:40.236   928  2873 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-17 11:22:40.248   928  2861 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-17 11:22:40.256   507   922 D CommandListener: Setting iface cfg
,11-17 11:22:40.263   928  2861 D WifiStateMachine: Start Dhcp Watchdog 1
,11-17 11:22:40.269   928  5539 D DhcpClient: Receive thread started
,11-17 11:22:40.273   928  2861 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-17 11:22:40.274   928  2873 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-17 11:22:40.274   928  2873 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,11-17 11:22:40.354   928  2861 E native  : do suspend false
,11-17 11:22:40.367   928  5538 D DhcpClient: Broadcasting DHCPDISCOVER
,11-17 11:22:40.387   928  5539 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 164853, domain null
,11-17 11:22:40.389   928  5538 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 164853 seconds
,11-17 11:22:40.392   928  5538 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-17 11:22:40.394   389   389 I MSM-irqbalance: Discovered a new IRQ: 146
,11-17 11:22:40.397   389   389 I MSM-irqbalance: Discovered a new IRQ: 271
,11-17 11:22:40.397   389   389 I MSM-irqbalance: Discovered a new IRQ: 304
,11-17 11:22:40.407   928  5539 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-17 11:22:40.408   928  5538 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-17 11:22:40.412   507   922 D CommandListener: Setting iface cfg
,11-17 11:22:40.417   928  2861 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-17 11:22:40.421   928  5538 D DhcpClient: Scheduling renewal in 86399s
,11-17 11:22:40.431   928  2861 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-17 11:22:40.431   928  2861 D WifiConfigStore: No blacklist allowed without epno enabled
,11-17 11:22:40.433   928  2873 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-17 11:22:40.437   928  2861 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-17 11:22:40.440   928  2873 D ConnectivityService: Adding iface wlan0 to network 100
,11-17 11:22:40.457   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 11:22:40.484   928  2873 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-17 11:22:40.484   928  2873 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 100
,11-17 11:22:40.487   928  2873 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 100
,11-17 11:22:40.490   928  2873 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 100
,11-17 11:22:40.492   928  2873 D ConnectivityService: Setting Dns servers for network 100 to [/192.168.1.1]
,11-17 11:22:40.500   928  2873 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-17 11:22:40.506   928  2873 D ConnectivityService: scheduleUnvalidatedPrompt 100
,11-17 11:22:40.506   928  2873 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 100]
11-17 11:22:40.506   928  2873 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 100]
,11-17 11:22:40.506   928  2873 D ConnectivityService:    accepting network in place of null
11-17 11:22:40.506   928  2861 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,11-17 11:22:40.506   928  2861 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-17 11:22:40.507   928  2873 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-17 11:22:40.516   928  5537 D NetlinkSocketObserver: NeighborEvent{elapsedMs=130614, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-17 11:22:40.528   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-17 11:22:40.549   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-17 11:22:40.551   928  2873 D ConnectivityService: Setting tx/rx TCP buffers to 524288,2097152,4194304,262144,524288,1048576
,11-17 11:22:40.557   928  2873 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
,11-17 11:22:40.557   928  2873 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-17 11:22:40.557  3603  3771 W QCNEJ   : |CORE| network available: 100
11-17 11:22:40.558   928  2873 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 100]
,11-17 11:22:40.560   928   945 D Tethering: MasterInitialState.processMessage what=3
11-17 11:22:40.560  3603  3771 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
,11-17 11:22:40.562  3603  3771 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-17 11:22:40.563  3603  3771 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-17 11:22:40.566  5123  5123 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@719cc53 and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,11-17 11:22:40.575  5123  5123 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,11-17 11:22:40.581  4898  4921 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-17 11:22:40.581  4898  4921 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-17 11:22:40.581  4898  4921 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-17 11:22:40.581  4898  4921 E SarControlService: no key has been found,reset the power
,11-17 11:22:40.581  4898  4935 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-17 11:22:40.582  4898  4935 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-17 11:22:40.583  4898  4935 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-17 11:22:40.585  4923  4923 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-17 11:22:40.585  4923  4923 D QcrilMsgTunnelSocket: [1000] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-17 11:22:40.589   928  5536 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
11-17 11:22:40.590  3792  3792 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-17 11:22:40.593  3541  3541 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-17 11:22:40.598  3541  3541 D SystemUpdateService: onCreate
,11-17 11:22:40.599  4898  4935 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-17 11:22:40.601  4923  4937 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@95f0491 HexData = [00000000e803000000000000ffffffff]
11-17 11:22:40.601  4923  4937 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-17 11:22:40.601  4923  4937 D QcrilMsgTunnelSocket: [1000] < OEM_HOOK_RAW [null]
11-17 11:22:40.602  4923  4923 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-17 11:22:40.602  4898  4909 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-17 11:22:40.600  4898  4935 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-17 11:22:40.606  4898  4935 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
,11-17 11:22:40.607  4923  4923 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-17 11:22:40.607  4923  4923 D QcrilMsgTunnelSocket: [1001] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-17 11:22:40.608   928  5548 D GpsLocationProvider: NTP server returned: 1479399760399 (Thu Nov 17 11:22:40 EST 2016) reference: 130708 certainty: 6 system time offset: -209
11-17 11:22:40.609   928  3588 D AlarmManagerService: Setting time of day to sec=1479399760
11-17 11:22:40.609  3541  3541 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-17 11:22:40.399   928  3588 W AlarmManagerService: Unable to set rtc to 1479399760: Invalid argument
11-17 11:22:40.399  4923  4937 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@95f0491 HexData = [00000000e903000000000000ffffffff]
11-17 11:22:40.399  4923  4937 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-17 11:22:40.399  4923  4937 D QcrilMsgTunnelSocket: [1001] < OEM_HOOK_RAW [null]
11-17 11:22:40.400  4923  4923 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-17 11:22:40.401  4898  4908 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-17 11:22:40.407   928  3563 E LocSvc_eng: E/Callback function for request xtra is NULL
,11-17 11:22:40.427  3541  5556 I SystemUpdateService: active receiver: enabled
,11-17 11:22:40.439  3541  3541 E MDM     : [1] SitrepService.a: No Google accounts; deferring server state update.
,11-17 11:22:40.446  3541  5556 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-17 11:22:40.451   928  5536 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 17 Nov 2016 16:22:40 GMT], X-Android-Received-Millis=[1479399760450], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479399760405]}
,11-17 11:22:40.451   928  2873 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-17 11:22:40.452   928  2873 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation  passed
11-17 11:22:40.452   928  2873 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-17 11:22:40.453   928  2873 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-17 11:22:40.456  3541  5564 I iu.SyncManager: SYNC; picasa accounts
,11-17 11:22:40.459  3541  3541 D NetworkLogImpl: Loaded NetworkSpeedPredictor
,11-17 11:22:40.463  3541  3541 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-17 11:22:40.466  3541  5556 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-17 11:22:40.466  3541  5556 I SystemUpdateService: now status is 0 (complete)
11-17 11:22:40.466  3541  5556 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-17 11:22:40.466  3541  5556 I SystemUpdateService: file has been verified
,11-17 11:22:40.466  3541  5556 I SystemUpdateService: OTA package size = 21989297
,11-17 11:22:40.478  3541  5564 I iu.UploadsManager: num queued entries: 0
,11-17 11:22:40.479  3541  5564 I iu.UploadsManager: num updated entries: 0
,11-17 11:22:40.485  3541  5556 I SystemUpdateService: showing system update notification
,11-17 11:22:40.487  3541  3541 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-17 11:22:40.488  3541  3541 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-17 11:22:40.491  3541  5564 I iu.SyncManager: NEXT; no task
,11-17 11:22:40.500   928  3527 I ActivityManager: Start proc 5567:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-17 11:22:40.516  3541  3541 D SystemUpdateService: onDestroy
,11-17 11:22:40.544  5567  5567 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-17 11:22:40.546  5567  5567 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-17 11:22:40.552  5567  5567 D SprintDMHelper: simOperator: 
,11-17 11:22:40.552  5567  5567 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-17 11:22:40.573   928  3438 I ActivityManager: Start proc 5579:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
11-17 11:22:40.576   928  3438 I ActivityManager: Killing 4829:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-17 11:22:40.823   928  3680 I ActivityManager: Start proc 5597:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,11-17 11:22:40.860  5597  5597 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,11-17 11:22:40.920  4872  5596 I Babel   : connection state changed from UNKNOWN to CONNECTED
,11-17 11:22:40.924   928   939 I ActivityManager: Killing 5123:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-17 11:22:41.148   928  3438 I ActivityManager: Killing 4550:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-17 11:22:41.247   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 11:22:41.901  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-17 11:22:41.902  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ad88bf6 added. We now have 4 listener(s)
11-17 11:22:41.902  5374  5420 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-17 11:22:41.909  5374  5420 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-17 11:22:41.915  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-17 11:22:41.916  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ad88bf6 removed from the list
11-17 11:22:41.916  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
11-17 11:22:41.917  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-17 11:22:41.917  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f1cbbf7 added. We now have 4 listener(s)
11-17 11:22:41.917  5374  5420 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-17 11:22:41.921  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-17 11:22:41.921  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@f1cbbf7 removed from the list
11-17 11:22:41.921  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
11-17 11:22:41.922  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-17 11:22:41.922  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@88b7a64 added. We now have 4 listener(s)
11-17 11:22:41.922  5374  5420 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-17 11:22:41.925   928   939 D WifiService: setWifiEnabled: false pid=5374, uid=10077
11-17 11:22:41.925   928   939 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-17 11:22:41.927   928  2861 D WifiStateMachine: WifiStateMachine: Leaving Connected state,
11-17 11:22:41.927   928  2861 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-17 11:22:41.927   928  2861 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-17 11:22:41.928   928  2861 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-17 11:22:41.931  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-17 11:22:41.931  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-17 11:22:41.932  5425  5437 D BluetoothAdapterState: Current state: ON, message: 23
11-17 11:22:41.932  5425  5437 D BluetoothAdapterProperties: Setting state to 13
11-17 11:22:41.932  5425  5437 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-17 11:22:41.933  5425  5437 D BluetoothAdapterProperties: onBluetoothDisable()
11-17 11:22:41.934  5425  5437 I BluetoothAdapterState: Entering PendingCommandState
,11-17 11:22:41.936  5425  5425 D BluetoothMapService: onReceive
11-17 11:22:41.937  5425  5441 D BluetoothAdapterProperties: Scan Mode:20
,11-17 11:22:41.938  5425  5437 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-17 11:22:41.936  5425  5425 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-17 11:22:41.940  5425  5425 D BluetoothMapService: STATE_TURNING_OFF
11-17 11:22:41.941  5472  5472 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-17 11:22:41.942  5425  5425 D HeadsetService: Received stop request...Stopping profile...
,11-17 11:22:41.942   928  5538 D DhcpClient: Clearing IP address
11-17 11:22:41.942   507   922 D CommandListener: Clearing all IP addresses on wlan0
,11-17 11:22:41.944  5374  5420 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-17 11:22:41.944  5374  5420 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-17 11:22:41.944  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-17 11:22:41.944  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-17 11:22:41.944  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-17 11:22:41.944  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-17 11:22:41.944  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-17 11:22:41.944  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-17 11:22:41.944  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-17 11:22:41.944  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-17 11:22:41.945  5374  5420 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-17 11:22:41.945  5374  5420 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-17 11:22:41.945  5374  5420 D io.jxcore.node.ConnectivityMonitor: start: OK
11-17 11:22:41.948  3019  3031 D BluetoothHeadset: Proxy object disconnected
11-17 11:22:41.948  5425  5425 D BluetoothMapService: MAP Service closeService in
11-17 11:22:41.948  5472  5484 D BluetoothHeadset: Proxy object disconnected
11-17 11:22:41.948  5425  5425 D BluetoothMapMasInstance0: MAP Service shutdown
11-17 11:22:41.948  5425  5425 D ObexServerSockets0: shutdown(block = true)
11-17 11:22:41.948   928   928 D BluetoothHeadset: Proxy object disconnected
,11-17 11:22:41.949   507   922 D CommandListener: Setting iface cfg
11-17 11:22:41.949  3656  3856 D BluetoothHeadset: Proxy object disconnected
11-17 11:22:41.949   928   928 D BluetoothHeadset: Proxy object disconnected
11-17 11:22:41.949   928   928 D BluetoothHeadset: Proxy object disconnected
11-17 11:22:41.950  5425  5425 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-17 11:22:41.950  5425  5494 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-17 11:22:41.950  5425  5425 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-17 11:22:41.950  5425  5469 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-17 11:22:41.950  5425  5495 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-17 11:22:41.951  5472  5472 D DockEventReceiver: finishStartingService: stopping service
11-17 11:22:41.951  5374  5374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-17 11:22:41.952  5425  5425 I BtOppRfcommListener: stopping Accept Thread
11-17 11:22:41.953  5425  5530 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-17 11:22:41.953  5425  5530 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-17 11:22:41.953  5472  5472 D HeadsetProfile: Bluetooth service disconnected
,11-17 11:22:41.954  5374  5374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-17 11:22:41.956  5425  5425 D A2dpService: Received stop request...Stopping profile...
11-17 11:22:41.956  5425  5486 D A2dpStateMachine: Exit Disconnected: -1
11-17 11:22:41.957  3019  3019 D HeadsetProfile: Bluetooth service disconnected
11-17 11:22:41.958  5374  5374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-17 11:22:41.959   928   928 D BluetoothA2dp: Proxy object disconnected
11-17 11:22:41.960  3019  3019 D BluetoothA2dp: Proxy object disconnected
11-17 11:22:41.960  5425  5425 D HidService: Received stop request...Stopping profile...
11-17 11:22:41.960  5472  5472 D BluetoothA2dp: Proxy object disconnected
11-17 11:22:41.960  5425  5425 D HidService: Stopping Bluetooth HidService
11-17 11:22:41.961  5472  5472 D BluetoothInputDevice: Proxy object disconnected
,11-17 11:22:41.962  3424  5592 V NativeCrypto: Read error: ssl=0x7f9eb44680: I/O error during system call, Connection timed out
,11-17 11:22:41.962  5472  5472 D HidProfile: Bluetooth service disconnected
,11-17 11:22:41.962  3019  3019 D BluetoothInputDevice: Proxy object disconnected
11-17 11:22:41.962  3019  3019 D HidProfile: Bluetooth service disconnected
11-17 11:22:41.962  5425  5425 D HealthService: Received stop request...Stopping profile...
11-17 11:22:41.962  5374  5374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-17 11:22:41.963  5425  5425 V BluetoothAdapterState: isTurningOff()=true
,11-17 11:22:41.963  5425  5425 V BluetoothAdapterState: isTurningOn()=false
11-17 11:22:41.963  5425  5425 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:22:41.963  5425  5425 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:22:41.963  3424  5592 V NativeCrypto: SSL shutdown failed: ssl=0x7f9eb44680: I/O error during system call, Broken pipe
11-17 11:22:41.966   928  3068 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-17 11:22:41.967  3424  3424 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-17 11:22:41.967   928  2873 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-17 11:22:41.967   928  2873 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-17 11:22:41.967   928  5536 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-17 11:22:41.968   928  5536 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Checking http://connectivitycheck.gstatic.com/generate_204 on <unknown ssid>, connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
11-17 11:22:41.973   533   533 E Parcel  : Reading a NULL string not supported here.
,11-17 11:22:41.976   928  2873 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
,11-17 11:22:41.977   928   928 D RttService: SCAN_AVAILABLE : 1
11-17 11:22:41.977   928  5536 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:400d:802::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
11-17 11:22:41.978   928  2953 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-17 11:22:41.978  3603  3771 W QCNEJ   : |CORE| network lost: 100
11-17 11:22:41.978  5425  5425 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-17 11:22:41.978  3603  3771 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-17 11:22:41.978  5425  5425 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-17 11:22:41.979  5425  5450 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-17 11:22:41.979  5425  5450 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-17 11:22:41.979  5425  5450 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-17 11:22:41.979   928  5539 D DhcpClient: Receive thread stopped
11-17 11:22:41.979  5425  5441 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-17 11:22:41.979  5425  5441 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-17 11:22:41.980  5425  5425 D PanService: Received stop request...Stopping profile...
11-17 11:22:41.980  5472  5472 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-17 11:22:41.980  5472  5472 D PanProfile: Bluetooth service disconnected
11-17 11:22:41.981  5425  5425 D BluetoothMapService: Received stop request...Stopping profile...
11-17 11:22:41.981  5425  5425 D BluetoothMapService: stop()
11-17 11:22:41.982  5425  5425 D BluetoothMapAppObserver: deinitObservers()
11-17 11:22:41.982  5425  5425 D BluetoothMapAppObserver: removeReceiver()
,11-17 11:22:41.983  5425  5425 D SapService: Received stop request...Stopping profile...
,11-17 11:22:41.983  5425  5425 V SapService: stop()
11-17 11:22:41.986  5425  5425 V BluetoothAdapterState: isTurningOff()=true
11-17 11:22:41.986  5425  5425 V BluetoothAdapterState: isTurningOn()=false
11-17 11:22:41.986  5425  5425 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:22:41.986  5425  5425 V BluetoothAdapterState: isBleTurningOff()=false
,11-17 11:22:41.989   928  2861 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-17 11:22:41.990  3019  3019 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-17 11:22:41.990  5425  5441 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-17 11:22:41.990  5425  5450 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-17 11:22:41.990  5425  5425 V BluetoothAdapterState: isTurningOff()=true
11-17 11:22:41.990  5425  5425 V BluetoothAdapterState: isTurningOn()=false
11-17 11:22:41.990  5425  5425 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:22:41.990  5425  5450 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-17 11:22:41.990  5425  5425 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:22:41.990  3019  3019 D PanProfile: Bluetooth service disconnected
11-17 11:22:41.990  5425  5450 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-17 11:22:41.990  5425  5450 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-17 11:22:41.990  5472  5472 D BluetoothMap: Proxy object disconnected
11-17 11:22:41.990  5425  5450 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-17 11:22:41.990  5425  5425 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-17 11:22:41.990  5472  5472 D MapProfile: Bluetooth service disconnected
,11-17 11:22:41.990  3019  3019 D BluetoothMap: Proxy object disconnected
11-17 11:22:41.990  5425  5450 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-17 11:22:41.990  3019  3019 D MapProfile: Bluetooth service disconnected
11-17 11:22:41.990  5425  5425 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-17 11:22:41.991  5425  5441 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-17 11:22:41.991  5425  5425 V BluetoothAdapterState: isTurningOff()=true
11-17 11:22:41.991  5425  5425 V BluetoothAdapterState: isTurningOn()=false
11-17 11:22:41.991  5425  5425 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:22:41.991  5425  5425 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:22:41.992  5425  5425 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-17 11:22:41.992  5425  5441 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-17 11:22:41.992  5425  5425 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-17 11:22:41.995  5425  5425 V BluetoothAdapterState: isTurningOff()=true
11-17 11:22:41.995  5425  5425 V BluetoothAdapterState: isTurningOn()=false
11-17 11:22:41.995  5425  5425 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:22:41.995  5425  5425 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:22:41.995  5425  5425 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-17 11:22:41.996  5425  5425 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-17 11:22:41.996  5425  5425 D BluetoothMapService: MAP Service closeService in
11-17 11:22:41.997  5425  5425 V BluetoothAdapterState: isTurningOff()=true
11-17 11:22:41.997  5425  5425 V BluetoothAdapterState: isTurningOn()=false
11-17 11:22:41.997  5425  5425 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:22:41.997  5425  5425 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:22:41.997  5425  5425 D BluetoothMapService: cleanup()
11-17 11:22:41.997  5425  5425 D BluetoothMapService: MAP Service closeService in
11-17 11:22:41.997  5425  5425 V BluetoothAdapterState: isTurningOff()=true
,11-17 11:22:41.997  5425  5425 V BluetoothAdapterState: isTurningOn()=false
11-17 11:22:41.997  5425  5425 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:22:41.997  5425  5425 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:22:41.997  5425  5437 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-17 11:22:41.997  5425  5437 D BluetoothAdapterProperties: Setting state to 15
11-17 11:22:41.998  5425  5437 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-17 11:22:41.998  5425  5437 I BluetoothAdapterState: Entering BleOnState
11-17 11:22:41.998  5472  5483 D BluetoothPan: onBluetoothStateChange on: false
11-17 11:22:42.000  5472  5484 D BluetoothPbap: onBluetoothStateChange: up=false
11-17 11:22:42.000   928  2861 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-17 11:22:42.000   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-17 11:22:42.000  3019  3031 D BluetoothMap: onBluetoothStateChange: up=false
11-17 11:22:42.001  5472  5472 D BluetoothPbap: Proxy object disconnected
11-17 11:22:42.001  5472  5472 D PbapServerProfile: Bluetooth service disconnected
11-17 11:22:42.001  3019  3840 D BluetoothA2dp: onBluetoothStateChange: up=false
11-17 11:22:42.002  3019  3031 D BluetoothPbap: onBluetoothStateChange: up=false
,11-17 11:22:42.002  3019  3840 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-17 11:22:42.003  5472  5483 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-17 11:22:42.009  3656  3685 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-17 11:22:42.010  5472  5484 D BluetoothHeadset: onBluetoothStateChange: up=false
11-17 11:22:42.010   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
11-17 11:22:42.010  5472  5483 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-17 11:22:42.010   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-17 11:22:42.011  5472  5484 D BluetoothMap: onBluetoothStateChange: up=false
11-17 11:22:42.011  3019  3030 D BluetoothPan: onBluetoothStateChange on: false
11-17 11:22:42.012  3019  3031 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-17 11:22:42.012   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-17 11:22:42.012   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-17 11:22:42.013  5425  5437 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-17 11:22:42.013  5425  5437 D BluetoothAdapterProperties: Setting state to 16
11-17 11:22:42.013  5425  5437 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-17 11:22:42.013  5425  5437 D BluetoothAdapterProperties: onBleDisable
11-17 11:22:42.013  5425  5437 I BluetoothAdapterState: Entering PendingCommandState
11-17 11:22:42.014  5425  5438 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-17 11:22:42.015  5425  5441 D BluetoothAdapterProperties: Scan Mode:20
11-17 11:22:42.015  5425  5450 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-17 11:22:42.015  5425  5450 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-17 11:22:42.018  5374  5374 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-17 11:22:42.018  5374  5374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-17 11:22:42.018  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-17 11:22:42.018  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-17 11:22:42.018  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-17 11:22:42.018  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-17 11:22:42.018  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-17 11:22:42.018  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-17 11:22:42.018  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-17 11:22:42.018  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-17 11:22:42.019  5374  5374 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-17 11:22:42.019  5374  5374 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-17 11:22:42.020  5472  5472 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-17 11:22:42.021  5374  5374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-17 11:22:42.028  3424  3424 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-17 11:22:42.028  5472  5472 D DockEventReceiver: finishStartingService: stopping service
,11-17 11:22:42.038   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-17 11:22:42.039   507   922 D CommandListener: Clearing all IP addresses on wlan0
,11-17 11:22:42.040   928  2873 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-17 11:22:42.040   928  2873 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-17 11:22:42.041   928  2861 D DhcpClient: doQuit
11-17 11:22:42.041   928  2861 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-17 11:22:42.041   928  5538 D DhcpClient: onQuitting
,11-17 11:22:42.042  5449  5449 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-17 11:22:42.043   928   945 D Tethering: MasterInitialState.processMessage what=3
,11-17 11:22:42.046  3792  3792 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-17 11:22:42.047  5374  5374 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-17 11:22:42.047  5374  5374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-17 11:22:42.047  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-17 11:22:42.047  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-17 11:22:42.047  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-17 11:22:42.047  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-17 11:22:42.047  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-17 11:22:42.047  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-17 11:22:42.047  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-17 11:22:42.047  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-17 11:22:42.048  5374  5374 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-17 11:22:42.048  5374  5374 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-17 11:22:42.049  5374  5374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-17 11:22:42.052  3541  3541 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-17 11:22:42.052  4898  4921 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-17 11:22:42.052  4898  4921 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-17 11:22:42.053  4898  4921 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-17 11:22:42.053  4898  4921 E SarControlService: no key has been found,reset the power
11-17 11:22:42.054  4898  4935 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-17 11:22:42.054  4898  4935 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-17 11:22:42.054  4898  4935 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-17 11:22:42.055  4923  4923 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-17 11:22:42.055  4923  4923 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-17 11:22:42.057  4898  4935 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-17 11:22:42.057  4898  4935 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-17 11:22:42.057  4898  4935 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-17 11:22:42.057  4923  4923 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-17 11:22:42.057  4923  4923 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-17 11:22:42.060  3541  3541 D SystemUpdateService: onCreate
,11-17 11:22:42.062  4923  4937 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@95f0491 HexData = [00000000ea03000000000000ffffffff]
,11-17 11:22:42.062  4923  4937 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-17 11:22:42.062  4923  4937 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-17 11:22:42.062  4923  4923 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-17 11:22:42.062  4898  4908 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-17 11:22:42.064  4923  4937 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@95f0491 HexData = [00000000eb03000000000000ffffffff]
11-17 11:22:42.065  4923  4937 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-17 11:22:42.065  4923  4937 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,11-17 11:22:42.065  4923  4923 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-17 11:22:42.065  4898  4909 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-17 11:22:42.066  3541  3541 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-17 11:22:42.069  5449  5449 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-17 11:22:42.073  3541  5629 I SystemUpdateService: active receiver: enabled
,11-17 11:22:42.073  5449  5449 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-17 11:22:42.076  3541  3541 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-17 11:22:42.081  3541  5564 I iu.UploadsManager: num queued entries: 0
,11-17 11:22:42.081  3541  5564 I iu.UploadsManager: num updated entries: 0
11-17 11:22:42.082  3541  5564 I iu.SyncManager: NEXT; no task
,11-17 11:22:42.084  3541  3541 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-17 11:22:42.086  3541  3541 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-17 11:22:42.088  5567  5567 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-17 11:22:42.090   507   922 E Netd    : netlink response contains error (No such file or directory)
,11-17 11:22:42.091   928  2873 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-17 11:22:42.091   928  2873 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-17 11:22:42.092  5567  5567 D SprintDMHelper: simOperator: 
11-17 11:22:42.092  5567  5567 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-17 11:22:42.102  3541  5629 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-17 11:22:42.104  4872  5633 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-17 11:22:42.107  3541  5629 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-17 11:22:42.107  3541  5629 I SystemUpdateService: now status is 0 (complete)
11-17 11:22:42.107  3541  5629 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-17 11:22:42.107  3541  5629 I SystemUpdateService: file has been verified
,11-17 11:22:42.112  5449  5449 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-17 11:22:42.113  3541  5629 I SystemUpdateService: OTA package size = 21989297
,11-17 11:22:42.120  5449  5449 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-17 11:22:42.122  3541  5629 I SystemUpdateService: showing system update notification
,11-17 11:22:42.135  3541  3541 D SystemUpdateService: onDestroy
,11-17 11:22:42.223  5425  5441 I bt_hci  : shut_down
,11-17 11:22:42.226   928  2861 D wifi    : In wifi stop Hal
,11-17 11:22:42.227   928  2861 D wifi    : halHandle = 0x7f8e3b62e0, mVM = 0x7fa4c0d140, mCls = 0x200f96
11-17 11:22:42.227   928  5448 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-17 11:22:42.227   928  5448 D WifiHAL : Got a signal to exit!!!
11-17 11:22:42.227   928  5448 I WifiHAL : Exit wifi_event_loop
11-17 11:22:42.228   928  2861 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-17 11:22:42.228   928  2861 E WifiHAL : Event processing terminated
,11-17 11:22:42.228   928  2861 D wifi    : In wifi cleaned up handler
11-17 11:22:42.228   928  2861 I WifiHAL : Internal cleanup completed
11-17 11:22:42.229  5374  5374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-17 11:22:42.230  3911  4081 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-17 11:22:42.231  4872  4872 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-17 11:22:42.231  5425  5445 D bt_hwcfg: hw_epilog_process
,11-17 11:22:42.231  5425  5445 I bt_vendor: low_power_mode_cb
,11-17 11:22:42.234  5425  5445 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-17 11:22:42.234  5425  5445 I bt_vendor: epilog_cb
11-17 11:22:42.234  5425  5445 I bt_hci  : epilog_finished_callback
11-17 11:22:42.236  5425  5441 I bt_hci_h4: hal_close
,11-17 11:22:42.237  5425  5441 I bt_userial_vendor: device fd = 54 close
,11-17 11:22:42.247   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 11:22:42.252   928  5448 D wifi    : set interface wlan0 flags (DOWN)
,11-17 11:22:42.252   928  2861 D WifiNative-HAL: HAL event thread stopped successfully
,11-17 11:22:42.344  5425  5438 D bt_stack_manager: event_shut_down_stack finished.
,11-17 11:22:42.345  5425  5437 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-17 11:22:42.347  5425  5437 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-17 11:22:42.347  5425  5425 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-17 11:22:42.348  5425  5425 D BtGatt.GattService: Received stop request...Stopping profile...
,11-17 11:22:42.348  5425  5425 D BtGatt.GattService: stop()
11-17 11:22:42.348  5425  5425 D BtGatt.AdvertiseManager: advertise clients cleared
,11-17 11:22:42.350  5425  5425 V BluetoothAdapterState: isTurningOff()=false
11-17 11:22:42.350  5425  5425 V BluetoothAdapterState: isTurningOn()=false
11-17 11:22:42.350  5425  5425 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:22:42.350  5425  5425 V BluetoothAdapterState: isBleTurningOff()=true
11-17 11:22:42.350  5425  5437 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-17 11:22:42.350  5425  5437 D BluetoothAdapterProperties: Setting state to 10
11-17 11:22:42.351  5425  5437 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,11-17 11:22:42.351  5425  5437 I BluetoothAdapterState: Entering OffState
,11-17 11:22:42.353   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-17 11:22:42.361  5425  5425 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-17 11:22:42.361  5425  5425 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-17 11:22:42.361  5425  5425 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-17 11:22:42.363  5425  5438 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-17 11:22:42.366  5425  5425 I art     : System.exit called, status: 0
11-17 11:22:42.367  5425  5425 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-17 11:22:42.389   928   938 I ActivityManager: Process com.android.bluetooth (pid 5425) has died
,11-17 11:22:42.455   928   945 D Tethering: InitialState.processMessage what=4
,11-17 11:22:42.458   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-17 11:22:43.248   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-17 11:22:46.948   928  3529 D WifiService: setWifiEnabled: true pid=5374, uid=10077
,11-17 11:22:46.948   928  3529 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-17 11:22:46.956   507   922 D SoftapController: Softap fwReload - Ok
,11-17 11:22:46.962   507   922 D CommandListener: Setting iface cfg
,11-17 11:22:46.963   507   922 D CommandListener: Trying to bring down wlan0
11-17 11:22:46.965   507   922 D CommandListener: Clearing all IP addresses on wlan0
,11-17 11:22:46.971   928  2861 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-17 11:22:47.578   928  2861 D wifi    : set interface wlan0 flags (UP)
,11-17 11:22:47.582   928  2861 I WifiHAL : Initializing wifi
11-17 11:22:47.582   928  2861 I WifiHAL : Creating socket
11-17 11:22:47.587   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
11-17 11:22:47.590   928  2861 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-17 11:22:47.590   928  2861 D wifi    : Did set static halHandle = 0x7f8e3b62e0
,11-17 11:22:47.590   928  2861 D wifi    : halHandle = 0x7f8e3b62e0, mVM = 0x7fa4c0d140, mCls = 0x101862
11-17 11:22:47.590   928  2861 D wifi    : array field set
11-17 11:22:47.591   928  2861 I WifiNative-HAL: interface[0] = wlan0
,11-17 11:22:47.593   928  5637 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547847103200
11-17 11:22:47.593   928  5637 D wifi    : waitForHalEvents called, vm = 0x7fa4c0d140, obj = 0x101862, env = 0x7f885b4c80
,11-17 11:22:47.653  5638  5638 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-17 11:22:47.675  5638  5638 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-17 11:22:47.684  5638  5638 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-17 11:22:47.684  5638  5638 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-17 11:22:47.694   928  2861 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-17 11:22:47.707  5374  5374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-17 11:22:47.709   928  2861 D WifiConfigStore: Loading config and enabling all networks 
,11-17 11:22:47.710  5374  5374 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-17 11:22:47.710  5374  5374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-17 11:22:47.710  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-17 11:22:47.710  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-17 11:22:47.710  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-17 11:22:47.710  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-17 11:22:47.710  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-17 11:22:47.710  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-17 11:22:47.710  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-17 11:22:47.710  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-17 11:22:47.710  5374  5374 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-17 11:22:47.710  5374  5374 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-17 11:22:47.720   928  2861 D WifiConfigStore: loaded 0 passpoint configs
,11-17 11:22:47.720   928  2861 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
11-17 11:22:47.720   928  2861 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-17 11:22:47.721   928  2861 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
11-17 11:22:47.722   928  2861 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-17 11:22:47.722   928  2861 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
,11-17 11:22:47.723   928  2861 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-17 11:22:47.723   928  2861 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
11-17 11:22:47.726  4872  4872 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-17 11:22:47.726   928  2861 D WifiNative-HAL: Setting external_sim to 1
,11-17 11:22:47.727   928  2861 D wifi    : setting dfs flag to true, 0x7f8b499b80
,11-17 11:22:47.728   928  2861 D WifiStateMachine: Setting OUI to DA-A1-19
,11-17 11:22:47.728   928  2861 D wifi    : setting scan oui 0x7f8b499b80
11-17 11:22:47.728   928  2861 D WifiHAL : Sending mac address OUI
,11-17 11:22:47.732   928  2861 E native  : do suspend false
,11-17 11:22:47.739   928   928 D RttService: SCAN_AVAILABLE : 3
11-17 11:22:47.739   928  2861 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-17 11:22:47.739   507   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-17 11:22:47.740   928  2953 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-17 11:22:47.740   507   922 D CommandListener: Setting iface cfg
,11-17 11:22:47.745   928  2849 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '129 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 129 Failed to set address (No such device)'
11-17 11:22:47.745   928  2849 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-17 11:22:47.756   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=138067 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=12 mControllerEnergyUsed=45 }
,11-17 11:22:47.759   928  2849 D WifiNative-HAL: p2pGetDeviceAddress
,11-17 11:22:47.759   928  2849 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-17 11:22:48.302   928  2873 D ConnectivityService: handlePromptUnvalidated 100
,11-17 11:22:50.551   928  2842 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-17 11:22:50.599  3541  5643 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
,11-17 11:22:50.604  3541  5643 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,11-17 11:22:50.609  3792  5644 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
,11-17 11:22:50.636  3911  3911 V GmsNetworkLocationProvi: DISABLE
,11-17 11:22:50.643  3911  3911 I GCoreNlp: shouldConfirmNlp, NLP off. Ensuring opt-in disabled
,11-17 11:22:50.659  3541  4799 I Icing   : updateResources: need to parse f{com.google.android.gms}
,11-17 11:22:50.660  3792  5644 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 51 ms] updated apps [took 51 ms] 
,11-17 11:22:50.829  5638  5638 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-17 11:22:50.835  5638  5638 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-17 11:22:50.842  5638  5638 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-17 11:22:50.869   928  2861 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-17 11:22:50.870   928  2861 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-17 11:22:50.871   928  2861 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-17 11:22:50.882   928  2861 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-17 11:22:50.916   928  2861 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-17 11:22:50.917  5638  5638 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-17 11:22:51.333  5638  5638 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-17 11:22:51.365  5638  5638 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-17 11:22:51.366  5638  5638 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-17 11:22:51.373   928  2861 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-17 11:22:51.373   928  2861 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-17 11:22:51.374   928  2873 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-17 11:22:51.393   928  2861 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-17 11:22:51.403   507   922 D CommandListener: Setting iface cfg
,11-17 11:22:51.408   928  2861 D WifiStateMachine: Start Dhcp Watchdog 2
,11-17 11:22:51.414   928  5651 D DhcpClient: Receive thread started
,11-17 11:22:51.420   928  2873 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-17 11:22:51.420   928  2861 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-17 11:22:51.420   928  2873 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-17 11:22:51.501   928  2861 E native  : do suspend false
,11-17 11:22:51.515   928  5650 D DhcpClient: Broadcasting DHCPDISCOVER
,11-17 11:22:51.534   928  5651 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172788, domain null
,11-17 11:22:51.535   928  5650 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172788 seconds
,11-17 11:22:51.538   928  5650 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-17 11:22:51.553   928  5651 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-17 11:22:51.554   928  5650 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-17 11:22:51.557   507   922 D CommandListener: Setting iface cfg
,11-17 11:22:51.561   928  2861 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-17 11:22:51.566   928  5650 D DhcpClient: Scheduling renewal in 86399s
,11-17 11:22:51.577   928  2861 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-17 11:22:51.578   928  2861 D WifiConfigStore: No blacklist allowed without epno enabled
11-17 11:22:51.578   928  2873 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-17 11:22:51.580   928  2861 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
11-17 11:22:51.584   928  2873 D ConnectivityService: Adding iface wlan0 to network 101
,11-17 11:22:51.623   928  2873 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-17 11:22:51.624   928  2873 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-17 11:22:51.626   928  2873 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-17 11:22:51.628   928  2873 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-17 11:22:51.630   928  2873 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-17 11:22:51.637   928  2873 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-17 11:22:51.641   928  2873 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-17 11:22:51.641   928  2873 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,11-17 11:22:51.642   928  2873 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
,11-17 11:22:51.642   928  2861 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-17 11:22:51.642   928  2873 D ConnectivityService:    accepting network in place of null
11-17 11:22:51.642   928  2861 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-17 11:22:51.642   928  2873 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -53]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-17 11:22:51.655   928  5649 D NetlinkSocketObserver: NeighborEvent{elapsedMs=141966, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-17 11:22:51.666   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-17 11:22:51.687   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-17 11:22:51.691   928  2873 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-17 11:22:51.691   928  2873 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-17 11:22:51.691  3603  3771 W QCNEJ   : |CORE| network available: 101
11-17 11:22:51.692   928  2873 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,11-17 11:22:51.693   928   945 D Tethering: MasterInitialState.processMessage what=3
11-17 11:22:51.694  3603  3771 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-17 11:22:51.695  3603  3771 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-17 11:22:51.696  3603  3771 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-17 11:22:51.699  5374  5374 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-17 11:22:51.699  5374  5374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-17 11:22:51.699  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-17 11:22:51.699  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-17 11:22:51.699  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-17 11:22:51.699  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-17 11:22:51.699  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-17 11:22:51.699  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-17 11:22:51.699  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-17 11:22:51.699  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-17 11:22:51.699  5374  5374 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-17 11:22:51.699  5374  5374 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-17 11:22:51.707  3792  3792 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-17 11:22:51.708  4898  4921 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-17 11:22:51.709  4898  4921 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-17 11:22:51.709  4898  4921 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-17 11:22:51.709  4898  4921 E SarControlService: no key has been found,reset the power
,11-17 11:22:51.709  4898  4935 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-17 11:22:51.709  4898  4935 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-17 11:22:51.709  4898  4935 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-17 11:22:51.710  4923  4923 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-17 11:22:51.710  4923  4923 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-17 11:22:51.712  4898  4935 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
,11-17 11:22:51.712  4898  4935 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-17 11:22:51.712  4898  4935 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-17 11:22:51.712  4923  4923 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-17 11:22:51.713  4923  4923 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-17 11:22:51.715  3541  3541 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-17 11:22:51.717  4923  4937 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@95f0491 HexData = [00000000ec03000000000000ffffffff]
11-17 11:22:51.717  4923  4937 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-17 11:22:51.717  4923  4937 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-17 11:22:51.717  4923  4923 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-17 11:22:51.718  4898  4908 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-17 11:22:51.718  3541  3541 D SystemUpdateService: onCreate
,11-17 11:22:51.720  4923  4937 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@95f0491 HexData = [00000000ed03000000000000ffffffff]
,11-17 11:22:51.720  4923  4937 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-17 11:22:51.720  4923  4937 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,11-17 11:22:51.721  4923  4923 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-17 11:22:51.721  4898  4909 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-17 11:22:51.722  3541  3541 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-17 11:22:51.725  3541  5661 I SystemUpdateService: active receiver: enabled
,11-17 11:22:51.728   928  5648 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.206,2a00:1450:400d:802::200e
,11-17 11:22:51.734  3541  5661 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-17 11:22:51.734  3541  3541 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-17 11:22:51.736  3541  5564 I iu.UploadsManager: num queued entries: 0
,11-17 11:22:51.736  3541  5661 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
11-17 11:22:51.736  3541  5564 I iu.UploadsManager: num updated entries: 0
11-17 11:22:51.736  3541  5661 I SystemUpdateService: now status is 0 (complete)
11-17 11:22:51.736  3541  5661 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-17 11:22:51.736  3541  5661 I SystemUpdateService: file has been verified
11-17 11:22:51.737  3541  5661 I SystemUpdateService: OTA package size = 21989297
11-17 11:22:51.737  3541  5564 I iu.SyncManager: NEXT; no task
,11-17 11:22:51.739  3541  5661 I SystemUpdateService: showing system update notification
,11-17 11:22:51.745  3541  3541 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-17 11:22:51.746  3541  3541 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-17 11:22:51.749  3541  3541 D SystemUpdateService: onDestroy
,11-17 11:22:51.750  5567  5567 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-17 11:22:51.755  5567  5567 D SprintDMHelper: simOperator: 
,11-17 11:22:51.755  5567  5567 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-17 11:22:51.773   928  5648 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 17 Nov 2016 16:22:51 GMT], X-Android-Received-Millis=[1479399771772], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479399771750]}
,11-17 11:22:51.773   928  2873 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-17 11:22:51.774   928  2873 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-17 11:22:51.774   928  2873 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-17 11:22:51.775   928  2873 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-17 11:22:51.850  4872  5666 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-17 11:22:51.954   928  3723 D WifiService: setWifiEnabled: false pid=5374, uid=10077
11-17 11:22:51.955   928  3723 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-17 11:22:51.961   928  2861 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-17 11:22:51.961   928  2861 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-17 11:22:51.961   928  2861 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-17 11:22:51.962   928  2861 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-17 11:22:51.976   928  5650 D DhcpClient: Clearing IP address
,11-17 11:22:51.977   507   922 D CommandListener: Clearing all IP addresses on wlan0
,11-17 11:22:51.979   507   922 D CommandListener: Setting iface cfg
,11-17 11:22:51.986   928  5651 D DhcpClient: Receive thread stopped
,11-17 11:22:51.992   928  2873 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-17 11:22:51.992   928  2873 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
11-17 11:22:51.996   533   533 E Parcel  : Reading a NULL string not supported here.
,11-17 11:22:52.000   928   928 D RttService: SCAN_AVAILABLE : 1
11-17 11:22:52.000  3424  5671 V NativeCrypto: Read error: ssl=0x7f9eb44680: I/O error during system call, Connection timed out
,11-17 11:22:52.001   928  2953 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-17 11:22:52.001   928  2873 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,11-17 11:22:52.002  3424  5671 V NativeCrypto: SSL shutdown failed: ssl=0x7f9eb44680: I/O error during system call, Broken pipe
11-17 11:22:52.002  3603  3771 W QCNEJ   : |CORE| network lost: 101
,11-17 11:22:52.003  3603  3771 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-17 11:22:52.010   928  2861 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-17 11:22:52.014   928  2861 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-17 11:22:52.029   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-17 11:22:52.049   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-17 11:22:52.050   928  2873 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-17 11:22:52.050   507   922 D CommandListener: Clearing all IP addresses on wlan0
11-17 11:22:52.050   928  2873 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-17 11:22:52.052   928   945 D Tethering: MasterInitialState.processMessage what=3
,11-17 11:22:52.054  5374  5374 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-17 11:22:52.054  5374  5374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-17 11:22:52.054  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-17 11:22:52.054  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-17 11:22:52.054  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-17 11:22:52.054  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-17 11:22:52.054  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-17 11:22:52.054  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-17 11:22:52.054  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-17 11:22:52.054  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-17 11:22:52.054  5374  5374 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-17 11:22:52.054  5374  5374 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-17 11:22:52.055   928  2861 D DhcpClient: doQuit
11-17 11:22:52.055   928  2861 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-17 11:22:52.056   928  5650 D DhcpClient: onQuitting
,11-17 11:22:52.056  5638  5638 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,11-17 11:22:52.058  3792  3792 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-17 11:22:52.060  5374  5374 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-17 11:22:52.060  5374  5374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-17 11:22:52.060  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-17 11:22:52.060  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-17 11:22:52.060  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-17 11:22:52.060  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-17 11:22:52.060  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-17 11:22:52.060  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-17 11:22:52.060  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-17 11:22:52.060  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-17 11:22:52.061  5374  5374 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-17 11:22:52.061  5374  5374 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-17 11:22:52.061  4898  4921 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-17 11:22:52.061  4898  4921 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
,11-17 11:22:52.061  4898  4921 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-17 11:22:52.062  4898  4921 E SarControlService: no key has been found,reset the power
11-17 11:22:52.063  4898  4935 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-17 11:22:52.063  4898  4935 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-17 11:22:52.063  4898  4935 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-17 11:22:52.064  3541  3541 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-17 11:22:52.064  4923  4923 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-17 11:22:52.064  4923  4923 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-17 11:22:52.065  4898  4935 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-17 11:22:52.065  4898  4935 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-17 11:22:52.065  4898  4935 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-17 11:22:52.066  4923  4923 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-17 11:22:52.066  4923  4923 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-17 11:22:52.066  3541  3541 D SystemUpdateService: onCreate
,11-17 11:22:52.069  3541  3541 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-17 11:22:52.071  4923  4937 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@95f0491 HexData = [00000000ee03000000000000ffffffff]
,11-17 11:22:52.072  3541  5680 I SystemUpdateService: active receiver: enabled
11-17 11:22:52.073  4923  4937 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-17 11:22:52.073  4923  4937 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-17 11:22:52.073  4923  4923 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-17 11:22:52.074  4898  4909 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-17 11:22:52.074  4923  4937 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@95f0491 HexData = [00000000ef03000000000000ffffffff]
11-17 11:22:52.074  4923  4937 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-17 11:22:52.074  4923  4937 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-17 11:22:52.076  5638  5638 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-17 11:22:52.076  4923  4923 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-17 11:22:52.076  4898  4908 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-17 11:22:52.078  3541  5680 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-17 11:22:52.079  3541  3541 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
11-17 11:22:52.080  3541  5680 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-17 11:22:52.080  3541  5680 I SystemUpdateService: now status is 0 (complete)
11-17 11:22:52.080  3541  5680 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-17 11:22:52.080  3541  5680 I SystemUpdateService: file has been verified
11-17 11:22:52.080  3541  5680 I SystemUpdateService: OTA package size = 21989297
11-17 11:22:52.080  3541  5564 I iu.UploadsManager: num queued entries: 0
11-17 11:22:52.081  3541  5564 I iu.UploadsManager: num updated entries: 0
11-17 11:22:52.082  5638  5638 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-17 11:22:52.083  3541  5680 I SystemUpdateService: showing system update notification
,11-17 11:22:52.085  3541  5564 I iu.SyncManager: NEXT; no task
,11-17 11:22:52.091  3541  3541 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-17 11:22:52.093  3541  3541 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-17 11:22:52.095  5567  5567 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-17 11:22:52.096  3541  3541 D SystemUpdateService: onDestroy
,11-17 11:22:52.115   507   922 E Netd    : netlink response contains error (No such file or directory)
,11-17 11:22:52.115  5638  5638 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
11-17 11:22:52.115   928  2873 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
,11-17 11:22:52.118  5567  5567 D SprintDMHelper: simOperator: 
11-17 11:22:52.118  5567  5567 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-17 11:22:52.123  5638  5638 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-17 11:22:52.132  4872  5684 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-17 11:22:52.228   928  2861 D wifi    : In wifi stop Hal
,11-17 11:22:52.228   928  2861 D wifi    : halHandle = 0x7f8e3b62e0, mVM = 0x7fa4c0d140, mCls = 0x101862
,11-17 11:22:52.228   928  5637 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-17 11:22:52.228   928  5637 D WifiHAL : Got a signal to exit!!!
11-17 11:22:52.228   928  5637 I WifiHAL : Exit wifi_event_loop
11-17 11:22:52.229   928  2861 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-17 11:22:52.230   928  2861 E WifiHAL : Event processing terminated
11-17 11:22:52.231   928  2861 D wifi    : In wifi cleaned up handler
11-17 11:22:52.231   928  2861 I WifiHAL : Internal cleanup completed
,11-17 11:22:52.232  4872  4872 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-17 11:22:52.234  3911  4081 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-17 11:22:52.234  5374  5374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-17 11:22:52.253   928  5637 D wifi    : set interface wlan0 flags (DOWN)
11-17 11:22:52.254   928  2861 D WifiNative-HAL: HAL event thread stopped successfully
,11-17 11:22:52.461   928   945 D Tethering: InitialState.processMessage what=4
,11-17 11:22:52.468   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-17 11:22:52.692   928  2873 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-17 11:22:53.249   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 11:22:54.250   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 11:22:55.251   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 11:22:56.252   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 11:22:56.998   928   945 I ActivityManager: Start proc 5687:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-17 11:22:57.097  5687  5687 D AdapterServiceConfig: Adding HeadsetService
,11-17 11:22:57.097  5687  5687 D AdapterServiceConfig: Adding A2dpService
,11-17 11:22:57.098  5687  5687 D AdapterServiceConfig: Adding HidService
11-17 11:22:57.098  5687  5687 D AdapterServiceConfig: Adding HealthService
,11-17 11:22:57.098  5687  5687 D AdapterServiceConfig: Adding PanService
11-17 11:22:57.098  5687  5687 D AdapterServiceConfig: Adding GattService
,11-17 11:22:57.098  5687  5687 D AdapterServiceConfig: Adding BluetoothMapService
11-17 11:22:57.099  5687  5687 D AdapterServiceConfig: Adding SapService
,11-17 11:22:57.114   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@bf7ccee:true
,11-17 11:22:57.115  5687  5687 D BluetoothAdapterState: make() - Creating AdapterState
,11-17 11:22:57.118  5687  5687 I bt_bluedroid: init
,11-17 11:22:57.118  5687  5699 I BluetoothAdapterState: Entering OffState
,11-17 11:22:57.121  5687  5700 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-17 11:22:57.122  5687  5700 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-17 11:22:57.122  5687  5700 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-17 11:22:57.122  5687  5700 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-17 11:22:57.122  5687  5687 I bt_bluedroid: get_profile_interface socket
,11-17 11:22:57.125  5687  5703 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-17 11:22:57.126  5687  5687 I bt_bluedroid: get_profile_interface sdp
11-17 11:22:57.127  5687  5703 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-17 11:22:57.132  5687  5698 I bt_bluedroid: config_hci_snoop_log
,11-17 11:22:57.134   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-17 11:22:57.139  5687  5699 D BluetoothAdapterState: Current state: OFF, message: 0
,11-17 11:22:57.139  5687  5699 D BluetoothAdapterProperties: Setting state to 14
11-17 11:22:57.140  5687  5699 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-17 11:22:57.141  5687  5699 D BluetoothBondStateMachine: make
,11-17 11:22:57.144  5687  5704 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-17 11:22:57.147  5687  5699 I BluetoothAdapterState: Entering PendingCommandState
,11-17 11:22:57.148  5687  5687 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-17 11:22:57.151  5687  5687 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f0c67ce
11-17 11:22:57.152  5687  5687 D BtGatt.DebugUtils: handleDebugAction() action=null
11-17 11:22:57.152  5687  5687 D BtGatt.GattService: Received start request. Starting profile...
11-17 11:22:57.152  5687  5687 D BtGatt.GattService: start()
11-17 11:22:57.152  5687  5687 I bt_bluedroid: get_profile_interface gatt
,11-17 11:22:57.154  5687  5687 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f0c67ce
,11-17 11:22:57.154  5687  5687 D BtGatt.AdvertiseManager: advertise manager created
,11-17 11:22:57.160  5687  5687 V BluetoothAdapterState: isTurningOff()=false
11-17 11:22:57.160  5687  5687 V BluetoothAdapterState: isTurningOn()=false
11-17 11:22:57.160  5687  5687 V BluetoothAdapterState: isBleTurningOn()=true
11-17 11:22:57.160  5687  5687 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:22:57.160  5687  5699 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-17 11:22:57.162  5687  5699 I bt_bluedroid: bt_bluedroid
,11-17 11:22:57.162  5687  5700 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-17 11:22:57.162  5687  5700 I bt_hci  : start_up
,11-17 11:22:57.167  5687  5700 I bt_vendor: alloc value 0xf3b57871
,11-17 11:22:57.167  5687  5700 I bt_vendor: init
11-17 11:22:57.167  5687  5700 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-17 11:22:57.168  5687  5700 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-17 11:22:57.253   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 11:22:57.279  5687  5700 D bt_hci  : start_up starting async portion
,11-17 11:22:57.280  5687  5707 I bt_hci  : event_finish_startup
11-17 11:22:57.280  5687  5707 I bt_hci_h4: hal_open
11-17 11:22:57.280  5687  5707 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
11-17 11:22:57.279  5708  5708 W irq/448-msm_hs_: type=1400 audit(0.0:110): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-17 11:22:57.284  5687  5707 I bt_userial_vendor: device fd = 54 open
,11-17 11:22:57.298  5687  5707 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-17 11:22:57.300  5687  5707 D bt_hwcfg: Chipset BCM4358A3
,11-17 11:22:57.301  5687  5707 D bt_hwcfg: Target name = [BCM4358A3]
11-17 11:22:57.301  5687  5707 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-17 11:22:57.709  5687  5707 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-17 11:22:57.709  5687  5707 D bt_hwcfg: Settlement delay -- 100 ms
,11-17 11:22:57.709  5687  5707 I bt_hwcfg: Setting fw settlement delay to 100 
,11-17 11:22:57.843  5687  5707 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-17 11:22:57.844  5687  5707 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
11-17 11:22:57.845  5687  5707 I bt_hwcfg: vendor lib fwcfg completed
11-17 11:22:57.845  5687  5707 I bt_vendor: firmware callback
11-17 11:22:57.845  5687  5707 I bt_hci  : firmware_config_callback
,11-17 11:22:57.855  5687  5710 I bt_btu  : btu_task pending for preload complete event
,11-17 11:22:57.855  5687  5710 I bt_btu_task: Bluetooth chip preload is complete
,11-17 11:22:57.857  5687  5710 I bt_btu  : btu_task received preload complete event
,11-17 11:22:57.863  5687  5710 I         : BTE_InitTraceLevels -- TRC_HCI
,11-17 11:22:57.863  5687  5710 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-17 11:22:57.863  5687  5710 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-17 11:22:57.863  5687  5710 I         : BTE_InitTraceLevels -- TRC_AVDT
11-17 11:22:57.863  5687  5710 I         : BTE_InitTraceLevels -- TRC_AVRC
11-17 11:22:57.863  5687  5710 I         : BTE_InitTraceLevels -- TRC_A2D
,11-17 11:22:57.863  5687  5710 I         : BTE_InitTraceLevels -- TRC_BNEP
11-17 11:22:57.864  5687  5710 I         : BTE_InitTraceLevels -- TRC_BTM
11-17 11:22:57.864  5687  5710 I         : BTE_InitTraceLevels -- TRC_GAP
11-17 11:22:57.864  5687  5710 I         : BTE_InitTraceLevels -- TRC_PAN
,11-17 11:22:57.864  5687  5710 I         : BTE_InitTraceLevels -- TRC_SDP
11-17 11:22:57.864  5687  5710 I         : BTE_InitTraceLevels -- TRC_GATT
11-17 11:22:57.864  5687  5710 I         : BTE_InitTraceLevels -- TRC_SMP
,11-17 11:22:57.864  5687  5710 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-17 11:22:57.864  5687  5710 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-17 11:22:57.948  5687  5710 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3ad5549
11-17 11:22:57.948  5687  5710 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3ad5549 
,11-17 11:22:57.972  5687  5703 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-17 11:22:57.974  5687  5703 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-17 11:22:57.974  5687  5703 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-17 11:22:57.976  5687  5703 D BluetoothAdapterProperties: Name is: Nexus 6P
11-17 11:22:57.979  5687  5703 D BluetoothAdapterProperties: Scan Mode:20
11-17 11:22:57.979  5687  5703 D BluetoothAdapterProperties: Discoverable Timeout:120
11-17 11:22:57.980  5687  5703 D bt_hci  : do_postload posting postload work item
,11-17 11:22:57.980  5687  5707 I bt_hci  : event_postload
11-17 11:22:57.980  5687  5707 I bt_vendor: sco_config_cb
11-17 11:22:57.980  5687  5707 I bt_hci  : sco_config_callback postload finished.
,11-17 11:22:57.984  5374  5374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-17 11:22:57.986  5687  5703 D bt_bte_conf: Device ID record 1 : primary
11-17 11:22:57.987  5687  5703 D bt_bte_conf:   vendorId            = 000f
11-17 11:22:57.987  5687  5703 D bt_bte_conf:   vendorIdSource      = 0001
,11-17 11:22:57.987  5687  5703 D bt_bte_conf:   product             = 1200
11-17 11:22:57.987  5687  5703 D bt_bte_conf:   version             = 1436
11-17 11:22:57.987  5687  5703 D bt_bte_conf:   clientExecutableURL = 
11-17 11:22:57.987  5687  5703 D bt_bte_conf:   serviceDescription  = 
11-17 11:22:57.987  5687  5703 D bt_bte_conf:   documentationURL    = 
,11-17 11:22:57.987  5687  5703 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-17 11:22:57.987  5687  5700 D bt_stack_manager: event_start_up_stack finished
11-17 11:22:57.988  5687  5699 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
,11-17 11:22:57.989  5687  5699 D BluetoothAdapterProperties: Setting state to 15
,11-17 11:22:57.989  5687  5699 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,11-17 11:22:57.990  5687  5707 I bt_vendor: low_power_mode_cb
,11-17 11:22:57.991  5687  5699 I BluetoothAdapterState: Entering BleOnState
,11-17 11:22:57.996  5687  5699 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-17 11:22:57.996  5687  5699 D BluetoothAdapterProperties: Setting state to 11
11-17 11:22:57.996  5687  5699 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-17 11:22:58.002  5687  5687 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f0c67ce
,11-17 11:22:58.003  5374  5374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-17 11:22:58.003  5687  5687 D HeadsetService: Received start request. Starting profile...
,11-17 11:22:58.008  5687  5687 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-17 11:22:58.008  5687  5687 D HeadsetStateMachine: make
,11-17 11:22:58.014  5687  5699 I BluetoothAdapterState: Entering PendingCommandState
,11-17 11:22:58.017  5687  5687 D HeadsetStateMachine: max_hf_connections = 1
,11-17 11:22:58.017  5687  5687 I bt_bluedroid: get_profile_interface handsfree
11-17 11:22:58.018  5687  5703 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-17 11:22:58.018  5687  5703 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,11-17 11:22:58.021  5687  5687 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f0c67ce
,11-17 11:22:58.021  5687  5687 D A2dpService: Received start request. Starting profile...
,11-17 11:22:58.022  5687  5687 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,11-17 11:22:58.023  5687  5687 I bt_bluedroid: get_profile_interface avrcp
,11-17 11:22:58.028  5687  5687 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-17 11:22:58.028  5687  5687 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-17 11:22:58.028  5687  5687 D A2dpStateMachine: make
,11-17 11:22:58.030  5687  5687 I bt_bluedroid: get_profile_interface a2dp
,11-17 11:22:58.030  5687  5703 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-17 11:22:58.032  5687  5718 D A2dpStateMachine: Enter Disconnected: -2
,11-17 11:22:58.035  5687  5687 I BluetoothHidServiceJni: classInitNative: succeeds
,11-17 11:22:58.036  3424  3424 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-17 11:22:58.036  5687  5687 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f0c67ce
,11-17 11:22:58.036  5687  5687 D HidService: Received start request. Starting profile...
,11-17 11:22:58.037  5687  5687 I bt_bluedroid: get_profile_interface hidhost
,11-17 11:22:58.037  5687  5703 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ab656d
11-17 11:22:58.037  5687  5687 D HidService: setHidService(): set to: null
11-17 11:22:58.037  5687  5703 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-17 11:22:58.037  5687  5687 I BluetoothHealthServiceJni: classInitNative: succeeds
11-17 11:22:58.038  5687  5687 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f0c67ce
11-17 11:22:58.039  5687  5687 D HealthService: Received start request. Starting profile...
,11-17 11:22:58.040  5687  5687 I bt_bluedroid: get_profile_interface health
,11-17 11:22:58.041  5687  5687 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-17 11:22:58.041  5687  5687 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f0c67ce
,11-17 11:22:58.042  5687  5687 D PanService: Received start request. Starting profile...
11-17 11:22:58.042  5687  5687 D BluetoothPanServiceJni: initializeNative(L110): pan
11-17 11:22:58.042  5687  5687 I bt_bluedroid: get_profile_interface pan
11-17 11:22:58.043  5687  5703 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-17 11:22:58.044  5687  5687 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f0c67ce
,11-17 11:22:58.045  5687  5687 D BluetoothMapService: Received start request. Starting profile...
11-17 11:22:58.045  5687  5687 D BluetoothMapService: start()
,11-17 11:22:58.047  5687  5687 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-17 11:22:58.048  5687  5687 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-17 11:22:58.048  5687  5687 D BluetoothMapAppObserver: createReceiver()
11-17 11:22:58.049  5687  5687 D BluetoothMapAppObserver: initObservers()
11-17 11:22:58.049  5687  5687 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-17 11:22:58.057  5687  5687 V SapService: SapBinder()
11-17 11:22:58.057  5687  5687 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f0c67ce
,11-17 11:22:58.057  5687  5687 D SapService: Received start request. Starting profile...
11-17 11:22:58.057  5687  5687 V SapService: start()
,11-17 11:22:58.060  5687  5687 V BluetoothAdapterState: isTurningOff()=false
11-17 11:22:58.060  5687  5687 V BluetoothAdapterState: isTurningOn()=true
11-17 11:22:58.060  5687  5687 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:22:58.060  5687  5687 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:22:58.061  5687  5687 V BluetoothAdapterState: isTurningOff()=false
11-17 11:22:58.061  5687  5687 V BluetoothAdapterState: isTurningOn()=true
11-17 11:22:58.061  5687  5687 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:22:58.061  5687  5687 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:22:58.061  5687  5716 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-17 11:22:58.061  5687  5687 V BluetoothAdapterState: isTurningOff()=false
11-17 11:22:58.061  5687  5687 V BluetoothAdapterState: isTurningOn()=true
11-17 11:22:58.061  5687  5687 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:22:58.061  5687  5687 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:22:58.061  5687  5687 V BluetoothAdapterState: isTurningOff()=false
,11-17 11:22:58.061  5687  5687 V BluetoothAdapterState: isTurningOn()=true
11-17 11:22:58.061  5687  5687 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:22:58.061  5687  5687 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:22:58.061  5687  5687 V BluetoothAdapterState: isTurningOff()=false
11-17 11:22:58.061  5687  5687 V BluetoothAdapterState: isTurningOn()=true
11-17 11:22:58.062  5687  5687 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:22:58.062  5687  5687 V BluetoothAdapterState: isBleTurningOff()=false
,11-17 11:22:58.062  5687  5687 V BluetoothAdapterState: isTurningOff()=false
11-17 11:22:58.063  5687  5687 V BluetoothAdapterState: isTurningOn()=true
11-17 11:22:58.064  5687  5687 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:22:58.064  5687  5687 V BluetoothAdapterState: isBleTurningOff()=false
,11-17 11:22:58.065  5687  5687 V BluetoothAdapterState: isTurningOff()=false
,11-17 11:22:58.065  5687  5687 V BluetoothAdapterState: isTurningOn()=true
11-17 11:22:58.065  5687  5687 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:22:58.065  5687  5687 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:22:58.065  5687  5699 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-17 11:22:58.065  5687  5699 D BluetoothAdapterProperties: ScanMode =  20
11-17 11:22:58.065  5687  5699 D BluetoothAdapterProperties: State =  11
11-17 11:22:58.065  5687  5699 D BluetoothAdapterProperties: Setting state to 12
,11-17 11:22:58.065  5687  5699 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-17 11:22:58.066  5687  5699 I BluetoothAdapterState: Entering OnState
11-17 11:22:58.066  5472  5483 D BluetoothPan: onBluetoothStateChange on: true
11-17 11:22:58.068  5687  5703 D BluetoothAdapterProperties: Scan Mode:21
11-17 11:22:58.068  5472  5484 D BluetoothPbap: onBluetoothStateChange: up=true
11-17 11:22:58.068  5687  5703 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-17 11:22:58.069  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-17 11:22:58.070   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-17 11:22:58.070  3019  3031 D BluetoothMap: onBluetoothStateChange: up=true
11-17 11:22:58.070  5374  5374 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-17 11:22:58.072  3019  3030 D BluetoothA2dp: onBluetoothStateChange: up=true
11-17 11:22:58.073  3019  3019 D BluetoothMap: Proxy object connected
11-17 11:22:58.073  3019  3019 D MapProfile: Bluetooth service connected
11-17 11:22:58.073  3019  3019 D BluetoothMap: getConnectedDevices()
11-17 11:22:58.073  5374  5374 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-17 11:22:58.076  5687  5687 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-17 11:22:58.076  3019  3031 D BluetoothPbap: onBluetoothStateChange: up=true
11-17 11:22:58.076  5687  5687 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-17 11:22:58.077  5374  5374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-17 11:22:58.077  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-17 11:22:58.077  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-17 11:22:58.077  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-17 11:22:58.077  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-17 11:22:58.077  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-17 11:22:58.077  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-17 11:22:58.077  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-17 11:22:58.077  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-17 11:22:58.077  5472  5472 D BluetoothPan: BluetoothPAN Proxy object connected
11-17 11:22:58.077  5472  5472 D PanProfile: Bluetooth service connected
11-17 11:22:58.078  5687  5687 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-17 11:22:58.078  3019  3840 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-17 11:22:58.079  5374  5374 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-17 11:22:58.079  5687  5687 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-17 11:22:58.081  5687  5687 D ObexServerSockets: Succeed to create listening sockets 
11-17 11:22:58.081  5687  5687 D ObexServerSockets0: startAccept()
,11-17 11:22:58.081  5687  5687 D ObexServerSockets0: prepareForNewConnect()
,11-17 11:22:58.081  5472  5483 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-17 11:22:58.083  5687  5687 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-17 11:22:58.083  5687  5687 D BluetoothSdpJni: SDP Create record success - handle: 0
11-17 11:22:58.084  5687  5724 D ObexServerSockets0: Accepting socket connection...
,11-17 11:22:58.084  3656  3856 D BluetoothHeadset: onBluetoothStateChange: up=true
11-17 11:22:58.085  3019  3019 D BluetoothA2dp: Proxy object connected
11-17 11:22:58.085  5472  5723 D BluetoothHeadset: onBluetoothStateChange: up=true
11-17 11:22:58.085  5687  5725 D ObexServerSockets0: Accepting socket connection...
11-17 11:22:58.086   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-17 11:22:58.087  3019  3019 D BluetoothInputDevice: Proxy object connected
11-17 11:22:58.087  3019  3019 D HidProfile: Bluetooth service connected
11-17 11:22:58.087   928   928 D BluetoothA2dp: Proxy object connected
11-17 11:22:58.087  5472  5483 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-17 11:22:58.089   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-17 11:22:58.089  5472  5472 D BluetoothA2dp: Proxy object connected
11-17 11:22:58.090  5472  5723 D BluetoothMap: onBluetoothStateChange: up=true
,11-17 11:22:58.091  3019  3840 D BluetoothPan: onBluetoothStateChange on: true
11-17 11:22:58.093  3019  3019 D BluetoothPan: BluetoothPAN Proxy object connected
11-17 11:22:58.093  3019  3030 D BluetoothHeadset: onBluetoothStateChange: up=true
11-17 11:22:58.093  3019  3019 D PanProfile: Bluetooth service connected
11-17 11:22:58.093   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-17 11:22:58.094  5472  5472 D BluetoothInputDevice: Proxy object connected
11-17 11:22:58.094  5472  5472 D HidProfile: Bluetooth service connected
11-17 11:22:58.094   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
11-17 11:22:58.095  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-17 11:22:58.096  5687  5687 D BluetoothMapService: onReceive
11-17 11:22:58.096  5687  5687 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-17 11:22:58.096  5687  5687 D BluetoothMapService: STATE_ON
,11-17 11:22:58.097  5472  5472 D BluetoothMap: Proxy object connected
11-17 11:22:58.097  5472  5472 D MapProfile: Bluetooth service connected
11-17 11:22:58.097  5472  5472 D BluetoothMap: getConnectedDevices()
,11-17 11:22:58.098  5374  5374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-17 11:22:58.099  5687  5728 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-17 11:22:58.102  5687  5728 D BluetoothSdpJni: sdpCreateSapsRecordNative:
,11-17 11:22:58.102  5687  5728 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-17 11:22:58.105  5472  5472 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-17 11:22:58.109  5472  5472 D DockEventReceiver: finishStartingService: stopping service
,11-17 11:22:58.111  3424  3424 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-17 11:22:58.117  3019  3019 D BluetoothPbap: Proxy object connected
,11-17 11:22:58.117  3019  3019 D PbapServerProfile: Bluetooth service connected
,11-17 11:22:58.119  5472  5472 D BluetoothPbap: Proxy object connected
,11-17 11:22:58.119  5472  5472 D PbapServerProfile: Bluetooth service connected
,11-17 11:22:58.122  5687  5687 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-17 11:22:58.122  5687  5687 D ObexServerSockets0: prepareForNewConnect()
,11-17 11:22:58.125  5687  5732 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-17 11:22:58.138  5687  5736 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-17 11:22:58.139  5687  5736 I BtOppRfcommListener: Accept thread started.
,11-17 11:22:58.172  3019  3031 D BluetoothHeadset: Proxy object connected
,11-17 11:22:58.172  3019  3019 D HeadsetProfile: Bluetooth service connected
11-17 11:22:58.172  5472  5483 D BluetoothHeadset: Proxy object connected
,11-17 11:22:58.172   928   928 D BluetoothHeadset: Proxy object connected
,11-17 11:22:58.173  3656  3685 D BluetoothHeadset: Proxy object connected
11-17 11:22:58.173   928   928 D BluetoothHeadset: Proxy object connected
11-17 11:22:58.173   928   928 D BluetoothHeadset: Proxy object connected
11-17 11:22:58.174  5472  5472 D HeadsetProfile: Bluetooth service connected
,11-17 11:22:58.185  3656  3855 D BluetoothHeadset: Proxy object connected
,11-17 11:22:58.186  5472  5484 D BluetoothHeadset: Proxy object connected
,11-17 11:22:58.187  5472  5472 D HeadsetProfile: Bluetooth service connected
,11-17 11:22:58.189   928   945 D BluetoothHeadset: Proxy object connected
,11-17 11:22:58.193  3019  3030 D BluetoothHeadset: Proxy object connected
11-17 11:22:58.193  3019  3019 D HeadsetProfile: Bluetooth service connected
,11-17 11:22:58.193   928   945 D BluetoothHeadset: Proxy object connected
,11-17 11:22:58.253   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-17 11:22:59.649   928  2873 D ConnectivityService: handlePromptUnvalidated 101
,11-17 11:23:01.973  5687  5699 D BluetoothAdapterState: Current state: ON, message: 23
,11-17 11:23:01.973  5687  5699 D BluetoothAdapterProperties: Setting state to 13
11-17 11:23:01.973  5687  5699 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,11-17 11:23:01.974  5687  5699 D BluetoothAdapterProperties: onBluetoothDisable()
11-17 11:23:01.976  5687  5699 I BluetoothAdapterState: Entering PendingCommandState
,11-17 11:23:01.979  5687  5687 D BluetoothMapService: onReceive
,11-17 11:23:01.979  5687  5687 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-17 11:23:01.980  5687  5687 D BluetoothMapService: STATE_TURNING_OFF
11-17 11:23:01.980  5687  5687 D BluetoothMapService: MAP Service closeService in
,11-17 11:23:01.980  5687  5687 D BluetoothMapMasInstance0: MAP Service shutdown
,11-17 11:23:01.981  5687  5687 D ObexServerSockets0: shutdown(block = true)
,11-17 11:23:01.982  5687  5687 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-17 11:23:01.982  5374  5374 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-17 11:23:01.982  5374  5374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-17 11:23:01.982  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-17 11:23:01.982  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-17 11:23:01.982  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-17 11:23:01.982  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-17 11:23:01.982  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-17 11:23:01.982  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-17 11:23:01.982  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-17 11:23:01.982  5374  5374 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-17 11:23:01.982  5687  5724 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-17 11:23:01.982  5687  5687 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-17 11:23:01.983  5687  5712 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-17 11:23:01.983  5687  5725 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-17 11:23:01.984  5374  5374 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-17 11:23:01.984  5374  5374 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-17 11:23:01.986  5687  5687 I BtOppRfcommListener: stopping Accept Thread
11-17 11:23:01.986  5687  5736 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-17 11:23:01.987  5687  5736 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-17 11:23:01.987  5687  5703 D BluetoothAdapterProperties: Scan Mode:20
11-17 11:23:01.988  5687  5699 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-17 11:23:01.990  5374  5374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-17 11:23:01.994  5687  5687 D HeadsetService: Received stop request...Stopping profile...
11-17 11:23:01.995  5472  5472 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-17 11:23:01.997  3019  3840 D BluetoothHeadset: Proxy object disconnected
11-17 11:23:01.999  5687  5687 D A2dpService: Received stop request...Stopping profile...
11-17 11:23:02.000  5687  5718 D A2dpStateMachine: Exit Disconnected: -1
11-17 11:23:02.000  5472  5484 D BluetoothHeadset: Proxy object disconnected
11-17 11:23:02.001   928   928 D BluetoothHeadset: Proxy object disconnected
11-17 11:23:02.001  3656  3681 D BluetoothHeadset: Proxy object disconnected
11-17 11:23:02.002   928   928 D BluetoothHeadset: Proxy object disconnected
,11-17 11:23:02.002   928   928 D BluetoothHeadset: Proxy object disconnected
11-17 11:23:02.003   928   928 D BluetoothA2dp: Proxy object disconnected
11-17 11:23:02.006  5687  5687 D HidService: Received stop request...Stopping profile...
11-17 11:23:02.007  5687  5687 D HidService: Stopping Bluetooth HidService
11-17 11:23:02.008  5687  5687 V BluetoothAdapterState: isTurningOff()=true
11-17 11:23:02.008  5687  5687 V BluetoothAdapterState: isTurningOn()=false
11-17 11:23:02.008  5687  5687 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:23:02.008  5687  5687 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:23:02.009  5687  5687 D HealthService: Received stop request...Stopping profile...
11-17 11:23:02.009  3019  3019 D HeadsetProfile: Bluetooth service disconnected
11-17 11:23:02.009  3019  3019 D BluetoothA2dp: Proxy object disconnected
11-17 11:23:02.010  3019  3019 D BluetoothInputDevice: Proxy object disconnected
11-17 11:23:02.010  3019  3019 D HidProfile: Bluetooth service disconnected
11-17 11:23:02.010  5472  5472 D DockEventReceiver: finishStartingService: stopping service
11-17 11:23:02.011  5472  5472 D HeadsetProfile: Bluetooth service disconnected
11-17 11:23:02.011  5472  5472 D BluetoothA2dp: Proxy object disconnected
11-17 11:23:02.011  5472  5472 D BluetoothInputDevice: Proxy object disconnected
11-17 11:23:02.011  5472  5472 D HidProfile: Bluetooth service disconnected
,11-17 11:23:02.013  5687  5687 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-17 11:23:02.013  5687  5687 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-17 11:23:02.013  5687  5710 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-17 11:23:02.014  5687  5710 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-17 11:23:02.014  5687  5710 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-17 11:23:02.014  5687  5687 V BluetoothAdapterState: isTurningOff()=true
11-17 11:23:02.014  5687  5687 V BluetoothAdapterState: isTurningOn()=false
11-17 11:23:02.014  5687  5687 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:23:02.014  5687  5687 V BluetoothAdapterState: isBleTurningOff()=false
,11-17 11:23:02.015  5687  5703 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-17 11:23:02.015  5687  5703 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
,11-17 11:23:02.016  5687  5703 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-17 11:23:02.016  5687  5710 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-17 11:23:02.016  5687  5710 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-17 11:23:02.016  5687  5710 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-17 11:23:02.016  5687  5710 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-17 11:23:02.016  5687  5710 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-17 11:23:02.016  5687  5710 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-17 11:23:02.018  5687  5687 D PanService: Received stop request...Stopping profile...
11-17 11:23:02.019  3019  3019 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-17 11:23:02.019  3424  3424 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-17 11:23:02.020  3019  3019 D PanProfile: Bluetooth service disconnected
11-17 11:23:02.020  5472  5472 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-17 11:23:02.020  5472  5472 D PanProfile: Bluetooth service disconnected
11-17 11:23:02.021  5687  5687 V BluetoothAdapterState: isTurningOff()=true
11-17 11:23:02.021  5687  5687 V BluetoothAdapterState: isTurningOn()=false
11-17 11:23:02.021  5687  5687 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:23:02.021  5687  5687 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:23:02.021  5687  5687 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-17 11:23:02.022  5687  5703 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-17 11:23:02.022  5687  5687 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-17 11:23:02.023  5687  5687 D BluetoothMapService: Received stop request...Stopping profile...
11-17 11:23:02.023  5687  5687 D BluetoothMapService: stop()
11-17 11:23:02.024  5687  5687 D BluetoothMapAppObserver: deinitObservers()
11-17 11:23:02.024  5687  5687 D BluetoothMapAppObserver: removeReceiver()
,11-17 11:23:02.026  3019  3019 D BluetoothMap: Proxy object disconnected
,11-17 11:23:02.026  3019  3019 D MapProfile: Bluetooth service disconnected
11-17 11:23:02.026  5687  5687 V BluetoothAdapterState: isTurningOff()=true
11-17 11:23:02.026  5687  5687 V BluetoothAdapterState: isTurningOn()=false
11-17 11:23:02.026  5687  5687 V BluetoothAdapterState: isBleTurningOn()=false
,11-17 11:23:02.026  5687  5687 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:23:02.027  5687  5687 D SapService: Received stop request...Stopping profile...
11-17 11:23:02.027  5687  5687 V SapService: stop()
11-17 11:23:02.028  5472  5472 D BluetoothMap: Proxy object disconnected
11-17 11:23:02.028  5472  5472 D MapProfile: Bluetooth service disconnected
,11-17 11:23:02.029  5687  5687 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-17 11:23:02.030  5687  5703 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-17 11:23:02.030  5687  5687 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-17 11:23:02.032  3019  3019 D BluetoothPbap: Proxy object disconnected
,11-17 11:23:02.032  3019  3019 D PbapServerProfile: Bluetooth service disconnected
11-17 11:23:02.032  5687  5687 V BluetoothAdapterState: isTurningOff()=true
11-17 11:23:02.032  5687  5687 V BluetoothAdapterState: isTurningOn()=false
11-17 11:23:02.033  5687  5687 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:23:02.033  5687  5687 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:23:02.033  5687  5687 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-17 11:23:02.033  5687  5687 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,11-17 11:23:02.033  5472  5472 D BluetoothPbap: Proxy object disconnected
11-17 11:23:02.034  5472  5472 D PbapServerProfile: Bluetooth service disconnected
11-17 11:23:02.035  5687  5687 D BluetoothMapService: MAP Service closeService in
11-17 11:23:02.035  5687  5687 V BluetoothAdapterState: isTurningOff()=true
11-17 11:23:02.035  5687  5687 V BluetoothAdapterState: isTurningOn()=false
11-17 11:23:02.035  5687  5687 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:23:02.036  5687  5687 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:23:02.036  5687  5687 D BluetoothMapService: cleanup()
11-17 11:23:02.036  5687  5687 D BluetoothMapService: MAP Service closeService in
11-17 11:23:02.036  5687  5687 V BluetoothAdapterState: isTurningOff()=true
11-17 11:23:02.036  5687  5687 V BluetoothAdapterState: isTurningOn()=false
11-17 11:23:02.036  5687  5687 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:23:02.036  5687  5687 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:23:02.036  5687  5699 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-17 11:23:02.036  5687  5699 D BluetoothAdapterProperties: Setting state to 15
11-17 11:23:02.036  5687  5699 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-17 11:23:02.037  5687  5699 I BluetoothAdapterState: Entering BleOnState
,11-17 11:23:02.038  5472  5723 D BluetoothPan: onBluetoothStateChange on: false
11-17 11:23:02.039  5472  5483 D BluetoothPbap: onBluetoothStateChange: up=false
11-17 11:23:02.040   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-17 11:23:02.040  3019  3840 D BluetoothMap: onBluetoothStateChange: up=false
,11-17 11:23:02.041  3019  3031 D BluetoothA2dp: onBluetoothStateChange: up=false
11-17 11:23:02.041  3019  3030 D BluetoothPbap: onBluetoothStateChange: up=false
11-17 11:23:02.042  3019  3840 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-17 11:23:02.042  5472  5484 D BluetoothA2dp: onBluetoothStateChange: up=false
11-17 11:23:02.044  3656  3856 D BluetoothHeadset: onBluetoothStateChange: up=false
11-17 11:23:02.044  5472  5723 D BluetoothHeadset: onBluetoothStateChange: up=false
11-17 11:23:02.044   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
11-17 11:23:02.044  5472  5483 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-17 11:23:02.045   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-17 11:23:02.045  5472  5484 D BluetoothMap: onBluetoothStateChange: up=false
,11-17 11:23:02.046  3019  3031 D BluetoothPan: onBluetoothStateChange on: false
11-17 11:23:02.047  3019  3030 D BluetoothHeadset: onBluetoothStateChange: up=false
11-17 11:23:02.047   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-17 11:23:02.047  5687  5699 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-17 11:23:02.047  5687  5699 D BluetoothAdapterProperties: Setting state to 16
11-17 11:23:02.047  5687  5699 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-17 11:23:02.048  5687  5699 D BluetoothAdapterProperties: onBleDisable
11-17 11:23:02.049  5687  5699 I BluetoothAdapterState: Entering PendingCommandState
11-17 11:23:02.049  5687  5700 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-17 11:23:02.050  5687  5703 D BluetoothAdapterProperties: Scan Mode:20
11-17 11:23:02.050  5472  5472 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-17 11:23:02.050  5687  5710 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-17 11:23:02.050  5687  5710 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-17 11:23:02.052  5374  5374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-17 11:23:02.054  5374  5374 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-17 11:23:02.055  3424  3424 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-17 11:23:02.063  5472  5472 D DockEventReceiver: finishStartingService: stopping service
,11-17 11:23:02.261  5687  5703 I bt_hci  : shut_down
,11-17 11:23:02.268  5687  5707 D bt_hwcfg: hw_epilog_process
,11-17 11:23:02.268  5687  5707 I bt_vendor: low_power_mode_cb
,11-17 11:23:02.271  5687  5707 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-17 11:23:02.271  5687  5707 I bt_vendor: epilog_cb
11-17 11:23:02.271  5687  5707 I bt_hci  : epilog_finished_callback
,11-17 11:23:02.275  5687  5703 I bt_hci_h4: hal_close
,11-17 11:23:02.276  5687  5703 I bt_userial_vendor: device fd = 54 close
,11-17 11:23:02.386  5687  5700 D bt_stack_manager: event_shut_down_stack finished.
,11-17 11:23:02.387  5687  5699 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-17 11:23:02.393  5687  5687 D BtGatt.DebugUtils: handleDebugAction() action=null
11-17 11:23:02.393  5687  5699 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-17 11:23:02.394  5687  5687 D BtGatt.GattService: Received stop request...Stopping profile...
11-17 11:23:02.394  5687  5687 D BtGatt.GattService: stop()
,11-17 11:23:02.394  5687  5687 D BtGatt.AdvertiseManager: advertise clients cleared
11-17 11:23:02.397  5687  5687 V BluetoothAdapterState: isTurningOff()=false
11-17 11:23:02.397  5687  5687 V BluetoothAdapterState: isTurningOn()=false
11-17 11:23:02.397  5687  5687 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:23:02.397  5687  5687 V BluetoothAdapterState: isBleTurningOff()=true
,11-17 11:23:02.397  5687  5699 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-17 11:23:02.398  5687  5699 D BluetoothAdapterProperties: Setting state to 10
11-17 11:23:02.398  5687  5699 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-17 11:23:02.399  5687  5699 I BluetoothAdapterState: Entering OffState
,11-17 11:23:02.400   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-17 11:23:02.412  5687  5687 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-17 11:23:02.412  5687  5687 W BluetoothSdpJni: Cleaning up Bluetooth Health object
,11-17 11:23:02.415  5687  5687 I BluetoothServiceJni: cleanupNative: return from cleanup
11-17 11:23:02.415  5687  5700 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-17 11:23:02.419  5687  5687 I art     : System.exit called, status: 0
11-17 11:23:02.419  5687  5687 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-17 11:23:02.452   928  3711 I ActivityManager: Process com.android.bluetooth (pid 5687) has died
,11-17 11:23:06.971  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
,11-17 11:23:06.971  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-17 11:23:06.976  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:23:06.977  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@88b7a64 removed from the list
,11-17 11:23:06.977  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
,11-17 11:23:06.980  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-17 11:23:06.980  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2572093 added. We now have 4 listener(s)
11-17 11:23:06.980  5374  5420 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-17 11:23:06.982  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-17 11:23:06.982  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2572093 removed from the list
,11-17 11:23:06.982  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
,11-17 11:23:06.984  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-17 11:23:06.984  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fb7d8d0 added. We now have 4 listener(s)
11-17 11:23:06.985  5374  5420 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-17 11:23:08.191  3541  3541 D SnetService: snet destroyed
,11-17 11:23:11.994  5374  5420 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-17 11:23:12.025   928   945 I ActivityManager: Start proc 5750:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-17 11:23:12.115  5750  5750 D AdapterServiceConfig: Adding HeadsetService
,11-17 11:23:12.115  5750  5750 D AdapterServiceConfig: Adding A2dpService
11-17 11:23:12.116  5750  5750 D AdapterServiceConfig: Adding HidService
11-17 11:23:12.116  5750  5750 D AdapterServiceConfig: Adding HealthService
11-17 11:23:12.116  5750  5750 D AdapterServiceConfig: Adding PanService
11-17 11:23:12.116  5750  5750 D AdapterServiceConfig: Adding GattService
,11-17 11:23:12.116  5750  5750 D AdapterServiceConfig: Adding BluetoothMapService
11-17 11:23:12.116  5750  5750 D AdapterServiceConfig: Adding SapService
,11-17 11:23:12.128   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d16ed12:true
,11-17 11:23:12.128  5750  5750 D BluetoothAdapterState: make() - Creating AdapterState
,11-17 11:23:12.131  5750  5750 I bt_bluedroid: init
11-17 11:23:12.131  5750  5762 I BluetoothAdapterState: Entering OffState
,11-17 11:23:12.134  5750  5763 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-17 11:23:12.134  5750  5763 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-17 11:23:12.134  5750  5763 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-17 11:23:12.134  5750  5763 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-17 11:23:12.135  5750  5750 I bt_bluedroid: get_profile_interface socket
,11-17 11:23:12.137  5750  5766 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-17 11:23:12.137  5750  5750 I bt_bluedroid: get_profile_interface sdp
11-17 11:23:12.139  5750  5766 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-17 11:23:12.142  5750  5761 I bt_bluedroid: config_hci_snoop_log
,11-17 11:23:12.143   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-17 11:23:12.147  5750  5762 D BluetoothAdapterState: Current state: OFF, message: 0
11-17 11:23:12.147  5750  5762 D BluetoothAdapterProperties: Setting state to 14
11-17 11:23:12.147  5750  5762 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-17 11:23:12.149  5750  5762 D BluetoothBondStateMachine: make
,11-17 11:23:12.151  5750  5767 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-17 11:23:12.154  5750  5762 I BluetoothAdapterState: Entering PendingCommandState
,11-17 11:23:12.155  5750  5750 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-17 11:23:12.157  5750  5750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f0c67ce
11-17 11:23:12.158  5750  5750 D BtGatt.DebugUtils: handleDebugAction() action=null
11-17 11:23:12.158  5750  5750 D BtGatt.GattService: Received start request. Starting profile...
11-17 11:23:12.158  5750  5750 D BtGatt.GattService: start()
11-17 11:23:12.158  5750  5750 I bt_bluedroid: get_profile_interface gatt
11-17 11:23:12.159  5750  5750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f0c67ce
,11-17 11:23:12.160  5750  5750 D BtGatt.AdvertiseManager: advertise manager created
,11-17 11:23:12.165  5750  5750 V BluetoothAdapterState: isTurningOff()=false
,11-17 11:23:12.166  5750  5750 V BluetoothAdapterState: isTurningOn()=false
11-17 11:23:12.166  5750  5750 V BluetoothAdapterState: isBleTurningOn()=true
11-17 11:23:12.166  5750  5750 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:23:12.166  5750  5762 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-17 11:23:12.167  5750  5762 I bt_bluedroid: bt_bluedroid
,11-17 11:23:12.168  5750  5763 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-17 11:23:12.168  5750  5763 I bt_hci  : start_up
,11-17 11:23:12.174  5750  5763 I bt_vendor: alloc value 0xf3b57871
,11-17 11:23:12.174  5750  5763 I bt_vendor: init
11-17 11:23:12.174  5750  5763 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-17 11:23:12.174  5750  5763 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-17 11:23:12.286  5750  5763 D bt_hci  : start_up starting async portion
,11-17 11:23:12.287  5750  5770 I bt_hci  : event_finish_startup
,11-17 11:23:12.287  5750  5770 I bt_hci_h4: hal_open
11-17 11:23:12.287  5750  5770 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-17 11:23:12.289  5771  5771 W irq/448-msm_hs_: type=1400 audit(0.0:111): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
11-17 11:23:12.291  5750  5770 I bt_userial_vendor: device fd = 54 open
,11-17 11:23:12.307  5750  5770 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-17 11:23:12.311  5750  5770 D bt_hwcfg: Chipset BCM4358A3
,11-17 11:23:12.311  5750  5770 D bt_hwcfg: Target name = [BCM4358A3]
11-17 11:23:12.312  5750  5770 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-17 11:23:12.782  5750  5770 I bt_hwcfg: bt vendor lib: set UART baud 115200
11-17 11:23:12.783  5750  5770 D bt_hwcfg: Settlement delay -- 100 ms
11-17 11:23:12.783  5750  5770 I bt_hwcfg: Setting fw settlement delay to 100 
,11-17 11:23:12.918  5750  5770 I bt_hwcfg: bt vendor lib: set UART baud 3000000
11-17 11:23:12.918  5750  5770 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,11-17 11:23:12.920  5750  5770 I bt_hwcfg: vendor lib fwcfg completed
,11-17 11:23:12.920  5750  5770 I bt_vendor: firmware callback
11-17 11:23:12.920  5750  5770 I bt_hci  : firmware_config_callback
,11-17 11:23:12.930  5750  5773 I bt_btu  : btu_task pending for preload complete event
,11-17 11:23:12.930  5750  5773 I bt_btu_task: Bluetooth chip preload is complete
,11-17 11:23:12.930  5750  5773 I bt_btu  : btu_task received preload complete event
,11-17 11:23:12.937  5750  5773 I         : BTE_InitTraceLevels -- TRC_HCI
11-17 11:23:12.938  5750  5773 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-17 11:23:12.938  5750  5773 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-17 11:23:12.938  5750  5773 I         : BTE_InitTraceLevels -- TRC_AVDT
11-17 11:23:12.938  5750  5773 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-17 11:23:12.938  5750  5773 I         : BTE_InitTraceLevels -- TRC_A2D
11-17 11:23:12.938  5750  5773 I         : BTE_InitTraceLevels -- TRC_BNEP
11-17 11:23:12.939  5750  5773 I         : BTE_InitTraceLevels -- TRC_BTM
11-17 11:23:12.939  5750  5773 I         : BTE_InitTraceLevels -- TRC_GAP
11-17 11:23:12.939  5750  5773 I         : BTE_InitTraceLevels -- TRC_PAN
11-17 11:23:12.939  5750  5773 I         : BTE_InitTraceLevels -- TRC_SDP
11-17 11:23:12.939  5750  5773 I         : BTE_InitTraceLevels -- TRC_GATT
11-17 11:23:12.939  5750  5773 I         : BTE_InitTraceLevels -- TRC_SMP
11-17 11:23:12.940  5750  5773 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-17 11:23:12.940  5750  5773 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-17 11:23:13.020  5750  5773 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3ad5549
,11-17 11:23:13.020  5750  5773 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3ad5549 
,11-17 11:23:13.032  5750  5766 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-17 11:23:13.033  5750  5766 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-17 11:23:13.034  5750  5766 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-17 11:23:13.037  5750  5766 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-17 11:23:13.040  5750  5766 D BluetoothAdapterProperties: Scan Mode:20
11-17 11:23:13.040  5750  5766 D BluetoothAdapterProperties: Discoverable Timeout:120
11-17 11:23:13.041  5750  5766 D bt_hci  : do_postload posting postload work item
11-17 11:23:13.041  5750  5770 I bt_hci  : event_postload
11-17 11:23:13.041  5750  5770 I bt_vendor: sco_config_cb
11-17 11:23:13.041  5750  5770 I bt_hci  : sco_config_callback postload finished.
,11-17 11:23:13.044  5750  5766 D bt_bte_conf: Device ID record 1 : primary
11-17 11:23:13.045  5750  5766 D bt_bte_conf:   vendorId            = 000f
,11-17 11:23:13.045  5750  5766 D bt_bte_conf:   vendorIdSource      = 0001
11-17 11:23:13.045  5750  5766 D bt_bte_conf:   product             = 1200
11-17 11:23:13.045  5750  5766 D bt_bte_conf:   version             = 1436
11-17 11:23:13.045  5750  5766 D bt_bte_conf:   clientExecutableURL = 
11-17 11:23:13.045  5750  5766 D bt_bte_conf:   serviceDescription  = 
11-17 11:23:13.045  5750  5766 D bt_bte_conf:   documentationURL    = 
,11-17 11:23:13.045  5750  5766 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-17 11:23:13.046  5750  5763 D bt_stack_manager: event_start_up_stack finished
,11-17 11:23:13.047  5750  5762 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-17 11:23:13.047  5750  5762 D BluetoothAdapterProperties: Setting state to 15
11-17 11:23:13.047  5750  5762 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
11-17 11:23:13.049  5750  5762 I BluetoothAdapterState: Entering BleOnState
,11-17 11:23:13.053  5750  5770 I bt_vendor: low_power_mode_cb
,11-17 11:23:13.055  5750  5762 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-17 11:23:13.055  5750  5762 D BluetoothAdapterProperties: Setting state to 11
11-17 11:23:13.055  5750  5762 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-17 11:23:13.064  5750  5750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f0c67ce
11-17 11:23:13.065  5750  5750 D HeadsetService: Received start request. Starting profile...
,11-17 11:23:13.068  5750  5750 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-17 11:23:13.068  5750  5750 D HeadsetStateMachine: make
,11-17 11:23:13.077  5750  5762 I BluetoothAdapterState: Entering PendingCommandState
,11-17 11:23:13.080  5750  5750 D HeadsetStateMachine: max_hf_connections = 1
,11-17 11:23:13.080  5750  5750 I bt_bluedroid: get_profile_interface handsfree
11-17 11:23:13.080  5750  5766 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-17 11:23:13.080  5750  5766 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-17 11:23:13.084  5750  5750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f0c67ce
,11-17 11:23:13.084  5750  5750 D A2dpService: Received start request. Starting profile...
11-17 11:23:13.085  5750  5750 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-17 11:23:13.085  5750  5750 I bt_bluedroid: get_profile_interface avrcp
,11-17 11:23:13.091  5750  5750 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-17 11:23:13.091  5750  5750 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-17 11:23:13.091  5750  5750 D A2dpStateMachine: make
11-17 11:23:13.092  5750  5750 I bt_bluedroid: get_profile_interface a2dp
,11-17 11:23:13.093  5750  5766 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-17 11:23:13.094  5750  5780 D A2dpStateMachine: Enter Disconnected: -2
,11-17 11:23:13.096  5750  5750 I BluetoothHidServiceJni: classInitNative: succeeds
11-17 11:23:13.097  5750  5750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f0c67ce
11-17 11:23:13.097  3424  3424 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-17 11:23:13.097  5750  5750 D HidService: Received start request. Starting profile...
11-17 11:23:13.098  5750  5750 I bt_bluedroid: get_profile_interface hidhost
11-17 11:23:13.098  5750  5766 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3ab656d
11-17 11:23:13.098  5750  5750 D HidService: setHidService(): set to: null
,11-17 11:23:13.098  5750  5750 I BluetoothHealthServiceJni: classInitNative: succeeds
11-17 11:23:13.098  5750  5766 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-17 11:23:13.099  5750  5750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f0c67ce
11-17 11:23:13.100  5750  5750 D HealthService: Received start request. Starting profile...
,11-17 11:23:13.101  5750  5750 I bt_bluedroid: get_profile_interface health
,11-17 11:23:13.102  5750  5750 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-17 11:23:13.103  5750  5750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f0c67ce
,11-17 11:23:13.103  5750  5750 D PanService: Received start request. Starting profile...
11-17 11:23:13.104  5750  5750 D BluetoothPanServiceJni: initializeNative(L110): pan
11-17 11:23:13.104  5750  5750 I bt_bluedroid: get_profile_interface pan
11-17 11:23:13.104  5750  5766 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-17 11:23:13.106  5750  5750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f0c67ce
,11-17 11:23:13.107  5750  5750 D BluetoothMapService: Received start request. Starting profile...
11-17 11:23:13.107  5750  5750 D BluetoothMapService: start()
11-17 11:23:13.110  5750  5750 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-17 11:23:13.111  5750  5750 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-17 11:23:13.111  5750  5750 D BluetoothMapAppObserver: createReceiver()
11-17 11:23:13.112  5750  5750 D BluetoothMapAppObserver: initObservers()
11-17 11:23:13.113  5750  5750 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-17 11:23:13.121  5750  5750 V SapService: SapBinder()
,11-17 11:23:13.121  5750  5750 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f0c67ce
11-17 11:23:13.121  5750  5750 D SapService: Received start request. Starting profile...
11-17 11:23:13.121  5750  5750 V SapService: start()
,11-17 11:23:13.123  5750  5750 V BluetoothAdapterState: isTurningOff()=false
,11-17 11:23:13.124  5750  5750 V BluetoothAdapterState: isTurningOn()=true
11-17 11:23:13.124  5750  5750 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:23:13.124  5750  5750 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:23:13.124  5750  5750 V BluetoothAdapterState: isTurningOff()=false
11-17 11:23:13.124  5750  5750 V BluetoothAdapterState: isTurningOn()=true
11-17 11:23:13.124  5750  5750 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:23:13.124  5750  5750 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:23:13.124  5750  5778 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-17 11:23:13.124  5750  5750 V BluetoothAdapterState: isTurningOff()=false
11-17 11:23:13.124  5750  5750 V BluetoothAdapterState: isTurningOn()=true
11-17 11:23:13.124  5750  5750 V BluetoothAdapterState: isBleTurningOn()=false
,11-17 11:23:13.124  5750  5750 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:23:13.125  5750  5750 V BluetoothAdapterState: isTurningOff()=false
11-17 11:23:13.125  5750  5750 V BluetoothAdapterState: isTurningOn()=true
11-17 11:23:13.125  5750  5750 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:23:13.125  5750  5750 V BluetoothAdapterState: isBleTurningOff()=false
,11-17 11:23:13.125  5750  5750 V BluetoothAdapterState: isTurningOff()=false
11-17 11:23:13.125  5750  5750 V BluetoothAdapterState: isTurningOn()=true
11-17 11:23:13.125  5750  5750 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:23:13.125  5750  5750 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:23:13.125  5750  5750 V BluetoothAdapterState: isTurningOff()=false
11-17 11:23:13.125  5750  5750 V BluetoothAdapterState: isTurningOn()=true
11-17 11:23:13.125  5750  5750 V BluetoothAdapterState: isBleTurningOn()=false
,11-17 11:23:13.125  5750  5750 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:23:13.127  5750  5750 V BluetoothAdapterState: isTurningOff()=false
11-17 11:23:13.127  5750  5750 V BluetoothAdapterState: isTurningOn()=true
11-17 11:23:13.127  5750  5750 V BluetoothAdapterState: isBleTurningOn()=false
11-17 11:23:13.127  5750  5750 V BluetoothAdapterState: isBleTurningOff()=false
11-17 11:23:13.127  5750  5762 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-17 11:23:13.127  5750  5762 D BluetoothAdapterProperties: ScanMode =  20
11-17 11:23:13.127  5750  5762 D BluetoothAdapterProperties: State =  11
11-17 11:23:13.128  5750  5762 D BluetoothAdapterProperties: Setting state to 12
11-17 11:23:13.128  5750  5762 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-17 11:23:13.128  5750  5762 I BluetoothAdapterState: Entering OnState
11-17 11:23:13.128  5472  5484 D BluetoothPan: onBluetoothStateChange on: true
,11-17 11:23:13.131  5750  5766 D BluetoothAdapterProperties: Scan Mode:21
11-17 11:23:13.131  5750  5766 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-17 11:23:13.132  5472  5723 D BluetoothPbap: onBluetoothStateChange: up=true
11-17 11:23:13.134   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-17 11:23:13.134  3019  3030 D BluetoothMap: onBluetoothStateChange: up=true
11-17 11:23:13.135  3019  3840 D BluetoothA2dp: onBluetoothStateChange: up=true
11-17 11:23:13.136  3019  3019 D BluetoothMap: Proxy object connected
11-17 11:23:13.136  3019  3019 D MapProfile: Bluetooth service connected
11-17 11:23:13.136  3019  3019 D BluetoothMap: getConnectedDevices()
11-17 11:23:13.137  3019  3030 D BluetoothPbap: onBluetoothStateChange: up=true
11-17 11:23:13.139  3019  3019 D BluetoothA2dp: Proxy object connected
11-17 11:23:13.139  3019  3840 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-17 11:23:13.139  5750  5750 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-17 11:23:13.140  5750  5750 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-17 11:23:13.140  5472  5472 D BluetoothPan: BluetoothPAN Proxy object connected
11-17 11:23:13.140  5472  5472 D PanProfile: Bluetooth service connected
11-17 11:23:13.141  5472  5483 D BluetoothA2dp: onBluetoothStateChange: up=true
11-17 11:23:13.141  5750  5750 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-17 11:23:13.143  5750  5750 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-17 11:23:13.143  3656  3856 D BluetoothHeadset: onBluetoothStateChange: up=true
11-17 11:23:13.143  5472  5723 D BluetoothHeadset: onBluetoothStateChange: up=true
11-17 11:23:13.144   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-17 11:23:13.144  5750  5750 D ObexServerSockets: Succeed to create listening sockets 
11-17 11:23:13.144  5750  5750 D ObexServerSockets0: startAccept()
11-17 11:23:13.144  5750  5750 D ObexServerSockets0: prepareForNewConnect()
11-17 11:23:13.144   928   928 D BluetoothA2dp: Proxy object connected
11-17 11:23:13.144  5472  5484 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-17 11:23:13.146   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-17 11:23:13.146  5472  5483 D BluetoothMap: onBluetoothStateChange: up=true
,11-17 11:23:13.146  5750  5750 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-17 11:23:13.146  5750  5750 D BluetoothSdpJni: SDP Create record success - handle: 0
11-17 11:23:13.147  5750  5786 D ObexServerSockets0: Accepting socket connection...
11-17 11:23:13.147  5750  5787 D ObexServerSockets0: Accepting socket connection...
11-17 11:23:13.148  3019  3019 D BluetoothInputDevice: Proxy object connected
11-17 11:23:13.148  3019  3019 D HidProfile: Bluetooth service connected
11-17 11:23:13.150  3019  3030 D BluetoothPan: onBluetoothStateChange on: true
11-17 11:23:13.151  3019  3019 D BluetoothPan: BluetoothPAN Proxy object connected
11-17 11:23:13.151  3019  3840 D BluetoothHeadset: onBluetoothStateChange: up=true
11-17 11:23:13.151  5472  5472 D BluetoothA2dp: Proxy object connected
11-17 11:23:13.151  3019  3019 D PanProfile: Bluetooth service connected
11-17 11:23:13.152   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-17 11:23:13.152   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
11-17 11:23:13.154  5750  5750 D BluetoothMapService: onReceive
11-17 11:23:13.154  5750  5750 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-17 11:23:13.154  5750  5750 D BluetoothMapService: STATE_ON
,11-17 11:23:13.155  5472  5472 D BluetoothInputDevice: Proxy object connected
11-17 11:23:13.155  5472  5472 D HidProfile: Bluetooth service connected
11-17 11:23:13.157  5750  5789 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-17 11:23:13.157  5472  5472 D BluetoothMap: Proxy object connected
11-17 11:23:13.157  5472  5472 D MapProfile: Bluetooth service connected
11-17 11:23:13.157  5472  5472 D BluetoothMap: getConnectedDevices()
11-17 11:23:13.158  5750  5789 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-17 11:23:13.158  5750  5789 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-17 11:23:13.163  5472  5472 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-17 11:23:13.169  3424  3424 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-17 11:23:13.170  5472  5472 D DockEventReceiver: finishStartingService: stopping service
,11-17 11:23:13.176  3019  3019 D BluetoothPbap: Proxy object connected
,11-17 11:23:13.176  5472  5472 D BluetoothPbap: Proxy object connected
11-17 11:23:13.176  5472  5472 D PbapServerProfile: Bluetooth service connected
11-17 11:23:13.176  3019  3019 D PbapServerProfile: Bluetooth service connected
,11-17 11:23:13.181  5750  5750 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,11-17 11:23:13.181  5750  5750 D ObexServerSockets0: prepareForNewConnect()
,11-17 11:23:13.183  5750  5793 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-17 11:23:13.197  5750  5797 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-17 11:23:13.198  5750  5797 I BtOppRfcommListener: Accept thread started.
,11-17 11:23:13.235  3019  3031 D BluetoothHeadset: Proxy object connected
,11-17 11:23:13.235  3019  3019 D HeadsetProfile: Bluetooth service connected
11-17 11:23:13.235  5472  5723 D BluetoothHeadset: Proxy object connected
11-17 11:23:13.236   928   928 D BluetoothHeadset: Proxy object connected
,11-17 11:23:13.236  3656  3685 D BluetoothHeadset: Proxy object connected
,11-17 11:23:13.236   928   928 D BluetoothHeadset: Proxy object connected
11-17 11:23:13.236   928   928 D BluetoothHeadset: Proxy object connected
11-17 11:23:13.236  5472  5472 D HeadsetProfile: Bluetooth service connected
,11-17 11:23:13.244  3656  3855 D BluetoothHeadset: Proxy object connected
,11-17 11:23:13.244  5472  5484 D BluetoothHeadset: Proxy object connected
,11-17 11:23:13.245  5472  5472 D HeadsetProfile: Bluetooth service connected
,11-17 11:23:13.247   928   945 D BluetoothHeadset: Proxy object connected
,11-17 11:23:13.251  3019  3840 D BluetoothHeadset: Proxy object connected
11-17 11:23:13.252  3019  3019 D HeadsetProfile: Bluetooth service connected
,11-17 11:23:13.252   928   945 D BluetoothHeadset: Proxy object connected
,11-17 11:23:13.253   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 11:23:14.254   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 11:23:15.255   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 11:23:16.256   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 11:23:17.010  5374  5420 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-17 11:23:17.010  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-17 11:23:17.010  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-17 11:23:17.010  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-17 11:23:17.010  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-17 11:23:17.010  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-17 11:23:17.010  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-17 11:23:17.010  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-17 11:23:17.010  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-17 11:23:17.018  5374  5420 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-17 11:23:17.019  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:23:17.020  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@fb7d8d0 removed from the list
11-17 11:23:17.020  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
11-17 11:23:17.022  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-17 11:23:17.022  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@636e0c9 added. We now have 4 listener(s)
11-17 11:23:17.022  5374  5420 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-17 11:23:17.025   928  3680 D WifiService: setWifiEnabled: false pid=5374, uid=10077
11-17 11:23:17.025   928  3680 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-17 11:23:17.257   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 11:23:18.258   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-17 11:23:22.035  5374  5420 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-17 11:23:22.036   928  3723 D WifiService: setWifiEnabled: true pid=5374, uid=10077
11-17 11:23:22.036   928  3723 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-17 11:23:22.049   507   922 D SoftapController: Softap fwReload - Ok
,11-17 11:23:22.055   507   922 D CommandListener: Setting iface cfg
11-17 11:23:22.055   507   922 D CommandListener: Trying to bring down wlan0
11-17 11:23:22.056   507   922 D CommandListener: Clearing all IP addresses on wlan0
,11-17 11:23:22.061   928  2861 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-17 11:23:22.669   928  2861 D wifi    : set interface wlan0 flags (UP)
,11-17 11:23:22.676   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-17 11:23:22.677   928  2861 I WifiHAL : Initializing wifi
,11-17 11:23:22.677   928  2861 I WifiHAL : Creating socket
,11-17 11:23:22.683   928  2861 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-17 11:23:22.683   928  2861 D wifi    : Did set static halHandle = 0x7f8e3b62e0
11-17 11:23:22.684   928  2861 D wifi    : halHandle = 0x7f8e3b62e0, mVM = 0x7fa4c0d140, mCls = 0x17a6
11-17 11:23:22.684   928  2861 D wifi    : array field set
,11-17 11:23:22.684   928  2861 I WifiNative-HAL: interface[0] = wlan0
11-17 11:23:22.686   928  5803 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547847103200
11-17 11:23:22.686   928  5803 D wifi    : waitForHalEvents called, vm = 0x7fa4c0d140, obj = 0x17a6, env = 0x7f89554200
,11-17 11:23:22.752  5804  5804 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-17 11:23:22.775  5804  5804 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-17 11:23:22.789   928  2861 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-17 11:23:22.794  5804  5804 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-17 11:23:22.794  5804  5804 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-17 11:23:22.810   928  2861 D WifiConfigStore: Loading config and enabling all networks 
,11-17 11:23:22.824   928  2861 D WifiConfigStore: loaded 0 passpoint configs
,11-17 11:23:22.825   928  2861 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
11-17 11:23:22.825   928  2861 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-17 11:23:22.826   928  2861 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-17 11:23:22.827   928  2861 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-17 11:23:22.828   928  2861 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-17 11:23:22.828   928  2861 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-17 11:23:22.828   928  2861 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-17 11:23:22.832   928  2861 D WifiNative-HAL: Setting external_sim to 1
,11-17 11:23:22.832  4872  4872 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-17 11:23:22.832   928  2861 D wifi    : setting dfs flag to true, 0x7f8a015560
11-17 11:23:22.833   928  2861 D WifiStateMachine: Setting OUI to DA-A1-19
,11-17 11:23:22.833   928  2861 D wifi    : setting scan oui 0x7f8a015560
11-17 11:23:22.833   928  2861 D WifiHAL : Sending mac address OUI
,11-17 11:23:22.837   928  2861 E native  : do suspend false
,11-17 11:23:22.845   928  2861 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-17 11:23:22.846   928   928 D RttService: SCAN_AVAILABLE : 3
11-17 11:23:22.846   507   922 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
11-17 11:23:22.846   928  2953 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-17 11:23:22.847   507   922 D CommandListener: Setting iface cfg
,11-17 11:23:22.851   928  2849 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '162 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 162 Failed to set address (No such device)'
,11-17 11:23:22.851   928  2849 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-17 11:23:22.863   928  2849 D WifiNative-HAL: p2pGetDeviceAddress
,11-17 11:23:22.865   928  2849 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-17 11:23:22.870   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=173181 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=18 mControllerEnergyUsed=68 }
,11-17 11:23:25.953  5804  5804 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-17 11:23:25.966  5804  5804 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-17 11:23:25.974  5804  5804 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-17 11:23:26.012   928  2861 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-17 11:23:26.013   928  2861 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-17 11:23:26.013   928  2861 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-17 11:23:26.025   928  2861 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-17 11:23:26.057   928  2861 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-17 11:23:26.059  5804  5804 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-17 11:23:26.529  5804  5804 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-17 11:23:26.572  5804  5804 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-17 11:23:26.574  5804  5804 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-17 11:23:26.586   928  2861 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-17 11:23:26.587   928  2861 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-17 11:23:26.587   928  2873 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-17 11:23:26.608   928  2861 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-17 11:23:26.626   507   922 D CommandListener: Setting iface cfg
,11-17 11:23:26.631   928  2861 D WifiStateMachine: Start Dhcp Watchdog 3
,11-17 11:23:26.637   928  5809 D DhcpClient: Receive thread started
,11-17 11:23:26.641   928  2873 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-17 11:23:26.641   928  2861 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-17 11:23:26.641   928  2873 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-17 11:23:26.720   928  2861 E native  : do suspend false
,11-17 11:23:26.729   928  5808 D DhcpClient: Broadcasting DHCPDISCOVER
,11-17 11:23:26.747   928  5809 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,11-17 11:23:26.747   928  5808 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,11-17 11:23:26.748   928  5808 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-17 11:23:26.774   928  5809 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-17 11:23:26.775   928  5808 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-17 11:23:26.778   507   922 D CommandListener: Setting iface cfg
,11-17 11:23:26.784   928  2861 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-17 11:23:26.787   928  5808 D DhcpClient: Scheduling renewal in 86399s
,11-17 11:23:26.800   928  2861 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-17 11:23:26.802   928  2861 D WifiConfigStore: No blacklist allowed without epno enabled
11-17 11:23:26.804   928  2873 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-17 11:23:26.807   928  2873 D ConnectivityService: Adding iface wlan0 to network 102
,11-17 11:23:26.811   928  2861 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-17 11:23:26.856   928  2873 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-17 11:23:26.856   928  2873 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
11-17 11:23:26.859   928  2873 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
11-17 11:23:26.861   928  2873 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-17 11:23:26.863   928  2873 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-17 11:23:26.870   928  2873 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-17 11:23:26.874   928  2873 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-17 11:23:26.874   928  2873 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-17 11:23:26.875   928  2873 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-17 11:23:26.875   928  2873 D ConnectivityService:    accepting network in place of null
11-17 11:23:26.875   928  2861 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-17 11:23:26.875   928  2861 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-17 11:23:26.875   928  2873 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-17 11:23:26.895   928  5807 D NetlinkSocketObserver: NeighborEvent{elapsedMs=177206, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-17 11:23:26.897   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-17 11:23:26.918   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-17 11:23:26.921   928  2873 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
,11-17 11:23:26.921  3603  3771 W QCNEJ   : |CORE| network available: 102
11-17 11:23:26.921   928  2873 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-17 11:23:26.922   928  2873 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
,11-17 11:23:26.924   928   945 D Tethering: MasterInitialState.processMessage what=3
11-17 11:23:26.927  3603  3771 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-17 11:23:26.929  3603  3771 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-17 11:23:26.929  3603  3771 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-17 11:23:26.938  3792  3792 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-17 11:23:26.938  4898  4921 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-17 11:23:26.938  4898  4921 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-17 11:23:26.939  4898  4921 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-17 11:23:26.939  4898  4921 E SarControlService: no key has been found,reset the power
11-17 11:23:26.939  4898  4935 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-17 11:23:26.940  4898  4935 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-17 11:23:26.940  4898  4935 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-17 11:23:26.941  4923  4923 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-17 11:23:26.941  4923  4923 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-17 11:23:26.946  3541  3541 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-17 11:23:26.949  4923  4937 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@95f0491 HexData = [00000000f003000000000000ffffffff]
11-17 11:23:26.949  4923  4937 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-17 11:23:26.949  4923  4937 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
,11-17 11:23:26.949  4923  4923 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-17 11:23:26.949  4898  4909 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-17 11:23:26.950  3541  3541 D SystemUpdateService: onCreate
11-17 11:23:26.945  4898  4935 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-17 11:23:26.950  4898  4935 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,11-17 11:23:26.950  4898  4935 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-17 11:23:26.951  4923  4923 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-17 11:23:26.951  4923  4923 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-17 11:23:26.954  4923  4937 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@95f0491 HexData = [00000000f103000000000000ffffffff]
,11-17 11:23:26.954  4923  4937 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-17 11:23:26.954  4923  4937 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-17 11:23:26.955  4923  4923 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-17 11:23:26.955  4898  4908 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-17 11:23:26.958  3541  3541 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-17 11:23:26.974  3541  3541 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-17 11:23:26.980  3541  5564 I iu.UploadsManager: num queued entries: 0
,11-17 11:23:26.980  3541  5564 I iu.UploadsManager: num updated entries: 0
11-17 11:23:26.981  3541  5564 I iu.SyncManager: NEXT; no task
11-17 11:23:26.985  3541  5819 I SystemUpdateService: active receiver: enabled
,11-17 11:23:26.987  3541  3541 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-17 11:23:26.988  3541  3541 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-17 11:23:26.990  5567  5567 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-17 11:23:26.992   928  5806 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-17 11:23:26.996  5567  5567 D SprintDMHelper: simOperator: 
11-17 11:23:26.996  5567  5567 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-17 11:23:27.020  3541  5819 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-17 11:23:27.024  3541  5819 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-17 11:23:27.024  3541  5819 I SystemUpdateService: now status is 0 (complete)
,11-17 11:23:27.043  3541  5819 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
,11-17 11:23:27.043  3541  5819 I SystemUpdateService: file has been verified
11-17 11:23:27.043  3541  5819 I SystemUpdateService: OTA package size = 21989297
,11-17 11:23:27.050  3424  5831 I VacuumService: Vacuum at: now=1479399807050 tag=VacuumService
,11-17 11:23:27.057  5374  5420 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-17 11:23:27.057  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-17 11:23:27.057  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-17 11:23:27.057  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-17 11:23:27.057  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-17 11:23:27.057  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-17 11:23:27.057  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-17 11:23:27.057  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-17 11:23:27.057  5374  5420 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-17 11:23:27.059  5374  5420 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-17 11:23:27.059  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:23:27.060  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@636e0c9 removed from the list
11-17 11:23:27.060  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
,11-17 11:23:27.061  3541  5819 I SystemUpdateService: showing system update notification
,11-17 11:23:27.065  5374  5420 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-17 11:23:27.065  5374  5420 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,11-17 11:23:27.068  5374  5420 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@69ad485 Bundle[{}]
,11-17 11:23:27.068  5374  5420 I io.jxcore.node.LifeCycleMonitor: start: OK
11-17 11:23:27.069  5374  5420 I io.jxcore.node.LifeCycleMonitor: stop: OK
,11-17 11:23:27.069  5374  5420 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
,11-17 11:23:27.069   928  5806 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 17 Nov 2016 16:23:27 GMT], X-Android-Received-Millis=[1479399807068], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479399807036]}
11-17 11:23:27.070   928  2873 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-17 11:23:27.070  5374  5420 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
11-17 11:23:27.070   928  2873 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
11-17 11:23:27.070   928  2873 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-17 11:23:27.070  5374  5420 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-17 11:23:27.071   928  2873 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-17 11:23:27.071  5374  5420 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-17 11:23:27.077  5374  5420 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 160)
11-17 11:23:27.078  5374  5420 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-17 11:23:27.078  5374  5420 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 161)
,11-17 11:23:27.081  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-17 11:23:27.081  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25123ce added. We now have 3 listener(s)
,11-17 11:23:27.082  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-17 11:23:27.083  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-17 11:23:27.083  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-17 11:23:27.083  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-17 11:23:27.083  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c932ef added. We now have 4 listener(s)
11-17 11:23:27.083  5374  5420 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-17 11:23:27.084  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-17 11:23:27.085  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-17 11:23:27.085  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b09b1fc added. We now have 4 listener(s)
,11-17 11:23:27.087  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-17 11:23:27.087  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-17 11:23:27.087  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-17 11:23:27.087  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-17 11:23:27.087  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c43c085 added. We now have 5 listener(s)
11-17 11:23:27.087  5374  5420 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-17 11:23:27.087  5374  5420 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-17 11:23:27.088  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-17 11:23:27.088  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-17 11:23:27.088  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-17 11:23:27.088  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:23:27.088  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-17 11:23:27.088  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@25123ce removed from the list
11-17 11:23:27.088  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:23:27.088  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c932ef removed from the list
11-17 11:23:27.088  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
11-17 11:23:27.088  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:23:27.089  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:23:27.090  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:23:27.091  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.091  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.091  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-17 11:23:27.091  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-17 11:23:27.091  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:23:27.091  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@4c932ef not in the list
11-17 11:23:27.091  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.091  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:23:27.092  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.092  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.092  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:23:27.092  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-17 11:23:27.092  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-17 11:23:27.092  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:23:27.092  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c43c085 removed from the list
11-17 11:23:27.092  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-17 11:23:27.092  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:23:27.092  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-17 11:23:27.092  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@b09b1fc removed from the list
11-17 11:23:27.093  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-17 11:23:27.093  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@95faeda added. We now have 3 listener(s)
11-17 11:23:27.094  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-17 11:23:27.094  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-17 11:23:27.094  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-17 11:23:27.094  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-17 11:23:27.094  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba00f0b added. We now have 4 listener(s)
11-17 11:23:27.094  5374  5420 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-17 11:23:27.095  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-17 11:23:27.097  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-17 11:23:27.097  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53df1e8 added. We now have 4 listener(s)
11-17 11:23:27.098  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-17 11:23:27.098  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-17 11:23:27.098  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-17 11:23:27.098  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-17 11:23:27.098  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c84e001 added. We now have 5 listener(s)
11-17 11:23:27.098  5374  5420 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-17 11:23:27.098  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-17 11:23:27.098  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-17 11:23:27.098  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-17 11:23:27.098  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-17 11:23:27.098  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-17 11:23:27.099  3541  3541 D SystemUpdateService: onDestroy
,11-17 11:23:27.100  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-17 11:23:27.104  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-17 11:23:27.104  5374  5420 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-17 11:23:27.105  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-17 11:23:27.110  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.110  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-17 11:23:27.112  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-17 11:23:27.113  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-17 11:23:27.113  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-17 11:23:27.117  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:23:27.117  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-17 11:23:27.117  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-17 11:23:27.117  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-17 11:23:27.118  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-17 11:23:27.118  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.119  5374  5420 D BluetoothAdapter: STATE_ON
,11-17 11:23:27.122  5750  5798 D BtGatt.GattService: registerClient() - UUID=81911ff5-f85b-4355-8ebf-c9955867a86b
11-17 11:23:27.123  5750  5766 D BtGatt.GattService: onClientRegistered() - UUID=81911ff5-f85b-4355-8ebf-c9955867a86b, clientIf=5
,11-17 11:23:27.124  5374  5384 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-17 11:23:27.125  5750  5760 D BtGatt.GattService: start scan with filters
11-17 11:23:27.128  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-17 11:23:27.128  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.128  5750  5769 D BtGatt.ScanManager: handling starting scan
11-17 11:23:27.128  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-17 11:23:27.128  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.129  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-17 11:23:27.129  5374  5374 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-17 11:23:27.129  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.129  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-17 11:23:27.129  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-17 11:23:27.129  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.129  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.130  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.130  5374  5374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.130  5750  5769 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@f0c67ce
11-17 11:23:27.130  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-17 11:23:27.130  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.132  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.133  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-17 11:23:27.133  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.133  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.133  5374  5420 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-17 11:23:27.133  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-17 11:23:27.133  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-17 11:23:27.133  5374  5420 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-17 11:23:27.133  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-17 11:23:27.133  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-17 11:23:27.133  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-17 11:23:27.133  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-17 11:23:27.134  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.134  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-17 11:23:27.134  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-17 11:23:27.134  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.134  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.134  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.134  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-17 11:23:27.134  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:23:27.135  5374  5420 D BluetoothAdapter: STATE_ON
11-17 11:23:27.135  4872  5825 I Babel   : connection state changed from DISCONNECTED to CONNECTED
11-17 11:23:27.135  5750  5761 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-17 11:23:27.135  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-17 11:23:27.136  5374  5420 D BluetoothAdapter: STATE_ON
11-17 11:23:27.137  5750  5766 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-17 11:23:27.137  5750  5766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 11:23:27.137  5750  5760 D BtGatt.GattService: stopScan() - queue size =1
11-17 11:23:27.137  5750  5769 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-17 11:23:27.137  5750  5788 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-17 11:23:27.138  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-17 11:23:27.138  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.138  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-17 11:23:27.138  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.138  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.138  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.138  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.138  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-17 11:23:27.139  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.139  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:23:27.139  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.139  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-17 11:23:27.139  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-17 11:23:27.142  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-17 11:23:27.143  5750  5766 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-17 11:23:27.143  5750  5766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 11:23:27.143  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.143  5750  5769 D BtGatt.ScanManager: Starting BLE batch scan
11-17 11:23:27.143  5750  5769 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-17 11:23:27.144  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:23:27.144  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 11:23:27.144  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.144  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.144  5374  5374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-17 11:23:27.150  5374  5420 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-17 11:23:27.150  5374  5374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.150  5374  5374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.150  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-17 11:23:27.150  5374  5374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.150  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-17 11:23:27.150  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 11:23:27.150  5374  5374 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-17 11:23:27.150  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:23:27.150  5374  5374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 11:23:27.150  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-17 11:23:27.150  5374  5374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 11:23:27.150  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@95faeda removed from the list
11-17 11:23:27.150  5374  5374 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-17 11:23:27.150  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:23:27.150  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba00f0b removed from the list
11-17 11:23:27.150  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.150  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
11-17 11:23:27.150  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-17 11:23:27.150  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
,11-17 11:23:27.150  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.151  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.151  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.151  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.151  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.151  5374  5374 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-17 11:23:27.151  5374  5374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.151  5374  5374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.151  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.151  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.152  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.152  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-17 11:23:27.152  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-17 11:23:27.152  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:23:27.152  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ba00f0b not in the list
,11-17 11:23:27.152  5374  5374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.152  5374  5374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.152  5374  5374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.152  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.152  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.152  5750  5766 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-17 11:23:27.152  5750  5766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 11:23:27.155  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.155  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.155  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.155  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-17 11:23:27.155  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-17 11:23:27.155  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:23:27.155  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c84e001 removed from the list
11-17 11:23:27.155  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 11:23:27.155  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:23:27.155  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-17 11:23:27.155  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@53df1e8 removed from the list
,11-17 11:23:27.156  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-17 11:23:27.156  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f53f32 added. We now have 3 listener(s)
11-17 11:23:27.157  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-17 11:23:27.157  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-17 11:23:27.157  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-17 11:23:27.157  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-17 11:23:27.157  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b595483 added. We now have 4 listener(s)
11-17 11:23:27.157  5374  5420 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-17 11:23:27.157  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-17 11:23:27.158  5750  5766 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-17 11:23:27.158  5750  5766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 11:23:27.158  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-17 11:23:27.158  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1b1600 added. We now have 4 listener(s)
11-17 11:23:27.159  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-17 11:23:27.159  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-17 11:23:27.159  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-17 11:23:27.159  5750  5769 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-17 11:23:27.160  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-17 11:23:27.160  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@93c8e39 added. We now have 5 listener(s)
11-17 11:23:27.160  5374  5420 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-17 11:23:27.160  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-17 11:23:27.160  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-17 11:23:27.160  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-17 11:23:27.160  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-17 11:23:27.160  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-17 11:23:27.161  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-17 11:23:27.161  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-17 11:23:27.164  5750  5766 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-17 11:23:27.164  5750  5766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 11:23:27.164  5750  5766 E BtGatt.ContextMap: Context not found for ID 5
11-17 11:23:27.166  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-17 11:23:27.166  5374  5420 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-17 11:23:27.166  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-17 11:23:27.170  5750  5766 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-17 11:23:27.170  5750  5766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 11:23:27.170  5750  5769 D BtGatt.ScanManager: stopping BLe Batch
11-17 11:23:27.170  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.170  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-17 11:23:27.171  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-17 11:23:27.171  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-17 11:23:27.171  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-17 11:23:27.175  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.175  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-17 11:23:27.175  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-17 11:23:27.175  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-17 11:23:27.176  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-17 11:23:27.176  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.176  5750  5766 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-17 11:23:27.176  5750  5766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 11:23:27.176  5750  5769 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-17 11:23:27.178  5374  5420 D BluetoothAdapter: STATE_ON
,11-17 11:23:27.184  5750  5766 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-17 11:23:27.184  5750  5766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-17 11:23:27.185  5750  5761 D BtGatt.GattService: registerClient() - UUID=e4f1cf60-740b-40ec-aa84-5465d1ef4edf
,11-17 11:23:27.186  5750  5766 D BtGatt.GattService: onClientRegistered() - UUID=e4f1cf60-740b-40ec-aa84-5465d1ef4edf, clientIf=5
11-17 11:23:27.186  5374  5496 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-17 11:23:27.186  5750  5788 D BtGatt.GattService: start scan with filters
,11-17 11:23:27.190  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-17 11:23:27.190  5750  5769 D BtGatt.ScanManager: handling starting scan
11-17 11:23:27.190  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.190  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-17 11:23:27.190  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.191  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-17 11:23:27.191  5374  5374 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-17 11:23:27.191  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.191  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-17 11:23:27.191  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-17 11:23:27.191  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.191  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.191  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.191  5374  5374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.192  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-17 11:23:27.192  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:23:27.194  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:23:27.194  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-17 11:23:27.194  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.194  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.194  5374  5374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.194  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-17 11:23:27.194  5374  5420 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-17 11:23:27.195  5374  5420 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-17 11:23:27.195  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-17 11:23:27.195  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-17 11:23:27.195  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-17 11:23:27.195  5374  5420 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-17 11:23:27.195  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-17 11:23:27.195  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:23:27.195  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-17 11:23:27.195  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3f53f32 removed from the list
11-17 11:23:27.195  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:23:27.195  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b595483 removed from the list
11-17 11:23:27.195  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
,11-17 11:23:27.195  5374  5420 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-17 11:23:27.195  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-17 11:23:27.195  5750  5766 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-17 11:23:27.195  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.195  5750  5766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 11:23:27.195  5374  5420 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-17 11:23:27.195  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-17 11:23:27.195  5374  5420 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-17 11:23:27.195  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-17 11:23:27.196  5750  5769 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-17 11:23:27.196  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.196  5374  5374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.196  5374  5374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.196  5374  5374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.197  5374  5374 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-17 11:23:27.197  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.197  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.197  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.197  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-17 11:23:27.197  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-17 11:23:27.197  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:23:27.197  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b595483 not in the list
11-17 11:23:27.197  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-17 11:23:27.197  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.197  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-17 11:23:27.197  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-17 11:23:27.197  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.197  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:23:27.198  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.198  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-17 11:23:27.198  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.200  5750  5766 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-17 11:23:27.200  5374  5420 D BluetoothAdapter: STATE_ON
11-17 11:23:27.200  5750  5766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 11:23:27.200  5750  5769 D BtGatt.ScanManager: Starting BLE batch scan
11-17 11:23:27.200  5750  5769 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-17 11:23:27.200  5750  5785 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-17 11:23:27.201  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-17 11:23:27.201  5374  5420 D BluetoothAdapter: STATE_ON
11-17 11:23:27.202  5750  5798 D BtGatt.GattService: stopScan() - queue size =1
11-17 11:23:27.202  5750  5761 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-17 11:23:27.203  3424  5837 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-17 11:23:27.203  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-17 11:23:27.203  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.203  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-17 11:23:27.203  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.203  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.203  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.203  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.203  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-17 11:23:27.203  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.203  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.203  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.203  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-17 11:23:27.203  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-17 11:23:27.204  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-17 11:23:27.205  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:23:27.206  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.206  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 11:23:27.206  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.206  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.206  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-17 11:23:27.206  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-17 11:23:27.206  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:23:27.206  5374  5374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 11:23:27.206  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@93c8e39 removed from the list
11-17 11:23:27.206  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 11:23:27.206  5374  5374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 11:23:27.206  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:23:27.206  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-17 11:23:27.207  5374  5374 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-17 11:23:27.207  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d1b1600 removed from the list
11-17 11:23:27.207  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.207  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-17 11:23:27.207  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-17 11:23:27.207  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.207  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.207  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.207  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-17 11:23:27.207  5374  5374 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 11:23:27.207  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@df1828a added. We now have 3 listener(s)
11-17 11:23:27.207  5374  5374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.207  5374  5374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main],, id: 1
11-17 11:23:27.208  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-17 11:23:27.208  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-17 11:23:27.209  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-17 11:23:27.209  5374  5374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.209  5374  5374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.209  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-17 11:23:27.209  5374  5374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.209  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@656d0fb added. We now have 4 listener(s)
11-17 11:23:27.209  5374  5420 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-17 11:23:27.209  5750  5766 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-17 11:23:27.209  5750  5766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 11:23:27.210  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-17 11:23:27.211  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-17 11:23:27.211  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c5a518 added. We now have 4 listener(s)
11-17 11:23:27.213  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-17 11:23:27.213  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-17 11:23:27.213  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-17 11:23:27.213  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-17 11:23:27.213  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c04cb71 added. We now have 5 listener(s)
11-17 11:23:27.213  5374  5420 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-17 11:23:27.213  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-17 11:23:27.213  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-17 11:23:27.214  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-17 11:23:27.214  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-17 11:23:27.214  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-17 11:23:27.214  5750  5766 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-17 11:23:27.214  5750  5766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-17 11:23:27.215  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-17 11:23:27.216  5750  5769 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-17 11:23:27.221  5750  5766 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-17 11:23:27.221  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-17 11:23:27.221  5750  5766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 11:23:27.221  5374  5420 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-17 11:23:27.221  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-17 11:23:27.221  5750  5766 E BtGatt.ContextMap: Context not found for ID 5
,11-17 11:23:27.225  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:23:27.226  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-17 11:23:27.226  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-17 11:23:27.226  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-17 11:23:27.226  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-17 11:23:27.232  5750  5766 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-17 11:23:27.232  5750  5766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 11:23:27.232  5750  5769 D BtGatt.ScanManager: stopping BLe Batch
11-17 11:23:27.232  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.232  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-17 11:23:27.232  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-17 11:23:27.232  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-17 11:23:27.232  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-17 11:23:27.232  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:23:27.233  5374  5420 D BluetoothAdapter: STATE_ON
11-17 11:23:27.235  5750  5788 D BtGatt.GattService: registerClient() - UUID=12435547-716f-4dbb-8c63-1d8e516cdfd7
,11-17 11:23:27.235  5750  5766 D BtGatt.GattService: onClientRegistered() - UUID=12435547-716f-4dbb-8c63-1d8e516cdfd7, clientIf=5
,11-17 11:23:27.236  5374  5385 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-17 11:23:27.237  5750  5760 D BtGatt.GattService: start scan with filters
11-17 11:23:27.237  5750  5766 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-17 11:23:27.237  5750  5766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 11:23:27.237  5750  5769 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-17 11:23:27.241  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-17 11:23:27.241  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.241  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-17 11:23:27.241  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.241  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-17 11:23:27.241  5374  5374 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-17 11:23:27.242  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.242  5750  5766 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-17 11:23:27.242  5750  5766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 11:23:27.242  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-17 11:23:27.242  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-17 11:23:27.242  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.242  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,11-17 11:23:27.242  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.242  5374  5374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-17 11:23:27.243  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-17 11:23:27.243  5750  5769 D BtGatt.ScanManager: handling starting scan
11-17 11:23:27.243  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.244  3424  5835 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-17 11:23:27.247  3424  5835 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
,11-17 11:23:27.249  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.249  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-17 11:23:27.249  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.249  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.249  5374  5374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.250  5750  5766 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-17 11:23:27.250  5750  5766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 11:23:27.250  5750  5769 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-17 11:23:27.252  5374  5420 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-17 11:23:27.252  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-17 11:23:27.252  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-17 11:23:27.252  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 11:23:27.252  5374  5420 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-17 11:23:27.252  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-17 11:23:27.252  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:23:27.252  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-17 11:23:27.252  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@df1828a removed from the list
11-17 11:23:27.252  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:23:27.253  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@656d0fb removed from the list
11-17 11:23:27.253  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
11-17 11:23:27.253  5374  5420 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-17 11:23:27.253  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-17 11:23:27.253  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.253  5374  5420 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-17 11:23:27.253  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-17 11:23:27.253  5374  5420 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-17 11:23:27.253  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-17 11:23:27.253  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.253  5374  5374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.253  5374  5374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.253  5374  5374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.253  5374  5374 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-17 11:23:27.254  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.254  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.254  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.254  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-17 11:23:27.254  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-17 11:23:27.254  5374  5420 I org.th,aliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:23:27.254  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@656d0fb not in the list
11-17 11:23:27.254  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-17 11:23:27.254  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.254  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-17 11:23:27.254  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-17 11:23:27.254  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.254  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.255  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.255  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-17 11:23:27.255  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.255  5374  5420 D BluetoothAdapter: STATE_ON
11-17 11:23:27.255  5750  5785 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-17 11:23:27.256  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-17 11:23:27.256  5374  5420 D BluetoothAdapter: STATE_ON
11-17 11:23:27.257  5750  5788 D BtGatt.GattService: stopScan() - queue size =1
11-17 11:23:27.259  5750  5798 D BtGatt.GattService: unregisterClient() - clientIf=5
11-17 11:23:27.259  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-17 11:23:27.259  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.259  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-17 11:23:27.259  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.259  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.259  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.259  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.259  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-17 11:23:27.259  5750  5766 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-17 11:23:27.259  5750  5766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 11:23:27.259  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.259  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:23:27.260  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.260  5750  5769 D BtGatt.ScanManager: Starting BLE batch scan
11-17 11:23:27.260  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-17 11:23:27.260  5750  5769 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-17 11:23:27.260  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-17 11:23:27.260  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-17 11:23:27.261  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.261  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.261  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 11:23:27.262  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.262  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.262  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-17 11:23:27.262  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-17 11:23:27.262  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-17 11:23:27.262  5374  5374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 11:23:27.262  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c04cb71 removed from the list
11-17 11:23:27.262  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 11:23:27.262  5374  5374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-17 11:23:27.262  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:23:27.262  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-17 11:23:27.262  5374  5374 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-17 11:23:27.262  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.262  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3c5a518 removed from the list
11-17 11:23:27.262  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-17 11:23:27.262  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-17 11:23:27.262  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-17 11:23:27.262  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.262  5374  5374 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.263  5374  5374 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-17 11:23:27.263  5374  5374 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.263  5374  5374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.263  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-17 11:23:27.263  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@117d8e2 added. We now have 3 listener(s)
11-17 11:23:27.264  5374  5374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-17 11:23:27.264  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-17 11:23:27.264  5374  5374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.264  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-17 11:23:27.264  5374  5374 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-17 11:23:27.264  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-17 11:23:27.264  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-17 11:23:27.264  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c086473 added. We now have 4 listener(s)
11-17 11:23:27.264  5374  5420 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-17 11:23:27.266  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-17 11:23:27.266  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-17 11:23:27.267  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21fff30 added. We now have 4 listener(s)
11-17 11:23:27.268  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-17 11:23:27.268  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-17 11:23:27.268  5374  5420 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-17 11:23:27.268  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-17 11:23:27.268  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68077a9 added. We now have 5 listener(s)
,11-17 11:23:27.268  5374  5420 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-17 11:23:27.268  5750  5766 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-17 11:23:27.268  5750  5766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 11:23:27.268  5374  5420 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-17 11:23:27.268  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-17 11:23:27.268  5374  5420 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-17 11:23:27.268  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 11:23:27.268  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-17 11:23:27.268  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-17 11:23:27.268  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@117d8e2 removed from the list
11-17 11:23:27.269  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:23:27.269  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c086473 removed from the list
11-17 11:23:27.269  5374  5420 D io.jxcore.node.ConnectivityMonitor: stop
11-17 11:23:27.269  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.269  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.272  3424  5837 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
11-17 11:23:27.272  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.273  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.273  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.273  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-17 11:23:27.273  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-17 11:23:27.273  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:23:27.273  5374  5420 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c086473 not in the list
11-17 11:23:27.273  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-53,5,main], id: 53
,11-17 11:23:27.273  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.274  5750  5766 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-17 11:23:27.274  5750  5766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 11:23:27.275  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.275  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.275  5374  5420 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-53,5,main], id: 53
11-17 11:23:27.275  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-17 11:23:27.275  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-17 11:23:27.275  5374  5420 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-17 11:23:27.275  5374  5420 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@68077a9 removed from the list
11-17 11:23:27.275  5374  5420 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-17 11:23:27.275  5374  5420 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-17 11:23:27.275  5374  5420 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-17 11:23:27.276  5374  5420 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@21fff30 removed from the list
11-17 11:23:27.276  5750  5769 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-17 11:23:27.276  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-17 11:23:27.277  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-17 11:23:27.277  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-17 11:23:27.277  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-17 11:23:27.277  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-17 11:23:27.277  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-17 11:23:27.282  5750  5766 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-17 11:23:27.282  5750  5766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 11:23:27.282  5750  5766 E BtGatt.ContextMap: Context not found for ID 5
,11-17 11:23:27.289  5750  5766 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-17 11:23:27.289  5750  5766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 11:23:27.289  5750  5769 D BtGatt.ScanManager: stopping BLe Batch
,11-17 11:23:27.293  5750  5766 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-17 11:23:27.293  5750  5766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-17 11:23:27.293  5750  5769 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-17 11:23:27.298  5750  5766 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-17 11:23:27.298  5750  5766 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-17 11:23:27.651  5374  5374 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-17 11:23:27.708  5374  5374 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-17 11:23:27.736  3424  5835 W Uploader:  no longer exists, so no auth token.
,11-17 11:23:27.742  3424  5839 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-17 11:23:27.762  5374  5374 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-17 11:23:27.802  3424  5837 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-17 11:23:27.864  3424  5839 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-17 11:23:27.934  3424  5837 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-17 11:23:28.136  3424  5839 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-17 11:23:28.193  3424  5835 W Uploader:  no longer exists, so no auth token.
,11-17 11:23:28.205  3424  5837 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-17 11:23:28.294  3424  5839 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-17 11:23:29.423  5374  5844 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 169, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-17 11:23:29.423  5374  5844 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-17 11:23:29.649   928  2873 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-17 11:23:30.226  5374  5844 W !!      : call onHalfStreamCopied
,11-17 11:23:30.226  5374  5844 I testCopyDataAndClose: closing input stream
,11-17 11:23:31.006  5374  5844 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 169, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].,
11-17 11:23:31.006  5374  5844 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-17 11:23:31.006  5374  5844 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
,11-17 11:23:31.006  5374  5844 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-17 11:23:31.006  5374  5844 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-17 11:23:31.006  5374  5844 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-17 11:23:31.006  5374  5844 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-17 11:23:31.006  5374  5844 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-17 11:23:31.006  5374  5844 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-17 11:23:31.006  5374  5844 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 169, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-17 11:23:31.006  5374  5844 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-17 11:23:32.675   928  2873 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-17 11:23:34.876   928  2873 D ConnectivityService: handlePromptUnvalidated 102
,11-17 11:23:35.087  5374  5845 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 172, name: My test thread name). Connection data: Peer properties: [null null].
11-17 11:23:35.087  5374  5845 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-17 11:23:35.693   928  2873 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-17 11:23:37.087  5374  5420 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 172. Connection data: Peer properties: [null null].
11-17 11:23:37.087  5374  5420 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-17 11:23:37.087  5374  5420 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 172, name: My test thread name)
,11-17 11:23:37.215  5374  5846 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 174, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-17 11:23:37.215  5374  5846 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-17 11:23:37.245  5374  5845 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-17 11:23:37.246  5374  5845 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 172, name: My test thread name). Connection data: Peer properties: [null null].
11-17 11:23:37.246  5374  5845 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 132 and the total number of bytes written 132
,11-17 11:23:37.864   928  2861 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 6, 7 -> obsolete
,11-17 11:23:38.259   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 11:23:38.830  5374  5846 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 174, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-17 11:23:38.830  5374  5846 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-17 11:23:38.830  5374  5846 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-17 11:23:38.830  5374  5846 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-17 11:23:38.830  5374  5846 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-17 11:23:38.830  5374  5846 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-17 11:23:38.830  5374  5846 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-17 11:23:38.830  5374  5846 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-17 11:23:38.830  5374  5846 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-17 11:23:38.830  5374  5846 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 174, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-17 11:23:38.830  5374  5846 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-17 11:23:39.260   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 11:23:40.262   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 11:23:41.263   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 11:23:42.264   535   535 I ServiceManager: Waiting for service AtCmdFwd...
,11-17 11:23:42.924  5374  5847 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 176, name: My test thread name). Connection data: Peer properties: [null null].
11-17 11:23:42.924  5374  5847 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-17 11:23:42.925  5374  5847 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 176, thread name: My test thread name). Connection data: Peer properties: [null null].
11-17 11:23:42.925  5374  5847 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-17 11:23:42.925  5374  5847 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-17 11:23:42.925  5374  5847 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-17 11:23:42.925  5374  5847 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-17 11:23:42.925  5374  5847 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-17 11:23:42.926  5374  5847 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-17 11:23:42.926  5374  5847 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-17 11:23:42.926  5374  5847 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-17 11:23:42.926  5374  5847 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 176, name: My test thread name). Connection data: Peer properties: [null null].
11-17 11:23:42.926  5374  5847 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-17 11:23:42.937  5374  5420 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-17 11:23:42.940  5374  5848 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-17 11:23:42.940  5374  5848 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-17 11:23:42.940  5374  5848 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 180, thread name: My test thread name): Test exception.
11-17 11:23:42.940  5374  5848 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-17 11:23:42.940  5374  5848 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-17 11:23:42.941  5374  5848 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-17 11:23:42.941  5374  5848 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-17 11:23:42.941  5374  5848 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-17 11:23:42.945  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-17 11:23:42.945  5374  5420 I jxcore-log: 
,11-17 11:23:42.946  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG UnitTest_app: 'Number of passed tests:  81'
11-17 11:23:42.946  5374  5420 I jxcore-log: 
11-17 11:23:42.946  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG UnitTest_app: 'Number of failed tests:  1'
11-17 11:23:42.946  5374  5420 I jxcore-log: 
11-17 11:23:42.946  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-17 11:23:42.946  5374  5420 I jxcore-log: 
11-17 11:23:42.946  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG UnitTest_app: 'Total duration:  86030'
11-17 11:23:42.946  5374  5420 I jxcore-log: 
,11-17 11:23:42.948  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG UnitTest_app: 'Failures: 
11-17 11:23:42.948  5374  5420 I jxcore-log:  DiscoveryManager1 isRunning should return true
11-17 11:23:42.948  5374  5420 I jxcore-log: Expected: is <true>
11-17 11:23:42.948  5374  5420 I jxcore-log:      but: was <false>
11-17 11:23:42.948  5374  5420 I jxcore-log: '
11-17 11:23:42.948  5374  5420 I jxcore-log: 
,11-17 11:23:42.949  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG UnitTest_app: 'Failed to execute UT.'
11-17 11:23:42.949  5374  5420 I jxcore-log: 
,11-17 11:23:42.951  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-17 11:23:42.951  5374  5420 I jxcore-log: 
,11-17 11:23:42.967  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-17 11:23:42.967  5374  5420 I jxcore-log: 
,11-17 11:23:42.972  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-17 11:23:42.972  5374  5420 I jxcore-log: 
11-17 11:23:42.972  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-17 11:23:42.972  5374  5420 I jxcore-log: 
,11-17 11:23:42.972  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-17 11:23:42.972  5374  5420 I jxcore-log: 
11-17 11:23:42.973  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-17 11:23:42.973  5374  5420 I jxcore-log: 
11-17 11:23:42.973  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-17 11:23:42.973  5374  5420 I jxcore-log: 
11-17 11:23:42.973  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-17 11:23:42.973  5374  5420 I jxcore-log: 
11-17 11:23:42.974  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-17 11:23:42.974  5374  5420 I jxcore-log: 
11-17 11:23:42.974  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-17 11:23:42.974  5374  5420 I jxcore-log: 
11-17 11:23:42.974  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-17 11:23:42.974  5374  5420 I jxcore-log: 
11-17 11:23:42.974  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-17 11:23:42.974  5374  5420 I jxcore-log: 
11-17 11:23:42.975  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-17 11:23:42.975  5374  5420 I jxcore-log: 
11-17 11:23:42.975  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-17 11:23:42.975  5374  5420 I jxcore-log: 
11-17 11:23:42.975  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-17 11:23:42.975  5374  5420 I jxcore-log: 
,11-17 11:23:42.975  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-17 11:23:42.975  5374  5420 I jxcore-log: 
11-17 11:23:42.976  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-17 11:23:42.976  5374  5420 I jxcore-log: 
11-17 11:23:42.976  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-17 11:23:42.976  5374  5420 I jxcore-log: 
11-17 11:23:42.976  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-17 11:23:42.976  5374  5420 I jxcore-log: 
,11-17 11:23:42.977  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-17 11:23:42.977  5374  5420 I jxcore-log: 
11-17 11:23:42.977  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-17 11:23:42.977  5374  5420 I jxcore-log: 
11-17 11:23:42.977  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-17 11:23:42.977  5374  5420 I jxcore-log: 
11-17 11:23:42.977  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-17 11:23:42.977  5374  5420 I jxcore-log: 
11-17 11:23:42.978  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-17 11:23:42.978  5374  5420 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-17 11:23:42.978  5374  5420 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-17 11:23:42.978  5374  5420 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
,11-17 11:23:42.979  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-17 11:23:42.979  5374  5420 I jxcore-log: 
11-17 11:23:42.980  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-17 11:23:42.980  5374  5420 I jxcore-log: 
11-17 11:23:42.980  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-17 11:23:42.980  5374  5420 I jxcore-log: 
11-17 11:23:42.980  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-17 11:23:42.980  5374  5420 I jxcore-log: 
11-17 11:23:42.980  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-17 11:23:42.980  5374  5420 I jxcore-log: 
,11-17 11:23:42.980  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-17 11:23:42.980  5374  5420 I jxcore-log: 
,11-17 11:23:42.981  5374  5374 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
11-17 11:23:42.982   928   938 D WifiService: setWifiEnabled: true pid=5374, uid=10077
11-17 11:23:42.982   928   938 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-17 11:23:42.985  5374  5420 D BluetoothAdapter: enable(): BT is already enabled..!
,11-17 11:23:42.989  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-17 11:23:42.989  5374  5420 I jxcore-log: 
,11-17 11:23:42.990  5374  5420 I jxcore-log: 2016-11-17 16:23:42 - WARN testUtils: 'myNameCallback not set!'
11-17 11:23:42.990  5374  5420 I jxcore-log: 
11-17 11:23:42.990  5804  5804 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-17 11:23:43.017   928  2861 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-17 11:23:43.017   928  2861 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-17 11:23:43.017   928  2861 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-17 11:23:43.018   928  2861 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-17 11:23:43.018  5804  5804 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=WORLD
,11-17 11:23:43.032   928  5808 D DhcpClient: Clearing IP address
,11-17 11:23:43.033   507   922 D CommandListener: Clearing all IP addresses on wlan0
,11-17 11:23:43.035   507   922 D CommandListener: Setting iface cfg
,11-17 11:23:43.040  3424  5833 V NativeCrypto: Read error: ssl=0x7f9eb42700: I/O error during system call, Connection timed out
,11-17 11:23:43.043  3424  5833 V NativeCrypto: SSL shutdown failed: ssl=0x7f9eb42700: I/O error during system call, Broken pipe
,11-17 11:23:43.045   928  3529 D ConnectivityService: reportNetworkConnectivity(102, false) by 10012
11-17 11:23:43.046   928  5806 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Forcing reevaluation for UID 10012
,11-17 11:23:43.048   928  5806 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-17 11:23:43.049   928  2873 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation failed
,11-17 11:23:43.049   928  2873 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-17 11:23:43.051   928  2873 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-17 11:23:43.060   928  2873 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-17 11:23:43.060   928  2873 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] got DISCONNECTED, was satisfying 3
,11-17 11:23:43.061   928  2861 D WifiStateMachine: Start Disconnecting Watchdog 1
,11-17 11:23:43.062   533   533 E Parcel  : Reading a NULL string not supported here.
,11-17 11:23:43.064   928  2861 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-17 11:23:43.066   507   922 D CommandListener: Clearing all IP addresses on wlan0
11-17 11:23:43.067   928  2873 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 102]
,11-17 11:23:43.070   928  2861 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-17 11:23:43.070  3603  3771 W QCNEJ   : |CORE| network lost: 102
11-17 11:23:43.071  3603  3771 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-17 11:23:43.073   928  5809 D DhcpClient: Receive thread stopped
,11-17 11:23:43.097   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-17 11:23:43.116   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-17 11:23:43.116   507   922 D TetherController: Setting IP forward enable = 0
,11-17 11:23:43.117   928  2873 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
11-17 11:23:43.117   928  2873 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-17 11:23:43.120   928   945 D Tethering: MasterInitialState.processMessage what=3
,11-17 11:23:43.128  3792  3792 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-17 11:23:43.131  3541  3541 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-17 11:23:43.133  4898  4921 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-17 11:23:43.133  4898  4921 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-17 11:23:43.133  4898  4921 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-17 11:23:43.133  4898  4921 E SarControlService: no key has been found,reset the power
11-17 11:23:43.133  4898  4935 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-17 11:23:43.133  4898  4935 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,11-17 11:23:43.133  4898  4935 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-17 11:23:43.134  4923  4923 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-17 11:23:43.134  4923  4923 D QcrilMsgTunnelSocket: [1010] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-17 11:23:43.135  4898  4935 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-17 11:23:43.135  4898  4935 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-17 11:23:43.135  4898  4935 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-17 11:23:43.136  4923  4923 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-17 11:23:43.136  4923  4923 D QcrilMsgTunnelSocket: [1011] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-17 11:23:43.136  4923  4937 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@95f0491 HexData = [00000000f203000000000000ffffffff]
11-17 11:23:43.137  4923  4937 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-17 11:23:43.137  4923  4937 D QcrilMsgTunnelSocket: [1010] < OEM_HOOK_RAW [null]
11-17 11:23:43.137  4923  4923 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-17 11:23:43.138  4898  4908 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-17 11:23:43.138  4923  4937 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@95f0491 HexData = [00000000f303000000000000ffffffff]
11-17 11:23:43.138  4923  4937 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-17 11:23:43.138  4923  4937 D QcrilMsgTunnelSocket: [1011] < OEM_HOOK_RAW [null]
11-17 11:23:43.139  4923  4923 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-17 11:23:43.140  4898  4909 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-17 11:23:43.143  3541  3541 D SystemUpdateService: onCreate
,11-17 11:23:43.146  3541  3541 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-17 11:23:43.162  3541  3541 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-17 11:23:43.165   507   922 E Netd    : netlink response contains error (No such file or directory)
,11-17 11:23:43.166  3541  5564 I iu.UploadsManager: num queued entries: 0
11-17 11:23:43.166   507   922 D TetherController: Setting IP forward enable = 0
11-17 11:23:43.166  3541  5564 I iu.UploadsManager: num updated entries: 0
11-17 11:23:43.167  3541  5866 I SystemUpdateService: active receiver: enabled
11-17 11:23:43.168   928  2873 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-17 11:23:43.171  3541  3541 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
11-17 11:23:43.172  3541  3541 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-17 11:23:43.174  5567  5567 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-17 11:23:43.178  5567  5567 D SprintDMHelper: simOperator: 
11-17 11:23:43.178  5567  5567 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-17 11:23:43.186  3541  5866 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-17 11:23:43.188  3541  5564 I iu.SyncManager: NEXT; no task
,11-17 11:23:43.190  4872  5871 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-17 11:23:43.198  3541  5866 I SystemUpdateService: network: null; metered: false; mobile allowed: true
11-17 11:23:43.198  3541  5866 I SystemUpdateService: now status is 0 (complete)
,11-17 11:23:43.198  3541  5866 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-17 11:23:43.199  3541  5866 I SystemUpdateService: file has been verified
11-17 11:23:43.199  3541  5866 I SystemUpdateService: OTA package size = 21989297
,11-17 11:23:43.207  3541  5866 I SystemUpdateService: showing system update notification
,11-17 11:23:43.218  3541  3541 D SystemUpdateService: onDestroy
,11-17 11:23:43.264   535   535 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-17 11:23:44.967  5374  5420 I jxcore-log: 2016-11-17 16:23:44 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-17 11:23:44.967  5374  5420 I jxcore-log: 
,11-17 11:23:44.970  5374  5420 I jxcore-log: 2016-11-17 16:23:44 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-17 11:23:44.970  5374  5420 I jxcore-log: 
,11-17 11:23:45.312  5374  5420 I jxcore-log: 2016-11-17 16:23:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-17 11:23:45.312  5374  5420 I jxcore-log: 
,11-17 11:23:45.323  5374  5420 I jxcore-log: 2016-11-17 16:23:45 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-17 11:23:45.323  5374  5420 I jxcore-log: 
,11-17 11:23:46.148  5804  5804 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-17 11:23:46.161  5804  5804 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-17 11:23:46.170  5804  5804 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-17 11:23:46.202   928  2861 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=14.00 rxSuccessRate=12.00 delta 1000 -> 994
,11-17 11:23:46.203   928  2861 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
,11-17 11:23:46.203   928  2861 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-17 11:23:46.220   928  2861 D WifiConfigStore: Setting BSSID for "NG700"WPA_PSK to any
,11-17 11:23:46.234   928  2861 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-17 11:23:46.235  5804  5804 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-17 11:23:46.449  5374  5420 I jxcore-log: 2016-11-17 16:23:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-17 11:23:46.449  5374  5420 I jxcore-log: 
,11-17 11:23:46.637  5374  5420 I jxcore-log: 2016-11-17 16:23:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-17 11:23:46.637  5374  5420 I jxcore-log: 
,11-17 11:23:46.642  5374  5420 I jxcore-log: 2016-11-17 16:23:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-17 11:23:46.642  5374  5420 I jxcore-log: 
,11-17 11:23:46.644  5804  5804 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-17 11:23:46.647  5374  5420 I jxcore-log: 2016-11-17 16:23:46 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-17 11:23:46.647  5374  5420 I jxcore-log: 
,11-17 11:23:46.677  5804  5804 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-17 11:23:46.678  5804  5804 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-17 11:23:46.685   928  2861 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{103}  lp{{InterfaceName: wlan0 LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-17 11:23:46.685   928  2861 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-17 11:23:46.686   928  2873 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-17 11:23:46.700   928  2861 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-17 11:23:46.711   507   922 D CommandListener: Setting iface cfg
,11-17 11:23:46.713   928  2861 D WifiStateMachine: Start Dhcp Watchdog 4
,11-17 11:23:46.723   928  2873 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 103] to 60
,11-17 11:23:46.723   928  2861 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-17 11:23:46.727   928  5875 D DhcpClient: Receive thread started
,11-17 11:23:46.808   928  2861 E native  : do suspend false
,11-17 11:23:46.823   928  5808 D DhcpClient: Broadcasting DHCPDISCOVER
,11-17 11:23:46.836   928  5875 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172780, domain null
,11-17 11:23:46.837   928  5808 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172780 seconds
,11-17 11:23:46.839   928  5808 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-17 11:23:46.851   928  5875 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-17 11:23:46.851   928  5808 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-17 11:23:46.854   507   922 D CommandListener: Setting iface cfg
,11-17 11:23:46.858   928  2861 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-17 11:23:46.861   928  5808 D DhcpClient: Scheduling renewal in 86399s
,11-17 11:23:46.867   928  2861 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
11-17 11:23:46.868   928  2861 D WifiConfigStore: No blacklist allowed without epno enabled
,11-17 11:23:46.869   928  2873 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
11-17 11:23:46.869   928  2873 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-17 11:23:46.871   928  2873 D ConnectivityService: Adding iface wlan0 to network 103
,11-17 11:23:46.875   928  2861 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-17 11:23:46.922   928  2873 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-17 11:23:46.923   928  2873 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 103
,11-17 11:23:46.924   928  2873 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 103
,11-17 11:23:46.927   928  2873 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 103
,11-17 11:23:46.929   928  2873 D ConnectivityService: Setting Dns servers for network 103 to [/192.168.1.1]
11-17 11:23:46.932   928  2861 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 7, 8 -> obsolete
,11-17 11:23:46.938   928  2873 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 103]
,11-17 11:23:46.942   928  2873 D ConnectivityService: scheduleUnvalidatedPrompt 103
,11-17 11:23:46.942   928  2873 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 103]
11-17 11:23:46.942   928  2873 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 103]
11-17 11:23:46.942   928  2873 D ConnectivityService:    accepting network in place of null
11-17 11:23:46.942   928  2861 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-17 11:23:46.942   928  2861 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-17 11:23:46.943   928  2873 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{103}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -52]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-17 11:23:46.953   928  5874 D NetlinkSocketObserver: NeighborEvent{elapsedMs=197264, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-17 11:23:46.963   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-17 11:23:46.984   507   922 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-17 11:23:46.988   928  2873 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 103] isDefaultNetwork=true
11-17 11:23:46.988   928  2873 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-17 11:23:46.988  3603  3771 W QCNEJ   : |CORE| network available: 103
,11-17 11:23:46.989   928  2873 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 103]
11-17 11:23:46.990   928   945 D Tethering: MasterInitialState.processMessage what=3
11-17 11:23:46.991  3603  3771 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-17 11:23:46.992  3603  3771 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
,11-17 11:23:46.993  3603  3771 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-17 11:23:47.002  4898  4921 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-17 11:23:47.002  4898  4921 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-17 11:23:47.002  4898  4921 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-17 11:23:47.002  4898  4921 E SarControlService: no key has been found,reset the power
11-17 11:23:47.002  4898  4935 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-17 11:23:47.002  4898  4935 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
,11-17 11:23:47.002  4898  4935 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-17 11:23:47.003  4923  4923 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-17 11:23:47.003  4923  4923 D QcrilMsgTunnelSocket: [1012] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-17 11:23:47.005  3792  3792 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
11-17 11:23:47.006  4898  4935 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-17 11:23:47.006  4898  4935 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-17 11:23:47.006  4898  4935 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-17 11:23:47.006  4923  4923 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-17 11:23:47.007  4923  4923 D QcrilMsgTunnelSocket: [1013] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-17 11:23:47.008  3541  3541 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-17 11:23:47.012  4923  4937 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@95f0491 HexData = [00000000f403000000000000ffffffff]
,11-17 11:23:47.012  4923  4937 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-17 11:23:47.012  4923  4937 D QcrilMsgTunnelSocket: [1012] < OEM_HOOK_RAW [null]
11-17 11:23:47.012  4923  4923 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-17 11:23:47.012  4898  4908 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-17 11:23:47.014  3541  3541 D SystemUpdateService: onCreate
,11-17 11:23:47.019  4923  4937 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@95f0491 HexData = [00000000f503000000000000ffffffff]
,11-17 11:23:47.019  4923  4937 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-17 11:23:47.019  4923  4937 D QcrilMsgTunnelSocket: [1013] < OEM_HOOK_RAW [null]
11-17 11:23:47.020  4923  4923 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-17 11:23:47.020  4898  4909 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-17 11:23:47.021  3541  3541 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-17 11:23:47.030   928  5873 D NetworkMonitor/NetworkAgentInfo [WIFI () - 103]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=216.58.214.238,2a00:1450:400d:803::200e
,11-17 11:23:47.035  3541  3541 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-17 11:23:47.041  3541  5564 I iu.UploadsManager: num queued entries: 0
,11-17 11:23:47.041  3541  5564 I iu.UploadsManager: num updated entries: 0
11-17 11:23:47.042  3541  5564 I iu.SyncManager: NEXT; no task
,11-17 11:23:47.044  3541  5887 I SystemUpdateService: active receiver: enabled
,11-17 11:23:47.046  3541  3541 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-17 11:23:47.047  3541  3541 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
11-17 11:23:47.049  5567  5567 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-17 11:23:47.052  5567  5567 D SprintDMHelper: simOperator: 
11-17 11:23:47.052  5567  5567 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-17 11:23:47.080  5374  5420 I jxcore-log: 2016-11-17 16:23:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-17 11:23:47.080  5374  5420 I jxcore-log: 
,11-17 11:23:47.083   928  5873 D NetworkMonitor/NetworkAgentInfo [WIFI () - 103]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Thu, 17 Nov 2016 16:23:47 GMT], X-Android-Received-Millis=[1479399827082], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479399827057]}
,11-17 11:23:47.084   928  2873 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-17 11:23:47.084   928  2873 D ConnectivityService: NetworkAgentInfo [WIFI () - 103] validation  passed
11-17 11:23:47.084   928  2873 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 103]
11-17 11:23:47.085   928  2873 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-17 11:23:47.091  3541  5887 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-17 11:23:47.098  3541  5887 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-17 11:23:47.098  3541  5887 I SystemUpdateService: now status is 0 (complete)
11-17 11:23:47.098  3541  5887 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-17 11:23:47.098  3541  5887 I SystemUpdateService: file has been verified
11-17 11:23:47.098  3541  5887 I SystemUpdateService: OTA package size = 21989297
,11-17 11:23:47.107  3541  5887 I SystemUpdateService: showing system update notification
,11-17 11:23:47.116  3541  3541 D SystemUpdateService: onDestroy
,11-17 11:23:47.120  5374  5420 I jxcore-log: 2016-11-17 16:23:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-17 11:23:47.120  5374  5420 I jxcore-log: 
,11-17 11:23:47.131  5374  5420 I jxcore-log: 2016-11-17 16:23:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-17 11:23:47.131  5374  5420 I jxcore-log: 
,11-17 11:23:47.134  5374  5420 I jxcore-log: 2016-11-17 16:23:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-17 11:23:47.134  5374  5420 I jxcore-log: 
,11-17 11:23:47.175  4872  5892 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-17 11:23:47.386  5374  5420 I jxcore-log: 2016-11-17 16:23:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-17 11:23:47.386  5374  5420 I jxcore-log: 
,11-17 11:23:47.512  5374  5420 I jxcore-log: 2016-11-17 16:23:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-17 11:23:47.512  5374  5420 I jxcore-log: 
,11-17 11:23:47.886  5374  5420 I jxcore-log: 2016-11-17 16:23:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-17 11:23:47.886  5374  5420 I jxcore-log: 
,11-17 11:23:47.895  5374  5420 I jxcore-log: 2016-11-17 16:23:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-17 11:23:47.895  5374  5420 I jxcore-log: 
,11-17 11:23:47.898  5374  5420 I jxcore-log: 2016-11-17 16:23:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-17 11:23:47.898  5374  5420 I jxcore-log: 
,11-17 11:23:47.903  5374  5420 I jxcore-log: 2016-11-17 16:23:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-17 11:23:47.903  5374  5420 I jxcore-log: 
,11-17 11:23:47.908  5374  5420 I jxcore-log: 2016-11-17 16:23:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-17 11:23:47.908  5374  5420 I jxcore-log: 
,11-17 11:23:47.935  5374  5420 I jxcore-log: 2016-11-17 16:23:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-17 11:23:47.935  5374  5420 I jxcore-log: 
,11-17 11:23:47.971  5374  5420 I jxcore-log: 2016-11-17 16:23:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-17 11:23:47.971  5374  5420 I jxcore-log: 
,11-17 11:23:47.979  5374  5420 I jxcore-log: 2016-11-17 16:23:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-17 11:23:47.979  5374  5420 I jxcore-log: 
,11-17 11:23:47.986  5374  5420 I jxcore-log: 2016-11-17 16:23:47 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-17 11:23:47.986  5374  5420 I jxcore-log: 
,11-17 11:23:47.989   928  2873 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 102] cleared because we found a replacement network
,11-17 11:23:48.001  5374  5420 I jxcore-log: 2016-11-17 16:23:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-17 11:23:48.001  5374  5420 I jxcore-log: 
,11-17 11:23:48.016  5374  5420 I jxcore-log: 2016-11-17 16:23:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-17 11:23:48.016  5374  5420 I jxcore-log: 
,11-17 11:23:48.022  5374  5420 I jxcore-log: 2016-11-17 16:23:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-17 11:23:48.022  5374  5420 I jxcore-log: 
,11-17 11:23:48.027  5374  5420 I jxcore-log: 2016-11-17 16:23:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-17 11:23:48.027  5374  5420 I jxcore-log: 
,11-17 11:23:48.040  5374  5420 I jxcore-log: 2016-11-17 16:23:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-17 11:23:48.040  5374  5420 I jxcore-log: 
,11-17 11:23:48.058  5374  5420 I jxcore-log: 2016-11-17 16:23:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-17 11:23:48.058  5374  5420 I jxcore-log: 
,11-17 11:23:48.073  5374  5420 I jxcore-log: 2016-11-17 16:23:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-17 11:23:48.073  5374  5420 I jxcore-log: 
,11-17 11:23:48.084  5374  5420 I jxcore-log: 2016-11-17 16:23:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-17 11:23:48.084  5374  5420 I jxcore-log: 
,11-17 11:23:48.098  5374  5420 I jxcore-log: 2016-11-17 16:23:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-17 11:23:48.098  5374  5420 I jxcore-log: 
,11-17 11:23:48.108  5374  5420 I jxcore-log: 2016-11-17 16:23:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-17 11:23:48.108  5374  5420 I jxcore-log: 
,11-17 11:23:48.121  5374  5420 I jxcore-log: 2016-11-17 16:23:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-17 11:23:48.121  5374  5420 I jxcore-log: 
,11-17 11:23:48.131  5374  5420 I jxcore-log: 2016-11-17 16:23:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-17 11:23:48.131  5374  5420 I jxcore-log: 
,11-17 11:23:48.148  5374  5420 I jxcore-log: 2016-11-17 16:23:48 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-17 11:23:48.148  5374  5420 I jxcore-log: 
,11-17 11:23:48.170  5374  5420 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-17 11:23:48.171  5374  5420 I jxcore-log: 2016-11-17 16:23:48 - INFO testUtils: 'BLE multiple advertisement supported'
11-17 11:23:48.171  5374  5420 I jxcore-log: 
,11-17 11:23:48.202  5374  5420 I jxcore-log: 2016-11-17 16:23:48 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-17 11:23:48.202  5374  5420 I jxcore-log: 
,11-17 11:23:48.247  5374  5420 I jxcore-log: 2016-11-17 16:23:48 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 11:23:48.247  5374  5420 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 11:23:48.247  5374  5420 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 11:23:48.247  5374  5420 I jxcore-log: emit@events.js:82:1
11-17 11:23:48.247  5374  5420 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 11:23:48.247  5374  5420 I jxcore-log: emit@events.js:82:1''
11-17 11:23:48.247  5374  5420 I jxcore-log: 
,11-17 11:23:48.247  5374  5420 I jxcore-log: 2016-11-17 16:23:48 - DEBUG CoordinatedClient: 'test client failed'
11-17 11:23:48.247  5374  5420 I jxcore-log: 
,11-17 11:23:48.250  5374  5420 I jxcore-log: 2016-11-17 16:23:48 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-17 11:23:48.250  5374  5420 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-17 11:23:48.250  5374  5420 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-17 11:23:48.250  5374  5420 I jxcore-log: emit@events.js:82:1
11-17 11:23:48.250  5374  5420 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-17 11:23:48.250  5374  5420 I jxcore-log: emit@events.js:82:1''
11-17 11:23:48.250  5374  5420 I jxcore-log: 
11-17 11:23:48.250  5374  5420 I jxcore-log: 2016-11-17 16:23:48 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-17 11:23:48.250  5374  5420 I jxcore-log: 
,11-17 11:23:48.736  5899  5899 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-17 11:23:48.743  5899  5899 D AndroidRuntime: CheckJNI is OFF
,11-17 11:23:48.770  5899  5899 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-17 11:23:48.797  5899  5899 I Radio-JNI: register_android_hardware_Radio DONE
,11-17 11:23:48.813  5899  5899 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-17 11:23:48.821   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-17 11:23:48.822   928   941 I ActivityManager: Killing 5374:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-17 11:23:48.907   928  3723 I WindowState: WIN DEATH: Window{db1ae85 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-17 11:23:48.907   928   939 D GraphicsStats: Buffer count: 2
,11-17 11:23:48.909   928  2868 D WifiService: Client connection lost with reason: 4
,11-17 11:23:48.965   928   951 I art     : Starting a blocking GC Explicit
,11-17 11:23:48.964   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
11-17 11:23:48.966   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,11-17 11:23:48.967   928   941 E ActivityManager: Failure starting process com.test.thalitest
11-17 11:23:48.967   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-17 11:23:48.967   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-17 11:23:48.967   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-17 11:23:48.967   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-17 11:23:48.967   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-17 11:23:48.967   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-17 11:23:48.967   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-17 11:23:48.967   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-17 11:23:48.967   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-17 11:23:48.967   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-17 11:23:48.967   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-17 11:23:48.967   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-17 11:23:48.967   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-17 11:23:48.967   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-17 11:23:48.967   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-17 11:23:48.967   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 11:23:48.967   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-17 11:23:48.967   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 11:23:48.967   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-17 11:23:48.967   928   941 I ActivityManager:   Force finishing activity ActivityRecord{b3bcc6e u0 com.test.thalitest/.MainActivity t6}
,11-17 11:23:48.981   928   946 W WindowManager: Attempted to add application window with unknown token Token{bd3bf0f ActivityRecord{b3bcc6e u0 com.test.thalitest/.MainActivity t6 f}}.  Aborting.
,11-17 11:23:48.981   928   946 W WindowManager: Token{bd3bf0f ActivityRecord{b3bcc6e u0 com.test.thalitest/.MainActivity t6 f}} already running, starting window not displayed. Unable to add window -- token Token{bd3bf0f ActivityRecord{b3bcc6e u0 com.test.thalitest/.MainActivity t6 f}} is not valid; is your activity running?
11-17 11:23:48.981   928   946 W WindowManager: view not successfully added to wm, removing view
11-17 11:23:48.982   928   946 W WindowManager: Exception when adding starting window
11-17 11:23:48.982   928   946 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{e0924fa V.E...... R.....ID 0,0-0,0} not attached to window manager
11-17 11:23:48.982   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
11-17 11:23:48.982   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
11-17 11:23:48.982   928   946 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
11-17 11:23:48.982   928   946 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
11-17 11:23:48.982   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
11-17 11:23:48.982   928   946 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 11:23:48.982   928   946 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
11-17 11:23:48.982   928   946 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-17 11:23:48.982   928   946 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-17 11:23:48.982   928  3711 W ActivityManager: Spurious death for ProcessRecord{6851aab 0:com.test.thalitest/u0a77}, curProc for 5374: null
,11-17 11:23:49.054   928   951 I art     : Explicit concurrent mark sweep GC freed 79601(5MB) AllocSpace objects, 18(628KB) LOS objects, 33% free, 29MB/43MB, paused 1.765ms total 88.751ms
,11-17 11:23:49.077   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-17 11:23:49.080  5899  5899 I art     : System.exit called, status: 0
11-17 11:23:49.080  5899  5899 I AndroidRuntime: VM exiting with result code 0.
,11-17 11:23:49.084   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-17 11:23:49.093   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,11-17 11:23:49.097  3528  3528 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-17 11:23:49.098  5750  5750 D BluetoothMapAppObserver: onReceive
,11-17 11:23:49.098  5750  5750 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-17 11:23:49.101  3911  4012 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-17 11:23:49.102   928  2842 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-17 11:23:49.113  3528  5910 I Keyboard.Facilitator.DecoderInitializer: run()
,11-17 11:23:49.126  3271  5911 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-17 11:23:49.136  3528  5910 I Decoder : createOrResetDecoder
,11-17 11:23:49.144  3656  3656 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-17 11:23:49.153  3424  3424 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-17 11:23:49.153  3424  3424 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-17 11:23:49.170   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-17 11:23:49.174  3541  5916 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-17 11:23:49.174  3541  5916 D AccountUtils: Clearing selected account for com.test.thalitest
,11-17 11:23:49.190  3424  3424 I ConfigService: onCreate
,11-17 11:23:49.195    17    17 W kworker/2:0: type=1400 audit(0.0:112): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-17 11:23:49.199    17    17 W kworker/2:0: type=1400 audit(0.0:113): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-17 11:23:49.210  3528  5910 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-17 11:23:49.221   928  3438 I ActivityManager: Start proc 5921:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
11-17 11:23:49.222  3686  3834 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-17 11:23:49.222  3686  3834 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3686
11-17 11:23:49.222  3686  3834 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
11-17 11:23:49.222  3686  3834 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-17 11:23:49.222  3686  3834 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-17 11:23:49.222  3686  3834 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-17 11:23:49.222  3686  3834 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-17 11:23:49.222  3686  3834 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-17 11:23:49.222  3686  3834 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-17 11:23:49.222  3686  3834 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-17 11:23:49.222  3686  3834 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-17 11:23:49.222  3686  3834 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-17 11:23:49.222  3686  3834 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-17 11:23:49.222  3686  3834 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-17 11:23:49.222    17    17 W kworker/2:0: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-17 11:23:49.228   928   938 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-17 11:23:49.235  3686  3834 I Process : Sending signal. PID: 3686 SIG: 9
,11-17 11:23:49.241  3541  5916 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-17 11:23:49.255  3541  5916 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-17 11:23:49.255  3541  5916 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 11:23:49.255  3541  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 11:23:49.255  3541  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-17 11:23:49.255  3541  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-17 11:23:49.255  3541  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 11:23:49.255  3541  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 11:23:49.255  3541  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 11:23:49.255  3541  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-17 11:23:49.255  3541  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-17 11:23:49.255  3541  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-17 11:23:49.255  3541  5916 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-17 11:23:49.255  3541  5916 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-17 11:23:49.255  3541  5916 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-17 11:23:49.255  3541  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 11:23:49.255  3541  5916 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-17 11:23:49.255  3541  5916 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-17 11:23:49.255  3541  5916 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-17 11:23:49.255  3541  5916 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 11:23:49.255  3541  5916 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-17 11:23:49.255  3541  5916 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-17 11:23:49.262  3541  5916 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-17 11:23:49.262  3541  5916 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-17 11:23:49.262  3541  5916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-17 11:23:49.262  3541  5916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-17 11:23:49.262  3541  5916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-17 11:23:49.262  3541  5916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-17 11:23:49.262  3541  5916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-17 11:23:49.262  3541  5916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-17 11:23:49.262  3541  5916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-17 11:23:49.262  3541  5916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-17 11:23:49.262  3541  5916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-17 11:23:49.262  3541  5916 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-17 11:23:49.262  3541  5916 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-17 11:23:49.262  3541  5916 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-17 11:23:49.262  3541  5916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-17 11:23:49.262  3541  5916 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-17 11:23:49.262  3541  5916 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-17 11:23:49.262  3541  5916 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-17 11:23:49.262  3541  5916 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-17 11:23:49.262  3541  5916 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-17 11:23:49.262  3541  5916 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-17 11:23:49.263  3541  5916 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,11-17 11:23:49.281   928  5929 E DropBoxManagerService: Can't write: system_app_crash
11-17 11:23:49.281   928  5929 E DropBoxManagerService: java.io.IOException: write failed: EROFS (Read-only file system)
11-17 11:23:49.281   928  5929 E DropBoxManagerService: 	at libcore.io.IoBridge.write(IoBridge.java:498)
11-17 11:23:49.281   928  5929 E DropBoxManagerService: 	at java.io.FileOutputStream.write(FileOutputStream.java:186)
11-17 11:23:49.281   928  5929 E DropBoxManagerService: 	at java.io.BufferedOutputStream.flushInternal(BufferedOutputStream.java:185)
11-17 11:23:49.281   928  5929 E DropBoxManagerService: 	at java.io.BufferedOutputStream.flush(BufferedOutputStream.java:85)
11-17 11:23:49.281   928  5929 E DropBoxManagerService: 	at java.io.FilterOutputStream.close(FilterOutputStream.java:61)
11-17 11:23:49.281   928  5929 E DropBoxManagerService: 	at java.io.BufferedOutputStream.close(BufferedOutputStream.java:152)
11-17 11:23:49.281   928  5929 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:230)
11-17 11:23:49.281   928  5929 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-17 11:23:49.281   928  5929 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-17 11:23:49.281   928  5929 E DropBoxManagerService: Caused by: android.system.ErrnoException: write failed: EROFS (Read-only file system)
11-17 11:23:49.281   928  5929 E DropBoxManagerService: 	at libcore.io.Posix.writeBytes(Native Method)
11-17 11:23:49.281   928  5929 E DropBoxManagerService: 	at libcore.io.Posix.write(Posix.java:271)
11-17 11:23:49.281   928  5929 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.write(BlockGuardOs.java:313)
11-17 11:23:49.281   928  5929 E DropBoxManagerService: 	at libcore.io.IoBridge.write(IoBridge.java:493)
11-17 11:23:49.281   928  5929 E DropBoxManagerService: 	... 8 more
,11-17 11:23:49.310  3541  3541 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
11-17 11:23:49.310  3541  3541 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,11-17 11:23:49.324  3541  3541 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
,11-17 11:23:49.324  3541  3541 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,11-17 11:23:49.339   383   383 E lowmemorykiller: Error writing /proc/3686/oom_score_adj; errno=22
,11-17 11:23:49.339   928   938 E JavaBinder: !!! FAILED BINDER TRANSACTION !!!  (parcel size = 2712)
11-17 11:23:49.340   928   938 W BroadcastQueue: Exception when sending broadcast to ComponentInfo{com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver}
11-17 11:23:49.340   928   938 W BroadcastQueue: android.os.DeadObjectException: Transaction failed on small parcel; remote process probably died
11-17 11:23:49.340   928   938 W BroadcastQueue: 	at android.os.BinderProxy.transactNative(Native Method)
11-17 11:23:49.340   928   938 W BroadcastQueue: 	at android.os.BinderProxy.transact(Binder.java:503)
11-17 11:23:49.340   928   938 W BroadcastQueue: 	at android.app.ApplicationThreadProxy.scheduleReceiver(ApplicationThreadNative.java:891)
11-17 11:23:49.340   928   938 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processCurBroadcastLocked(BroadcastQueue.java:273)
11-17 11:23:49.340   928   938 W BroadcastQueue: 	at com.android.server.am.BroadcastQueue.processNextBroadcast(BroadcastQueue.java:1039)
11-17 11:23:49.340   928   938 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.finishReceiver(ActivityManagerService.java:17151)
11-17 11:23:49.340   928   938 W BroadcastQueue: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:496)
11-17 11:23:49.340   928   938 W BroadcastQueue: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2489)
11-17 11:23:49.340   928   938 W BroadcastQueue: 	at android.os.Binder.execTransact(Binder.java:453)
,11-17 11:23:49.365   928  3069 D GraphicsStats: Buffer count: 1
,11-17 11:23:49.365   928  3068 I WindowState: WIN DEATH: Window{6dca7c8 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,11-17 11:23:49.372   928   938 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,11-17 11:23:49.384   928   938 I ActivityManager: Start proc 5942:com.google.android.googlequicksearchbox/u0a29 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
,11-17 11:23:49.388   928  3680 W ActivityManager: Spurious death for ProcessRecord{62835f3 5942:com.google.android.googlequicksearchbox/u0a29}, curProc for 3686: null
,11-17 11:23:49.390  3792  5939 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,11-17 11:23:49.442  3541  5938 W BaseAppContext: Using Auth Proxy for data requests.
,11-17 11:23:49.446  3541  5938 W BaseAppContext: Using Auth Proxy for data requests.
,11-17 11:23:49.487  3541  3541 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
,11-17 11:23:49.503  3541  5956 I GMPM-SVC: App measurement is starting up
,11-17 11:23:49.512  3541  5956 E GMPM-SVC: AppMeasurementService not registered/enabled
,11-17 11:23:49.513  3541  5956 E GMPM-SVC: Uploading is not possible. App measurement disabled
,11-17 11:23:49.606   385   479 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
