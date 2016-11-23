#### Test 950476158569fbe_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
11-23 13:12:41.527  5537  5579 W GAv4    : AnalyticsService not registered in the app manifest. Hits might not be delivered reliably. See http://goo.gl/8Rd3yj for instructions.
,--------- beginning of system
11-23 13:12:41.740   928  3837 I ActivityManager: Killing 5241:org.codeaurora.ims/1001 (adj 15): empty #17
11-23 13:12:41.925  3715  4860 I Icing   : Indexing F030E08B5368E93E2F43DEEC3A6B244C622F15EE from com.google.android.googlequicksearchbox
11-23 13:12:42.000  5587  5587 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
11-23 13:12:42.004  5587  5587 D AndroidRuntime: CheckJNI is OFF
11-23 13:12:42.055  5587  5587 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
11-23 13:12:42.081  5587  5587 I Radio-JNI: register_android_hardware_Radio DONE
11-23 13:12:42.095  5587  5587 D AndroidRuntime: Calling main entry com.android.commands.am.Am
11-23 13:12:42.103   928   938 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
11-23 13:12:42.110  3715  4860 I Icing   : Indexing done F030E08B5368E93E2F43DEEC3A6B244C622F15EE
11-23 13:12:42.130   928   938 I ActivityManager: Start proc 5605:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
11-23 13:12:42.134  5587  5587 D AndroidRuntime: Shutting down VM
11-23 13:12:42.191  3715  3715 I ConfigFetchService: fetch service done; releasing wakelock
11-23 13:12:42.193  3715  3715 I ConfigFetchService: stopping self
,11-23 13:12:42.483   928  3841 I WindowManager: Screenshot max retries 4 of Token{5a03563 ActivityRecord{4399792 u0 com.test.thalitest/.MainActivity t10}} appWin=Window{8bceddb u0 Starting com.test.thalitest} drawState=2
,11-23 13:12:42.537  5537  5590 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm64
,11-23 13:12:42.570  5605  5605 I CordovaLog: Changing log level to DEBUG(3)
,11-23 13:12:42.570  5605  5605 I CordovaActivity: Apache Cordova native platform version 6.0.0 is starting
11-23 13:12:42.570  5605  5605 D CordovaActivity: CordovaActivity.onCreate()
,11-23 13:12:42.577  5605  5605 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
,11-23 13:12:42.591  5537  5590 V JNIHelp : Registering com/google/android/gms/org/conscrypt/NativeCrypto's 241 native methods...
,11-23 13:12:42.603  5605  5605 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
,11-23 13:12:42.621  5537  5590 I ProviderInstaller: Installed default security provider GmsCore_OpenSSL
,11-23 13:12:42.666  5605  5605 I LibraryLoader: Time to load native libraries: 59 ms (timestamps 160-219)
11-23 13:12:42.666  5605  5605 I LibraryLoader: Expected native library version number "",actual native library version number ""
,11-23 13:12:42.703  5605  5605 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {743b8be}
,11-23 13:12:42.704  5605  5605 I LibraryLoader: Expected native library version number "",actual native library version number ""
11-23 13:12:42.704  5605  5605 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
,11-23 13:12:42.707  5605  5605 I BrowserStartupController: Initializing chromium process, singleProcess=true
,11-23 13:12:42.708  5605  5605 E SysUtils: ApplicationContext is null in ApplicationStatus
,11-23 13:12:42.757  5605  5605 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
,11-23 13:12:42.771  5605  5605 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-23 13:12:42.771  5605  5605 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
11-23 13:12:42.771  5605  5605 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
11-23 13:12:42.771  5605  5605 I Adreno  : Build Date                       : 12/06/15
11-23 13:12:42.771  5605  5605 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
11-23 13:12:42.771  5605  5605 I Adreno  : Local Branch                     : mybranch17112971
11-23 13:12:42.771  5605  5605 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
11-23 13:12:42.771  5605  5605 I Adreno  : Remote Branch                    : NONE
11-23 13:12:42.771  5605  5605 I Adreno  : Reconstruct Branch               : NOTHING
,11-23 13:12:42.817   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@b8c778e:true
,11-23 13:12:42.850   402   402 W Binder_1: type=1400 audit(0.0:100): avc: denied { ioctl } for path="socket:[32926]" dev="sockfs" ino=32926 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 13:12:42.854   402   402 W Binder_1: type=1400 audit(0.0:101): avc: denied { ioctl } for path="socket:[32926]" dev="sockfs" ino=32926 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 13:12:42.865  5605  5605 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,11-23 13:12:42.874  5605  5605 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,11-23 13:12:42.879  5605  5605 D PluginManager: init()
,11-23 13:12:42.882  5605  5605 D CordovaWebViewImpl: >>> loadUrl(file:///android_asset/www/index.html)
,11-23 13:12:42.900  5605  5605 D CordovaActivity: Started the activity.
11-23 13:12:42.900  5605  5605 D CordovaActivity: Resumed the activity.
,11-23 13:12:42.900   405   405 W Binder_2: type=1400 audit(0.0:102): avc: denied { ioctl } for path="socket:[32161]" dev="sockfs" ino=32161 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,11-23 13:12:42.900   405   405 W Binder_2: type=1400 audit(0.0:103): avc: denied { ioctl } for path="socket:[32161]" dev="sockfs" ino=32161 ioctlcmd=7704 scontext=u:r:surfaceflinger:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
11-23 13:12:42.904  5605  5644 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,11-23 13:12:42.904  3835  3835 W Binder_8: type=1400 audit(0.0:104): avc: denied { ioctl } for path="socket:[32937]" dev="sockfs" ino=32937 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 13:12:42.909  5605  5605 D CordovaActivity: Paused the activity.
11-23 13:12:42.904  3835  3835 W Binder_8: type=1400 audit(0.0:105): avc: denied { ioctl } for path="socket:[32937]" dev="sockfs" ino=32937 ioctlcmd=7704 scontext=u:r:system_server:s0 tcontext=u:r:system_server:s0 tclass=unix_stream_socket permissive=0
,11-23 13:12:42.911  5605  5631 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,11-23 13:12:42.938  5605  5644 I OpenGLRenderer: Initialized EGL, version 1.4
,11-23 13:12:42.949  5605  5605 D CordovaActivity: Stopped the activity.
,11-23 13:12:43.013   928   946 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +528ms (total +893ms)
,11-23 13:12:43.032  5605  5605 D CordovaWebViewImpl: onPageDidNavigate(file:///android_asset/www/index.html)
,11-23 13:12:43.056  5605  5605 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5605
,11-23 13:12:43.160  5605  5605 D JsMessageQueue: Set native->JS mode to EvalBridgeMode
,11-23 13:12:43.423  5605  5647 D jxcore_app_log: JniHelper::setJavaVM(0xf503c000), pthread_self() = -591132368
,11-23 13:12:43.428  5605  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
11-23 13:12:43.428  5605  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
11-23 13:12:43.428  5605  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
11-23 13:12:43.428  5605  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
11-23 13:12:43.428  5605  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,11-23 13:12:43.428  5605  5647 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2824cd7 added. We now have 1 listener(s)
,11-23 13:12:43.431  5605  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,11-23 13:12:43.431  5605  5647 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-23 13:12:43.432  5605  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-23 13:12:43.432  5605  5647 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-23 13:12:43.434  5605  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
11-23 13:12:43.434  5605  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
11-23 13:12:43.434  5605  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
11-23 13:12:43.434  5605  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
11-23 13:12:43.434  5605  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
11-23 13:12:43.434  5605  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
11-23 13:12:43.434  5605  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
11-23 13:12:43.434  5605  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
11-23 13:12:43.434  5605  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
11-23 13:12:43.434  5605  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
11-23 13:12:43.434  5605  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
11-23 13:12:43.434  5605  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
11-23 13:12:43.434  5605  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
11-23 13:12:43.434  5605  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,11-23 13:12:43.434  5605  5647 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@28d5fe2 added. We now have 1 listener(s)
11-23 13:12:43.434  5605  5647 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 13:12:43.440   928  2966 D WifiService: New client listening to asynchronous messages
,11-23 13:12:43.440  5605  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 13:12:43.440  5605  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
11-23 13:12:43.440  5605  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-23 13:12:43.440  5605  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
11-23 13:12:43.440  5605  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
11-23 13:12:43.440  5605  5647 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
11-23 13:12:43.441  5605  5647 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onAdvertiseScanSettingsChanged: Current thread: Thread[JavaBridge,5,main], id: 55
11-23 13:12:43.442  5605  5647 I io.jxcore.node.LifeCycleMonitor: start: OK
,11-23 13:12:43.469  5605  5605 D CordovaWebViewImpl: onPageFinished(file:///android_asset/www/index.html)
,11-23 13:12:43.479  5605  5605 D SystemWebChromeClient: file:///android_asset/www/js/index.js: Line 36 : Uncaught TypeError: Cannot read property 'querySelector' of null
,11-23 13:12:43.479  5605  5605 I chromium: [INFO:CONSOLE(36)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (36)
,11-23 13:12:43.998  5605  5614 I art     : Background sticky concurrent mark sweep GC freed 77756(7MB) AllocSpace objects, 16(1076KB) LOS objects, 23% free, 25MB/32MB, paused 1.801ms total 268.597ms
,11-23 13:12:45.141  5605  5614 I art     : Background partial concurrent mark sweep GC freed 51050(5MB) AllocSpace objects, 2(1176KB) LOS objects, 36% free, 27MB/43MB, paused 964us total 232.771ms
,11-23 13:12:45.924  5605  5653 W jxcore-log: Initializing JXcore engine
,11-23 13:12:45.925  5605  5653 W jxcore-log: JXcore engine is ready
,11-23 13:12:45.947  5653  5653 W Thread-61: type=1400 audit(0.0:106): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12321 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,11-23 13:12:45.947  5653  5653 W Thread-61: type=1400 audit(0.0:107): avc: denied { ioctl } for path="socket:[15449]" dev="sockfs" ino=15449 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
11-23 13:12:45.947  5653  5653 W Thread-61: type=1400 audit(0.0:108): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=2866 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
11-23 13:12:45.947  5653  5653 W Thread-61: type=1400 audit(0.0:109): avc: denied { ioctl } for path="socket:[32132]" dev="sockfs" ino=32132 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:untrusted_app:s0:c512,c768 tclass=netlink_route_socket permissive=0
,11-23 13:12:45.956  5605  5653 W jxcore-log: Starting JXcore engine
,11-23 13:12:46.006  5605  5653 W jxcore-log: Platform android
11-23 13:12:46.006  5605  5653 W jxcore-log: 
,11-23 13:12:46.006  5605  5653 W jxcore-log: Process ARCH arm
11-23 13:12:46.006  5605  5653 W jxcore-log: 
,11-23 13:12:46.184  5605  5653 I jxcore-log: JXcore Cordova bridge is ready!
11-23 13:12:46.184  5605  5653 I jxcore-log: 
,11-23 13:12:46.184  5605  5653 W jxcore-log: JXcore engine is started
,11-23 13:12:46.197  5605  5647 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,11-23 13:12:46.204  5605  5605 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 41 : Application has the required permission.
,11-23 13:12:46.205  5605  5605 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,11-23 13:12:47.501  3563  3563 I ConfigService: onDestroy
,11-23 13:12:53.035   928  2965 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 13:12:55.466  4747  4792 D Finsky  : [180] AppStatesReplicator.handleContentSyncResponse: Completed 0 account content syncs with 0 successful.
,11-23 13:12:55.468  4747  4747 D Finsky  : [1] ContentSyncService$5.onFinished: Installation state replication succeeded.
,11-23 13:12:55.471   928  3837 I ActivityManager: Killing 5256:com.android.settings/1000 (adj 15): empty #17
,11-23 13:12:55.833  5605  5653 I jxcore-log: 2016-11-23 18:12:55 - DEBUG thaliMobileNativeWrapper: 'Method peerAvailabilityChanged registered to native'
11-23 13:12:55.833  5605  5653 I jxcore-log: 
,11-23 13:12:55.835  5605  5653 I jxcore-log: 2016-11-23 18:12:55 - DEBUG thaliMobileNativeWrapper: 'Method discoveryAdvertisingStateUpdateNonTCP registered to native'
11-23 13:12:55.835  5605  5653 I jxcore-log: 
,11-23 13:12:55.840  5605  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,11-23 13:12:55.840  5605  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 13:12:55.840  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 13:12:55.840  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 13:12:55.840  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 13:12:55.840  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 13:12:55.840  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 13:12:55.840  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 13:12:55.840  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 13:12:55.840  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 13:12:55.842  5605  5653 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 13:12:55.844  5605  5653 I jxcore-log: 2016-11-23 18:12:55 - DEBUG thaliMobileNativeWrapper: 'Method networkChanged registered to native'
11-23 13:12:55.844  5605  5653 I jxcore-log: 
,11-23 13:12:55.846  5605  5653 I jxcore-log: 2016-11-23 18:12:55 - DEBUG thaliMobileNativeWrapper: 'Method incomingConnectionToPortNumberFailed registered to native'
11-23 13:12:55.846  5605  5653 I jxcore-log: 
,11-23 13:12:56.090  5605  5653 I jxcore-log: 2016-11-23 18:12:56 - DEBUG UnitTest_app: 'Running unit tests'
11-23 13:12:56.090  5605  5653 I jxcore-log: 
,11-23 13:12:56.091  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-23 13:12:56.091  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2054e3f added. We now have 2 listener(s)
11-23 13:12:56.092  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-23 13:12:56.092  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 13:12:56.092  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 13:12:56.092  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 13:12:56.092  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd3b30c added. We now have 2 listener(s)
,11-23 13:12:56.092  5605  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 13:12:56.093  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 13:12:56.094  5605  5653 D executeNativeTests: Running unit tests
,11-23 13:12:56.137  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-23 13:12:56.137  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c28bcc5 added. We now have 3 listener(s)
11-23 13:12:56.137  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 13:12:56.137  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,11-23 13:12:56.137  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 13:12:56.138  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 13:12:56.138  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a added. We now have 3 listener(s)
11-23 13:12:56.138  5605  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 13:12:56.138  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 13:12:56.140  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-23 13:12:56.140  5605  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,11-23 13:12:56.140  5605  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 13:12:56.140  5605  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 13:12:56.141  5605  5653 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
11-23 13:12:56.141  5605  5653 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-23 13:12:56.141  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-23 13:12:56.141  5605  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 13:12:56.141  5605  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 13:12:56.141  5605  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 13:12:56.141  5605  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 13:12:56.141  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 13:12:56.141  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 13:12:56.142  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:12:56.142  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:12:56.142  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 13:12:56.142  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c28bcc5 removed from the list
11-23 13:12:56.142  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:12:56.142  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a removed from the list
,11-23 13:12:56.142  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
11-23 13:12:56.142  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:12:56.142  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:12:56.143  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:12:56.143  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:12:56.143  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:12:56.143  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 13:12:56.143  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 13:12:56.143  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:12:56.143  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
,11-23 13:12:56.144  5605  5653 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
11-23 13:12:56.144  5605  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 13:12:56.144  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 13:12:56.144  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 13:12:56.144  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 13:12:56.144  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:12:56.144  5605  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c28bcc5 not in the list
11-23 13:12:56.144  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:12:56.144  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:12:56.144  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
11-23 13:12:56.144  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:12:56.144  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:12:56.145  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:12:56.145  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:12:56.145  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:12:56.145  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 13:12:56.145  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 13:12:56.145  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:12:56.145  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:12:56.147  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-23 13:12:56.147  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-23 13:12:56.147  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-23 13:12:56.148  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-23 13:12:56.148  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-23 13:12:56.148  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-23 13:12:56.148  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-23 13:12:56.148  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
,11-23 13:12:56.148  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-23 13:12:56.148  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-23 13:12:56.148  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-23 13:12:56.148  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-23 13:12:56.148  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
11-23 13:12:56.148  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-23 13:12:56.148  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-23 13:12:56.148  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-23 13:12:56.148  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-23 13:12:56.148  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-23 13:12:56.148  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-23 13:12:56.148  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-23 13:12:56.148  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
,11-23 13:12:56.148  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-23 13:12:56.148  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-23 13:12:56.148  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-23 13:12:56.148  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
11-23 13:12:56.148  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-23 13:12:56.148  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-23 13:12:56.148  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-23 13:12:56.148  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-23 13:12:56.148  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-23 13:12:56.148  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-23 13:12:56.148  5605  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 13:12:56.148  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 13:12:56.148  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 13:12:56.149  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:12:56.149  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:12:56.149  5605  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c28bcc5 not in the list
11-23 13:12:56.149  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:12:56.149  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:12:56.149  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
11-23 13:12:56.149  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:12:56.149  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:12:56.149  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:12:56.149  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:12:56.149  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:12:56.149  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 13:12:56.149  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 13:12:56.150  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:12:56.150  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:12:56.150  5605  5653 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-23 13:12:56.151  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-23 13:12:56.151  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-23 13:12:56.159  5605  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 13:12:56.159  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 13:12:56.159  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 13:12:56.159  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 13:12:56.159  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 13:12:56.159  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 13:12:56.159  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 13:12:56.159  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 13:12:56.159  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 13:12:56.160  5605  5653 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 13:12:56.160  5605  5653 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 13:12:56.160  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 13:12:56.160  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 13:12:56.160  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 13:12:56.160  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 13:12:56.160  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 13:12:56.163  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 13:12:56.164  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 13:12:56.164  5605  5653 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 13:12:56.164  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 13:12:56.167  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 13:12:56.168  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:12:56.168  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 13:12:56.170  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 13:12:56.170  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 13:12:56.170  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-23 13:12:56.171  5605  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
,11-23 13:12:56.172  5605  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
11-23 13:12:56.172  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:12:56.172  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,11-23 13:12:56.173  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
,11-23 13:12:56.173  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 13:12:56.173  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 13:12:56.173  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:12:56.173  5605  5653 D BluetoothAdapter: STATE_ON
,11-23 13:12:56.176  4549  4767 D BtGatt.GattService: registerClient() - UUID=13080a35-e734-451e-9e97-7d7870768666
11-23 13:12:56.176  4549  4610 D BtGatt.GattService: onClientRegistered() - UUID=13080a35-e734-451e-9e97-7d7870768666, clientIf=5
,11-23 13:12:56.177  5605  5616 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-23 13:12:56.178  4549  4564 D BtGatt.GattService: start scan with filters
11-23 13:12:56.181  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 13:12:56.181  4549  4614 D BtGatt.ScanManager: handling starting scan
11-23 13:12:56.181  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:12:56.181  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 13:12:56.182  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:12:56.182  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
,11-23 13:12:56.182  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
,11-23 13:12:56.182  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 13:12:56.182  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 13:12:56.182  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 13:12:56.182  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
,11-23 13:12:56.182  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 13:12:56.182  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:12:56.182  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 13:12:56.183  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 13:12:56.183  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
,11-23 13:12:56.183  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:12:56.184  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:12:56.184  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:12:56.185  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 13:12:56.185  4549  4614 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b98b1
,11-23 13:12:56.186  5605  5653 I io.jxcore.node.ConnectionHelper: start: OK
11-23 13:12:56.187  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 13:12:56.187  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 13:12:56.187  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 13:12:56.188  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 13:12:56.188  5605  5605 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-23 13:12:56.192  4549  4610 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,11-23 13:12:56.192  4549  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:12:56.192  4549  4614 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-23 13:12:56.198  4549  4610 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,11-23 13:12:56.198  4549  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:12:56.198  4549  4614 D BtGatt.ScanManager: Starting BLE batch scan
11-23 13:12:56.199  4549  4614 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-23 13:12:56.208  4549  4610 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 13:12:56.208  4549  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 13:12:56.213  4549  4610 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 13:12:56.213  4549  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 13:12:56.344   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:12:56.690  5605  5605 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
,11-23 13:12:56.690  5605  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 13:12:56.690  5605  5605 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 13:12:57.345   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:12:58.170   928  2967 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 13:12:58.174   928  2967 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 56
,11-23 13:12:58.346   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:12:59.347   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:13:00.348   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:13:01.190  5605  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 13:13:01.190  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 13:13:01.191  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 13:13:01.191  5605  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-23 13:13:01.191  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,11-23 13:13:01.191  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:13:01.191  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
,11-23 13:13:01.191  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 13:13:01.191  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:01.191  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 13:13:01.192  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 13:13:01.193  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:01.193  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:01.193  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:13:01.193  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 13:13:01.193  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:01.194  5605  5653 D BluetoothAdapter: STATE_ON
11-23 13:13:01.195  4549  4564 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 13:13:01.195  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 13:13:01.197   928  2967 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-23 13:13:01.199  4549  4614 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 13:13:01.201  5605  5653 D BluetoothAdapter: STATE_ON
11-23 13:13:01.201   928  2967 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
11-23 13:13:01.202  4549  4767 D BtGatt.GattService: stopScan() - queue size =1
11-23 13:13:01.204  4549  4562 D BtGatt.GattService: unregisterClient() - clientIf=5
,11-23 13:13:01.204  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 13:13:01.204  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:01.204  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 13:13:01.205  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:01.205  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:01.205  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:01.205  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:01.205  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 13:13:01.206  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:01.206  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:01.206  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:01.206  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 13:13:01.206  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-23 13:13:01.210  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 13:13:01.210  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:01.210  4549  4549 D BtGatt.ScanManager: awakened up at time 88764
11-23 13:13:01.212  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:01.212  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 13:13:01.212  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:01.212  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:01.212  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:13:01.212  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
,11-23 13:13:01.212  5605  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 13:13:01.212  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 13:13:01.212  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 13:13:01.212  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:13:01.212  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 13:13:01.212  5605  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c28bcc5 not in the list
11-23 13:13:01.212  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:01.212  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 13:13:01.212  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:13:01.212  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
11-23 13:13:01.212  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 13:13:01.213  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 13:13:01.213  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 13:13:01.213  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 13:13:01.213  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
,11-23 13:13:01.213  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 13:13:01.213  5605  5605 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 13:13:01.213  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 13:13:01.213  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-23 13:13:01.215  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 13:13:01.215  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 13:13:01.216  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-23 13:13:01.242  4549  4610 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
11-23 13:13:01.242  4549  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:13:01.242  4549  4610 D BtGatt.GattService: current time is 88796530318
,11-23 13:13:01.243  4549  4610 D BtGatt.GattService: Batch record : [116, -43, -111, -91, -20, -29, 1, -128, -69, 50, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91, 81, 34, 97, 112, -14, -5, 1, -128, -68, 46, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, -46, -4, -117, 6, 105, -37, 1, -128, -74, 85, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 35, 97, 126, -92, 22, -56, 1, -128, -72, 44, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 71, -122, -77, 84, 69, -12, 1, -128, -80, 78, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, 37, -47, 14, -113, 116, -46, 1, -128, -74, 71, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -104, 11, -30, 21, 88, -39, 1, -128, -100, 70, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -102, -63, 5, 75, -127, -125, 45, -98, 105, -12, 94, 3, 1, -25, 20, -105, -7, -94, -88, 0]
,11-23 13:13:01.244  4549  4610 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-23 13:13:01.245  4549  4610 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-23 13:13:01.245  4549  4610 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-23 13:13:01.246  4549  4610 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-23 13:13:01.246  4549  4610 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-23 13:13:01.246  4549  4610 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-23 13:13:01.246  4549  4610 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, -102, -63, 5, 75, -127, -125, 45, -98, 105, -12, 94, 3, 1, -25, 20, -105, -7, -94, -88]
,11-23 13:13:01.253  4549  4610 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 13:13:01.253  4549  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:13:01.253  4549  4614 D BtGatt.ScanManager: stopping BLe Batch
,11-23 13:13:01.258  4549  4610 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-23 13:13:01.258  4549  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:13:01.258  4549  4614 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 13:13:01.263  4549  4610 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 13:13:01.263  4549  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 13:13:01.349   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 13:13:01.717  5605  5605 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 13:13:06.215  5605  5653 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,11-23 13:13:06.220  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-23 13:13:06.221  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-23 13:13:06.235  5605  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 13:13:06.235  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 13:13:06.235  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 13:13:06.235  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 13:13:06.235  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 13:13:06.235  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 13:13:06.235  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 13:13:06.235  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 13:13:06.235  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 13:13:06.240  5605  5653 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-23 13:13:06.240  5605  5653 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 13:13:06.240  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 13:13:06.241  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
,11-23 13:13:06.241  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 13:13:06.241  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-23 13:13:06.241  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 13:13:06.245  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 13:13:06.247  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 13:13:06.247  5605  5653 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 13:13:06.248  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,11-23 13:13:06.249  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 13:13:06.256  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:13:06.256  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,11-23 13:13:06.258  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-23 13:13:06.259  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 13:13:06.259  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 13:13:06.262  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:13:06.262  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 13:13:06.262  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 13:13:06.262  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 13:13:06.262  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 13:13:06.262  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:13:06.263  5605  5653 D BluetoothAdapter: STATE_ON
11-23 13:13:06.265  4549  4562 D BtGatt.GattService: registerClient() - UUID=911101d5-2275-47ea-aa69-8c6139ab4484
11-23 13:13:06.266  4549  4610 D BtGatt.GattService: onClientRegistered() - UUID=911101d5-2275-47ea-aa69-8c6139ab4484, clientIf=5
,11-23 13:13:06.266  5605  5617 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,11-23 13:13:06.267  4549  4756 D BtGatt.GattService: start scan with filters
,11-23 13:13:06.271  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
,11-23 13:13:06.271  4549  4614 D BtGatt.ScanManager: handling starting scan
11-23 13:13:06.271  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.271  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 13:13:06.271  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:13:06.271  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 13:13:06.272  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 13:13:06.272  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
,11-23 13:13:06.272  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 13:13:06.272  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 13:13:06.272  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 13:13:06.272  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
,11-23 13:13:06.272  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 13:13:06.272  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 13:13:06.273  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 13:13:06.273  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:13:06.277  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.277  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,11-23 13:13:06.277  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.277  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.277  5605  5653 I io.jxcore.node.ConnectionHelper: start: OK
11-23 13:13:06.277  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-23 13:13:06.279  4549  4610 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 13:13:06.279  4549  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:13:06.279  4549  4614 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,11-23 13:13:06.281  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 13:13:06.281  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 13:13:06.281  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-23 13:13:06.281  5605  5605 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 13:13:06.281  5605  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 13:13:06.282  5605  5653 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-23 13:13:06.282  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 13:13:06.282  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-23 13:13:06.282  5605  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 13:13:06.282  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-23 13:13:06.282  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:13:06.282  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 13:13:06.282  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-23 13:13:06.282  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.282  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 13:13:06.282  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 13:13:06.282  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.282  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:13:06.282  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.282  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 13:13:06.282  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.283  5605  5653 D BluetoothAdapter: STATE_ON
11-23 13:13:06.283  4549  4767 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
,11-23 13:13:06.284  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 13:13:06.285  4549  4610 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 13:13:06.285  5605  5653 D BluetoothAdapter: STATE_ON
11-23 13:13:06.285  4549  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:13:06.286  4549  4614 D BtGatt.ScanManager: Starting BLE batch scan
11-23 13:13:06.286  4549  4614 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,11-23 13:13:06.286  4549  4562 D BtGatt.GattService: stopScan() - queue size =1
11-23 13:13:06.287  4549  4767 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 13:13:06.287  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 13:13:06.288  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.288  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 13:13:06.288  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.288  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.288  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:13:06.288  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.288  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 13:13:06.288  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.288  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.288  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.288  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 13:13:06.288  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 13:13:06.289  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-23 13:13:06.289  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.291  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.291  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 13:13:06.291  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:13:06.292  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:13:06.292  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:13:06.292  5605  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 13:13:06.292  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 13:13:06.292  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 13:13:06.292  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:13:06.292  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 13:13:06.292  5605  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c28bcc5 not in the list
11-23 13:13:06.292  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:06.292  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 13:13:06.292  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:13:06.292  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 13:13:06.292  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
11-23 13:13:06.292  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 13:13:06.292  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 13:13:06.292  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 13:13:06.292  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 13:13:06.292  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 13:13:06.292  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 13:13:06.293  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.293  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.294  5605  5605 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 13:13:06.294  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 13:13:06.296  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.296  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.296  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.296  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 13:13:06.297  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 13:13:06.297  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 13:13:06.297  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 13:13:06.298  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 13:13:06.298  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 13:13:06.298  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:06.298  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
,11-23 13:13:06.298  4549  4610 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 13:13:06.298  4549  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:13:06.298  5605  5653 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
11-23 13:13:06.300  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 13:13:06.300  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-23 13:13:06.304  4549  4610 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 13:13:06.304  4549  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:13:06.305  4549  4614 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 13:13:06.307  5605  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 13:13:06.307  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 13:13:06.307  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 13:13:06.307  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 13:13:06.307  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 13:13:06.307  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 13:13:06.307  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 13:13:06.307  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 13:13:06.307  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 13:13:06.308  5605  5653 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 13:13:06.308  5605  5653 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 13:13:06.309  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 13:13:06.309  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 13:13:06.309  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 13:13:06.309  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 13:13:06.309  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 13:13:06.311  4549  4610 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 13:13:06.311  4549  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:13:06.311  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 13:13:06.311  4549  4610 E BtGatt.ContextMap: Context not found for ID 5
11-23 13:13:06.312  5605  5653 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 13:13:06.312  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 13:13:06.312  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 13:13:06.315  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 13:13:06.316  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.317  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 13:13:06.317  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 13:13:06.317  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 13:13:06.318  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 13:13:06.318  4549  4610 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 13:13:06.318  4549  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:13:06.318  4549  4614 D BtGatt.ScanManager: stopping BLe Batch
11-23 13:13:06.323  4549  4610 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 13:13:06.323  4549  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:13:06.323  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.323  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 13:13:06.323  4549  4614 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 13:13:06.323  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 13:13:06.323  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 13:13:06.323  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 13:13:06.323  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.324  5605  5653 D BluetoothAdapter: STATE_ON
11-23 13:13:06.327  4549  4562 D BtGatt.GattService: registerClient() - UUID=3d4519dc-1d27-4745-915d-531cc3b5b2af
11-23 13:13:06.327  4549  4610 D BtGatt.GattService: onClientRegistered() - UUID=3d4519dc-1d27-4745-915d-531cc3b5b2af, clientIf=5
11-23 13:13:06.328  5605  5616 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 13:13:06.328  4549  4610 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 13:13:06.328  4549  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:13:06.328  4549  4564 D BtGatt.GattService: start scan with filters
11-23 13:13:06.331  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 13:13:06.331  4549  4614 D BtGatt.ScanManager: handling starting scan
11-23 13:13:06.331  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.331  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 13:13:06.331  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.331  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 13:13:06.331  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 13:13:06.331  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 13:13:06.331  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 13:13:06.331  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 13:13:06.332  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 13:13:06.332  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 13:13:06.332  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 13:13:06.332  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 13:13:06.332  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 13:13:06.332  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:13:06.336  4549  4610 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 13:13:06.336  4549  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:13:06.337  4549  4614 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 13:13:06.337  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.337  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 13:13:06.337  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.337  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:06.337  5605  5653 I io.jxcore.node.ConnectionHelper: start: OK
11-23 13:13:06.337  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 13:13:06.339  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 13:13:06.339  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 13:13:06.339  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 13:13:06.339  5605  5605 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 13:13:06.341  4549  4610 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 13:13:06.341  4549  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:13:06.341  4549  4614 D BtGatt.ScanManager: Starting BLE batch scan
11-23 13:13:06.342  4549  4614 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 13:13:06.349  4549  4610 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 13:13:06.350  4549  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:13:06.354  4549  4610 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 13:13:06.354  4549  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 13:13:06.841  5605  5605 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: true, is advertising: false
11-23 13:13:06.841  5605  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,11-23 13:13:06.841  5605  5605 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 13:13:07.251   928  2967 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 13:13:07.254   928  2967 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 55
,11-23 13:13:10.278   928  2967 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 13:13:10.287   928  2967 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 100] to 60
,11-23 13:13:11.337  5605  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 13:13:11.338  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
,11-23 13:13:11.338  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,11-23 13:13:11.338  5605  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,11-23 13:13:11.338  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
11-23 13:13:11.338  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 13:13:11.339  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 13:13:11.339  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
,11-23 13:13:11.339  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:11.339  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 13:13:11.340  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
,11-23 13:13:11.341  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:11.341  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:13:11.341  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:11.341  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 13:13:11.342  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:13:11.346  5605  5653 D BluetoothAdapter: STATE_ON
,11-23 13:13:11.347  4549  4564 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 13:13:11.348  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 13:13:11.349  4549  4614 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 13:13:11.349  5605  5653 D BluetoothAdapter: STATE_ON
11-23 13:13:11.351  4549  4767 D BtGatt.GattService: stopScan() - queue size =1
11-23 13:13:11.354  4549  4562 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 13:13:11.356  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,11-23 13:13:11.356  4549  4549 D BtGatt.ScanManager: awakened up at time 98909
11-23 13:13:11.356  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:11.356  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 13:13:11.356  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:11.357  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:11.357  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:11.357  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:13:11.357  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 13:13:11.357  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:11.357  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:11.357  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:11.358  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 13:13:11.358  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,11-23 13:13:11.359   928  3876 I ActivityManager: Killing 5000:com.google.android.apps.maps/u0a58 (adj 15): empty #17
,11-23 13:13:11.388  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-23 13:13:11.388  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:13:11.389  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:11.389  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,11-23 13:13:11.389  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:11.389  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:13:11.389  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 13:13:11.390  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 13:13:11.390  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 13:13:11.390  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 13:13:11.390  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
,11-23 13:13:11.390  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 13:13:11.390  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 13:13:11.390  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 13:13:11.390  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 13:13:11.390  5605  5605 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 13:13:11.390  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 13:13:11.390  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
,11-23 13:13:11.392  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 13:13:11.392  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 13:13:11.392  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
,11-23 13:13:11.405  4549  4610 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=7
,11-23 13:13:11.405  4549  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:13:11.405  4549  4610 D BtGatt.GattService: current time is 98959028700
11-23 13:13:11.405  4549  4610 D BtGatt.GattService: Batch record : [37, -47, 14, -113, 116, -46, 1, -128, -74, 55, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113, -46, -4, -117, 6, 105, -37, 1, -128, -69, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6, 81, 34, 97, 112, -14, -5, 1, -128, -68, 49, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112, 71, -122, -77, 84, 69, -12, 1, -128, -80, 81, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84, -80, -54, -100, -120, -128, -10, 1, -128, -101, 84, 0, 31, 2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 116, 43, -120, 27, -33, -52, -88, -28, -70, -16, 94, 3, 1, -29, 24, 62, -117, 66, -78, 0, 35, 97, 126, -92, 22, -56, 1, -128, -71, 47, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92, 116, -43, -111, -91, -20, -29, 1, -128, -67, 54, 0, 30, 2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 25, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
11-23 13:13:11.405  4549  4610 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -47, 37, -113, 14, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 37, -47, 14, -113, 116, -46, -74, 37, -47, 14, -113]
11-23 13:13:11.406  4549  4610 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -4, -46, 6, -117, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, -46, -4, -117, 6, 105, -37, -74, -46, -4, -117, 6]
11-23 13:13:11.406  4549  4610 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 34, 81, 112, 97, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 81, 34, 97, 112, -14, -5, -74, 81, 34, 97, 112]
11-23 13:13:11.406  4549  4610 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -122, 71, 84, -77, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 71, -122, -77, 84, 69, -12, -74, 71, -122, -77, 84]
11-23 13:13:11.406  4549  4610 D BtGatt.GattService: ScanRecord : [2, 1, 6, 3, 2, 4, 24, 23, -1, -7, 0, 1, 116, 43, -120, 27, -33, -52, -88, -28, -70, -16, 94, 3, 1, -29, 24, 62, -117, 66, -78]
,11-23 13:13:11.406  4549  4610 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, 97, 35, -92, 126, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 35, 97, 126, -92, 22, -56, -74, 35, 97, 126, -92]
11-23 13:13:11.406  4549  4610 D BtGatt.GattService: ScanRecord : [2, 1, 6, 26, -1, 76, 0, 2, 21, -71, 64, 127, 48, -11, -8, 70, 110, -81, -7, 37, 85, 107, 87, -2, 109, -43, 116, -91, -111, -74, 9, 9, 101, 115, 116, 105, 109, 111, 116, 101, 14, 22, 10, 24, 116, -43, -111, -91, -20, -29, -74, 116, -43, -111, -91]
,11-23 13:13:11.411  4549  4610 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 13:13:11.411  4549  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:13:11.412  4549  4614 D BtGatt.ScanManager: stopping BLe Batch
,11-23 13:13:11.417  4549  4610 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-23 13:13:11.417  4549  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:13:11.418  4549  4614 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 13:13:11.422  4549  4610 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,11-23 13:13:11.423  4549  4610 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 13:13:11.891  5605  5605 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 13:13:11.891  5605  5605 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 13:13:11.892  5605  5605 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
,11-23 13:13:14.257   928  5371 D NetlinkSocketObserver: NeighborEvent{elapsedMs=101810, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,11-23 13:13:16.390  5605  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 13:13:16.391  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 13:13:16.391  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-23 13:13:16.391  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 13:13:16.391  5605  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 13:13:16.392  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,11-23 13:13:16.392  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:13:16.392  5605  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c28bcc5 not in the list
11-23 13:13:16.392  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:16.392  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
,11-23 13:13:16.392  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
11-23 13:13:16.393  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 13:13:16.395  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.395  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:13:16.398  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:13:16.398  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.399  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.399  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 13:13:16.399  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 13:13:16.399  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 13:13:16.399  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:13:16.401  5605  5653 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
11-23 13:13:16.402  5605  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 13:13:16.403  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 13:13:16.403  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-23 13:13:16.403  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:13:16.403  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:13:16.404  5605  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c28bcc5 not in the list
11-23 13:13:16.404  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:16.404  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:13:16.404  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 13:13:16.404  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.405  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.408  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.409  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.409  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.409  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 13:13:16.409  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 13:13:16.410  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 13:13:16.410  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
,11-23 13:13:16.411  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-23 13:13:16.412  5605  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 13:13:16.412  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 13:13:16.412  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 13:13:16.412  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,11-23 13:13:16.412  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:13:16.412  5605  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c28bcc5 not in the list
11-23 13:13:16.412  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:16.412  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:13:16.412  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
11-23 13:13:16.413  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:13:16.413  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.415  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.415  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:13:16.415  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.415  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 13:13:16.415  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 13:13:16.415  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:16.415  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
,11-23 13:13:16.416  5605  5653 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
,11-23 13:13:16.417  5605  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 13:13:16.417  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 13:13:16.417  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-23 13:13:16.417  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:13:16.417  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:13:16.417  5605  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c28bcc5 not in the list
11-23 13:13:16.417  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 13:13:16.417  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:13:16.417  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
11-23 13:13:16.417  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.418  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:13:16.420  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.420  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.420  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.420  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-23 13:13:16.420  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 13:13:16.420  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 13:13:16.420  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:13:16.421  5605  5653 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
11-23 13:13:16.421  5605  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 13:13:16.422  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 13:13:16.422  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 13:13:16.422  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:13:16.422  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:13:16.422  5605  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c28bcc5 not in the list
11-23 13:13:16.422  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:16.422  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:13:16.422  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
11-23 13:13:16.422  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.422  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.424  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.424  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.424  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.424  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 13:13:16.424  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 13:13:16.424  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:16.425  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
,11-23 13:13:16.425  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-23 13:13:16.426  5605  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 13:13:16.426  5605  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 13:13:16.426  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
11-23 13:13:16.426  5605  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 13:13:16.426  5605  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 13:13:16.426  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
11-23 13:13:16.426  5605  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 13:13:16.426  5605  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
11-23 13:13:16.427  5605  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 13:13:16.427  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 13:13:16.427  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 13:13:16.427  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:13:16.427  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 13:13:16.427  5605  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c28bcc5 not in the list
11-23 13:13:16.427  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:16.427  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:13:16.427  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
11-23 13:13:16.428  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.428  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:13:16.430  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.430  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.430  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.430  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-23 13:13:16.430  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 13:13:16.430  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:16.430  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:13:16.431  5605  5653 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 13:13:16.431  5605  5653 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
11-23 13:13:16.431  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
11-23 13:13:16.435  5605  5653 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 13:13:16.435  5605  5653 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
11-23 13:13:16.435  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
11-23 13:13:16.435  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
11-23 13:13:16.435  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
11-23 13:13:16.435  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
11-23 13:13:16.435  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
11-23 13:13:16.435  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
11-23 13:13:16.435  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
11-23 13:13:16.435  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
11-23 13:13:16.436  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
11-23 13:13:16.436  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
11-23 13:13:16.436  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
11-23 13:13:16.436  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
,11-23 13:13:16.436  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
11-23 13:13:16.436  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
11-23 13:13:16.436  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
11-23 13:13:16.436  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
11-23 13:13:16.436  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
11-23 13:13:16.436  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
11-23 13:13:16.436  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
11-23 13:13:16.436  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
11-23 13:13:16.436  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
11-23 13:13:16.436  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
11-23 13:13:16.436  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
11-23 13:13:16.436  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,11-23 13:13:16.436  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
11-23 13:13:16.436  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
11-23 13:13:16.436  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
11-23 13:13:16.437  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
11-23 13:13:16.437  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
11-23 13:13:16.437  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
11-23 13:13:16.437  5605  5653 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
11-23 13:13:16.437  5605  5653 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-23 13:13:16.437  5605  5653 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
11-23 13:13:16.437  5605  5653 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 13:13:16.438  5605  5653 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
,11-23 13:13:16.438  5605  5653 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
11-23 13:13:16.438  5605  5653 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 13:13:16.438  5605  5653 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
11-23 13:13:16.438  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,11-23 13:13:16.441  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
11-23 13:13:16.442  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
11-23 13:13:16.442  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,11-23 13:13:16.443  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
11-23 13:13:16.443  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
,11-23 13:13:16.443  5605  5653 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
11-23 13:13:16.443  5605  5653 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
11-23 13:13:16.444  5605  5653 E io.jxcore.node.ConnectionHelper: connect: Callback is null
11-23 13:13:16.444  5605  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 125)
11-23 13:13:16.444  5605  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: tryToConnect:  socketConnectSucceeded = false, mIsShuttingDown = false
11-23 13:13:16.444  5605  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: socket closed
11-23 13:13:16.444  5605  5656 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: SYSTEM_DECIDED_INSECURE_RFCOMM_SOCKET_PORT
11-23 13:13:16.444  5605  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 13:13:16.445  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 13:13:16.445  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 13:13:16.445  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:13:16.445  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:13:16.445  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
11-23 13:13:16.446  5605  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c28bcc5 not in the list
11-23 13:13:16.446  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:16.446  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:13:16.446  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
11-23 13:13:16.446  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:13:16.446  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.446  5605  5656 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connecting
11-23 13:13:16.446  5605  5656 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 13:13:16.447  5605  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 125
11-23 13:13:16.444  4756  4756 W Binder_3: type=1400 audit(0.0:110): avc: denied { ioctl } for path="socket:[28659]" dev="sockfs" ino=28659 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
11-23 13:13:16.444  4756  4756 W Binder_3: type=1400 audit(0.0:111): avc: denied { ioctl } for path="socket:[28659]" dev="sockfs" ino=28659 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-23 13:13:16.448  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.447  5605  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close
,11-23 13:13:16.448  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.448  5605  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 125)
11-23 13:13:16.448  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.448  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 13:13:16.448  5605  5657 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 125)
11-23 13:13:16.448  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 13:13:16.448  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:16.448  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
,11-23 13:13:16.449  5605  5653 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
11-23 13:13:16.450  5605  5656 E org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread:  createSocketAndConnect: connect, socket closed
11-23 13:13:16.450  5605  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: socketConnectSucceeded false
11-23 13:13:16.450  5605  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 13:13:16.450  5605  5656 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 125)
11-23 13:13:16.450  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 13:13:16.450  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 13:13:16.450  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:13:16.450  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:13:16.450  5605  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c28bcc5 not in the list
,11-23 13:13:16.450  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:16.450  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:13:16.450  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
11-23 13:13:16.450  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.450  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.451  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.452  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.452  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.452  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-23 13:13:16.452  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 13:13:16.452  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:16.452  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:13:16.453  5605  5653 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
11-23 13:13:16.453  5605  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 13:13:16.453  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 13:13:16.453  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 13:13:16.453  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:13:16.453  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:13:16.453  5605  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c28bcc5 not in the list
,11-23 13:13:16.453  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:16.453  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:13:16.453  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
11-23 13:13:16.454  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.454  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.454  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.454  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.455  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:13:16.455  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 13:13:16.455  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 13:13:16.455  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:16.455  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:13:16.455  5605  5653 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
11-23 13:13:16.455  5605  5653 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
11-23 13:13:16.456  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-23 13:13:16.456  5605  5653 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
11-23 13:13:16.456  5605  5653 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
,11-23 13:13:16.456  5605  5653 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
11-23 13:13:16.456  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-23 13:13:16.456  5605  5653 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
11-23 13:13:16.456  5605  5653 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
11-23 13:13:16.456  5605  5653 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
11-23 13:13:16.457  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
11-23 13:13:16.457  5605  5653 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
11-23 13:13:16.457  5605  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 13:13:16.457  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 13:13:16.457  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 13:13:16.457  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:13:16.457  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:13:16.457  5605  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c28bcc5 not in the list
11-23 13:13:16.457  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:16.457  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:13:16.457  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 13:13:16.457  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.457  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.458  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.458  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.458  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:16.458  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 13:13:16.458  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 13:13:16.459  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 13:13:16.459  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:13:16.459  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:13:16.459  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:13:16.459  5605  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c28bcc5 not in the list
11-23 13:13:16.459  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:16.459  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:13:16.459  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 13:13:19.337   928  2967 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 13:13:21.460  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 13:13:21.461  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:13:21.461  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:13:21.461  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:13:21.461  5605  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c28bcc5 not in the list
11-23 13:13:21.461  5605  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 13:13:21.462  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 13:13:21.462  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 13:13:21.462  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:13:21.462  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
,11-23 13:13:21.462  5605  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c28bcc5 not in the list
11-23 13:13:21.463  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:21.463  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:13:21.463  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 13:13:21.463  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:21.463  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:13:21.467  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:21.468  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:21.468  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:21.468  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 13:13:21.468  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 13:13:21.468  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:21.468  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
,11-23 13:13:21.472  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
,11-23 13:13:21.473  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,11-23 13:13:21.473  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,11-23 13:13:21.480  4564  4564 W Binder_2: type=1400 audit(0.0:112): avc: denied { ioctl } for path="socket:[30407]" dev="sockfs" ino=30407 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-23 13:13:21.480  4564  4564 W Binder_2: type=1400 audit(0.0:113): avc: denied { ioctl } for path="socket:[30407]" dev="sockfs" ino=30407 ioctlcmd=7704 scontext=u:r:bluetooth:s0 tcontext=u:r:bluetooth:s0 tclass=unix_stream_socket permissive=0
,11-23 13:13:21.479  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
11-23 13:13:21.482  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
11-23 13:13:21.482  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  true, mIsServerStarted:  true
11-23 13:13:21.482  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
11-23 13:13:21.482  5605  5658 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Entering thread
,11-23 13:13:21.482  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
11-23 13:13:21.482  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 13:13:21.482  5605  5605 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
11-23 13:13:21.483  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:13:21.483  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
11-23 13:13:21.483  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
11-23 13:13:21.483  5605  5658 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 13:13:21.483  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
11-23 13:13:21.483  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 13:13:21.484  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-23 13:13:21.484  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
,11-23 13:13:21.484  5605  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c28bcc5 not in the list
11-23 13:13:21.484  5605  5605 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
11-23 13:13:21.484  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:21.484  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 13:13:21.484  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:21.484  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
,11-23 13:13:21.484  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 13:13:21.484  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:21.485  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:21.486  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 13:13:21.486  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:21.486  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:13:21.486  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:13:21.486  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 13:13:21.486  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 13:13:21.486  5605  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 13:13:21.486  5605  5605 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 13:13:21.486  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 13:13:21.486  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-23 13:13:21.486  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:13:21.486  5605  5658 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
11-23 13:13:21.486  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  true
11-23 13:13:21.486  5605  5658 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
,11-23 13:13:21.487  5605  5658 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
11-23 13:13:21.487  5605  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c28bcc5 not in the list
11-23 13:13:21.487  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:21.487  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:13:21.487  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
11-23 13:13:21.487  5605  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,11-23 13:13:21.487  5605  5605 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:13:21.487  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:21.487  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:21.488  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:21.489  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:21.489  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:21.489  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,11-23 13:13:21.489  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 13:13:21.489  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:21.489  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:13:21.491  5605  5653 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
11-23 13:13:21.491  5605  5653 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
11-23 13:13:21.491  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,11-23 13:13:21.491  5605  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 13:13:21.491  5605  5653 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
11-23 13:13:21.493  5605  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 13:13:21.493  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 13:13:21.493  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-23 13:13:21.494  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:13:21.494  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:13:21.495  5605  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c28bcc5 not in the list
11-23 13:13:21.495  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:21.496  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:13:21.496  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
11-23 13:13:21.496  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:13:21.497  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:21.500  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:21.500  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:21.500  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:21.501  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 13:13:21.501  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 13:13:21.501  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:21.501  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
,11-23 13:13:21.506  5605  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,11-23 13:13:21.506  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 13:13:21.506  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 13:13:21.506  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:13:21.507  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:13:21.507  5605  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c28bcc5 not in the list
11-23 13:13:21.507  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:21.507  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
,11-23 13:13:21.507  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
11-23 13:13:21.507  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:21.507  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:21.508  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:21.508  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:21.508  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:21.508  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 13:13:21.508  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,11-23 13:13:21.508  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:21.508  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:13:21.509  5605  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 13:13:21.509  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 13:13:21.509  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 13:13:21.509  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:13:21.509  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:13:21.509  5605  5653 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@c28bcc5 not in the list
,11-23 13:13:21.509  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:21.509  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:13:21.509  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
11-23 13:13:21.510  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:21.510  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:21.511  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:21.511  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:13:21.511  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:13:21.511  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 13:13:21.511  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 13:13:21.511  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:21.511  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c3a961a not in the list
11-23 13:13:21.512  5605  5653 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
11-23 13:13:21.512  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-23 13:13:21.512  5605  5653 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
,11-23 13:13:21.512  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
11-23 13:13:21.512  5605  5653 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
11-23 13:13:21.513  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,11-23 13:13:21.515  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
11-23 13:13:21.515  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
11-23 13:13:21.515  5605  5653 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
11-23 13:13:21.515  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-23 13:13:21.515  5605  5653 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
11-23 13:13:21.515  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
11-23 13:13:21.516  5605  5653 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
11-23 13:13:21.516  5605  5653 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
11-23 13:13:21.516  5605  5653 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
,11-23 13:13:21.516  5605  5653 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
11-23 13:13:21.517  5605  5653 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
11-23 13:13:21.517  5605  5653 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
11-23 13:13:21.517  5605  5653 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
,11-23 13:13:21.517  5605  5653 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
,11-23 13:13:21.518  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 13:13:21.518  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@a0ad73b added. We now have 3 listener(s)
11-23 13:13:21.518  5605  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 13:13:21.520  5605  5653 D BluetoothAdapter: enable(): BT is already enabled..!
,11-23 13:13:21.520   928  3577 D WifiService: setWifiEnabled: true pid=5605, uid=10077
11-23 13:13:21.520   928  3577 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 13:13:21.576  4549  4742 W bt_sdp  : SDP - Rcvd conn cnf with error: 0x4  CID 0x40
,11-23 13:13:21.576  4549  4745 E bt_btif_sock_rfcomm: find_rfc_slot_by_id unable to find RFCOMM slot id: 5
,11-23 13:13:21.987  5605  5605 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 13:13:22.362   928  2967 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
,11-23 13:13:26.349   544   544 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 13:13:26.350   544   544 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 13:13:26.526  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 13:13:26.526  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6d3ce58 added. We now have 4 listener(s)
,11-23 13:13:26.527  5605  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 13:13:26.542  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 13:13:26.542  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6d3ce58 removed from the list
11-23 13:13:26.542  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 13:13:26.544  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 13:13:26.544  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@11ddbb1 added. We now have 4 listener(s)
,11-23 13:13:26.544  5605  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 13:13:26.547  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 13:13:26.548  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@11ddbb1 removed from the list
,11-23 13:13:26.548  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 13:13:26.550  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,11-23 13:13:26.551  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e8ca896 added. We now have 4 listener(s)
11-23 13:13:26.551  5605  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 13:13:26.556   928  3835 D WifiService: setWifiEnabled: false pid=5605, uid=10077
11-23 13:13:26.556   928  3835 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 13:13:26.564   928  2965 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-23 13:13:26.564   928  2965 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-23 13:13:26.564   928  2965 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 13:13:26.564   928  2965 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 13:13:26.573  4549  4606 D BluetoothAdapterState: Current state: ON, message: 23
11-23 13:13:26.573  4549  4606 D BluetoothAdapterProperties: Setting state to 13
,11-23 13:13:26.573  4549  4606 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-23 13:13:26.574  4549  4606 D BluetoothAdapterProperties: onBluetoothDisable()
11-23 13:13:26.575  4549  4606 I BluetoothAdapterState: Entering PendingCommandState
11-23 13:13:26.579  4549  4549 D BluetoothMapService: onReceive
,11-23 13:13:26.580  4549  4549 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-23 13:13:26.580  4549  4549 D BluetoothMapService: STATE_TURNING_OFF
11-23 13:13:26.580  4549  4549 D BluetoothMapService: MAP Service closeService in
11-23 13:13:26.580  4549  4549 D BluetoothMapMasInstance0: MAP Service shutdown
11-23 13:13:26.580  4549  4549 D ObexServerSockets0: shutdown(block = true)
11-23 13:13:26.581  4549  4549 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 13:13:26.581  4549  4549 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 13:13:26.581  4549  4769 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
11-23 13:13:26.582  4549  4770 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-23 13:13:26.581  4549  4745 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-23 13:13:26.582   507   920 D CommandListener: Clearing all IP addresses on wlan0
,11-23 13:13:26.582   928  5372 D DhcpClient: Clearing IP address
,11-23 13:13:26.591  4549  4549 I BtOppRfcommListener: stopping Accept Thread
,11-23 13:13:26.591  4549  5306 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,11-23 13:13:26.592  4549  5306 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-23 13:13:26.597   507   920 D CommandListener: Setting iface cfg
11-23 13:13:26.600  3563  5426 V NativeCrypto: Read error: ssl=0x7f75349a80: I/O error during system call, Connection timed out
,11-23 13:13:26.602  3563  5426 V NativeCrypto: SSL shutdown failed: ssl=0x7f75349a80: I/O error during system call, Broken pipe
,11-23 13:13:26.605   928  3684 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
,11-23 13:13:26.605   928  5370 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
11-23 13:13:26.608   928  5370 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
11-23 13:13:26.610   928  2967 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
,11-23 13:13:26.610   928  2967 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
11-23 13:13:26.610   928   941 I ActivityManager: Start proc 5662:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
11-23 13:13:26.611  4549  4610 D BluetoothAdapterProperties: Scan Mode:20
11-23 13:13:26.612   928  2967 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
11-23 13:13:26.612  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 13:13:26.612  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-23 13:13:26.613  4549  4606 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
11-23 13:13:26.614   928  2967 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,11-23 13:13:26.614   928  2967 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
,11-23 13:13:26.619  5605  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 13:13:26.619  5605  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
11-23 13:13:26.619  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 13:13:26.619  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 13:13:26.619  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 13:13:26.619  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 13:13:26.619  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 13:13:26.619  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 13:13:26.619  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 13:13:26.619  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 13:13:26.620  5605  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 13:13:26.620  5605  5653 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 13:13:26.620  5605  5653 D io.jxcore.node.ConnectivityMonitor: start: OK
11-23 13:13:26.622  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 13:13:26.622   542   542 E Parcel  : Reading a NULL string not supported here.
,11-23 13:13:26.624  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 13:13:26.625   928  2967 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
11-23 13:13:26.625  4549  4549 D HeadsetService: Received stop request...Stopping profile...
11-23 13:13:26.627   928   928 D RttService: SCAN_AVAILABLE : 1
,11-23 13:13:26.628   928  3056 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-23 13:13:26.630  3740  3903 W QCNEJ   : |CORE| network lost: 100
,11-23 13:13:26.630   928  5373 D DhcpClient: Receive thread stopped
11-23 13:13:26.630  3790  3820 D BluetoothHeadset: Proxy object disconnected
11-23 13:13:26.631  3106  3966 D BluetoothHeadset: Proxy object disconnected
11-23 13:13:26.631   928   928 D BluetoothHeadset: Proxy object disconnected
11-23 13:13:26.631   928   928 D BluetoothHeadset: Proxy object disconnected
11-23 13:13:26.631   928   928 D BluetoothHeadset: Proxy object disconnected
11-23 13:13:26.632  4549  4549 D A2dpService: Received stop request...Stopping profile...
11-23 13:13:26.632  4549  4762 D A2dpStateMachine: Exit Disconnected: -1
,11-23 13:13:26.634   928   928 D BluetoothA2dp: Proxy object disconnected
,11-23 13:13:26.634  3740  3903 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,11-23 13:13:26.636  4549  4549 D HidService: Received stop request...Stopping profile...
11-23 13:13:26.637  3106  3106 D HeadsetProfile: Bluetooth service disconnected
,11-23 13:13:26.636  4549  4549 D HidService: Stopping Bluetooth HidService
,11-23 13:13:26.638  3106  3106 D BluetoothA2dp: Proxy object disconnected
11-23 13:13:26.640  4549  4549 D HealthService: Received stop request...Stopping profile...
11-23 13:13:26.642  4549  4549 D PanService: Received stop request...Stopping profile...
11-23 13:13:26.643  4549  4549 V BluetoothAdapterState: isTurningOff()=true
11-23 13:13:26.643  4549  4549 V BluetoothAdapterState: isTurningOn()=false
11-23 13:13:26.643  4549  4549 V BluetoothAdapterState: isBleTurningOn()=false
11-23 13:13:26.643  4549  4549 V BluetoothAdapterState: isBleTurningOff()=false
11-23 13:13:26.648   928  2965 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,11-23 13:13:26.651  4549  4549 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
,11-23 13:13:26.651  4549  4549 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-23 13:13:26.651  4549  4742 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 13:13:26.651  4549  4742 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 13:13:26.651  4549  4742 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 13:13:26.652  4549  4610 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
11-23 13:13:26.652  4549  4610 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-23 13:13:26.652  4549  4549 D BluetoothMapService: Received stop request...Stopping profile...
11-23 13:13:26.652  4549  4549 D BluetoothMapService: stop()
11-23 13:13:26.652  4549  4549 D BluetoothMapAppObserver: deinitObservers()
11-23 13:13:26.652  4549  4549 D BluetoothMapAppObserver: removeReceiver()
11-23 13:13:26.658  4549  4549 D SapService: Received stop request...Stopping profile...
11-23 13:13:26.658  4549  4549 V SapService: stop()
,11-23 13:13:26.660   928  2965 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-23 13:13:26.661  3106  3106 D BluetoothInputDevice: Proxy object disconnected
,11-23 13:13:26.661  3106  3106 D HidProfile: Bluetooth service disconnected
,11-23 13:13:26.662  3106  3106 D BluetoothPan: BluetoothPAN Proxy object disconnected
,11-23 13:13:26.662  3106  3106 D PanProfile: Bluetooth service disconnected
,11-23 13:13:26.662  3106  3106 D BluetoothMap: Proxy object disconnected
11-23 13:13:26.662  3106  3106 D MapProfile: Bluetooth service disconnected
,11-23 13:13:26.665  4549  4549 V BluetoothAdapterState: isTurningOff()=true
,11-23 13:13:26.665  4549  4549 V BluetoothAdapterState: isTurningOn()=false
,11-23 13:13:26.665  4549  4549 V BluetoothAdapterState: isBleTurningOn()=false
11-23 13:13:26.665  4549  4549 V BluetoothAdapterState: isBleTurningOff()=false
11-23 13:13:26.666  4549  4742 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 13:13:26.666  4549  4549 V BluetoothAdapterState: isTurningOff()=true
,11-23 13:13:26.666  4549  4742 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 13:13:26.666  4549  4549 V BluetoothAdapterState: isTurningOn()=false
,11-23 13:13:26.666  4549  4549 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 13:13:26.666  4549  4549 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 13:13:26.667  4549  4742 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 13:13:26.667  4549  4742 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 13:13:26.667  4549  4742 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 13:13:26.667  4549  4549 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,11-23 13:13:26.667  4549  4742 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,11-23 13:13:26.667  4549  4549 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
11-23 13:13:26.667  4549  4610 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-23 13:13:26.667  4549  4549 V BluetoothAdapterState: isTurningOff()=true
11-23 13:13:26.667  4549  4549 V BluetoothAdapterState: isTurningOn()=false
11-23 13:13:26.667  4549  4610 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-23 13:13:26.667  4549  4549 V BluetoothAdapterState: isBleTurningOn()=false
11-23 13:13:26.667  4549  4549 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 13:13:26.667  4549  4549 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
,11-23 13:13:26.668  4549  4610 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-23 13:13:26.668  4549  4549 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
,11-23 13:13:26.668  4549  4549 V BluetoothAdapterState: isTurningOff()=true
11-23 13:13:26.668  4549  4549 V BluetoothAdapterState: isTurningOn()=false
11-23 13:13:26.668  4549  4549 V BluetoothAdapterState: isBleTurningOn()=false
11-23 13:13:26.668  4549  4549 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 13:13:26.669  4549  4549 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
,11-23 13:13:26.669  4549  4549 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
11-23 13:13:26.670  4549  4549 D BluetoothMapService: MAP Service closeService in
,11-23 13:13:26.670  4549  4549 V BluetoothAdapterState: isTurningOff()=true
,11-23 13:13:26.670  4549  4549 V BluetoothAdapterState: isTurningOn()=false
,11-23 13:13:26.670  4549  4549 V BluetoothAdapterState: isBleTurningOn()=false
11-23 13:13:26.670  4549  4549 V BluetoothAdapterState: isBleTurningOff()=false
11-23 13:13:26.670  4549  4549 D BluetoothMapService: cleanup()
11-23 13:13:26.670  4549  4549 D BluetoothMapService: MAP Service closeService in
11-23 13:13:26.670  4549  4549 V BluetoothAdapterState: isTurningOff()=true
11-23 13:13:26.671  4549  4549 V BluetoothAdapterState: isTurningOn()=false
11-23 13:13:26.671  4549  4549 V BluetoothAdapterState: isBleTurningOn()=false
11-23 13:13:26.671  4549  4549 V BluetoothAdapterState: isBleTurningOff()=false
11-23 13:13:26.671  4549  4606 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-23 13:13:26.671  4549  4606 D BluetoothAdapterProperties: Setting state to 15
11-23 13:13:26.671  4549  4606 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-23 13:13:26.672  4549  4606 I BluetoothAdapterState: Entering BleOnState
11-23 13:13:26.672  3106  5604 D BluetoothPbap: onBluetoothStateChange: up=false
11-23 13:13:26.673   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 13:13:26.673  3106  3123 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 13:13:26.674  3106  3117 D BluetoothPan: onBluetoothStateChange on: false
11-23 13:13:26.674   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 13:13:26.675  3106  3966 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 13:13:26.675   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 13:13:26.675  3106  5604 D BluetoothMap: onBluetoothStateChange: up=false
11-23 13:13:26.676  3790  4024 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 13:13:26.676   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 13:13:26.676  3106  3123 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-23 13:13:26.677  4549  4606 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-23 13:13:26.677  4549  4606 D BluetoothAdapterProperties: Setting state to 16
11-23 13:13:26.677  4549  4606 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-23 13:13:26.678  4549  4606 D BluetoothAdapterProperties: onBleDisable
11-23 13:13:26.678  4549  4606 I BluetoothAdapterState: Entering PendingCommandState
11-23 13:13:26.678  4549  4607 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
11-23 13:13:26.679  4549  4610 D BluetoothAdapterProperties: Scan Mode:20
11-23 13:13:26.679  4549  4742 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-23 13:13:26.679  4549  4742 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 13:13:26.681   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-23 13:13:26.682  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 13:13:26.682  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 13:13:26.682  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 13:13:26.682  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 13:13:26.682  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 13:13:26.682  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 13:13:26.682  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 13:13:26.682  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 13:13:26.682  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 13:13:26.682  5605  5605 V io.jxcore.node.ConnectivityMonitor:    , - active network type is Wi-Fi: false
11-23 13:13:26.684  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 13:13:26.691  5662  5662 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
11-23 13:13:26.706   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-23 13:13:26.706   507   920 D CommandListener: Clearing all IP addresses on wlan0
11-23 13:13:26.706   507   920 D TetherController: Setting IP forward enable = 0
11-23 13:13:26.708   928  2967 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
11-23 13:13:26.708   928  2967 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
11-23 13:13:26.709   928   945 D Tethering: MasterInitialState.processMessage what=3
,11-23 13:13:26.711  5270  5270 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@8f9298a and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
,11-23 13:13:26.712  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 13:13:26.716  4988  5012 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-23 13:13:26.716  4988  5012 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 13:13:26.716  4988  5012 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-23 13:13:26.716  4988  5012 E SarControlService: no key has been found,reset the power
11-23 13:13:26.718  4988  5023 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-23 13:13:26.718  4988  5023 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 13:13:26.718  4988  5023 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-23 13:13:26.719  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 13:13:26.719  5013  5013 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-23 13:13:26.720  4988  5023 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-23 13:13:26.720  4988  5023 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-23 13:13:26.720  4988  5023 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-23 13:13:26.720  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 13:13:26.720  5013  5013 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-23 13:13:26.723  5013  5027 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@747c840 HexData = [00000000ea03000000000000ffffffff]
11-23 13:13:26.723  5013  5027 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 13:13:26.723  5013  5027 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
11-23 13:13:26.723  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 13:13:26.724  4988  4998 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-23 13:13:26.727  5662  5662 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-23 13:13:26.731  5013  5027 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@747c840 HexData = [00000000eb03000000000000ffffffff]
11-23 13:13:26.731  5013  5027 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 13:13:26.731  5013  5027 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
11-23 13:13:26.732  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 13:13:26.732  4988  4999 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-23 13:13:26.734  3563  3563 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-23 13:13:26.736   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@6d4c802:true
11-23 13:13:26.747   928  3837 I ActivityManager: Start proc 5691:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
11-23 13:13:26.757   507   920 E Netd    : netlink response contains error (No such file or directory)
11-23 13:13:26.758   507   920 D TetherController: Setting IP forward enable = 0
11-23 13:13:26.758  5662  5662 D LocalBluetoothProfileManager: Adding local MAP profile
11-23 13:13:26.759   928  2965 D DhcpClient: doQuit
11-23 13:13:26.759   928  2967 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
11-23 13:13:26.760   928  2965 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-23 13:13:26.760   928  5372 D DhcpClient: onQuitting
11-23 13:13:26.761  3438  3438 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-23 13:13:26.764  5662  5662 D BluetoothMap: Create BluetoothMap proxy object
11-23 13:13:26.765  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 13:13:26.765  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 13:13:26.765  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 13:13:26.765  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 13:13:26.765  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 13:13:26.765  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 13:13:26.765  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 13:13:26.765  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 13:13:26.765  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 13:13:26.765  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 13:13:26.766  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 13:13:26.766  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 13:13:26.773  5662  5662 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,11-23 13:13:26.780  3438  3438 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,11-23 13:13:26.782  5662  5662 D DockEventReceiver: finishStartingService: stopping service
11-23 13:13:26.783  3438  3438 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,11-23 13:13:26.791   928  3837 I ActivityManager: Killing 4888:com.google.android.calendar/u0a36 (adj 15): empty #17
,11-23 13:13:26.806  5691  5691 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,11-23 13:13:26.815  3438  3438 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-23 13:13:26.817  3438  3438 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,11-23 13:13:26.897  4549  4610 I bt_hci  : shut_down
,11-23 13:13:26.902  4549  4616 D bt_hwcfg: hw_epilog_process
,11-23 13:13:26.902  4549  4616 I bt_vendor: low_power_mode_cb
,11-23 13:13:26.904  4549  4616 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-23 13:13:26.905  4549  4616 I bt_vendor: epilog_cb
11-23 13:13:26.905  4549  4616 I bt_hci  : epilog_finished_callback
,11-23 13:13:26.907  4549  4610 I bt_hci_h4: hal_close
11-23 13:13:26.908  4549  4610 I bt_userial_vendor: device fd = 54 close
,11-23 13:13:26.921   928  2965 D wifi    : In wifi stop Hal
,11-23 13:13:26.921  4931  4931 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 13:13:26.921   928  2965 D wifi    : halHandle = 0x7f62b8d900, mVM = 0x7f7f20d140, mCls = 0x100a02
11-23 13:13:26.921   928  3437 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
11-23 13:13:26.922   928  3437 D WifiHAL : Got a signal to exit!!!
11-23 13:13:26.922   928  3437 I WifiHAL : Exit wifi_event_loop
11-23 13:13:26.922   928  2965 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 11
11-23 13:13:26.922   928  2965 E WifiHAL : Event processing terminated
11-23 13:13:26.922   928  2965 D wifi    : In wifi cleaned up handler
11-23 13:13:26.922   928  2965 I WifiHAL : Internal cleanup completed
11-23 13:13:26.923  4074  4214 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 13:13:26.924  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 13:13:26.942   928  3437 D wifi    : set interface wlan0 flags (DOWN)
,11-23 13:13:26.942   928  2965 D WifiNative-HAL: HAL event thread stopped successfully
,11-23 13:13:26.998  5691  5691 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at java.io.File.exists(File.java:361)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,11-23 13:13:26.998  5691  5691 D StrictMode: StrictMode policy violation; ~duration=121 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-23 13:13:26.998  5691  5691 D StrictMode: StrictMode policy violation; ~duration=120 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.ap,p.a.a(PG:244)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-23 13:13:26.998  5691  5691 D StrictMode: StrictMode policy violation; ~duration=119 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.r.k.a(PG:2107)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.r.e.b(PG:170)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread.-wrap1(Activit,yThread.java)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-23 13:13:26.998  5691  5691 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.r.k.d(PG:1187)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.r.k.c(PG:18147)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.r.k.d(PG:583)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.r.v.a(PG:1161)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.r.y.a(PG:2188)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.r.e.b(PG:170)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.r.e.b(PG:15188)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-23 13:13:26.998  5691  5691 D StrictMode: StrictMode policy violation; ~duration=79 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at java.io.File.exists(File.java:361)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-23 13:13:26.998  5691  5691 D StrictMode: StrictMode policy violation; ~duration=78 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at java.io.File.doAccess(File.java:281)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at java.io.File.exists(File.java:361)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-23 13:13:26.998  5691  5691 D StrictMode: StrictMode policy violation; ~duration=77 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at java.io.File.lastModified(File.java:569)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4712)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5422)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
11-23 13:13:26.998  5691  5691 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
11-23 13:13:27.004  5662  5662 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-23 13:13:27.011  3563  3563 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-23 13:13:27.015  4549  4607 D bt_stack_manager: event_shut_down_stack finished.
11-23 13:13:27.015  5662  5662 D DockEventReceiver: finishStartingService: stopping service
11-23 13:13:27.015  4549  4606 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
11-23 13:13:27.017  4549  4606 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
11-23 13:13:27.017  4549  4549 D BtGatt.DebugUtils: handleDebugAction() action=null
11-23 13:13:27.017  4549  4549 D BtGatt.GattService: Received stop request...Stopping profile...
11-23 13:13:27.017  4549  4549 D BtGatt.GattService: stop()
11-23 13:13:27.018  4549  4549 D BtGatt.AdvertiseManager: advertise clients cleared
11-23 13:13:27.019  4549  4549 V BluetoothAdapterState: isTurningOff()=false
11-23 13:13:27.019  4549  4549 V BluetoothAdapterState: isTurningOn()=false
11-23 13:13:27.019  4549  4549 V BluetoothAdapterState: isBleTurningOn()=false
11-23 13:13:27.019  4549  4549 V BluetoothAdapterState: isBleTurningOff()=true
11-23 13:13:27.019  4549  4606 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
11-23 13:13:27.019  4549  4606 D BluetoothAdapterProperties: Setting state to 10
11-23 13:13:27.019  4549  4606 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-23 13:13:27.020   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
11-23 13:13:27.021  4549  4606 I BluetoothAdapterState: Entering OffState
11-23 13:13:27.030  4549  4549 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
11-23 13:13:27.030  4549  4549 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-23 13:13:27.030  4549  4607 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
11-23 13:13:27.031  4549  4549 I BluetoothServiceJni: cleanupNative: return from cleanup
,11-23 13:13:27.043   928  3684 I ActivityManager: Killing 5400:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
11-23 13:13:27.050  4549  4607 D bt_stack_manager: event_clean_up_stack finished.
11-23 13:13:27.050  4549  4549 I art     : System.exit called, status: 0
11-23 13:13:27.050  4549  4549 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
11-23 13:13:27.073  3715  3715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-23 13:13:27.076  3715  3715 D SystemUpdateService: onCreate
,11-23 13:13:27.091  3715  3715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-23 13:13:27.099  3715  3715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-23 13:13:27.104  3715  5397 I iu.UploadsManager: num queued entries: 0
,11-23 13:13:27.104  3715  5397 I iu.UploadsManager: num updated entries: 0
11-23 13:13:27.105  3715  5397 I iu.SyncManager: NEXT; no task
,11-23 13:13:27.106  3715  3715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-23 13:13:27.109  3715  3715 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-23 13:13:27.113  3715  5726 I SystemUpdateService: active receiver: enabled
,11-23 13:13:27.120   928  3837 I ActivityManager: Start proc 5728:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
,11-23 13:13:27.121   928  3184 I ActivityManager: Process com.android.bluetooth (pid 4549) has died
,11-23 13:13:27.131  3715  5726 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-23 13:13:27.145   928   945 D Tethering: InitialState.processMessage what=4
,11-23 13:13:27.149   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-23 13:13:27.156  5728  5728 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,11-23 13:13:27.158  5728  5728 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-23 13:13:27.166  5728  5728 D SprintDMHelper: simOperator: 
11-23 13:13:27.166  5728  5728 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 13:13:27.175  3715  5726 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-23 13:13:27.175  3715  5726 I SystemUpdateService: now status is 0 (complete)
11-23 13:13:27.175  3715  5726 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 13:13:27.175  3715  5726 I SystemUpdateService: file has been verified
,11-23 13:13:27.175  3715  5726 I SystemUpdateService: OTA package size = 21989297
,11-23 13:13:27.186  4931  5740 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-23 13:13:27.192   928  3837 I ActivityManager: Start proc 5741:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,11-23 13:13:27.206  3715  5726 I SystemUpdateService: showing system update notification
,11-23 13:13:27.223  5741  5741 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,11-23 13:13:27.237   928  3841 I ActivityManager: Killing 5270:com.google.android.music:main/u0a59 (adj 15): empty #17
,11-23 13:13:27.272  3715  3715 D SystemUpdateService: onDestroy
,11-23 13:13:27.276   928  3684 I ActivityManager: Killing 4620:com.android.providers.calendar/u0a1 (adj 15): empty #17
,11-23 13:13:27.386  5691  5718 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,11-23 13:13:27.395   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@8da4e57:true
,11-23 13:13:31.351   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:13:31.622   928  3577 D WifiService: setWifiEnabled: true pid=5605, uid=10077
,11-23 13:13:31.623   928  3577 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 13:13:31.634   507   920 D SoftapController: Softap fwReload - Ok
,11-23 13:13:31.639   507   920 D CommandListener: Setting iface cfg
,11-23 13:13:31.640   507   920 D CommandListener: Trying to bring down wlan0
,11-23 13:13:31.641   507   920 D CommandListener: Clearing all IP addresses on wlan0
,11-23 13:13:31.645   928  2965 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-23 13:13:32.220   928  2965 D wifi    : set interface wlan0 flags (UP)
,11-23 13:13:32.222   928  2965 I WifiHAL : Initializing wifi
11-23 13:13:32.222   928  2965 I WifiHAL : Creating socket
,11-23 13:13:32.223   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-23 13:13:32.225   928  2965 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
11-23 13:13:32.225   928  2965 D wifi    : Did set static halHandle = 0x7f62b8d900
11-23 13:13:32.225   928  2965 D wifi    : halHandle = 0x7f62b8d900, mVM = 0x7f7f20d140, mCls = 0x1862
,11-23 13:13:32.225   928  2965 D wifi    : array field set
,11-23 13:13:32.225   928  2965 I WifiNative-HAL: interface[0] = wlan0
,11-23 13:13:32.227   928  5760 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547117127936
11-23 13:13:32.228   928  5760 D wifi    : waitForHalEvents called, vm = 0x7f7f20d140, obj = 0x1862, env = 0x7f5f1dae40
,11-23 13:13:32.293  5761  5761 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-23 13:13:32.307  5761  5761 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 13:13:32.313  5761  5761 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 13:13:32.313  5761  5761 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-23 13:13:32.329   928  2965 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
11-23 13:13:32.332  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 13:13:32.332  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 13:13:32.332  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 13:13:32.332  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 13:13:32.332  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 13:13:32.332  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 13:13:32.332  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 13:13:32.332  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 13:13:32.332  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 13:13:32.332  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 13:13:32.332  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 13:13:32.332  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
,11-23 13:13:32.333   928  2965 D WifiConfigStore: Loading config and enabling all networks 
11-23 13:13:32.333  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 13:13:32.341   928  2965 D WifiConfigStore: loaded 0 passpoint configs
,11-23 13:13:32.341   928  2965 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
11-23 13:13:32.341   928  2965 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
11-23 13:13:32.342   928  2965 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-23 13:13:32.343   928  2965 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
,11-23 13:13:32.343   928  2965 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-23 13:13:32.343   928  2965 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-23 13:13:32.343   928  2965 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-23 13:13:32.345   928  2965 D WifiNative-HAL: Setting external_sim to 1
,11-23 13:13:32.346   928  2965 D wifi    : setting dfs flag to true, 0x7f668bfa60
,11-23 13:13:32.345  4931  4931 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-23 13:13:32.346   928  2965 D WifiStateMachine: Setting OUI to DA-A1-19
11-23 13:13:32.346   928  2965 D wifi    : setting scan oui 0x7f668bfa60
11-23 13:13:32.346   928  2965 D WifiHAL : Sending mac address OUI
,11-23 13:13:32.349   928  2965 E native  : do suspend false
,11-23 13:13:32.351   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:13:32.355   928  2965 D wifi    : android_net_wifi_setLinkLayerStats: 1
,11-23 13:13:32.356   928   928 D RttService: SCAN_AVAILABLE : 3
11-23 13:13:32.356   928  3056 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,11-23 13:13:32.359   507   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-23 13:13:32.361   507   920 D CommandListener: Setting iface cfg
,11-23 13:13:32.362   928  2964 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '128 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 128 Failed to set address (No such device)'
,11-23 13:13:32.363   928  2964 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-23 13:13:32.370   928  2964 D WifiNative-HAL: p2pGetDeviceAddress
,11-23 13:13:32.374   928  2964 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,11-23 13:13:32.375   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=119928 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,11-23 13:13:33.039   928  2965 D WifiStateMachine: Disconnected CMD_START_SCAN source -2 7, 8 -> obsolete
,11-23 13:13:33.352   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:13:34.353   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:13:35.354   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:13:35.463  5761  5761 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 13:13:35.471  5761  5761 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 13:13:35.477  5761  5761 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 13:13:35.484  5761  5761 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 13:13:35.509   928  2965 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-23 13:13:35.510   928  2965 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-23 13:13:35.510   928  2965 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 13:13:35.520   928  2965 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-23 13:13:35.553   928  2965 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-23 13:13:35.556  5761  5761 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-23 13:13:35.981  5761  5761 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-23 13:13:36.013  5761  5761 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-23 13:13:36.014  5761  5761 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-23 13:13:36.022   928  2965 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
11-23 13:13:36.022   928  2965 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 13:13:36.022   928  2967 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-23 13:13:36.039   928  2965 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 13:13:36.050   507   920 D CommandListener: Setting iface cfg
,11-23 13:13:36.055   928  2965 D WifiStateMachine: Start Dhcp Watchdog 2
,11-23 13:13:36.060   928  5767 D DhcpClient: Receive thread started
,11-23 13:13:36.065   928  2967 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 13:13:36.065   928  2965 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
11-23 13:13:36.065   928  2967 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
,11-23 13:13:36.145   928  2965 E native  : do suspend false
,11-23 13:13:36.156   928  5766 D DhcpClient: Broadcasting DHCPDISCOVER
,11-23 13:13:36.170   928  5767 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172716, domain null
,11-23 13:13:36.171   928  5766 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172716 seconds
,11-23 13:13:36.173   928  5766 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-23 13:13:36.199   928  5767 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-23 13:13:36.200   928  5766 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
,11-23 13:13:36.203   507   920 D CommandListener: Setting iface cfg
11-23 13:13:36.206   928  2965 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-23 13:13:36.212   928  5766 D DhcpClient: Scheduling renewal in 86399s
,11-23 13:13:36.222   928  2965 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-23 13:13:36.223   928  2965 D WifiConfigStore: No blacklist allowed without epno enabled
,11-23 13:13:36.226   928  2965 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
11-23 13:13:36.227   928  2967 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-23 13:13:36.229   928  2967 D ConnectivityService: Adding iface wlan0 to network 101
,11-23 13:13:36.272   928  2967 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-23 13:13:36.272   928  2967 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
,11-23 13:13:36.274   928  2967 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
,11-23 13:13:36.276   928  2967 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
,11-23 13:13:36.280   928  2967 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
,11-23 13:13:36.289   928  2967 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
,11-23 13:13:36.293   928  2967 D ConnectivityService: scheduleUnvalidatedPrompt 101
11-23 13:13:36.293   928  2967 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 101]
,11-23 13:13:36.293   928  2967 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 101]
11-23 13:13:36.293   928  2967 D ConnectivityService:    accepting network in place of null
11-23 13:13:36.293   928  2965 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
11-23 13:13:36.293   928  2965 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 13:13:36.294   928  2967 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -46]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 13:13:36.310   928  5765 D NetlinkSocketObserver: NeighborEvent{elapsedMs=123864, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 13:13:36.317   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 13:13:36.340   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 13:13:36.343   928  2967 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
,11-23 13:13:36.344   928  2967 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-23 13:13:36.344  3740  3903 W QCNEJ   : |CORE| network available: 101
11-23 13:13:36.345   928  2967 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
11-23 13:13:36.346   928   945 D Tethering: MasterInitialState.processMessage what=3
11-23 13:13:36.348  3740  3903 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-23 13:13:36.349  3740  3903 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-23 13:13:36.349  3740  3903 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-23 13:13:36.351  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 13:13:36.351  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 13:13:36.351  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 13:13:36.351  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 13:13:36.351  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 13:13:36.351  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 13:13:36.351  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 13:13:36.351  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 13:13:36.351  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 13:13:36.351  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
11-23 13:13:36.351  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 13:13:36.351  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
11-23 13:13:36.355   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
11-23 13:13:36.358  4988  5012 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-23 13:13:36.359  4988  5012 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 13:13:36.359  4988  5012 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-23 13:13:36.359  4988  5012 E SarControlService: no key has been found,reset the power
,11-23 13:13:36.359  4988  5023 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-23 13:13:36.359  4988  5023 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 13:13:36.359  4988  5023 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
,11-23 13:13:36.360  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-23 13:13:36.360  5013  5013 D QcrilMsgTunnelSocket: [1004] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-23 13:13:36.362  4988  5023 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-23 13:13:36.362  4988  5023 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-23 13:13:36.362  4988  5023 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-23 13:13:36.362  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-23 13:13:36.363  5013  5013 D QcrilMsgTunnelSocket: [1005] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-23 13:13:36.367  3715  3715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-23 13:13:36.371  5013  5027 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@747c840 HexData = [00000000ec03000000000000ffffffff]
11-23 13:13:36.371  5013  5027 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 13:13:36.372  5013  5027 D QcrilMsgTunnelSocket: [1004] < OEM_HOOK_RAW [null]
11-23 13:13:36.372  3715  3715 D SystemUpdateService: onCreate
11-23 13:13:36.372  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 13:13:36.373  4988  4998 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-23 13:13:36.375   928  5764 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.14,2a00:1450:4001:802::200e
11-23 13:13:36.376  3715  3715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-23 13:13:36.379  5013  5027 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@747c840 HexData = [00000000ed03000000000000ffffffff]
11-23 13:13:36.379  5013  5027 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 13:13:36.379  5013  5027 D QcrilMsgTunnelSocket: [1005] < OEM_HOOK_RAW [null]
,11-23 13:13:36.380  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 13:13:36.380  4988  4999 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-23 13:13:36.385  3715  3715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-23 13:13:36.392  3715  5397 I iu.UploadsManager: num queued entries: 0
,11-23 13:13:36.392  3715  5397 I iu.UploadsManager: num updated entries: 0
,11-23 13:13:36.399  3715  5397 I iu.SyncManager: NEXT; no task
,11-23 13:13:36.401  3715  3715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-23 13:13:36.402  3715  3715 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-23 13:13:36.404  5728  5728 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-23 13:13:36.409  5728  5728 D SprintDMHelper: simOperator: 
11-23 13:13:36.409  5728  5728 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 13:13:36.417  3715  5777 I SystemUpdateService: active receiver: enabled
,11-23 13:13:36.424   928  5764 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 23 Nov 2016 18:13:36 GMT], X-Android-Received-Millis=[1479924816424], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479924816399]}
,11-23 13:13:36.425   928  2967 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-23 13:13:36.425   928  2967 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] validation  passed
11-23 13:13:36.425   928  2967 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 101]
11-23 13:13:36.426   928  2967 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-23 13:13:36.435  3715  5777 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-23 13:13:36.440  3715  5777 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-23 13:13:36.440  3715  5777 I SystemUpdateService: now status is 0 (complete)
11-23 13:13:36.441  3715  5777 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 13:13:36.441  3715  5777 I SystemUpdateService: file has been verified
11-23 13:13:36.441  3715  5777 I SystemUpdateService: OTA package size = 21989297
,11-23 13:13:36.447  3715  5777 I SystemUpdateService: showing system update notification
,11-23 13:13:36.457  3715  3715 D SystemUpdateService: onDestroy
,11-23 13:13:36.515  4931  5782 I Babel   : connection state changed from DISCONNECTED to CONNECTED
,11-23 13:13:36.629   928  3835 D WifiService: setWifiEnabled: false pid=5605, uid=10077
11-23 13:13:36.629   928  3835 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 13:13:36.634   928  2965 D WifiStateMachine: WifiStateMachine: Leaving Connected state
11-23 13:13:36.634   928  2965 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
,11-23 13:13:36.634   928  2965 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 13:13:36.635   928  2965 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 13:13:36.652   928  5766 D DhcpClient: Clearing IP address
,11-23 13:13:36.652   507   920 D CommandListener: Clearing all IP addresses on wlan0
,11-23 13:13:36.670  3563  5787 V NativeCrypto: Read error: ssl=0x7f75349a80: I/O error during system call, Connection timed out
11-23 13:13:36.672  3563  5787 V NativeCrypto: SSL shutdown failed: ssl=0x7f75349a80: I/O error during system call, Broken pipe
,11-23 13:13:36.675   928  3140 D ConnectivityService: reportNetworkConnectivity(101, false) by 10012
11-23 13:13:36.675   928  5764 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Forcing reevaluation for UID 10012
11-23 13:13:36.675   928  5764 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.14,2a00:1450:4001:802::200e
11-23 13:13:36.680   507   920 D CommandListener: Setting iface cfg
11-23 13:13:36.682   928  2967 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
11-23 13:13:36.682   928  2967 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 3
,11-23 13:13:36.686   542   542 E Parcel  : Reading a NULL string not supported here.
,11-23 13:13:36.691   928  5764 D NetworkMonitor/NetworkAgentInfo [WIFI () - 101]: Probably not a portal: exception java.net.ConnectException: failed to connect to connectivitycheck.gstatic.com/2a00:1450:4001:802::200e (port 80) after 10000ms: connect failed: ENETUNREACH (Network is unreachable)
,11-23 13:13:36.692   928  2967 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
,11-23 13:13:36.694  3740  3903 W QCNEJ   : |CORE| network lost: 101
11-23 13:13:36.695  3740  3903 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
11-23 13:13:36.698   928   928 D RttService: SCAN_AVAILABLE : 1
11-23 13:13:36.698   928  3056 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
11-23 13:13:36.700   928  5767 D DhcpClient: Receive thread stopped
,11-23 13:13:36.705   928  2965 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
11-23 13:13:36.708   928  2965 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,11-23 13:13:36.719   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 13:13:36.742   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
11-23 13:13:36.743   507   920 D CommandListener: Clearing all IP addresses on wlan0
,11-23 13:13:36.743   928  2967 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
11-23 13:13:36.743   928  2967 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-23 13:13:36.745   928   945 D Tethering: MasterInitialState.processMessage what=3
11-23 13:13:36.746   928  2965 D DhcpClient: doQuit
,11-23 13:13:36.746   928  2965 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
11-23 13:13:36.746   928  5766 D DhcpClient: onQuitting
11-23 13:13:36.747  5761  5761 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
11-23 13:13:36.748  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 13:13:36.748  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 13:13:36.748  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 13:13:36.748  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 13:13:36.748  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 13:13:36.748  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 13:13:36.748  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 13:13:36.748  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 13:13:36.748  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 13:13:36.748  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 13:13:36.748  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 13:13:36.748  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 13:13:36.752  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 13:13:36.757  4988  5012 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
,11-23 13:13:36.757  4988  5012 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 13:13:36.758  4988  5012 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
11-23 13:13:36.755  3715  3715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
11-23 13:13:36.759  4988  5012 E SarControlService: no key has been found,reset the power
,11-23 13:13:36.759  4988  5023 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
,11-23 13:13:36.759  4988  5023 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 13:13:36.759  4988  5023 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-23 13:13:36.760  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
11-23 13:13:36.760  5013  5013 D QcrilMsgTunnelSocket: [1006] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-23 13:13:36.760  5761  5761 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
11-23 13:13:36.761  4988  5023 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-23 13:13:36.761  4988  5023 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-23 13:13:36.761  4988  5023 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-23 13:13:36.762  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-23 13:13:36.762  5013  5013 D QcrilMsgTunnelSocket: [1007] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
11-23 13:13:36.764  5761  5761 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
11-23 13:13:36.767  5013  5027 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@747c840 HexData = [00000000ee03000000000000ffffffff]
11-23 13:13:36.768  5013  5027 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 13:13:36.768  5013  5027 D QcrilMsgTunnelSocket: [1006] < OEM_HOOK_RAW [null]
11-23 13:13:36.768  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-23 13:13:36.768  4988  4999 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
11-23 13:13:36.768  5013  5027 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@747c840 HexData = [00000000ef03000000000000ffffffff]
11-23 13:13:36.768  5013  5027 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 13:13:36.768  5013  5027 D QcrilMsgTunnelSocket: [1007] < OEM_HOOK_RAW [null]
11-23 13:13:36.769  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 13:13:36.769  4988  4998 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
11-23 13:13:36.770  3715  3715 D SystemUpdateService: onCreate
,11-23 13:13:36.774  3715  3715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,11-23 13:13:36.778  3715  5796 I SystemUpdateService: active receiver: enabled
,11-23 13:13:36.783  3715  3715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,11-23 13:13:36.788  3715  5397 I iu.UploadsManager: num queued entries: 0
11-23 13:13:36.789  3715  5397 I iu.UploadsManager: num updated entries: 0
,11-23 13:13:36.790  5761  5761 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,11-23 13:13:36.792  3715  3715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-23 13:13:36.794  3715  3715 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-23 13:13:36.796  5728  5728 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
11-23 13:13:36.799  5728  5728 D SprintDMHelper: simOperator: 
11-23 13:13:36.799  5728  5728 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 13:13:36.800  5761  5761 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
11-23 13:13:36.801  3715  5796 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-23 13:13:36.807   507   920 E Netd    : netlink response contains error (No such file or directory)
,11-23 13:13:36.808   928  2967 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
11-23 13:13:36.808   928  2967 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-23 13:13:36.812  3715  5397 I iu.SyncManager: NEXT; no task
,11-23 13:13:36.812  3715  5796 I SystemUpdateService: network: null; metered: false; mobile allowed: true
,11-23 13:13:36.812  3715  5796 I SystemUpdateService: now status is 0 (complete)
11-23 13:13:36.812  3715  5796 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 13:13:36.812  3715  5796 I SystemUpdateService: file has been verified
,11-23 13:13:36.816  4931  5800 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,11-23 13:13:36.818  3715  5796 I SystemUpdateService: OTA package size = 21989297
,11-23 13:13:36.833  3715  5796 I SystemUpdateService: showing system update notification
,11-23 13:13:36.842  3715  3715 D SystemUpdateService: onDestroy
,11-23 13:13:36.905   928  2965 D wifi    : In wifi stop Hal
11-23 13:13:36.905   928  2965 D wifi    : halHandle = 0x7f62b8d900, mVM = 0x7f7f20d140, mCls = 0x1862
11-23 13:13:36.906   928  5760 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
,11-23 13:13:36.906   928  5760 D WifiHAL : Got a signal to exit!!!
11-23 13:13:36.906   928  5760 I WifiHAL : Exit wifi_event_loop
11-23 13:13:36.907  4931  4931 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
11-23 13:13:36.907   928  2965 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
11-23 13:13:36.907   928  2965 E WifiHAL : Event processing terminated
11-23 13:13:36.907   928  2965 D wifi    : In wifi cleaned up handler
11-23 13:13:36.907   928  2965 I WifiHAL : Internal cleanup completed
11-23 13:13:36.908  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 13:13:36.908  4074  4214 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-23 13:13:36.929   928  5760 D wifi    : set interface wlan0 flags (DOWN)
,11-23 13:13:36.929   928  2965 D WifiNative-HAL: HAL event thread stopped successfully
,11-23 13:13:37.134   928   945 D Tethering: InitialState.processMessage what=4
,11-23 13:13:37.138   928   945 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,11-23 13:13:37.343   928  2967 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,11-23 13:13:41.355   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:13:41.670   928   945 I ActivityManager: Start proc 5802:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-23 13:13:41.762  5802  5802 D AdapterServiceConfig: Adding HeadsetService
,11-23 13:13:41.763  5802  5802 D AdapterServiceConfig: Adding A2dpService
,11-23 13:13:41.763  5802  5802 D AdapterServiceConfig: Adding HidService
11-23 13:13:41.763  5802  5802 D AdapterServiceConfig: Adding HealthService
,11-23 13:13:41.763  5802  5802 D AdapterServiceConfig: Adding PanService
11-23 13:13:41.763  5802  5802 D AdapterServiceConfig: Adding GattService
11-23 13:13:41.763  5802  5802 D AdapterServiceConfig: Adding BluetoothMapService
,11-23 13:13:41.764  5802  5802 D AdapterServiceConfig: Adding SapService
,11-23 13:13:41.776   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@4767f7a:true
,11-23 13:13:41.777  5802  5802 D BluetoothAdapterState: make() - Creating AdapterState
,11-23 13:13:41.782  5802  5802 I bt_bluedroid: init
,11-23 13:13:41.782  5802  5814 I BluetoothAdapterState: Entering OffState
,11-23 13:13:41.785  5802  5815 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
11-23 13:13:41.785  5802  5815 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-23 13:13:41.785  5802  5815 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-23 13:13:41.785  5802  5815 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
,11-23 13:13:41.786  5802  5802 I bt_bluedroid: get_profile_interface socket
,11-23 13:13:41.788  5802  5802 I bt_bluedroid: get_profile_interface sdp
11-23 13:13:41.788  5802  5818 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-23 13:13:41.789  5802  5818 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 13:13:41.794  5802  5813 I bt_bluedroid: config_hci_snoop_log
11-23 13:13:41.795   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-23 13:13:41.799  5802  5814 D BluetoothAdapterState: Current state: OFF, message: 0
,11-23 13:13:41.799  5802  5814 D BluetoothAdapterProperties: Setting state to 14
11-23 13:13:41.799  5802  5814 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,11-23 13:13:41.801  5802  5814 D BluetoothBondStateMachine: make
,11-23 13:13:41.803  5802  5819 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-23 13:13:41.806  5802  5814 I BluetoothAdapterState: Entering PendingCommandState
,11-23 13:13:41.807  5802  5802 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-23 13:13:41.809  5802  5802 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b98b1
11-23 13:13:41.810  5802  5802 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-23 13:13:41.811  5802  5802 D BtGatt.GattService: Received start request. Starting profile...
11-23 13:13:41.811  5802  5802 D BtGatt.GattService: start()
11-23 13:13:41.811  5802  5802 I bt_bluedroid: get_profile_interface gatt
,11-23 13:13:41.812  5802  5802 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b98b1
11-23 13:13:41.812  5802  5802 D BtGatt.AdvertiseManager: advertise manager created
,11-23 13:13:41.817  5802  5802 V BluetoothAdapterState: isTurningOff()=false
,11-23 13:13:41.817  5802  5802 V BluetoothAdapterState: isTurningOn()=false
11-23 13:13:41.817  5802  5802 V BluetoothAdapterState: isBleTurningOn()=true
11-23 13:13:41.818  5802  5802 V BluetoothAdapterState: isBleTurningOff()=false
11-23 13:13:41.818  5802  5814 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-23 13:13:41.819  5802  5814 I bt_bluedroid: bt_bluedroid
11-23 13:13:41.819  5802  5815 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-23 13:13:41.820  5802  5815 I bt_hci  : start_up
,11-23 13:13:41.825  5802  5815 I bt_vendor: alloc value 0xf3ceb871
,11-23 13:13:41.825  5802  5815 I bt_vendor: init
11-23 13:13:41.825  5802  5815 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-23 13:13:41.825  5802  5815 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-23 13:13:41.936  5802  5815 D bt_hci  : start_up starting async portion
11-23 13:13:41.937  5802  5822 I bt_hci  : event_finish_startup
,11-23 13:13:41.937  5802  5822 I bt_hci_h4: hal_open
11-23 13:13:41.937  5802  5822 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-23 13:13:41.934  5823  5823 W irq/448-msm_hs_: type=1400 audit(0.0:114): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 13:13:41.941  5802  5822 I bt_userial_vendor: device fd = 54 open
,11-23 13:13:41.954  5802  5822 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 13:13:41.957  5802  5822 D bt_hwcfg: Chipset BCM4358A3
11-23 13:13:41.957  5802  5822 D bt_hwcfg: Target name = [BCM4358A3]
,11-23 13:13:41.958  5802  5822 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-23 13:13:42.357   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:13:42.360  5802  5822 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-23 13:13:42.360  5802  5822 D bt_hwcfg: Settlement delay -- 100 ms
11-23 13:13:42.360  5802  5822 I bt_hwcfg: Setting fw settlement delay to 100 
,11-23 13:13:42.494  5802  5822 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 13:13:42.494  5802  5822 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
11-23 13:13:42.496  5802  5822 I bt_hwcfg: vendor lib fwcfg completed
,11-23 13:13:42.496  5802  5822 I bt_vendor: firmware callback
11-23 13:13:42.496  5802  5822 I bt_hci  : firmware_config_callback
,11-23 13:13:42.505  5802  5825 I bt_btu  : btu_task pending for preload complete event
,11-23 13:13:42.505  5802  5825 I bt_btu_task: Bluetooth chip preload is complete
11-23 13:13:42.506  5802  5825 I bt_btu  : btu_task received preload complete event
,11-23 13:13:42.514  5802  5825 I         : BTE_InitTraceLevels -- TRC_HCI
,11-23 13:13:42.514  5802  5825 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-23 13:13:42.514  5802  5825 I         : BTE_InitTraceLevels -- TRC_RFCOMM
11-23 13:13:42.514  5802  5825 I         : BTE_InitTraceLevels -- TRC_AVDT
11-23 13:13:42.514  5802  5825 I         : BTE_InitTraceLevels -- TRC_AVRC
,11-23 13:13:42.514  5802  5825 I         : BTE_InitTraceLevels -- TRC_A2D
11-23 13:13:42.514  5802  5825 I         : BTE_InitTraceLevels -- TRC_BNEP
11-23 13:13:42.515  5802  5825 I         : BTE_InitTraceLevels -- TRC_BTM
11-23 13:13:42.515  5802  5825 I         : BTE_InitTraceLevels -- TRC_GAP
,11-23 13:13:42.515  5802  5825 I         : BTE_InitTraceLevels -- TRC_PAN
11-23 13:13:42.515  5802  5825 I         : BTE_InitTraceLevels -- TRC_SDP
11-23 13:13:42.515  5802  5825 I         : BTE_InitTraceLevels -- TRC_GATT
11-23 13:13:42.515  5802  5825 I         : BTE_InitTraceLevels -- TRC_SMP
,11-23 13:13:42.515  5802  5825 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-23 13:13:42.515  5802  5825 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-23 13:13:42.597  5802  5825 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c69549
,11-23 13:13:42.597  5802  5825 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c69549 
,11-23 13:13:42.608  5802  5818 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-23 13:13:42.610  5802  5818 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-23 13:13:42.610  5802  5818 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-23 13:13:42.613  5802  5818 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 13:13:42.616  5802  5818 D BluetoothAdapterProperties: Scan Mode:20
,11-23 13:13:42.617  5802  5818 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-23 13:13:42.617  5802  5818 D bt_hci  : do_postload posting postload work item
11-23 13:13:42.617  5802  5822 I bt_hci  : event_postload
,11-23 13:13:42.617  5802  5822 I bt_vendor: sco_config_cb
11-23 13:13:42.617  5802  5822 I bt_hci  : sco_config_callback postload finished.
,11-23 13:13:42.621  5802  5818 D bt_bte_conf: Device ID record 1 : primary
11-23 13:13:42.621  5802  5818 D bt_bte_conf:   vendorId            = 000f
,11-23 13:13:42.621  5802  5818 D bt_bte_conf:   vendorIdSource      = 0001
11-23 13:13:42.622  5802  5818 D bt_bte_conf:   product             = 1200
,11-23 13:13:42.622  5802  5818 D bt_bte_conf:   version             = 1436
11-23 13:13:42.622  5802  5818 D bt_bte_conf:   clientExecutableURL = 
11-23 13:13:42.622  5802  5818 D bt_bte_conf:   serviceDescription  = 
,11-23 13:13:42.622  5802  5818 D bt_bte_conf:   documentationURL    = 
11-23 13:13:42.623  5802  5818 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-23 13:13:42.625  5802  5815 D bt_stack_manager: event_start_up_stack finished
,11-23 13:13:42.625  5802  5814 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-23 13:13:42.626  5802  5814 D BluetoothAdapterProperties: Setting state to 15
11-23 13:13:42.626  5802  5814 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,11-23 13:13:42.626  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 13:13:42.627  5802  5814 I BluetoothAdapterState: Entering BleOnState
11-23 13:13:42.631  5802  5822 I bt_vendor: low_power_mode_cb
,11-23 13:13:42.633  5802  5814 D BluetoothAdapterState: Current state: BLE ON, message: 1
,11-23 13:13:42.633  5802  5814 D BluetoothAdapterProperties: Setting state to 11
,11-23 13:13:42.633  5802  5814 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-23 13:13:42.639  5802  5802 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b98b1
11-23 13:13:42.641  5802  5802 D HeadsetService: Received start request. Starting profile...
11-23 13:13:42.642  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 13:13:42.644  5802  5802 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-23 13:13:42.644  5802  5802 D HeadsetStateMachine: make
,11-23 13:13:42.652  5802  5814 I BluetoothAdapterState: Entering PendingCommandState
,11-23 13:13:42.655  5802  5802 D HeadsetStateMachine: max_hf_connections = 1
,11-23 13:13:42.655  5802  5802 I bt_bluedroid: get_profile_interface handsfree
11-23 13:13:42.655  5802  5818 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
11-23 13:13:42.656  5802  5818 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-23 13:13:42.659  5802  5802 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b98b1
,11-23 13:13:42.660  5802  5802 D A2dpService: Received start request. Starting profile...
11-23 13:13:42.661  5802  5802 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-23 13:13:42.661  5802  5802 I bt_bluedroid: get_profile_interface avrcp
,11-23 13:13:42.667  5802  5802 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-23 13:13:42.667  5802  5802 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-23 13:13:42.667  5802  5802 D A2dpStateMachine: make
,11-23 13:13:42.669  5802  5802 I bt_bluedroid: get_profile_interface a2dp
,11-23 13:13:42.670  5802  5818 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,11-23 13:13:42.671  5802  5833 D A2dpStateMachine: Enter Disconnected: -2
,11-23 13:13:42.674  5802  5802 I BluetoothHidServiceJni: classInitNative: succeeds
,11-23 13:13:42.675  3563  3563 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-23 13:13:42.675  5802  5802 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b98b1
,11-23 13:13:42.678  5802  5802 D HidService: Received start request. Starting profile...
,11-23 13:13:42.678  5802  5802 I bt_bluedroid: get_profile_interface hidhost
11-23 13:13:42.679  5802  5802 D HidService: setHidService(): set to: null
11-23 13:13:42.679  5802  5818 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c4a56d
11-23 13:13:42.679  5802  5818 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-23 13:13:42.679  5802  5802 I BluetoothHealthServiceJni: classInitNative: succeeds
,11-23 13:13:42.680  5662  5662 D BluetoothInputDevice: Proxy object connected
,11-23 13:13:42.681  5662  5662 D HidProfile: Bluetooth service connected
11-23 13:13:42.682  5802  5802 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b98b1
11-23 13:13:42.683  5802  5802 D HealthService: Received start request. Starting profile...
,11-23 13:13:42.684  5802  5802 I bt_bluedroid: get_profile_interface health
,11-23 13:13:42.685  5802  5802 I BluetoothPanServiceJni: classInitNative(L105): succeeds
11-23 13:13:42.686  5802  5802 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b98b1
11-23 13:13:42.686  5662  5662 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 13:13:42.687  5802  5802 D PanService: Received start request. Starting profile...
11-23 13:13:42.687  5802  5802 D BluetoothPanServiceJni: initializeNative(L110): pan
11-23 13:13:42.687  5802  5802 I bt_bluedroid: get_profile_interface pan
11-23 13:13:42.687  5662  5662 D PanProfile: Bluetooth service connected
11-23 13:13:42.687  5802  5818 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,11-23 13:13:42.689  5802  5802 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b98b1
,11-23 13:13:42.690  5662  5662 D BluetoothMap: Proxy object connected
,11-23 13:13:42.690  5802  5802 D BluetoothMapService: Received start request. Starting profile...
11-23 13:13:42.691  5802  5802 D BluetoothMapService: start()
11-23 13:13:42.691  5662  5662 D MapProfile: Bluetooth service connected
11-23 13:13:42.691  5662  5662 D BluetoothMap: getConnectedDevices()
11-23 13:13:42.692  5662  5662 D BluetoothMap: Bluetooth is Not enabled
,11-23 13:13:42.693  5802  5802 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-23 13:13:42.694  5802  5802 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-23 13:13:42.694  5802  5802 D BluetoothMapAppObserver: createReceiver()
11-23 13:13:42.695  5802  5802 D BluetoothMapAppObserver: initObservers()
11-23 13:13:42.695  5802  5802 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-23 13:13:42.702  5802  5802 V SapService: SapBinder()
11-23 13:13:42.702  5802  5802 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b98b1
,11-23 13:13:42.703  5802  5802 D SapService: Received start request. Starting profile...
11-23 13:13:42.703  5802  5802 V SapService: start()
,11-23 13:13:42.705  5802  5802 V BluetoothAdapterState: isTurningOff()=false
,11-23 13:13:42.705  5802  5802 V BluetoothAdapterState: isTurningOn()=true
11-23 13:13:42.705  5802  5802 V BluetoothAdapterState: isBleTurningOn()=false
11-23 13:13:42.705  5802  5831 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-23 13:13:42.705  5802  5802 V BluetoothAdapterState: isBleTurningOff()=false
11-23 13:13:42.705  5802  5802 V BluetoothAdapterState: isTurningOff()=false
11-23 13:13:42.705  5802  5802 V BluetoothAdapterState: isTurningOn()=true
11-23 13:13:42.705  5802  5802 V BluetoothAdapterState: isBleTurningOn()=false
11-23 13:13:42.705  5802  5802 V BluetoothAdapterState: isBleTurningOff()=false
11-23 13:13:42.706  5802  5802 V BluetoothAdapterState: isTurningOff()=false
11-23 13:13:42.706  5802  5802 V BluetoothAdapterState: isTurningOn()=true
11-23 13:13:42.706  5802  5802 V BluetoothAdapterState: isBleTurningOn()=false
11-23 13:13:42.706  5802  5802 V BluetoothAdapterState: isBleTurningOff()=false
11-23 13:13:42.706  5802  5802 V BluetoothAdapterState: isTurningOff()=false
11-23 13:13:42.706  5802  5802 V BluetoothAdapterState: isTurningOn()=true
,11-23 13:13:42.706  5802  5802 V BluetoothAdapterState: isBleTurningOn()=false
11-23 13:13:42.706  5802  5802 V BluetoothAdapterState: isBleTurningOff()=false
11-23 13:13:42.706  5802  5802 V BluetoothAdapterState: isTurningOff()=false
11-23 13:13:42.706  5802  5802 V BluetoothAdapterState: isTurningOn()=true
11-23 13:13:42.706  5802  5802 V BluetoothAdapterState: isBleTurningOn()=false
11-23 13:13:42.706  5802  5802 V BluetoothAdapterState: isBleTurningOff()=false
11-23 13:13:42.706  5802  5802 V BluetoothAdapterState: isTurningOff()=false
11-23 13:13:42.706  5802  5802 V BluetoothAdapterState: isTurningOn()=true
11-23 13:13:42.706  5802  5802 V BluetoothAdapterState: isBleTurningOn()=false
11-23 13:13:42.706  5802  5802 V BluetoothAdapterState: isBleTurningOff()=false
11-23 13:13:42.708  5802  5802 V BluetoothAdapterState: isTurningOff()=false
11-23 13:13:42.708  5802  5802 V BluetoothAdapterState: isTurningOn()=true
11-23 13:13:42.708  5802  5802 V BluetoothAdapterState: isBleTurningOn()=false
11-23 13:13:42.708  5802  5802 V BluetoothAdapterState: isBleTurningOff()=false
11-23 13:13:42.708  5802  5814 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-23 13:13:42.709  5802  5814 D BluetoothAdapterProperties: ScanMode =  20
11-23 13:13:42.709  5802  5814 D BluetoothAdapterProperties: State =  11
,11-23 13:13:42.710  5802  5818 D BluetoothAdapterProperties: Scan Mode:21
,11-23 13:13:42.710  5802  5814 D BluetoothAdapterProperties: Setting state to 12
,11-23 13:13:42.710  5802  5814 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-23 13:13:42.711  5802  5818 D BluetoothAdapterProperties: Discoverable Timeout:120
11-23 13:13:42.711  5802  5814 I BluetoothAdapterState: Entering OnState
11-23 13:13:42.712  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-23 13:13:42.712  3106  3117 D BluetoothPbap: onBluetoothStateChange: up=true
11-23 13:13:42.714   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-23 13:13:42.714  5662  5678 D BluetoothPan: onBluetoothStateChange on: true
,11-23 13:13:42.715  5662  5674 D BluetoothMap: onBluetoothStateChange: up=true
11-23 13:13:42.715  3106  3123 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 13:13:42.716  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 13:13:42.716  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 13:13:42.716  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 13:13:42.716  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 13:13:42.716  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 13:13:42.716  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 13:13:42.716  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 13:13:42.716  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 13:13:42.716  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 13:13:42.717  3106  3966 D BluetoothPan: onBluetoothStateChange on: true
11-23 13:13:42.718  3106  3106 D BluetoothA2dp: Proxy object connected
,11-23 13:13:42.719   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 13:13:42.719  3106  3123 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 13:13:42.720  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 13:13:42.720  3106  3106 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 13:13:42.720  3106  3106 D PanProfile: Bluetooth service connected
11-23 13:13:42.720  5662  5678 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 13:13:42.720   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 13:13:42.720  5802  5802 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-23 13:13:42.720  3106  5604 D BluetoothMap: onBluetoothStateChange: up=true
11-23 13:13:42.721  5802  5802 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-23 13:13:42.722  3106  3106 D BluetoothMap: Proxy object connected
11-23 13:13:42.722  3790  3822 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-23 13:13:42.722  3106  3106 D MapProfile: Bluetooth service connected
11-23 13:13:42.722  3106  3106 D BluetoothMap: getConnectedDevices()
11-23 13:13:42.722  5802  5802 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 13:13:42.722  5662  5674 D BluetoothPbap: onBluetoothStateChange: up=true
11-23 13:13:42.723   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 13:13:42.724   928   928 D BluetoothA2dp: Proxy object connected
,11-23 13:13:42.724  5802  5802 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 13:13:42.724  3106  3966 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 13:13:42.725  5802  5802 D ObexServerSockets: Succeed to create listening sockets 
11-23 13:13:42.725  5802  5802 D ObexServerSockets0: startAccept()
11-23 13:13:42.725  5802  5802 D ObexServerSockets0: prepareForNewConnect()
11-23 13:13:42.725  3106  3106 D BluetoothInputDevice: Proxy object connected
11-23 13:13:42.725  3106  3106 D HidProfile: Bluetooth service connected
11-23 13:13:42.727   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
11-23 13:13:42.728  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: resolveFeatureSupport
11-23 13:13:42.729  5802  5802 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-23 13:13:42.729  5802  5802 D BluetoothSdpJni: SDP Create record success - handle: 0
11-23 13:13:42.730  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 13:13:42.731  5802  5802 D BluetoothMapService: onReceive
,11-23 13:13:42.731  5802  5840 D ObexServerSockets0: Accepting socket connection...
11-23 13:13:42.731  5802  5802 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 13:13:42.731  5802  5839 D ObexServerSockets0: Accepting socket connection...
11-23 13:13:42.731  5802  5802 D BluetoothMapService: STATE_ON
,11-23 13:13:42.732  5662  5662 D LocalBluetoothProfileManager: Adding local A2DP profile
,11-23 13:13:42.733  5802  5841 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 13:13:42.735  5802  5841 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-23 13:13:42.735  5802  5841 D BluetoothSdpJni: SDP Create record success - handle: 1
11-23 13:13:42.736  5662  5662 D LocalBluetoothProfileManager: Adding local HEADSET profile
,11-23 13:13:42.742  5662  5662 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 13:13:42.745  5662  5662 D BluetoothA2dp: Proxy object connected
,11-23 13:13:42.749  3563  3563 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 13:13:42.756  5662  5662 D DockEventReceiver: finishStartingService: stopping service
11-23 13:13:42.756  3106  3106 D BluetoothPbap: Proxy object connected
11-23 13:13:42.756  3106  3106 D PbapServerProfile: Bluetooth service connected
11-23 13:13:42.756  5802  5802 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-23 13:13:42.756  5802  5802 D ObexServerSockets0: prepareForNewConnect()
11-23 13:13:42.757  5662  5662 D BluetoothPbap: Proxy object connected
,11-23 13:13:42.758  5662  5662 D PbapServerProfile: Bluetooth service connected
,11-23 13:13:42.764  5802  5845 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 13:13:42.776  5802  5849 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 13:13:42.778  5802  5849 I BtOppRfcommListener: Accept thread started.
,11-23 13:13:42.816  3790  4024 D BluetoothHeadset: Proxy object connected
,11-23 13:13:42.817  3106  5604 D BluetoothHeadset: Proxy object connected
11-23 13:13:42.817  3106  3106 D HeadsetProfile: Bluetooth service connected
11-23 13:13:42.817   928   928 D BluetoothHeadset: Proxy object connected
11-23 13:13:42.817   928   928 D BluetoothHeadset: Proxy object connected
11-23 13:13:42.817   928   928 D BluetoothHeadset: Proxy object connected
,11-23 13:13:42.818   928   945 D BluetoothHeadset: Proxy object connected
,11-23 13:13:42.820  3106  3117 D BluetoothHeadset: Proxy object connected
,11-23 13:13:42.820  3106  3106 D HeadsetProfile: Bluetooth service connected
11-23 13:13:42.820   928   945 D BluetoothHeadset: Proxy object connected
,11-23 13:13:42.822  3790  3820 D BluetoothHeadset: Proxy object connected
,11-23 13:13:42.839  5662  5674 D BluetoothHeadset: Proxy object connected
,11-23 13:13:42.841  5662  5662 D HeadsetProfile: Bluetooth service connected
,11-23 13:13:43.357   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:13:44.300   928  2967 D ConnectivityService: handlePromptUnvalidated 101
,11-23 13:13:44.358   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:13:45.359   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:13:46.360   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 13:13:46.642  5802  5814 D BluetoothAdapterState: Current state: ON, message: 23
,11-23 13:13:46.642  5802  5814 D BluetoothAdapterProperties: Setting state to 13
11-23 13:13:46.642  5802  5814 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
11-23 13:13:46.643  5802  5814 D BluetoothAdapterProperties: onBluetoothDisable()
11-23 13:13:46.644  5802  5814 I BluetoothAdapterState: Entering PendingCommandState
,11-23 13:13:46.650  5802  5818 D BluetoothAdapterProperties: Scan Mode:20
,11-23 13:13:46.651  5802  5814 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,11-23 13:13:46.654  5802  5802 D BluetoothMapService: onReceive
11-23 13:13:46.654  5802  5802 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
11-23 13:13:46.655  5802  5802 D BluetoothMapService: STATE_TURNING_OFF
11-23 13:13:46.655  5802  5802 D BluetoothMapService: MAP Service closeService in
11-23 13:13:46.655  5802  5802 D BluetoothMapMasInstance0: MAP Service shutdown
11-23 13:13:46.655  5802  5802 D ObexServerSockets0: shutdown(block = true)
11-23 13:13:46.655  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,11-23 13:13:46.656  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 13:13:46.656  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 13:13:46.656  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 13:13:46.656  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 13:13:46.656  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
11-23 13:13:46.656  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 13:13:46.656  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 13:13:46.656  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 13:13:46.656  5605  5605 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
11-23 13:13:46.656  5802  5802 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 13:13:46.657  5802  5839 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
11-23 13:13:46.657  5605  5605 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
11-23 13:13:46.657  5802  5802 D ObexServerSockets0: shutdown called from another thread - interrupt().
11-23 13:13:46.657  5605  5605 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 13:13:46.657  5802  5840 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
11-23 13:13:46.657  5802  5827 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
11-23 13:13:46.660  5802  5802 I BtOppRfcommListener: stopping Accept Thread
11-23 13:13:46.660  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 13:13:46.661  5802  5849 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
11-23 13:13:46.661  5802  5849 I BtOppRfcommListener: BluetoothSocket listen thread finished
11-23 13:13:46.662  5662  5662 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 13:13:46.666  5802  5802 D HeadsetService: Received stop request...Stopping profile...
,11-23 13:13:46.668  3790  3822 D BluetoothHeadset: Proxy object disconnected
11-23 13:13:46.669  5802  5802 D A2dpService: Received stop request...Stopping profile...
11-23 13:13:46.670  5802  5833 D A2dpStateMachine: Exit Disconnected: -1
11-23 13:13:46.670  5662  5678 D BluetoothHeadset: Proxy object disconnected
11-23 13:13:46.671  3106  3117 D BluetoothHeadset: Proxy object disconnected
11-23 13:13:46.671   928   928 D BluetoothHeadset: Proxy object disconnected
11-23 13:13:46.671   928   928 D BluetoothHeadset: Proxy object disconnected
11-23 13:13:46.671   928   928 D BluetoothHeadset: Proxy object disconnected
11-23 13:13:46.671   928   928 D BluetoothA2dp: Proxy object disconnected
11-23 13:13:46.672  5802  5802 D HidService: Received stop request...Stopping profile...
11-23 13:13:46.672  5802  5802 D HidService: Stopping Bluetooth HidService
,11-23 13:13:46.675  5802  5802 D HealthService: Received stop request...Stopping profile...
,11-23 13:13:46.677  5802  5802 D PanService: Received stop request...Stopping profile...
,11-23 13:13:46.677  5662  5662 D DockEventReceiver: finishStartingService: stopping service
,11-23 13:13:46.678  5662  5662 D HeadsetProfile: Bluetooth service disconnected
11-23 13:13:46.679  5662  5662 D BluetoothA2dp: Proxy object disconnected
11-23 13:13:46.679  5662  5662 D BluetoothInputDevice: Proxy object disconnected
11-23 13:13:46.679  5662  5662 D HidProfile: Bluetooth service disconnected
11-23 13:13:46.679  5662  5662 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-23 13:13:46.680  5662  5662 D PanProfile: Bluetooth service disconnected
11-23 13:13:46.680  5802  5802 D BluetoothMapService: Received stop request...Stopping profile...
11-23 13:13:46.680  5802  5802 D BluetoothMapService: stop()
11-23 13:13:46.681  3106  3106 D HeadsetProfile: Bluetooth service disconnected
11-23 13:13:46.681  3106  3106 D BluetoothA2dp: Proxy object disconnected
11-23 13:13:46.681  3106  3106 D BluetoothInputDevice: Proxy object disconnected
11-23 13:13:46.681  3106  3106 D HidProfile: Bluetooth service disconnected
,11-23 13:13:46.681  3106  3106 D BluetoothPan: BluetoothPAN Proxy object disconnected
11-23 13:13:46.681  3106  3106 D PanProfile: Bluetooth service disconnected
11-23 13:13:46.681  5802  5802 D BluetoothMapAppObserver: deinitObservers()
11-23 13:13:46.681  5802  5802 D BluetoothMapAppObserver: removeReceiver()
11-23 13:13:46.683  3106  3106 D BluetoothMap: Proxy object disconnected
11-23 13:13:46.683  3106  3106 D MapProfile: Bluetooth service disconnected
11-23 13:13:46.683  5662  5662 D BluetoothMap: Proxy object disconnected
11-23 13:13:46.683  5662  5662 D MapProfile: Bluetooth service disconnected
11-23 13:13:46.684  5802  5802 D SapService: Received stop request...Stopping profile...
11-23 13:13:46.684  5802  5802 V SapService: stop()
11-23 13:13:46.685  5802  5802 V BluetoothAdapterState: isTurningOff()=true
11-23 13:13:46.685  5802  5802 V BluetoothAdapterState: isTurningOn()=false
11-23 13:13:46.685  5802  5802 V BluetoothAdapterState: isBleTurningOn()=false
11-23 13:13:46.685  5802  5802 V BluetoothAdapterState: isBleTurningOff()=false
11-23 13:13:46.687  5802  5802 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
11-23 13:13:46.687  5802  5802 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
11-23 13:13:46.687  5802  5825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 13:13:46.687  5802  5825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 13:13:46.687  5802  5825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 13:13:46.687  5802  5802 V BluetoothAdapterState: isTurningOff()=true
11-23 13:13:46.687  5802  5802 V BluetoothAdapterState: isTurningOn()=false
,11-23 13:13:46.688  5802  5802 V BluetoothAdapterState: isBleTurningOn()=false
11-23 13:13:46.688  5802  5802 V BluetoothAdapterState: isBleTurningOff()=false
11-23 13:13:46.688  5802  5818 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
,11-23 13:13:46.688  5802  5818 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
11-23 13:13:46.689  5802  5818 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
11-23 13:13:46.689  5802  5825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 13:13:46.689  5802  5802 V BluetoothAdapterState: isTurningOff()=true
11-23 13:13:46.689  5802  5802 V BluetoothAdapterState: isTurningOn()=false
11-23 13:13:46.689  5802  5802 V BluetoothAdapterState: isBleTurningOn()=false
11-23 13:13:46.689  5802  5802 V BluetoothAdapterState: isBleTurningOff()=false
11-23 13:13:46.689  5802  5825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 13:13:46.689  5802  5825 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 13:13:46.689  5802  5825 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 13:13:46.689  5802  5825 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
11-23 13:13:46.689  5802  5825 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
11-23 13:13:46.690  5802  5802 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
11-23 13:13:46.690  5802  5802 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
,11-23 13:13:46.690  5802  5802 V BluetoothAdapterState: isTurningOff()=true
11-23 13:13:46.690  5802  5818 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
11-23 13:13:46.691  5802  5802 V BluetoothAdapterState: isTurningOn()=false
11-23 13:13:46.691  5802  5802 V BluetoothAdapterState: isBleTurningOn()=false
11-23 13:13:46.691  5802  5802 V BluetoothAdapterState: isBleTurningOff()=false
11-23 13:13:46.691  5802  5802 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
11-23 13:13:46.691  5802  5818 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
11-23 13:13:46.691  5802  5802 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
11-23 13:13:46.691  3563  3563 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-23 13:13:46.691  5802  5802 V BluetoothAdapterState: isTurningOff()=true
11-23 13:13:46.692  5802  5802 V BluetoothAdapterState: isTurningOn()=false
11-23 13:13:46.692  5802  5802 V BluetoothAdapterState: isBleTurningOn()=false
11-23 13:13:46.692  5802  5802 V BluetoothAdapterState: isBleTurningOff()=false
11-23 13:13:46.692  5802  5802 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
11-23 13:13:46.692  5802  5802 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,11-23 13:13:46.693  5802  5802 D BluetoothMapService: MAP Service closeService in
,11-23 13:13:46.693  5802  5802 V BluetoothAdapterState: isTurningOff()=true
11-23 13:13:46.693  5802  5802 V BluetoothAdapterState: isTurningOn()=false
11-23 13:13:46.693  5802  5802 V BluetoothAdapterState: isBleTurningOn()=false
11-23 13:13:46.693  5802  5802 V BluetoothAdapterState: isBleTurningOff()=false
11-23 13:13:46.693  5802  5802 D BluetoothMapService: cleanup()
11-23 13:13:46.693  5802  5802 D BluetoothMapService: MAP Service closeService in
11-23 13:13:46.694  5802  5802 V BluetoothAdapterState: isTurningOff()=true
11-23 13:13:46.694  5802  5802 V BluetoothAdapterState: isTurningOn()=false
11-23 13:13:46.694  5802  5802 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 13:13:46.694  5802  5802 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 13:13:46.703  5802  5814 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
11-23 13:13:46.703  5802  5814 D BluetoothAdapterProperties: Setting state to 15
11-23 13:13:46.703  5802  5814 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
11-23 13:13:46.704  3106  3966 D BluetoothPbap: onBluetoothStateChange: up=false
11-23 13:13:46.704  5802  5814 I BluetoothAdapterState: Entering BleOnState
11-23 13:13:46.705  5662  5662 D BluetoothPbap: Proxy object disconnected
11-23 13:13:46.705  5662  5662 D PbapServerProfile: Bluetooth service disconnected
11-23 13:13:46.708   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
,11-23 13:13:46.708  5662  5674 D BluetoothPan: onBluetoothStateChange on: false
,11-23 13:13:46.710  5662  5678 D BluetoothMap: onBluetoothStateChange: up=false
11-23 13:13:46.710  3106  3117 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 13:13:46.711  3106  3123 D BluetoothPan: onBluetoothStateChange on: false
11-23 13:13:46.711   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 13:13:46.711  3106  5604 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 13:13:46.711  5662  5674 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-23 13:13:46.712   928   945 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 13:13:46.712  5662  5678 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 13:13:46.712  3106  3966 D BluetoothMap: onBluetoothStateChange: up=false
11-23 13:13:46.712  3790  4024 D BluetoothHeadset: onBluetoothStateChange: up=false
11-23 13:13:46.713  5662  5674 D BluetoothA2dp: onBluetoothStateChange: up=false
,11-23 13:13:46.713  5662  5678 D BluetoothPbap: onBluetoothStateChange: up=false
11-23 13:13:46.714   928   945 D BluetoothA2dp: onBluetoothStateChange: up=false
11-23 13:13:46.714  3106  3117 D BluetoothInputDevice: onBluetoothStateChange: up=false
11-23 13:13:46.715  5802  5814 D BluetoothAdapterState: Current state: BLE ON, message: 20
11-23 13:13:46.715  5802  5814 D BluetoothAdapterProperties: Setting state to 16
11-23 13:13:46.715  5802  5814 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
11-23 13:13:46.716  5802  5814 D BluetoothAdapterProperties: onBleDisable
11-23 13:13:46.716  5802  5814 I BluetoothAdapterState: Entering PendingCommandState
11-23 13:13:46.716  5802  5815 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
,11-23 13:13:46.717  5802  5825 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
11-23 13:13:46.717  5802  5825 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
11-23 13:13:46.719  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
11-23 13:13:46.719  5662  5662 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
11-23 13:13:46.719  5802  5818 D BluetoothAdapterProperties: Scan Mode:20
,11-23 13:13:46.722  5605  5605 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 13:13:46.724  3563  3563 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
11-23 13:13:46.724  5662  5662 D DockEventReceiver: finishStartingService: stopping service
,11-23 13:13:46.927  5802  5818 I bt_hci  : shut_down
,11-23 13:13:46.937  5802  5822 D bt_hwcfg: hw_epilog_process
,11-23 13:13:46.938  5802  5822 I bt_vendor: low_power_mode_cb
,11-23 13:13:46.941  5802  5822 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
11-23 13:13:46.941  5802  5822 I bt_vendor: epilog_cb
11-23 13:13:46.941  5802  5822 I bt_hci  : epilog_finished_callback
,11-23 13:13:46.943  5802  5818 I bt_hci_h4: hal_close
,11-23 13:13:46.944  5802  5818 I bt_userial_vendor: device fd = 54 close
,11-23 13:13:47.055  5802  5815 D bt_stack_manager: event_shut_down_stack finished.
,11-23 13:13:47.056  5802  5814 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,11-23 13:13:47.062  5802  5802 D BtGatt.DebugUtils: handleDebugAction() action=null
,11-23 13:13:47.062  5802  5814 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
,11-23 13:13:47.063  5802  5802 D BtGatt.GattService: Received stop request...Stopping profile...
11-23 13:13:47.063  5802  5802 D BtGatt.GattService: stop()
11-23 13:13:47.063  5802  5802 D BtGatt.AdvertiseManager: advertise clients cleared
11-23 13:13:47.067  5802  5802 V BluetoothAdapterState: isTurningOff()=false
11-23 13:13:47.068  5802  5802 V BluetoothAdapterState: isTurningOn()=false
11-23 13:13:47.068  5802  5802 V BluetoothAdapterState: isBleTurningOn()=false
11-23 13:13:47.068  5802  5802 V BluetoothAdapterState: isBleTurningOff()=true
11-23 13:13:47.068  5802  5814 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,11-23 13:13:47.069  5802  5814 D BluetoothAdapterProperties: Setting state to 10
11-23 13:13:47.069  5802  5814 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
11-23 13:13:47.070  5802  5814 I BluetoothAdapterState: Entering OffState
,11-23 13:13:47.071   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,11-23 13:13:47.087  5802  5802 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,11-23 13:13:47.087  5802  5802 W BluetoothSdpJni: Cleaning up Bluetooth Health object
11-23 13:13:47.087  5802  5802 I BluetoothServiceJni: cleanupNative: return from cleanup
11-23 13:13:47.090  5802  5815 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
,11-23 13:13:47.098  5802  5802 I art     : System.exit called, status: 0
,11-23 13:13:47.099  5802  5802 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,11-23 13:13:47.130   928   938 I ActivityManager: Process com.android.bluetooth (pid 5802) has died
,11-23 13:13:51.642  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
11-23 13:13:51.642  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,11-23 13:13:51.650  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,11-23 13:13:51.650  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e8ca896 removed from the list
11-23 13:13:51.651  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
11-23 13:13:51.653  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 13:13:51.653  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d8381ed added. We now have 4 listener(s)
11-23 13:13:51.653  5605  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 13:13:51.655  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:13:51.656  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@d8381ed removed from the list
,11-23 13:13:51.656  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 13:13:51.659  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 13:13:51.660  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ce2b822 added. We now have 4 listener(s)
11-23 13:13:51.661  5605  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 13:13:56.361   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:13:56.672  5605  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 13:13:56.704   928   945 I ActivityManager: Start proc 5859:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,11-23 13:13:56.789  5859  5859 D AdapterServiceConfig: Adding HeadsetService
,11-23 13:13:56.789  5859  5859 D AdapterServiceConfig: Adding A2dpService
11-23 13:13:56.789  5859  5859 D AdapterServiceConfig: Adding HidService
11-23 13:13:56.789  5859  5859 D AdapterServiceConfig: Adding HealthService
,11-23 13:13:56.790  5859  5859 D AdapterServiceConfig: Adding PanService
11-23 13:13:56.790  5859  5859 D AdapterServiceConfig: Adding GattService
,11-23 13:13:56.790  5859  5859 D AdapterServiceConfig: Adding BluetoothMapService
11-23 13:13:56.790  5859  5859 D AdapterServiceConfig: Adding SapService
,11-23 13:13:56.800   928   945 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@c9f2eb:true
,11-23 13:13:56.800  5859  5859 D BluetoothAdapterState: make() - Creating AdapterState
,11-23 13:13:56.803  5859  5859 I bt_bluedroid: init
,11-23 13:13:56.804  5859  5871 I BluetoothAdapterState: Entering OffState
,11-23 13:13:56.806  5859  5872 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
,11-23 13:13:56.806  5859  5872 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
11-23 13:13:56.806  5859  5872 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
11-23 13:13:56.806  5859  5872 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
11-23 13:13:56.807  5859  5859 I bt_bluedroid: get_profile_interface socket
,11-23 13:13:56.810  5859  5875 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-23 13:13:56.810  5859  5859 I bt_bluedroid: get_profile_interface sdp
11-23 13:13:56.811  5859  5875 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 13:13:56.815  5859  5870 I bt_bluedroid: config_hci_snoop_log
,11-23 13:13:56.816   928   945 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,11-23 13:13:56.821  5859  5871 D BluetoothAdapterState: Current state: OFF, message: 0
,11-23 13:13:56.821  5859  5871 D BluetoothAdapterProperties: Setting state to 14
11-23 13:13:56.821  5859  5871 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
11-23 13:13:56.822  5859  5871 D BluetoothBondStateMachine: make
,11-23 13:13:56.824  5859  5876 I BluetoothBondStateMachine: StableState(): Entering Off State
,11-23 13:13:56.826  5859  5871 I BluetoothAdapterState: Entering PendingCommandState
,11-23 13:13:56.827  5859  5859 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,11-23 13:13:56.829  5859  5859 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b98b1
11-23 13:13:56.829  5859  5859 D BtGatt.DebugUtils: handleDebugAction() action=null
11-23 13:13:56.830  5859  5859 D BtGatt.GattService: Received start request. Starting profile...
11-23 13:13:56.830  5859  5859 D BtGatt.GattService: start()
,11-23 13:13:56.830  5859  5859 I bt_bluedroid: get_profile_interface gatt
11-23 13:13:56.831  5859  5859 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b98b1
11-23 13:13:56.831  5859  5859 D BtGatt.AdvertiseManager: advertise manager created
,11-23 13:13:56.835  5859  5859 V BluetoothAdapterState: isTurningOff()=false
,11-23 13:13:56.835  5859  5859 V BluetoothAdapterState: isTurningOn()=false
11-23 13:13:56.835  5859  5859 V BluetoothAdapterState: isBleTurningOn()=true
11-23 13:13:56.836  5859  5859 V BluetoothAdapterState: isBleTurningOff()=false
11-23 13:13:56.836  5859  5871 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
,11-23 13:13:56.837  5859  5871 I bt_bluedroid: bt_bluedroid
11-23 13:13:56.838  5859  5872 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,11-23 13:13:56.838  5859  5872 I bt_hci  : start_up
,11-23 13:13:56.842  5859  5872 I bt_vendor: alloc value 0xf3ceb871
11-23 13:13:56.843  5859  5872 I bt_vendor: init
11-23 13:13:56.843  5859  5872 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
11-23 13:13:56.843  5859  5872 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,11-23 13:13:56.950  5859  5872 D bt_hci  : start_up starting async portion
11-23 13:13:56.950  5859  5879 I bt_hci  : event_finish_startup
11-23 13:13:56.950  5859  5879 I bt_hci_h4: hal_open
11-23 13:13:56.950  5859  5879 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,11-23 13:13:56.947  5880  5880 W irq/448-msm_hs_: type=1400 audit(0.0:115): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 13:13:56.952  5859  5879 I bt_userial_vendor: device fd = 54 open
,11-23 13:13:56.965  5859  5879 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 13:13:56.968  5859  5879 D bt_hwcfg: Chipset BCM4358A3
11-23 13:13:56.969  5859  5879 D bt_hwcfg: Target name = [BCM4358A3]
11-23 13:13:56.969  5859  5879 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,11-23 13:13:57.362   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:13:57.492  5859  5879 I bt_hwcfg: bt vendor lib: set UART baud 115200
,11-23 13:13:57.493  5859  5879 D bt_hwcfg: Settlement delay -- 100 ms
,11-23 13:13:57.493  5859  5879 I bt_hwcfg: Setting fw settlement delay to 100 
,11-23 13:13:57.627  5859  5879 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,11-23 13:13:57.627  5859  5879 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
11-23 13:13:57.630  5859  5879 I bt_hwcfg: vendor lib fwcfg completed
11-23 13:13:57.630  5859  5879 I bt_vendor: firmware callback
,11-23 13:13:57.630  5859  5879 I bt_hci  : firmware_config_callback
,11-23 13:13:57.640  5859  5882 I bt_btu  : btu_task pending for preload complete event
,11-23 13:13:57.641  5859  5882 I bt_btu_task: Bluetooth chip preload is complete
,11-23 13:13:57.641  5859  5882 I bt_btu  : btu_task received preload complete event
,11-23 13:13:57.646  5859  5882 I         : BTE_InitTraceLevels -- TRC_HCI
,11-23 13:13:57.646  5859  5882 I         : BTE_InitTraceLevels -- TRC_L2CAP
11-23 13:13:57.646  5859  5882 I         : BTE_InitTraceLevels -- TRC_RFCOMM
,11-23 13:13:57.647  5859  5882 I         : BTE_InitTraceLevels -- TRC_AVDT
,11-23 13:13:57.647  5859  5882 I         : BTE_InitTraceLevels -- TRC_AVRC
11-23 13:13:57.647  5859  5882 I         : BTE_InitTraceLevels -- TRC_A2D
,11-23 13:13:57.647  5859  5882 I         : BTE_InitTraceLevels -- TRC_BNEP
,11-23 13:13:57.647  5859  5882 I         : BTE_InitTraceLevels -- TRC_BTM
11-23 13:13:57.647  5859  5882 I         : BTE_InitTraceLevels -- TRC_GAP
,11-23 13:13:57.647  5859  5882 I         : BTE_InitTraceLevels -- TRC_PAN
11-23 13:13:57.647  5859  5882 I         : BTE_InitTraceLevels -- TRC_SDP
11-23 13:13:57.647  5859  5882 I         : BTE_InitTraceLevels -- TRC_GATT
,11-23 13:13:57.648  5859  5882 I         : BTE_InitTraceLevels -- TRC_SMP
11-23 13:13:57.648  5859  5882 I         : BTE_InitTraceLevels -- TRC_BTAPP
11-23 13:13:57.648  5859  5882 I         : BTE_InitTraceLevels -- TRC_BTIF
,11-23 13:13:57.742  5859  5882 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3c69549
,11-23 13:13:57.742  5859  5882 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3c69549 
,11-23 13:13:57.772  5859  5875 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,11-23 13:13:57.774  5859  5875 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,11-23 13:13:57.774  5859  5875 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,11-23 13:13:57.777  5859  5875 D BluetoothAdapterProperties: Name is: Nexus 6P
,11-23 13:13:57.779  5859  5875 D BluetoothAdapterProperties: Scan Mode:20
,11-23 13:13:57.780  5859  5875 D BluetoothAdapterProperties: Discoverable Timeout:120
,11-23 13:13:57.780  5859  5875 D bt_hci  : do_postload posting postload work item
,11-23 13:13:57.780  5859  5879 I bt_hci  : event_postload
11-23 13:13:57.780  5859  5879 I bt_vendor: sco_config_cb
,11-23 13:13:57.781  5859  5879 I bt_hci  : sco_config_callback postload finished.
,11-23 13:13:57.787  5859  5875 D bt_bte_conf: Device ID record 1 : primary
,11-23 13:13:57.787  5859  5875 D bt_bte_conf:   vendorId            = 000f
11-23 13:13:57.787  5859  5875 D bt_bte_conf:   vendorIdSource      = 0001
11-23 13:13:57.787  5859  5875 D bt_bte_conf:   product             = 1200
11-23 13:13:57.787  5859  5875 D bt_bte_conf:   version             = 1436
11-23 13:13:57.787  5859  5875 D bt_bte_conf:   clientExecutableURL = 
11-23 13:13:57.787  5859  5875 D bt_bte_conf:   serviceDescription  = 
11-23 13:13:57.787  5859  5875 D bt_bte_conf:   documentationURL    = 
11-23 13:13:57.787  5859  5875 D bt_bte_conf: bte_load_did_conf no section named DID2.
11-23 13:13:57.788  5859  5872 D bt_stack_manager: event_start_up_stack finished
11-23 13:13:57.788  5859  5871 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
11-23 13:13:57.789  5859  5871 D BluetoothAdapterProperties: Setting state to 15
11-23 13:13:57.789  5859  5871 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,11-23 13:13:57.789  5859  5879 I bt_vendor: low_power_mode_cb
11-23 13:13:57.790  5859  5871 I BluetoothAdapterState: Entering BleOnState
,11-23 13:13:57.794  5859  5871 D BluetoothAdapterState: Current state: BLE ON, message: 1
11-23 13:13:57.794  5859  5871 D BluetoothAdapterProperties: Setting state to 11
11-23 13:13:57.795  5859  5871 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,11-23 13:13:57.801  5859  5859 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b98b1
,11-23 13:13:57.804  5859  5859 D HeadsetService: Received start request. Starting profile...
,11-23 13:13:57.807  5859  5859 I BluetoothHeadsetServiceJni: classInitNative: succeeds
11-23 13:13:57.807  5859  5859 D HeadsetStateMachine: make
,11-23 13:13:57.819  5859  5871 I BluetoothAdapterState: Entering PendingCommandState
,11-23 13:13:57.820  5859  5859 D HeadsetStateMachine: max_hf_connections = 1
11-23 13:13:57.820  5859  5859 I bt_bluedroid: get_profile_interface handsfree
11-23 13:13:57.820  5859  5875 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
,11-23 13:13:57.821  5859  5875 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,11-23 13:13:57.824  5859  5859 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b98b1
11-23 13:13:57.824  5859  5859 D A2dpService: Received start request. Starting profile...
11-23 13:13:57.825  5859  5859 I BluetoothAvrcpServiceJni: classInitNative: succeeds
11-23 13:13:57.825  5859  5859 I bt_bluedroid: get_profile_interface avrcp
,11-23 13:13:57.831  5859  5859 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,11-23 13:13:57.832  5859  5859 I BluetoothA2dpServiceJni: classInitNative: succeeds
11-23 13:13:57.832  5859  5859 D A2dpStateMachine: make
,11-23 13:13:57.833  5859  5859 I bt_bluedroid: get_profile_interface a2dp
,11-23 13:13:57.835  5859  5875 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
11-23 13:13:57.836  5859  5889 D A2dpStateMachine: Enter Disconnected: -2
11-23 13:13:57.836  5859  5859 I BluetoothHidServiceJni: classInitNative: succeeds
,11-23 13:13:57.837  5859  5859 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b98b1
11-23 13:13:57.837  5859  5859 D HidService: Received start request. Starting profile...
11-23 13:13:57.837  5859  5859 I bt_bluedroid: get_profile_interface hidhost
11-23 13:13:57.838  5859  5859 D HidService: setHidService(): set to: null
11-23 13:13:57.838  5859  5875 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3c4a56d
11-23 13:13:57.838  5859  5875 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
11-23 13:13:57.839  5859  5859 I BluetoothHealthServiceJni: classInitNative: succeeds
11-23 13:13:57.840  5859  5859 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b98b1
11-23 13:13:57.841  5859  5859 D HealthService: Received start request. Starting profile...
,11-23 13:13:57.842  3563  3563 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 13:13:57.844  5859  5859 I bt_bluedroid: get_profile_interface health
11-23 13:13:57.846  5859  5859 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,11-23 13:13:57.847  5859  5859 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b98b1
,11-23 13:13:57.847  5859  5859 D PanService: Received start request. Starting profile...
11-23 13:13:57.848  5859  5859 D BluetoothPanServiceJni: initializeNative(L110): pan
,11-23 13:13:57.848  5859  5859 I bt_bluedroid: get_profile_interface pan
11-23 13:13:57.849  5859  5875 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
11-23 13:13:57.850  5859  5859 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b98b1
11-23 13:13:57.851  5859  5859 D BluetoothMapService: Received start request. Starting profile...
11-23 13:13:57.851  5859  5859 D BluetoothMapService: start()
,11-23 13:13:57.855  5859  5859 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,11-23 13:13:57.860  5859  5859 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
11-23 13:13:57.860  5859  5859 D BluetoothMapAppObserver: createReceiver()
11-23 13:13:57.862  5859  5859 D BluetoothMapAppObserver: initObservers()
11-23 13:13:57.862  5859  5859 D BluetoothMapAppObserver: getEnabledAccountItems()
,11-23 13:13:57.867  5859  5859 V SapService: SapBinder()
11-23 13:13:57.868  5859  5859 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b98b1
,11-23 13:13:57.868  5859  5859 D SapService: Received start request. Starting profile...
,11-23 13:13:57.868  5859  5859 V SapService: start()
11-23 13:13:57.870  5859  5859 V BluetoothAdapterState: isTurningOff()=false
11-23 13:13:57.870  5859  5859 V BluetoothAdapterState: isTurningOn()=true
11-23 13:13:57.870  5859  5859 V BluetoothAdapterState: isBleTurningOn()=false
11-23 13:13:57.870  5859  5859 V BluetoothAdapterState: isBleTurningOff()=false
11-23 13:13:57.870  5859  5859 V BluetoothAdapterState: isTurningOff()=false
11-23 13:13:57.870  5859  5887 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
11-23 13:13:57.870  5859  5859 V BluetoothAdapterState: isTurningOn()=true
,11-23 13:13:57.870  5859  5859 V BluetoothAdapterState: isBleTurningOn()=false
11-23 13:13:57.870  5859  5859 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 13:13:57.871  5859  5859 V BluetoothAdapterState: isTurningOff()=false
11-23 13:13:57.871  5859  5859 V BluetoothAdapterState: isTurningOn()=true
11-23 13:13:57.871  5859  5859 V BluetoothAdapterState: isBleTurningOn()=false
11-23 13:13:57.871  5859  5859 V BluetoothAdapterState: isBleTurningOff()=false
11-23 13:13:57.872  5859  5859 V BluetoothAdapterState: isTurningOff()=false
11-23 13:13:57.872  5859  5859 V BluetoothAdapterState: isTurningOn()=true
11-23 13:13:57.872  5859  5859 V BluetoothAdapterState: isBleTurningOn()=false
11-23 13:13:57.872  5859  5859 V BluetoothAdapterState: isBleTurningOff()=false
11-23 13:13:57.872  5859  5859 V BluetoothAdapterState: isTurningOff()=false
11-23 13:13:57.872  5859  5859 V BluetoothAdapterState: isTurningOn()=true
11-23 13:13:57.872  5859  5859 V BluetoothAdapterState: isBleTurningOn()=false
,11-23 13:13:57.872  5859  5859 V BluetoothAdapterState: isBleTurningOff()=false
11-23 13:13:57.873  5859  5859 V BluetoothAdapterState: isTurningOff()=false
11-23 13:13:57.874  5859  5859 V BluetoothAdapterState: isTurningOn()=true
11-23 13:13:57.874  5859  5859 V BluetoothAdapterState: isBleTurningOn()=false
11-23 13:13:57.874  5859  5859 V BluetoothAdapterState: isBleTurningOff()=false
11-23 13:13:57.874  5859  5859 V BluetoothAdapterState: isTurningOff()=false
11-23 13:13:57.874  5859  5859 V BluetoothAdapterState: isTurningOn()=true
11-23 13:13:57.874  5859  5859 V BluetoothAdapterState: isBleTurningOn()=false
11-23 13:13:57.874  5859  5859 V BluetoothAdapterState: isBleTurningOff()=false
,11-23 13:13:57.875  5859  5871 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
11-23 13:13:57.875  5859  5871 D BluetoothAdapterProperties: ScanMode =  20
11-23 13:13:57.875  5859  5871 D BluetoothAdapterProperties: State =  11
11-23 13:13:57.875  5859  5871 D BluetoothAdapterProperties: Setting state to 12
11-23 13:13:57.875  5859  5871 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
11-23 13:13:57.876  3106  3117 D BluetoothPbap: onBluetoothStateChange: up=true
11-23 13:13:57.878  5859  5871 I BluetoothAdapterState: Entering OnState
11-23 13:13:57.878  5859  5875 D BluetoothAdapterProperties: Scan Mode:21
11-23 13:13:57.878  5859  5875 D BluetoothAdapterProperties: Discoverable Timeout:120
11-23 13:13:57.878   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 13:13:57.879  5662  5674 D BluetoothPan: onBluetoothStateChange on: true
,11-23 13:13:57.881  5662  5678 D BluetoothMap: onBluetoothStateChange: up=true
,11-23 13:13:57.884  3106  5604 D BluetoothA2dp: onBluetoothStateChange: up=true
,11-23 13:13:57.886  3106  3123 D BluetoothPan: onBluetoothStateChange on: true
11-23 13:13:57.887  3106  3106 D BluetoothA2dp: Proxy object connected
11-23 13:13:57.887  5859  5859 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-23 13:13:57.887  5859  5859 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
11-23 13:13:57.888   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 13:13:57.888  3106  3117 D BluetoothHeadset: onBluetoothStateChange: up=true
,11-23 13:13:57.888  3106  3106 D BluetoothPan: BluetoothPAN Proxy object connected
11-23 13:13:57.888  3106  3106 D PanProfile: Bluetooth service connected
11-23 13:13:57.888  5662  5678 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 13:13:57.889  5859  5859 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 13:13:57.889  5662  5662 D BluetoothPan: BluetoothPAN Proxy object connected
,11-23 13:13:57.890  5662  5662 D PanProfile: Bluetooth service connected
11-23 13:13:57.890  5662  5662 D BluetoothMap: Proxy object connected
11-23 13:13:57.890  5662  5662 D MapProfile: Bluetooth service connected
,11-23 13:13:57.890  5662  5662 D BluetoothMap: getConnectedDevices()
11-23 13:13:57.891  5859  5859 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
11-23 13:13:57.891   928   945 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 13:13:57.892  5662  5674 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 13:13:57.892  5859  5859 D ObexServerSockets: Succeed to create listening sockets 
11-23 13:13:57.892  5859  5859 D ObexServerSockets0: startAccept()
11-23 13:13:57.892  5859  5859 D ObexServerSockets0: prepareForNewConnect()
11-23 13:13:57.892  3106  5604 D BluetoothMap: onBluetoothStateChange: up=true
11-23 13:13:57.894  5859  5859 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
11-23 13:13:57.894  5859  5859 D BluetoothSdpJni: SDP Create record success - handle: 0
,11-23 13:13:57.895  3106  3106 D BluetoothMap: Proxy object connected
11-23 13:13:57.895  3106  3106 D MapProfile: Bluetooth service connected
11-23 13:13:57.895  3790  3820 D BluetoothHeadset: onBluetoothStateChange: up=true
11-23 13:13:57.895  3106  3106 D BluetoothMap: getConnectedDevices()
11-23 13:13:57.895  5662  5678 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 13:13:57.896  5859  5895 D ObexServerSockets0: Accepting socket connection...
11-23 13:13:57.897  5859  5896 D ObexServerSockets0: Accepting socket connection...
11-23 13:13:57.898  5662  5894 D BluetoothPbap: onBluetoothStateChange: up=true
11-23 13:13:57.899  5662  5662 D BluetoothInputDevice: Proxy object connected
11-23 13:13:57.900  5662  5662 D HidProfile: Bluetooth service connected
,11-23 13:13:57.901   928   945 D BluetoothA2dp: onBluetoothStateChange: up=true
11-23 13:13:57.901   928   928 D BluetoothA2dp: Proxy object connected
11-23 13:13:57.901  3106  3966 D BluetoothInputDevice: onBluetoothStateChange: up=true
11-23 13:13:57.903  3106  3106 D BluetoothInputDevice: Proxy object connected
,11-23 13:13:57.904  3106  3106 D HidProfile: Bluetooth service connected
11-23 13:13:57.904  5662  5662 D BluetoothA2dp: Proxy object connected
11-23 13:13:57.905  5859  5859 D BluetoothMapService: onReceive
11-23 13:13:57.905  5859  5859 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
,11-23 13:13:57.905  5859  5859 D BluetoothMapService: STATE_ON
,11-23 13:13:57.905   928   928 I Telecom : BluetoothPhoneService: queryPhoneState
,11-23 13:13:57.909  5859  5899 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 13:13:57.910  5859  5899 D BluetoothSdpJni: sdpCreateSapsRecordNative:
11-23 13:13:57.910  5859  5899 D BluetoothSdpJni: SDP Create record success - handle: 1
11-23 13:13:57.913  5662  5662 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,11-23 13:13:57.922  3563  3563 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,11-23 13:13:57.922  5662  5662 D DockEventReceiver: finishStartingService: stopping service
,11-23 13:13:57.928  5859  5859 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
11-23 13:13:57.929  5859  5859 D ObexServerSockets0: prepareForNewConnect()
,11-23 13:13:57.931  5662  5662 D BluetoothPbap: Proxy object connected
11-23 13:13:57.931  5662  5662 D PbapServerProfile: Bluetooth service connected
11-23 13:13:57.932  3106  3106 D BluetoothPbap: Proxy object connected
11-23 13:13:57.932  3106  3106 D PbapServerProfile: Bluetooth service connected
,11-23 13:13:57.937  5859  5903 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 13:13:57.951  5859  5907 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,11-23 13:13:57.952  5859  5907 I BtOppRfcommListener: Accept thread started.
,11-23 13:13:57.981  3790  3822 D BluetoothHeadset: Proxy object connected
,11-23 13:13:57.981  5662  5894 D BluetoothHeadset: Proxy object connected
11-23 13:13:57.982  3106  5604 D BluetoothHeadset: Proxy object connected
11-23 13:13:57.982  3106  3106 D HeadsetProfile: Bluetooth service connected
11-23 13:13:57.982   928   928 D BluetoothHeadset: Proxy object connected
11-23 13:13:57.982   928   928 D BluetoothHeadset: Proxy object connected
11-23 13:13:57.982   928   928 D BluetoothHeadset: Proxy object connected
,11-23 13:13:57.983  5662  5662 D HeadsetProfile: Bluetooth service connected
,11-23 13:13:57.989   928   945 D BluetoothHeadset: Proxy object connected
,11-23 13:13:57.989  3106  3123 D BluetoothHeadset: Proxy object connected
11-23 13:13:57.989  3106  3106 D HeadsetProfile: Bluetooth service connected
,11-23 13:13:57.991   928   945 D BluetoothHeadset: Proxy object connected
,11-23 13:13:57.993  5662  5674 D BluetoothHeadset: Proxy object connected
,11-23 13:13:57.993  5662  5662 D HeadsetProfile: Bluetooth service connected
,11-23 13:13:57.995  3790  4024 D BluetoothHeadset: Proxy object connected
,11-23 13:13:58.364   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:13:59.365   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:14:00.366   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:14:01.367   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-23 13:14:01.691  5605  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 13:14:01.691  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 13:14:01.691  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 13:14:01.691  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
11-23 13:14:01.691  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 13:14:01.691  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
11-23 13:14:01.691  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - SSID name: null
11-23 13:14:01.691  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
11-23 13:14:01.691  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,11-23 13:14:01.696  5605  5653 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null, SSID name: null
11-23 13:14:01.697  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:14:01.697  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ce2b822 removed from the list
11-23 13:14:01.697  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
,11-23 13:14:01.699  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 13:14:01.699  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ceef2b3 added. We now have 4 listener(s)
,11-23 13:14:01.699  5605  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 13:14:01.702   928  3837 D WifiService: setWifiEnabled: false pid=5605, uid=10077
11-23 13:14:01.702   928  3837 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 13:14:06.712  5605  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,11-23 13:14:06.714   928  3841 D WifiService: setWifiEnabled: true pid=5605, uid=10077
,11-23 13:14:06.714   928  3841 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,11-23 13:14:06.722   507   920 D SoftapController: Softap fwReload - Ok
,11-23 13:14:06.727   507   920 D CommandListener: Setting iface cfg
11-23 13:14:06.727   507   920 D CommandListener: Trying to bring down wlan0
,11-23 13:14:06.730   507   920 D CommandListener: Clearing all IP addresses on wlan0
,11-23 13:14:06.734   928  2965 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,11-23 13:14:07.412   928  2965 D wifi    : set interface wlan0 flags (UP)
,11-23 13:14:07.414   928  2965 I WifiHAL : Initializing wifi
,11-23 13:14:07.414   928  2965 I WifiHAL : Creating socket
,11-23 13:14:07.421   928   945 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
,11-23 13:14:07.422   928  2965 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
,11-23 13:14:07.422   928  2965 D wifi    : Did set static halHandle = 0x7f62b8d900
11-23 13:14:07.422   928  2965 D wifi    : halHandle = 0x7f62b8d900, mVM = 0x7f7f20d140, mCls = 0x1016fa
,11-23 13:14:07.422   928  2965 D wifi    : array field set
,11-23 13:14:07.423   928  2965 I WifiNative-HAL: interface[0] = wlan0
11-23 13:14:07.425   928  5912 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547117127936
,11-23 13:14:07.425   928  5912 D wifi    : waitForHalEvents called, vm = 0x7f7f20d140, obj = 0x1016fa, env = 0x7f5f1dc7c0
,11-23 13:14:07.484  5913  5913 I wpa_supplicant: Successfully initialized wpa_supplicant
,11-23 13:14:07.504  5913  5913 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,11-23 13:14:07.527   928  2965 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,11-23 13:14:07.542  5913  5913 I wpa_supplicant: rfkill: Cannot open RFKILL control device
11-23 13:14:07.542  5913  5913 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,11-23 13:14:07.561   928  2965 D WifiConfigStore: Loading config and enabling all networks 
,11-23 13:14:07.575   928  2965 D WifiConfigStore: loaded 0 passpoint configs
,11-23 13:14:07.576   928  2965 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,11-23 13:14:07.577   928  2965 W WifiConfigStore: Upgrading network 1 to android.uid.system:1000
,11-23 13:14:07.578   928  2965 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
,11-23 13:14:07.579   928  2965 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
11-23 13:14:07.579   928  2965 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 2
11-23 13:14:07.579   928  2965 E WifiConfigStore: found sortedWifiConfigurations : "RA-WINGS"NONE
11-23 13:14:07.579   928  2965 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,11-23 13:14:07.582   928  2965 D WifiNative-HAL: Setting external_sim to 1
,11-23 13:14:07.582  4931  4931 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,11-23 13:14:07.583   928  2965 D wifi    : setting dfs flag to true, 0x7f64c5aac0
11-23 13:14:07.584   928  2965 D WifiStateMachine: Setting OUI to DA-A1-19
11-23 13:14:07.584   928  2965 D wifi    : setting scan oui 0x7f64c5aac0
,11-23 13:14:07.584   928  2965 D WifiHAL : Sending mac address OUI
,11-23 13:14:07.588   928  2965 E native  : do suspend false
,11-23 13:14:07.600   928  2965 D wifi    : android_net_wifi_setLinkLayerStats: 1
11-23 13:14:07.600   928   928 D RttService: SCAN_AVAILABLE : 3
11-23 13:14:07.600   507   920 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,11-23 13:14:07.600   928  3056 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
11-23 13:14:07.601   507   920 D CommandListener: Setting iface cfg
,11-23 13:14:07.606   928  2964 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '161 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 161 Failed to set address (No such device)'
,11-23 13:14:07.606   928  2964 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,11-23 13:14:07.615   928  2964 D WifiNative-HAL: p2pGetDeviceAddress
,11-23 13:14:07.621   928  2964 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
11-23 13:14:07.621   928   943 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=155174 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=15 mControllerEnergyUsed=57 }
,11-23 13:14:10.702  5913  5913 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 13:14:10.711  5913  5913 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 13:14:10.717  5913  5913 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 13:14:10.751   928  2965 D WifiStateMachine: shouldSwitchNetwork  txSuccessRate=0.00 rxSuccessRate=0.00 delta 1000 -> 1000
,11-23 13:14:10.752   928  2965 D WifiStateMachine: CMD_AUTO_CONNECT sup state ScanState my state DisconnectedState nid=0 roam=3
11-23 13:14:10.752   928  2965 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 13:14:10.760   928  2965 D WifiStateMachine: CMD_AUTO_CONNECT will save config -> "NG700" nid=0
,11-23 13:14:10.792   928  2965 D WifiStateMachine: CMD_AUTO_CONNECT did save config ->  nid=0
,11-23 13:14:10.794  5913  5913 I wpa_supplicant: wlan0: Trying to associate with SSID 'NG700'
,11-23 13:14:11.216  5913  5913 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,11-23 13:14:11.253  5913  5913 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
,11-23 13:14:11.254  5913  5913 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
,11-23 13:14:11.266   928  2965 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20}  everValidated{false}  lastValidated{false}  created{false} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 13:14:11.266   928  2965 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
11-23 13:14:11.266   928  2967 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
,11-23 13:14:11.282   928  2965 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
,11-23 13:14:11.294   507   920 D CommandListener: Setting iface cfg
,11-23 13:14:11.300   928  2965 D WifiStateMachine: Start Dhcp Watchdog 3
,11-23 13:14:11.305   928  5918 D DhcpClient: Receive thread started
,11-23 13:14:11.310   928  2965 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{1}, ntable=[]
,11-23 13:14:11.310   928  2967 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 13:14:11.310   928  2967 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
,11-23 13:14:11.391   928  2965 E native  : do suspend false
,11-23 13:14:11.402   928  5917 D DhcpClient: Broadcasting DHCPDISCOVER
,11-23 13:14:11.415   928  5918 D DhcpClient: Received packet: 60:83:34:25:d7:62 OFFER, ip /192.168.1.113, mask /255.255.255.0, DNS servers: /192.168.1.1 , gateways [/192.168.1.1] lease time 172765, domain null
,11-23 13:14:11.415   928  5917 D DhcpClient: Got pending lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172765 seconds
,11-23 13:14:11.417   928  5917 D DhcpClient: Broadcasting DHCPREQUEST ciaddr=0.0.0.0 request=192.168.1.113 serverid=192.168.1.1
,11-23 13:14:11.430   928  5918 D DhcpClient: Received packet: 60:83:34:25:d7:62 ACK: your new IP /192.168.1.113, netmask /255.255.255.0, gateways [/192.168.1.1] DNS servers: /192.168.1.1 , lease time 172800
,11-23 13:14:11.430   928  5917 D DhcpClient: Confirmed lease: IP address 192.168.1.113/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info null lease 172800 seconds
11-23 13:14:11.433   507   920 D CommandListener: Setting iface cfg
,11-23 13:14:11.437   928  2965 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{2}, ntable=[]
,11-23 13:14:11.440   928  5917 D DhcpClient: Scheduling renewal in 86399s
,11-23 13:14:11.451   928  2965 D IpReachabilityMonitor: watch: iface{wlan0/5}, v{3}, ntable=[192.168.1.1/NUD_NONE]
,11-23 13:14:11.452   928  2965 D WifiConfigStore: No blacklist allowed without epno enabled
11-23 13:14:11.453   928  2967 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
11-23 13:14:11.455   928  2967 D ConnectivityService: Adding iface wlan0 to network 102
,11-23 13:14:11.466   928  2965 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
,11-23 13:14:11.507   928  2967 E ConnectivityService: Unexpected mtu value: 0, wlan0
11-23 13:14:11.507   928  2967 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
,11-23 13:14:11.511   928  2967 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,11-23 13:14:11.514   928  2967 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
,11-23 13:14:11.518   928  2967 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
,11-23 13:14:11.530   928  2967 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 13:14:11.534   928  2967 D ConnectivityService: scheduleUnvalidatedPrompt 102
,11-23 13:14:11.534   928  2967 D ConnectivityService: updateSignalStrengthThresholds: CONNECT, sending [] to NetworkAgentInfo [WIFI () - 102]
11-23 13:14:11.534   928  2967 D ConnectivityService: rematch for NetworkAgentInfo [WIFI () - 102]
11-23 13:14:11.534   928  2967 D ConnectivityService:    accepting network in place of null
11-23 13:14:11.534   928  2965 D WifiNetworkAgent: NetworkAgent: Received signal strength thresholds: []
,11-23 13:14:11.534   928  2965 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
11-23 13:14:11.535   928  2967 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps SignalStrength: -44]}  Score{20}  everValidated{false}  lastValidated{false}  created{true} lingering{false} explicitlySelected{false} acceptUnvalidated{false} everCaptivePortalDetected{false} lastCaptivePortalDetected{false} }
,11-23 13:14:11.549   928  5916 D NetlinkSocketObserver: NeighborEvent{elapsedMs=159102, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_REACHABLE}
,11-23 13:14:11.557   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -A idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 13:14:11.578   507   920 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -A idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
,11-23 13:14:11.581   928  2967 D CSLegacyTypeTracker: Sending CONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
11-23 13:14:11.581  3740  3903 W QCNEJ   : |CORE| network available: 102
11-23 13:14:11.581   928  2967 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,11-23 13:14:11.583   928   945 D Tethering: MasterInitialState.processMessage what=3
11-23 13:14:11.584  3740  3903 W QCNEJ   : |CORE| onAvailable: bind the process to WIFI
11-23 13:14:11.583   928  2967 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
11-23 13:14:11.587  3740  3903 W QCNEJ   : |CORE| newLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,2097152,4194304,262144,524288,1048576}
11-23 13:14:11.587  3740  3903 W QCNEJ   : |CORE| curLp: {InterfaceName: wlan0 LinkAddresses: [fe80::6283:34ff:fe25:d762/64,192.168.1.113/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0}
,11-23 13:14:11.597  4988  5012 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
11-23 13:14:11.598  4988  5012 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
11-23 13:14:11.598  4988  5012 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,1,0,0
11-23 13:14:11.598  4988  5012 E SarControlService: no key has been found,reset the power
11-23 13:14:11.598  4988  5023 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
11-23 13:14:11.598  4988  5023 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
11-23 13:14:11.598  4988  5023 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
11-23 13:14:11.599  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-23 13:14:11.599  5013  5013 D QcrilMsgTunnelSocket: [1008] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
11-23 13:14:11.600  4988  5023 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
11-23 13:14:11.600  4988  5023 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
11-23 13:14:11.601  4988  5023 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
11-23 13:14:11.601  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
,11-23 13:14:11.601  5013  5013 D QcrilMsgTunnelSocket: [1009] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
,11-23 13:14:11.604  3715  3715 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,11-23 13:14:11.606  5013  5027 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@747c840 HexData = [00000000f003000000000000ffffffff]
11-23 13:14:11.606  5013  5027 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
11-23 13:14:11.606  5013  5027 D QcrilMsgTunnelSocket: [1008] < OEM_HOOK_RAW [null]
11-23 13:14:11.609  3715  3715 D SystemUpdateService: onCreate
11-23 13:14:11.611   928  5915 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: Checking http://connectivitycheck.gstatic.com/generate_204 on "NG700", connectivitycheck.gstatic.com=172.217.21.14,2a00:1450:4001:802::200e
,11-23 13:14:11.614  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,11-23 13:14:11.615  4988  4999 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,11-23 13:14:11.618  3715  3715 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
11-23 13:14:11.619  5013  5027 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@747c840 HexData = [00000000f103000000000000ffffffff]
11-23 13:14:11.619  5013  5027 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
,11-23 13:14:11.619  5013  5027 D QcrilMsgTunnelSocket: [1009] < OEM_HOOK_RAW [null]
11-23 13:14:11.620  5013  5013 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
11-23 13:14:11.620  4988  4998 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,11-23 13:14:11.635  3715  3715 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? true*
,11-23 13:14:11.644  3715  5928 I SystemUpdateService: active receiver: enabled
,11-23 13:14:11.647  3715  3715 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,11-23 13:14:11.648  3715  3715 I Kids    : [GCoreUtils] Current gmscore version, 8122448 is smaller than the required version 8400000
,11-23 13:14:11.650  5728  5728 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,11-23 13:14:11.655  5728  5728 D SprintDMHelper: simOperator: 
11-23 13:14:11.655  5728  5728 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,11-23 13:14:11.665  3715  5397 I iu.UploadsManager: num queued entries: 0
,11-23 13:14:11.665  3715  5397 I iu.UploadsManager: num updated entries: 0
,11-23 13:14:11.681   928  5915 D NetworkMonitor/NetworkAgentInfo [WIFI () - 102]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Wed, 23 Nov 2016 18:14:11 GMT], X-Android-Received-Millis=[1479924851680], X-Android-Response-Source=[NETWORK 204], X-Android-Selected-Protocol=[http/1.1], X-Android-Sent-Millis=[1479924851636]}
,11-23 13:14:11.681   928  2967 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,11-23 13:14:11.682   928  2967 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] validation  passed
,11-23 13:14:11.682   928  2967 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
11-23 13:14:11.683   928  2967 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,11-23 13:14:11.684  3715  5928 I SystemUpdateService: Already downloaded, skipping offpeak checks.
,11-23 13:14:11.700  3715  5397 I iu.SyncManager: NEXT; no task
,11-23 13:14:11.708  3715  5928 I SystemUpdateService: network: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true]; metered: false; mobile allowed: true
,11-23 13:14:11.708  3715  5928 I SystemUpdateService: now status is 0 (complete)
11-23 13:14:11.708  3715  5928 I SystemUpdateService: processDownloadedFile /data/user/0/com.google.android.gms/app_download/update.zip
11-23 13:14:11.708  3715  5928 I SystemUpdateService: file has been verified
,11-23 13:14:11.709  3715  5928 I SystemUpdateService: OTA package size = 21989297
,11-23 13:14:11.717  3563  5939 I VacuumService: Vacuum at: now=1479924851717 tag=VacuumService
,11-23 13:14:11.728  3715  5928 I SystemUpdateService: showing system update notification
,11-23 13:14:11.731  5605  5653 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
11-23 13:14:11.731  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
11-23 13:14:11.731  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
11-23 13:14:11.731  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
11-23 13:14:11.731  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
11-23 13:14:11.731  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
11-23 13:14:11.731  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - SSID name: "NG700"
11-23 13:14:11.731  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
11-23 13:14:11.731  5605  5653 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,11-23 13:14:11.735  5605  5653 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e, SSID name: "NG700"
,11-23 13:14:11.735  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:14:11.736  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@ceef2b3 removed from the list
11-23 13:14:11.736  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
11-23 13:14:11.739  5605  5653 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
11-23 13:14:11.739  5605  5653 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
11-23 13:14:11.741  5605  5653 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@8b61904 Bundle[{}]
11-23 13:14:11.742  5605  5653 I io.jxcore.node.LifeCycleMonitor: start: OK
11-23 13:14:11.742  3563  5942 D GetConfigurationSnapshotOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader, 1, 
,11-23 13:14:11.743  5605  5653 I io.jxcore.node.LifeCycleMonitor: stop: OK
11-23 13:14:11.744  5605  5653 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
11-23 13:14:11.745  5605  5653 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
,11-23 13:14:11.746  5605  5653 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,11-23 13:14:11.748  5605  5653 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,11-23 13:14:11.760  5605  5653 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 168)
,11-23 13:14:11.760  5605  5653 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
11-23 13:14:11.761  5605  5653 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 169)
,11-23 13:14:11.762  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-23 13:14:11.763  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9221070 added. We now have 3 listener(s)
,11-23 13:14:11.764  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-23 13:14:11.764  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 13:14:11.764  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 13:14:11.765  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 13:14:11.765  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b234fe9 added. We now have 4 listener(s)
11-23 13:14:11.765  5605  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 13:14:11.765  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-23 13:14:11.767  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,11-23 13:14:11.767  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@798346e added. We now have 4 listener(s)
,11-23 13:14:11.769  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-23 13:14:11.769  3715  3715 D SystemUpdateService: onDestroy
11-23 13:14:11.769  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 13:14:11.769  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 13:14:11.769  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 13:14:11.769  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dc070f added. We now have 5 listener(s)
11-23 13:14:11.769  5605  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 13:14:11.770  5605  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 13:14:11.770  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 13:14:11.770  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,11-23 13:14:11.770  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:14:11.770  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:14:11.770  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 13:14:11.770  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9221070 removed from the list
11-23 13:14:11.770  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:14:11.770  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b234fe9 removed from the list
11-23 13:14:11.770  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
11-23 13:14:11.771  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.771  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.772  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:14:11.772  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.772  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.772  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 13:14:11.772  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 13:14:11.772  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:14:11.772  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b234fe9 not in the list
11-23 13:14:11.773  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.773  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:14:11.774  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:14:11.774  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.774  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.774  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 13:14:11.774  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 13:14:11.774  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:14:11.774  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@6dc070f removed from the list
11-23 13:14:11.774  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:14:11.775  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:14:11.775  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,11-23 13:14:11.775  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@798346e removed from the list
11-23 13:14:11.775  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 13:14:11.775  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a6fc39c added. We now have 3 listener(s)
,11-23 13:14:11.777  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-23 13:14:11.777  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 13:14:11.777  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 13:14:11.777  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 13:14:11.777  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d801a5 added. We now have 4 listener(s)
11-23 13:14:11.778  5605  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 13:14:11.778  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,11-23 13:14:11.779  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 13:14:11.780  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@817297a added. We now have 4 listener(s)
,11-23 13:14:11.781  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,11-23 13:14:11.781  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 13:14:11.781  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,11-23 13:14:11.781  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 13:14:11.781  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@edc052b added. We now have 5 listener(s)
11-23 13:14:11.781  5605  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,11-23 13:14:11.781  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 13:14:11.781  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 13:14:11.781  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 13:14:11.781  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 13:14:11.781  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-23 13:14:11.782  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 13:14:11.784  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 13:14:11.784  5605  5653 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 13:14:11.784  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 13:14:11.786  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.786  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 13:14:11.786  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,11-23 13:14:11.786  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 13:14:11.786  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
,11-23 13:14:11.788  3563  5940 I PhenotypeFlagCommitter: Experiment Configs successfully retrieved for com.google.android.gms.playlog.uploader
,11-23 13:14:11.788  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.789  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 13:14:11.789  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 13:14:11.789  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
,11-23 13:14:11.789  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 13:14:11.789  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.789  5605  5653 D BluetoothAdapter: STATE_ON
,11-23 13:14:11.790  3563  5940 I GoogleURLConnFactory: Using platform SSLCertificateSocketFactory
11-23 13:14:11.791  5859  5898 D BtGatt.GattService: registerClient() - UUID=b4c980fa-e20b-472e-b9c2-bebf51af0f99
11-23 13:14:11.792  5859  5875 D BtGatt.GattService: onClientRegistered() - UUID=b4c980fa-e20b-472e-b9c2-bebf51af0f99, clientIf=5
11-23 13:14:11.792  5605  5616 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 13:14:11.795  5859  5870 D BtGatt.GattService: start scan with filters
11-23 13:14:11.798  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 13:14:11.798  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:14:11.798  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,11-23 13:14:11.798  5859  5878 D BtGatt.ScanManager: handling starting scan
11-23 13:14:11.798  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.798  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 13:14:11.798  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 13:14:11.798  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.798  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 13:14:11.798  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 13:14:11.798  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.798  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.798  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.798  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.799  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 13:14:11.799  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.799  5859  5878 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@13b98b1
11-23 13:14:11.801  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.801  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 13:14:11.801  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.801  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.802  5605  5653 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
11-23 13:14:11.802  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.802  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 13:14:11.802  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
11-23 13:14:11.802  5605  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 13:14:11.802  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 13:14:11.802  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:14:11.802  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
11-23 13:14:11.804  5605  ,5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.804  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.804  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.804  5605  5605 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 13:14:11.804  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 13:14:11.804  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.804  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 13:14:11.804  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 13:14:11.804  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.804  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.804  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.804  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 13:14:11.804  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.805  5605  5653 D BluetoothAdapter: STATE_ON
11-23 13:14:11.805  5859  5870 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 13:14:11.805  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 13:14:11.805  5605  5653 D BluetoothAdapter: STATE_ON
11-23 13:14:11.806  5859  5869 D BtGatt.GattService: stopScan() - queue size =1
11-23 13:14:11.806  5859  5875 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 13:14:11.806  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:14:11.806  5859  5898 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 13:14:11.807  5859  5878 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 13:14:11.807  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 13:14:11.807  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.807  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 13:14:11.807  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.807  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.807  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.807  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.807  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 13:1,4:11.807  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.807  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.807  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.807  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 13:14:11.807  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 13:14:11.808  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 13:14:11.808  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.810  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.810  4931  5934 I Babel   : connection state changed from DISCONNECTED to CONNECTED
11-23 13:14:11.810  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 13:14:11.810  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.810  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.810  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 13:14:11.811  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 13:14:11.811  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 13:14:11.811  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.811  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 13:14:11.811  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 13:14:11.811  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.811  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.811  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.811  5605  5605 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 13:14:11.811  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.811  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.812  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.812  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.812  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.813  5859  5875 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 13:14:11.813  5605  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 13:14:11.813  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:14:11.813  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 13:14:11.813  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 13:14:11.813  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:14:11.813  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:14:11.813  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 13:14:11.813  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a6fc39c removed from the list
11-23 13:14:11.814  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:14:11.814  5859  5878 D BtGatt.ScanManager: Starting BLE batch scan
11-23 13:14:11.814  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d801a5 removed from the list
11-23 13:14:11.814  5859  5878 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 13:14:11.814  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
11-23 13:14:11.814  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.814  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.815  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.815  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.815  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.815  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 13:14:11.815  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 13:14:11.815  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:14:11.815  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@5d801a5 not in the list
11-23 13:14:11.815  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.815  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.816  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.816  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.816  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.816  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 13:14:11.816  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 13:14:11.816  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:14:11.816  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@edc052b removed from the list
11-23 13:14:11.816  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:14:11.816  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:14:11.816  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 13:14:11.816  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@817297a removed from the list
11-23 13:14:11.817  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 13:14:11.817  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@296ea34 added. We now have 3 listener(s)
11-23 13:14:11.818  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 13:14:11.818  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 13:14:11.818  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 13:14:11.818  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 13:14:11.819  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd5c05d added. We now have 4 listener(s)
11-23 13:14:11.819  5605  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 13:14:11.819  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 13:14:11.820  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 13:14:11.821  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@98d6dd2 added. We now have 4 listener(s)
11-23 13:14:11.821  5859  5875 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 13:14:11.821  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:14:11.822  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 13:14:11.822  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 13:14:11.822  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 13:14:11.823  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 13:14:11.823  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b19eea3 added. We now have 5 listener(s)
11-23 13:14:11.823  5605  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 13:14:11.823  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 13:14:11.823  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 13:14:11.824  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 13:14:11.824  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 13:14:11.824  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 13:14:11.824  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-23 13:14:11.825  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 13:14:11.825  5859  5875 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 13:14:11.825  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:14:11.828  5859  5878 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 13:14:11.829  3563  5940 W Uploader:  no longer exists, so no auth token.
11-23 13:14:11.829  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 13:14:11.829  5605  5653 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 13:14:11.829  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 13:14:11.832  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.832  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 13:14:11.832  5859  5875 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 13:14:11.832  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 13:14:11.833  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 13:14:11.833  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 13:14:11.833  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:14:11.834  5859  5875 E BtGatt.ContextMap: Context not found for ID 5
11-23 13:14:11.835  3563  5942 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
11-23 13:14:11.839  5859  5875 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 13:14:11.839  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:14:11.839  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.839  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 13:14:11.839  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 13:14:11.839  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 13:14:11.839  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 13:14:11.839  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.839  5859  5878 D BtGatt.ScanManager: stopping BLe Batch
11-23 13:14:11.842  5605  5653 D BluetoothAdapter: STATE_ON
11-23 13:14:11.843  5859  5875 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 13:14:11.843  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:14:11.844  5859  5878 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 13:14:11.844  5859  5898 D BtGatt.GattService: registerClient() - UUID=66e008b7-e7ed-4a0e-bbec-087cd9f9bd74
11-23 13:14:11.845  5859  5875 D BtGatt.GattService: onClientRegistered() - UUID=66e008b7-e7ed-4a0e-bbec-087cd9f9bd74, clientIf=5
11-23 13:14:11.845  5605  5616 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 13:14:11.845  5859  5870 D BtGatt.GattService: start scan with filters
11-23 13:14:11.847  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 13:14:11.847  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.847  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 13:14:11.847  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.848  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 13:14:11.848  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 13:14:11.848  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.848  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 13:14:11.848  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 13:14:11.848  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.848  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.848  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.848  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.848  5859  5875 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 13:14:11.848  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:14:11.848  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 13:14:11.848  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.850  5859  5878 D BtGatt.ScanManager: handling starting scan
11-23 13:14:11.850  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.850  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 13:14:11.850  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.850  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.850  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 13:14:11.850  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.850  5605  5653 D io.jxcore.node.StartStopOperationHandler: processCurrentOperationStatus: Operation successfully executed
11-23 13:14:11.850  5605  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 13:14:11.850  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 13:14:11.850  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 13:14:11.851  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:14:11.851  5605  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 13:14:11.851  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 13:14:11.851  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:14:11.851  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 13:14:11.851  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@296ea34 removed from the list
11-23 13:14:11.851  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:14:11.851  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd5c05d removed from the list
11-23 13:14:11.851  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
11-23 13:14:11.851  5605  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 13:14:11.851  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 13:14:11.851  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.851  5605  5653 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-23 13:14:11.851  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-23 13:14:11.851  5605  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 13:14:11.851  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 13:14:11.851  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.852  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.852  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.852  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.852  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 13:14:11.852  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 13:14:11.852  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:14:11.853  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@dd5c05d not in the list
11-23 13:14:11.853  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.853  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.853  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.853  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 13:14:11.853  5605  5605 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 13:14:11.854  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.854  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 13:14:11.854  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 13:14:11.854  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.854  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.854  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.854  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 13:14:11.854  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.854  5605  5653 D BluetoothAdapter: STATE_ON
11-23 13:14:11.854  5859  5875 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 13:14:11.854  5859  5869 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 13:14:11.855  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:14:11.855  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 13:14:11.855  5859  5878 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 13:14:11.855  5605  5653 D BluetoothAdapter: STATE_ON
11-23 13:14:11.856  5859  5898 D BtGatt.GattService: stopScan() - queue size =1
11-23 13:14:11.856  5859  5870 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 13:14:11.857  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 13:14:11.857  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.857  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 13:14:11.857  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.857  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.857  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.857  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.857  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 13:14:11.857  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.857  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.857  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.857  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 13:14:11.857  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 13:14:11.858  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 13:14:11.858  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.858  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.859  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 13:14:11.859  5859  5875 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 13:14:11.859  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.859  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:14:11.859  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.859  5859  5878 D BtGatt.ScanManager: Starting BLE batch scan
11-23 13:14:11.859  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 13:14:11.859  5859  5878 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 13:14:11.859  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 13:14:11.859  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:14:11.859  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 13:14:11.859  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b19eea3 removed from the list
11-23 13:14:11.859  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:14:11.859  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 13:14:11.859  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 13:14:11.859  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:14:11.859  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.859  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 13:14:11.859  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 13:14:11.859  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@98d6dd2 removed from the list
11-23 13:14:11.859  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 13:14:11.859  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.859  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.859  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.859  5605  5605 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 13:14:11.860  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 13:14:11.860  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.860  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3794bcc added. We now have 3 listener(s)
11-23 13:14:11.860  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.860  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 13:14:11.860  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 13:14:11.861  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 13:14:11.861  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.861  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.861  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 13:14:11.861  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.861  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b859e15 added. We now have 4 listener(s)
11-23 13:14:11.861  5605  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 13:14:11.861  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 13:14:11.863  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 13:14:11.863  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74ce52a added. We now have 4 listener(s)
11-23 13:14:11.864  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 13:14:11.864  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 13:14:11.864  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 13:14:11.864  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 13:14:11.864  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20c8f1b added. We now have 5 listener(s)
11-23 13:14:11.865  5605  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 13:14:11.865  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 13:14:11.865  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
11-23 13:14:11.865  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
11-23 13:14:11.865  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
11-23 13:14:11.865  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
11-23 13:14:11.866  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
11-23 13:14:11.868  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer
11-23 13:14:11.869  5605  5653 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
11-23 13:14:11.869  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
11-23 13:14:11.869  5859  5875 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 13:14:11.869  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:14:11.872  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings, Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.872  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
11-23 13:14:11.872  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
11-23 13:14:11.872  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
11-23 13:14:11.872  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: beacon extra : 0
11-23 13:14:11.873  5859  5875 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 13:14:11.873  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:14:11.874  5859  5878 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 13:14:11.875  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.875  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
11-23 13:14:11.875  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
11-23 13:14:11.875  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: manufacturer ID: 7413
11-23 13:14:11.875  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
11-23 13:14:11.875  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.875  5605  5653 D BluetoothAdapter: STATE_ON
11-23 13:14:11.877  5859  5870 D BtGatt.GattService: registerClient() - UUID=727bd832-a157-4248-a77b-7f66f0c34843
11-23 13:14:11.879  5859  5875 D BtGatt.GattService: onClientRegistered() - UUID=727bd832-a157-4248-a77b-7f66f0c34843, clientIf=5
11-23 13:14:11.879  5605  5617 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
11-23 13:14:11.879  5859  5875 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 13:14:11.879  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:14:11.880  5859  5897 D BtGatt.GattService: start scan with filters
11-23 13:14:11.883  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: start: scan started
11-23 13:14:11.883  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.883  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
11-23 13:14:11.883  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  true. Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.884  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
11-23 13:14:11.884  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: onBatchScanResults: results count  = 0. Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.884  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: trueCurrent thread: Thread[main,5,main], id: 1
11-23 13:14:11.884  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.884  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [SCANNING]
11-23 13:14:11.884  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [NOT_STARTED]
11-23 13:14:11.884  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.884  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.884  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.884  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING] Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.885  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
11-23 13:14:11.885  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.886  5859  5875 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
11-23 13:14:11.886  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:14:11.886  5859  5878 D BtGatt.ScanManager: stopping BLe Batch
11-23 13:14:11.887  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
,11-23 13:14:11.887  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 13:14:11.887  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.887  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.887  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.889  5605  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 13:14:11.889  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 13:14:11.889  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 13:14:11.890  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:14:11.890  5605  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 13:14:11.890  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 13:14:11.890  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:14:11.890  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 13:14:11.890  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3794bcc removed from the list
11-23 13:14:11.890  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:14:11.890  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b859e15 removed from the list
11-23 13:14:11.890  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
11-23 13:14:11.890  5605  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 13:14:11.890  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 13:14:11.890  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.890  5605  5653 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
11-23 13:14:11.890  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
11-23 13:14:11.890  5605  5653 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
11-23 13:14:11.890  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
11-23 13:14:11.890  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.890  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.890  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.890  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.890  5605  5605 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
11-23 13:14:11.891  5859  5875 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
11-23 13:14:11.891  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.891  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:14:11.891  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.891  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.891  5859  5878 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 13:14:11.891  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 13:14:11.891  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 13:14:11.891  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:14:11.891  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b859e15 not in the list
11-23 13:14:11.891  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
11-23 13:14:11.891  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.891  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart. RUNNING_BLE
11-23 13:14:11.891  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
11-23 13:14:11.891  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.891  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopPeerAddressHelperAdvertiser Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.892  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.892  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
11-23 13:14:11.892  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop, Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.892  5605  5653 D BluetoothAdapter: STATE_ON
11-23 13:14:11.892  5859  5869 D BtGatt.GattService: flushPendingBatchResults - clientIf=5, isServer=false
11-23 13:14:11.892  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: scan results are flushed 
11-23 13:14:11.893  5605  5653 D BluetoothAdapter: STATE_ON
11-23 13:14:11.893  5859  5870 D BtGatt.GattService: stopScan() - queue size =0
11-23 13:14:11.894  5859  5898 D BtGatt.GattService: unregisterClient() - clientIf=5
11-23 13:14:11.894  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
11-23 13:14:11.894  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: set state: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.894  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
11-23 13:14:11.894  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: notifyScannerStateChanged: started =  false. Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.894  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop finished, Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.894  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopAdvertiser:Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.894  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop. Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.894  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
11-23 13:14:11.894  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: current  = NOT_STARTED, new = NOT_STARTEDCurrent thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.894  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setState: finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.894  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop finished. Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.894  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
11-23 13:14:11.895  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
11-23 13:14:11.895  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
11-23 13:14:11.896  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.897  5859  5875 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 13:14:11.897  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:14:11.897  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.897  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 13:14:11.897  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.897  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.897  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 13:14:11.897  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 13:14:11.897  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:14:11.897  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 13:14:11.897  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@20c8f1b removed from the list
11-23 13:14:11.897  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:14:11.897  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
11-23 13:14:11.897  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:14:11.897  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 13:14:11.897  5605  5605 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: falseCurrent thread: Thread[main,5,main], id: 1
11-23 13:14:11.897  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74ce52a removed from the list
11-23 13:14:11.897  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState : Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.898  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: deducedStateSet: [NOT_STARTED]
11-23 13:14:11.898  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: stateSet: [SCANNING]
11-23 13:14:11.898  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.898  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.898  5605  5605 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: update state finished. Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.898  5605  5605 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
11-23 13:14:11.898  5605  5605 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED] Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.898  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 13:14:11.898  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.898  5859  5878 D BtGatt.ScanManager: handling starting scan
11-23 13:14:11.898  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@be34864 added. We now have 3 listener(s)
11-23 13:14:11.899  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.899  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.899  5605  5605 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[main,5,main], id: 1
11-23 13:14:11.899  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 13:14:11.899  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 13:14:11.899  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 13:14:11.899  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 13:14:11.899  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12c7acd added. We now have 4 listener(s)
11-23 13:14:11.900  5605  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 13:14:11.900  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
11-23 13:14:11.901  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
11-23 13:14:11.901  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e8ef82 added. We now have 4 listener(s)
11-23 13:14:11.902  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
11-23 13:14:11.902  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
11-23 13:14:11.902  5605  5653 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
11-23 13:14:11.902  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
11-23 13:14:11.902  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3c693 added. We now have 5 listener(s)
11-23 13:14:11.902  5605  5653 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
11-23 13:14:11.902  5605  5653 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
11-23 13:14:11.903  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
11-23 13:14:11.903  5605  5653 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
11-23 13:14:11.903  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:14:11.903  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:14:11.903  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 13:14:11.903  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@be34864 removed from the list
11-23 13:14:11.903  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:14:11.903  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12c7acd removed from the list
11-23 13:14:11.903  5605  5653 D io.jxcore.node.ConnectivityMonitor: stop
11-23 13:14:11.903  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.903  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.904  5859  5875 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
11-23 13:14:11.904  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:14:11.904  5859  5878 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
11-23 13:14:11.904  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.904  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.904  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.904  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 13:14:11.905  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 13:14:11.905  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:14:11.905  5605  5653 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@12c7acd not in the list
11-23 13:14:11.905  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.905  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.906  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.906  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateStateInternal finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.906  5605  5653 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState finished Current thread: Thread[Thread-61,5,main], id: 61
11-23 13:14:11.906  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
11-23 13:14:11.906  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
11-23 13:14:11.906  5605  5653 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
11-23 13:14:11.907  5605  5653 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3c693 removed from the list
11-23 13:14:11.907  5605  5653 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
11-23 13:14:11.907  5605  5653 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: updateState: mShouldBeStarted :  false, mIsServerStarted:  false
11-23 13:14:11.907  5605  5653 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
11-23 13:14:11.907  5605  5653 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@4e8ef82 removed from the list
11-23 13:14:11.907  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
11-23 13:14:11.908  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
11-23 13:14:11.908  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
11-23 13:14:11.908  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 13:14:11.908  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
11-23 13:14:11.908  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
11-23 13:14:11.908  5859  5875 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
11-23 13:14:11.908  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:14:11.909  5859  5878 D BtGatt.ScanManager: Starting BLE batch scan
11-23 13:14:11.909  5859  5878 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
11-23 13:14:11.915  5859  5875 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
11-23 13:14:11.915  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:14:11.919  5859  5875 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
11-23 13:14:11.919  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:14:11.920  5859  5878 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
11-23 13:14:11.923  5859  5875 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 13:14:11.923  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:14:11.924  5859  5875 E BtGatt.ContextMap: Context not found for ID 5
,11-23 13:14:11.928  5859  5875 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
,11-23 13:14:11.928  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:14:11.928  5859  5878 D BtGatt.ScanManager: stopping BLe Batch
,11-23 13:14:11.932  5859  5875 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
,11-23 13:14:11.932  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
11-23 13:14:11.932  5859  5878 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,11-23 13:14:11.936  5859  5875 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
11-23 13:14:11.936  5859  5875 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,11-23 13:14:12.313  5605  5605 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 13:14:12.360  5605  5605 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 13:14:12.364  3563  5952 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 13:14:12.397  5605  5605 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,11-23 13:14:12.441  3563  5940 W Uploader:  no longer exists, so no auth token.
,11-23 13:14:12.449  3563  5953 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 13:14:12.537  3563  5952 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
,11-23 13:14:14.067  5605  5955 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 13:14:14.067  5605  5955 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 13:14:14.333   928  2967 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 102]
,11-23 13:14:14.880  5605  5955 W !!      : call onHalfStreamCopied
,11-23 13:14:14.880  5605  5955 I testCopyDataAndClose: closing input stream
,11-23 13:14:15.655  5605  5955 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 177, thread name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 13:14:15.655  5605  5955 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 13:14:15.655  5605  5955 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 13:14:15.655  5605  5955 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 13:14:15.655  5605  5955 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
11-23 13:14:15.655  5605  5955 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-23 13:14:15.655  5605  5955 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-23 13:14:15.655  5605  5955 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-23 13:14:15.655  5605  5955 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-23 13:14:15.655  5605  5955 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 177, name: testCopyDataAndCloseConnection thread). Connection data: Peer properties: [null null].
11-23 13:14:15.655  5605  5955 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-23 13:14:16.368   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:14:17.369   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:14:18.370   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:14:19.371   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:14:19.447  5605  5956 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-23 13:14:19.447  5605  5956 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 13:14:19.540   928  2967 D ConnectivityService: handlePromptUnvalidated 102
,11-23 13:14:20.372   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:14:21.373   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-23 13:14:21.447  5605  5653 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 180. Connection data: Peer properties: [null null].
11-23 13:14:21.447  5605  5653 I io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 13:14:21.447  5605  5653 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 180, name: My test thread name)
,11-23 13:14:21.556  5605  5956 D io.jxcore.node.StreamCopyingThread: number of bytes read = 0
,11-23 13:14:21.556  5605  5956 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 180, name: My test thread name). Connection data: Peer properties: [null null].
11-23 13:14:21.556  5605  5956 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 187 and the total number of bytes written 187
11-23 13:14:21.556  5605  5957 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 13:14:21.556  5605  5957 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 13:14:22.623   928  2965 D WifiStateMachine: L2Connected CMD_START_SCAN source -2 10, 11 -> obsolete
,11-23 13:14:23.221  5605  5957 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 182, thread name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 13:14:23.221  5605  5957 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 13:14:23.221  5605  5957 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 13:14:23.221  5605  5957 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 13:14:23.221  5605  5957 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-23 13:14:23.221  5605  5957 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
11-23 13:14:23.221  5605  5957 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
11-23 13:14:23.221  5605  5957 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
11-23 13:14:23.221  5605  5957 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
,11-23 13:14:23.221  5605  5957 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 182, name: testCopyBigData thread). Connection data: Peer properties: [null null].
11-23 13:14:23.221  5605  5957 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 20971520 and the total number of bytes written 20971520
,11-23 13:14:26.946  5605  5958 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-23 13:14:26.946  5605  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 13:14:26.947  5605  5958 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 184, thread name: My test thread name). Connection data: Peer properties: [null null].
11-23 13:14:26.947  5605  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 13:14:26.947  5605  5958 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Connection data: Peer properties: [null null].
11-23 13:14:26.947  5605  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
,11-23 13:14:26.947  5605  5958 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Flushing
,11-23 13:14:26.947  5605  5958 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closing
,11-23 13:14:26.947  5605  5958 D io.jxcore.node.StreamCopyingThread: closeOutputStream. Closed
,11-23 13:14:26.947  5605  5958 D io.jxcore.node.StreamCopyingThread: number of bytes read = -1
,11-23 13:14:26.948  5605  5958 D io.jxcore.node.StreamCopyingThread: onStreamCopyingThreadDone
11-23 13:14:26.948  5605  5958 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 184, name: My test thread name). Connection data: Peer properties: [null null].
11-23 13:14:26.948  5605  5958 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
,11-23 13:14:26.950  5605  5653 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,11-23 13:14:26.953  5605  5959 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-23 13:14:26.953  5605  5959 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false
11-23 13:14:26.953  5605  5959 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 188, thread name: My test thread name): Test exception.
11-23 13:14:26.954  5605  5959 D io.jxcore.node.StreamCopyingThread: onStreamCopyError (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-23 13:14:26.954  5605  5959 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-23 13:14:26.954  5605  5959 D io.jxcore.node.StreamCopyingThread: number of bytes read = 22
11-23 13:14:26.954  5605  5959 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 188, name: My test thread name). Connection data: Peer properties: [null null].
11-23 13:14:26.954  5605  5959 D io.jxcore.node.StreamCopyingThread:  Is incomming connection: false .During the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
11-23 13:14:26.959  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - DEBUG UnitTest_app: 'Total number of executed tests:  82'
11-23 13:14:26.959  5605  5653 I jxcore-log: 
11-23 13:14:26.959  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - DEBUG UnitTest_app: 'Number of passed tests:  82'
11-23 13:14:26.959  5605  5653 I jxcore-log: 
,11-23 13:14:26.959  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - DEBUG UnitTest_app: 'Number of failed tests:  0'
11-23 13:14:26.959  5605  5653 I jxcore-log: 
11-23 13:14:26.959  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - DEBUG UnitTest_app: 'Number of ignored tests:  0'
11-23 13:14:26.959  5605  5653 I jxcore-log: 
11-23 13:14:26.960  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - DEBUG UnitTest_app: 'Total duration:  90820'
11-23 13:14:26.960  5605  5653 I jxcore-log: 
11-23 13:14:26.962  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - DEBUG UnitTest_app: 'Unit Test app is loaded'
11-23 13:14:26.962  5605  5653 I jxcore-log: 
11-23 13:14:26.965  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 13:14:26.965  5605  5653 I jxcore-log: 
11-23 13:14:26.966  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 13:14:26.966  5605  5653 I jxcore-log: 
11-23 13:14:26.966  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-23 13:14:26.966  5605  5653 I jxcore-log: 
11-23 13:14:26.966  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-23 13:14:26.966  5605  5653 I jxcore-log: 
,11-23 13:14:26.967  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 13:14:26.967  5605  5653 I jxcore-log: 
11-23 13:14:26.967  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 13:14:26.967  5605  5653 I jxcore-log: 
11-23 13:14:26.967  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 13:14:26.967  5605  5653 I jxcore-log: 
11-23 13:14:26.967  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 13:14:26.967  5605  5653 I jxcore-log: 
,11-23 13:14:26.968  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 13:14:26.968  5605  5653 I jxcore-log: 
11-23 13:14:26.968  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":true,"advertisingActive":false}'
11-23 13:14:26.968  5605  5653 I jxcore-log: 
11-23 13:14:26.968  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - INFO thaliMobile: 'Received state ({"discoveryActive":true,"advertisingActive":false}) did not match with target ({"started":false,"listening":false,"advertising":false,"networkType":"BOTH"})'
11-23 13:14:26.968  5605  5653 I jxcore-log: 
11-23 13:14:26.969  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 13:14:26.969  5605  5653 I jxcore-log: 
11-23 13:14:26.969  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 13:14:26.969  5605  5653 I jxcore-log: 
11-23 13:14:26.969  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 13:14:26.969  5605  5653 I jxcore-log: 
11-23 13:14:26.969  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 13:14:26.969  5605  5653 I jxcore-log: 
11-23 13:14:26.969  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 13:14:26.969  5605  5653 I jxcore-log: 
11-23 13:14:26.970  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-23 13:14:26.970  5605  5653 I jxcore-log: 
11-23 13:14:26.970  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 13:14:26.970  5605  5653 I jxcore-log: 
,11-23 13:14:26.970  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}'
11-23 13:14:26.970  5605  5653 I jxcore-log: 
11-23 13:14:26.971  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 13:14:26.971  5605  5653 I jxcore-log: 
,11-23 13:14:26.971  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 13:14:26.971  5605  5653 I jxcore-log: 
11-23 13:14:26.971  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-23 13:14:26.971  5605  5653 I jxcore-log: 
11-23 13:14:26.971  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}'
11-23 13:14:26.971  5605  5653 I jxcore-log: 
,11-23 13:14:26.972  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}'
11-23 13:14:26.972  5605  5653 I jxcore-log: 
,11-23 13:14:26.973  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - DEBUG thaliMobileNativeWrapper: 'networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e","ssidName":"\"NG700\""}'
11-23 13:14:26.973  5605  5653 I jxcore-log: 
11-23 13:14:26.973  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
,11-23 13:14:26.973  5605  5653 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: null
11-23 13:14:26.974  5605  5653 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
11-23 13:14:26.974  5605  5653 D io.jxcore.node.StartStopOperationHandler: Operation timeout, state error: Discovery manager not started
11-23 13:14:26.974  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 13:14:26.974  5605  5653 I jxcore-log: 
11-23 13:14:26.974  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 13:14:26.974  5605  5653 I jxcore-log: 
11-23 13:14:26.974  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 13:14:26.974  5605  5653 I jxcore-log: 
,11-23 13:14:26.974  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 13:14:26.974  5605  5653 I jxcore-log: 
11-23 13:14:26.975  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - DEBUG thaliMobileNativeWrapper: 'discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}'
11-23 13:14:26.975  5605  5653 I jxcore-log: 
11-23 13:14:26.975  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - INFO thaliMobile: 'Filtered out discoveryAdvertisingStateUpdate (was in stopped state).'
11-23 13:14:26.975  5605  5653 I jxcore-log: 
,11-23 13:14:26.977  5605  5605 D SystemWebChromeClient: file:///android_asset/www/js/thali_main.js: Line 68 : UIApp is all set and ready!
11-23 13:14:26.978  5605  5605 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
,11-23 13:14:26.980  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - DEBUG UnitTest_app: 'My device name is: Huawei-Nexus 6P'
11-23 13:14:26.980  5605  5653 I jxcore-log: 
11-23 13:14:26.981  5605  5653 I jxcore-log: 2016-11-23 18:14:26 - WARN testUtils: 'myNameCallback not set!'
11-23 13:14:26.981  5605  5653 I jxcore-log: 
,11-23 13:14:29.023  5605  5653 I jxcore-log: 2016-11-23 18:14:29 - INFO runTests: 'Starting tests. Network type: WIFI. Platform: android'
11-23 13:14:29.023  5605  5653 I jxcore-log: 
,11-23 13:14:29.025  5605  5653 I jxcore-log: 2016-11-23 18:14:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreateNativeListener.js'
11-23 13:14:29.025  5605  5653 I jxcore-log: 
,11-23 13:14:29.371  5605  5653 I jxcore-log: 2016-11-23 18:14:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testCreatePeerListener.js'
11-23 13:14:29.371  5605  5653 I jxcore-log: 
,11-23 13:14:29.381  5605  5653 I jxcore-log: 2016-11-23 18:14:29 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManager.js'
11-23 13:14:29.381  5605  5653 I jxcore-log: 
,11-23 13:14:30.495  5605  5653 I jxcore-log: 2016-11-23 18:14:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testLocalSeqManagerCoordinated.js'
11-23 13:14:30.495  5605  5653 I jxcore-log: 
,11-23 13:14:30.688  5605  5653 I jxcore-log: 2016-11-23 18:14:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testMakeIntoCloseAllServer.js'
11-23 13:14:30.688  5605  5653 I jxcore-log: 
,11-23 13:14:30.693  5605  5653 I jxcore-log: 2016-11-23 18:14:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testNativeMethod.js'
11-23 13:14:30.693  5605  5653 I jxcore-log: 
,11-23 13:14:30.698  5605  5653 I jxcore-log: 2016-11-23 18:14:30 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBCheckpointPlugin.js'
11-23 13:14:30.698  5605  5653 I jxcore-log: 
,11-23 13:14:31.183  5605  5653 I jxcore-log: 2016-11-23 18:14:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPouchDBGenerator.js'
11-23 13:14:31.183  5605  5653 I jxcore-log: 
,11-23 13:14:31.228  5605  5653 I jxcore-log: 2016-11-23 18:14:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testPromiseQueue.js'
11-23 13:14:31.228  5605  5653 I jxcore-log: 
,11-23 13:14:31.242  5605  5653 I jxcore-log: 2016-11-23 18:14:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testTests.js'
11-23 13:14:31.242  5605  5653 I jxcore-log: 
,11-23 13:14:31.246  5605  5653 I jxcore-log: 2016-11-23 18:14:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManager.js'
11-23 13:14:31.246  5605  5653 I jxcore-log: 
,11-23 13:14:31.517  5605  5653 I jxcore-log: 2016-11-23 18:14:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliManagerCoordinated.js'
11-23 13:14:31.517  5605  5653 I jxcore-log: 
,11-23 13:14:31.646  5605  5653 I jxcore-log: 2016-11-23 18:14:31 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobile.js'
11-23 13:14:31.646  5605  5653 I jxcore-log: 
,11-23 13:14:32.022  5605  5653 I jxcore-log: 2016-11-23 18:14:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNative.js'
11-23 13:14:32.022  5605  5653 I jxcore-log: 
,11-23 13:14:32.030  5605  5653 I jxcore-log: 2016-11-23 18:14:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeDiscoveryCoordinated.js'
11-23 13:14:32.030  5605  5653 I jxcore-log: 
,11-23 13:14:32.034  5605  5653 I jxcore-log: 2016-11-23 18:14:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliMobileNativeWrapper.js'
11-23 13:14:32.034  5605  5653 I jxcore-log: 
,11-23 13:14:32.040  5605  5653 I jxcore-log: 2016-11-23 18:14:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotification.js'
11-23 13:14:32.040  5605  5653 I jxcore-log: 
,11-23 13:14:32.046  5605  5653 I jxcore-log: 2016-11-23 18:14:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationAction.js'
11-23 13:14:32.046  5605  5653 I jxcore-log: 
,11-23 13:14:32.074  5605  5653 I jxcore-log: 2016-11-23 18:14:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationBeacons.js'
11-23 13:14:32.074  5605  5653 I jxcore-log: 
,11-23 13:14:32.108  5605  5653 I jxcore-log: 2016-11-23 18:14:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationClient.js'
11-23 13:14:32.108  5605  5653 I jxcore-log: 
,11-23 13:14:32.115  5605  5653 I jxcore-log: 2016-11-23 18:14:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationLocal.js'
11-23 13:14:32.115  5605  5653 I jxcore-log: 
,11-23 13:14:32.121  5605  5653 I jxcore-log: 2016-11-23 18:14:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliNotificationServer.js'
11-23 13:14:32.121  5605  5653 I jxcore-log: 
,11-23 13:14:32.137  5605  5653 I jxcore-log: 2016-11-23 18:14:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerAction.js'
11-23 13:14:32.137  5605  5653 I jxcore-log: 
,11-23 13:14:32.152  5605  5653 I jxcore-log: 2016-11-23 18:14:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerDictionary.js'
11-23 13:14:32.152  5605  5653 I jxcore-log: 
,11-23 13:14:32.158  5605  5653 I jxcore-log: 2016-11-23 18:14:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolDefault.js'
11-23 13:14:32.158  5605  5653 I jxcore-log: 
,11-23 13:14:32.163  5605  5653 I jxcore-log: 2016-11-23 18:14:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolInterface.js'
11-23 13:14:32.163  5605  5653 I jxcore-log: 
,11-23 13:14:32.176  5605  5653 I jxcore-log: 2016-11-23 18:14:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPeerPoolOneAtATime.js'
11-23 13:14:32.176  5605  5653 I jxcore-log: 
,11-23 13:14:32.193  5605  5653 I jxcore-log: 2016-11-23 18:14:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotification.js'
11-23 13:14:32.193  5605  5653 I jxcore-log: 
,11-23 13:14:32.208  5605  5653 I jxcore-log: 2016-11-23 18:14:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliPullReplicationFromNotificationCoordinated.js'
11-23 13:14:32.208  5605  5653 I jxcore-log: 
,11-23 13:14:32.219  5605  5653 I jxcore-log: 2016-11-23 18:14:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerAction.js'
11-23 13:14:32.219  5605  5653 I jxcore-log: 
,11-23 13:14:32.232  5605  5653 I jxcore-log: 2016-11-23 18:14:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationPeerActionCoordinated.js'
11-23 13:14:32.232  5605  5653 I jxcore-log: 
,11-23 13:14:32.243  5605  5653 I jxcore-log: 2016-11-23 18:14:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliReplicationUtilities.js'
11-23 13:14:32.243  5605  5653 I jxcore-log: 
,11-23 13:14:32.256  5605  5653 I jxcore-log: 2016-11-23 18:14:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliSendNotificationBasedOnReplication.js'
11-23 13:14:32.256  5605  5653 I jxcore-log: 
,11-23 13:14:32.266  5605  5653 I jxcore-log: 2016-11-23 18:14:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliTcpServersManager.js'
11-23 13:14:32.266  5605  5653 I jxcore-log: 
,11-23 13:14:32.273  5605  5653 I jxcore-log: 2016-11-23 18:14:32 - INFO runTests: 'Test runner loading file: /data/data/com.test.thalitest/files/www/jxcore/bv_tests/testThaliWifiInfrastructure.js'
11-23 13:14:32.273  5605  5653 I jxcore-log: 
,11-23 13:14:32.294  5605  5653 V io.jxcore.node.JXcoreExtension: isBleMultipleAdvertisementSupported: SUPPORTED
,11-23 13:14:32.295  5605  5653 I jxcore-log: 2016-11-23 18:14:32 - INFO testUtils: 'BLE multiple advertisement supported'
11-23 13:14:32.295  5605  5653 I jxcore-log: 
,11-23 13:14:32.327  5605  5653 I jxcore-log: 2016-11-23 18:14:32 - INFO CoordinatedClient: 'Connecting to coordination server on http://85.14.110.168:3000/'
11-23 13:14:32.327  5605  5653 I jxcore-log: 
,11-23 13:14:32.561  5605  5653 I jxcore-log: 2016-11-23 18:14:32 - DEBUG CoordinatedClient: 'connected to the test server',
11-23 13:14:32.561  5605  5653 I jxcore-log: 
,11-23 13:14:41.375   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:14:42.376   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:14:43.377   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:14:44.378   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:14:45.380   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:14:46.380   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 13:14:51.511   928  2965 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 13:15:11.381   544   544 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 13:15:11.382   544   544 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 13:15:21.383   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:15:22.385   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:15:23.386   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:15:24.387   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:15:25.389   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:15:26.389   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 13:15:31.391   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:15:31.517   928  2965 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 13:15:32.392   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:15:33.394   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:15:34.395   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:15:35.397   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:15:36.397   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 13:15:46.399   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:15:47.401   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:15:48.402   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:15:49.403   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:15:50.404   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:15:51.405   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-23 13:15:51.518   928  2965 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 13:16:06.407   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:16:07.408   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:16:08.409   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:16:09.411   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:16:10.412   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:16:11.413   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-23 13:16:15.269  5913  5913 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-REGDOM-CHANGE init=BEACON_HINT type=UNKNOWN
,11-23 13:16:31.415   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:16:31.520   928  2965 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 13:16:32.417   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:16:33.418   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:16:34.420   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:16:35.421   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:16:36.422   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 13:16:51.524   928  2965 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 13:17:01.422   544   544 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 13:17:01.423   544   544 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 13:17:11.527   928  2965 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 13:17:16.424   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:17:17.425   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:17:18.427   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:17:19.428   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:17:20.430   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:17:21.430   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 13:17:26.431   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:17:27.433   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:17:28.434   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:17:29.436   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:17:30.437   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:17:31.438   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 13:17:41.440   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:17:42.441   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:17:43.442   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:17:44.444   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:17:45.445   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:17:46.446   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 3
,11-23 13:17:51.531   928  2965 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 13:18:01.447   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:18:02.448   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:18:03.449   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:18:04.450   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:18:05.452   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:18:06.452   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,11-23 13:18:11.533   928  2965 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 13:18:26.454   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:18:27.455   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:18:28.457   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:18:29.458   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:18:30.460   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:18:31.460   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 5
,11-23 13:18:31.537   928  2965 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 13:18:51.540   928  2965 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 13:18:56.461   544   544 I Atfwd_Sendcmd: AtCmdFwd service not ready - Exhausted retry attempts - :6
,11-23 13:18:56.461   544   544 I Atfwd_Daemon: result : -1 	 ,Init step :2 	 ,qmiErrorCode: 0
,11-23 13:19:11.541   928  2965 D WifiStateMachine: starting scan for "NG700"WPA_PSK with 2437
,11-23 13:19:16.463   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:19:17.464   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:19:18.465   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:19:19.466   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:19:20.467   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:19:21.468   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 1
,11-23 13:19:26.470   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:19:27.471   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:19:28.473   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:19:29.474   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:19:30.475   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,11-23 13:19:30.650  5605  5653 I jxcore-log: 2016-11-23 18:19:30 - DEBUG CoordinatedClient: 'device disconnected from the test server'
11-23 13:19:30.650  5605  5653 I jxcore-log: 
,11-23 13:19:30.960  5605  5653 I jxcore-log: 2016-11-23 18:19:30 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 13:19:30.960  5605  5653 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 13:19:30.960  5605  5653 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 13:19:30.960  5605  5653 I jxcore-log: emit@events.js:82:1
11-23 13:19:30.960  5605  5653 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 13:19:30.960  5605  5653 I jxcore-log: emit@events.js:82:1''
11-23 13:19:30.960  5605  5653 I jxcore-log: 
,11-23 13:19:30.962  5605  5653 I jxcore-log: 2016-11-23 18:19:30 - DEBUG CoordinatedClient: 'test client failed'
11-23 13:19:30.962  5605  5653 I jxcore-log: 
,11-23 13:19:30.971  5605  5653 I jxcore-log: 2016-11-23 18:19:30 - ERROR CoordinatedClient: 'connection error: 'Error: websocket error', description: 'Error: connect ECONNREFUSED', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 13:19:30.971  5605  5653 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 13:19:30.971  5605  5653 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 13:19:30.971  5605  5653 I jxcore-log: emit@events.js:82:1
11-23 13:19:30.971  5605  5653 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 13:19:30.971  5605  5653 I jxcore-log: emit@events.js:82:1''
11-23 13:19:30.971  5605  5653 I jxcore-log: 
,11-23 13:19:30.972  5605  5653 I jxcore-log: 2016-11-23 18:19:30 - DEBUG CoordinatedClient: 'test client failed'
11-23 13:19:30.972  5605  5653 I jxcore-log: 
,11-23 13:19:30.976  5605  5653 I jxcore-log: 2016-11-23 18:19:30 - ERROR CoordinatedThaliTape: 'tests failed, error: 'Error: websocket error', stack: 'Transport.prototype.onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transport.js:62:13
11-23 13:19:30.976  5605  5653 I jxcore-log: WS.prototype.addEventListeners/this.ws.onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/engine.io-client/lib/transports/websocket.js:135:5
11-23 13:19:30.976  5605  5653 I jxcore-log: onError@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:428:5
11-23 13:19:30.976  5605  5653 I jxcore-log: emit@events.js:82:1
11-23 13:19:30.976  5605  5653 I jxcore-log: onerror@/data/data/com.test.thalitest/files/www/jxcore/node_modules/ws/lib/WebSocket.js:686:5
11-23 13:19:30.976  5605  5653 I jxcore-log: emit@events.js:82:1''
11-23 13:19:30.976  5605  5653 I jxcore-log: 
,11-23 13:19:30.977  5605  5653 I jxcore-log: 2016-11-23 18:19:30 - DEBUG CoordinatedThaliTape: '****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****'
11-23 13:19:30.977  5605  5653 I jxcore-log: 
,11-23 13:19:31.476   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 2
,11-23 13:19:31.595  5972  5972 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,11-23 13:19:31.619  5972  5972 D AndroidRuntime: CheckJNI is OFF
,11-23 13:19:31.647  5972  5972 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,11-23 13:19:31.680  5972  5972 I Radio-JNI: register_android_hardware_Radio DONE
,11-23 13:19:31.695  5972  5972 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,11-23 13:19:31.705   928   941 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,11-23 13:19:31.706   928   941 I ActivityManager: Killing 5605:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,11-23 13:19:31.809   928  2966 D WifiService: Client connection lost with reason: 4
,11-23 13:19:31.809   928  3194 I WindowState: WIN DEATH: Window{6cbe03e u0 com.test.thalitest/com.test.thalitest.MainActivity}
11-23 13:19:31.809   928  3140 D GraphicsStats: Buffer count: 2
,11-23 13:19:31.842   928   941 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,11-23 13:19:31.844   928   941 W PackageManager: Package com.test.thalitest is missing; assuming frozen
11-23 13:19:31.845   928   941 E ActivityManager: Failure starting process com.test.thalitest
11-23 13:19:31.845   928   941 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
11-23 13:19:31.845   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3278)
11-23 13:19:31.845   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3237)
11-23 13:19:31.845   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3116)
11-23 13:19:31.845   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
11-23 13:19:31.845   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
11-23 13:19:31.845   928   941 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
11-23 13:19:31.845   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
11-23 13:19:31.845   928   941 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
11-23 13:19:31.845   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4598)
11-23 13:19:31.845   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5955)
11-23 13:19:31.845   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5614)
11-23 13:19:31.845   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5763)
11-23 13:19:31.845   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
11-23 13:19:31.845   928   941 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1736)
11-23 13:19:31.845   928   941 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 13:19:31.845   928   941 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
11-23 13:19:31.845   928   941 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-23 13:19:31.845   928   941 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
11-23 13:19:31.846   928   941 I ActivityManager:   Force finishing activity ActivityRecord{4399792 u0 com.test.thalitest/.MainActivity t10}
11-23 13:19:31.846   928   951 I art     : Starting a blocking GC Explicit
,11-23 13:19:31.852   928   938 W ActivityManager: Spurious death for ProcessRecord{649380e 0:com.test.thalitest/u0a77}, curProc for 5605: null
,11-23 13:19:31.856   928   946 W WindowManager: Attempted to add application window with unknown token Token{5a03563 ActivityRecord{4399792 u0 com.test.thalitest/.MainActivity t10 f}}.  Aborting.
,11-23 13:19:31.857   928   946 W WindowManager: Token{5a03563 ActivityRecord{4399792 u0 com.test.thalitest/.MainActivity t10 f}} already running, starting window not displayed. Unable to add window -- token Token{5a03563 ActivityRecord{4399792 u0 com.test.thalitest/.MainActivity t10 f}} is not valid; is your activity running?
11-23 13:19:31.857   928   946 W WindowManager: view not successfully added to wm, removing view
11-23 13:19:31.857   928   946 W WindowManager: Exception when adding starting window
11-23 13:19:31.857   928   946 W WindowManager: java.lang.IllegalArgumentException: View=com.android.internal.policy.PhoneWindow$DecorView{2e0541 V.E...... R.....ID 0,0-0,0} not attached to window manager
11-23 13:19:31.857   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.findViewLocked(WindowManagerGlobal.java:424)
11-23 13:19:31.857   928   946 W WindowManager: 	at android.view.WindowManagerGlobal.removeView(WindowManagerGlobal.java:350)
11-23 13:19:31.857   928   946 W WindowManager: 	at android.view.WindowManagerImpl.removeViewImmediate(WindowManagerImpl.java:116)
11-23 13:19:31.857   928   946 W WindowManager: 	at com.android.server.policy.PhoneWindowManager.addStartingWindow(PhoneWindowManager.java:2386)
11-23 13:19:31.857   928   946 W WindowManager: 	at com.android.server.wm.WindowManagerService$H.handleMessage(WindowManagerService.java:7824)
11-23 13:19:31.857   928   946 W WindowManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 13:19:31.857   928   946 W WindowManager: 	at android.os.Looper.loop(Looper.java:148)
11-23 13:19:31.857   928   946 W WindowManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-23 13:19:31.857   928   946 W WindowManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,11-23 13:19:31.922   928   951 I art     : Explicit concurrent mark sweep GC freed 16391(1074KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 29MB/43MB, paused 1.871ms total 75.865ms
,11-23 13:19:31.942   928   951 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,11-23 13:19:31.946  5972  5972 I art     : System.exit called, status: 0
,11-23 13:19:31.946  5972  5972 I AndroidRuntime: VM exiting with result code 0.
,11-23 13:19:31.952   928   951 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,11-23 13:19:31.956   928   941 I ActivityManager: Exiting empty application process com.test.thalitest (null)
11-23 13:19:31.960  5859  5859 D BluetoothMapAppObserver: onReceive
11-23 13:19:31.960  5859  5859 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,11-23 13:19:31.964  4074  4170 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,11-23 13:19:31.968   928  2954 I InputReader: Reconfiguring input devices.  changes=0x00000010
,11-23 13:19:31.969  3650  3650 I Keyboard.Facilitator: resetDictionaries() : en_US
,11-23 13:19:31.999  3389  5988 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,11-23 13:19:32.001  3650  5986 I Keyboard.Facilitator.DecoderInitializer: run()
,11-23 13:19:32.019   928   928 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,11-23 13:19:32.020  3790  3790 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,11-23 13:19:32.030  3650  5986 I Decoder : createOrResetDecoder
,11-23 13:19:32.044    28    28 W kworker/3:1: type=1400 audit(0.0:116): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 13:19:32.054    28    28 W kworker/3:1: type=1400 audit(0.0:117): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 13:19:32.055  3563  3563 E NetworkScheduler.SchedulerReceiver: Invalid parameter app
,11-23 13:19:32.055  3563  3563 E NetworkScheduler.SchedulerReceiver: Invalid package name : Perhaps you didn't include a PendingIntent in the extras?
,11-23 13:19:32.070    28    28 W kworker/3:1: type=1400 audit(0.0:118): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,11-23 13:19:32.088  3389  3413 E SQLiteLog: (2570) os_unix.c:31406: (30) unlink(/data/user/0/com.android.providers.contacts/databases/contacts2.db-mjBE61A49DF) - 
,11-23 13:19:32.089  3563  3563 I ConfigService: onCreate
,11-23 13:19:32.089  3715  5992 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
11-23 13:19:32.093  3563  5993 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/config.db'.
11-23 13:19:32.093  3563  5993 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-23 13:19:32.093  3563  5993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-23 13:19:32.093  3563  5993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-23 13:19:32.093  3563  5993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-23 13:19:32.093  3563  5993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-23 13:19:32.093  3563  5993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-23 13:19:32.093  3563  5993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-23 13:19:32.093  3563  5993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-23 13:19:32.093  3563  5993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-23 13:19:32.093  3563  5993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-23 13:19:32.093  3563  5993 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-23 13:19:32.093  3563  5993 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-23 13:19:32.093  3563  5993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-23 13:19:32.093  3563  5993 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-23 13:19:32.093  3563  5993 E SQLiteDatabase: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-23 13:19:32.093  3563  5993 E SQLiteDatabase: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-23 13:19:32.093  3563  5993 E SQLiteDatabase: 	at java.lang.Thread.run(Thread.java:818)
,11-23 13:19:32.093  3563  5993 E SQLiteOpenHelper: Couldn't open config.db for writing (will try read-only):
11-23 13:19:32.093  3563  5993 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-23 13:19:32.093  3563  5993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-23 13:19:32.093  3563  5993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-23 13:19:32.093  3563  5993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-23 13:19:32.093  3563  5993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-23 13:19:32.093  3563  5993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-23 13:19:32.093  3563  5993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-23 13:19:32.093  3563  5993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-23 13:19:32.093  3563  5993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-23 13:19:32.093  3563  5993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-23 13:19:32.093  3563  5993 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-23 13:19:32.093  3563  5993 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-23 13:19:32.093  3563  5993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-23 13:19:32.093  3563  5993 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-23 13:19:32.093  3563  5993 E SQLiteOpenHelper: 	at com.google.android.gms.config.ConfigService.a(SourceFile:49)
11-23 13:19:32.093  3563  5993 E SQLiteOpenHelper: 	at com.google.android.gms.config.j.run(SourceFile:152)
11-23 13:19:32.093  3563  5993 E SQLiteOpenHelper: 	at java.lang.Thread.run(Thread.java:818)
11-23 13:19:32.095  3563  5993 W SQLiteOpenHelper: Opened config.db in read-only mode
11-23 13:19:32.096  3715  5992 D AccountUtils: Clearing selected account for com.test.thalitest
,11-23 13:19:32.121  3650  5986 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,11-23 13:19:32.150  3715  5992 I LocationSettingsChecker: Removing dialog suppression flag for package com.test.thalitest
,11-23 13:19:32.163  3715  5992 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.gms/databases/phenotype.db'.
11-23 13:19:32.163  3715  5992 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-23 13:19:32.163  3715  5992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-23 13:19:32.163  3715  5992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-23 13:19:32.163  3715  5992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-23 13:19:32.163  3715  5992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-23 13:19:32.163  3715  5992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-23 13:19:32.163  3715  5992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-23 13:19:32.163  3715  5992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-23 13:19:32.163  3715  5992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-23 13:19:32.163  3715  5992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-23 13:19:32.163  3715  5992 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-23 13:19:32.163  3715  5992 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-23 13:19:32.163  3715  5992 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-23 13:19:32.163  3715  5992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-23 13:19:32.163  3715  5992 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-23 13:19:32.163  3715  5992 E SQLiteDatabase: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-23 13:19:32.163  3715  5992 E SQLiteDatabase: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-23 13:19:32.163  3715  5992 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 13:19:32.163  3715  5992 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
11-23 13:19:32.163  3715  5992 E SQLiteDatabase: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-23 13:19:32.164  3715  5992 E SQLiteOpenHelper: Couldn't open phenotype.db for writing (will try read-only):
11-23 13:19:32.164  3715  5992 E SQLiteOpenHelper: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
11-23 13:19:32.164  3715  5992 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
11-23 13:19:32.164  3715  5992 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
11-23 13:19:32.164  3715  5992 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
11-23 13:19:32.164  3715  5992 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
11-23 13:19:32.164  3715  5992 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
11-23 13:19:32.164  3715  5992 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
11-23 13:19:32.164  3715  5992 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
11-23 13:19:32.164  3715  5992 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
11-23 13:19:32.164  3715  5992 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
11-23 13:19:32.164  3715  5992 E SQLiteOpenHelper: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
11-23 13:19:32.164  3715  5992 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-23 13:19:32.164  3715  5992 E SQLiteOpenHelper: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
11-23 13:19:32.164  3715  5992 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
11-23 13:19:32.164  3715  5992 E SQLiteOpenHelper: 	at android.database.sqlite.SQLiteOpenHelper.getReadableDatabase(SQLiteOpenHelper.java:187)
11-23 13:19:32.164  3715  5992 E SQLiteOpenHelper: 	at com.google.android.gms.app.service.PackageBroadcastService.onHandleIntent(SourceFile:70)
11-23 13:19:32.164  3715  5992 E SQLiteOpenHelper: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
11-23 13:19:32.164  3715  5992 E SQLiteOpenHelper: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 13:19:32.164  3715  5992 E SQLiteOpenHelper: 	at android.os.Looper.loop(Looper.java:148)
11-23 13:19:32.164  3715  5992 E SQLiteOpenHelper: 	at android.os.HandlerThread.run(HandlerThread.java:61)
11-23 13:19:32.165  3715  5992 W SQLiteOpenHelper: Opened phenotype.db in read-only mode
,--------- beginning of crash
11-23 13:19:32.186  3389  3413 E AndroidRuntime: FATAL EXCEPTION: ContactsProviderWorker
11-23 13:19:32.186  3389  3413 E AndroidRuntime: Process: android.process.acore, PID: 3389
11-23 13:19:32.186  3389  3413 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 2570)
11-23 13:19:32.186  3389  3413 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
11-23 13:19:32.186  3389  3413 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
11-23 13:19:32.186  3389  3413 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransactionUnchecked(SQLiteSession.java:437)
11-23 13:19:32.186  3389  3413 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.endTransaction(SQLiteSession.java:401)
11-23 13:19:32.186  3389  3413 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:522)
11-23 13:19:32.186  3389  3413 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.updateDirectoriesForPackage(ContactDirectoryManager.java:411)
11-23 13:19:32.186  3389  3413 E AndroidRuntime: 	at com.android.providers.contacts.ContactDirectoryManager.onPackageChanged(ContactDirectoryManager.java:360)
11-23 13:19:32.186  3389  3413 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2.performBackgroundTask(ContactsProvider2.java:1753)
11-23 13:19:32.186  3389  3413 E AndroidRuntime: 	at com.android.providers.contacts.ContactsProvider2$1.handleMessage(ContactsProvider2.java:1516)
11-23 13:19:32.186  3389  3413 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
11-23 13:19:32.186  3389  3413 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
11-23 13:19:32.186  3389  3413 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,11-23 13:19:32.229  3389  3413 I Process : Sending signal. PID: 3389 SIG: 9
,11-23 13:19:32.257  3715  6000 I GMPM-SVC: App measurement is starting up
,11-23 13:19:32.270  3715  6000 E GMPM-SVC: AppMeasurementService not registered/enabled
,11-23 13:19:32.271  3715  6000 E GMPM-SVC: Uploading is not possible. App measurement disabled
,11-23 13:19:32.464   382   479 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
