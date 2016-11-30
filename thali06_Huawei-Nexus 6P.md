#### Test 95813110567bbc2_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-30 16:37:56.066  5640  5681 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,--------- beginning of system
11-30 16:37:56.258   926  3613 I ActivityManager: Killing 5125:com.google.android.apps.maps/u0a58 (adj 15): empty #17
11-30 16:37:56.431  5640  5692 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
11-30 16:37:56.459  3998  3998 I ConfigFetchService: fetch service done; releasing wakelock
11-30 16:37:56.460  3998  3998 I ConfigFetchService: stopping self
11-30 16:37:56.493  5640  5692 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
11-30 16:37:56.496  3998  4994 I Icing   : Indexing F030E08B5368E93E2F43DEEC3A6B244C622F15EE from com.google.android.googlequicksearchbox
11-30 16:37:56.508  5689  5689 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-30 16:37:56.511  5689  5689 D AndroidRuntime: CheckJNI is OFF
11-30 16:37:56.534  5689  5689 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-30 16:37:56.563  5689  5689 I Radio-JNI: register_android_hardware_Radio DONE
11-30 16:37:56.578  5689  5689 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-30 16:37:56.581   926  3633 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-30 16:37:56.601  5640  5692 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
11-30 16:37:56.612   926  3633 I ActivityManager: Start proc 5706:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-30 16:37:56.619  5689  5689 D AndroidRuntime: Shutting down VM
11-30 16:37:56.628  3998  4994 I Icing   : Indexing done F030E08B5368E93E2F43DEEC3A6B244C622F15EE
,11-30 16:37:56.937   926  3244 I WindowManager: Screenshot max retries 4 of Token{263e4b3 ActivityRecord{2c3222 u0 com.test.thalitest/.MainActivity t10}} appWin=Window{7d5e37a u0 Starting com.test.thalitest} drawState=2
,11-30 16:37:57.023  5706  5706 I CordovaLog: Changing log level to DEBUG(3)
11-30 16:37:57.023  5706  5706 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-30 16:37:57.023  5706  5706 D CordovaActivity: CordovaActivity.onCreate()
,11-30 16:37:57.030  5706  5706 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-30 16:37:57.064  5706  5706 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-30 16:37:57.132  5706  5706 I LibraryLoader: Time to load native libraries: 57 ms (timestamps 6102-6159)
,11-30 16:37:57.132  5706  5706 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-30 16:37:57.172  5706  5706 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {c0ff852}
,11-30 16:37:57.173  5706  5706 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-30 16:37:57.173  5706  5706 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-30 16:37:57.179  5706  5706 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-30 16:37:57.180  5706  5706 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-30 16:37:57.225  5706  5706 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-30 16:37:57.245  5706  5706 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
,11-30 16:37:57.245  5706  5706 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-30 16:37:57.245  5706  5706 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-30 16:37:57.245  5706  5706 I Adreno  : Build Date                       : 12/06/15
11-30 16:37:57.245  5706  5706 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-30 16:37:57.245  5706  5706 I Adreno  : Local Branch                     : mybranch17112971
11-30 16:37:57.245  5706  5706 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-30 16:37:57.245  5706  5706 I Adreno  : Remote Branch                    : NONE
11-30 16:37:57.245  5706  5706 I Adreno  : Reconstruct Branch               : NOTHING
,11-30 16:37:57.300   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5922f1e:true
,11-30 16:37:57.339  2986  2986 W Binder_4: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[22331]" dev="sockfs" ino=22331 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-30 16:37:57.339  2986  2986 W Binder_4: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[22331]" dev="sockfs" ino=22331 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-30 16:37:57.351  5706  5706 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-30 16:37:57.360  5706  5706 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-30 16:37:57.365  5706  5706 D PluginManager: init()
,11-30 16:37:57.368  5706  5706 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-30 16:37:57.395  5706  5706 D CordovaActivity: Started the activity.
,11-30 16:37:57.395  5706  5706 D CordovaActivity: Resumed the activity.
,11-30 16:37:57.399   400   400 W Binder_1: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32349]" dev="sockfs" ino=32349 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-30 16:37:57.399   400   400 W Binder_1: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32349]" dev="sockfs" ino=32349 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-30 16:37:57.400  5706  5743 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-30 16:37:57.402  3204  3204 W Binder_3: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[14217]" dev="sockfs" ino=14217 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-30 16:37:57.402  3204  3204 W Binder_3: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[14217]" dev="sockfs" ino=14217 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
11-30 16:37:57.405  5706  5706 D CordovaActivity: Paused the activity.
,11-30 16:37:57.407  5706  5730 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup,
,11-30 16:37:57.441  5706  5743 I OpenGLRenderer: Initialized EGL, version 1.4
,11-30 16:37:57.458  5706  5706 D CordovaActivity: Stopped the activity.
,11-30 16:37:57.527   926   944 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +587ms (total +932ms)
,11-30 16:37:57.540  5706  5706 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-30 16:37:57.560  5706  5706 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5706
,11-30 16:37:57.664  5706  5706 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-30 16:37:57.825  5706  5746 D jxcore_app_log: JniHelper::setJavaVM(0xf53fc000), pthread_self() = -579598032
,11-30 16:37:57.830  5706  5746 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-30 16:37:57.830  5706  5746 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-30 16:37:57.830  5706  5746 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-30 16:37:57.830  5706  5746 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-30 16:37:57.830  5706  5746 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-30 16:37:57.830  5706  5746 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@fa81bf8 added. We now have 1 listener(s)
,11-30 16:37:57.832  5706  5746 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,11-30 16:37:57.833  5706  5746 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-30 16:37:57.833  5706  5746 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-30 16:37:57.833  5706  5746 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-30 16:37:57.836  5706  5746 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-30 16:37:57.836  5706  5746 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-30 16:37:57.836  5706  5746 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-30 16:37:57.836  5706  5746 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
11-30 16:37:57.836  5706  5746 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-30 16:37:57.836  5706  5746 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-30 16:37:57.836  5706  5746 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-30 16:37:57.836  5706  5746 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-30 16:37:57.836  5706  5746 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-30 16:37:57.836  5706  5746 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-30 16:37:57.836  5706  5746 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-30 16:37:57.836  5706  5746 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-30 16:37:57.836  5706  5746 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-30 16:37:57.836  5706  5746 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
11-30 16:37:57.836  5706  5746 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5820e37 added. We now have 1 listener(s)
11-30 16:37:57.836  5706  5746 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-30 16:37:57.840  5706  5746 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-30 16:37:57.841  5706  5746 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-30 16:37:57.841  5706  5746 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-30 16:37:57.841  5706  5746 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-30 16:37:57.841  5706  5746 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-30 16:37:57.841  5706  5746 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-30 16:37:57.841  5706  5746 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
,11-30 16:37:57.843   926  3023 D WifiService: New client listening to asynchronous messages
,11-30 16:37:57.844  5706  5746 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-30 16:37:57.858  5706  5706 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-30 16:37:57.863  5706  5706 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,11-30 16:37:57.863  5706  5706 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-30 16:37:58.316  5706  5752 W jxcore-log: Initializing JXcore engine
,11-30 16:37:58.316  5706  5752 W jxcore-log: JXcore engine is ready
,11-30 16:37:58.349  5752  5752 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=11639 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-30 16:37:58.349  5752  5752 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[16395]" dev="sockfs" ino=16395 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-30 16:37:58.349  5752  5752 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=5886 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-30 16:37:58.349  5752  5752 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[29680]" dev="sockfs" ino=29680 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-30 16:37:58.357  5706  5752 W jxcore-log: Starting JXcore engine
,11-30 16:37:58.416  5706  5752 W jxcore-log: Platform android
11-30 16:37:58.416  5706  5752 W jxcore-log: 
11-30 16:37:58.416  5706  5752 W jxcore-log: Process ARCH arm
11-30 16:37:58.416  5706  5752 W jxcore-log: 
,11-30 16:37:58.563  5706  5752 I jxcore-log: JXcore Cordova bridge is ready!
11-30 16:37:58.563  5706  5752 I jxcore-log: 
11-30 16:37:58.563  5706  5752 W jxcore-log: JXcore engine is started
,11-30 16:37:58.575  5706  5746 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-30 16:37:58.582  5706  5706 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,11-30 16:37:58.582  5706  5706 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-30 16:38:01.470  3619  3619 I ConfigService: onDestroy
,11-30 16:38:03.002   926  3022 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-30 16:38:04.362   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 16:38:05.363   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 16:38:06.365   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 16:38:07.366   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 16:38:08.312  5706  5752 I jxcore-log: 2016-11-30 21:38:08 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-30 16:38:08.312  5706  5752 I jxcore-log: 
,11-30 16:38:08.313  5706  5752 I jxcore-log: 2016-11-30 21:38:08 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-30 16:38:08.313  5706  5752 I jxcore-log: 
,11-30 16:38:08.318  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-30 16:38:08.319  5706  5752 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-30 16:38:08.319  5706  5752 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-30 16:38:08.319  5706  5752 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-30 16:38:08.319  5706  5752 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-30 16:38:08.319  5706  5752 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-30 16:38:08.319  5706  5752 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-30 16:38:08.319  5706  5752 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-30 16:38:08.319  5706  5752 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-30 16:38:08.319  5706  5752 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-30 16:38:08.320  5706  5752 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-30 16:38:08.323  5706  5752 I jxcore-log: 2016-11-30 21:38:08 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-30 16:38:08.323  5706  5752 I jxcore-log: 
11-30 16:38:08.324  5706  5752 I jxcore-log: 2016-11-30 21:38:08 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-30 16:38:08.324  5706  5752 I jxcore-log: 
,11-30 16:38:08.367   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 16:38:08.575  5706  5752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-30 16:38:08.576  5706  5752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9022709 added. We now have 2 listener(s)
11-30 16:38:08.576  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-30 16:38:08.576  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-30 16:38:08.576  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-30 16:38:08.577  5706  5752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-30 16:38:08.577  5706  5752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@7c58d0e added. We now have 2 listener(s)
11-30 16:38:08.577  5706  5752 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-30 16:38:08.577  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-30 16:38:08.578  5706  5752 D ExecuteNativeTests: Running unit tests
,11-30 16:38:08.579  5706  5752 D BluetoothAdapter: enable(): BT is already enabled..!
11-30 16:38:08.579   926  3244 D WifiService: setWifiEnabled: true pid=5706, uid=10077
11-30 16:38:08.580   926  3244 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-30 16:38:09.367   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-30 16:38:09.944  4886  4916 D Finsky  : [180] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-30 16:38:09.946  4886  4886 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-30 16:38:09.950   926  3917 I ActivityManager: Killing 5482:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,11-30 16:38:18.585  5706  5752 I com.test.thalitest.ThaliTestRunner: Running UT
,11-30 16:38:18.655  5706  5752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-30 16:38:18.655  5706  5752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49c1670 added. We now have 3 listener(s)
11-30 16:38:18.656  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-30 16:38:18.656  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-30 16:38:18.656  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-30 16:38:18.656  5706  5752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-30 16:38:18.656  5706  5752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@febdde9 added. We now have 3 listener(s)
,11-30 16:38:18.656  5706  5752 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-30 16:38:18.657  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-30 16:38:18.662  5706  5752 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionTimeout
,11-30 16:38:18.663  5706  5752 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-30 16:38:18.663  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 16:38:18.663  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-30 16:38:18.663  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-30 16:38:18.664  5706  5752 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,11-30 16:38:18.665  5706  5752 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-30 16:38:18.665  5706  5752 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-30 16:38:18.665  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-30 16:38:18.665  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-30 16:38:18.665  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-30 16:38:18.666  5706  5752 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnBluetoothMacAddressResolved
11-30 16:38:18.667  5706  5752 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-30 16:38:18.669  5706  5752 I io.jxcore.node.ConnectionHelperTest: Starting test: testHasMaximumNumberOfConnections
,11-30 16:38:18.671  5706  5752 I io.jxcore.node.ConnectionHelperTest: Starting test: testStart
11-30 16:38:18.671  5706  5752 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-30 16:38:18.672  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 16:38:18.672  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-30 16:38:18.681  5706  5752 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-30 16:38:18.681  5706  5752 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-30 16:38:18.681  5706  5752 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-30 16:38:18.681  5706  5752 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-30 16:38:18.681  5706  5752 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-30 16:38:18.681  5706  5752 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-30 16:38:18.681  5706  5752 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-30 16:38:18.681  5706  5752 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-30 16:38:18.681  5706  5752 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-30 16:38:18.682  5706  5752 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-30 16:38:18.682  5706  5752 D io.jxcore.node.ConnectivityMonitor: start: OK
11-30 16:38:18.682  5706  5752 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
11-30 16:38:18.682  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
11-30 16:38:18.682  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:18.682  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:18.682  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:18.682  5706  5752 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-30 16:38:18.682  5706  5752 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-30 16:38:18.682  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-30 16:38:18.683  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 16:38:18.683  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-30 16:38:18.684  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-30 16:38:18.684  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-30 16:38:18.684  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-30 16:38:18.684  5706  5752 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-30 16:38:18.684  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-30 16:38:18.684  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 16:38:18.684  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-30 16:38:18.684  5706  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-30 16:38:18.686  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-30 16:38:18.686  5706  5752 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-30 16:38:18.686  5706  5752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-30 16:38:18.687  5706  5706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-30 16:38:18.687  5706  5754 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-30 16:38:18.689  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:18.689  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-30 16:38:18.690  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-30 16:38:18.690  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-30 16:38:18.690  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 1
11-30 16:38:18.691  5706  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-30 16:38:18.691  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:18.691  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:18.688  4672  4672 W Binder_1: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[33804]" dev="sockfs" ino=33804 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-30 16:38:18.691  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-30 16:38:18.691  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-30 16:38:18.691  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-30 16:38:18.692  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 01 60 83 34 25 D7 C6
11-30 16:38:18.693  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 16:38:18.693  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
,11-30 16:38:18.693  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:18.693  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-30 16:38:18.693  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 16:38:18.693  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:18.693  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:18.693  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[1, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:18.694  5706  5706 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-30 16:38:18.694  5706  5706 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
,11-30 16:38:18.694  5706  5752 D BluetoothAdapter: STATE_ON
11-30 16:38:18.688  4672  4672 W Binder_1: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[33804]" dev="sockfs" ino=33804 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 16:38:18.697  4654  4873 D BtGatt.GattService: registerClient() - UUID=c75930b4-7522-4828-97b6-3e57e1ae7619
11-30 16:38:18.697  4654  4725 D BtGatt.GattService: onClientRegistered() - UUID=c75930b4-7522-4828-97b6-3e57e1ae7619, clientIf=5
11-30 16:38:18.699  5706  5717 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-30 16:38:18.702  4654  4727 D BtGatt.AdvertiseManager: message : 0
,11-30 16:38:18.705  4654  4727 D BtGatt.AdvertiseManager: starting multi advertising
,11-30 16:38:18.718  4654  4725 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-30 16:38:18.726  4654  4725 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-30 16:38:18.727  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:18.727  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:18.727  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-30 16:38:18.728  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:18.728  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:18.728  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:18.728  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:18.728  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:18.728  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-30 16:38:18.728  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-30 16:38:18.728  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:18.729  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:18.729  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:18.729  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:18.729  5706  5752 I io.jxcore.node.ConnectionHelper: start: OK
11-30 16:38:18.730  5706  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
,11-30 16:38:18.730  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-30 16:38:18.731  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-30 16:38:18.731  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-30 16:38:18.731  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-30 16:38:18.731  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-30 16:38:18.731  5706  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-30 16:38:18.732  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-30 16:38:18.732  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-30 16:38:18.732  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-30 16:38:18.732  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 16:38:18.732  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
,11-30 16:38:18.732  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 16:38:18.733  5706  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-30 16:38:18.733  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 16:38:18.736  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-30 16:38:18.736  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-30 16:38:18.736  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 16:38:18.736  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 16:38:18.736  5706  5706 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-30 16:38:19.232  5706  5755 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,11-30 16:38:19.234  5706  5752 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-30 16:38:19.234  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-30 16:38:19.235  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-30 16:38:19.235  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-30 16:38:19.235  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
,11-30 16:38:19.235  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-30 16:38:19.235  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-30 16:38:19.235  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-30 16:38:19.235  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-30 16:38:19.235  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-30 16:38:19.235  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
,11-30 16:38:19.235  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-30 16:38:19.235  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-30 16:38:19.236  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-30 16:38:19.236  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
,11-30 16:38:19.236  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-30 16:38:19.236  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-30 16:38:19.236  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-30 16:38:19.236  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-30 16:38:19.236  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-30 16:38:19.236  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-30 16:38:19.237  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,11-30 16:38:19.237  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-30 16:38:19.237  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-30 16:38:19.237  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-30 16:38:19.237  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-30 16:38:19.237  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-30 16:38:19.237  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-30 16:38:19.237  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-30 16:38:19.237  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-30 16:38:19.237  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-30 16:38:19.238  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-30 16:38:19.238  5706  5752 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-30 16:38:19.238  5706  5752 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-30 16:38:19.238  5706  5752 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-30 16:38:19.238  5706  5706 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-30 16:38:19.238  5706  5752 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-30 16:38:19.238  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-30 16:38:19.238  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-30 16:38:19.239  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-30 16:38:19.239  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-30 16:38:19.239  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-30 16:38:19.239  5706  5752 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-30 16:38:19.239  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-30 16:38:19.239  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.239  5706  5754 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-30 16:38:19.239  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-30 16:38:19.240  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-30 16:38:19.239  5706  5754 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-30 16:38:19.240  5706  5754 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-30 16:38:19.241  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.241  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.241  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.242  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.243  5706  5752 D BluetoothAdapter: STATE_ON
11-30 16:38:19.243  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-30 16:38:19.244  5706  5752 D BluetoothAdapter: STATE_ON
11-30 16:38:19.244  5706  5752 D BluetoothLeScanner: could not find callback wrapper
11-30 16:38:19.244  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-30 16:38:19.244  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.244  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.245  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.245  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-30 16:38:19.245  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.246  4654  4727 D BtGatt.AdvertiseManager: message : 1
11-30 16:38:19.247  4654  4727 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-30 16:38:19.260  4654  4725 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-30 16:38:19.260  4654  4725 D BtGatt.GattService: Client app is not null!
11-30 16:38:19.261  4654  4674 D BtGatt.GattService: unregisterClient() - clientIf=5
11-30 16:38:19.262  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-30 16:38:19.262  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.262  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-30 16:38:19.262  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.262  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.263  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.263  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
,11-30 16:38:19.263  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-30 16:38:19.264  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-30 16:38:19.264  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.266  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.266  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 16:38:19.266  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:19.267  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:19.267  5706  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-30 16:38:19.267  5706  5706 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-30 16:38:19.268  5706  5706 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-30 16:38:19.269  5706  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-30 16:38:19.269  5706  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-30 16:38:19.269  5706  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-30 16:38:19.269  5706  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-30 16:38:19.269  5706  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-30 16:38:19.269  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.269  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-30 16:38:19.270  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-30 16:38:19.270  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.270  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.270  5706  5756 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
11-30 16:38:19.270  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.270  5706  5706 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 16:38:19.270  5706  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.270  5706  5752 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-30 16:38:19.270  5706  5752 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-30 16:38:19.270  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.270  5706  5752 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 2
11-30 16:38:19.271  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 1 -> 2
11-30 16:38:19.271  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.271  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.271  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.271  5706  5752 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-30 16:38:19.271  5706  5752 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-30 16:38:19.271  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-30 16:38:19.271  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 16:38:19.273  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.273  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.273  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.274  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-30 16:38:19.274  5706  5752 D org.th,aliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-30 16:38:19.274  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-30 16:38:19.274  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-30 16:38:19.274  5706  5752 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-30 16:38:19.275  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-30 16:38:19.275  5706  5706 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-30 16:38:19.275  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 16:38:19.275  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-30 16:38:19.275  5706  5757 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-30 16:38:19.279  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-30 16:38:19.279  5706  5752 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-30 16:38:19.279  5706  5752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-30 16:38:19.281  5706  5757 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-30 16:38:19.285  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.285  4674  4674 W Binder_2: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[32792]" dev="sockfs" ino=32792 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 16:38:19.285  4674  4674 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[32792]" dev="sockfs" ino=32792 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 16:38:19.285  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-30 16:38:19.286  5706  5757 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-30 16:38:19.287  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-30 16:38:19.288  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-30 16:38:19.288  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 2
11-30 16:38:19.290  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.291  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.291  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-30 16:38:19.291  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-30 16:38:19.291  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-30 16:38:19.291  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 02 60 83 34 25 D7 C6
11-30 16:38:19.291  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 16:38:19.291  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 16:38:19.291  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.291  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-30 16:38:19.292  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 16:38:19.292  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.292  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.292  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[2, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.293  5706  5752 D BluetoothAdapter: STATE_ON
11-30 16:38:19.296  4654  4674 D BtGatt.GattService: registerClient() - UUID=f237e7e5-f77a-46f2-9463-fa397d97914a
11-30 16:38:19.296  4654  4725 D BtGatt.GattService: onClientRegistered() - UUID=f237e7e5-f77a-46f2-9463-fa397d97914a, clientIf=5
11-30 16:38:19.297  5706  5716 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
11-30 16:38:19.298  4654  4727 D BtGatt.AdvertiseManager: message : 0
11-30 16:38:19.301  4654  4727 D BtGatt.AdvertiseManager: starting multi advertising
11-30 16:38:19.314  4654  4725 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-30 16:38:19.320  4654  4725 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
11-30 16:38:19.321  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.321  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.321  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-30 16:38:19.321  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.321  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.321  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.321  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.321  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.321  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-30 16:38:19.323  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-30 16:38:19.323  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.324  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.324  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.324  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.324  5706  5752 I io.jxcore.node.ConnectionHelper: start: OK
11-30 16:38:19.325  5706  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-30 16:38:19.325  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.325  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-30 16:38:19.325  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-30 16:38:19.325  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.325  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.325  5706  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 16:38:19.325  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.325  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-30 16:38:19.325  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-30 16:38:19.325  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.326  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.326  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.326  5706  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.326  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.329  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.329  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-30 16:38:19.329  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.329  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.329  5706  5706 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-30 16:38:19.826  5706  5758 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,11-30 16:38:19.829  5706  5752 I io.jxcore.node.ConnectionHelperTest: Starting test: testStop
11-30 16:38:19.829  5706  5752 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-30 16:38:19.829  5706  5752 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-30 16:38:19.830  5706  5752 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-30 16:38:19.830  5706  5752 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 3
11-30 16:38:19.830  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 2 -> 3
11-30 16:38:19.830  5706  5706 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-30 16:38:19.831  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.831  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.831  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:19.833  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-30 16:38:19.833  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-30 16:38:19.833  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-30 16:38:19.833  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 3
11-30 16:38:19.833  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-30 16:38:19.833  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-30 16:38:19.833  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-30 16:38:19.833  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-30 16:38:19.833  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-30 16:38:19.833  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:19.833  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 3
11-30 16:38:19.834  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.835  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop advertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.835  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.837  4654  4727 D BtGatt.AdvertiseManager: message : 1
11-30 16:38:19.838  4654  4727 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-30 16:38:19.851  4654  4725 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-30 16:38:19.851  4654  4725 D BtGatt.GattService: Client app is not null!
,11-30 16:38:19.852  4654  4672 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-30 16:38:19.852  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-30 16:38:19.852  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:19.852  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
,11-30 16:38:19.853  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:19.853  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.853  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.853  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-30 16:38:19.853  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.853  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.853  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.853  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-30 16:38:19.853  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-30 16:38:19.853  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-30 16:38:19.854  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 03 60 83 34 25 D7 C6
,11-30 16:38:19.854  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 16:38:19.854  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 16:38:19.854  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.854  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-30 16:38:19.854  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 16:38:19.854  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.854  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.855  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[3, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.855  5706  5752 D BluetoothAdapter: STATE_ON
11-30 16:38:19.860  4654  4672 D BtGatt.GattService: registerClient() - UUID=42d1dea0-61a4-4cc6-b9eb-f755ec1c0a6e
11-30 16:38:19.861  4654  4725 D BtGatt.GattService: onClientRegistered() - UUID=42d1dea0-61a4-4cc6-b9eb-f755ec1c0a6e, clientIf=5
11-30 16:38:19.861  5706  5717 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-30 16:38:19.862  4654  4727 D BtGatt.AdvertiseManager: message : 0
,11-30 16:38:19.866  4654  4727 D BtGatt.AdvertiseManager: starting multi advertising
,11-30 16:38:19.877  4654  4725 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-30 16:38:19.883  4654  4725 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-30 16:38:19.884  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.884  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.884  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-30 16:38:19.884  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.884  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:19.884  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.884  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.884  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.884  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start advertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.884  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-30 16:38:19.884  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.885  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-30 16:38:19.885  5706  5752 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-30 16:38:19.885  5706  5752 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-30 16:38:19.885  5706  5752 I io.jxcore.node.ConnectionHelper: start: OK
11-30 16:38:19.885  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.885  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-30 16:38:19.885  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-30 16:38:19.885  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.885  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,11-30 16:38:19.886  5706  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 16:38:19.886  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.886  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-30 16:38:19.886  5706  5759 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
11-30 16:38:19.886  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,11-30 16:38:19.886  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.886  5706  5752 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-30 16:38:19.886  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.886  5706  5752 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-30 16:38:19.886  5706  5752 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-30 16:38:19.886  5706  5752 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-30 16:38:19.886  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-30 16:38:19.886  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-30 16:38:19.886  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-30 16:38:19.886  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-30 16:38:19.886  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-30 16:38:19.887  5706  5752 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-30 16:38:19.887  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-30 16:38:19.887  5706  5757 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-30 16:38:19.887  5706  5757 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-30 16:38:19.887  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.887  5706  5757 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-30 16:38:19.887  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-30 16:38:19.887  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-30 16:38:19.887  5706  5706 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-30 16:38:19.887  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.887  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.887  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.887  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:19.888  5706  5752 D BluetoothAdapter: STATE_ON
11-30 16:38:19.888  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-30 16:38:19.888  5706  5752 D BluetoothAdapter: STATE_ON
11-30 16:38:19.888  5706  5752 D BluetoothLeScanner: could not find callback wrapper
11-30 16:38:19.889  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-30 16:38:19.889  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.889  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:19.889  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.889  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-30 16:38:19.889  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.890  4654  4727 D BtGatt.AdvertiseManager: message : 1
11-30 16:38:19.890  4654  4727 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-30 16:38:19.897  4654  4725 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
11-30 16:38:19.897  4654  4725 D BtGatt.GattService: Client app is not null!
,11-30 16:38:19.897  4654  4882 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-30 16:38:19.898  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-30 16:38:19.898  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:19.898  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-30 16:38:19.899  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.899  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.899  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.899  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-30 16:38:19.899  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-30 16:38:19.902  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-30 16:38:19.902  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.903  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.903  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 16:38:19.903  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.903  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.903  5706  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-30 16:38:19.903  5706  5706 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-30 16:38:19.903  5706  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-30 16:38:19.903  5706  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-30 16:38:19.903  5706  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 16:38:19.903  5706  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 16:38:19.904  5706  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-30 16:38:19.904  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-30 16:38:19.904  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-30 16:38:19.904  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-30 16:38:19.904  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.904  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.904  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.904  5706  5706 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,11-30 16:38:19.904  5706  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.904  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.905  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.906  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.906  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.907  5706  5760 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,11-30 16:38:19.908  5706  5752 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPeerReadyToProvideBluetoothMacAddress
11-30 16:38:19.908  5706  5752 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
,11-30 16:38:19.909  5706  5752 I io.jxcore.node.ConnectionHelperTest: Starting test: testKillAllConnections
,11-30 16:38:19.910  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-30 16:38:19.911  5706  5752 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionManagerStateChanged
11-30 16:38:19.911  5706  5752 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,11-30 16:38:19.912  5706  5752 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnPermissionCheckRequired
11-30 16:38:19.912  5706  5752 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-30 16:38:19.912  5706  5752 I io.jxcore.node.ConnectionHelperTest: Starting test: testToggleBetweenSystemDecidedAndAlternativeInsecureRfcommPortNumber
11-30 16:38:19.913  5706  5752 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-30 16:38:19.913  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 16:38:19.913  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 16:38:19.913  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 16:38:19.913  5706  5752 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-30 16:38:19.913  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-30 16:38:19.913  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-30 16:38:19.913  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,11-30 16:38:19.913  5706  5752 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-30 16:38:19.913  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 16:38:19.913  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-30 16:38:19.914  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-30 16:38:19.914  5706  5752 I io.jxcore.node.ConnectionHelperTest: Starting test: testConnect
11-30 16:38:19.915  5706  5752 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-30 16:38:19.915  5706  5752 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-30 16:38:19.915  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
,11-30 16:38:19.918  5706  5752 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-30 16:38:19.918  5706  5752 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-30 16:38:19.918  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-30 16:38:19.918  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
,11-30 16:38:19.918  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-30 16:38:19.919  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-30 16:38:19.919  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-30 16:38:19.919  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-30 16:38:19.919  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-30 16:38:19.919  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-30 16:38:19.919  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-30 16:38:19.919  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-30 16:38:19.919  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-30 16:38:19.919  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-30 16:38:19.919  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-30 16:38:19.919  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-30 16:38:19.919  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-30 16:38:19.919  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-30 16:38:19.919  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
,11-30 16:38:19.919  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-30 16:38:19.919  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
,11-30 16:38:19.919  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-30 16:38:19.919  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-30 16:38:19.919  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
,11-30 16:38:19.920  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-30 16:38:19.920  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-30 16:38:19.920  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-30 16:38:19.920  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-30 16:38:19.920  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
,11-30 16:38:19.920  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-30 16:38:19.920  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-30 16:38:19.920  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-30 16:38:19.920  5706  5752 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-30 16:38:19.920  5706  5752 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,11-30 16:38:19.921  5706  5752 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-30 16:38:19.921  5706  5752 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-30 16:38:19.921  5706  5752 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-30 16:38:19.921  5706  5752 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-30 16:38:19.921  5706  5752 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-30 16:38:19.921  5706  5752 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,11-30 16:38:19.921  5706  5752 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-30 16:38:19.928  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
,11-30 16:38:19.929  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port 1
11-30 16:38:19.929  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,11-30 16:38:19.930  5706  5752 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
,11-30 16:38:19.930  5706  5761 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 133)
11-30 16:38:19.930  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
11-30 16:38:19.930  5706  5752 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-30 16:38:19.930  5706  5761 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-30 16:38:19.931  5706  5761 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-30 16:38:19.931  5706  5752 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-30 16:38:19.931  5706  5761 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: given port
11-30 16:38:19.931  5706  5752 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-30 16:38:19.931  5706  5761 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothUtils: createBluetoothSocketToServiceRecord: Socket created with channel/port 1
11-30 16:38:19.931  5706  5761 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-30 16:38:19.931  5706  5761 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-30 16:38:19.932  4873  4873 W Binder_3: type=1400 audit(0.0:114): avc: denied { ioctl } for path="socket:[32801]" dev="sockfs" ino=32801 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 16:38:19.933  5706  5752 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnProvideBluetoothMacAddressRequest
11-30 16:38:19.933  5706  5752 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-30 16:38:19.934  5706  5752 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnDiscoveryManagerStateChanged
11-30 16:38:19.934  5706  5752 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-30 16:38:19.935  5706  5752 I io.jxcore.node.ConnectionHelperTest: Starting test: testDisconnectOutgoingConnection
11-30 16:38:19.935  5706  5752 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-30 16:38:19.935  5706  5752 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-30 16:38:19.936  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-30 16:38:19.936  5706  5752 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-30 16:38:19.936  5706  5752 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-30 16:38:19.936  5706  5752 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-30 16:38:19.936  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-30 16:38:19.936  5706  5752 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-30 16:38:19.936  5706  5752 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-30 16:38:19.936  5706  5752 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-30 16:38:19.936  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-30 16:38:19.936  5706  5752 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-30 16:38:19.937  5706  5752 I io.jxcore.node.ConnectionHelperTest: Starting test: testDispose
11-30 16:38:19.937  5706  5752 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: true
11-30 16:38:19.937  5706  5752 V io.jxcore.node.ConnectivityMonitor: start: Already started
11-30 16:38:19.937  5706  5752 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 4
11-30 16:38:19.937  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 3 -> 4
11-30 16:38:19.937  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.937  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.937  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.937  5706  5752 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-30 16:38:19.937  5706  5752 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-30 16:38:19.937  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-30 16:38:19.937  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 16:38:19.932  4873  4873 W Binder_3: type=1400 audit(0.0:115): avc: denied { ioctl } for path="socket:[32801]" dev="sockfs" ino=32801 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 16:38:19.939  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-30 16:38:19.939  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-30 16:38:19.939  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-30 16:38:19.939  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-30 16:38:19.939  5706  5752 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-30 16:38:19.939  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-30 16:38:19.939  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 16:38:19.939  5706  5706 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-30 16:38:19.939  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-30 16:38:19.940  5706  5762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-30 16:38:19.941  5706  5762 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-30 16:38:19.943  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-30 16:38:19.943  5706  5752 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-30 16:38:19.943  5706  5752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-30 16:38:19.942  4672  4672 W Binder_1: type=1400 audit(0.0:116): avc: denied { ioctl } for path="socket:[32438]" dev="sockfs" ino=32438 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 16:38:19.942  4672  4672 W Binder_1: type=1400 audit(0.0:117): avc: denied { ioctl } for path="socket:[32438]" dev="sockfs" ino=32438 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 16:38:19.944  5706  5762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-30 16:38:19.948  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.948  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-30 16:38:19.949  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-30 16:38:19.949  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-30 16:38:19.949  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 4
,11-30 16:38:19.951  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.951  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.951  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-30 16:38:19.951  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-30 16:38:19.952  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-30 16:38:19.952  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 04 60 83 34 25 D7 C6
11-30 16:38:19.952  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 16:38:19.952  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 16:38:19.952  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.952  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-30 16:38:19.953  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 16:38:19.953  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.953  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.953  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[4, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.954  5706  5752 D BluetoothAdapter: STATE_ON
,11-30 16:38:19.957  4654  4674 D BtGatt.GattService: registerClient() - UUID=bfa28949-854f-4dda-a7be-f2be8c251029
11-30 16:38:19.957  4654  4725 D BtGatt.GattService: onClientRegistered() - UUID=bfa28949-854f-4dda-a7be-f2be8c251029, clientIf=5
11-30 16:38:19.958  5706  5717 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-30 16:38:19.959  4654  4727 D BtGatt.AdvertiseManager: message : 0
,11-30 16:38:19.961  4654  4727 D BtGatt.AdvertiseManager: starting multi advertising
,11-30 16:38:19.970  4654  4725 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-30 16:38:19.975  4654  4725 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-30 16:38:19.976  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.976  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.976  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-30 16:38:19.976  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.976  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.976  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.976  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.976  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.976  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-30 16:38:19.977  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-30 16:38:19.977  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.978  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.978  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.979  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:19.979  5706  5752 I io.jxcore.node.ConnectionHelper: start: OK
11-30 16:38:19.979  5706  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-30 16:38:19.979  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.979  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-30 16:38:19.979  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-30 16:38:19.979  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
,11-30 16:38:19.979  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.979  5706  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 16:38:19.979  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.979  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-30 16:38:19.980  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-30 16:38:19.980  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.980  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.980  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.980  5706  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.980  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-30 16:38:19.982  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-30 16:38:19.982  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-30 16:38:19.982  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.982  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 16:38:19.982  5706  5706 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-30 16:38:20.479  5706  5755 D io.jxcore.node.ConnectionHelperTest: Discovery manager is running
,11-30 16:38:20.480  5706  5752 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-30 16:38:20.480  5706  5752 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-30 16:38:20.480  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-30 16:38:20.480  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-30 16:38:20.481  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-30 16:38:20.481  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-30 16:38:20.481  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-30 16:38:20.481  5706  5762 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-30 16:38:20.481  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-30 16:38:20.481  5706  5762 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-30 16:38:20.481  5706  5706 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-30 16:38:20.481  5706  5762 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,11-30 16:38:20.481  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-30 16:38:20.481  5706  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
11-30 16:38:20.481  5706  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-30 16:38:20.483  5706  5706 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
11-30 16:38:20.484  5706  5752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49c1670 removed from the list
11-30 16:38:20.484  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-30 16:38:20.484  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-30 16:38:20.484  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:20.484  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-30 16:38:20.484  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-30 16:38:20.484  5706  5763 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 133
11-30 16:38:20.485  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:20.485  5706  5763 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
11-30 16:38:20.485  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:20.485  5706  5763 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 133)
11-30 16:38:20.485  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:20.485  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:20.485  4654  4863 E bt_btif_sock_rfcomm: btsock_rfc_signaled socket signaled for read while disconnected, slot: 7, channel: 1
11-30 16:38:20.485  5706  5763 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 133)
11-30 16:38:20.486  5706  5761 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, read failed, socket might closed or timeout, read ret: -1
11-30 16:38:20.486  5706  5761 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-30 16:38:20.486  5706  5761 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 133)
11-30 16:38:20.486  5706  5752 D BluetoothAdapter: STATE_ON
11-30 16:38:20.487  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-30 16:38:20.488  5706  5752 D BluetoothAdapter: STATE_ON
11-30 16:38:20.488  5706  5752 D BluetoothLeScanner: could not find callback wrapper
11-30 16:38:20.488  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-30 16:38:20.488  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:20.488  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:20.489  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:20.489  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-30 16:38:20.489  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:20.490  4654  4727 D BtGatt.AdvertiseManager: message : 1
11-30 16:38:20.491  4654  4727 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-30 16:38:20.499  4654  4725 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-30 16:38:20.500  4654  4725 D BtGatt.GattService: Client app is not null!
11-30 16:38:20.501  4654  4672 D BtGatt.GattService: unregisterClient() - clientIf=5
11-30 16:38:20.502  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-30 16:38:20.502  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:20.502  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-30 16:38:20.502  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:20.503  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:20.503  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:20.503  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-30 16:38:20.503  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-30 16:38:20.506  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-30 16:38:20.506  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:20.508  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:20.508  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 16:38:20.508  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:20.509  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:20.509  5706  5752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@febdde9 removed from the list
11-30 16:38:20.509  5706  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 16:38:20.509  5706  5752 D io.jxcore.node.ConnectivityMonitor: stop
11-30 16:38:20.509  5706  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 16:38:20.509  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-30 16:38:20.509  5706  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-30 16:38:20.509  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-30 16:38:20.509  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-30 16:38:20.510  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
11-30 16:38:20.510  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 16:38:20.510  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-30 16:38:20.510  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 16:38:20.511  5706  5706 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 16:38:20.511  5706  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-30 16:38:20.511  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 16:38:20.513  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 16:38:20.514  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 16:38:20.514  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-30 16:38:21.012  5706  5706 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-30 16:38:25.060  4654  4827 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-30 16:38:25.061  4654  4827 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 7
,11-30 16:38:25.513  5706  5756 D io.jxcore.node.ConnectionHelperTest: Discovery manager is NOT running
,11-30 16:38:25.516  5706  5752 I io.jxcore.node.ConnectionHelperTest: Starting test: testIsRunning
,11-30 16:38:25.519  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-30 16:38:25.519  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 16:38:25.520  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-30 16:38:25.525  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-30 16:38:25.527  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
,11-30 16:38:25.527  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-30 16:38:25.527  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-30 16:38:25.527  5706  5752 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-30 16:38:25.527  5706  5752 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-30 16:38:25.528  5706  5764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-30 16:38:25.528  5706  5706 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-30 16:38:25.530  5706  5764 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-30 16:38:25.532  4873  4873 W Binder_3: type=1400 audit(0.0:118): avc: denied { ioctl } for path="socket:[32446]" dev="sockfs" ino=32446 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-30 16:38:25.532  4873  4873 W Binder_3: type=1400 audit(0.0:119): avc: denied { ioctl } for path="socket:[32446]" dev="sockfs" ino=32446 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-30 16:38:25.532  5706  5752 I io.jxcore.node.ConnectionHelperTest: Starting test: testOnConnectionFailed
11-30 16:38:25.534  5706  5752 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
,11-30 16:38:25.534  5706  5752 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-30 16:38:25.534  5706  5752 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-30 16:38:25.535  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-30 16:38:25.535  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-30 16:38:25.536  5706  5764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-30 16:38:25.537  5706  5752 I io.jxcore.node.ConnectionHelperTest: Starting test: testGetConnectivityMonitorGetDiscoveryManagerGetConnectionModelGetBluetoothName
,11-30 16:38:25.545  5706  5752 I io.jxcore.node.ConnectionHelperTest: Starting test: testConstructor
,11-30 16:38:25.546  5706  5752 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-30 16:38:25.546  5706  5752 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-30 16:38:25.546  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-30 16:38:25.546  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-30 16:38:25.546  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-30 16:38:25.547  5706  5764 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-30 16:38:25.547  5706  5764 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-30 16:38:25.547  5706  5764 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-30 16:38:25.547  5706  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-30 16:38:25.548  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-30 16:38:25.548  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-30 16:38:25.548  5706  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-30 16:38:25.548  5706  5752 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@49c1670 not in the list
11-30 16:38:25.548  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-30 16:38:25.548  5706  5706 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-30 16:38:25.548  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-30 16:38:25.548  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:25.549  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-30 16:38:25.549  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-30 16:38:25.549  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:25.551  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:25.551  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 16:38:25.551  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:25.551  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:25.551  5706  5752 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@febdde9 not in the list
11-30 16:38:25.551  5706  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 16:38:25.551  5706  5752 D io.jxcore.node.ConnectivityMonitor: stop
,11-30 16:38:25.552  5706  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 16:38:25.552  5706  5706 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 16:38:25.553  5706  5752 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentOutgoingConnections
,11-30 16:38:25.554  5706  5752 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
,11-30 16:38:25.554  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-30 16:38:25.554  5706  5752 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
11-30 16:38:25.554  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-30 16:38:25.554  5706  5752 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
,11-30 16:38:25.554  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-30 16:38:25.556  5706  5752 I io.jxcore.node.ConnectionModelTest: Starting test: constructorTest
11-30 16:38:25.557  5706  5752 I io.jxcore.node.ConnectionModelTest: Starting test: testHasIncomingConnection
11-30 16:38:25.559  5706  5752 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentConnections
11-30 16:38:25.559  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,11-30 16:38:25.559  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-30 16:38:25.560  5706  5752 I io.jxcore.node.ConnectionModelTest: Starting test: testGetNumberOfCurrentIncomingConnections
11-30 16:38:25.561  5706  5752 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-30 16:38:25.561  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-30 16:38:25.561  5706  5752 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-30 16:38:25.561  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
,11-30 16:38:25.561  5706  5752 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-30 16:38:25.561  5706  5752 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
,11-30 16:38:25.563  5706  5752 I io.jxcore.node.ConnectionModelTest: Starting test: testGetOutgoingConnectionCallbackByBluetoothMacAddress
11-30 16:38:25.564  5706  5752 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,11-30 16:38:25.564  5706  5752 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-30 16:38:25.565  5706  5752 I io.jxcore.node.ConnectionModelTest: Starting test: testHasConnection
11-30 16:38:25.565  5706  5752 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-30 16:38:25.565  5706  5752 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-30 16:38:25.565  5706  5752 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
11-30 16:38:25.565  5706  5752 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
11-30 16:38:25.566  5706  5752 I io.jxcore.node.ConnectionModelTest: Starting test: testHasOutgoingConnection
11-30 16:38:25.567  5706  5752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-30 16:38:25.567  5706  5752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90c8fff added. We now have 3 listener(s)
11-30 16:38:25.569  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-30 16:38:25.569  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-30 16:38:25.569  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-30 16:38:25.569  5706  5752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-30 16:38:25.570  5706  5752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7331cc added. We now have 3 listener(s)
11-30 16:38:25.570  5706  5752 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-30 16:38:25.570  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-30 16:38:25.574  5706  5752 D BluetoothAdapter: enable(): BT is already enabled..!
,11-30 16:38:25.574   926   936 D WifiService: setWifiEnabled: true pid=5706, uid=10077
11-30 16:38:25.574   926   936 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-30 16:38:25.576  5706  5752 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBleMultipleAdvertisementSupported
,11-30 16:38:25.580  5706  5752 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothSupported
11-30 16:38:25.581  5706  5752 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiDirectSupported
,11-30 16:38:25.582  5706  5752 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsBluetoothEnabled
,11-30 16:38:25.588  4654  4721 D BluetoothAdapterState: Current state: ON, message: 23
,11-30 16:38:25.589  5706  5752 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-30 16:38:25.589  5706  5752 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-30 16:38:25.589  5706  5752 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-30 16:38:25.589  5706  5752 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-30 16:38:25.589  5706  5752 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-30 16:38:25.589  5706  5752 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-30 16:38:25.589  5706  5752 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-30 16:38:25.589  5706  5752 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-30 16:38:25.589  5706  5752 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-30 16:38:25.589  4654  4721 D BluetoothAdapterProperties: Setting state to 13
11-30 16:38:25.589  4654  4721 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-30 16:38:25.589  4654  4721 D BluetoothAdapterProperties: onBluetoothDisable()
11-30 16:38:25.589  5706  5752 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-30 16:38:25.590  5706  5752 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-30 16:38:25.592  4654  4721 I BluetoothAdapterState: Entering PendingCommandState
,11-30 16:38:25.594  4654  4654 D BluetoothMapService: onReceive
11-30 16:38:25.594  4654  4654 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-30 16:38:25.594  4654  4654 D BluetoothMapService: STATE_TURNING_OFF
11-30 16:38:25.595  4654  4654 D BluetoothMapService: MAP Service closeService in
,11-30 16:38:25.595  4654  4654 D BluetoothMapMasInstance0: MAP Service shutdown
11-30 16:38:25.595  4654  4654 D ObexServerSockets0: shutdown(block = true)
11-30 16:38:25.596  4654  4654 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-30 16:38:25.596  4654  4884 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-30 16:38:25.596  4654  4654 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-30 16:38:25.596  4654  4863 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-30 16:38:25.597  4654  4885 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-30 16:38:25.598  4654  4654 I BtOppRfcommListener: stopping Accept Thread
11-30 16:38:25.599  4654  5383 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-30 16:38:25.601  4654  5383 I BtOppRfcommListener: BluetoothSocket listen thread finished
,11-30 16:38:25.614   926   939 I ActivityManager: Start proc 5767:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
,11-30 16:38:25.615  4654  4725 D BluetoothAdapterProperties: Scan Mode:20
,11-30 16:38:25.615  4654  4721 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-30 16:38:25.619  4654  4654 D HeadsetService: Received stop request...Stopping profile...
11-30 16:38:25.621   926   926 D BluetoothHeadset: Proxy object disconnected
11-30 16:38:25.621  3835  4274 D BluetoothHeadset: Proxy object disconnected
11-30 16:38:25.622  4654  4654 D A2dpService: Received stop request...Stopping profile...
11-30 16:38:25.622  4654  4877 D A2dpStateMachine: Exit Disconnected: -1
11-30 16:38:25.623  3190  3202 D BluetoothHeadset: Proxy object disconnected
11-30 16:38:25.623   926   926 D BluetoothHeadset: Proxy object disconnected
11-30 16:38:25.623   926   926 D BluetoothHeadset: Proxy object disconnected
11-30 16:38:25.623  3190  3190 D HeadsetProfile: Bluetooth service disconnected
,11-30 16:38:25.625   926   926 D BluetoothA2dp: Proxy object disconnected
11-30 16:38:25.627  3190  3190 D BluetoothA2dp: Proxy object disconnected
11-30 16:38:25.627  4654  4654 D HidService: Received stop request...Stopping profile...
11-30 16:38:25.627  4654  4654 D HidService: Stopping Bluetooth HidService
,11-30 16:38:25.629  3190  3190 D BluetoothInputDevice: Proxy object disconnected
,11-30 16:38:25.629  3190  3190 D HidProfile: Bluetooth service disconnected
,11-30 16:38:25.630  4654  4654 D HealthService: Received stop request...Stopping profile...
11-30 16:38:25.631  4654  4654 V BluetoothAdapterState: isTurningOff()=true
11-30 16:38:25.632  4654  4654 V BluetoothAdapterState: isTurningOn()=false
11-30 16:38:25.632  4654  4654 V BluetoothAdapterState: isBleTurningOn()=false
11-30 16:38:25.632  4654  4654 V BluetoothAdapterState: isBleTurningOff()=false
,11-30 16:38:25.634  4654  4654 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-30 16:38:25.634  4654  4654 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,11-30 16:38:25.635  4654  4827 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-30 16:38:25.635  4654  4827 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-30 16:38:25.635  4654  4827 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-30 16:38:25.635  4654  4725 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-30 16:38:25.635  4654  4725 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-30 16:38:25.635  4654  4654 D PanService: Received stop request...Stopping profile...
11-30 16:38:25.636  3190  3190 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-30 16:38:25.637  3190  3190 D PanProfile: Bluetooth service disconnected
,11-30 16:38:25.637  4654  4654 V BluetoothAdapterState: isTurningOff()=true
11-30 16:38:25.637  4654  4654 V BluetoothAdapterState: isTurningOn()=false
11-30 16:38:25.637  4654  4654 V BluetoothAdapterState: isBleTurningOn()=false
,11-30 16:38:25.637  4654  4654 V BluetoothAdapterState: isBleTurningOff()=false
,11-30 16:38:25.639  4654  4725 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-30 16:38:25.639  4654  4654 V BluetoothAdapterState: isTurningOff()=true
11-30 16:38:25.639  4654  4654 V BluetoothAdapterState: isTurningOn()=false
11-30 16:38:25.639  4654  4654 V BluetoothAdapterState: isBleTurningOn()=false
,11-30 16:38:25.639  4654  4654 V BluetoothAdapterState: isBleTurningOff()=false
11-30 16:38:25.639  4654  4827 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-30 16:38:25.639  4654  4827 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-30 16:38:25.639  4654  4827 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-30 16:38:25.640  4654  4827 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-30 16:38:25.640  4654  4654 D BluetoothMapService: Received stop request...Stopping profile...
11-30 16:38:25.640  4654  4654 D BluetoothMapService: stop()
11-30 16:38:25.640  4654  4827 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-30 16:38:25.640  4654  4827 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-30 16:38:25.640  4654  4654 D BluetoothMapAppObserver: deinitObservers()
11-30 16:38:25.640  4654  4654 D BluetoothMapAppObserver: removeReceiver()
,11-30 16:38:25.641  3190  3190 D BluetoothMap: Proxy object disconnected
11-30 16:38:25.641  3190  3190 D MapProfile: Bluetooth service disconnected
11-30 16:38:25.642  4654  4654 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-30 16:38:25.642  4654  4654 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-30 16:38:25.642  4654  4725 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-30 16:38:25.642  4654  4654 D SapService: Received stop request...Stopping profile...
11-30 16:38:25.642  4654  4654 V SapService: stop()
11-30 16:38:25.643  4654  4654 V BluetoothAdapterState: isTurningOff()=true
11-30 16:38:25.643  4654  4654 V BluetoothAdapterState: isTurningOn()=false
11-30 16:38:25.643  4654  4654 V BluetoothAdapterState: isBleTurningOn()=false
11-30 16:38:25.643  4654  4654 V BluetoothAdapterState: isBleTurningOff()=false
,11-30 16:38:25.644  4654  4654 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-30 16:38:25.644  4654  4725 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-30 16:38:25.644  4654  4654 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-30 16:38:25.644  4654  4654 V BluetoothAdapterState: isTurningOff()=true
11-30 16:38:25.644  4654  4654 V BluetoothAdapterState: isTurningOn()=false
11-30 16:38:25.644  4654  4654 V BluetoothAdapterState: isBleTurningOn()=false
11-30 16:38:25.644  4654  4654 V BluetoothAdapterState: isBleTurningOff()=false
11-30 16:38:25.645  4654  4654 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-30 16:38:25.645  4654  4654 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-30 16:38:25.646  4654  4654 D BluetoothMapService: MAP Service closeService in
,11-30 16:38:25.646  4654  4654 V BluetoothAdapterState: isTurningOff()=true
11-30 16:38:25.646  4654  4654 V BluetoothAdapterState: isTurningOn()=false
11-30 16:38:25.646  4654  4654 V BluetoothAdapterState: isBleTurningOn()=false
11-30 16:38:25.647  4654  4654 V BluetoothAdapterState: isBleTurningOff()=false
11-30 16:38:25.647  4654  4654 D BluetoothMapService: cleanup()
11-30 16:38:25.647  4654  4654 D BluetoothMapService: MAP Service closeService in
11-30 16:38:25.647  4654  4654 V BluetoothAdapterState: isTurningOff()=true
11-30 16:38:25.648  4654  4654 V BluetoothAdapterState: isTurningOn()=false
11-30 16:38:25.648  4654  4654 V BluetoothAdapterState: isBleTurningOn()=false
11-30 16:38:25.648  4654  4654 V BluetoothAdapterState: isBleTurningOff()=false
11-30 16:38:25.648  4654  4721 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-30 16:38:25.648  4654  4721 D BluetoothAdapterProperties: Setting state to 15
11-30 16:38:25.648  4654  4721 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
,11-30 16:38:25.649  4654  4721 I BluetoothAdapterState: Entering BleOnState
11-30 16:38:25.650   926  3204 I ActivityManager: Killing 5495:com.android.chrome/u0a39 (adj 15): empty #17
,11-30 16:38:25.668  3190  3205 D BluetoothPan: onBluetoothStateChange on: false
,11-30 16:38:25.669   926   943 D BluetoothA2dp: onBluetoothStateChange: up=false
11-30 16:38:25.670  3190  3992 D BluetoothInputDevice: onBluetoothStateChange: up=false
,11-30 16:38:25.671   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-30 16:38:25.671  3190  3202 D BluetoothPbap: onBluetoothStateChange: up=false
,11-30 16:38:25.672  3190  3205 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-30 16:38:25.673  3190  3992 D BluetoothMap: onBluetoothStateChange: up=false
11-30 16:38:25.673   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-30 16:38:25.673   926   943 D BluetoothHeadset: onBluetoothStateChange: up=false
11-30 16:38:25.673  3835  4043 D BluetoothHeadset: onBluetoothStateChange: up=false
11-30 16:38:25.674  3190  3202 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-30 16:38:25.675  4654  4721 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-30 16:38:25.675  4654  4721 D BluetoothAdapterProperties: Setting state to 16
,11-30 16:38:25.675  4654  4721 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-30 16:38:25.676  4654  4721 D BluetoothAdapterProperties: onBleDisable
11-30 16:38:25.676  4654  4721 I BluetoothAdapterState: Entering PendingCommandState
11-30 16:38:25.676  4654  4722 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-30 16:38:25.677  4654  4827 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-30 16:38:25.677  4654  4827 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,11-30 16:38:25.680  4654  4725 D BluetoothAdapterProperties: Scan Mode:20
,11-30 16:38:25.682  5767  5767 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
,11-30 16:38:25.695  5767  5767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-30 16:38:25.700   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c1732c4:true
,11-30 16:38:25.701  3619  3619 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-30 16:38:25.718   926  3911 I ActivityManager: Start proc 5779:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,11-30 16:38:25.729  5767  5767 D LocalBluetoothProfileManager: Adding local MAP profile
,11-30 16:38:25.741  5767  5767 D BluetoothMap: Create BluetoothMap proxy object
,11-30 16:38:25.751  5779  5779 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-30 16:38:25.754  5767  5767 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-30 16:38:25.764  5767  5767 D DockEventReceiver: finishStartingService: stopping service
,11-30 16:38:25.774   926  3204 I ActivityManager: Killing 5036:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-30 16:38:25.892  4654  4725 I bt_hci  : shut_down
,11-30 16:38:25.896  4654  4729 D bt_hwcfg: hw_epilog_process
,11-30 16:38:25.897  4654  4729 I bt_vendor: low_power_mode_cb
,11-30 16:38:25.899  4654  4729 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,11-30 16:38:25.899  4654  4729 I bt_vendor: epilog_cb
11-30 16:38:25.899  4654  4729 I bt_hci  : epilog_finished_callback
,11-30 16:38:25.902  4654  4725 I bt_hci_h4: hal_close
,11-30 16:38:25.902  4654  4725 I bt_userial_vendor: device fd = 54 close
,11-30 16:38:25.946  5779  5779 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-30 16:38:25.946  5779  5779 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at java.io.File.exists(File.java:361)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-30 16:38:25.946  5779  5779 D StrictMode: StrictMode policy violation; ~duration=111 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-30 16:38:25.946  5779  5779 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-30 16:38:25.946  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-30 16:38:25.947  5779  5779 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-30 16:38:25.947  5779  5779 D StrictMode: StrictMode policy violation; ~duration=109 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.r.e.b(PG:170)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-30 16:38:25.947  5779  5779 D StrictMode: StrictMode policy violation; ~duration=103 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.r.k.d(PG:583)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.r.e.b(PG:170)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-30 16:38:25.947  5779  5779 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at java.io.File.exists(File.java:361)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-30 16:38:25.947  5779  5779 D StrictMode: StrictMode policy violation; ~duration=80 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at java.io.File.exists(File.java:361)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-30 16:38:25.947  5779  5779 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-30 16:38:25.947  5779  5779 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-30 16:38:25.953  5767  5767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-30 16:38:25.959  3619  3619 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-30 16:38:25.971  5767  5767 D DockEventReceiver: finishStartingService: stopping service
11-30 16:38:25.972   926  3911 I ActivityManager: Killing 5201:com.google.android.deskclock/u0a66 (adj 15): empty #17
,11-30 16:38:26.009  4654  4722 D bt_stack_manager: event_shut_down_stack finished.
11-30 16:38:26.009  4654  4721 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-30 16:38:26.011  4654  4654 D BtGatt.DebugUtils: handleDebugAction() action=null
11-30 16:38:26.011  4654  4721 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-30 16:38:26.011  4654  4654 D BtGatt.GattService: Received stop request...Stopping profile...
11-30 16:38:26.011  4654  4654 D BtGatt.GattService: stop()
11-30 16:38:26.011  4654  4654 D BtGatt.AdvertiseManager: advertise clients cleared
11-30 16:38:26.013  4654  4654 V BluetoothAdapterState: isTurningOff()=false
11-30 16:38:26.013  4654  4654 V BluetoothAdapterState: isTurningOn()=false
11-30 16:38:26.013  4654  4654 V BluetoothAdapterState: isBleTurningOn()=false
11-30 16:38:26.013  4654  4654 V BluetoothAdapterState: isBleTurningOff()=true
11-30 16:38:26.013  4654  4721 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-30 16:38:26.013  4654  4721 D BluetoothAdapterProperties: Setting state to 10
11-30 16:38:26.013  4654  4721 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-30 16:38:26.014   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-30 16:38:26.015  4654  4721 I BluetoothAdapterState: Entering OffState
11-30 16:38:26.020  4654  4654 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-30 16:38:26.020  4654  4654 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-30 16:38:26.020  4654  4654 I BluetoothServiceJni: cleanupNative: return from cleanup
11-30 16:38:26.021  4654  4722 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-30 16:38:26.025  4654  4654 I art     : System.exit called, status: 0
11-30 16:38:26.025  4654  4654 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-30 16:38:26.052  5706  5706 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-30 16:38:26.061   926  3633 I ActivityManager: Process com.android.bluetooth (pid 4654) has died
,11-30 16:38:26.090  5706  5765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-30 16:38:26.090  5706  5765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-30 16:38:26.090  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-30 16:38:26.090  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-30 16:38:26.090  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-30 16:38:26.090  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-30 16:38:26.090  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-30 16:38:26.090  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-30 16:38:26.090  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-30 16:38:26.090  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-30 16:38:26.090  5706  5765 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-30 16:38:26.090  5706  5765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-30 16:38:26.094  5706  5752 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-30 16:38:26.103  5779  5811 W ActivityThread: ClassLoader.loadClass: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
,11-30 16:38:26.104   926   943 I ActivityManager: Start proc 5812:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-30 16:38:26.163  5812  5812 D AdapterServiceConfig: Adding HeadsetService
,11-30 16:38:26.163  5812  5812 D AdapterServiceConfig: Adding A2dpService
11-30 16:38:26.163  5812  5812 D AdapterServiceConfig: Adding HidService
11-30 16:38:26.164  5812  5812 D AdapterServiceConfig: Adding HealthService
11-30 16:38:26.164  5812  5812 D AdapterServiceConfig: Adding PanService
11-30 16:38:26.164  5812  5812 D AdapterServiceConfig: Adding GattService
11-30 16:38:26.164  5812  5812 D AdapterServiceConfig: Adding BluetoothMapService
11-30 16:38:26.164  5812  5812 D AdapterServiceConfig: Adding SapService
,11-30 16:38:26.171  5812  5812 D BluetoothAdapterState: make() - Creating AdapterState
,11-30 16:38:26.171   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@48d4778:true
,11-30 16:38:26.173  5812  5812 I bt_bluedroid: init
,11-30 16:38:26.173  5812  5825 I BluetoothAdapterState: Entering OffState
,11-30 16:38:26.176  5812  5826 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-30 16:38:26.176  5812  5826 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
,11-30 16:38:26.176  5812  5826 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-30 16:38:26.176  5812  5826 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-30 16:38:26.177  5812  5812 I bt_bluedroid: get_profile_interface socket
,11-30 16:38:26.178  5812  5829 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
11-30 16:38:26.178  5812  5812 I bt_bluedroid: get_profile_interface sdp
,11-30 16:38:26.179  5812  5829 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-30 16:38:26.183  5812  5824 I bt_bluedroid: config_hci_snoop_log
,11-30 16:38:26.184   926   943 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 9 receivers.
,11-30 16:38:26.187  5812  5825 D BluetoothAdapterState: Current state: OFF, message: 0
,11-30 16:38:26.187  5812  5825 D BluetoothAdapterProperties: Setting state to 14
11-30 16:38:26.187  5812  5825 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-30 16:38:26.188  5812  5825 D BluetoothBondStateMachine: make
,11-30 16:38:26.190  5812  5830 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-30 16:38:26.191  5779  5802 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-30 16:38:26.192  5812  5825 I BluetoothAdapterState: Entering PendingCommandState
,11-30 16:38:26.193  5812  5812 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-30 16:38:26.195  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@779d295
11-30 16:38:26.196  5812  5812 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-30 16:38:26.197  5812  5812 D BtGatt.GattService: Received start request. Starting profile...
,11-30 16:38:26.197  5812  5812 D BtGatt.GattService: start()
11-30 16:38:26.197  5812  5812 I bt_bluedroid: get_profile_interface gatt
11-30 16:38:26.198  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@779d295
11-30 16:38:26.198  5812  5812 D BtGatt.AdvertiseManager: advertise manager created
,11-30 16:38:26.202  5812  5812 V BluetoothAdapterState: isTurningOff()=false
,11-30 16:38:26.202  5812  5812 V BluetoothAdapterState: isTurningOn()=false
11-30 16:38:26.202  5812  5812 V BluetoothAdapterState: isBleTurningOn()=true
11-30 16:38:26.202  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
,11-30 16:38:26.203  5812  5825 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
11-30 16:38:26.204  5812  5825 I bt_bluedroid: bt_bluedroid
11-30 16:38:26.204  5812  5826 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-30 16:38:26.204  5812  5826 I bt_hci  : start_up
,11-30 16:38:26.209  5812  5826 I bt_vendor: alloc value 0xf40a9871
11-30 16:38:26.210  5812  5826 I bt_vendor: init
11-30 16:38:26.210  5812  5826 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-30 16:38:26.210  5812  5826 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-30 16:38:26.260   926   943 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@305f2bc:true
,11-30 16:38:26.316  5812  5826 D bt_hci  : start_up starting async portion
,11-30 16:38:26.316  5812  5833 I bt_hci  : event_finish_startup
11-30 16:38:26.316  5812  5833 I bt_hci_h4: hal_open
11-30 16:38:26.316  5812  5833 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-30 16:38:26.318  5812  5833 I bt_userial_vendor: device fd = 54 open
,11-30 16:38:26.315  5837  5837 W irq/448-msm_hs_: type=1400 audit(0.0:120): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-30 16:38:26.330  5812  5833 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-30 16:38:26.332  5812  5833 D bt_hwcfg: Chipset BCM4358A3
11-30 16:38:26.332  5812  5833 D bt_hwcfg: Target name = [BCM4358A3]
11-30 16:38:26.332  5812  5833 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-30 16:38:26.596  5812  5825 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
,11-30 16:38:26.618  3619  5841 V NQFileLogger: [127] e.a: about to write to file
,11-30 16:38:26.623  3619  5841 V ProcessReports: [127] ProcessReportsService.a: If not already scheduled, schedule for 3600 to 14400 seconds from now (but might be processed inline after 900 seconds instead)
,11-30 16:38:26.835  5812  5833 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-30 16:38:26.835  5812  5833 D bt_hwcfg: Settlement delay -- 100 ms
11-30 16:38:26.835  5812  5833 I bt_hwcfg: Setting fw settlement delay to 100 
,11-30 16:38:26.960  5812  5833 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-30 16:38:26.961  5812  5833 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,11-30 16:38:26.963  5812  5833 I bt_hwcfg: vendor lib fwcfg completed
,11-30 16:38:26.963  5812  5833 I bt_vendor: firmware callback
11-30 16:38:26.964  5812  5833 I bt_hci  : firmware_config_callback
,11-30 16:38:26.974  5812  5843 I bt_btu  : btu_task pending for preload complete event
11-30 16:38:26.974  5812  5843 I bt_btu_task: Bluetooth chip preload is complete
11-30 16:38:26.975  5812  5843 I bt_btu  : btu_task received preload complete event
11-30 16:38:26.982  5812  5843 I         : BTE_InitTraceLevels -- TRC_HCI
11-30 16:38:26.982  5812  5843 I         : BTE_InitTraceLevels -- TRC_L2CAP
,11-30 16:38:26.982  5812  5843 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-30 16:38:26.982  5812  5843 I         : BTE_InitTraceLevels -- TRC_AVDT
11-30 16:38:26.982  5812  5843 I         : BTE_InitTraceLevels -- TRC_AVRC
11-30 16:38:26.983  5812  5843 I         : BTE_InitTraceLevels -- TRC_A2D
11-30 16:38:26.983  5812  5843 I         : BTE_InitTraceLevels -- TRC_BNEP
11-30 16:38:26.983  5812  5843 I         : BTE_InitTraceLevels -- TRC_BTM
,11-30 16:38:26.983  5812  5843 I         : BTE_InitTraceLevels -- TRC_GAP
11-30 16:38:26.983  5812  5843 I         : BTE_InitTraceLevels -- TRC_PAN
11-30 16:38:26.983  5812  5843 I         : BTE_InitTraceLevels -- TRC_SDP
,11-30 16:38:26.983  5812  5843 I         : BTE_InitTraceLevels -- TRC_GATT
11-30 16:38:26.983  5812  5843 I         : BTE_InitTraceLevels -- TRC_SMP
11-30 16:38:26.984  5812  5843 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-30 16:38:26.984  5812  5843 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-30 16:38:27.078  5812  5843 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf4027549
11-30 16:38:27.078  5812  5843 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf4027549 
,11-30 16:38:27.098  5812  5829 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-30 16:38:27.103  5812  5829 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-30 16:38:27.104  5812  5829 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-30 16:38:27.105  5812  5825 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 0
11-30 16:38:27.106  5812  5829 D BluetoothAdapterProperties: Name is: Nexus 6P
11-30 16:38:27.109  5812  5829 D BluetoothAdapterProperties: Scan Mode:20
11-30 16:38:27.109  5812  5829 D BluetoothAdapterProperties: Discoverable Timeout:120
11-30 16:38:27.110  5812  5829 D bt_hci  : do_postload posting postload work item
11-30 16:38:27.110  5812  5833 I bt_hci  : event_postload
,11-30 16:38:27.110  5812  5833 I bt_vendor: sco_config_cb
,11-30 16:38:27.110  5812  5833 I bt_hci  : sco_config_callback postload finished.
11-30 16:38:27.115  5812  5829 D bt_bte_conf: Device ID record 1 : primary
11-30 16:38:27.115  5812  5829 D bt_bte_conf:   vendorId            = 000f
11-30 16:38:27.115  5812  5829 D bt_bte_conf:   vendorIdSource      = 0001
11-30 16:38:27.115  5812  5829 D bt_bte_conf:   product             = 1200
,11-30 16:38:27.115  5812  5829 D bt_bte_conf:   version             = 1436
11-30 16:38:27.115  5812  5829 D bt_bte_conf:   clientExecutableURL = 
11-30 16:38:27.115  5812  5829 D bt_bte_conf:   serviceDescription  = 
,11-30 16:38:27.115  5812  5829 D bt_bte_conf:   documentationURL    = 
11-30 16:38:27.116  5812  5829 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-30 16:38:27.117  5812  5826 D bt_stack_manager: event_start_up_stack finished
11-30 16:38:27.118  5812  5825 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-30 16:38:27.118  5812  5825 D BluetoothAdapterProperties: Setting state to 15
11-30 16:38:27.118  5812  5825 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,11-30 16:38:27.118  5812  5833 I bt_vendor: low_power_mode_cb
11-30 16:38:27.120  5812  5825 I BluetoothAdapterState: Entering BleOnState
,11-30 16:38:27.128  5812  5825 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-30 16:38:27.128  5812  5825 D BluetoothAdapterProperties: Setting state to 11
11-30 16:38:27.128  5812  5825 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-30 16:38:27.134  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@779d295
11-30 16:38:27.135  5812  5812 D HeadsetService: Received start request. Starting profile...
11-30 16:38:27.139  5812  5812 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,11-30 16:38:27.139  5812  5812 D HeadsetStateMachine: make
,11-30 16:38:27.152  5812  5825 I BluetoothAdapterState: Entering PendingCommandState
,11-30 16:38:27.152  5812  5812 D HeadsetStateMachine: max_hf_connections = 1
,11-30 16:38:27.153  5812  5812 I bt_bluedroid: get_profile_interface handsfree
11-30 16:38:27.153  5812  5829 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-30 16:38:27.154  5812  5829 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
11-30 16:38:27.156  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@779d295
11-30 16:38:27.156  5812  5812 D A2dpService: Received start request. Starting profile...
11-30 16:38:27.157  5812  5812 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-30 16:38:27.157  5812  5812 I bt_bluedroid: get_profile_interface avrcp
,11-30 16:38:27.164  5812  5812 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
11-30 16:38:27.164  5812  5812 I BluetoothA2dpServiceJni: classInitNative: succeeds
,11-30 16:38:27.164  5812  5812 D A2dpStateMachine: make
11-30 16:38:27.166  5812  5812 I bt_bluedroid: get_profile_interface a2dp
,11-30 16:38:27.167  5812  5829 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-30 16:38:27.169  5812  5851 D A2dpStateMachine: Enter Disconnected: -2
,11-30 16:38:27.169  5812  5812 I BluetoothHidServiceJni: classInitNative: succeeds
11-30 16:38:27.170  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@779d295
,11-30 16:38:27.172  5767  5767 D BluetoothInputDevice: Proxy object connected
,11-30 16:38:27.173  5812  5812 D HidService: Received start request. Starting profile...
11-30 16:38:27.173  5812  5812 I bt_bluedroid: get_profile_interface hidhost
11-30 16:38:27.173  5812  5812 D HidService: setHidService(): set to: null
11-30 16:38:27.173  5812  5829 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf400856d
11-30 16:38:27.173  5812  5829 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-30 16:38:27.175  5812  5812 I BluetoothHealthServiceJni: classInitNative: succeeds
11-30 16:38:27.176  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@779d295
11-30 16:38:27.176  3619  3619 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-30 16:38:27.176  5812  5812 D HealthService: Received start request. Starting profile...
11-30 16:38:27.177  5767  5767 D HidProfile: Bluetooth service connected
11-30 16:38:27.178  5812  5812 I bt_bluedroid: get_profile_interface health
11-30 16:38:27.178  5812  5812 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-30 16:38:27.179  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@779d295
11-30 16:38:27.180  5767  5767 D BluetoothPan: BluetoothPAN Proxy object connected
11-30 16:38:27.181  5812  5812 D PanService: Received start request. Starting profile...
11-30 16:38:27.181  5812  5812 D BluetoothPanServiceJni: initializeNative(L110): pan
11-30 16:38:27.181  5812  5812 I bt_bluedroid: get_profile_interface pan
11-30 16:38:27.181  5767  5767 D PanProfile: Bluetooth service connected
11-30 16:38:27.181  5812  5829 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-30 16:38:27.183  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@779d295
,11-30 16:38:27.184  5767  5767 D BluetoothMap: Proxy object connected
11-30 16:38:27.185  5812  5812 D BluetoothMapService: Received start request. Starting profile...
11-30 16:38:27.185  5812  5812 D BluetoothMapService: start()
11-30 16:38:27.187  5767  5767 D MapProfile: Bluetooth service connected
11-30 16:38:27.188  5812  5812 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
11-30 16:38:27.188  5767  5767 D BluetoothMap: getConnectedDevices()
11-30 16:38:27.188  5812  5812 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-30 16:38:27.188  5812  5812 D BluetoothMapAppObserver: createReceiver()
11-30 16:38:27.189  5767  5767 D BluetoothMap: Bluetooth is Not enabled
,11-30 16:38:27.190  5812  5812 D BluetoothMapAppObserver: initObservers()
11-30 16:38:27.190  5812  5812 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-30 16:38:27.198  5812  5812 V SapService: SapBinder()
11-30 16:38:27.198  5812  5812 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@779d295
11-30 16:38:27.199  5812  5812 D SapService: Received start request. Starting profile...
11-30 16:38:27.199  5812  5812 V SapService: start()
11-30 16:38:27.201  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-30 16:38:27.201  5812  5812 V BluetoothAdapterState: isTurningOn()=true
11-30 16:38:27.201  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-30 16:38:27.201  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-30 16:38:27.201  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-30 16:38:27.201  5812  5812 V BluetoothAdapterState: isTurningOn()=true
11-30 16:38:27.202  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-30 16:38:27.202  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-30 16:38:27.202  5812  5849 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-30 16:38:27.202  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-30 16:38:27.202  5812  5812 V BluetoothAdapterState: isTurningOn()=true
11-30 16:38:27.202  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-30 16:38:27.202  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-30 16:38:27.203  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-30 16:38:27.203  5812  5812 V BluetoothAdapterState: isTurningOn()=true
11-30 16:38:27.203  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-30 16:38:27.203  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-30 16:38:27.204  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-30 16:38:27.204  5812  5812 V BluetoothAdapterState: isTurningOn()=true
11-30 16:38:27.204  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-30 16:38:27.204  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-30 16:38:27.204  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-30 16:38:27.204  5812  5812 V BluetoothAdapterState: isTurningOn()=true
11-30 16:38:27.204  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-30 16:38:27.204  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-30 16:38:27.205  5812  5812 V BluetoothAdapterState: isTurningOff()=false
11-30 16:38:27.205  5812  5812 V BluetoothAdapterState: isTurningOn()=true
11-30 16:38:27.205  5812  5812 V BluetoothAdapterState: isBleTurningOn()=false
11-30 16:38:27.205  5812  5812 V BluetoothAdapterState: isBleTurningOff()=false
11-30 16:38:27.206  5812  5825 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-30 16:38:27.206  5812  5825 D BluetoothAdapterProperties: ScanMode =  20
11-30 16:38:27.206  5812  5825 D BluetoothAdapterProperties: State =  11
11-30 16:38:27.206  5812  5825 D BluetoothAdapterProperties: Setting state to 12
11-30 16:38:27.206  5812  5825 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-30 16:38:27.207  5812  5829 D BluetoothAdapterProperties: Scan Mode:21
11-30 16:38:27.207  3190  3205 D BluetoothPan: onBluetoothStateChange on: true
11-30 16:38:27.207  5812  5829 D BluetoothAdapterProperties: Discoverable Timeout:120
11-30 16:38:27.207  5812  5825 I BluetoothAdapterState: Entering OnState
11-30 16:38:27.209  3190  3190 D BluetoothPan: BluetoothPAN Proxy object connected
11-30 16:38:27.209  3190  3190 D PanProfile: Bluetooth service connected
11-30 16:38:27.209  5767  5777 D BluetoothPan: onBluetoothStateChange on: true
11-30 16:38:27.209  5767  5778 D BluetoothPbap: onBluetoothStateChange: up=true
11-30 16:38:27.211  5767  5777 D BluetoothMap: onBluetoothStateChange: up=true
11-30 16:38:27.211   926   943 D BluetoothA2dp: onBluetoothStateChange: up=true
11-30 16:38:27.211  3190  3992 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-30 16:38:27.212   926   926 D BluetoothA2dp: Proxy object connected
11-30 16:38:27.213   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-30 16:38:27.213  3190  3190 D BluetoothInputDevice: Proxy object connected
11-30 16:38:27.213  3190  3205 D BluetoothPbap: onBluetoothStateChange: up=true
11-30 16:38:27.213  3190  3190 D HidProfile: Bluetooth service connected
11-30 16:38:27.215  3190  3992 D BluetoothHeadset: onBluetoothStateChange: up=true
11-30 16:38:27.215  3190  3202 D BluetoothMap: onBluetoothStateChange: up=true
11-30 16:38:27.217  5812  5812 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-30 16:38:27.217   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-30 16:38:27.217   926   943 D BluetoothHeadset: onBluetoothStateChange: up=true
11-30 16:38:27.217  3190  3190 D BluetoothMap: Proxy object connected
11-30 16:38:27.217  3190  3190 D MapProfile: Bluetooth service connected
11-30 16:38:27.217  3835  3855 D BluetoothHeadset: onBluetoothStateChange: up=true
11-30 16:38:27.217  3190  3190 D BluetoothMap: getConnectedDevices()
11-30 16:38:27.217  5812  5812 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-30 16:38:27.218  3190  3992 D BluetoothA2dp: onBluetoothStateChange: up=true
11-30 16:38:27.218  5812  5812 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-30 16:38:27.219  3190  3190 D BluetoothA2dp: Proxy object connected
11-30 16:38:27.220  5812  5812 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-30 16:38:27.221  5812  5812 D ObexServerSockets: Succeed to create listening sockets 
11-30 16:38:27.221  5812  5812 D ObexServerSockets0: startAccept()
11-30 16:38:27.221  5812  5812 D ObexServerSockets0: prepareForNewConnect()
11-30 16:38:27.224  5767  5778 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-30 16:38:27.224  5812  5812 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-30 16:38:27.224  5812  5812 D BluetoothSdpJni: SDP Create record success - handle: 0
11-30 16:38:27.225   926   926 I Telecom : BluetoothPhoneService: queryPhoneState
11-30 16:38:27.227  5812  5856 D ObexServerSockets0: Accepting socket connection...
11-30 16:38:27.228  5767  5767 D LocalBluetoothProfileManager: Adding local A2DP profile
11-30 16:38:27.228  5812  5857 D ObexServerSockets0: Accepting socket connection...
11-30 16:38:27.228  5812  5812 D BluetoothMapService: onReceive
11-30 16:38:27.228  5812  5812 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-30 16:38:27.228  5812  5812 D BluetoothMapService: STATE_ON
11-30 16:38:27.230  5812  5860 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-30 16:38:27.232  5767  5767 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-30 16:38:27.232  5812  5860 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-30 16:38:27.232  5812  5860 D BluetoothSdpJni: SDP Create record success - handle: 1
,11-30 16:38:27.238  5767  5767 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-30 16:38:27.241  5767  5767 D BluetoothA2dp: Proxy object connected
,11-30 16:38:27.245  3619  3619 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-30 16:38:27.246  5767  5767 D DockEventReceiver: finishStartingService: stopping service
,11-30 16:38:27.253  5767  5767 D BluetoothPbap: Proxy object connected
,11-30 16:38:27.253  5767  5767 D PbapServerProfile: Bluetooth service connected
11-30 16:38:27.254  5812  5812 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-30 16:38:27.254  5812  5812 D ObexServerSockets0: prepareForNewConnect()
11-30 16:38:27.254  3190  3190 D BluetoothPbap: Proxy object connected
11-30 16:38:27.255  3190  3190 D PbapServerProfile: Bluetooth service connected
,11-30 16:38:27.261  5812  5864 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-30 16:38:27.277  5812  5868 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-30 16:38:27.278  5812  5868 I BtOppRfcommListener: Accept thread started.
,11-30 16:38:27.315   926   926 D BluetoothHeadset: Proxy object connected
,11-30 16:38:27.316  3835  3851 D BluetoothHeadset: Proxy object connected
11-30 16:38:27.316  3190  3202 D BluetoothHeadset: Proxy object connected
11-30 16:38:27.316  3190  3190 D HeadsetProfile: Bluetooth service connected
11-30 16:38:27.316   926   926 D BluetoothHeadset: Proxy object connected
11-30 16:38:27.316   926   926 D BluetoothHeadset: Proxy object connected
11-30 16:38:27.317   926   943 D BluetoothHeadset: Proxy object connected
,11-30 16:38:27.317   926   943 D BluetoothHeadset: Proxy object connected
11-30 16:38:27.318  3835  4274 D BluetoothHeadset: Proxy object connected
,11-30 16:38:27.335  5767  5777 D BluetoothHeadset: Proxy object connected
11-30 16:38:27.338  5767  5767 D HeadsetProfile: Bluetooth service connected
,11-30 16:38:27.619  5706  5765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-30 16:38:27.619  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-30 16:38:27.619  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-30 16:38:27.619  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-30 16:38:27.619  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-30 16:38:27.619  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-30 16:38:27.619  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-30 16:38:27.619  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-30 16:38:27.619  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-30 16:38:27.626  5706  5765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-30 16:38:27.629  5706  5752 I io.jxcore.node.ConnectivityMonitorTest: Starting test: testIsWifiEnabled
,11-30 16:38:27.631   926  3917 D WifiService: setWifiEnabled: false pid=5706, uid=10077
,11-30 16:38:27.631   926  3917 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-30 16:38:27.635  5706  5752 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-30 16:38:27.637   926  3022 D WifiStateMachine: WifiStateMachine: Leaving Connected state
,11-30 16:38:27.637   926  3022 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
11-30 16:38:27.638   926  3022 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-30 16:38:27.638   926  3022 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-30 16:38:27.653   926  5456 D DhcpClient: Clearing IP address
,11-30 16:38:27.653   508   920 D CommandListener: Clearing all IP addresses on wlan0
,11-30 16:38:27.661   508   920 D CommandListener: Setting iface cfg
,11-30 16:38:27.672  3619  5508 V NativeCrypto: Read error: ssl=0x7f7a197c80: I/O error during system call, Connection timed out
,11-30 16:38:27.674  3619  5508 V NativeCrypto: SSL shutdown failed: ssl=0x7f7a197c80: I/O error during system call, Broken pipe
,11-30 16:38:27.674   926  5457 D DhcpClient: Receive thread stopped
11-30 16:38:27.677   926  3915 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
11-30 16:38:27.677   926  3024 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-30 16:38:27.677   926  3024 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
11-30 16:38:27.681   926  5454 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-30 16:38:27.681   926   926 D RttService: SCAN_AVAILABLE : 1
11-30 16:38:27.682   926  3132 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-30 16:38:27.683   534   534 E Parcel  : Reading a NULL string not supported here.
11-30 16:38:27.686   926  5454 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
,11-30 16:38:27.688   926  3024 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-30 16:38:27.692  3805  3952 W QCNEJ   : |CORE| network lost: 100
11-30 16:38:27.692  3805  3952 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-30 16:38:27.700   926  3022 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-30 16:38:27.720   926  3022 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-30 16:38:27.731   508   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-30 16:38:27.751   508   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-30 16:38:27.751   508   920 D CommandListener: Clearing all IP addresses on wlan0
11-30 16:38:27.752   508   920 D TetherController: Setting IP forward enable = 0
11-30 16:38:27.752   926  3024 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-30 16:38:27.752   926  3024 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-30 16:38:27.754   926  3022 D DhcpClient: doQuit
11-30 16:38:27.754   926  3022 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-30 16:38:27.754   926   943 D Tethering: MasterInitialState.processMessage what=3
,11-30 16:38:27.755  3499  3499 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-30 16:38:27.755   926  5456 D DhcpClient: onQuitting
,11-30 16:38:27.763  4997  4997 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 6
,11-30 16:38:27.766  5372  5372 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@126c25e and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,11-30 16:38:27.769  5113  5137 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-30 16:38:27.769  5113  5137 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-30 16:38:27.769  5113  5137 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-30 16:38:27.769  5113  5137 E SarControlService: no key has been found,reset the power
11-30 16:38:27.769  5113  5150 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-30 16:38:27.770  5113  5150 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-30 16:38:27.770  5113  5150 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,11-30 16:38:27.774  5138  5138 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-30 16:38:27.774  5138  5138 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-30 16:38:27.775  5113  5150 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-30 16:38:27.775  5113  5150 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-30 16:38:27.775  5113  5150 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-30 16:38:27.776  5138  5138 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-30 16:38:27.776  5138  5138 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-30 16:38:27.780  5138  5152 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@bdad0b4 HexData = [00000000ea03000000000000ffffffff]
11-30 16:38:27.780  5138  5152 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-30 16:38:27.780  5138  5152 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
,11-30 16:38:27.780  3998  3998 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-30 16:38:27.782  5138  5138 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-30 16:38:27.782  5113  5124 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-30 16:38:27.783  3998  3998 D SystemUpdateService: onCreate
11-30 16:38:27.784  3499  3499 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-30 16:38:27.787  3998  3998 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-30 16:38:27.789  3998  5886 I SystemUpdateService: active receiver: enabled
,11-30 16:38:27.792  5138  5152 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@bdad0b4 HexData = [00000000eb03000000000000ffffffff]
,11-30 16:38:27.792  5138  5152 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-30 16:38:27.793  5138  5152 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-30 16:38:27.794  5138  5138 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-30 16:38:27.794  5113  5123 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-30 16:38:27.795  3998  3998 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-30 16:38:27.796  3998  5480 I iu.UploadsManager: num queued entries: 0
11-30 16:38:27.797  3998  5480 I iu.UploadsManager: num updated entries: 0
11-30 16:38:27.798  3998  5480 I iu.SyncManager: NEXT; no task
,11-30 16:38:27.798  3499  3499 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-30 16:38:27.801   508   913 W SocketClient: write error (Broken pipe)
11-30 16:38:27.802   508   913 W SocketClient: Unable to send msg '600 Iface linkstate wlan0 up'
11-30 16:38:27.802   508   913 W SocketListener: Error sending broadcast (Broken pipe)
11-30 16:38:27.802  3998  3998 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-30 16:38:27.804  3998  5886 I SystemUpdateService: Already downloaded, skipping offpeak checks.
11-30 16:38:27.804  3998  3998 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-30 16:38:27.805  3998  5886 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-30 16:38:27.805  3998  5886 I SystemUpdateService: now status is 0 (complete)
11-30 16:38:27.805  3998  5886 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-30 16:38:27.806  3998  5886 I SystemUpdateService: file has been verified
11-30 16:38:27.806  3998  5886 I SystemUpdateService: OTA package size = 21989297
,11-30 16:38:27.809  3998  5886 I SystemUpdateService: showing system update notification
,11-30 16:38:27.816   926   936 I ActivityManager: Start proc 5889:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
11-30 16:38:27.816  3499  3499 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-30 16:38:27.827  3998  3998 D SystemUpdateService: onDestroy
,11-30 16:38:27.829   508   920 E Netd    : netlink response contains error (No such file or directory)
11-30 16:38:27.829   508   920 D TetherController: Setting IP forward enable = 0
11-30 16:38:27.830   926  3024 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-30 16:38:27.832  3499  3499 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-30 16:38:27.852  5889  5889 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-30 16:38:27.854  5889  5889 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-30 16:38:27.860  5889  5889 D SprintDMHelper: simOperator: 
11-30 16:38:27.860  5889  5889 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-30 16:38:27.872   926  3633 I ActivityManager: Start proc 5904:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,11-30 16:38:27.935   926  3022 D wifi    : In wifi stop Hal
,11-30 16:38:27.935   926  3022 D wifi    : halHandle = 0x7f5dadb040, mVM = 0x7f7a10d140, mCls = 0x100a02
11-30 16:38:27.935   926  3498 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-30 16:38:27.936   926  3498 D WifiHAL : Got a signal to exit!!!
11-30 16:38:27.936   926  3498 I WifiHAL : Exit wifi_event_loop
,11-30 16:38:27.936   926  3022 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-30 16:38:27.936   926  3022 E WifiHAL : Event processing terminated
11-30 16:38:27.936   926  3022 D wifi    : In wifi cleaned up handler
11-30 16:38:27.936   926  3022 I WifiHAL : Internal cleanup completed
11-30 16:38:27.936  5086  5086 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-30 16:38:27.937  4166  4273 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-30 16:38:27.939  5086  5918 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-30 16:38:27.942   926  3911 I ActivityManager: Killing 5532:com.qualcomm.timeservice/1000 (adj 15): empty #17
,11-30 16:38:27.962   926  3498 D wifi    : set interface wlan0 flags (DOWN)
11-30 16:38:27.963   926  3022 D WifiNative-HAL: HAL event thread stopped successfully
,11-30 16:38:27.971   926   936 I ActivityManager: Start proc 5919:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-30 16:38:27.998  5919  5919 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-30 16:38:28.006   926   936 I ActivityManager: Killing 5372:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-30 16:38:28.139  5706  5765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-30 16:38:28.139  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-30 16:38:28.139  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-30 16:38:28.139  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-30 16:38:28.139  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-30 16:38:28.139  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-30 16:38:28.139  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-30 16:38:28.139  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-30 16:38:28.139  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-30 16:38:28.142  5706  5765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-30 16:38:28.144   926  3613 D WifiService: setWifiEnabled: true pid=5706, uid=10077
11-30 16:38:28.144   926  3613 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-30 16:38:28.145  5706  5752 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-30 16:38:28.165   508   920 D SoftapController: Softap fwReload - Ok
,11-30 16:38:28.167   926   943 D Tethering: InitialState.processMessage what=4
,11-30 16:38:28.169   508   920 D CommandListener: Setting iface cfg
11-30 16:38:28.169   508   920 D CommandListener: Trying to bring down wlan0
11-30 16:38:28.170   926   943 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
11-30 16:38:28.171   508   920 D CommandListener: Clearing all IP addresses on wlan0
,11-30 16:38:28.174   926  3022 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-30 16:38:28.648   926  3633 D WifiService: setWifiEnabled: true pid=5706, uid=10077
,11-30 16:38:28.652   926  3633 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-30 16:38:28.794   926  3022 D wifi    : set interface wlan0 flags (UP)
,11-30 16:38:28.796   926  3022 I WifiHAL : Initializing wifi
,11-30 16:38:28.796   926  3022 I WifiHAL : Creating socket
11-30 16:38:28.800   926   943 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-30 16:38:28.802   926  3022 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-30 16:38:28.802   926  3022 D wifi    : Did set static halHandle = 0x7f5dadb040
11-30 16:38:28.802   926  3022 D wifi    : halHandle = 0x7f5dadb040, mVM = 0x7f7a10d140, mCls = 0x1972
,11-30 16:38:28.803   926  3022 D wifi    : array field set
11-30 16:38:28.803   926  3022 I WifiNative-HAL: interface[0] = wlan0
11-30 16:38:28.805   926  5935 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547032510528
11-30 16:38:28.807   926  5935 D wifi    : waitForHalEvents called, vm = 0x7f7a10d140, obj = 0x1972, env = 0x7f5f2835c0
11-30 16:38:28.810   926  3022 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
11-30 16:38:28.811   926  3022 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,11-30 16:38:28.878  5936  5936 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-30 16:38:28.899  5936  5936 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-30 16:38:28.910  5936  5936 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-30 16:38:28.910  5936  5936 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-30 16:38:29.155   926  3244 D WifiService: setWifiEnabled: true pid=5706, uid=10077
,11-30 16:38:29.156   926  3244 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-30 16:38:29.660   926  3915 D WifiService: setWifiEnabled: true pid=5706, uid=10077
,11-30 16:38:29.660   926  3915 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-30 16:38:29.829   926  3022 D WifiConfigStore: Loading config and enabling all networks 
,11-30 16:38:29.851   926  3022 D WifiConfigStore: loaded 0 passpoint configs
,11-30 16:38:29.852   926  3022 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,11-30 16:38:29.853   926  3022 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-30 16:38:29.856   926  3022 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-30 16:38:29.858   926  3022 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-30 16:38:29.858   926  3022 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-30 16:38:29.858   926  3022 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-30 16:38:29.859   926  3022 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-30 16:38:29.864   926  3022 D WifiNative-HAL: Setting external_sim to 1
,11-30 16:38:29.865  5086  5086 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-30 16:38:29.865   926  3022 D wifi    : setting dfs flag to true, 0x7f61b924e0
,11-30 16:38:29.866   926  3022 D WifiStateMachine: Setting OUI to DA-A1-19
,11-30 16:38:29.867   926  3022 D wifi    : setting scan oui 0x7f61b924e0
11-30 16:38:29.867   926  3022 D WifiHAL : Sending mac address OUI
,11-30 16:38:29.872   926  3022 E native  : do suspend false
,11-30 16:38:29.883   926  3022 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-30 16:38:29.883   926   926 D RttService: SCAN_AVAILABLE : 3
11-30 16:38:29.883   926  3132 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-30 16:38:29.883   508   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-30 16:38:29.885   508   920 D CommandListener: Setting iface cfg
,11-30 16:38:29.889   926  3005 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '128 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 128 Failed to set address (No such device)'
,11-30 16:38:29.889   926  3005 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-30 16:38:29.901   926  3005 D WifiNative-HAL: p2pGetDeviceAddress
,11-30 16:38:29.906   926   941 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=108933 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=18 mControllerEnergyUsed=68 }
11-30 16:38:29.906   926  3005 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-30 16:38:30.170  5706  5765 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-30 16:38:30.170  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-30 16:38:30.170  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-30 16:38:30.170  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-30 16:38:30.170  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-30 16:38:30.170  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-30 16:38:30.170  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-30 16:38:30.170  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-30 16:38:30.170  5706  5765 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-30 16:38:30.175  5706  5765 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-30 16:38:30.178  5706  5752 D BluetoothAdapter: enable(): BT is already enabled..!
,11-30 16:38:30.179   926  3633 D WifiService: setWifiEnabled: true pid=5706, uid=10077
11-30 16:38:30.180   926  3633 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
11-30 16:38:30.181  5706  5752 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-30 16:38:30.181  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-30 16:38:30.181  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-30 16:38:30.181  5706  5752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@90c8fff removed from the list
,11-30 16:38:30.181  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-30 16:38:30.181  5706  5752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c7331cc removed from the list
11-30 16:38:30.181  5706  5752 D io.jxcore.node.ConnectivityMonitor: stop
11-30 16:38:30.183  5706  5752 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testSetTcpPortNumber
11-30 16:38:30.185  5706  5752 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetTcpPortNumber
11-30 16:38:30.185  5706  5752 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testGetLocalHostPort
,11-30 16:38:30.186  5706  5752 I io.jxcore.node.IncomingSocketThreadTest: Starting test: testConstructor
11-30 16:38:30.189  5706  5752 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityCreated
,11-30 16:38:30.190  5706  5752 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,11-30 16:38:30.191  5706  5752 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityResumed
11-30 16:38:30.191  5706  5752 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-30 16:38:30.191  5706  5752 I io.jxcore.node.LifeCycleMonitorTest: Starting test: constructor
,11-30 16:38:30.194  5706  5752 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivitySaveInstanceState
,11-30 16:38:30.195  5706  5752 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@a720311 Bundle[{}]
11-30 16:38:30.195  5706  5752 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testStartStop
11-30 16:38:30.195  5706  5752 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-30 16:38:30.196  5706  5752 I io.jxcore.node.LifeCycleMonitor: stop: OK
,11-30 16:38:30.197  5706  5752 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStarted
11-30 16:38:30.197  5706  5752 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-30 16:38:30.198  5706  5752 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityStopped
11-30 16:38:30.198  5706  5752 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-30 16:38:30.198  5706  5752 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityDestroyed
11-30 16:38:30.198  5706  5752 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
11-30 16:38:30.199  5706  5752 I io.jxcore.node.LifeCycleMonitorTest: Starting test: testOnActivityPaused
11-30 16:38:30.200  5706  5752 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
11-30 16:38:30.201  5706  5752 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToString
11-30 16:38:30.203  5706  5752 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testToJsonObject
,11-30 16:38:30.205  5706  5752 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testConstructorWithParameters
,11-30 16:38:30.206  5706  5752 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testSetListeningOnPortNumber
,11-30 16:38:30.207  5706  5752 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testGetListeningOnPortNumber
,11-30 16:38:30.208  5706  5752 I io.jxcore.node.ListenerOrIncomingConnectionTest: Starting test: testDefaultConstructor
,11-30 16:38:30.210  5706  5752 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testClose
,11-30 16:38:30.211  5706  5752 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testNoAvailablePorts
,11-30 16:38:31.217  5706  5752 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testGetListeningOnPortNumber
,11-30 16:38:31.219  5706  5752 I io.jxcore.node.OutgoingSocketThreadTest: Starting test: testConstructor
,11-30 16:38:31.225  5706  5752 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetListener
,11-30 16:38:31.227  5706  5752 I io.jxcore.node.SocketThreadBaseTest: Starting test: testSetPeerProperties
,11-30 16:38:31.228  5706  5752 I io.jxcore.node.SocketThreadBaseTest: Starting test: testClose
,11-30 16:38:31.229  5706  5752 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 176)
,11-30 16:38:31.231  5706  5752 I io.jxcore.node.SocketThreadBaseTest: Starting test: testCloseLocalSocketAndStreams
,11-30 16:38:31.231  5706  5752 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,11-30 16:38:31.232  5706  5752 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 177)
,11-30 16:38:31.234  5706  5752 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetPeerProperties
,11-30 16:38:31.236  5706  5752 I io.jxcore.node.SocketThreadBaseTest: Starting test: testEquals
,11-30 16:38:31.238  5706  5752 I io.jxcore.node.SocketThreadBaseTest: Starting test: testGetLocalHostAddressAsString
,11-30 16:38:31.239  5706  5752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-30 16:38:31.240  5706  5752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6283b2a added. We now have 3 listener(s)
,11-30 16:38:31.244  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-30 16:38:31.244  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-30 16:38:31.244  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-30 16:38:31.244  5706  5752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-30 16:38:31.244  5706  5752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da42d1b added. We now have 3 listener(s)
11-30 16:38:31.244  5706  5752 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-30 16:38:31.245  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-30 16:38:31.251  5706  5752 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCancelCurrentOperation
,11-30 16:38:31.252  5706  5752 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStopOperation
11-30 16:38:31.252  5706  5752 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 5
11-30 16:38:31.252  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 4 -> 5
11-30 16:38:31.253  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:31.253  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:31.253  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:31.253  5706  5752 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-30 16:38:31.253  5706  5752 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
,11-30 16:38:31.253  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-30 16:38:31.253  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 16:38:31.253  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-30 16:38:31.257  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,11-30 16:38:31.259  5706  5940 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-30 16:38:31.259  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-30 16:38:31.260  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
,11-30 16:38:31.260  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-30 16:38:31.260  5706  5752 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
,11-30 16:38:31.260  5706  5706 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-30 16:38:31.260  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
11-30 16:38:31.260  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-30 16:38:31.260  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-30 16:38:31.261  5706  5940 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-30 16:38:31.262  5823  5823 W Binder_1: type=1400 audit(0.0:121): avc: denied { ioctl } for path="socket:[28637]" dev="sockfs" ino=28637 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-30 16:38:31.262  5823  5823 W Binder_1: type=1400 audit(0.0:122): avc: denied { ioctl } for path="socket:[28637]" dev="sockfs" ino=28637 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-30 16:38:31.264  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-30 16:38:31.264  5706  5752 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-30 16:38:31.264  5706  5752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-30 16:38:31.266  5706  5940 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
,11-30 16:38:31.269  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:31.269  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-30 16:38:31.269  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-30 16:38:31.270  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-30 16:38:31.270  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
11-30 16:38:31.272  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:31.272  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:31.272  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-30 16:38:31.272  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-30 16:38:31.272  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-30 16:38:31.272  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 05 60 83 34 25 D7 C6
,11-30 16:38:31.272  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 16:38:31.272  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 16:38:31.272  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:31.272  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: was started = false
11-30 16:38:31.273  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 16:38:31.273  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:31.273  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:31.273  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[5, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:31.274  5706  5752 D BluetoothAdapter: STATE_ON
11-30 16:38:31.276  5812  5858 D BtGatt.GattService: registerClient() - UUID=8c50c907-daea-4307-9eb6-9234ffabbf4d
11-30 16:38:31.277  5812  5829 D BtGatt.GattService: onClientRegistered() - UUID=8c50c907-daea-4307-9eb6-9234ffabbf4d, clientIf=5
,11-30 16:38:31.278  5706  5717 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=5
,11-30 16:38:31.281  5812  5831 D BtGatt.AdvertiseManager: message : 0
,11-30 16:38:31.283  5812  5831 D BtGatt.AdvertiseManager: starting multi advertising
,11-30 16:38:31.295  5812  5829 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=5, status=0
,11-30 16:38:31.301  5812  5829 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=5, status=0
,11-30 16:38:31.302  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:31.302  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:31.302  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
11-30 16:38:31.302  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:31.302  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:31.302  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:31.302  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:31.303  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:31.303  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-30 16:38:31.304  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-30 16:38:31.304  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:31.305  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:31.305  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:31.305  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:31.305  5706  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
11-30 16:38:31.306  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
,11-30 16:38:31.306  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-30 16:38:31.306  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-30 16:38:31.306  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-30 16:38:31.306  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
11-30 16:38:31.306  5706  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-30 16:38:31.306  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 16:38:31.306  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [ADVERTISING]
11-30 16:38:31.306  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-30 16:38:31.306  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 16:38:31.306  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [ADVERTISING]Current thread: Thread[main,5,main], id: 1
11-30 16:38:31.306  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 16:38:31.307  5706  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-30 16:38:31.307  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 16:38:31.310  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 16:38:31.310  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: false, is advertising: true
11-30 16:38:31.310  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 16:38:31.310  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 16:38:31.310  5706  5706 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: false, is advertising: true
,11-30 16:38:31.593   926  3917 I ActivityManager: Killing 4735:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-30 16:38:31.811  5706  5706 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: true
,11-30 16:38:31.811  5706  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-30 16:38:31.811  5706  5706 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-30 16:38:33.051  5936  5936 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-30 16:38:33.052  5936  5936 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
11-30 16:38:33.053  5936  5936 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-30 16:38:33.097   926  3022 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
11-30 16:38:33.098   926  3022 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-30 16:38:33.098   926  3022 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-30 16:38:33.107   926  3022 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-30 16:38:33.133   926  3022 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-30 16:38:33.135  5936  5936 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-30 16:38:33.556  5936  5936 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-30 16:38:33.589  5936  5936 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-30 16:38:33.590  5936  5936 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-30 16:38:33.601   926  3022 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-30 16:38:33.601   926  3022 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-30 16:38:33.601   926  3024 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-30 16:38:33.618   926  3022 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-30 16:38:33.631   508   920 D CommandListener: Setting iface cfg
,11-30 16:38:33.637   926  3022 D WifiStateMachine: Start Dhcp Watchdog 2
,11-30 16:38:33.642   926  5945 D DhcpClient: Receive thread started
,11-30 16:38:33.647   926  3024 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 16:38:33.647   926  3022 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-30 16:38:33.647   926  3024 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-30 16:38:33.727   926  3022 E native  : do suspend false
,11-30 16:38:33.742   926  5944 D DhcpClient: Broadcasting DHCPDISCOVER
,11-30 16:38:33.755   926  5945 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172729, domain null
,11-30 16:38:33.756   926  5944 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172729 seconds
,11-30 16:38:33.759   926  5944 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-30 16:38:33.775   926  5945 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-30 16:38:33.775   926  5944 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-30 16:38:33.778   508   920 D CommandListener: Setting iface cfg
11-30 16:38:33.783   926  3022 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-30 16:38:33.788   926  5944 D DhcpClient: Scheduling renewal in 86399s
,11-30 16:38:33.798   926  3022 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-30 16:38:33.800   926  3022 D WifiConfigStore: No blacklist allowed without epno enabled
,11-30 16:38:33.804   926  3022 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-30 16:38:33.811   926  3024 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,11-30 16:38:33.815   926  3024 D ConnectivityService: Adding iface wlan0 to network 101
,11-30 16:38:33.856   926  3024 E ConnectivityService: Unexpected mtu value: 0, wlan0
,11-30 16:38:33.856   926  3024 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-30 16:38:33.858   926  3024 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-30 16:38:33.860   926  3024 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-30 16:38:33.861   926  3024 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-30 16:38:33.867   926  3024 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 16:38:33.872   926  3024 D ConnectivityService: scheduleUnvalidatedPrompt 101
,11-30 16:38:33.872   926  3024 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
11-30 16:38:33.872   926  3024 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-30 16:38:33.872   926  3022 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-30 16:38:33.872   926  3024 D ConnectivityService:    accepting network in place of null
11-30 16:38:33.872   926  3022 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-30 16:38:33.873   926  3024 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -49]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-30 16:38:33.890   926  5943 D NetlinkSocketObserver: NeighborEvent{elapsedMs=112917, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-30 16:38:33.896   508   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-30 16:38:33.918   508   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-30 16:38:33.921   926  3024 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-30 16:38:33.921  3805  3952 W QCNEJ   : |CORE| network available: 101
,11-30 16:38:33.921   926  3024 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-30 16:38:33.922  3805  3952 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-30 16:38:33.923   926  3024 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-30 16:38:33.923  3805  3952 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-30 16:38:33.924  3805  3952 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
11-30 16:38:33.924   926   943 D Tethering: MasterInitialState.processMessage what=3
,11-30 16:38:33.940  5113  5137 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-30 16:38:33.941  5113  5137 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-30 16:38:33.941  5113  5137 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-30 16:38:33.941  5113  5137 E SarControlService: no key has been found,reset the power
11-30 16:38:33.941  5113  5150 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-30 16:38:33.941  5113  5150 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-30 16:38:33.941  5113  5150 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-30 16:38:33.942  5138  5138 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-30 16:38:33.942  5138  5138 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
,11-30 16:38:33.943  4997  4997 D NetworkChangeNotifierAutoDetect: Network connectivity changed, type is: 2
,11-30 16:38:33.944  5113  5150 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-30 16:38:33.944  5113  5150 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-30 16:38:33.944  5113  5150 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-30 16:38:33.945  5138  5138 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-30 16:38:33.945  5138  5138 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-30 16:38:33.947  3998  3998 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-30 16:38:33.950  5138  5152 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@bdad0b4 HexData = [00000000ec03000000000000ffffffff]
,11-30 16:38:33.950  5138  5152 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-30 16:38:33.950  5138  5152 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
,11-30 16:38:33.950  5138  5152 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@bdad0b4 HexData = [00000000ed03000000000000ffffffff]
11-30 16:38:33.950  5138  5152 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-30 16:38:33.950  5138  5152 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,11-30 16:38:33.951  5138  5138 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-30 16:38:33.951  5113  5124 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-30 16:38:33.952  3998  3998 D SystemUpdateService: onCreate
11-30 16:38:33.952  5138  5138 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-30 16:38:33.954  5113  5123 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-30 16:38:33.955   926  5942 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.16.174,2a00:1450:4001:814::200e
,11-30 16:38:33.957  3998  3998 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-30 16:38:33.968  3998  3998 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-30 16:38:33.973  3998  5480 I iu.UploadsManager: num queued entries: 0
,11-30 16:38:33.974  3998  5480 I iu.UploadsManager: num updated entries: 0
11-30 16:38:33.974  3998  5480 I iu.SyncManager: NEXT; no task
,11-30 16:38:33.978  3998  5955 I SystemUpdateService: active receiver: enabled
,11-30 16:38:33.979  3998  3998 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-30 16:38:33.981  3998  3998 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-30 16:38:33.983  5889  5889 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-30 16:38:33.987  5889  5889 D SprintDMHelper: simOperator: 
11-30 16:38:33.987  5889  5889 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-30 16:38:34.012  3998  5955 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-30 16:38:34.020   926  5942 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 30 Nov 2016 21:38:34 GMT], X-Android-Received-Millis=[1480541914019], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1480541913990]}
,11-30 16:38:34.020   926  3024 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-30 16:38:34.020   926  3024 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
,11-30 16:38:34.020   926  3024 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 16:38:34.021   926  3024 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-30 16:38:34.026  3998  5955 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-30 16:38:34.026  3998  5955 I SystemUpdateService: now status is 0 (complete)
11-30 16:38:34.026  3998  5955 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-30 16:38:34.026  3998  5955 I SystemUpdateService: file has been verified
11-30 16:38:34.027  3998  5955 I SystemUpdateService: OTA package size = 21989297
,11-30 16:38:34.033  3998  5955 I SystemUpdateService: showing system update notification
,11-30 16:38:34.042  3998  3998 D SystemUpdateService: onDestroy
,11-30 16:38:34.122  5086  5960 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-30 16:38:34.368   536   536 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-30 16:38:34.368   536   536 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-30 16:38:34.808  5706  5752 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Stop operation: Should start/stop everything
11-30 16:38:34.808  5706  5752 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-30 16:38:34.808  5706  5752 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-30 16:38:34.808  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-30 16:38:34.809  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-30 16:38:34.809  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-30 16:38:34.809  5706  5940 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-30 16:38:34.810  5706  5940 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
11-30 16:38:34.810  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-30 16:38:34.810  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-30 16:38:34.810  5706  5940 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-30 16:38:34.810  5706  5752 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-30 16:38:34.810  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-30 16:38:34.810  5706  5706 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-30 16:38:34.811  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:34.811  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-30 16:38:34.811  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-30 16:38:34.811  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:34.812  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:34.812  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:34.813  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:34.817  5706  5752 D BluetoothAdapter: STATE_ON
11-30 16:38:34.818  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-30 16:38:34.820  5706  5752 D BluetoothAdapter: STATE_ON
11-30 16:38:34.820  5706  5752 D BluetoothLeScanner: could not find callback wrapper
11-30 16:38:34.820  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-30 16:38:34.821  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:34.821  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:34.821  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:34.821  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
,11-30 16:38:34.821  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:34.823  5812  5831 D BtGatt.AdvertiseManager: message : 1
11-30 16:38:34.824  5812  5831 D BtGatt.AdvertiseManager: stop advertise for client 5
,11-30 16:38:34.834  5812  5829 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=5, status=0
,11-30 16:38:34.835  5812  5829 D BtGatt.GattService: Client app is not null!
11-30 16:38:34.836  5812  5859 D BtGatt.GattService: unregisterClient() - clientIf=5
11-30 16:38:34.837  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,11-30 16:38:34.837  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:34.838  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-30 16:38:34.838  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:34.838  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:34.838  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:34.839  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-30 16:38:34.839  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-30 16:38:34.840  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-30 16:38:34.842  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:34.844  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:34.844  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 16:38:34.845  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:34.845  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:34.845  5706  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-30 16:38:34.845  5706  5706 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-30 16:38:34.846  5706  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-30 16:38:34.846  5706  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-30 16:38:34.846  5706  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 16:38:34.846  5706  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 16:38:34.846  5706  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-30 16:38:34.847  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-30 16:38:34.847  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-30 16:38:34.847  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [ADVERTISING]
,11-30 16:38:34.847  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-30 16:38:34.847  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-30 16:38:34.847  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
,11-30 16:38:34.847  5706  5706 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 16:38:34.848  5706  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-30 16:38:34.848  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 16:38:34.851  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-30 16:38:34.851  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 16:38:34.851  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-30 16:38:34.854  5706  5752 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testCheckCurrentOperationStatus
,11-30 16:38:34.854  5706  5752 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-30 16:38:34.855  5706  5752 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-30 16:38:34.855  5706  5752 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-30 16:38:34.855  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-30 16:38:34.855  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-30 16:38:34.855  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-30 16:38:34.858  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,11-30 16:38:34.863  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
,11-30 16:38:34.863  5706  5752 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-30 16:38:34.863  5706  5752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-30 16:38:34.869  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:34.869  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-30 16:38:34.870  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-30 16:38:34.870  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,11-30 16:38:34.870  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 5
,11-30 16:38:34.874  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
11-30 16:38:34.882  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-30 16:38:34.883  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:34.883  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-30 16:38:34.884  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-30 16:38:34.884  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-30 16:38:34.887  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,11-30 16:38:34.887  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:34.889  5706  5752 D BluetoothAdapter: STATE_ON
11-30 16:38:34.892  5812  5858 D BtGatt.GattService: registerClient() - UUID=29a1e413-9b83-4e58-9f81-c984b15e0995
11-30 16:38:34.892  5812  5829 D BtGatt.GattService: onClientRegistered() - UUID=29a1e413-9b83-4e58-9f81-c984b15e0995, clientIf=5
11-30 16:38:34.893  5706  5717 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-30 16:38:34.895  5812  5848 D BtGatt.GattService: start scan with filters
,11-30 16:38:34.899  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-30 16:38:34.899  5812  5832 D BtGatt.ScanManager: handling starting scan
,11-30 16:38:34.899  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:34.899  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-30 16:38:34.900  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:34.900  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-30 16:38:34.901  5706  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 16:38:34.901  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 16:38:34.901  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
,11-30 16:38:34.901  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-30 16:38:34.901  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 16:38:34.901  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-30 16:38:34.901  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 16:38:34.901  5706  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-30 16:38:34.902  5812  5832 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@779d295
,11-30 16:38:34.902  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,11-30 16:38:34.903  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:34.906  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:34.906  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-30 16:38:34.906  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:34.906  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:34.906  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-30 16:38:34.909  5812  5829 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-30 16:38:34.909  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 16:38:34.909  5812  5832 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-30 16:38:34.910  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-30 16:38:34.910  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 16:38:34.910  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 16:38:34.910  5706  5706 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-30 16:38:34.916  5812  5829 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-30 16:38:34.916  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 16:38:34.917  5812  5832 D BtGatt.ScanManager: Starting BLE batch scan
11-30 16:38:34.917  5812  5832 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-30 16:38:34.921   926  3024 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-30 16:38:34.927  5812  5829 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-30 16:38:34.927  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-30 16:38:34.933  5812  5829 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-30 16:38:34.933  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-30 16:38:35.411  5706  5706 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-30 16:38:35.411  5706  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-30 16:38:35.412  5706  5706 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-30 16:38:37.909  5706  5752 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testExecuteStartOperation
,11-30 16:38:37.909  5706  5752 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 6
11-30 16:38:37.910  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 5 -> 6
11-30 16:38:37.910  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:37.910  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:37.911  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:37.911  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings:
11-30 16:38:37.911  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Manufacturer ID: 7413
11-30 16:38:37.911  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad length and type: 533
11-30 16:38:37.911  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Beacon ad extra information: 6
11-30 16:38:37.911  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertisement data type: DO_NOT_CARE
11-30 16:38:37.911  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise mode: 2
11-30 16:38:37.911  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Advertise TX power level: 3
11-30 16:38:37.911  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan mode: 2
11-30 16:38:37.911  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Scan report delay in milliseconds: 500
11-30 16:38:37.911  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer:     - Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:37.911  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 6
11-30 16:38:37.911  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: advertiserWasStarted false Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:37.911  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:37.912  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-30 16:38:37.912  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-30 16:38:37.912  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: scannerWasStarted true Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:37.913  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: stop scanner Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:37.913  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:37.917  5706  5752 D BluetoothAdapter: STATE_ON
11-30 16:38:37.918  5812  5858 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-30 16:38:37.920  5812  5832 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-30 16:38:37.920  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
,11-30 16:38:37.926  5706  5752 D BluetoothAdapter: STATE_ON
,11-30 16:38:37.930  5812  5824 D BtGatt.GattService: stopScan() - queue size =1
11-30 16:38:37.931  5812  5859 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-30 16:38:37.932  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-30 16:38:37.932  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:37.933  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-30 16:38:37.933  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:37.933  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-30 16:38:37.933  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:37.933  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:37.933  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-30 16:38:37.933  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-30 16:38:37.933  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-30 16:38:37.934  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-30 16:38:37.934  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:37.935  5706  5752 D BluetoothAdapter: STATE_ON
11-30 16:38:37.939  5812  5824 D BtGatt.GattService: registerClient() - UUID=b333d257-a858-4bf5-a190-18ca56d5a614
11-30 16:38:37.940  5812  5829 D BtGatt.GattService: onClientRegistered() - UUID=b333d257-a858-4bf5-a190-18ca56d5a614, clientIf=5
11-30 16:38:37.941  5706  5716 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-30 16:38:37.941  5812  5859 D BtGatt.GattService: start scan with filters
11-30 16:38:37.947  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-30 16:38:37.947  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:37.947  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-30 16:38:37.947  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:37.947  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: applySettings: start scanner started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:37.947  5706  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 16:38:37.947  5706  5752 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-30 16:38:37.947  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 16:38:37.948  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-30 16:38:37.948  5706  5752 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
11-30 16:38:37.948  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
11-30 16:38:37.948  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-30 16:38:37.948  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-30 16:38:37.948  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 16:38:37.948  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 16:38:37.949  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-30 16:38:37.950  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-30 16:38:37.950  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-30 16:38:37.950  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,11-30 16:38:37.950  5706  5752 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-30 16:38:37.950  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: true
11-30 16:38:37.951  5706  5706 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-30 16:38:37.951  5706  5969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
11-30 16:38:37.955  5858  5858 W Binder_4: type=1400 audit(0.0:123): avc: denied { ioctl } for path="socket:[33112]" dev="sockfs" ino=33112 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 16:38:37.955  5858  5858 W Binder_4: type=1400 audit(0.0:124): avc: denied { ioctl } for path="socket:[33112]" dev="sockfs" ino=33112 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-30 16:38:37.953  5812  5812 D BtGatt.ScanManager: awakened up at time 116980
11-30 16:38:37.953  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-30 16:38:37.954  5706  5752 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-30 16:38:37.955  5706  5969 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-30 16:38:37.958  5706  5969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
11-30 16:38:37.961  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser : Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:37.962  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:37.962  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:37.962  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser: Starting...
11-30 16:38:37.962  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: createAdvertiseDataToServiceData 
11-30 16:38:37.962  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service UUID: "b6a44ad1-d319-4b3a-815d-8b805a47fb51", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-30 16:38:37.962  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Service data (length is 7 bytes): 06 60 83 34 25 D7 C6
11-30 16:38:37.963  5706  5752 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.PeerAdvertisementFactory: createAdvertiseDataToServiceData: Created: AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 16:38:37.963  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: createAdvertiseData: created AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 16:38:37.963  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:37.963  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: w,as started = false
11-30 16:38:37.963  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData: advertiseData = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]
11-30 16:38:37.963  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseData finished: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:37.963  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start:  state = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:37.963  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Starting... adv data = AdvertiseData [mServiceUuids=[b6a44ad1-d319-4b3a-815d-8b805a47fb51], mManufacturerSpecificData={}, mServiceData={b6a44ad1-d319-4b3a-815d-8b805a47fb51=[6, 96, -125, 52, 37, -41, -58]}, mIncludeTxPowerLevel=false, mIncludeDeviceName=false]Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:37.964  5706  5752 D BluetoothAdapter: STATE_ON
11-30 16:38:37.965  5812  5829 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=8
11-30 16:38:37.965  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 16:38:37.965  5812  5829 D BtGatt.GattService: current time is 116993044846
11-30 16:38:37.966  5812  5829 D BtGatt.GattService: Batch record : [35, 97, 126, -92, 22, -56, 1, -128, -67, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -67, 15, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 86, -31, -99, 30, -52, -57, 1, 0, -93, 49, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 36, -115, 113, 6, -73, -88, 58, 61, -108, 126, 104, 3, 2, -29, 20, 62, -51, 19, 66, 28, 6, 8, 116, 105, 115, 53, 65, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 37, -47, 14, -113, 116, -46, 1, -128, -74, 1, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -71, 2, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, -75, 112, 8, 38, 113, -28, 1, -128, -94, 38, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 41, 111, -36, 20, -14, -81, 113, -83, -42, 97, 104, 3, 2, -25, 23, 62, 36, 57, 58, 0, 71, -122, -77, 84, 69, -12, 1, -128, -79, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -24, -5, 124, 62, -54, -40, 1, 0, -95, 13, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -25, 12, 29, 8, 4, 41, 19, -57, -12, 90, 104, 3, 1, -25, 23, -109, -64, 2, 52, 28, 6, 8, 116, 105, 110, 53, 50, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-30 16:38:37.968  5812  5823 D BtGatt.GattService: registerClient() - UUID=d0fb9b7b-b067-4c63-abc5-319dd3d573a7
11-30 16:38:37.969  5812  5829 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2,, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-30 16:38:37.970  5812  5829 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-30 16:38:37.970  5812  5829 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 36, -115, 113, 6, -73, -88, 58, 61, -108, 126, 104, 3, 2, -29, 20, 62, -51, 19, 66, 6, 8, 116, 105, 115, 53, 65, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-30 16:38:37.970  5812  5829 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-30 16:38:37.970  5812  5829 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-30 16:38:37.971  5812  5829 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 41, 111, -36, 20, -14, -81, 113, -83, -42, 97, 104, 3, 2, -25, 23, 62, 36, 57, 58]
11-30 16:38:37.971  5812  5829 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-30 16:38:37.971  5812  5829 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -25, 12, 29, 8, 4, 41, 19, -57, -12, 90, 104, 3, 1, -25, 23, -109, -64, 2, 52, 6, 8, 116, 105, 110, 53, 50, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-30 16:38:37.972  5812  5829 D BtGatt.GattService: onClientRegistered() - UUID=d0fb9b7b-b067-4c63-abc5-319dd3d573a7, clientIf=6
11-30 16:38:37.972  5706  5717 D BluetoothLeAdvertiser: onClientRegistered() - status=0 clientIf=6
11-30 16:38:37.975  5812  5831 D BtGatt.AdvertiseManager: message : 0
11-30 16:38:37.978  5812  5829 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-30 16:38:37.978  5812  5831 D BtGatt.AdvertiseManager: starting multi advertising
11-30 16:38:37.978  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 16:38:37.978  5812  5832 D BtGatt.ScanManager: stopping BLe Batch
11-30 16:38:37.984  5812  5829 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-30 16:38:37.984  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 16:38:37.984  5812  5832 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-30 16:38:37.993  5812  5829 D BtGatt.GattService: onAdvertiseInstanceEnabled() - clientIf=6, status=0
,11-30 16:38:37.996  5812  5829 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-30 16:38:37.996  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-30 16:38:37.998  5812  5832 D BtGatt.ScanManager: handling starting scan
,11-30 16:38:38.000  5812  5829 D BtGatt.GattService: onAdvertiseDataSet() - clientIf=6, status=0
,11-30 16:38:38.001  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: Started advertisment Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:38.001  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:38.001  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from NOT_STARTED to STARTING
,11-30 16:38:38.001  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: onIsAdvertiserStartedChanged default (no call to listener). Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:38.001  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:38.001  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start: return, state = STARTINGCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:38.001  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: start returned: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:38.001  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startAdvertiser started = true Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:38.001  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: advertiser is started. Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:38.001  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:38.001  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:38.001  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Already running
,11-30 16:38:38.002  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScannerAndAdvertiser: adv = true, disc = true
11-30 16:38:38.002  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-30 16:38:38.003  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-30 16:38:38.003  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:38.005  5812  5829 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-30 16:38:38.005  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 16:38:38.005  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:38.005  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:38.005  5812  5832 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-30 16:38:38.005  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:38.005  5706  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-30 16:38:38.005  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: onStartSuccess : Current thread: Thread[main,5,main], id: 1
11-30 16:38:38.005  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = STARTING, new = RUNNINGCurrent thread: Thread[main,5,main], id: 1
11-30 16:38:38.006  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from STARTING to RUNNING
11-30 16:38:38.006  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  true. Current thread: Thread[main,5,main], id: 1
11-30 16:38:38.006  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[main,5,main], id: 1
,11-30 16:38:38.006  5706  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-30 16:38:38.006  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 16:38:38.006  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING, ADVERTISING]
11-30 16:38:38.006  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-30 16:38:38.006  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 16:38:38.006  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [SCANNING, ADVERTISING]Current thread: Thread[main,5,main], id: 1
,11-30 16:38:38.006  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 16:38:38.009  5812  5829 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-30 16:38:38.014  5706  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [SCANNING, ADVERTISING] Current thread: Thread[main,5,main], id: 1
11-30 16:38:38.014  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 16:38:38.014  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 16:38:38.015  5812  5832 D BtGatt.ScanManager: Starting BLE batch scan
11-30 16:38:38.015  5812  5832 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-30 16:38:38.017  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
,11-30 16:38:38.017  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: true
11-30 16:38:38.017  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 16:38:38.017  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 16:38:38.017  5706  5706 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: true
,11-30 16:38:38.023  5812  5829 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,11-30 16:38:38.023  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-30 16:38:38.028  5812  5829 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
,11-30 16:38:38.028  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-30 16:38:38.029  5812  5832 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-30 16:38:38.033  5812  5829 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-30 16:38:38.033  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 16:38:38.034  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
,11-30 16:38:38.518  5706  5706 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: true
,11-30 16:38:38.519  5706  5706 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-30 16:38:38.519  5706  5706 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-30 16:38:39.370   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 16:38:39.687   926  3024 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 16:38:40.371   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 16:38:41.008  5706  5752 I io.jxcore.node.StartStopOperationHandlerTest: Starting test: testConstructor
,11-30 16:38:41.009  5706  5752 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-30 16:38:41.009  5706  5752 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-30 16:38:41.010  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
,11-30 16:38:41.010  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-30 16:38:41.010  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-30 16:38:41.010  5706  5969 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
,11-30 16:38:41.010  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
,11-30 16:38:41.010  5706  5969 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-30 16:38:41.011  5706  5752 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
11-30 16:38:41.011  5706  5969 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-30 16:38:41.011  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-30 16:38:41.011  5706  5706 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
,11-30 16:38:41.011  5706  5752 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6283b2a removed from the list
,11-30 16:38:41.011  5706  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-30 16:38:41.011  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-30 16:38:41.012  5706  5752 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-30 16:38:41.012  5706  5706 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-30 16:38:41.012  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:41.012  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-30 16:38:41.012  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-30 16:38:41.013  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:41.013  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:41.013  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:41.013  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,11-30 16:38:41.013  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:41.016  5706  5752 D BluetoothAdapter: STATE_ON
11-30 16:38:41.016  5812  5859 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-30 16:38:41.017  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-30 16:38:41.018  5812  5832 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-30 16:38:41.018  5706  5752 D BluetoothAdapter: STATE_ON
11-30 16:38:41.020  5812  5858 D BtGatt.GattService: stopScan() - queue size =1
11-30 16:38:41.025  5812  5812 D BtGatt.ScanManager: awakened up at time 120052
,11-30 16:38:41.025  5812  5823 D BtGatt.GattService: unregisterClient() - clientIf=5
11-30 16:38:41.029  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-30 16:38:41.029  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:41.030  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-30 16:38:41.030  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:41.030  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:41.030  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:41.030  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser: Stopping...
11-30 16:38:41.030  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:41.032  5812  5831 D BtGatt.AdvertiseManager: message : 1
11-30 16:38:41.032  5812  5831 D BtGatt.AdvertiseManager: stop advertise for client 6
,11-30 16:38:41.049  5812  5829 D BtGatt.GattService: onAdvertiseInstanceDisabled() - clientIf=6, status=0
,11-30 16:38:41.049  5812  5829 D BtGatt.GattService: Client app is not null!
,11-30 16:38:41.050  5812  5858 D BtGatt.GattService: unregisterClient() - clientIf=6
,11-30 16:38:41.050  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-30 16:38:41.051  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = RUNNING, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:41.051  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: State changed from RUNNING to NOT_STARTED
11-30 16:38:41.051  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: notifyAdvertiserStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:41.051  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:41.051  5706  5752 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:41.051  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-30 16:38:41.051  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-30 16:38:41.052  5706  5752 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-30 16:38:41.053  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:41.056  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-30 16:38:41.057  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 16:38:41.057  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:41.057  5706  5752 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-30 16:38:41.057  5706  5752 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@da42d1b removed from the list
11-30 16:38:41.057  5706  5752 D io.jxcore.node.ConnectivityMonitor: stop
11-30 16:38:41.057  5706  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-30 16:38:41.057  5706  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-30 16:38:41.057  5706  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-30 16:38:41.057  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 16:38:41.057  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-30 16:38:41.057  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING, ADVERTISING]
11-30 16:38:41.058  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 16:38:41.058  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING, ADVERTISING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-30 16:38:41.058  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 16:38:41.058  5706  5706 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsAdvertiserStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-30 16:38:41.058  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-30 16:38:41.058  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-30 16:38:41.058  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-30 16:38:41.058  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-30 16:38:41.058  5706  5706 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-30 16:38:41.058  5706  5706 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-30 16:38:41.058  5706  5752 I io.jxcore.node.StartStopOperationTest: Starting test: testIsTargetState
11-30 16:38:41.059  5706  5752 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-30 16:38:41.059  5706  5706 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING, ADVERTISING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-30 16:38:41.059  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-30 16:38:41.059  5706  5752 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-30 16:38:41.059  5706  5752 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-30 16:38:41.059  5706  5752 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-30 16:38:41.059  5706  5752 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-30 16:38:41.059  5706  5752 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING,, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-30 16:38:41.060  5706  5752 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStartOperation
11-30 16:38:41.061  5706  5752 I io.jxcore.node.StartStopOperationTest: Starting test: testGetShouldStartOrStopListeningToAdvertisementsOnly
11-30 16:38:41.062  5706  5752 I io.jxcore.node.StartStopOperationTest: Starting test: testIsStartOperation
11-30 16:38:41.063  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-30 16:38:41.063  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-30 16:38:41.063  5706  5706 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-30 16:38:41.063  5706  5752 I io.jxcore.node.StartStopOperationTest: Starting test: testToString
11-30 16:38:41.064  5706  5752 I io.jxcore.node.StartStopOperationTest: Starting test: testCreateStopOperation
11-30 16:38:41.065  5706  5752 I io.jxcore.node.StartStopOperationTest: Starting test: testSetOperationExecutedTime
11-30 16:38:41.066  5706  5752 I io.jxcore.node.StartStopOperationTest: Starting test: testGetOperationExecutedTime
11-30 16:38:41.066  5706  5752 I io.jxcore.node.StartStopOperationTest: Starting test: testGetCallback
11-30 16:38:41.073  5812  5829 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=9
11-30 16:38:41.073  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 16:38:41.074  5812  5829 D BtGatt.GattService: current time is 120101355810
11-30 16:38:41.074  5812  5829 D BtGatt.GattService: Batch record : [86, -31, -99, 30, -52, -57, 1, 0, -93, 60, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 36, -115, 113, 6, -73, -88, 58, 61, -105, 126, 104, 3, 2, -29, 20, 62, 49, -95, -10, 28, 6, 8, 116, 105, 115, 53, 65, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 71, -122, -77, 84, 69, -12, 1, -128, -79, 60, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 35, 97, 126, -92, 22, -56, 1, -128, -71, 38, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, -75, 112, 8, 38, 113, -28, 1, 0, -97, 48, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 41, 111, -36, 20, -14, -81, 113, -83, -39, 97, 104, 3, 2, -25, 23, 62, 75, -114, -113, 28, 6, 8, 116, 105, 115, 54, 50, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0, 81, 34, 97, 112, -14, -5, 1, -128, -69, 48, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 0, -46, -4, -117, 6, 105, -37, 1, -128, -70, 45, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 37, -47, 14, -113, 116, -46, 1, -128, -70, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, 116, -43, -111, -91, -20, -29, 1, -128, -65, 37, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, -106, -15, -31, -128, 20, -7, 1, 0, -96, 34, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, 25, 91, 104, 3, 2, -25, 21, 62, -116, 98, 63, 28, 6, 8, 116, 105, 115, 53, 69, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-30 16:38:41.074  5812  5829 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 36, -115, 113, 6, -73, -88, 58, 61, -105, 126, 104, 3, 2, -29, 20, 62, 49, -95, -10, 6, 8, 116, 105, 115, 53, 65, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-30 16:38:41.074  5812  5829 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-30 16:38:41.075  5812  5829 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-30 16:38:41.075  5812  5829 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 41, 111, -36, 20, -14, -81, 113, -83, -39, 97, 104, 3, 2, -25, 23, 62, 75, -114, -113, 6, 8, 116, 105, 115, 54, 50, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-30 16:38:41.075  5812  5829 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74]
11-30 16:38:41.075  5812  5829 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-30 16:38:41.075  5812  5829 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-30 16:38:41.076  5812  5829 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-30 16:38:41.076  5812  5829 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -33, -68, 76, -31, 14, 98, -25, 121, 25, 91, 104, 3, 2, -25, 21, 62, -116, 98, 63, 6, 8, 116, 105, 115, 53, 69, 17, 6, -90, -38, 55, -34, -63, -102, -4, -128, -108, 74, -40, -88, 2, 98, -62, -66, 2, 10, 0]
11-30 16:38:41.081  5812  5829 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-30 16:38:41.081  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 16:38:41.081  5812  5832 D BtGatt.ScanManager: stopping BLe Batch
11-30 16:38:41.087  5812  5829 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-30 16:38:41.087  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-30 16:38:41.088  5812  5832 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-30 16:38:41.093  5812  5829 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-30 16:38:41.093  5812  5829 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-30 16:38:41.372   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 16:38:41.560  5706  5706 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-30 16:38:41.874   926  3024 D ConnectivityService: handlePromptUnvalidated 101
,11-30 16:38:42.373   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 16:38:42.702   926  3024 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-30 16:38:43.006   926  3022 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 7, 9 -> obsolete
,11-30 16:38:43.071  5706  5752 I StreamCopyingThreadTest: Starting test: testCopyDataAndCloseConnection
,11-30 16:38:43.193  5706  5974 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 190, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-30 16:38:43.193  5706  5974 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-30 16:38:43.374   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 16:38:43.981  5706  5974 W !!      : call onHalfStreamCopied
,11-30 16:38:43.981  5706  5974 I testCopyDataAndClose: closing input stream
,11-30 16:38:44.374   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-30 16:38:44.761  5706  5974 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 190, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-30 16:38:44.761  5706  5974 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-30 16:38:44.761  5706  5974 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-30 16:38:44.761  5706  5974 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-30 16:38:44.761  5706  5974 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-30 16:38:44.761  5706  5974 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-30 16:38:44.761  5706  5974 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-30 16:38:44.761  5706  5974 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-30 16:38:44.761  5706  5974 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-30 16:38:44.761  5706  5974 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 190, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-30 16:38:44.761  5706  5974 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-30 16:38:44.900   926  3022 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 8, 9 -> obsolete
,11-30 16:38:48.508  5706  5752 I StreamCopyingThreadTest: Starting test: testCopyBigData
,11-30 16:38:48.605  5706  5975 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 193, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-30 16:38:48.605  5706  5975 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-30 16:38:49.375   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 16:38:50.284  5706  5975 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 193, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-30 16:38:50.284  5706  5975 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-30 16:38:50.284  5706  5975 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-30 16:38:50.284  5706  5975 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-30 16:38:50.284  5706  5975 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-30 16:38:50.284  5706  5975 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-30 16:38:50.284  5706  5975 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-30 16:38:50.284  5706  5975 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-30 16:38:50.284  5706  5975 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-30 16:38:50.284  5706  5975 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 193, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-30 16:38:50.284  5706  5975 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-30 16:38:50.376   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 16:38:51.377   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 16:38:52.379   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 16:38:53.380   536   536 I ServiceManager: Waiting for service AtCmdFwd...
,11-30 16:38:54.020  5706  5752 I StreamCopyingThreadTest: Starting test: testRunNotify
,11-30 16:38:54.023  5706  5976 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 195, name: My test thread name). Connection data: Peer properties: [null null].
11-30 16:38:54.023  5706  5976 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-30 16:38:54.023  5706  5976 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 195, thread name: My test thread name). Connection data: Peer properties: [null null].
11-30 16:38:54.023  5706  5976 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-30 16:38:54.024  5706  5976 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-30 16:38:54.024  5706  5976 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-30 16:38:54.024  5706  5976 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-30 16:38:54.024  5706  5976 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-30 16:38:54.024  5706  5976 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-30 16:38:54.024  5706  5976 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-30 16:38:54.024  5706  5976 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-30 16:38:54.025  5706  5976 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 195, name: My test thread name). Connection data: Peer properties: [null null].
11-30 16:38:54.025  5706  5976 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
11-30 16:38:54.026  5706  5752 I StreamCopyingThreadTest: Starting test: testSetBufferSize
,11-30 16:38:54.027  5706  5752 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
11-30 16:38:54.027  5706  5752 I StreamCopyingThreadTest: Starting test: testRunWithException
,11-30 16:38:54.030  5706  5977 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 199, name: My test thread name). Connection data: Peer properties: [null null].
11-30 16:38:54.030  5706  5977 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-30 16:38:54.030  5706  5977 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 199, thread name: My test thread name): Test exception.
11-30 16:38:54.030  5706  5977 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 199, name: My test thread name). Connection data: Peer properties: [null null].
11-30 16:38:54.030  5706  5977 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-30 16:38:54.031  5706  5977 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-30 16:38:54.031  5706  5977 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 199, name: My test thread name). Connection data: Peer properties: [null null].
11-30 16:38:54.031  5706  5977 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,11-30 16:38:54.035  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - DEBUG UnitTest_app: 'Running unit tests'
11-30 16:38:54.035  5706  5752 I jxcore-log: 
11-30 16:38:54.036  5706  5752 I jxcore-log: *Native tests were executed*
11-30 16:38:54.036  5706  5752 I jxcore-log: 
,11-30 16:38:54.036  5706  5752 I jxcore-log: Total number of executed tests:  81
11-30 16:38:54.036  5706  5752 I jxcore-log: 
11-30 16:38:54.036  5706  5752 I jxcore-log: Number of passed tests:  79
11-30 16:38:54.036  5706  5752 I jxcore-log: 
11-30 16:38:54.036  5706  5752 I jxcore-log: Number of failed tests:  0
11-30 16:38:54.036  5706  5752 I jxcore-log: 
,11-30 16:38:54.036  5706  5752 I jxcore-log: Number of ignored tests:  2
11-30 16:38:54.036  5706  5752 I jxcore-log: 
11-30 16:38:54.036  5706  5752 I jxcore-log: Total duration:  35379
11-30 16:38:54.036  5706  5752 I jxcore-log: 
11-30 16:38:54.038  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-30 16:38:54.038  5706  5752 I jxcore-log: 
,11-30 16:38:54.041  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-30 16:38:54.041  5706  5752 I jxcore-log: 
11-30 16:38:54.041  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-30 16:38:54.041  5706  5752 I jxcore-log: 
,11-30 16:38:54.042  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-30 16:38:54.042  5706  5752 I jxcore-log: 
11-30 16:38:54.042  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-30 16:38:54.042  5706  5752 I jxcore-log: 
11-30 16:38:54.043  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-30 16:38:54.043  5706  5752 I jxcore-log: 
11-30 16:38:54.044  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-30 16:38:54.044  5706  5752 I jxcore-log: 
11-30 16:38:54.044  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 16:38:54.044  5706  5752 I jxcore-log: 
11-30 16:38:54.045  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-30 16:38:54.045  5706  5752 I jxcore-log: 
11-30 16:38:54.045  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-30 16:38:54.045  5706  5752 I jxcore-log: 
11-30 16:38:54.045  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 16:38:54.045  5706  5752 I jxcore-log: 
,11-30 16:38:54.045  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-30 16:38:54.045  5706  5752 I jxcore-log: 
11-30 16:38:54.045  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-30 16:38:54.045  5706  5752 I jxcore-log: 
11-30 16:38:54.046  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 16:38:54.046  5706  5752 I jxcore-log: 
11-30 16:38:54.046  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-30 16:38:54.046  5706  5752 I jxcore-log: 
11-30 16:38:54.046  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 16:38:54.046  5706  5752 I jxcore-log: 
,11-30 16:38:54.046  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-30 16:38:54.046  5706  5752 I jxcore-log: 
11-30 16:38:54.047  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-30 16:38:54.047  5706  5752 I jxcore-log: 
11-30 16:38:54.047  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-30 16:38:54.047  5706  5752 I jxcore-log: 
11-30 16:38:54.047  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 16:38:54.047  5706  5752 I jxcore-log: 
,11-30 16:38:54.047  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-30 16:38:54.047  5706  5752 I jxcore-log: 
11-30 16:38:54.047  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-30 16:38:54.047  5706  5752 I jxcore-log: 
11-30 16:38:54.048  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-30 16:38:54.048  5706  5752 I jxcore-log: 
,11-30 16:38:54.048  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-30 16:38:54.048  5706  5752 I jxcore-log: 
11-30 16:38:54.048  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-30 16:38:54.048  5706  5752 I jxcore-log: 
11-30 16:38:54.048  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-30 16:38:54.048  5706  5752 I jxcore-log: 
,11-30 16:38:54.049  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}'
11-30 16:38:54.049  5706  5752 I jxcore-log: 
11-30 16:38:54.049  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - INFO thaliMobile: 'Filtered out networkChangedNonTCP (was in stopped state).'
11-30 16:38:54.049  5706  5752 I jxcore-log: 
11-30 16:38:54.049  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":true}'
11-30 16:38:54.049  5706  5752 I jxcore-log: 
11-30 16:38:54.049  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - INFO thaliMobile: 'Received state ({"discoveryActive":false,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-30 16:38:54.049  5706  5752 I jxcore-log: 
11-30 16:38:54.050  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 16:38:54.050  5706  5752 I jxcore-log: 
,11-30 16:38:54.051  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-30 16:38:54.051  5706  5752 I jxcore-log: 
11-30 16:38:54.051  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-30 16:38:54.051  5706  5752 I jxcore-log: 
11-30 16:38:54.051  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 16:38:54.051  5706  5752 I jxcore-log: 
11-30 16:38:54.052  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":true}'
11-30 16:38:54.052  5706  5752 I jxcore-log: 
,11-30 16:38:54.052  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":true}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-30 16:38:54.052  5706  5752 I jxcore-log: 
11-30 16:38:54.052  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 16:38:54.052  5706  5752 I jxcore-log: 
11-30 16:38:54.052  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-30 16:38:54.052  5706  5752 I jxcore-log: 
11-30 16:38:54.052  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-30 16:38:54.052  5706  5752 I jxcore-log: 
,11-30 16:38:54.057  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-30 16:38:54.057  5706  5752 I jxcore-log: 
11-30 16:38:54.057  5706  5752 I jxcore-log: 2016-11-30 21:38:54 - WARN testUtils: 'myNameCallback not set!'
11-30 16:38:54.057  5706  5752 I jxcore-log: 
,11-30 16:38:54.058  5706  5706 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
11-30 16:38:54.058  5706  5706 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-30 16:38:54.381   536   536 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-30 16:38:56.117  5706  5752 I jxcore-log: 2016-11-30 21:38:56 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-30 16:38:56.117  5706  5752 I jxcore-log: 
,11-30 16:38:56.119  5706  5752 I jxcore-log: 2016-11-30 21:38:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-30 16:38:56.119  5706  5752 I jxcore-log: 
,11-30 16:38:56.457  5706  5752 I jxcore-log: 2016-11-30 21:38:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-30 16:38:56.457  5706  5752 I jxcore-log: 
,11-30 16:38:56.468  5706  5752 I jxcore-log: 2016-11-30 21:38:56 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-30 16:38:56.468  5706  5752 I jxcore-log: 
,11-30 16:38:57.573  5706  5752 I jxcore-log: 2016-11-30 21:38:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-30 16:38:57.573  5706  5752 I jxcore-log: 
,11-30 16:38:57.736  5706  5752 I jxcore-log: 2016-11-30 21:38:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-30 16:38:57.736  5706  5752 I jxcore-log: 
,11-30 16:38:57.742  5706  5752 I jxcore-log: 2016-11-30 21:38:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-30 16:38:57.742  5706  5752 I jxcore-log: 
,11-30 16:38:57.754  5706  5752 I jxcore-log: 2016-11-30 21:38:57 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-30 16:38:57.754  5706  5752 I jxcore-log: 
,11-30 16:38:58.244  5706  5752 I jxcore-log: 2016-11-30 21:38:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-30 16:38:58.244  5706  5752 I jxcore-log: 
,11-30 16:38:58.288  5706  5752 I jxcore-log: 2016-11-30 21:38:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-30 16:38:58.288  5706  5752 I jxcore-log: 
,11-30 16:38:58.302  5706  5752 I jxcore-log: 2016-11-30 21:38:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-30 16:38:58.302  5706  5752 I jxcore-log: 
,11-30 16:38:58.306  5706  5752 I jxcore-log: 2016-11-30 21:38:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-30 16:38:58.306  5706  5752 I jxcore-log: 
,11-30 16:38:58.580  5706  5752 I jxcore-log: 2016-11-30 21:38:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-30 16:38:58.580  5706  5752 I jxcore-log: 
,11-30 16:38:58.708  5706  5752 I jxcore-log: 2016-11-30 21:38:58 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-30 16:38:58.708  5706  5752 I jxcore-log: 
,11-30 16:38:59.099  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-30 16:38:59.099  5706  5752 I jxcore-log: 
,11-30 16:38:59.107  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeAndroid.js'
11-30 16:38:59.107  5706  5752 I jxcore-log: 
,11-30 16:38:59.111  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-30 16:38:59.111  5706  5752 I jxcore-log: 
,11-30 16:38:59.115  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-30 16:38:59.115  5706  5752 I jxcore-log: 
,11-30 16:38:59.120  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeiOS.js'
11-30 16:38:59.120  5706  5752 I jxcore-log: 
,11-30 16:38:59.160  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-30 16:38:59.160  5706  5752 I jxcore-log: 
,11-30 16:38:59.168  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-30 16:38:59.168  5706  5752 I jxcore-log: 
,11-30 16:38:59.191  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-30 16:38:59.191  5706  5752 I jxcore-log: 
,11-30 16:38:59.230  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-30 16:38:59.230  5706  5752 I jxcore-log: 
,11-30 16:38:59.246  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-30 16:38:59.246  5706  5752 I jxcore-log: 
,11-30 16:38:59.253  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-30 16:38:59.253  5706  5752 I jxcore-log: 
,11-30 16:38:59.268  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-30 16:38:59.268  5706  5752 I jxcore-log: 
,11-30 16:38:59.283  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-30 16:38:59.283  5706  5752 I jxcore-log: 
,11-30 16:38:59.289  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-30 16:38:59.289  5706  5752 I jxcore-log: 
,11-30 16:38:59.295  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-30 16:38:59.295  5706  5752 I jxcore-log: 
,11-30 16:38:59.308  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-30 16:38:59.308  5706  5752 I jxcore-log: 
,11-30 16:38:59.326  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-30 16:38:59.326  5706  5752 I jxcore-log: 
,11-30 16:38:59.340  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-30 16:38:59.340  5706  5752 I jxcore-log: 
,11-30 16:38:59.351  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-30 16:38:59.351  5706  5752 I jxcore-log: 
,11-30 16:38:59.364  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-30 16:38:59.364  5706  5752 I jxcore-log: 
,11-30 16:38:59.374  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-30 16:38:59.374  5706  5752 I jxcore-log: 
,11-30 16:38:59.387  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-30 16:38:59.387  5706  5752 I jxcore-log: 
,11-30 16:38:59.397  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-30 16:38:59.397  5706  5752 I jxcore-log: 
,11-30 16:38:59.404  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-30 16:38:59.404  5706  5752 I jxcore-log: 
,11-30 16:38:59.425  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testUsn.js'
11-30 16:38:59.425  5706  5752 I jxcore-log: 
,11-30 16:38:59.431  5706  5752 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-30 16:38:59.432  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - INFO testUtils: 'BLE multiple advertisement supported'
11-30 16:38:59.432  5706  5752 I jxcore-log: 
,11-30 16:38:59.463  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-30 16:38:59.463  5706  5752 I jxcore-log: 
,11-30 16:38:59.506  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-30 16:38:59.506  5706  5752 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-30 16:38:59.506  5706  5752 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-30 16:38:59.506  5706  5752 I jxcore-log: emit@events.js:82:1
11-30 16:38:59.506  5706  5752 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-30 16:38:59.506  5706  5752 I jxcore-log: emit@events.js:82:1''
11-30 16:38:59.506  5706  5752 I jxcore-log: 
,11-30 16:38:59.507  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - DEBUG CoordinatedClient: 'test client failed'
11-30 16:38:59.507  5706  5752 I jxcore-log: 
11-30 16:38:59.510  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-30 16:38:59.510  5706  5752 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-30 16:38:59.510  5706  5752 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-30 16:38:59.510  5706  5752 I jxcore-log: emit@events.js:82:1
11-30 16:38:59.510  5706  5752 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-30 16:38:59.510  5706  5752 I jxcore-log: emit@events.js:82:1''
11-30 16:38:59.510  5706  5752 I jxcore-log: 
11-30 16:38:59.510  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-30 16:38:59.510  5706  5752 I jxcore-log: 
,11-30 16:38:59.511  5706  5752 I jxcore-log: 2016-11-30 21:38:59 - ERROR runTests: 'websocket error
11-30 16:38:59.511  5706  5752 I jxcore-log: Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-30 16:38:59.511  5706  5752 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-30 16:38:59.511  5706  5752 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-30 16:38:59.511  5706  5752 I jxcore-log: emit@events.js:82:1
11-30 16:38:59.511  5706  5752 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-30 16:38:59.511  5706  5752 I jxcore-log: emit@events.js:82:1'
11-30 16:38:59.511  5706  5752 I jxcore-log: 
,11-30 16:39:00.063  5978  5978 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-30 16:39:00.080  5978  5978 D AndroidRuntime: CheckJNI is OFF
,11-30 16:39:00.105  5978  5978 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-30 16:39:00.129  5978  5978 I Radio-JNI: register_android_hardware_Radio DONE
,11-30 16:39:00.143  5978  5978 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-30 16:39:00.148   926   939 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-30 16:39:00.148   926   939 I ActivityManager: Killing 5706:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-30 16:39:00.219   926  3915 D GraphicsStats: Buffer count: 2
,11-30 16:39:00.220   926  3023 D WifiService: Client connection lost with reason: 4
,11-30 16:39:00.221   926   937 I WindowState: WIN DEATH: Window{6b69bce u0 com.test.thalitest/com.test.thalitest.MainActivity}
,11-30 16:39:00.252   926   939 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-30 16:39:00.253   926   939 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,11-30 16:39:00.255   926   950 I art     : Starting a blocking GC Explicit
,11-30 16:39:00.255   926   939 E ActivityManager: Failure starting process com.test.thalitest
11-30 16:39:00.255   926   939 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-30 16:39:00.255   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-30 16:39:00.255   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-30 16:39:00.255   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-30 16:39:00.255   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-30 16:39:00.255   926   939 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-30 16:39:00.255   926   939 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-30 16:39:00.255   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-30 16:39:00.255   926   939 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-30 16:39:00.255   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-30 16:39:00.255   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-30 16:39:00.255   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-30 16:39:00.255   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-30 16:39:00.255   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-30 16:39:00.255   926   939 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-30 16:39:00.255   926   939 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 16:39:00.255   926   939 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-30 16:39:00.255   926   939 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-30 16:39:00.255   926   939 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-30 16:39:00.256   926   939 I ActivityManager:   Force finishing activity ActivityRecord{2c3222 u0 com.test.thalitest/.MainActivity t10}
,11-30 16:39:00.266   926   944 W WindowManager: Attempted to add application window with unknown token Token{263e4b3 ActivityRecord{2c3222 u0 com.test.thalitest/.MainActivity t10 f}}.  Aborting.
,11-30 16:39:00.266   926  3915 W ActivityManager: Spurious death for ProcessRecord{de2c3b3 0:com.test.thalitest/u0a77}, curProc for 5706: null
11-30 16:39:00.266   926   944 W WindowManager: Token{263e4b3 ActivityRecord{2c3222 u0 com.test.thalitest/.MainActivity t10 f}} already running, starting window not displayed. Unable to add window -- token Token{263e4b3 ActivityRecord{2c3222 u0 com.test.thalitest/.MainActivity t10 f}} is not valid; is your activity running?
11-30 16:39:00.266   926   944 W WindowManager: view not successfully added to wm, removing view
11-30 16:39:00.267   926   944 W WindowManager: Exception when adding starting window
11-30 16:39:00.267   926   944 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{a00d70 V.E...... R.....ID 0,0-0,0} not attached to window manager
11-30 16:39:00.267   926   944 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
11-30 16:39:00.267   926   944 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
11-30 16:39:00.267   926   944 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
11-30 16:39:00.267   926   944 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
11-30 16:39:00.267   926   944 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
11-30 16:39:00.267   926   944 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 16:39:00.267   926   944 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
11-30 16:39:00.267   926   944 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-30 16:39:00.267   926   944 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-30 16:39:00.339   926   950 I art     : Explicit concurrent mark sweep GC freed 69847(4MB) AllocSpace objects, 16(624KB) LOS objects, 33% free, 28MB/43MB, paused 1.504ms total 83.617ms
,11-30 16:39:00.359   926   950 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-30 16:39:00.362  5978  5978 I art     : System.exit called, status: 0
,11-30 16:39:00.362  5978  5978 I AndroidRuntime: VM exiting with result code 0.
,11-30 16:39:00.367   926   950 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-30 16:39:00.379   926   939 I ActivityManager: Exiting empty application process com.test.thalitest (null)
11-30 16:39:00.382  3713  3713 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-30 16:39:00.384  5812  5812 D BluetoothMapAppObserver: onReceive
,11-30 16:39:00.384  5812  5812 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
11-30 16:39:00.392  4166  4242 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-30 16:39:00.398   926  2988 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-30 16:39:00.403  3713  5989 I Keyboard.Facilitator.DecoderInitializer: run()
,11-30 16:39:00.418  3713  5989 I Decoder : createOrResetDecoder
,11-30 16:39:00.424  3448  5990 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-30 16:39:00.439  3835  3835 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-30 16:39:00.442   311   311 W kworker/2:2: type=1400 audit(0.0:125): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-30 16:39:00.452   311   311 W kworker/2:2: type=1400 audit(0.0:126): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-30 16:39:00.457  3619  3619 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-30 16:39:00.458  3619  3619 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-30 16:39:00.459   311   311 W kworker/2:2: type=1400 audit(0.0:127): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-30 16:39:00.475  3619  3619 I ConfigService: onCreate
,11-30 16:39:00.476  3998  5995 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,11-30 16:39:00.477  3998  5995 D AccountUtils: Clearing selected account for com.test.thalitest
,11-30 16:39:00.479   926   926 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-30 16:39:00.483   926   938 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
,11-30 16:39:00.483   926   938 E PackageManager: Failed to write settings, restoring backup
11-30 16:39:00.483   926   938 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
11-30 16:39:00.483   926   938 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
11-30 16:39:00.483   926   938 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
11-30 16:39:00.483   926   938 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
11-30 16:39:00.483   926   938 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
11-30 16:39:00.483   926   938 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 16:39:00.483   926   938 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
11-30 16:39:00.483   926   938 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-30 16:39:00.487   926   939 E DropBoxManagerService: Can't write: system_server_wtf
11-30 16:39:00.487   926   939 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
11-30 16:39:00.487   926   939 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-30 16:39:00.487   926   939 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-30 16:39:00.487   926   939 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-30 16:39:00.487   926   939 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-30 16:39:00.487   926   939 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-30 16:39:00.487   926   939 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-30 16:39:00.487   926   939 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12561)
11-30 16:39:00.487   926   939 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12374)
11-30 16:39:00.487   926   939 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12346)
11-30 16:39:00.487   926   939 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
11-30 16:39:00.487   926   939 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-30 16:39:00.487   926   939 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
11-30 16:39:00.487   926   939 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-30 16:39:00.487   926   939 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-30 16:39:00.487   926   939 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-30 16:39:00.487   926   939 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-30 16:39:00.487   926   939 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-30 16:39:00.487   926   939 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-30 16:39:00.487   926   939 E DropBoxManagerService: 	... 13 more
,11-30 16:39:00.491  3858  3965 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,11-30 16:39:00.492  3619  5996 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
11-30 16:39:00.492  3619  5996 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-30 16:39:00.492  3619  5996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-30 16:39:00.492  3619  5996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-30 16:39:00.492  3619  5996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-30 16:39:00.492  3619  5996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-30 16:39:00.492  3619  5996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-30 16:39:00.492  3619  5996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-30 16:39:00.492  3619  5996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-30 16:39:00.492  3619  5996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-30 16:39:00.492  3619  5996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-30 16:39:00.492  3619  5996 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-30 16:39:00.492  3619  5996 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-30 16:39:00.492  3619  5996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-30 16:39:00.492  3619  5996 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-30 16:39:00.492  3619  5996 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-30 16:39:00.492  3619  5996 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-30 16:39:00.492  3619  5996 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,11-30 16:39:00.493  3619  5996 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
11-30 16:39:00.493  3619  5996 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-30 16:39:00.493  3619  5996 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-30 16:39:00.493  3619  5996 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-30 16:39:00.493  3619  5996 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-30 16:39:00.493  3619  5996 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-30 16:39:00.493  3619  5996 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-30 16:39:00.493  3619  5996 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-30 16:39:00.493  3619  5996 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-30 16:39:00.493  3619  5996 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-30 16:39:00.493  3619  5996 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-30 16:39:00.493  3619  5996 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-30 16:39:00.493  3619  5996 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-30 16:39:00.493  3619  5996 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-30 16:39:00.493  3619  5996 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-30 16:39:00.493  3619  5996 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-30 16:39:00.493  3619  5996 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-30 16:39:00.493  3619  5996 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
,11-30 16:39:00.495  3619  5996 W SQLiteOpenHelper: Opened config.db in read-only mode
11-30 16:39:00.491  3448  3471 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mj76ED009D3) - 
,11-30 16:39:00.505   926   937 I ActivityManager: Start proc 5999:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
11-30 16:39:00.506  3858  3965 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
11-30 16:39:00.506  3858  3965 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3858
11-30 16:39:00.506  3858  3965 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
11-30 16:39:00.506  3858  3965 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
11-30 16:39:00.506  3858  3965 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
11-30 16:39:00.506  3858  3965 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
11-30 16:39:00.506  3858  3965 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
11-30 16:39:00.506  3858  3965 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
11-30 16:39:00.506  3858  3965 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
11-30 16:39:00.506  3858  3965 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
11-30 16:39:00.506  3858  3965 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
11-30 16:39:00.506  3858  3965 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
11-30 16:39:00.506  3858  3965 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-30 16:39:00.506  3858  3965 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-30 16:39:00.509   926  6006 E DropBoxManagerService: Can't write: system_app_crash
11-30 16:39:00.509   926  6006 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop115.tmp: open failed: EROFS (Read-only file system)
11-30 16:39:00.509   926  6006 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-30 16:39:00.509   926  6006 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-30 16:39:00.509   926  6006 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-30 16:39:00.509   926  6006 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-30 16:39:00.509   926  6006 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-30 16:39:00.509   926  6006 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-30 16:39:00.509   926  6006 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-30 16:39:00.509   926  6006 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-30 16:39:00.509   926  6006 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-30 16:39:00.509   926  6006 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-30 16:39:00.509   926  6006 E DropBoxManagerService: 	... 5 more
,11-30 16:39:00.510   926  3912 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,11-30 16:39:00.514  3858  3965 I Process : Sending signal. PID: 3858 SIG: 9
,11-30 16:39:00.521  3713  5989 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-30 16:39:00.538  3998  5995 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-30 16:39:00.562  3998  5995 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-30 16:39:00.562  3998  5995 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-30 16:39:00.562  3998  5995 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-30 16:39:00.562  3998  5995 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-30 16:39:00.562  3998  5995 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-30 16:39:00.562  3998  5995 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-30 16:39:00.562  3998  5995 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-30 16:39:00.562  3998  5995 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-30 16:39:00.562  3998  5995 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-30 16:39:00.562  3998  5995 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-30 16:39:00.562  3998  5995 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-30 16:39:00.562  3998  5995 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-30 16:39:00.562  3998  5995 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-30 16:39:00.562  3998  5995 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-30 16:39:00.562  3998  5995 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-30 16:39:00.562  3998  5995 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-30 16:39:00.562  3998  5995 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-30 16:39:00.562  3998  5995 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-30 16:39:00.562  3998  5995 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 16:39:00.562  3998  5995 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-30 16:39:00.562  3998  5995 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-30 16:39:00.562  3998  5995 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-30 16:39:00.562  3998  5995 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-30 16:39:00.562  3998  5995 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-30 16:39:00.562  3998  5995 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-30 16:39:00.562  3998  5995 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-30 16:39:00.562  3998  5995 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-30 16:39:00.562  3998  5995 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-30 16:39:00.562  3998  5995 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-30 16:39:00.562  3998  5995 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-30 16:39:00.562  3998  5995 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-30 16:39:00.562  3998  5995 E ,SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-30 16:39:00.562  3998  5995 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-30 16:39:00.562  3998  5995 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-30 16:39:00.562  3998  5995 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-30 16:39:00.562  3998  5995 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-30 16:39:00.562  3998  5995 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-30 16:39:00.562  3998  5995 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-30 16:39:00.562  3998  5995 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-30 16:39:00.562  3998  5995 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 16:39:00.562  3998  5995 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-30 16:39:00.562  3998  5995 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-30 16:39:00.563  3998  5995 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,11-30 16:39:00.579  3448  3471 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
11-30 16:39:00.579  3448  3471 E AndroidRuntime: Process: android.process.acore, PID: 3448
11-30 16:39:00.579  3448  3471 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
11-30 16:39:00.579  3448  3471 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-30 16:39:00.579  3448  3471 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
11-30 16:39:00.579  3448  3471 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
11-30 16:39:00.579  3448  3471 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
11-30 16:39:00.579  3448  3471 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
11-30 16:39:00.579  3448  3471 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
11-30 16:39:00.579  3448  3471 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
11-30 16:39:00.579  3448  3471 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
11-30 16:39:00.579  3448  3471 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
11-30 16:39:00.579  3448  3471 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-30 16:39:00.579  3448  3471 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-30 16:39:00.579  3448  3471 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-30 16:39:00.623   926  6015 E DropBoxManagerService: Can't write: system_app_crash
11-30 16:39:00.623   926  6015 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop116.tmp: open failed: EROFS (Read-only file system)
11-30 16:39:00.623   926  6015 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
11-30 16:39:00.623   926  6015 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
11-30 16:39:00.623   926  6015 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
11-30 16:39:00.623   926  6015 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
11-30 16:39:00.623   926  6015 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
11-30 16:39:00.623   926  6015 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12554)
11-30 16:39:00.623   926  6015 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
11-30 16:39:00.623   926  6015 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
11-30 16:39:00.623   926  6015 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
11-30 16:39:00.623   926  6015 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-30 16:39:00.623   926  6015 E DropBoxManagerService: 	... 5 more
,11-30 16:39:00.627   926   936 D GraphicsStats: Buffer count: 1
,11-30 16:39:00.627   926  3912 I WindowState: WIN DEATH: Window{144b32 u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
,11-30 16:39:00.628  3448  3471 I Process : Sending signal. PID: 3448 SIG: 9
,11-30 16:39:00.632   926  3915 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 3858) has died
,11-30 16:39:00.633   926  3915 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,11-30 16:39:00.677  3998  6017 I GMPM-SVC: App measurement is starting up
,11-30 16:39:00.681  3998  6017 E GMPM-SVC: AppMeasurementService not registered/enabled
,11-30 16:39:00.689  3998  6017 E GMPM-SVC: Uploading is not possible. App measurement disabled
,11-30 16:39:00.841   380   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
