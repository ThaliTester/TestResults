#### Test 8289468223f5822_thali06_Huawei-Nexus 6P Logs


```
--------- beginning of main
08-29 09:12:23.517  3576  5614 D GetCommittedConfigurationOperation: no corresponding serverToken: com.google.android.gms.playlog.uploader
08-29 09:12:24.038  3576  5615 I SQLiteConnectionPool: The connection pool for /data/user/0/com.google.android.gms/databases/phenotype.db has been closed but there are still 1 connections in use.  They will be closed as they are released back to the pool.
08-29 09:12:24.041  3576  5615 E ClearcutLoggerIntentService: attempt to re-open an already-closed object: SQLiteDatabase: /data/user/0/com.google.android.gms/databases/phenotype.db
08-29 09:12:24.041  3576  5615 E ClearcutLoggerIntentService: java.lang.IllegalStateException: attempt to re-open an already-closed object: SQLiteDatabase: /data/user/0/com.google.android.gms/databases/phenotype.db
08-29 09:12:24.041  3576  5615 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteClosable.acquireReference(SQLiteClosable.java:55)
08-29 09:12:24.041  3576  5615 E ClearcutLoggerIntentService: 	at android.database.sqlite.SQLiteDatabase.endTransaction(SQLiteDatabase.java:520)
08-29 09:12:24.041  3576  5615 E ClearcutLoggerIntentService: 	at com.google.android.gms.phenotype.service.a.g.a(SourceFile:143)
08-29 09:12:24.041  3576  5615 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:532)
08-29 09:12:24.041  3576  5615 E ClearcutLoggerIntentService: 	at com.google.android.gms.clearcut.service.a.a(SourceFile:149)
08-29 09:12:24.041  3576  5615 E ClearcutLoggerIntentService: 	at com.google.android.gms.common.service.g.run(SourceFile:178)
08-29 09:12:24.041  3576  5615 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-29 09:12:24.041  3576  5615 E ClearcutLoggerIntentService: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-29 09:12:24.041  3576  5615 E ClearcutLoggerIntentService: 	at java.lang.Thread.run(Thread.java:818)
,08-29 09:12:24.710  5616  5616 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-29 09:12:24.717  5616  5616 D AndroidRuntime: CheckJNI is OFF
08-29 09:12:24.746  5616  5616 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 09:12:24.781  5616  5616 I Radio-JNI: register_android_hardware_Radio DONE
08-29 09:12:24.797  5616  5616 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-29 09:12:24.802   930  3533 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-29 09:12:24.850   930  3533 I ActivityManager: Start proc 5625:com.test.thalitest/u0a77 for activity com.test.thalitest/.MainActivity
08-29 09:12:24.855  5616  5616 D AndroidRuntime: Shutting down VM
08-29 09:12:24.940  5625  5625 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011750)
08-29 09:12:24.972  5625  5625 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-29 09:12:24.996  5625  5625 I LibraryLoader: Time to load native libraries: 18 ms (timestamps 1959-1977)
08-29 09:12:24.996  5625  5625 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 09:12:25.014  5625  5625 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8bfae43}
08-29 09:12:25.014  5625  5625 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-29 09:12:25.015  5625  5625 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-29 09:12:25.019  5625  5625 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-29 09:12:25.021  5625  5625 E SysUtils: ApplicationContext is null in ApplicationStatus
08-29 09:12:25.053  5625  5625 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-29 09:12:25.066  5625  5625 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 09:12:25.066  5625  5625 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-29 09:12:25.066  5625  5625 I Adreno  : QUALCOMM build                   : 63c06b2, I8366cd0437
08-29 09:12:25.066  5625  5625 I Adreno  : Build Date                       : 10/21/15
08-29 09:12:25.066  5625  5625 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-29 09:12:25.066  5625  5625 I Adreno  : Local Branch                     : 
08-29 09:12:25.066  5625  5625 I Adreno  : Remote Branch                    : quic/LA.BF64.1.2.9_v2
08-29 09:12:25.066  5625  5625 I Adreno  : Remote Branch                    : NONE
08-29 09:12:25.066  5625  5625 I Adreno  : Reconstruct Branch               : NOTHING
,08-29 09:12:25.117   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1164cd7:true
,08-29 09:12:25.157  5625  5625 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-29 09:12:25.167  5625  5625 D SystemWebViewEngine: CordovaWebView is running on device made by: Huawei
,08-29 09:12:25.192  5625  5662 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-29 09:12:25.199  5625  5649 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-29 09:12:25.226  5625  5662 I OpenGLRenderer: Initialized EGL, version 1.4
,08-29 09:12:25.309   930   948 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +419ms (total +486ms)
,08-29 09:12:25.333  5625  5625 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 5625
,08-29 09:12:25.412  5625  5625 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-29 09:12:25.586  5625  5665 D jxcore_app_log: JniHelper::setJavaVM(0xf527c000), pthread_self() = -566752976
,08-29 09:12:25.592  5625  5665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-29 09:12:25.592  5625  5665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-29 09:12:25.592  5625  5665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-29 09:12:25.592  5625  5665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-29 09:12:25.592  5625  5665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-29 09:12:25.592  5625  5665 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@61418f1 added. We now have 1 listener(s)
,08-29 09:12:25.596  5625  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 60:83:34:25:D7:C6
,08-29 09:12:25.597  5625  5665 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 09:12:25.597  5625  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 09:12:25.598  5625  5665 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 09:12:25.602  5625  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-29 09:12:25.602  5625  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-29 09:12:25.602  5625  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-29 09:12:25.602  5625  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 60:83:34:25:D7:C6
08-29 09:12:25.602  5625  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-29 09:12:25.602  5625  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-29 09:12:25.602  5625  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-29 09:12:25.602  5625  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-29 09:12:25.602  5625  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-29 09:12:25.602  5625  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-29 09:12:25.602  5625  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-29 09:12:25.602  5625  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-29 09:12:25.602  5625  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-29 09:12:25.602  5625  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-29 09:12:25.602  5625  5665 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@337c644 added. We now have 1 listener(s)
08-29 09:12:25.602  5625  5665 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:12:25.605   930  2939 D WifiService: New client listening to asynchronous messages
,08-29 09:12:25.606  5625  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 09:12:25.606  5625  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-29 09:12:25.606  5625  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
,08-29 09:12:25.606  5625  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-29 09:12:25.606  5625  5665 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-29 09:12:25.609  5625  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:12:25.610  5625  5665 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 60:83:34:25:D7:C6
,08-29 09:12:25.615  5625  5665 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-29 09:12:25.615  5625  5665 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:12:25.615  5625  5665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:25.615  5625  5665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:25.615  5625  5665 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:12:25.615  5625  5665 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:12:25.615  5625  5665 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:12:25.615  5625  5665 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:12:25.615  5625  5665 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:12:25.615  5625  5665 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-29 09:12:25.616  5625  5665 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:12:25.616  5625  5665 I io.jxcore.node.LifeCycleMonitor: start: OK
08-29 09:12:25.618  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:12:25.621  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:12:25.638  5625  5625 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-29 09:12:25.910  5625  5671 W jxcore-log: Initializing JXcore engine
08-29 09:12:25.910  5625  5671 W jxcore-log: JXcore engine is ready
,08-29 09:12:25.922  5671  5671 W Thread-57: type=1400 audit(0.0:67): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=12770 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
,08-29 09:12:25.922  5671  5671 W Thread-57: type=1400 audit(0.0:68): avc: denied { ioctl } for path="socket:[6337]" dev="sockfs" ino=6337 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-29 09:12:25.922  5671  5671 W Thread-57: type=1400 audit(0.0:69): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=7220 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
,08-29 09:12:25.922  5671  5671 W Thread-57: type=1400 audit(0.0:70): avc: denied { ioctl } for path="socket:[31418]" dev="sockfs" ino=31418 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-29 09:12:25.944  5625  5671 W jxcore-log: Starting JXcore engine
,08-29 09:12:25.995  5625  5671 W jxcore-log: Platform android
08-29 09:12:25.995  5625  5671 W jxcore-log: 
08-29 09:12:25.995  5625  5671 W jxcore-log: Process ARCH arm
08-29 09:12:25.995  5625  5671 W jxcore-log: 
,08-29 09:12:26.092  5625  5671 I jxcore-log: JXcore Cordova bridge is ready!
08-29 09:12:26.092  5625  5671 I jxcore-log: 
,08-29 09:12:26.092  5625  5671 W jxcore-log: JXcore engine is started
,08-29 09:12:26.099  5625  5665 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-29 09:12:26.103  5625  5625 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-29 09:12:29.020   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:12:30.021   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:12:31.021   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:12:32.022   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:12:32.824  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-29 09:12:32.824  5625  5671 I jxcore-log: 
,08-29 09:12:32.826  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-29 09:12:32.826  5625  5671 I jxcore-log: 
,08-29 09:12:32.830  5625  5671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:12:32.830  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:32.830  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:32.830  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:12:32.830  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:12:32.830  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:12:32.830  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:12:32.830  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:12:32.831  5625  5671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-29 09:12:32.833  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-29 09:12:32.833  5625  5671 I jxcore-log: 
,08-29 09:12:32.834  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-29 09:12:32.834  5625  5671 I jxcore-log: 
,08-29 09:12:33.023   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:12:33.190  5625  5671 D executeNativeTests: Running unit tests
,08-29 09:12:33.229  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 09:12:33.229  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddd5181 added. We now have 2 listener(s)
08-29 09:12:33.230  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 09:12:33.230  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 09:12:33.230  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:12:33.230  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:12:33.230  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 added. We now have 2 listener(s)
08-29 09:12:33.230  5625  5671 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:12:33.231  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 09:12:33.233  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:12:33.236  5625  5671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:12:33.236  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:33.236  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:33.236  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:12:33.236  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:12:33.236  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:12:33.236  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:12:33.236  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:12:33.236  5625  5671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:12:33.237  5625  5671 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 09:12:33.239  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
,08-29 09:12:33.239  5625  5671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
,08-29 09:12:33.239  5625  5671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 09:12:33.240  5625  5671 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
,08-29 09:12:33.240  5625  5671 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 09:12:33.240  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
,08-29 09:12:33.240  5625  5671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-29 09:12:33.240  5625  5671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 09:12:33.241  5625  5671 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:12:33.241  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:12:33.241  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:12:33.241  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:33.242  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:12:33.242  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:12:33.242  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:12:33.242  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddd5181 removed from the list
08-29 09:12:33.242  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.242  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 removed from the list
08-29 09:12:33.243  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:12:33.243  5625  5671 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:12:33.243  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.244  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.244  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.246  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:12:33.246  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:12:33.246  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.246  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.247  5625  5671 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-29 09:12:33.248  5625  5671 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:12:33.248  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:12:33.248  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:12:33.248  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:33.248  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.248  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:12:33.248  5625  5671 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddd5181 not in the list
08-29 09:12:33.248  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.248  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.250  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:12:33.250  5625  5671 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:12:33.250  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.250  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.250  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.250  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.251  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:12:33.251  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:12:33.251  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.252  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 09:12:33.254  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 09:12:33.255  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 09:12:33.255  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 09:12:33.255  5625  5671 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:12:33.255  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:12:33.255  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:12:33.255  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:33.255  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.255  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.255  5625  5671 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddd5181 not in the list
08-29 09:12:33.255  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.255  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.255  5625  5671 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:12:33.255  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.255  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.255  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.255  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.255  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:12:33.256  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:12:33.256  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.256  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.256  5625  5671 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 09:12:33.257  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:12:33.259  5625  5671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:12:33.259  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:33.259  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:33.259  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:12:33.259  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:12:33.259  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:12:33.259  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:12:33.259  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:12:33.260  5625  5671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:12:33.260  5625  5671 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:12:33.260  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:12:33.260  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 09:12:33.260  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 09:12:33.260  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:12:33.260  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 09:12:33.262  5625  5671 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 09:12:33.262  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 09:12:33.262  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:12:33.265  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 09:12:33.265  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:12:33.266  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 09:12:33.267  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 09:12:33.269  5625  5671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (SUPPORTED) in persistent storage
08-29 09:12:33.272  5625  5671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (SUPPORTED) in persistent storage
08-29 09:12:33.272  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 09:12:33.272  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 09:12:33.273  5625  5671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 09:12:33.273  5625  5671 D BluetoothAdapter: STATE_ON
08-29 09:12:33.277  4356  4369 D BtGatt.GattService: registerClient() - UUID=61a1e193-7b38-4ecc-9bec-feccd3c79fec
08-29 09:12:33.278  4356  4452 D BtGatt.GattService: onClientRegistered() - UUID=61a1e193-7b38-4ecc-9bec-feccd3c79fec, clientIf=5
08-29 09:12:33.279  5625  5636 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 09:12:33.280  4356  4618 D BtGatt.GattService: start scan with filters
08-29 09:12:33.283  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 09:12:33.283  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 09:12:33.283  4356  4455 D BtGatt.ScanManager: handling starting scan
,08-29 09:12:33.284  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 09:12:33.284  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 09:12:33.286  4356  4455 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35c60b5
08-29 09:12:33.288  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 09:12:33.288  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 09:12:33.289  5625  5625 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 09:12:33.289  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 09:12:33.290  5625  5671 I io.jxcore.node.ConnectionHelper: start: OK
08-29 09:12:33.291  5625  5671 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:12:33.291  5625  5671 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 09:12:33.292  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 09:12:33.292  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 09:12:33.292  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.292  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 09:12:33.292  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 09:12:33.292  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 09:12:33.292  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 09:12:33.292  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 09:12:33.292  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 09:12:33.292  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 09:12:33.292  5625  5671 D BluetoothAdapter: STATE_ON
08-29 09:12:33.293  4356  4618 D BtGatt.GattService: stopScan() - queue size =1
08-29 09:12:33.293  4356  4452 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 09:12:33.293  4356  4452 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:33.294  4356  4597 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 09:12:33.294  4356  4455 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 09:12:33.294  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:12:33.294  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 09:12:33.294  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 09:12:33.294  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 09:12:33.294  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 09:12:33.296  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:12:33.296  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 09:12:33.297  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 09:12:33.297  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 09:12:33.297  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:12:33.298  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:33.298  5625  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:12:33.298  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.298  5625  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:12:33.298  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:12:33.299  5625  5625 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:12:33.299  5625  5671 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddd5181 not in the list
08-29 09:12:33.299  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.299  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.299  5625  5671 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:12:33.299  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.299  5625  5671 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 09:12:33.300  4356  4452 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 09:12:33.300  4356  4452 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:33.301  4356  4455 D BtGatt.ScanManager: Starting BLE batch scan
08-29 09:12:33.301  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:12:33.301  4356  4455 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 09:12:33.305  5625  5671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:12:33.305  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:33.305  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:33.305  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:12:33.305  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:12:33.305  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:12:33.305  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:12:33.305  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:12:33.309  5625  5671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:12:33.309  5625  5671 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:12:33.309  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:12:33.309  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 09:12:33.309  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 09:12:33.309  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:12:33.309  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 09:12:33.309  4356  4452 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 09:12:33.309  4356  4452 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:33.311  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:12:33.313  5625  5671 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 09:12:33.314  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 09:12:33.315  4356  4452 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 09:12:33.315  4356  4452 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:33.317  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:12:33.317  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 09:12:33.318  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 09:12:33.318  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 09:12:33.320  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 09:12:33.320  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 09:12:33.320  5625  5671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 09:12:33.321  5625  5671 D BluetoothAdapter: STATE_ON
08-29 09:12:33.321  4356  4452 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 09:12:33.321  4356  4452 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:33.322  4356  4455 D BtGatt.ScanManager: stopping BLe Batch
08-29 09:12:33.323  4356  4367 D BtGatt.GattService: registerClient() - UUID=971f573e-7c36-446d-845a-93e20a05a384
08-29 09:12:33.323  4356  4452 D BtGatt.GattService: onClientRegistered() - UUID=971f573e-7c36-446d-845a-93e20a05a384, clientIf=5
08-29 09:12:33.323  5625  5635 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 09:12:33.324  4356  4618 D BtGatt.GattService: start scan with filters
,08-29 09:12:33.326  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 09:12:33.326  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 09:12:33.326  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 09:12:33.326  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 09:12:33.327  4356  4452 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 09:12:33.327  4356  4452 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:33.327  4356  4455 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 09:12:33.330  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 09:12:33.330  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 09:12:33.330  5625  5625 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 09:12:33.331  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 09:12:33.331  4356  4452 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 09:12:33.331  4356  4452 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:33.332  4356  4455 D BtGatt.ScanManager: handling starting scan
,08-29 09:12:33.333  5625  5671 I io.jxcore.node.ConnectionHelper: start: OK
,08-29 09:12:33.334  5625  5671 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:12:33.335  5625  5671 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 09:12:33.335  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 09:12:33.335  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 09:12:33.335  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.335  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 09:12:33.335  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 09:12:33.335  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 09:12:33.335  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 09:12:33.335  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 09:12:33.335  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
,08-29 09:12:33.335  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
08-29 09:12:33.336  5625  5671 D BluetoothAdapter: STATE_ON
08-29 09:12:33.336  4356  4618 D BtGatt.GattService: stopScan() - queue size =1
08-29 09:12:33.337  4356  4367 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 09:12:33.337  4356  4452 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 09:12:33.337  4356  4452 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:33.337  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
,08-29 09:12:33.337  4356  4455 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 09:12:33.337  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 09:12:33.337  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 09:12:33.337  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 09:12:33.337  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 09:12:33.340  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:12:33.340  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
,08-29 09:12:33.340  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 09:12:33.340  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 09:12:33.340  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:12:33.341  5625  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:12:33.341  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:33.341  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.341  5625  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:12:33.341  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:12:33.341  5625  5625 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 09:12:33.341  5625  5671 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddd5181 not in the list
08-29 09:12:33.341  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.341  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.341  5625  5671 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:12:33.342  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:12:33.342  4356  4452 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 09:12:33.342  4356  4452 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 09:12:33.342  4356  4455 D BtGatt.ScanManager: Starting BLE batch scan
08-29 09:12:33.342  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.342  4356  4455 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 09:12:33.342  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.343  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:12:33.343  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:12:33.343  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.343  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.344  5625  5671 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-29 09:12:33.345  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:12:33.348  5625  5671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:12:33.348  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:33.348  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:33.348  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:12:33.348  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:12:33.348  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:12:33.348  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:12:33.348  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:12:33.349  5625  5671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:12:33.350  5625  5671 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:12:33.350  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:12:33.350  4356  4452 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
,08-29 09:12:33.350  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 09:12:33.350  4356  4452 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:33.350  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 09:12:33.350  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:12:33.350  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 09:12:33.352  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:12:33.353  5625  5671 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 09:12:33.353  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 09:12:33.354  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:12:33.354  4356  4452 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 09:12:33.354  4356  4452 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:33.356  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 09:12:33.357  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 09:12:33.357  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 09:12:33.359  4356  4452 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 09:12:33.359  4356  4452 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:33.359  4356  4455 D BtGatt.ScanManager: stopping BLe Batch
08-29 09:12:33.360  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 09:12:33.360  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 09:12:33.360  5625  5671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 09:12:33.361  5625  5671 D BluetoothAdapter: STATE_ON
08-29 09:12:33.363  4356  4452 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 09:12:33.363  4356  4452 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:33.364  4356  4367 D BtGatt.GattService: registerClient() - UUID=bf8f65bc-d94f-425f-bfbc-9081b9611917
,08-29 09:12:33.364  4356  4455 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 09:12:33.364  4356  4452 D BtGatt.GattService: onClientRegistered() - UUID=bf8f65bc-d94f-425f-bfbc-9081b9611917, clientIf=5
08-29 09:12:33.364  5625  5636 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 09:12:33.364  4356  4369 D BtGatt.GattService: start scan with filters
,08-29 09:12:33.367  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 09:12:33.367  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 09:12:33.367  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 09:12:33.367  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
08-29 09:12:33.367  4356  4452 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 09:12:33.367  4356  4452 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:33.368  4356  4455 D BtGatt.ScanManager: handling starting scan
08-29 09:12:33.369  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 09:12:33.369  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 09:12:33.369  5625  5625 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 09:12:33.370  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 09:12:33.372  4356  4452 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 09:12:33.372  5625  5671 I io.jxcore.node.ConnectionHelper: start: OK
08-29 09:12:33.372  4356  4452 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:33.372  5625  5671 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:12:33.372  5625  5671 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 09:12:33.372  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 09:12:33.372  4356  4455 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 09:12:33.373  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
,08-29 09:12:33.373  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.373  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 09:12:33.373  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 09:12:33.373  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 09:12:33.373  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 09:12:33.373  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 09:12:33.373  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 09:12:33.373  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 09:12:33.374  5625  5671 D BluetoothAdapter: STATE_ON
08-29 09:12:33.374  4356  4367 D BtGatt.GattService: stopScan() - queue size =1
08-29 09:12:33.374  4356  4597 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 09:12:33.375  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:12:33.375  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 09:12:33.375  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 09:12:33.375  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 09:12:33.375  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 09:12:33.376  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
,08-29 09:12:33.376  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 09:12:33.376  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 09:12:33.376  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 09:12:33.376  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:12:33.377  4356  4452 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
,08-29 09:12:33.377  4356  4452 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:33.377  4356  4455 D BtGatt.ScanManager: Starting BLE batch scan
,08-29 09:12:33.377  4356  4455 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 09:12:33.377  5625  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:12:33.377  5625  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:12:33.377  5625  5625 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:12:33.377  5625  5671 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:12:33.377  5625  5671 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
08-29 09:12:33.378  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:12:33.378  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:12:33.378  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:33.378  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.378  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:12:33.378  5625  5671 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddd5181 not in the list
08-29 09:12:33.378  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.379  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.379  5625  5671 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:12:33.379  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.379  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.379  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:12:33.380  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 09:12:33.380  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:12:33.380  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.380  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.381  5625  5671 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-29 09:12:33.381  5625  5671 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:12:33.381  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:12:33.381  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:12:33.381  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:33.381  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.381  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.382  5625  5671 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddd5181 not in the list
08-29 09:12:33.382  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.382  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.382  5625  5671 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:12:33.382  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:12:33.382  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.382  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.382  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.382  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:12:33.382  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:12:33.382  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.383  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.383  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
,08-29 09:12:33.383  5625  5671 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:12:33.383  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:12:33.384  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:12:33.384  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:33.384  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.384  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:12:33.384  5625  5671 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddd5181 not in the list
08-29 09:12:33.384  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.384  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.384  5625  5671 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:12:33.384  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.384  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.384  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.384  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.385  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:12:33.385  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:12:33.385  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:12:33.385  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.385  4356  4452 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 09:12:33.385  4356  4452 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:33.385  5625  5671 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-29 09:12:33.385  5625  5671 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:12:33.385  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:12:33.385  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:12:33.386  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:33.386  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.386  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.386  5625  5671 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddd5181 not in the list
08-29 09:12:33.386  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.386  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.386  5625  5671 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:12:33.386  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.386  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.386  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.386  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.387  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:12:33.387  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:12:33.387  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.387  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.388  5625  5671 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-29 09:12:33.388  5625  5671 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:12:33.388  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:12:33.388  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:12:33.388  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:33.388  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.Blu,etoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.388  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.388  5625  5671 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddd5181 not in the list
08-29 09:12:33.388  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.388  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.388  5625  5671 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:12:33.388  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.388  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.388  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.388  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.389  4356  4452 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 09:12:33.389  4356  4452 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:33.389  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:12:33.389  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:12:33.390  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.390  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.390  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 09:12:33.390  5625  5671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 09:12:33.391  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 09:12:33.391  5625  5671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 09:12:33.391  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-29 09:12:33.391  5625  5671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-29 09:12:33.391  5625  5671 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:12:33.391  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:12:33.391  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:12:33.391  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:33.391  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.392  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.392  5625  5671 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddd5181 not in the list
08-29 09:12:33.392  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.392  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.392  5625  5671 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:12:33.392  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.392  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.392  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.392  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.395  4356  4452 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 09:12:33.395  4356  4452 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:33.395  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:12:33.395  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:12:33.395  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.395  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
,08-29 09:12:33.396  4356  4455 D BtGatt.ScanManager: stopping BLe Batch
,08-29 09:12:33.396  5625  5671 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 09:12:33.396  5625  5671 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 09:12:33.396  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-29 09:12:33.399  5625  5671 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 09:12:33.400  5625  5671 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-29 09:12:33.400  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-29 09:12:33.400  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-29 09:12:33.400  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-29 09:12:33.400  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-29 09:12:33.400  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
,08-29 09:12:33.400  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-29 09:12:33.400  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-29 09:12:33.400  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-29 09:12:33.400  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-29 09:12:33.400  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-29 09:12:33.400  4356  4452 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 09:12:33.401  4356  4452 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:33.401  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
,08-29 09:12:33.401  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-29 09:12:33.401  4356  4455 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 09:12:33.401  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-29 09:12:33.401  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-29 09:12:33.401  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-29 09:12:33.401  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-29 09:12:33.401  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-29 09:12:33.401  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
,08-29 09:12:33.401  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-29 09:12:33.401  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-29 09:12:33.401  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-29 09:12:33.401  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-29 09:12:33.402  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-29 09:12:33.402  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
,08-29 09:12:33.402  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-29 09:12:33.402  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-29 09:12:33.402  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-29 09:12:33.402  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-29 09:12:33.402  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-29 09:12:33.402  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-29 09:12:33.402  5625  5671 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-29 09:12:33.402  5625  5671 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 09:12:33.403  5625  5671 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
,08-29 09:12:33.403  5625  5671 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 09:12:33.403  5625  5671 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 09:12:33.403  5625  5671 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-29 09:12:33.403  5625  5671 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-29 09:12:33.403  5625  5671 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-29 09:12:33.403  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
,08-29 09:12:33.405  4356  4452 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
,08-29 09:12:33.405  4356  4452 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 09:12:33.407  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-29 09:12:33.407  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-29 09:12:33.407  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
,08-29 09:12:33.408  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-29 09:12:33.408  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-29 09:12:33.408  5625  5671 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-29 09:12:33.408  5625  5671 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
,08-29 09:12:33.408  5625  5671 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-29 09:12:33.409  5625  5671 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:12:33.409  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:12:33.409  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:12:33.409  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:33.409  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.409  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.409  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-29 09:12:33.409  5625  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 121)
08-29 09:12:33.410  5625  5671 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddd5181 not in the list
08-29 09:12:33.410  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.410  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.410  5625  5671 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:12:33.410  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:12:33.410  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.410  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.410  5625  5673 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 121
08-29 09:12:33.410  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:12:33.412  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:12:33.412  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:12:33.412  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:12:33.412  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.413  5625  5671 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-29 09:12:33.413  5625  5671 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:12:33.413  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:12:33.413  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:12:33.413  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:33.413  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.413  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:12:33.413  5625  5671 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddd5181 not in the list
08-29 09:12:33.413  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.413  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.413  5625  5671 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:12:33.413  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.414  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.414  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.414  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.414  5625  5672 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:12:33.416  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:12:33.416  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-29 09:12:33.416  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.416  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.416  5625  5671 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-29 09:12:33.417  5625  5671 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:12:33.417  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:12:33.417  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:12:33.417  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:33.417  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.417  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.417  5625  5671 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddd5181 not in the list
08-29 09:12:33.417  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:12:33.417  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.417  5625  5671 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:12:33.417  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.417  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.417  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.417  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:12:33.419  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 09:12:33.419  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:12:33.419  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.420  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.420  5625  5671 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-29 09:12:33.420  5625  5671 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-29 09:12:33.420  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 09:12:33.420  5625  5671 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-29 09:12:33.420  5625  5671 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 09:12:33.421  5625  5671 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-29 09:12:33.421  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
,08-29 09:12:33.421  5625  5671 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-29 09:12:33.421  5625  5671 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-29 09:12:33.421  5625  5671 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-29 09:12:33.421  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 09:12:33.421  5625  5671 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-29 09:12:33.421  5625  5671 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:12:33.421  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:12:33.421  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:12:33.421  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:33.421  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.421  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:12:33.421  5625  5671 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddd5181 not in the list
08-29 09:12:33.421  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.421  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.422  5625  5671 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:12:33.422  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.422  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.422  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.422  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:12:33.423  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 09:12:33.424  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:12:33.424  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.424  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.424  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:33.424  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.424  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.424  5625  5671 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddd5181 not in the list
08-29 09:12:33.424  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.424  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.424  5625  5671 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:12:33.425  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.425  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.425  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.425  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
,08-29 09:12:33.425  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:33.425  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.425  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.425  5625  5671 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddd5181 not in the list
08-29 09:12:33.425  5625  5671 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:12:33.425  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:12:33.425  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:12:33.425  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:33.425  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.425  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.425  5625  5671 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddd5181 not in the list
08-29 09:12:33.425  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:12:33.425  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.426  5625  5671 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:12:33.426  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.426  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.426  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.426  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.426  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:12:33.427  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:12:33.427  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.427  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.428  5625  5671 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-29 09:12:33.428  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:12:33.428  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-29 09:12:33.430  5625  5671 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-29 09:12:33.430  5625  5671 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
,08-29 09:12:33.430  5625  5625 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-29 09:12:33.430  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-29 09:12:33.430  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 09:12:33.431  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:33.431  5625  5674 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:12:33.431  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-29 09:12:33.431  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-29 09:12:33.431  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-29 09:12:33.431  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.431  5625  5671 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-29 09:12:33.431  5625  5625 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-29 09:12:33.431  5625  5671 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddd5181 not in the list
,08-29 09:12:33.431  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.431  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 09:12:33.431  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 09:12:33.431  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 09:12:33.432  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.432  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.432  5625  5674 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-29 09:12:33.433  5625  5674 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-29 09:12:33.433  5625  5674 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-29 09:12:33.433  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:12:33.433  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
,08-29 09:12:33.433  5625  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:12:33.433  5625  5671 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:12:33.433  5625  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:12:33.433  5625  5625 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:12:33.433  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:12:33.433  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:12:33.433  5625  5625 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-29 09:12:33.433  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:33.433  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.433  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.433  5625  5671 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddd5181 not in the list
,08-29 09:12:33.433  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.433  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.433  5625  5671 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:12:33.433  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.433  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.433  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.433  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.434  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:12:33.434  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:12:33.434  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.434  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
,08-29 09:12:33.435  5625  5671 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-29 09:12:33.435  5625  5671 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-29 09:12:33.435  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-29 09:12:33.435  5625  5671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-29 09:12:33.435  5625  5671 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:12:33.436  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:12:33.436  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:12:33.436  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:33.436  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.436  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.436  5625  5671 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddd5181 not in the list
08-29 09:12:33.436  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:12:33.436  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.436  5625  5671 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:12:33.436  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.436  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.436  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.436  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.437  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:12:33.437  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:12:33.437  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.437  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.440  5625  5671 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:12:33.440  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:12:33.440  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:12:33.440  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:33.440  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.440  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.440  5625  5671 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddd5181 not in the list
08-29 09:12:33.440  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.441  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.441  5625  5671 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:12:33.441  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.441  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:12:33.441  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.441  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.441  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:12:33.441  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:12:33.442  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.442  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.442  5625  5671 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:12:33.442  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:12:33.442  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:12:33.442  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:33.442  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:12:33.442  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.442  5625  5671 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@ddd5181 not in the list
08-29 09:12:33.443  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:33.443  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.443  5625  5671 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:12:33.443  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.443  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.443  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:33.443  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:33.443  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:12:33.444  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:12:33.444  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:12:33.444  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d73226 not in the list
08-29 09:12:33.444  5625  5671 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-29 09:12:33.444  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 09:12:33.444  5625  5671 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-29 09:12:33.444  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-29 09:12:33.445  5625  5671 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-29 09:12:33.445  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-29 09:12:33.446  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-29 09:12:33.446  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-29 09:12:33.446  5625  5671 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
08-29 09:12:33.446  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 09:12:33.446  5625  5671 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
,08-29 09:12:33.446  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-29 09:12:33.446  5625  5671 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-29 09:12:33.446  5625  5671 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-29 09:12:33.447  5625  5671 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-29 09:12:33.447  5625  5671 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-29 09:12:33.447  5625  5671 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-29 09:12:33.447  5625  5671 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-29 09:12:33.447  5625  5671 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-29 09:12:33.447  5625  5671 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-29 09:12:33.448  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 09:12:33.448  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@afbcc98 added. We now have 2 listener(s)
08-29 09:12:33.448  5625  5671 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:12:33.450  5625  5671 D BluetoothAdapter: enable(): BT is already enabled..!
08-29 09:12:33.450   930  3530 D WifiService: setWifiEnabled: true pid=5625, uid=10077
08-29 09:12:33.450   930  3530 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-29 09:12:33.451  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:12:33.451  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b1c9cf1 added. We now have 3 listener(s)
08-29 09:12:33.451  5625  5671 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:12:33.457  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:12:33.457  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@66670d6 added. We now have 4 listener(s)
08-29 09:12:33.457  5625  5671 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:12:33.459  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 09:12:33.459  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@b836f57 added. We now have 5 listener(s)
08-29 09:12:33.459  5625  5671 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:12:33.461   930  3157 D WifiService: setWifiEnabled: false pid=5625, uid=10077
08-29 09:12:33.461   930  3157 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 09:12:33.463   930  2938 D WifiStateMachine: WifiStateMachine: Leaving Connected state
08-29 09:12:33.464   930  2938 D IpReachabilityMonitor: clear: iface{wlan0/5}, v{4}, ntable=[]
08-29 09:12:33.464   930  2938 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
08-29 09:12:33.464   930  2938 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-29 09:12:33.465  4356  4448 D BluetoothAdapterState: Current state: ON, message: 23
08-29 09:12:33.465  4356  4448 D BluetoothAdapterProperties: Setting state to 13
08-29 09:12:33.465  4356  4448 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 09:12:33.466  4356  4448 D BluetoothAdapterProperties: onBluetoothDisable()
08-29 09:12:33.466  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:12:33.466  4356  4448 I BluetoothAdapterState: Entering PendingCommandState
,08-29 09:12:33.468  4356  4356 D BluetoothMapService: onReceive
,08-29 09:12:33.468  4356  4356 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:12:33.468  4356  4356 D BluetoothMapService: STATE_TURNING_OFF
08-29 09:12:33.469  4356  4356 D BluetoothMapService: MAP Service closeService in
08-29 09:12:33.469  4356  4356 D BluetoothMapMasInstance0: MAP Service shutdown
08-29 09:12:33.469  4356  4356 D ObexServerSockets0: shutdown(block = true)
08-29 09:12:33.469  4356  4356 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 09:12:33.469  4356  4620 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 5
08-29 09:12:33.469  4356  4356 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 09:12:33.470  4356  4621 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 09:12:33.470  4356  4594 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
,08-29 09:12:33.471  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:12:33.471  4356  4356 I BtOppRfcommListener: stopping Accept Thread
08-29 09:12:33.471  5625  5671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:12:33.471  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:33.471  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:33.471  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:12:33.471  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:12:33.471  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:12:33.471  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:12:33.471  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-29 09:12:33.471  4356  5133 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-29 09:12:33.472  4356  5133 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 09:12:33.472  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:12:33.472  5625  5671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:12:33.472  5625  5671 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 09:12:33.475   930  2938 E native  : do suspend true
,08-29 09:12:33.476  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:12:33.478  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:12:33.478   930   943 I ActivityManager: Start proc 5677:com.android.settings/1000 for broadcast com.android.settings/.bluetooth.DockEventReceiver
08-29 09:12:33.479  4356  4452 D BluetoothAdapterProperties: Scan Mode:20
08-29 09:12:33.479  4356  4448 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
,08-29 09:12:33.483  5625  5625 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:12:33.483  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:12:33.483  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:33.483  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:33.483  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:12:33.483  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:12:33.483  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-29 09:12:33.483  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-29 09:12:33.483  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-29 09:12:33.484  4356  4356 D HeadsetService: Received stop request...Stopping profile...
08-29 09:12:33.484  5625  5625 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:12:33.484  5625  5625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-29 09:12:33.488  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:12:33.488  4356  4356 D A2dpService: Received stop request...Stopping profile...
,08-29 09:12:33.488   930   930 D BluetoothHeadset: Proxy object disconnected
08-29 09:12:33.488   930   930 D BluetoothHeadset: Proxy object disconnected
08-29 09:12:33.488  4356  4606 D A2dpStateMachine: Exit Disconnected: -1
08-29 09:12:33.489  3079  3693 D BluetoothHeadset: Proxy object disconnected
08-29 09:12:33.489   930   930 D BluetoothHeadset: Proxy object disconnected
08-29 09:12:33.489  3504  3531 D BluetoothHeadset: Proxy object disconnected
08-29 09:12:33.490   930   930 D BluetoothA2dp: Proxy object disconnected
08-29 09:12:33.491  4356  4356 D HidService: Received stop request...Stopping profile...
08-29 09:12:33.491  4356  4356 D HidService: Stopping Bluetooth HidService
,08-29 09:12:33.491  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:12:33.492  4356  4356 D HealthService: Received stop request...Stopping profile...
,08-29 09:12:33.493  4356  4356 D PanService: Received stop request...Stopping profile...
08-29 09:12:33.493  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:12:33.494  4356  4356 D BluetoothMapService: Received stop request...Stopping profile...
08-29 09:12:33.494  4356  4356 D BluetoothMapService: stop()
08-29 09:12:33.495  4356  4356 D BluetoothMapAppObserver: deinitObservers()
08-29 09:12:33.495  4356  4356 D BluetoothMapAppObserver: removeReceiver()
08-29 09:12:33.496  4356  4356 V BluetoothAdapterState: isTurningOff()=true
08-29 09:12:33.496  4356  4356 V BluetoothAdapterState: isTurningOn()=false
08-29 09:12:33.496  4356  4356 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:12:33.496  4356  4356 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:12:33.497  4356  4356 D SapService: Received stop request...Stopping profile...
08-29 09:12:33.497  4356  4356 V SapService: stop()
08-29 09:12:33.498  3079  3079 D HeadsetProfile: Bluetooth service disconnected
08-29 09:12:33.498  3079  3079 D BluetoothA2dp: Proxy object disconnected
08-29 09:12:33.498  3079  3079 D BluetoothInputDevice: Proxy object disconnected
08-29 09:12:33.498  3079  3079 D HidProfile: Bluetooth service disconnected
08-29 09:12:33.498  3079  3079 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 09:12:33.498  3079  3079 D PanProfile: Bluetooth service disconnected
08-29 09:12:33.498  3079  3079 D BluetoothMap: Proxy object disconnected
08-29 09:12:33.499  3079  3079 D MapProfile: Bluetooth service disconnected
08-29 09:12:33.499  4356  4356 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 09:12:33.499  4356  4356 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
,08-29 09:12:33.499  4356  4452 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 09:12:33.499  4356  4356 V BluetoothAdapterState: isTurningOff()=true
08-29 09:12:33.499  4356  4577 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:12:33.499  4356  4356 V BluetoothAdapterState: isTurningOn()=false
08-29 09:12:33.500  4356  4577 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:12:33.500  4356  4356 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 09:12:33.500  4356  4577 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:12:33.500  4356  4356 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:12:33.500  4356  4452 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 09:12:33.502  4356  4577 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:12:33.502  4356  4577 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:12:33.502  4356  4356 V BluetoothAdapterState: isTurningOff()=true
,08-29 09:12:33.502  4356  4356 V BluetoothAdapterState: isTurningOn()=false
08-29 09:12:33.502  4356  4356 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:12:33.502  4356  4577 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 09:12:33.503  4356  4356 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:12:33.503  4356  4577 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-29 09:12:33.503  4356  4577 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 09:12:33.503  4356  4577 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 09:12:33.503  4356  4356 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-29 09:12:33.503  4356  4452 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100000
08-29 09:12:33.503  4356  4356 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 09:12:33.503  4356  4452 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 09:12:33.503  4356  4356 V BluetoothAdapterState: isTurningOff()=true
08-29 09:12:33.503  4356  4356 V BluetoothAdapterState: isTurningOn()=false
08-29 09:12:33.503  4356  4356 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:12:33.503  4356  4356 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:12:33.503  4356  4356 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 09:12:33.504  4356  4452 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
,08-29 09:12:33.504  4356  4356 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 09:12:33.504  4356  4356 V BluetoothAdapterState: isTurningOff()=true
08-29 09:12:33.505  4356  4356 V BluetoothAdapterState: isTurningOn()=false
08-29 09:12:33.505  4356  4356 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:12:33.505  4356  4356 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:12:33.505  4356  4356 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 09:12:33.505  4356  4356 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 09:12:33.507  4356  4356 D BluetoothMapService: MAP Service closeService in
,08-29 09:12:33.507  4356  4356 V BluetoothAdapterState: isTurningOff()=true
08-29 09:12:33.507  4356  4356 V BluetoothAdapterState: isTurningOn()=false
08-29 09:12:33.507  4356  4356 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:12:33.507  4356  4356 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:12:33.507  4356  4356 D BluetoothMapService: cleanup()
08-29 09:12:33.508  4356  4356 D BluetoothMapService: MAP Service closeService in
08-29 09:12:33.508  4356  4356 V BluetoothAdapterState: isTurningOff()=true
08-29 09:12:33.508  4356  4356 V BluetoothAdapterState: isTurningOn()=false
08-29 09:12:33.508  4356  4356 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:12:33.508  4356  4356 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:12:33.508  4356  4448 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 09:12:33.508  4356  4448 D BluetoothAdapterProperties: Setting state to 15
08-29 09:12:33.508  4356  4448 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 09:12:33.509  3079  3094 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 09:12:33.509  4356  4448 I BluetoothAdapterState: Entering BleOnState
08-29 09:12:33.510  3079  3092 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:12:33.510   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:12:33.510   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:12:33.510  3504  3529 D BluetoothHeadset: onBluetoothStateChange: up=false
,08-29 09:12:33.510   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 09:12:33.511  3079  3693 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 09:12:33.511  3079  3094 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 09:12:33.512   930  5199 D DhcpClient: Clearing IP address
08-29 09:12:33.512   507   923 D CommandListener: Clearing all IP addresses on wlan0
,08-29 09:12:33.514   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:12:33.514  3079  3092 D BluetoothPan: onBluetoothStateChange on: false
08-29 09:12:33.515  3079  3693 D BluetoothMap: onBluetoothStateChange: up=false
,08-29 09:12:33.516  4356  4448 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 09:12:33.516  4356  4448 D BluetoothAdapterProperties: Setting state to 16
,08-29 09:12:33.516  4356  4448 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 09:12:33.517  4356  4448 D BluetoothAdapterProperties: onBleDisable
08-29 09:12:33.517  4356  4448 I BluetoothAdapterState: Entering PendingCommandState
08-29 09:12:33.518  4356  4449 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 09:12:33.519  4356  4452 D BluetoothAdapterProperties: Scan Mode:20
08-29 09:12:33.520   507   923 D CommandListener: Setting iface cfg
08-29 09:12:33.520  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:12:33.524  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:12:33.524  4356  4577 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 09:12:33.524  4356  4577 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:12:33.524  5625  5672 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 121)
,08-29 09:12:33.527  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:12:33.531  3576  5253 V NativeCrypto: Read error: ssl=0x7f905ad880: I/O error during system call, Connection timed out
,08-29 09:12:33.531  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:12:33.532  3576  5253 V NativeCrypto: SSL shutdown failed: ssl=0x7f905ad880: I/O error during system call, Broken pipe
08-29 09:12:33.534   930  3157 D ConnectivityService: reportNetworkConnectivity(100, false) by 10012
08-29 09:12:33.534   930  5197 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Forcing reevaluation for UID 10012
08-29 09:12:33.536   930  5197 D NetworkMonitor/NetworkAgentInfo [WIFI () - 100]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "connectivitycheck.gstatic.com": No address associated with hostname
08-29 09:12:33.537   930  2940 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] validation failed
08-29 09:12:33.537   930  2940 D ConnectivityService: notifyType CAP_CHANGED for NetworkAgentInfo [WIFI () - 100]
08-29 09:12:33.538   930  2940 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
,08-29 09:12:33.539   930  2940 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
,08-29 09:12:33.540  5677  5677 W System  : ClassLoader referenced unknown path: /system/priv-app/Settings/lib/arm64
08-29 09:12:33.540   930  2940 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 3
08-29 09:12:33.544   930  2940 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-29 09:12:33.545  3457  3648 W QCNEJ   : |CORE| network lost: 100
08-29 09:12:33.545  3457  3648 W QCNEJ   : |CORE| onLost: unbind the process to WIFI
,08-29 09:12:33.551   542   542 E Parcel  : Reading a NULL string not supported here.
,08-29 09:12:33.553   930   930 D RttService: SCAN_AVAILABLE : 1
,08-29 09:12:33.553   930  3046 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 09:12:33.556  5677  5677 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 09:12:33.557   930  2938 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-29 09:12:33.561   930  5200 D DhcpClient: Receive thread stopped
,08-29 09:12:33.562   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@e077743:true
08-29 09:12:33.562  3576  3576 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 09:12:33.568   930  2938 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 09:12:33.569   930  2938 E native  : do suspend true
,08-29 09:12:33.569   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t raw -D idletimer_raw_PREROUTING -i wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-29 09:12:33.578   930   941 I ActivityManager: Start proc 5697:com.google.android.apps.maps/u0a58 for broadcast com.google.android.apps.maps/com.google.android.apps.gmm.iamhere.ble.StartBleServiceReceiver
,08-29 09:12:33.592   507   923 V IdletimerController: runCmd(/system/bin/ip6tables -w -t mangle -D idletimer_mangle_POSTROUTING -o wlan0 -j IDLETIMER --timeout 15 --label 1 --send_nl_msg 1) res_ipv4=0, res_ipv6=0
08-29 09:12:33.592   507   923 D CommandListener: Clearing all IP addresses on wlan0
08-29 09:12:33.592   507   923 D TetherController: Setting IP forward enable = 0
08-29 09:12:33.593   930  2940 D CSLegacyTypeTracker: Sending DISCONNECTED broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-29 09:12:33.594   930  2940 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-29 09:12:33.595   930   947 D Tethering: MasterInitialState.processMessage what=3
,08-29 09:12:33.595  5677  5677 D LocalBluetoothProfileManager: Adding local MAP profile
,08-29 09:12:33.598  5119  5119 D MusicLifecycle: com.google.android.music.net.NetworkMonitor$2 generated event: Broadcast received with context com.google.android.music.net.NetworkMonitor@7276dac and intent Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 (has extras) }
08-29 09:12:33.599  5625  5625 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:12:33.599  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:12:33.599  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:33.599  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:33.599  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:12:33.599  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:12:33.599  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:12:33.599  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:12:33.599  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:12:33.600  5625  5625 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:12:33.600  5625  5625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:12:33.602  5625  5625 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:12:33.602  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:12:33.602  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:33.602  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:33.602  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:12:33.602  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:12:33.602  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:12:33.602  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:12:33.602  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:12:33.603  5625  5625 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:12:33.603  5625  5625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:12:33.606  4823  4856 E SarUtils: getCurrentMCC,the netWorkOperator is invalid
08-29 09:12:33.606  4823  4856 I SarControlServiceFlow: resetSARRuleDataList, the sar rule has been switched to boot mode
08-29 09:12:33.606  4823  4856 I SarControlServiceFlow: getSARControlOperation:searchKey is -1,-1,0,0,0,0,0
08-29 09:12:33.606  4823  4856 E SarControlService: no key has been found,reset the power
08-29 09:12:33.606  4823  4874 I QcRilHookFlow: invoke the qcRilSetSarDsi method,power:0
08-29 09:12:33.606  4823  4874 D QC_RIL_OEM_HOOK: qcRilSetSarDsi: index : 0,compatibilityKey : 0
08-29 09:12:33.606  4823  4874 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4bc9000800080000000000000000000000
08-29 09:12:33.607  4863  4863 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 09:12:33.607  4863  4863 D QcrilMsgTunnelSocket: [1002] > OEM_HOOK_RAW[514f454d484f4f4bc9000800080000000000000000000000]
08-29 09:12:33.610  4823  4874 I QcRilHookFlow: invoke the qcRilSetSarWifiTxPower method,power:127
08-29 09:12:33.611  4823  4874 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower: power : 127
,08-29 09:12:33.611  4823  4874 V QC_RIL_OEM_HOOK: sendRilOemHookMsgAsync: Outgoing Data is 514f454d484f4f4b12200900040000007f000000
08-29 09:12:33.612  4863  4863 D QcrilMsgTunnelIfaceManager: handleMessage what = 3
08-29 09:12:33.612  4863  4863 D QcrilMsgTunnelSocket: [1003] > OEM_HOOK_RAW[514f454d484f4f4b12200900040000007f000000]
08-29 09:12:33.617  4863  4878 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@d79e7f2 HexData = [00000000ea03000000000000ffffffff]
08-29 09:12:33.617  4863  4878 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 09:12:33.617  4863  4878 D QcrilMsgTunnelSocket: [1002] < OEM_HOOK_RAW [null]
08-29 09:12:33.617  4863  4863 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
08-29 09:12:33.617  4823  4834 D QC_RIL_OEM_HOOK: qcRilSetSarDsi DONE!
,08-29 09:12:33.625  4863  4878 D QcrilMsgTunnelSocket: readRilMessage: Buffer = [B@d79e7f2 HexData = [00000000eb03000000000000ffffffff]
,08-29 09:12:33.625  4863  4878 D QcrilMsgTunnelSocket: Rcvd SOLICITED response with 12 bytes data for SUB0
08-29 09:12:33.625  4863  4878 D QcrilMsgTunnelSocket: [1003] < OEM_HOOK_RAW [null]
,08-29 09:12:33.626  4863  4863 D QcrilMsgTunnelIfaceManager: handleMessage what = 4
,08-29 09:12:33.626  4823  4835 D QC_RIL_OEM_HOOK: qcRilSetSarWifiTxPower DONE!
,08-29 09:12:33.634  5697  5697 W System  : ClassLoader referenced unknown path: /system/app/Maps/lib/arm64
,08-29 09:12:33.635  5677  5677 D BluetoothMap: Create BluetoothMap proxy object
,08-29 09:12:33.641  5677  5677 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
,08-29 09:12:33.660  5677  5677 D DockEventReceiver: finishStartingService: stopping service
,08-29 09:12:33.663   930  3157 I ActivityManager: Killing 5227:com.android.sdm.plugins.sprintdm/1001 (adj 15): empty #17
,08-29 09:12:33.739  4356  4452 I bt_hci  : shut_down
,08-29 09:12:33.744  4356  4456 D bt_hwcfg: hw_epilog_process
,08-29 09:12:33.744  4356  4456 I bt_vendor: low_power_mode_cb
,08-29 09:12:33.747  4356  4456 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 09:12:33.747  4356  4456 I bt_vendor: epilog_cb
08-29 09:12:33.747  4356  4456 I bt_hci  : epilog_finished_callback
,08-29 09:12:33.749  4356  4452 I bt_hci_h4: hal_close
,08-29 09:12:33.750  4356  4452 I bt_userial_vendor: device fd = 51 close
,08-29 09:12:33.868  4356  4449 D bt_stack_manager: event_shut_down_stack finished.
,08-29 09:12:33.869  4356  4448 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
,08-29 09:12:33.871  4356  4448 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-29 09:12:33.871  4356  4356 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 09:12:33.871  4356  4356 D BtGatt.GattService: Received stop request...Stopping profile...
,08-29 09:12:33.871  4356  4356 D BtGatt.GattService: stop()
08-29 09:12:33.872  4356  4356 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 09:12:33.873  4356  4356 V BluetoothAdapterState: isTurningOff()=false
08-29 09:12:33.874  4356  4356 V BluetoothAdapterState: isTurningOn()=false
08-29 09:12:33.874  4356  4356 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:12:33.874  4356  4356 V BluetoothAdapterState: isBleTurningOff()=true
08-29 09:12:33.874  4356  4448 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
08-29 09:12:33.874  4356  4448 D BluetoothAdapterProperties: Setting state to 10
,08-29 09:12:33.874  4356  4448 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
08-29 09:12:33.875   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 9 receivers.
08-29 09:12:33.877  4356  4448 I BluetoothAdapterState: Entering OffState
,08-29 09:12:33.877  5697  5697 D StrictMode: StrictMode policy violation; ~duration=154 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 09:12:33.877  5697  5697 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 09:12:33.877  5697  5697 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 09:12:33.877  5697  5697 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 09:12:33.877  5697  5697 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 09:12:33.877  5697  5697 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 09:12:33.877  5697  5697 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 09:12:33.877  5697  5697 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:383)
08-29 09:12:33.877  5697  5697 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 09:12:33.877  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 09:12:33.877  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 09:12:33.877  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:12:33.877  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 09:12:33.877  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:12:33.877  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:12:33.877  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 09:12:33.877  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 09:12:33.877  5697  5697 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 09:12:33.877  5697  5697 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 09:12:33.877  5697  5697 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:12:33.877  5697  5697 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:12:33.877  5697  5697 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:12:33.877  5697  5697 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:12:33.877  5697  5697 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:12:33.877  5697  5697 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:12:33.877  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:12:33.877  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 09:12:33.882  4356  4356 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
08-29 09:12:33.882  4356  4356 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 09:12:33.882  4356  4356 I BluetoothServiceJni: cleanupNative: return from cleanup
08-29 09:12:33.883  4356  4449 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-29 09:12:33.884  4356  4449 D bt_stack_manager: event_clean_up_stack finished.
,08-29 09:12:33.885  4356  4356 I art     : System.exit called, status: 0
08-29 09:12:33.886  4356  4356 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 09:12:33.902  5697  5697 D StrictMode: StrictMode policy violation; ~duration=153 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 09:12:33.902  5697  5697 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:182)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
,08-29 09:12:33.902  5697  5697 D StrictMode: StrictMode policy violation; ~duration=153 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 09:12:33.902  5697  5697 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at libcore.io.BlockGuardOs.fstat(BlockGuardOs.java:132)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at libcore.io.IoBridge.open(IoBridge.java:441)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at java.io.FileInputStream.<init>(FileInputStream.java:76)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at android.app.ContextImpl.openFileInput(ContextImpl.java:384)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at android.content.ContextWrapper.openFileInput(ContextWrapper.java:177)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:250)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:12:33.902  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 09:12:33.903  5697  5697 D StrictMode: StrictMode policy violation; ~duration=152 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.r.k.a(PG:2107)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:23)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 09:12:33.903  5,697  5697 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 09:12:33.903  5697  5697 D StrictMode: StrictMode policy violation; ~duration=150 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at libcore.io.BlockGuardOs.read(BlockGuardOs.java:229)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at libcore.io.IoBridge.read(IoBridge.java:468)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at java.io.FileInputStream.read(FileInputStream.java:177)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at java.io.BufferedInputStream.read(BufferedInputStream.java:290)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at java.io.DataInputStream.read(DataInputStream.java:63)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.r.k.d(PG:1187)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.r.k.c(PG:18147)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.r.k.d(PG:583)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.w.a.a.do.<init>(PG:40)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.w.a.a.do.a(PG:405)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.r.v.a(PG:1161)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.r.y.a(PG:2188)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.r.e.b(PG:170)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.r.e.b(PG:15188)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.shared.i.h.a(PG:251)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8693)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 0,9:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 09:12:33.903  5697  5697 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.app.ContextImpl.createFilesDirLocked(ContextImpl.java:418)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.app.ContextImpl.getFilesDir(ContextImpl.java:441)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.app.ContextImpl.getFileStreamPath(ContextImpl.java:549)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.content.ContextWrapper.getFileStreamPath(ContextWrapper.java:193)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8701)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 09:12:33.903  5697  5697 D StrictMode: StrictMode policy violation; ~duration=110 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at libcore.io.BlockGuardOs.access(BlockGuardOs.java:67)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at java.io.File.doAccess(File.java:281)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at java.io.File.exists(File.java:361)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8703)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 09:12:33.903  5697  5697 D StrictMode: StrictMode policy violation; ~duration=108 ms: android.os.StrictMode$StrictModeDiskReadViolation: policy=65567 violation=2
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.os.StrictMode$AndroidBlockGuardPolicy.onReadFromDisk(StrictMode.java:1263)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at libcore.io.BlockGuardOs.stat(BlockGuardOs.java:292)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at java.io.File.lastModified(File.java:569)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.q.a(PG:8704)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.shared.f.a.a(PG:48)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.map.m.e.a(PG:1531)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:244)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.a.a(PG:2265)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.a(PG:206)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.google.android.apps.gmm.base.app.GoogleMapsApplication.onCreate(PG:174)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.app.Instrumentation.callApplicationOnCreate(Instrumentation.java:1013)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4707)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at java.lang.reflect.Method.invoke(Native Method)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-29 09:12:33.903  5697  5697 D StrictMode: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-29 09:12:33.906  5677  5677 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 09:12:33.914  5677  5677 D DockEventReceiver: finishStartingService: stopping service
08-29 09:12:33.916   930  3549 I ActivityManager: Killing 5240:com.android.chrome/u0a39 (adj 15): empty #17
08-29 09:12:33.933  5625  5625 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 09:12:33.985   930  3451 I ActivityManager: Process com.android.bluetooth (pid 4356) has died
,08-29 09:12:33.988  3576  3576 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 09:12:34.000   930  3548 I ActivityManager: Start proc 5737:com.android.bluetooth/1002 for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver
,08-29 09:12:34.023   544   544 W Atfwd_Sendcmd: AtCmdFwd service not published, waiting... retryCnt : 4
,08-29 09:12:34.061  5737  5737 D AdapterServiceConfig: Adding HeadsetService
,08-29 09:12:34.061  5737  5737 D AdapterServiceConfig: Adding A2dpService
08-29 09:12:34.061  5737  5737 D AdapterServiceConfig: Adding HidService
08-29 09:12:34.061  5737  5737 D AdapterServiceConfig: Adding HealthService
,08-29 09:12:34.061  5737  5737 D AdapterServiceConfig: Adding PanService
08-29 09:12:34.062  5737  5737 D AdapterServiceConfig: Adding GattService
08-29 09:12:34.062  5737  5737 D AdapterServiceConfig: Adding BluetoothMapService
08-29 09:12:34.062  5737  5737 D AdapterServiceConfig: Adding SapService
,08-29 09:12:34.067   930  4936 I ActivityManager: Killing 5257:com.google.android.apps.photos/u0a62 (adj 15): empty #17
,08-29 09:12:34.120  5697  5722 W com.google.a.a.b.d.a: Application name is not set. Call Builder#setApplicationName.
,08-29 09:12:34.134  3825  3825 I SystemUpdateService: receiver: Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.update.SystemUpdateService$ActiveReceiver (has extras) }
,08-29 09:12:34.137  3825  3825 D SystemUpdateService: onCreate
,08-29 09:12:34.141  3825  3825 D SystemUpdateService: onStartCommand: intent: Intent { cmp=com.google.android.gms/.update.SystemUpdateService (has extras) }
,08-29 09:12:34.150  3825  3825 I iu.Environment: update connectivity state; isNetworkMetered? false, isRoaming? false, isBackgroundDataAllowed? false*
,08-29 09:12:34.155  3825  5224 I iu.UploadsManager: num queued entries: 0
,08-29 09:12:34.156  3825  5224 I iu.UploadsManager: num updated entries: 0
08-29 09:12:34.156  3825  5224 I iu.SyncManager: NEXT; no task
,08-29 09:12:34.157  3825  5749 I SystemUpdateService: active receiver: enabled
,08-29 09:12:34.160  3825  3825 D ChimeraCfgMgr: Loading module com.google.android.gms.kids from APK com.google.android.gms
,08-29 09:12:34.162  3825  3825 I Kids    : [GCoreUtils] Current gmscore version, 8186448 is smaller than the required version 8400000
,08-29 09:12:34.174  3825  5749 I SystemUpdateService: showing system update notification
,08-29 09:12:34.175   930  3548 I ActivityManager: Start proc 5752:com.android.sdm.plugins.sprintdm/1001 for broadcast com.android.sdm.plugins.sprintdm/.SprintDMReceiver
08-29 09:12:34.177   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@a49d323:true
,08-29 09:12:34.211  5752  5752 W System  : ClassLoader referenced unknown path: /system/priv-app/SprintDM/lib/arm64
,08-29 09:12:34.217  5752  5752 D SprintDMReceiver: Received intent: android.net.conn.CONNECTIVITY_CHANGE
,08-29 09:12:34.224  5752  5752 D SprintDMHelper: simOperator: 
,08-29 09:12:34.224  5752  5752 D SprintDMReceiver: Not Sprint UICC, don't do anything.
,08-29 09:12:34.239   930  3533 I ActivityManager: Start proc 5765:com.android.chrome/u0a39 for broadcast com.android.chrome/org.chromium.chrome.browser.precache.PrecacheServiceLauncher
,08-29 09:12:34.240  3825  5749 V SystemUpdateService: retry (wakeup: false) in 3599928 ms
,08-29 09:12:34.242  3825  3825 D SystemUpdateService: onDestroy
,08-29 09:12:34.245   930  3549 I ActivityManager: Killing 5119:com.google.android.music:main/u0a59 (adj 15): empty #17
,08-29 09:12:34.336  4210  5779 I Babel   : connection state changed from CONNECTED to DISCONNECTED
,08-29 09:12:34.346   930  3548 I ActivityManager: Start proc 5780:com.google.android.apps.photos/u0a62 for broadcast com.google.android.apps.photos/.actionqueue.SystemReceiver
,08-29 09:12:34.348   930  3548 I ActivityManager: Killing 4462:com.android.providers.calendar/u0a1 (adj 15): empty #17
,08-29 09:12:34.388  5780  5780 W System  : ClassLoader referenced unknown path: /system/app/Photos/lib/arm
,08-29 09:12:34.551   930  3378 I ActivityManager: Killing 5408:com.android.defcontainer/u0a7 (adj 15): empty #17
,08-29 09:12:34.641   507   923 E Netd    : netlink response contains error (No such file or directory)
,08-29 09:12:34.642   930  2940 E NetdConnector: NDC Command {51 network destroy 100} took too long (1047ms)
08-29 09:12:34.642   930  2940 D ConnectivityService: setProvNotificationVisibleIntent null visible=false networkType=MOBILE extraInfo=null highPriority=false
,08-29 09:12:34.643   930  2938 E NetdConnector: NDC Command {52 interface ipv6 wlan0 disable} took too long (1047ms)
08-29 09:12:34.643   930  2936 E NetdConnector: NDC Command {53 bandwidth setglobalalert 2097152} took too long (1043ms)
08-29 09:12:34.643   507   923 D TetherController: Setting IP forward enable = 0
,08-29 09:12:34.643   930  2938 D DhcpClient: doQuit
08-29 09:12:34.643   930  2938 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
08-29 09:12:34.644   930  5199 D DhcpClient: onQuitting
,08-29 09:12:34.645  3572  3572 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,08-29 09:12:34.649  5625  5625 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:12:34.649  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:12:34.649  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:34.649  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:34.649  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:12:34.649  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:12:34.649  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:12:34.649  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:12:34.649  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:12:34.649  5625  5625 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:12:34.649  5625  5625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:12:34.651  5625  5625 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:12:34.651  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:12:34.651  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:34.651  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:34.651  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:12:34.651  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:12:34.651  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:12:34.651  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:12:34.651  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:12:34.651  5625  5625 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:12:34.651  5625  5625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:12:34.664  3572  3572 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,08-29 09:12:34.664   930   943 I ActivityManager: Start proc 5800:com.google.android.apps.gcs/u0a11 for broadcast com.google.android.apps.gcs/.receiver.WifiStateChangedReceiver
,08-29 09:12:34.668  3572  3572 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
,08-29 09:12:34.691  5800  5800 W System  : ClassLoader referenced unknown path: /system/priv-app/GCS/lib/arm64
,08-29 09:12:34.727  5800  5800 W ClientExperimentManager: [1] d.a: com.google.android.apps.gcs does not have permission com.google.android.apps.gcs.WRITE_EXPERIMENTS; disabling overrides
,08-29 09:12:34.733   930  3530 I ActivityManager: Killing 5332:android.process.acore/u0a2 (adj 15): empty #17
,08-29 09:12:34.744  3572  3572 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-29 09:12:34.758  3572  3572 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 09:12:34.862   930  2938 D wifi    : In wifi stop Hal
,08-29 09:12:34.862   930  2938 D wifi    : halHandle = 0x7f8efbac00, mVM = 0x7fab40d140, mCls = 0x100aee
,08-29 09:12:34.862   930  3568 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
08-29 09:12:34.863   930  3568 D WifiHAL : Got a signal to exit!!!
,08-29 09:12:34.863   930  3568 I WifiHAL : Exit wifi_event_loop
,08-29 09:12:34.865  4210  4210 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:12:34.868   930  2938 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
08-29 09:12:34.869   930  2938 E WifiHAL : Event processing terminated
08-29 09:12:34.869   930  2938 D wifi    : In wifi cleaned up handler
08-29 09:12:34.869   930  2938 I WifiHAL : Internal cleanup completed
,08-29 09:12:34.870  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:12:34.883  3442  3942 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 09:12:34.883  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:12:34.893   930  3568 D wifi    : set interface wlan0 flags (DOWN)
,08-29 09:12:34.893   930  2938 D WifiNative-HAL: HAL event thread stopped successfully
,08-29 09:12:35.098   930   947 D Tethering: InitialState.processMessage what=4
,08-29 09:12:35.102   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 09:12:36.474   930  3157 D WifiService: setWifiEnabled: true pid=5625, uid=10077
,08-29 09:12:36.475   930  3157 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 09:12:36.484   507   923 D SoftapController: Softap fwReload - Ok
,08-29 09:12:36.489   507   923 D CommandListener: Setting iface cfg
,08-29 09:12:36.490   507   923 D CommandListener: Trying to bring down wlan0
,08-29 09:12:36.492   507   923 D CommandListener: Clearing all IP addresses on wlan0
,08-29 09:12:36.496   930  2938 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 09:12:37.095   930  2938 D wifi    : set interface wlan0 flags (UP)
08-29 09:12:37.098   930  2938 I WifiHAL : Initializing wifi
,08-29 09:12:37.099   930  2938 I WifiHAL : Creating socket
,08-29 09:12:37.104   930  2938 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
08-29 09:12:37.104   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 09:12:37.104   930  2938 D wifi    : Did set static halHandle = 0x7f8efbac00
08-29 09:12:37.104   930  2938 D wifi    : halHandle = 0x7f8efbac00, mVM = 0x7fab40d140, mCls = 0x101656
,08-29 09:12:37.105   930  2938 D wifi    : array field set
08-29 09:12:37.105   930  2938 I WifiNative-HAL: interface[0] = wlan0
08-29 09:12:37.108   930  5824 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547859704832
08-29 09:12:37.109   930  5824 D wifi    : waitForHalEvents called, vm = 0x7fab40d140, obj = 0x101656, env = 0x7f90131fc0
,08-29 09:12:37.153  5825  5825 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 09:12:37.174  5825  5825 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 09:12:37.183  5825  5825 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 09:12:37.183  5825  5825 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-29 09:12:37.212   930  2938 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
,08-29 09:12:37.217  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:12:37.220  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:12:37.226   930  2938 D WifiConfigStore: Loading config and enabling all networks 
,08-29 09:12:37.229  5625  5625 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:12:37.229  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:12:37.229  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:37.229  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:37.229  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:12:37.229  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:12:37.229  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:12:37.229  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:12:37.229  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:12:37.229  5625  5625 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:12:37.229  5625  5625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:12:37.231  5625  5625 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:12:37.231  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:12:37.231  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:37.231  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:37.231  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:12:37.231  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:12:37.231  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:12:37.231  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:12:37.231  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:12:37.231  5625  5625 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:12:37.231  5625  5625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:12:37.233   930  2938 D WifiConfigStore: loaded 0 passpoint configs
08-29 09:12:37.233   930  2938 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-29 09:12:37.234   930  2938 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-29 09:12:37.235   930  2938 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 09:12:37.235   930  2938 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-29 09:12:37.235   930  2938 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
08-29 09:12:37.239   930  2938 D WifiNative-HAL: Setting external_sim to 1
08-29 09:12:37.239  4210  4210 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:12:37.239   930  2938 D wifi    : setting dfs flag to true, 0x7f93ef2740
08-29 09:12:37.240   930  2938 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 09:12:37.240   930  2938 D wifi    : setting scan oui 0x7f93ef2740
08-29 09:12:37.240   930  2938 D WifiHAL : Sending mac address OUI
,08-29 09:12:37.256   930  2938 E native  : do suspend true
,08-29 09:12:37.261   930  2938 D wifi    : android_net_wifi_setLinkLayerStats: 1
08-29 09:12:37.261   507   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
,08-29 09:12:37.262   930   930 D RttService: SCAN_AVAILABLE : 3
08-29 09:12:37.262   930  3046 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-29 09:12:37.262   507   923 D CommandListener: Setting iface cfg
,08-29 09:12:37.268   930  2937 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '63 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 63 Failed to set address (No such device)'
08-29 09:12:37.268   930  2937 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 09:12:37.271   930  2937 D WifiNative-HAL: p2pGetDeviceAddress
,08-29 09:12:37.275   930  2937 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,08-29 09:12:37.294   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=174275 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=19 mControllerEnergyUsed=72 }
,08-29 09:12:39.482   930  3119 D WifiService: setWifiEnabled: false pid=5625, uid=10077
,08-29 09:12:39.482   930  3119 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 09:12:39.493   930   930 D RttService: SCAN_AVAILABLE : 1
,08-29 09:12:39.493   930  3046 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 09:12:39.505   930  2938 D WifiNative-HAL: stopRssiMonitoring, cmdId 0
,08-29 09:12:39.505   507   923 D CommandListener: Clearing all IP addresses on wlan0
,08-29 09:12:39.508   930  2938 D WifiStateMachine: SupplicantStoppingState: stopSupplicant  init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
08-29 09:12:39.509  5825  5825 I wpa_supplicant: nl80211: deinit ifname=p2p-dev-wlan0 disabled_11b_rates=0
,08-29 09:12:39.515  5625  5625 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:12:39.515  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:12:39.515  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:39.515  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:39.515  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:12:39.515  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:12:39.515  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:12:39.515  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:12:39.515  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:12:39.515  5625  5625 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:12:39.515  5625  5625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:12:39.516  5625  5625 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:12:39.516  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:12:39.516  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:39.516  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:39.516  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:12:39.516  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:12:39.516  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:12:39.516  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:12:39.516  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:12:39.516  5625  5625 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:12:39.516  5625  5625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:12:39.521  5825  5825 I wpa_supplicant: p2p-dev-wlan0: CTRL-EVENT-TERMINATING 
,08-29 09:12:39.529  5825  5825 I wpa_supplicant: nl80211: deinit ifname=wlan0 disabled_11b_rates=0
,08-29 09:12:39.539  5825  5825 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-29 09:12:39.641  4210  4210 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:12:39.641   930  2938 D wifi    : In wifi stop Hal
,08-29 09:12:39.642   930  2938 D wifi    : halHandle = 0x7f8efbac00, mVM = 0x7fab40d140, mCls = 0x101656
08-29 09:12:39.642   930  5824 E WifiHAL : wifi_event_loop: Read after POLL returned 4, error no = 0
08-29 09:12:39.642   930  5824 D WifiHAL : Got a signal to exit!!!
08-29 09:12:39.642   930  5824 I WifiHAL : Exit wifi_event_loop
08-29 09:12:39.642   930  2938 E WifiHAL : wifi_cleanup: Read after POLL returned 4, error no = 0
08-29 09:12:39.642   930  2938 E WifiHAL : Event processing terminated
08-29 09:12:39.643   930  2938 D wifi    : In wifi cleaned up handler
08-29 09:12:39.643   930  2938 I WifiHAL : Internal cleanup completed
08-29 09:12:39.644  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:12:39.644  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:12:39.644  3442  3942 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-29 09:12:39.678   930  5824 D wifi    : set interface wlan0 flags (DOWN)
,08-29 09:12:39.679   930  2938 D WifiNative-HAL: HAL event thread stopped successfully
,08-29 09:12:39.884   930   947 D Tethering: InitialState.processMessage what=4
,08-29 09:12:39.888   930   947 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-29 09:12:42.512   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@5e5b04e:true
,08-29 09:12:42.512  5737  5737 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 09:12:42.517  5737  5737 I bt_bluedroid: init
08-29 09:12:42.517  5737  5831 I BluetoothAdapterState: Entering OffState
,08-29 09:12:42.519  5737  5832 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 09:12:42.520  5737  5832 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 09:12:42.520  5737  5832 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 09:12:42.520  5737  5832 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 09:12:42.520  5737  5737 I bt_bluedroid: get_profile_interface socket
,08-29 09:12:42.523  5737  5737 I bt_bluedroid: get_profile_interface sdp
08-29 09:12:42.523  5737  5835 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 09:12:42.525  5737  5835 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 09:12:42.528  5737  5747 I bt_bluedroid: config_hci_snoop_log
,08-29 09:12:42.530   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 09:12:42.534  5737  5831 D BluetoothAdapterState: Current state: OFF, message: 0
08-29 09:12:42.534  5737  5831 D BluetoothAdapterProperties: Setting state to 14
08-29 09:12:42.535  5737  5831 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 09:12:42.536  5737  5831 D BluetoothBondStateMachine: make
,08-29 09:12:42.538  5737  5836 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 09:12:42.541  5737  5831 I BluetoothAdapterState: Entering PendingCommandState
,08-29 09:12:42.542  5737  5737 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 09:12:42.544  5737  5737 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35c60b5
08-29 09:12:42.545  5737  5737 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 09:12:42.546  5737  5737 D BtGatt.GattService: Received start request. Starting profile...
,08-29 09:12:42.546  5737  5737 D BtGatt.GattService: start()
08-29 09:12:42.546  5737  5737 I bt_bluedroid: get_profile_interface gatt
,08-29 09:12:42.547  5737  5737 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35c60b5
08-29 09:12:42.547  5737  5737 D BtGatt.AdvertiseManager: advertise manager created
,08-29 09:12:42.553  5737  5737 V BluetoothAdapterState: isTurningOff()=false
08-29 09:12:42.553  5737  5737 V BluetoothAdapterState: isTurningOn()=false
08-29 09:12:42.553  5737  5737 V BluetoothAdapterState: isBleTurningOn()=true
08-29 09:12:42.553  5737  5737 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:12:42.553  5737  5831 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 09:12:42.553  5737  5831 I bt_bluedroid: enable
,08-29 09:12:42.553  5737  5832 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-29 09:12:42.554  5737  5832 I bt_hci  : start_up
,08-29 09:12:42.560  5737  5832 I bt_vendor: alloc value 0xf3eb904d
,08-29 09:12:42.560  5737  5832 I bt_vendor: init
08-29 09:12:42.560  5737  5832 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 09:12:42.560  5737  5832 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 09:12:42.683  5737  5832 D bt_hci  : start_up starting async portion
,08-29 09:12:42.684  5737  5839 I bt_hci  : event_finish_startup
08-29 09:12:42.684  5737  5839 I bt_hci_h4: hal_open
,08-29 09:12:42.684  5737  5839 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 09:12:42.687  5737  5839 I bt_userial_vendor: device fd = 51 open
,08-29 09:12:42.672  5840  5840 W irq/448-msm_hs_: type=1400 audit(0.0:71): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 09:12:42.700  5737  5839 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 09:12:42.703  5737  5839 D bt_hwcfg: Chipset BCM4358A3
,08-29 09:12:42.703  5737  5839 D bt_hwcfg: Target name = [BCM4358A3]
,08-29 09:12:42.704  5737  5839 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-29 09:12:43.108  5737  5839 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 09:12:43.109  5737  5839 D bt_hwcfg: Settlement delay -- 100 ms
,08-29 09:12:43.109  5737  5839 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 09:12:43.244  5737  5839 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 09:12:43.245  5737  5839 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,08-29 09:12:43.246  5737  5839 I bt_hwcfg: vendor lib fwcfg completed
08-29 09:12:43.246  5737  5839 I bt_vendor: firmware callback
08-29 09:12:43.246  5737  5839 I bt_hci  : firmware_config_callback
,08-29 09:12:43.257  5737  5842 I bt_btu  : btu_task pending for preload complete event
,08-29 09:12:43.257  5737  5842 I bt_btu_task: Bluetooth chip preload is complete
,08-29 09:12:43.257  5737  5842 I bt_btu  : btu_task received preload complete event
,08-29 09:12:43.264  5737  5842 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 09:12:43.265  5737  5842 I         : BTE_InitTraceLevels -- TRC_L2CAP
,08-29 09:12:43.265  5737  5842 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 09:12:43.265  5737  5842 I         : BTE_InitTraceLevels -- TRC_AVDT
08-29 09:12:43.265  5737  5842 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 09:12:43.265  5737  5842 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 09:12:43.265  5737  5842 I         : BTE_InitTraceLevels -- TRC_BNEP
08-29 09:12:43.265  5737  5842 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 09:12:43.266  5737  5842 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 09:12:43.266  5737  5842 I         : BTE_InitTraceLevels -- TRC_PAN
,08-29 09:12:43.266  5737  5842 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 09:12:43.266  5737  5842 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 09:12:43.266  5737  5842 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 09:12:43.266  5737  5842 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-29 09:12:43.266  5737  5842 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 09:12:43.338  5737  5842 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3e36c99
,08-29 09:12:43.338  5737  5842 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3e36c99 
,08-29 09:12:43.348  5737  5835 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 09:12:43.349  5737  5835 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 09:12:43.350  5737  5835 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 09:12:43.352  5737  5835 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 09:12:43.354  5737  5835 D BluetoothAdapterProperties: Scan Mode:20
,08-29 09:12:43.354  5737  5835 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 09:12:43.354  5737  5835 D bt_hci  : do_postload posting postload work item
08-29 09:12:43.354  5737  5839 I bt_hci  : event_postload
08-29 09:12:43.355  5737  5839 I bt_vendor: sco_config_cb
08-29 09:12:43.355  5737  5839 I bt_hci  : sco_config_callback postload finished.
08-29 09:12:43.358  5737  5835 D bt_bte_conf: Device ID record 1 : primary
08-29 09:12:43.358  5737  5835 D bt_bte_conf:   vendorId            = 000f
08-29 09:12:43.358  5737  5835 D bt_bte_conf:   vendorIdSource      = 0001
08-29 09:12:43.358  5737  5835 D bt_bte_conf:   product             = 1200
08-29 09:12:43.358  5737  5835 D bt_bte_conf:   version             = 1436
08-29 09:12:43.358  5737  5835 D bt_bte_conf:   clientExecutableURL = 
08-29 09:12:43.358  5737  5835 D bt_bte_conf:   serviceDescription  = 
08-29 09:12:43.358  5737  5835 D bt_bte_conf:   documentationURL    = 
08-29 09:12:43.359  5737  5835 D bt_bte_conf: bte_load_did_conf no section named DID2.
,08-29 09:12:43.359  5737  5832 D bt_stack_manager: event_start_up_stack finished
,08-29 09:12:43.360  5737  5831 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 09:12:43.361  5737  5831 D BluetoothAdapterProperties: Setting state to 15
08-29 09:12:43.361  5737  5831 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
,08-29 09:12:43.362  5737  5831 I BluetoothAdapterState: Entering BleOnState
08-29 09:12:43.365  5737  5839 I bt_vendor: low_power_mode_cb
08-29 09:12:43.366  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:12:43.369  5737  5831 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 09:12:43.369  5737  5831 D BluetoothAdapterProperties: Setting state to 11
08-29 09:12:43.369  5737  5831 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
08-29 09:12:43.370  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:12:43.378  5737  5737 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35c60b5
08-29 09:12:43.379  5737  5737 D HeadsetService: Received start request. Starting profile...
,08-29 09:12:43.381  5737  5737 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-29 09:12:43.382  5737  5737 D HeadsetStateMachine: make
,08-29 09:12:43.382  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:12:43.384  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:12:43.393  5737  5831 I BluetoothAdapterState: Entering PendingCommandState
,08-29 09:12:43.396  5737  5737 D HeadsetStateMachine: max_hf_connections = 1
,08-29 09:12:43.396  5737  5737 I bt_bluedroid: get_profile_interface handsfree
08-29 09:12:43.397  5737  5835 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 09:12:43.397  5737  5835 E bt_btif : btif_hf_upstreams_evt: Invalid index 3
,08-29 09:12:43.400  5737  5737 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35c60b5
08-29 09:12:43.401  5737  5737 D A2dpService: Received start request. Starting profile...
08-29 09:12:43.402  5737  5737 I BluetoothAvrcpServiceJni: classInitNative: succeeds
,08-29 09:12:43.402  5737  5737 I bt_bluedroid: get_profile_interface avrcp
,08-29 09:12:43.408  5737  5737 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 09:12:43.408  5737  5737 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 09:12:43.408  5737  5737 D A2dpStateMachine: make
,08-29 09:12:43.409  5737  5737 I bt_bluedroid: get_profile_interface a2dp
,08-29 09:12:43.410  5737  5835 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
,08-29 09:12:43.411  5737  5851 D A2dpStateMachine: Enter Disconnected: -2
,08-29 09:12:43.412  5737  5737 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 09:12:43.413  5737  5737 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35c60b5
08-29 09:12:43.415  3576  3576 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 09:12:43.415  5737  5737 D HidService: Received start request. Starting profile...
,08-29 09:12:43.415  5737  5737 I bt_bluedroid: get_profile_interface hidhost
,08-29 09:12:43.416  5737  5737 D HidService: setHidService(): set to: null
08-29 09:12:43.416  5737  5835 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3e182d9
08-29 09:12:43.416  5737  5835 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 09:12:43.416  5737  5737 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 09:12:43.417  5737  5737 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35c60b5
08-29 09:12:43.417  5737  5737 D HealthService: Received start request. Starting profile...
08-29 09:12:43.415  5677  5677 D BluetoothInputDevice: Proxy object connected
08-29 09:12:43.419  5677  5677 D HidProfile: Bluetooth service connected
08-29 09:12:43.419  5737  5737 I bt_bluedroid: get_profile_interface health
08-29 09:12:43.419  5737  5737 I BluetoothPanServiceJni: classInitNative(L105): succeeds
,08-29 09:12:43.420  5737  5737 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35c60b5
,08-29 09:12:43.421  5737  5737 D PanService: Received start request. Starting profile...
,08-29 09:12:43.421  5677  5677 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 09:12:43.421  5737  5737 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 09:12:43.421  5737  5737 I bt_bluedroid: get_profile_interface pan
08-29 09:12:43.422  5737  5835 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-29 09:12:43.422  5677  5677 D PanProfile: Bluetooth service connected
08-29 09:12:43.424  5737  5737 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35c60b5
,08-29 09:12:43.425  5677  5677 D BluetoothMap: Proxy object connected
,08-29 09:12:43.426  5677  5677 D MapProfile: Bluetooth service connected
08-29 09:12:43.426  5677  5677 D BluetoothMap: getConnectedDevices()
,08-29 09:12:43.427  5737  5737 D BluetoothMapService: Received start request. Starting profile...
08-29 09:12:43.427  5737  5737 D BluetoothMapService: start()
08-29 09:12:43.430  5737  5737 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
08-29 09:12:43.430  5737  5737 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
,08-29 09:12:43.430  5737  5737 D BluetoothMapAppObserver: createReceiver()
08-29 09:12:43.431  5737  5737 D BluetoothMapAppObserver: initObservers()
,08-29 09:12:43.432  5737  5737 D BluetoothMapAppObserver: getEnabledAccountItems()
08-29 09:12:43.436  5737  5737 V SapService: SapBinder()
08-29 09:12:43.437  5737  5737 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35c60b5
08-29 09:12:43.437  5737  5737 D SapService: Received start request. Starting profile...
08-29 09:12:43.437  5737  5737 V SapService: start()
08-29 09:12:43.440  5737  5737 V BluetoothAdapterState: isTurningOff()=false
08-29 09:12:43.440  5737  5737 V BluetoothAdapterState: isTurningOn()=true
08-29 09:12:43.440  5737  5737 V BluetoothAdapterState: isBleTurningOn()=false
,08-29 09:12:43.440  5737  5848 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 09:12:43.440  5737  5737 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:12:43.440  5737  5737 V BluetoothAdapterState: isTurningOff()=false
08-29 09:12:43.440  5737  5737 V BluetoothAdapterState: isTurningOn()=true
08-29 09:12:43.440  5737  5737 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:12:43.440  5737  5737 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:12:43.440  5737  5737 V BluetoothAdapterState: isTurningOff()=false
08-29 09:12:43.440  5737  5737 V BluetoothAdapterState: isTurningOn()=true
08-29 09:12:43.440  5737  5737 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:12:43.440  5737  5737 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:12:43.441  5737  5737 V BluetoothAdapterState: isTurningOff()=false
08-29 09:12:43.441  5737  5737 V BluetoothAdapterState: isTurningOn()=true
,08-29 09:12:43.441  5737  5737 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:12:43.441  5737  5737 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:12:43.441  5737  5737 V BluetoothAdapterState: isTurningOff()=false
08-29 09:12:43.441  5737  5737 V BluetoothAdapterState: isTurningOn()=true
08-29 09:12:43.442  5737  5737 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:12:43.442  5737  5737 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:12:43.442  5737  5737 V BluetoothAdapterState: isTurningOff()=false
08-29 09:12:43.442  5737  5737 V BluetoothAdapterState: isTurningOn()=true
08-29 09:12:43.442  5737  5737 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:12:43.442  5737  5737 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 09:12:43.442  5737  5737 V BluetoothAdapterState: isTurningOff()=false
08-29 09:12:43.443  5737  5737 V BluetoothAdapterState: isTurningOn()=true
08-29 09:12:43.443  5737  5737 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:12:43.443  5737  5737 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:12:43.443  5737  5831 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 09:12:43.443  5737  5831 D BluetoothAdapterProperties: ScanMode =  20
08-29 09:12:43.443  5737  5831 D BluetoothAdapterProperties: State =  11
08-29 09:12:43.446  5677  5677 D BluetoothMap: Bluetooth is Not enabled
08-29 09:12:43.446  5737  5835 D BluetoothAdapterProperties: Scan Mode:21
,08-29 09:12:43.446  5737  5831 D BluetoothAdapterProperties: Setting state to 12
08-29 09:12:43.446  5737  5831 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
,08-29 09:12:43.447  5737  5835 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 09:12:43.447  5737  5831 I BluetoothAdapterState: Entering OnState
08-29 09:12:43.447  5677  5688 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 09:12:43.448  3079  3094 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 09:12:43.449  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:12:43.449  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:43.449  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:43.449  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:12:43.449  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:12:43.449  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:12:43.449  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:12:43.449  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:12:43.450  3079  3079 D BluetoothInputDevice: Proxy object connected
08-29 09:12:43.450  3079  3092 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:12:43.450  3079  3079 D HidProfile: Bluetooth service connected
08-29 09:12:43.450   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:12:43.450   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 09:12:43.451  3504  3529 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:12:43.451  5625  5625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:12:43.451  5677  5687 D BluetoothMap: onBluetoothStateChange: up=true
08-29 09:12:43.451   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 09:12:43.452  3079  3094 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 09:12:43.453   930   930 D BluetoothA2dp: Proxy object connected
08-29 09:12:43.453  3079  3693 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 09:12:43.455  3079  3079 D BluetoothA2dp: Proxy object connected
08-29 09:12:43.455  5677  5688 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 09:12:43.455  5677  5687 D BluetoothPan: onBluetoothStateChange on: true
08-29 09:12:43.455   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:12:43.455  3079  3094 D BluetoothPan: onBluetoothStateChange on: true
08-29 09:12:43.456  5737  5737 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 09:12:43.457  5737  5737 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
08-29 09:12:43.457  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:12:43.457  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:43.457  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:43.457  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:12:43.457  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:12:43.457  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:12:43.457  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:12:43.457  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:12:43.457  3079  3094 D BluetoothMap: onBluetoothStateChange: up=true
08-29 09:12:43.457  3079  3079 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 09:12:43.457  3079  3079 D PanProfile: Bluetooth service connected
08-29 09:12:43.458  5737  5737 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:12:43.459  5625  5625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:12:43.460  3079  3079 D BluetoothMap: Proxy object connected
08-29 09:12:43.460  3079  3079 D MapProfile: Bluetooth service connected
08-29 09:12:43.460  3079  3079 D BluetoothMap: getConnectedDevices()
08-29 09:12:43.461   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 09:12:43.462  5737  5737 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:12:43.463  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:12:43.465  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:12:43.466  5737  5737 D ObexServerSockets: Succeed to create listening sockets 
08-29 09:12:43.466  5737  5737 D ObexServerSockets0: startAccept()
08-29 09:12:43.466  5737  5737 D ObexServerSockets0: prepareForNewConnect()
08-29 09:12:43.468  5737  5737 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 09:12:43.468  5737  5737 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 09:12:43.468  5737  5737 D BluetoothMapService: onReceive
08-29 09:12:43.468  5737  5737 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:12:43.468  5737  5737 D BluetoothMapService: STATE_ON
08-29 09:12:43.469  5677  5677 D LocalBluetoothProfileManager: Adding local A2DP profile
08-29 09:12:43.469  5737  5857 D ObexServerSockets0: Accepting socket connection...
08-29 09:12:43.470  5737  5859 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:12:43.471  5737  5858 D ObexServerSockets0: Accepting socket connection...
,08-29 09:12:43.473  5737  5859 D BluetoothSdpJni: sdpCreateSapsRecordNative:
08-29 09:12:43.473  5737  5859 D BluetoothSdpJni: SDP Create record success - handle: 1
,08-29 09:12:43.474  5677  5677 D LocalBluetoothProfileManager: Adding local HEADSET profile
,08-29 09:12:43.479  5677  5677 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 09:12:43.482  5677  5677 D BluetoothA2dp: Proxy object connected
,08-29 09:12:43.486  3576  3576 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 09:12:43.488  5677  5677 D DockEventReceiver: finishStartingService: stopping service
,08-29 09:12:43.493  5677  5677 D BluetoothPbap: Proxy object connected
,08-29 09:12:43.493  3079  3079 D BluetoothPbap: Proxy object connected
08-29 09:12:43.493  3079  3079 D PbapServerProfile: Bluetooth service connected
08-29 09:12:43.493  5737  5737 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 09:12:43.493  5737  5737 D ObexServerSockets0: prepareForNewConnect()
08-29 09:12:43.493  5677  5677 D PbapServerProfile: Bluetooth service connected
,08-29 09:12:43.500  5737  5863 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 09:12:43.513  5737  5867 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 09:12:43.514  5737  5867 I BtOppRfcommListener: Accept thread started.
,08-29 09:12:43.552   930   930 D BluetoothHeadset: Proxy object connected
,08-29 09:12:43.552   930   930 D BluetoothHeadset: Proxy object connected
08-29 09:12:43.552  3079  3092 D BluetoothHeadset: Proxy object connected
08-29 09:12:43.552  3079  3079 D HeadsetProfile: Bluetooth service connected
08-29 09:12:43.552   930   930 D BluetoothHeadset: Proxy object connected
08-29 09:12:43.553  3504  3738 D BluetoothHeadset: Proxy object connected
,08-29 09:12:43.555   930   947 D BluetoothHeadset: Proxy object connected
,08-29 09:12:43.576  5677  5688 D BluetoothHeadset: Proxy object connected
,08-29 09:12:43.577  5677  5677 D HeadsetProfile: Bluetooth service connected
,08-29 09:12:45.496  5737  5831 D BluetoothAdapterState: Current state: ON, message: 23
08-29 09:12:45.496  5737  5831 D BluetoothAdapterProperties: Setting state to 13
08-29 09:12:45.496  5737  5831 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
,08-29 09:12:45.497  5737  5831 D BluetoothAdapterProperties: onBluetoothDisable()
,08-29 09:12:45.499  5737  5831 I BluetoothAdapterState: Entering PendingCommandState
,08-29 09:12:45.500  5737  5835 D BluetoothAdapterProperties: Scan Mode:20
08-29 09:12:45.501  5737  5831 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 21
08-29 09:12:45.503  5737  5737 D BluetoothMapService: onReceive
,08-29 09:12:45.503  5737  5737 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:12:45.503  5737  5737 D BluetoothMapService: STATE_TURNING_OFF
,08-29 09:12:45.504  5737  5737 D BluetoothMapService: MAP Service closeService in
08-29 09:12:45.505  5737  5737 D BluetoothMapMasInstance0: MAP Service shutdown
,08-29 09:12:45.505  5737  5737 D ObexServerSockets0: shutdown(block = true)
08-29 09:12:45.506  5737  5737 D ObexServerSockets0: shutdown called from another thread - interrupt().
,08-29 09:12:45.506  5737  5857 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_RFCOMM Channel: 4
08-29 09:12:45.506  5737  5737 D ObexServerSockets0: shutdown called from another thread - interrupt().
08-29 09:12:45.507  5737  5858 D ObexServerSockets0: AcceptThread ended for: ServerSocket: Type: TYPE_L2CAP Channel: 4097
08-29 09:12:45.508  5737  5844 E bt_btif : SOCK_LIST: free(id = 1) - NO app_fd!
08-29 09:12:45.510  5737  5737 I BtOppRfcommListener: stopping Accept Thread
,08-29 09:12:45.512  5737  5867 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-29 09:12:45.513  5625  5625 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:12:45.513  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:12:45.513  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:45.513  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:45.513  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:12:45.513  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:12:45.513  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:12:45.513  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:12:45.513  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:12:45.515  5625  5625 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:12:45.515  5625  5625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:12:45.515  5737  5867 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-29 09:12:45.518  5677  5677 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 09:12:45.520  5625  5625 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-29 09:12:45.520  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:12:45.520  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:45.520  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:45.520  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:12:45.520  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-29 09:12:45.520  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:12:45.520  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:12:45.520  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:12:45.521  5625  5625 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-29 09:12:45.521  5625  5625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: OFF, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:12:45.523  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:12:45.524  5737  5737 D HeadsetService: Received stop request...Stopping profile...
,08-29 09:12:45.526  5677  5687 D BluetoothHeadset: Proxy object disconnected
,08-29 09:12:45.526  5737  5737 D A2dpService: Received stop request...Stopping profile...
08-29 09:12:45.526   930   930 D BluetoothHeadset: Proxy object disconnected
08-29 09:12:45.526   930   930 D BluetoothHeadset: Proxy object disconnected
08-29 09:12:45.526  5737  5851 D A2dpStateMachine: Exit Disconnected: -1
,08-29 09:12:45.527  3079  3693 D BluetoothHeadset: Proxy object disconnected
08-29 09:12:45.527   930   930 D BluetoothHeadset: Proxy object disconnected
08-29 09:12:45.527  3504  3531 D BluetoothHeadset: Proxy object disconnected
08-29 09:12:45.528  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:12:45.528  5737  5737 D HidService: Received stop request...Stopping profile...
08-29 09:12:45.528   930   930 D BluetoothA2dp: Proxy object disconnected
08-29 09:12:45.529  5737  5737 D HidService: Stopping Bluetooth HidService
,08-29 09:12:45.532  3079  3079 D HeadsetProfile: Bluetooth service disconnected
08-29 09:12:45.532  5737  5737 D HealthService: Received stop request...Stopping profile...
08-29 09:12:45.532  3079  3079 D BluetoothA2dp: Proxy object disconnected
08-29 09:12:45.532  3079  3079 D BluetoothInputDevice: Proxy object disconnected
08-29 09:12:45.533  3079  3079 D HidProfile: Bluetooth service disconnected
,08-29 09:12:45.534  5737  5737 D PanService: Received stop request...Stopping profile...
,08-29 09:12:45.534  5677  5677 D DockEventReceiver: finishStartingService: stopping service
,08-29 09:12:45.534  3079  3079 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 09:12:45.534  3079  3079 D PanProfile: Bluetooth service disconnected
08-29 09:12:45.535  5677  5677 D HeadsetProfile: Bluetooth service disconnected
08-29 09:12:45.536  5677  5677 D BluetoothA2dp: Proxy object disconnected
08-29 09:12:45.536  5737  5737 D BluetoothMapService: Received stop request...Stopping profile...
,08-29 09:12:45.536  5737  5737 D BluetoothMapService: stop()
08-29 09:12:45.536  5677  5677 D BluetoothInputDevice: Proxy object disconnected
08-29 09:12:45.536  5677  5677 D HidProfile: Bluetooth service disconnected
08-29 09:12:45.537  5677  5677 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-29 09:12:45.537  5737  5737 D BluetoothMapAppObserver: deinitObservers()
08-29 09:12:45.537  5677  5677 D PanProfile: Bluetooth service disconnected
08-29 09:12:45.537  5737  5737 D BluetoothMapAppObserver: removeReceiver()
08-29 09:12:45.539  3079  3079 D BluetoothMap: Proxy object disconnected
,08-29 09:12:45.539  3079  3079 D MapProfile: Bluetooth service disconnected
08-29 09:12:45.540  5737  5737 D SapService: Received stop request...Stopping profile...
08-29 09:12:45.540  5737  5737 V SapService: stop()
08-29 09:12:45.540  5677  5677 D BluetoothMap: Proxy object disconnected
08-29 09:12:45.540  5677  5677 D MapProfile: Bluetooth service disconnected
,08-29 09:12:45.541  5737  5737 V BluetoothAdapterState: isTurningOff()=true
08-29 09:12:45.541  5737  5737 V BluetoothAdapterState: isTurningOn()=false
08-29 09:12:45.541  5737  5737 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:12:45.541  5737  5737 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:12:45.544  5737  5737 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-29 09:12:45.544  5737  5737 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-29 09:12:45.544  5737  5835 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100008
08-29 09:12:45.544  5737  5842 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:12:45.544  5737  5737 V BluetoothAdapterState: isTurningOff()=true
08-29 09:12:45.544  5737  5842 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:12:45.544  5737  5737 V BluetoothAdapterState: isTurningOn()=false
08-29 09:12:45.544  5737  5842 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
,08-29 09:12:45.544  5737  5737 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:12:45.544  5737  5737 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:12:45.544  5737  5835 E bt_btif : btif_hf_upstreams_evt: Invalid index 99
08-29 09:12:45.546  5737  5737 V BluetoothAdapterState: isTurningOff()=true
08-29 09:12:45.546  5737  5737 V BluetoothAdapterState: isTurningOn()=false
08-29 09:12:45.546  5737  5737 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:12:45.546  5737  5737 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:12:45.547  5737  5737 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
,08-29 09:12:45.547  5737  5737 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-29 09:12:45.547  5737  5835 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 09:12:45.547  5737  5842 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:12:45.547  5737  5842 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:12:45.547  5737  5835 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
08-29 09:12:45.548  5737  5842 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 09:12:45.548  5737  5842 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-29 09:12:45.548  5737  5842 W bt_l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-29 09:12:45.548  5737  5842 W bt_l2cap: L2CAP - PSM: 0x0017 not found for deregistration
,08-29 09:12:45.552  5737  5737 V BluetoothAdapterState: isTurningOff()=true
08-29 09:12:45.552  5737  5737 V BluetoothAdapterState: isTurningOn()=false
,08-29 09:12:45.552  5737  5737 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:12:45.552  5737  5737 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:12:45.553  5737  5737 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-29 09:12:45.553  5737  5737 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-29 09:12:45.553  5737  5835 E bt_btif : btif_in_execute_service_request: Unknown service being enabled
08-29 09:12:45.553  3576  3576 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 09:12:45.553  5737  5737 V BluetoothAdapterState: isTurningOff()=true
,08-29 09:12:45.553  5737  5737 V BluetoothAdapterState: isTurningOn()=false
08-29 09:12:45.553  5737  5737 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:12:45.553  5737  5737 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:12:45.554  5737  5737 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-29 09:12:45.554  5737  5737 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
,08-29 09:12:45.556  5737  5737 D BluetoothMapService: MAP Service closeService in
08-29 09:12:45.557  5737  5737 V BluetoothAdapterState: isTurningOff()=true
08-29 09:12:45.557  5737  5737 V BluetoothAdapterState: isTurningOn()=false
08-29 09:12:45.557  5737  5737 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:12:45.557  5737  5737 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 09:12:45.557  5737  5737 D BluetoothMapService: cleanup()
08-29 09:12:45.557  5737  5737 D BluetoothMapService: MAP Service closeService in
08-29 09:12:45.557  5737  5737 V BluetoothAdapterState: isTurningOff()=true
08-29 09:12:45.557  5737  5737 V BluetoothAdapterState: isTurningOn()=false
08-29 09:12:45.557  5737  5737 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:12:45.558  5737  5737 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:12:45.558  5737  5831 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 26
08-29 09:12:45.558  5737  5831 D BluetoothAdapterProperties: Setting state to 15
08-29 09:12:45.558  5737  5831 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 15
08-29 09:12:45.559  5737  5831 I BluetoothAdapterState: Entering BleOnState
08-29 09:12:45.559  3079  3079 D BluetoothPbap: Proxy object disconnected
08-29 09:12:45.560  3079  3079 D PbapServerProfile: Bluetooth service disconnected
,08-29 09:12:45.560  5677  5688 D BluetoothPbap: onBluetoothStateChange: up=false
,08-29 09:12:45.562  3079  3092 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 09:12:45.563  3079  3693 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:12:45.564   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:12:45.564   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:12:45.564  3504  3529 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:12:45.565  5677  5687 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 09:12:45.566  5677  5688 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:12:45.566  5677  5872 D BluetoothMap: onBluetoothStateChange: up=false
08-29 09:12:45.567   930   947 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 09:12:45.567  3079  3094 D BluetoothPbap: onBluetoothStateChange: up=false
08-29 09:12:45.568  3079  3092 D BluetoothA2dp: onBluetoothStateChange: up=false
08-29 09:12:45.569  5677  5687 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-29 09:12:45.569  5677  5688 D BluetoothPan: onBluetoothStateChange on: false
08-29 09:12:45.570   930   947 D BluetoothHeadset: onBluetoothStateChange: up=false
08-29 09:12:45.570  3079  3693 D BluetoothPan: onBluetoothStateChange on: false
08-29 09:12:45.570  3079  3094 D BluetoothMap: onBluetoothStateChange: up=false
08-29 09:12:45.571  5737  5831 D BluetoothAdapterState: Current state: BLE ON, message: 20
08-29 09:12:45.571  5737  5831 D BluetoothAdapterProperties: Setting state to 16
08-29 09:12:45.571  5737  5831 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 16
08-29 09:12:45.572  5737  5831 D BluetoothAdapterProperties: onBleDisable
08-29 09:12:45.572  5737  5831 I BluetoothAdapterState: Entering PendingCommandState
08-29 09:12:45.573  5737  5832 D bt_stack_manager: event_shut_down_stack is bringing down the stack.
08-29 09:12:45.574  5677  5677 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
08-29 09:12:45.574  5737  5835 D BluetoothAdapterProperties: Scan Mode:20
08-29 09:12:45.574  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:12:45.574  5737  5842 W bt_btif : bta_dm_disable BTA_DISABLE_DELAY set to 200 ms
08-29 09:12:45.574  5737  5842 D bt_bta_sys_main: bta_sys_stop_timer expected alarm was not in bta alarm hash map.
08-29 09:12:45.576  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:12:45.578  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:12:45.579  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:12:45.583  3576  3576 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 09:12:45.584  5677  5677 D DockEventReceiver: finishStartingService: stopping service
,08-29 09:12:45.785  5737  5835 I bt_hci  : shut_down
,08-29 09:12:45.790  5737  5839 D bt_hwcfg: hw_epilog_process
,08-29 09:12:45.790  5737  5839 I bt_vendor: low_power_mode_cb
,08-29 09:12:45.793  5737  5839 D bt_hwcfg: hw_epilog_cback Opcode:0x0C03 Status: 0
,08-29 09:12:45.793  5737  5839 I bt_vendor: epilog_cb
08-29 09:12:45.793  5737  5839 I bt_hci  : epilog_finished_callback
,08-29 09:12:45.796  5737  5835 I bt_hci_h4: hal_close
,08-29 09:12:45.797  5737  5835 I bt_userial_vendor: device fd = 51 close
,08-29 09:12:45.919  5737  5832 D bt_stack_manager: event_shut_down_stack finished.
,08-29 09:12:45.920  5737  5831 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 24
08-29 09:12:45.924  5737  5831 D BluetoothAdapterState: Stopping Gatt profile services that were post enabled
08-29 09:12:45.925  5737  5737 D BtGatt.DebugUtils: handleDebugAction() action=null
,08-29 09:12:45.926  5737  5737 D BtGatt.GattService: Received stop request...Stopping profile...
08-29 09:12:45.926  5737  5737 D BtGatt.GattService: stop()
08-29 09:12:45.927  5737  5737 D BtGatt.AdvertiseManager: advertise clients cleared
,08-29 09:12:45.931  5737  5737 V BluetoothAdapterState: isTurningOff()=false
,08-29 09:12:45.932  5737  5737 V BluetoothAdapterState: isTurningOn()=false
08-29 09:12:45.932  5737  5737 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:12:45.932  5737  5737 V BluetoothAdapterState: isBleTurningOff()=true
08-29 09:12:45.932  5737  5831 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 25
,08-29 09:12:45.933  5737  5831 D BluetoothAdapterProperties: Setting state to 10
08-29 09:12:45.933  5737  5831 I BluetoothAdapterState: Bluetooth adapter state changed: 16-> 10
,08-29 09:12:45.935  5737  5831 I BluetoothAdapterState: Entering OffState
08-29 09:12:45.936   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 10 receivers.
,08-29 09:12:45.953  5737  5737 W BluetoothSdpJni: Cleaning up Bluetooth SDP Interface...
,08-29 09:12:45.953  5737  5737 W BluetoothSdpJni: Cleaning up Bluetooth Health object
08-29 09:12:45.953  5737  5832 D bt_stack_manager: event_clean_up_stack is cleaning up the stack.
08-29 09:12:45.956  5737  5832 D bt_stack_manager: event_clean_up_stack finished.
,08-29 09:12:45.957  5737  5737 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-29 09:12:45.960  5737  5737 I art     : System.exit called, status: 0
,08-29 09:12:45.961  5737  5737 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
,08-29 09:12:45.999   930  3119 I ActivityManager: Process com.android.bluetooth (pid 5737) has died
,08-29 09:12:48.494  5625  5671 D io.jxcore.node.ConnectivityMonitor: stop
,08-29 09:12:48.494  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:12:51.501  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded,
08-29 09:12:51.502  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@cd172d added. We now have 6 listener(s)
08-29 09:12:51.502  5625  5671 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:12:51.505  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:12:51.505  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@e30c462 added. We now have 7 listener(s)
,08-29 09:12:51.506  5625  5671 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:12:51.507  5625  5671 I System.out: IsBluetoothEnabled
,08-29 09:12:51.515  5625  5671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:12:51.540   930   947 I ActivityManager: Start proc 5877:com.android.bluetooth/1002 for service com.android.bluetooth/.btservice.AdapterService
,08-29 09:12:51.597  5877  5877 D AdapterServiceConfig: Adding HeadsetService
,08-29 09:12:51.597  5877  5877 D AdapterServiceConfig: Adding A2dpService
08-29 09:12:51.597  5877  5877 D AdapterServiceConfig: Adding HidService
08-29 09:12:51.597  5877  5877 D AdapterServiceConfig: Adding HealthService
08-29 09:12:51.598  5877  5877 D AdapterServiceConfig: Adding PanService
08-29 09:12:51.598  5877  5877 D AdapterServiceConfig: Adding GattService
,08-29 09:12:51.598  5877  5877 D AdapterServiceConfig: Adding BluetoothMapService
08-29 09:12:51.598  5877  5877 D AdapterServiceConfig: Adding SapService
,08-29 09:12:51.610   930   947 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@648392f:true
,08-29 09:12:51.611  5877  5877 D BluetoothAdapterState: make() - Creating AdapterState
,08-29 09:12:51.613  5877  5877 I bt_bluedroid: init
08-29 09:12:51.613  5877  5889 I BluetoothAdapterState: Entering OffState
,08-29 09:12:51.614  5877  5890 I bt_bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-29 09:12:51.614  5877  5890 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-29 09:12:51.615  5877  5890 I bt_bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-29 09:12:51.615  5877  5890 I bt_stack_config: init attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-29 09:12:51.615  5877  5877 I bt_bluedroid: get_profile_interface socket
,08-29 09:12:51.616  5877  5877 I bt_bluedroid: get_profile_interface sdp
08-29 09:12:51.617  5877  5893 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
08-29 09:12:51.618  5877  5893 D BluetoothAdapterProperties: Name is: Nexus 6P
,08-29 09:12:51.620  5877  5888 I bt_bluedroid: config_hci_snoop_log
08-29 09:12:51.621   930   947 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 10 receivers.
,08-29 09:12:51.625  5877  5889 D BluetoothAdapterState: Current state: OFF, message: 0
,08-29 09:12:51.625  5877  5889 D BluetoothAdapterProperties: Setting state to 14
08-29 09:12:51.625  5877  5889 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 14
,08-29 09:12:51.626  5877  5889 D BluetoothBondStateMachine: make
,08-29 09:12:51.627  5877  5894 I BluetoothBondStateMachine: StableState(): Entering Off State
,08-29 09:12:51.630  5877  5889 I BluetoothAdapterState: Entering PendingCommandState
,08-29 09:12:51.631  5877  5877 I BtGatt.JNI: classInitNative(L912): classInitNative: Success!
,08-29 09:12:51.633  5877  5877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35c60b5
08-29 09:12:51.633  5877  5877 D BtGatt.DebugUtils: handleDebugAction() action=null
08-29 09:12:51.634  5877  5877 D BtGatt.GattService: Received start request. Starting profile...
08-29 09:12:51.634  5877  5877 D BtGatt.GattService: start()
08-29 09:12:51.634  5877  5877 I bt_bluedroid: get_profile_interface gatt
08-29 09:12:51.634  5877  5877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35c60b5
08-29 09:12:51.635  5877  5877 D BtGatt.AdvertiseManager: advertise manager created
,08-29 09:12:51.639  5877  5877 V BluetoothAdapterState: isTurningOff()=false
,08-29 09:12:51.639  5877  5877 V BluetoothAdapterState: isTurningOn()=false
08-29 09:12:51.639  5877  5877 V BluetoothAdapterState: isBleTurningOn()=true
08-29 09:12:51.639  5877  5877 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:12:51.639  5877  5889 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 4
08-29 09:12:51.639  5877  5889 I bt_bluedroid: enable
08-29 09:12:51.640  5877  5890 D bt_stack_manager: event_start_up_stack is bringing up the stack.
,08-29 09:12:51.640  5877  5890 I bt_hci  : start_up
,08-29 09:12:51.645  5877  5890 I bt_vendor: alloc value 0xf3f3504d
08-29 09:12:51.645  5877  5890 I bt_vendor: init
,08-29 09:12:51.645  5877  5890 I bt_vnd_conf: Attempt to load conf from /etc/bluetooth/bt_vendor.conf
08-29 09:12:51.645  5877  5890 I bt_vnd_conf: vnd_load_conf file >/etc/bluetooth/bt_vendor.conf< not found
,08-29 09:12:51.763  5877  5890 D bt_hci  : start_up starting async portion
,08-29 09:12:51.763  5877  5897 I bt_hci  : event_finish_startup
08-29 09:12:51.763  5877  5897 I bt_hci_h4: hal_open
08-29 09:12:51.763  5877  5897 I bt_userial_vendor: userial vendor open: opening /dev/ttyHS0
,08-29 09:12:51.752  5898  5898 W irq/448-msm_hs_: type=1400 audit(0.0:72): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 09:12:51.767  5877  5897 I bt_userial_vendor: device fd = 51 open
,08-29 09:12:51.780  5877  5897 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 09:12:51.783  5877  5897 D bt_hwcfg: Chipset BCM4358A3
,08-29 09:12:51.783  5877  5897 D bt_hwcfg: Target name = [BCM4358A3]
08-29 09:12:51.784  5877  5897 I bt_hwcfg: Found patchfile: /vendor/firmware//BCM4358A3_RFSW.hcd
,08-29 09:12:52.180  5877  5897 I bt_hwcfg: bt vendor lib: set UART baud 115200
,08-29 09:12:52.181  5877  5897 D bt_hwcfg: Settlement delay -- 100 ms
,08-29 09:12:52.181  5877  5897 I bt_hwcfg: Setting fw settlement delay to 100 
,08-29 09:12:52.315  5877  5897 I bt_hwcfg: bt vendor lib: set UART baud 3000000
,08-29 09:12:52.316  5877  5897 I bt_hwcfg: Setting local bd addr to 60:83:34:25:D7:C6
,08-29 09:12:52.317  5877  5897 I bt_hwcfg: vendor lib fwcfg completed
,08-29 09:12:52.317  5877  5897 I bt_vendor: firmware callback
,08-29 09:12:52.318  5877  5897 I bt_hci  : firmware_config_callback
08-29 09:12:52.326  5877  5900 I bt_btu  : btu_task pending for preload complete event
,08-29 09:12:52.326  5877  5900 I bt_btu_task: Bluetooth chip preload is complete
,08-29 09:12:52.326  5877  5900 I bt_btu  : btu_task received preload complete event
,08-29 09:12:52.331  5877  5900 I         : BTE_InitTraceLevels -- TRC_HCI
,08-29 09:12:52.331  5877  5900 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-29 09:12:52.332  5877  5900 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-29 09:12:52.332  5877  5900 I         : BTE_InitTraceLevels -- TRC_AVDT
,08-29 09:12:52.332  5877  5900 I         : BTE_InitTraceLevels -- TRC_AVRC
08-29 09:12:52.332  5877  5900 I         : BTE_InitTraceLevels -- TRC_A2D
08-29 09:12:52.332  5877  5900 I         : BTE_InitTraceLevels -- TRC_BNEP
,08-29 09:12:52.332  5877  5900 I         : BTE_InitTraceLevels -- TRC_BTM
08-29 09:12:52.332  5877  5900 I         : BTE_InitTraceLevels -- TRC_GAP
08-29 09:12:52.332  5877  5900 I         : BTE_InitTraceLevels -- TRC_PAN
,08-29 09:12:52.332  5877  5900 I         : BTE_InitTraceLevels -- TRC_SDP
08-29 09:12:52.333  5877  5900 I         : BTE_InitTraceLevels -- TRC_GATT
08-29 09:12:52.333  5877  5900 I         : BTE_InitTraceLevels -- TRC_SMP
08-29 09:12:52.333  5877  5900 I         : BTE_InitTraceLevels -- TRC_BTAPP
,08-29 09:12:52.333  5877  5900 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-29 09:12:52.411  5877  5900 I bt_btm_sec: BTM_SecRegister p_cb_info->p_le_callback == 0x0xf3eb2c99
,08-29 09:12:52.411  5877  5900 I bt_btm_sec: BTM_SecRegister btm_cb.api.p_le_callback = 0x0xf3eb2c99 
,08-29 09:12:52.437  5877  5893 D BluetoothAdapterProperties: BT_PROPERTY_LOCAL_LE_FEATURES: update from BT controller mNumOfAdvertisementInstancesSupported = 5 mRpaOffloadSupported = true mNumOfOffloadedIrkSupported = 128 mNumOfOffloadedScanFilterSupported = 32 mOffloadedScanResultStorageBytes= 2048 mIsActivityAndEnergyReporting = true mVersSupported = 96 mTotNumOfTrackableAdv = 40 mIsExtendedScanSupported = true mIsDebugLogSupported = false
,08-29 09:12:52.438  5877  5893 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000000
,08-29 09:12:52.439  5877  5893 D BluetoothAdapterProperties: Address is:60:83:34:25:D7:C6
,08-29 09:12:52.442  5877  5893 D BluetoothAdapterProperties: Name is: Nexus 6P
08-29 09:12:52.444  5877  5893 D BluetoothAdapterProperties: Scan Mode:20
08-29 09:12:52.444  5877  5893 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 09:12:52.444  5877  5893 D bt_hci  : do_postload posting postload work item
08-29 09:12:52.445  5877  5897 I bt_hci  : event_postload
08-29 09:12:52.445  5877  5897 I bt_vendor: sco_config_cb
08-29 09:12:52.445  5877  5897 I bt_hci  : sco_config_callback postload finished.
,08-29 09:12:52.449  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:12:52.451  5877  5893 D bt_bte_conf: Device ID record 1 : primary
,08-29 09:12:52.452  5877  5893 D bt_bte_conf:   vendorId            = 000f
08-29 09:12:52.452  5877  5893 D bt_bte_conf:   vendorIdSource      = 0001
08-29 09:12:52.452  5877  5893 D bt_bte_conf:   product             = 1200
08-29 09:12:52.452  5877  5893 D bt_bte_conf:   version             = 1436
08-29 09:12:52.452  5877  5893 D bt_bte_conf:   clientExecutableURL = 
08-29 09:12:52.452  5877  5893 D bt_bte_conf:   serviceDescription  = 
08-29 09:12:52.452  5877  5893 D bt_bte_conf:   documentationURL    = 
08-29 09:12:52.452  5877  5893 D bt_bte_conf: bte_load_did_conf no section named DID2.
08-29 09:12:52.452  5877  5890 D bt_stack_manager: event_start_up_stack finished
08-29 09:12:52.453  5877  5889 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 3
08-29 09:12:52.453  5877  5889 D BluetoothAdapterProperties: Setting state to 15
,08-29 09:12:52.453  5877  5889 I BluetoothAdapterState: Bluetooth adapter state changed: 14-> 15
08-29 09:12:52.455  5877  5889 I BluetoothAdapterState: Entering BleOnState
08-29 09:12:52.455  5877  5897 I bt_vendor: low_power_mode_cb
,08-29 09:12:52.460  5877  5889 D BluetoothAdapterState: Current state: BLE ON, message: 1
,08-29 09:12:52.460  5877  5889 D BluetoothAdapterProperties: Setting state to 11
08-29 09:12:52.460  5877  5889 I BluetoothAdapterState: Bluetooth adapter state changed: 15-> 11
,08-29 09:12:52.465  5877  5877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35c60b5
,08-29 09:12:52.467  5877  5877 D HeadsetService: Received start request. Starting profile...
08-29 09:12:52.470  5877  5877 I BluetoothHeadsetServiceJni: classInitNative: succeeds
,08-29 09:12:52.471  5877  5877 D HeadsetStateMachine: make
08-29 09:12:52.472  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:12:52.481  5877  5877 D HeadsetStateMachine: max_hf_connections = 1
08-29 09:12:52.481  5877  5877 I bt_bluedroid: get_profile_interface handsfree
08-29 09:12:52.481  5877  5893 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000040
08-29 09:12:52.481  5877  5893 E bt_btif : btif_hf_upstreams_evt: Invalid index 127
,08-29 09:12:52.483  5877  5889 I BluetoothAdapterState: Entering PendingCommandState
08-29 09:12:52.484  5877  5877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35c60b5
,08-29 09:12:52.485  5877  5877 D A2dpService: Received start request. Starting profile...
,08-29 09:12:52.485  5877  5877 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-29 09:12:52.486  5877  5877 I bt_bluedroid: get_profile_interface avrcp
,08-29 09:12:52.491  5877  5877 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-29 09:12:52.491  5877  5877 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-29 09:12:52.491  5877  5877 D A2dpStateMachine: make
08-29 09:12:52.492  5877  5877 I bt_bluedroid: get_profile_interface a2dp,
08-29 09:12:52.492  5877  5893 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20000048
08-29 09:12:52.493  5877  5909 D A2dpStateMachine: Enter Disconnected: -2
,08-29 09:12:52.495  5877  5877 I BluetoothHidServiceJni: classInitNative: succeeds
,08-29 09:12:52.495  5877  5877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35c60b5
08-29 09:12:52.496  3576  3576 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-29 09:12:52.496  5877  5877 D HidService: Received start request. Starting profile...
08-29 09:12:52.496  5877  5877 I bt_bluedroid: get_profile_interface hidhost
08-29 09:12:52.496  5877  5893 I bt_bta_hh: BTA_HhEnable sec_mask:0x36 p_cback:0xf3e942d9
08-29 09:12:52.496  5877  5877 D HidService: setHidService(): set to: null
08-29 09:12:52.497  5877  5877 I BluetoothHealthServiceJni: classInitNative: succeeds
08-29 09:12:52.497  5877  5893 I bt_btif_storage: btif_storage_get_adapter_property service_mask:0x20100048
08-29 09:12:52.497  5877  5877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35c60b5
,08-29 09:12:52.498  5877  5877 D HealthService: Received start request. Starting profile...
,08-29 09:12:52.499  5877  5877 I bt_bluedroid: get_profile_interface health
,08-29 09:12:52.500  5877  5877 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-29 09:12:52.500  5877  5877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35c60b5
08-29 09:12:52.501  5877  5877 D PanService: Received start request. Starting profile...
08-29 09:12:52.501  5877  5877 D BluetoothPanServiceJni: initializeNative(L110): pan
08-29 09:12:52.501  5877  5877 I bt_bluedroid: get_profile_interface pan
08-29 09:12:52.501  5877  5893 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
,08-29 09:12:52.504  5877  5877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35c60b5
,08-29 09:12:52.505  5877  5877 D BluetoothMapService: Received start request. Starting profile...
08-29 09:12:52.505  5877  5877 D BluetoothMapService: start()
,08-29 09:12:52.507  5877  5877 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_PROVIDER
,08-29 09:12:52.508  5877  5877 D BluetoothMapAccountLoader: Found 0 application(s) with intent android.bluetooth.action.BLUETOOTH_MAP_IM_PROVIDER
08-29 09:12:52.508  5877  5877 D BluetoothMapAppObserver: createReceiver()
,08-29 09:12:52.509  5877  5877 D BluetoothMapAppObserver: initObservers()
,08-29 09:12:52.509  5877  5877 D BluetoothMapAppObserver: getEnabledAccountItems()
08-29 09:12:52.514  5877  5877 V BluetoothAdapterState: isTurningOff()=false
08-29 09:12:52.514  5877  5877 V BluetoothAdapterState: isTurningOn()=true
08-29 09:12:52.514  5877  5877 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:12:52.514  5877  5877 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:12:52.515  5877  5877 V SapService: SapBinder()
08-29 09:12:52.515  5877  5877 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35c60b5
08-29 09:12:52.516  5877  5877 D SapService: Received start request. Starting profile...
08-29 09:12:52.516  5877  5877 V SapService: start()
,08-29 09:12:52.517  5877  5877 V BluetoothAdapterState: isTurningOff()=false
,08-29 09:12:52.517  5877  5877 V BluetoothAdapterState: isTurningOn()=true
08-29 09:12:52.517  5877  5906 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-29 09:12:52.517  5877  5877 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:12:52.517  5877  5877 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:12:52.517  5877  5877 V BluetoothAdapterState: isTurningOff()=false
08-29 09:12:52.517  5877  5877 V BluetoothAdapterState: isTurningOn()=true
08-29 09:12:52.517  5877  5877 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:12:52.517  5877  5877 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:12:52.518  5877  5877 V BluetoothAdapterState: isTurningOff()=false
,08-29 09:12:52.518  5877  5877 V BluetoothAdapterState: isTurningOn()=true
08-29 09:12:52.518  5877  5877 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:12:52.518  5877  5877 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:12:52.518  5877  5877 V BluetoothAdapterState: isTurningOff()=false
08-29 09:12:52.519  5877  5877 V BluetoothAdapterState: isTurningOn()=true
08-29 09:12:52.519  5877  5877 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:12:52.519  5877  5877 V BluetoothAdapterState: isBleTurningOff()=false
08-29 09:12:52.519  5877  5877 V BluetoothAdapterState: isTurningOff()=false
08-29 09:12:52.519  5877  5877 V BluetoothAdapterState: isTurningOn()=true
08-29 09:12:52.519  5877  5877 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:12:52.519  5877  5877 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 09:12:52.520  5877  5877 V BluetoothAdapterState: isTurningOff()=false
08-29 09:12:52.520  5877  5877 V BluetoothAdapterState: isTurningOn()=true
,08-29 09:12:52.520  5877  5877 V BluetoothAdapterState: isBleTurningOn()=false
08-29 09:12:52.520  5877  5877 V BluetoothAdapterState: isBleTurningOff()=false
,08-29 09:12:52.520  5877  5889 D BluetoothAdapterState: Current state: PENDING_COMMAND, message: 2
08-29 09:12:52.520  5877  5889 D BluetoothAdapterProperties: ScanMode =  20
08-29 09:12:52.521  5877  5889 D BluetoothAdapterProperties: State =  11
,08-29 09:12:52.523  5877  5893 D BluetoothAdapterProperties: Scan Mode:21
,08-29 09:12:52.523  5877  5889 D BluetoothAdapterProperties: Setting state to 12
08-29 09:12:52.523  5877  5889 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-29 09:12:52.523  5877  5893 D BluetoothAdapterProperties: Discoverable Timeout:120
08-29 09:12:52.524  5877  5889 I BluetoothAdapterState: Entering OnState
08-29 09:12:52.524  5677  5688 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 09:12:52.525  3079  3693 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-29 09:12:52.526  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:12:52.526  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:52.526  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:52.526  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:12:52.526  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:12:52.526  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:12:52.526  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:12:52.526  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:12:52.527  3079  3094 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:12:52.527   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:12:52.527   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:12:52.528  3504  3529 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-29 09:12:52.528  3079  3079 D BluetoothInputDevice: Proxy object connected
08-29 09:12:52.528  3079  3079 D HidProfile: Bluetooth service connected
08-29 09:12:52.528  5677  5872 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 09:12:52.529  5625  5625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:12:52.530  5677  5687 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:12:52.530  5677  5687 D BluetoothMap: onBluetoothStateChange: up=true
08-29 09:12:52.532   930   947 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 09:12:52.532   930   930 D BluetoothA2dp: Proxy object connected
08-29 09:12:52.532  3079  3693 D BluetoothPbap: onBluetoothStateChange: up=true
08-29 09:12:52.533  5677  5677 D BluetoothA2dp: Proxy object connected
08-29 09:12:52.534  5877  5877 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
08-29 09:12:52.534  5877  5877 D ObexServerSockets: create(rfcomm = -2, l2capPsm = -2)
,08-29 09:12:52.536  5877  5877 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 09:12:52.538  5877  5877 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 09:12:52.539  5677  5677 D BluetoothMap: Proxy object connected
,08-29 09:12:52.539  5677  5677 D MapProfile: Bluetooth service connected
08-29 09:12:52.539  5677  5677 D BluetoothMap: getConnectedDevices()
08-29 09:12:52.540  5877  5877 D ObexServerSockets: Succeed to create listening sockets 
08-29 09:12:52.540  5877  5877 D ObexServerSockets0: startAccept()
08-29 09:12:52.540  5877  5877 D ObexServerSockets0: prepareForNewConnect()
,08-29 09:12:52.541  3079  3094 D BluetoothA2dp: onBluetoothStateChange: up=true
08-29 09:12:52.542  5877  5877 D BluetoothSdpJni: sdpCreateMapMasRecordNative:
08-29 09:12:52.542  5877  5877 D BluetoothSdpJni: SDP Create record success - handle: 0
08-29 09:12:52.542  3079  3079 D BluetoothA2dp: Proxy object connected
08-29 09:12:52.542  5677  5872 D BluetoothInputDevice: onBluetoothStateChange: up=true
,08-29 09:12:52.544  5877  5914 D ObexServerSockets0: Accepting socket connection...
,08-29 09:12:52.545  5877  5915 D ObexServerSockets0: Accepting socket connection...
,08-29 09:12:52.545  5677  5688 D BluetoothPan: onBluetoothStateChange on: true
,08-29 09:12:52.547   930   947 D BluetoothHeadset: onBluetoothStateChange: up=true
08-29 09:12:52.548  3079  3693 D BluetoothPan: onBluetoothStateChange on: true
08-29 09:12:52.550  3079  3092 D BluetoothMap: onBluetoothStateChange: up=true
08-29 09:12:52.550  3079  3079 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 09:12:52.550  3079  3079 D PanProfile: Bluetooth service connected
08-29 09:12:52.551  3079  3079 D BluetoothMap: Proxy object connected
08-29 09:12:52.551  3079  3079 D MapProfile: Bluetooth service connected
08-29 09:12:52.551  3079  3079 D BluetoothMap: getConnectedDevices()
,08-29 09:12:52.552  5677  5677 D BluetoothInputDevice: Proxy object connected
08-29 09:12:52.552  5677  5677 D HidProfile: Bluetooth service connected
08-29 09:12:52.552   930   930 I Telecom : BluetoothPhoneService: queryPhoneState
08-29 09:12:52.554  5877  5877 D BluetoothMapService: onReceive
08-29 09:12:52.554  5877  5877 D BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-29 09:12:52.554  5877  5877 D BluetoothMapService: STATE_ON
08-29 09:12:52.554  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:12:52.554  5677  5677 D BluetoothPan: BluetoothPAN Proxy object connected
08-29 09:12:52.554  5677  5677 D PanProfile: Bluetooth service connected
08-29 09:12:52.556  5877  5917 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-29 09:12:52.557  5877  5917 D BluetoothSdpJni: sdpCreateSapsRecordNative:
08-29 09:12:52.557  5877  5917 D BluetoothSdpJni: SDP Create record success - handle: 1
,08-29 09:12:52.559  5677  5677 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1221 android.content.ContextWrapper.startService:581 android.content.ContextWrapper.startService:581 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:134 com.android.settings.bluetooth.DockEventReceiver.onReceive:115 
,08-29 09:12:52.566  3576  3576 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x4000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-29 09:12:52.567  5677  5677 D DockEventReceiver: finishStartingService: stopping service
,08-29 09:12:52.575  5677  5677 D BluetoothPbap: Proxy object connected
08-29 09:12:52.575  5677  5677 D PbapServerProfile: Bluetooth service connected
,08-29 09:12:52.579  3079  3079 D BluetoothPbap: Proxy object connected
,08-29 09:12:52.579  3079  3079 D PbapServerProfile: Bluetooth service connected
,08-29 09:12:52.580  5877  5877 D BluetoothMapMasInstance0: Map Service startRfcommSocketListener
,08-29 09:12:52.580  5877  5877 D ObexServerSockets0: prepareForNewConnect()
08-29 09:12:52.580  5877  5921 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 09:12:52.595  5877  5925 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-29 09:12:52.597  5877  5925 I BtOppRfcommListener: Accept thread started.
,08-29 09:12:52.629  5677  5687 D BluetoothHeadset: Proxy object connected
,08-29 09:12:52.630  5677  5872 D BluetoothHeadset: Proxy object connected
,08-29 09:12:52.630   930   930 D BluetoothHeadset: Proxy object connected
,08-29 09:12:52.630   930   930 D BluetoothHeadset: Proxy object connected
08-29 09:12:52.630  3079  3693 D BluetoothHeadset: Proxy object connected
08-29 09:12:52.630  3079  3079 D HeadsetProfile: Bluetooth service connected
08-29 09:12:52.631   930   930 D BluetoothHeadset: Proxy object connected
08-29 09:12:52.631  3504  3738 D BluetoothHeadset: Proxy object connected
08-29 09:12:52.632  5677  5677 D HeadsetProfile: Bluetooth service connected
08-29 09:12:52.634  5677  5677 D HeadsetProfile: Bluetooth service connected
,08-29 09:12:52.648   930   947 D BluetoothHeadset: Proxy object connected
,08-29 09:12:53.532  5625  5671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:12:53.532  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:53.532  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:53.532  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-29 09:12:53.532  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:12:53.532  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:12:53.532  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:12:53.532  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:12:53.537  5625  5671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:12:53.540  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:12:53.540  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@c65a9f3 added. We now have 8 listener(s)
08-29 09:12:53.540  5625  5671 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-29 09:12:53.545   930  3119 D WifiService: setWifiEnabled: false pid=5625, uid=10077
,08-29 09:12:53.545   930  3119 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 09:12:53.552  5625  5671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:12:53.552   930  3548 D WifiService: setWifiEnabled: true pid=5625, uid=10077
08-29 09:12:53.553   930  3548 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-29 09:12:53.557   507   923 D SoftapController: Softap fwReload - Ok
,08-29 09:12:53.560   507   923 D CommandListener: Setting iface cfg
,08-29 09:12:53.560   507   923 D CommandListener: Trying to bring down wlan0
,08-29 09:12:53.561   507   923 D CommandListener: Clearing all IP addresses on wlan0
,08-29 09:12:53.565   930  2938 E WifiMonitor: killSupplicant p2ptrue init.svc.wpa_supplicant=unknown init.svc.p2p_supplicant=unknown
,08-29 09:12:54.024   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:12:54.165   930  2938 D wifi    : set interface wlan0 flags (UP)
,08-29 09:12:54.168   930  2938 I WifiHAL : Initializing wifi
,08-29 09:12:54.169   930  2938 I WifiHAL : Creating socket
,08-29 09:12:54.174   930   947 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-29 09:12:54.174   930  2938 I WifiHAL : Initialized Wifi HAL Successfully; vendor cmd = 103
08-29 09:12:54.174   930  2938 D wifi    : Did set static halHandle = 0x7f8efbac00
08-29 09:12:54.174   930  2938 D wifi    : halHandle = 0x7f8efbac00, mVM = 0x7fab40d140, mCls = 0x20181e
08-29 09:12:54.174   930  2938 D wifi    : array field set
08-29 09:12:54.175   930  2938 I WifiNative-HAL: interface[0] = wlan0
08-29 09:12:54.176   930  5930 I WifiNative-HAL: Waiting for HAL events mWifiHalHandle=547859704832
08-29 09:12:54.177   930  5930 D wifi    : waitForHalEvents called, vm = 0x7fab40d140, obj = 0x20181e, env = 0x7f901322c0
08-29 09:12:54.180   930  2938 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-29 09:12:54.181   930  2938 E WifiHW  : Unable to open connection to supplicant on "@android:wpa_wlan0": No such file or directory
,08-29 09:12:54.185  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:12:54.225  5931  5931 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-29 09:12:54.246  5931  5931 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 09:12:54.255  5931  5931 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-29 09:12:54.255  5931  5931 E wpa_supplicant: Could not read interface p2p-dev-wlan0 flags: No such device
,08-29 09:12:55.029   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:12:55.201   930  2938 D WifiConfigStore: Loading config and enabling all networks 
,08-29 09:12:55.214  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:12:55.214  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:55.214  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:55.214  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:12:55.214  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:12:55.214  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:12:55.214  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:12:55.214  5625  5625 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:12:55.216   930  2938 D WifiConfigStore: loaded 0 passpoint configs
08-29 09:12:55.217   930  2938 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
,08-29 09:12:55.218   930  2938 W WifiConfigStore: Upgrading network 0 to android.uid.system:1000
08-29 09:12:55.218  5625  5625 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:12:55.220   930  2938 E WifiConfigStore: readAutoJoinStatus: Error parsing configurationjava.io.FileNotFoundException: /data/misc/wifi/autojoinconfig.txt: open failed: ENOENT (No such file or directory)
08-29 09:12:55.222   930  2938 E WifiConfigStore: buildPnoList sortedWifiConfigurations size 1
08-29 09:12:55.222   930  2938 E WifiConfigStore: found sortedWifiConfigurations : "NG700"WPA_PSK
,08-29 09:12:55.227   930  2938 D WifiNative-HAL: Setting external_sim to 1
,08-29 09:12:55.227  4210  4210 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-29 09:12:55.227   930  2938 D wifi    : setting dfs flag to true, 0x7f91398080
08-29 09:12:55.228   930  2938 D WifiStateMachine: Setting OUI to DA-A1-19
08-29 09:12:55.228   930  2938 D wifi    : setting scan oui 0x7f91398080
,08-29 09:12:55.228   930  2938 D WifiHAL : Sending mac address OUI
,08-29 09:12:55.247   930  2938 E native  : do suspend true
,08-29 09:12:55.256   930   930 D RttService: SCAN_AVAILABLE : 3
,08-29 09:12:55.256   930  2938 D wifi    : android_net_wifi_setLinkLayerStats: 1
08-29 09:12:55.256   507   923 W CommandListener: Failed to retrieve HW addr for p2p0 (No such device)
08-29 09:12:55.256   930  3046 D RttService: DefaultState got{ when=-1ms what=160512 target=com.android.internal.util.StateMachine$SmHandler }
,08-29 09:12:55.257   507   923 D CommandListener: Setting iface cfg
,08-29 09:12:55.263   930  2937 E WifiP2pService: Unable to change interface settings: java.lang.IllegalStateException: command '75 interface setcfg p2p0 0.0.0.0 0 up' failed with '400 75 Failed to set address (No such device)'
,08-29 09:12:55.264   930  2937 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
,08-29 09:12:55.275   930  2937 D WifiNative-HAL: p2pGetDeviceAddress
08-29 09:12:55.275   930  2937 D WifiNative-HAL: p2pGetDeviceAddress returning 62:83:34:25:d7:62
,08-29 09:12:55.281   930   945 V BatteryStatsService: WiFi energy data was reset, new WiFi energy data is WifiActivityEnergyInfo{ timestamp=192263 mStackState=3 mControllerTxTimeMs=0 mControllerRxTimeMs=0 mControllerIdleTimeMs=10 mControllerEnergyUsed=38 }
,08-29 09:12:55.570  5625  5671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-29 09:12:55.570  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:55.570  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:55.570  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:12:55.570  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:12:55.570  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:12:55.570  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:12:55.570  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:12:55.576  5625  5671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:12:55.584  5625  5671 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
,08-29 09:12:55.585  5625  5671 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
,08-29 09:12:55.590  5625  5671 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@dbf5331 Bundle[{}]
,08-29 09:12:55.591  5625  5671 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-29 09:12:55.592  5625  5671 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-29 09:12:55.593  5625  5671 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-29 09:12:55.594  5625  5671 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-29 09:12:55.595  5625  5671 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-29 09:12:55.597  5625  5671 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-29 09:12:55.605  5625  5671 I System.out: Running OutgoingSocketThread
,08-29 09:12:55.607  5625  5933 D io.jxcore.node.OutgoingSocketThread: Entering thread (ID: 151)
,08-29 09:12:55.608  5625  5933 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 45591
08-29 09:12:55.608  5625  5933 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-29 09:12:56.030   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:12:56.608  5625  5671 I io.jxcore.node.OutgoingSocketThread: close (thread ID: 152)
,08-29 09:12:56.609  5625  5671 I io.jxcore.node.OutgoingSocketThread: close: Complete (thread ID: 152)
,08-29 09:12:56.614  5625  5671 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 157)
,08-29 09:12:56.618  5625  5671 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
,08-29 09:12:56.618  5625  5671 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 158)
,08-29 09:12:56.621  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 09:12:56.622  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60396b0 added. We now have 2 listener(s)
,08-29 09:12:56.623  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
,08-29 09:12:56.624  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:12:56.624  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-29 09:12:56.624  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:12:56.624  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@390f929 added. We now have 9 listener(s)
08-29 09:12:56.624  5625  5671 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:12:56.625  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 09:12:56.629  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:12:56.633  5625  5671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:12:56.633  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:56.633  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:56.633  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:12:56.633  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:12:56.633  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:12:56.633  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:12:56.633  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:12:56.635  5625  5671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:12:56.636  5625  5671 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:12:56.636  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:12:56.636  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e26f24f added. We now have 3 listener(s)
08-29 09:12:56.638  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:12:56.638  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 09:12:56.638  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:12:56.638  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:12:56.638  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-29 09:12:56.639  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c836ddc added. We now have 10 listener(s)
08-29 09:12:56.639  5625  5671 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:12:56.639  5625  5671 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:12:56.639  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:12:56.639  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:12:56.639  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:56.639  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:56.639  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:12:56.639  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:12:56.639  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@60396b0 removed from the list
08-29 09:12:56.640  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:56.640  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@390f929 removed from the list
08-29 09:12:56.641  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:12:56.641  5625  5671 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:12:56.641  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:12:56.642  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:56.643  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:12:56.644  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-29 09:12:56.644  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:12:56.644  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:56.644  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@390f929 not in the list
08-29 09:12:56.644  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:12:56.644  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
,08-29 09:12:56.646  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:12:56.646  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:12:56.646  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:56.646  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c836ddc removed from the list
08-29 09:12:56.646  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:56.646  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:56.646  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:56.646  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:12:56.646  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@e26f24f removed from the list
08-29 09:12:56.647  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-29 09:12:56.647  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@396fee5 added. We now have 2 listener(s)
08-29 09:12:56.649  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 09:12:56.649  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:12:56.649  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:12:56.649  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:12:56.649  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3127dba added. We now have 9 listener(s)
08-29 09:12:56.649  5625  5671 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:12:56.649  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 09:12:56.652  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:12:56.656  5625  5671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:12:56.656  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:56.656  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:56.656  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:12:56.656  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:12:56.656  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:12:56.656  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:12:56.656  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:12:56.658  5625  5671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:12:56.658  5625  5671 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 09:12:56.658  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:12:56.658  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c78bc8 added. We now have 3 listener(s)
08-29 09:12:56.659  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:12:56.660  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 09:12:56.660  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:12:56.660  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:12:56.660  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:12:56.660  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3da461 added. We now have 10 listener(s)
08-29 09:12:56.660  5625  5671 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:12:56.660  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:12:56.660  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 09:12:56.660  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 09:12:56.660  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:12:56.660  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 09:12:56.661  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:12:56.664  5625  5671 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 09:12:56.664  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 09:12:56.668  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 09:12:56.668  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 09:12:56.669  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
,08-29 09:12:56.671  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
,08-29 09:12:56.672  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 09:12:56.672  5625  5671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 09:12:56.672  5625  5671 D BluetoothAdapter: STATE_ON
08-29 09:12:56.675  5877  5888 D BtGatt.GattService: registerClient() - UUID=35ebd766-48ae-4e6a-b561-6daa3ea65e1b
08-29 09:12:56.675  5877  5893 D BtGatt.GattService: onClientRegistered() - UUID=35ebd766-48ae-4e6a-b561-6daa3ea65e1b, clientIf=5
08-29 09:12:56.676  5625  5635 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 09:12:56.677  5877  5887 D BtGatt.GattService: start scan with filters
,08-29 09:12:56.680  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 09:12:56.680  5877  5896 D BtGatt.ScanManager: handling starting scan
,08-29 09:12:56.680  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 09:12:56.680  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 09:12:56.680  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 09:12:56.683  5877  5896 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@35c60b5
,08-29 09:12:56.683  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 09:12:56.683  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 09:12:56.683  5625  5625 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 09:12:56.684  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 09:12:56.687  5625  5671 W io.jxcore.node.StartStopOperationHandler: executeStartOperation: Cancelling a pending operation
,08-29 09:12:56.687  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 09:12:56.687  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-29 09:12:56.687  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:56.687  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 09:12:56.687  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-29 09:12:56.687  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 09:12:56.687  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 09:12:56.687  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 09:12:56.687  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 09:12:56.687  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 09:12:56.688  5625  5671 D BluetoothAdapter: STATE_ON
08-29 09:12:56.689  5877  5905 D BtGatt.GattService: stopScan() - queue size =1
08-29 09:12:56.689  5877  5893 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 09:12:56.689  5877  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:56.690  5877  5916 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 09:12:56.690  5877  5896 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
08-29 09:12:56.690  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:12:56.690  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 09:12:56.690  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 09:12:56.691  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 09:12:56.691  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 09:12:56.692  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:12:56.692  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 09:12:56.692  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 09:12:56.692  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-29 09:12:56.693  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-29 09:12:56.694  5625  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:12:56.694  5625  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:12:56.694  5625  5625 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:12:56.696  5877  5893 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 09:12:56.696  5877  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:56.696  5625  5671 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:12:56.696  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:12:56.696  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:12:56.696  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:56.696  5877  5896 D BtGatt.ScanManager: Starting BLE batch scan
08-29 09:12:56.696  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:56.696  5877  5896 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
08-29 09:12:56.696  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:12:56.697  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:12:56.697  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@396fee5 removed from the list
08-29 09:12:56.697  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:56.697  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3127dba removed from the list
08-29 09:12:56.697  5625  5671 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:12:56.697  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:56.697  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:56.697  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:56.699  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:12:56.699  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:12:56.699  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:56.699  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3127dba not in the list
08-29 09:12:56.699  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:56.699  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:56.700  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:12:56.700  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:12:56.700  5625  5671 I org.t,haliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:56.700  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@b3da461 removed from the list
08-29 09:12:56.700  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:56.700  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:56.700  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:56.700  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:12:56.700  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@9c78bc8 removed from the list
08-29 09:12:56.701  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:12:56.701  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24f259d added. We now have 2 listener(s)
08-29 09:12:56.702  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 09:12:56.702  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:12:56.703  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:12:56.703  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:12:56.703  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d970a12 added. We now have 9 listener(s)
08-29 09:12:56.703  5625  5671 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:12:56.703  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 09:12:56.706  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:12:56.707  5877  5893 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 09:12:56.707  5877  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:56.709  5625  5671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:12:56.709  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:56.709  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:56.709  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:12:56.709  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:12:56.709  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:12:56.709  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:12:56.709  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-29 09:12:56.711  5625  5671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-29 09:12:56.712  5625  5671 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:12:56.712  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:12:56.712  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6420be0 added. We now have 3 listener(s)
08-29 09:12:56.713  5877  5893 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 09:12:56.713  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 09:12:56.713  5877  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:56.713  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:12:56.713  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:12:56.713  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:12:56.713  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:12:56.713  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fd7e99 added. We now have 10 listener(s)
08-29 09:12:56.713  5625  5671 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:12:56.714  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:12:56.714  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:12:56.714  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 09:12:56.714  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-29 09:12:56.714  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:12:56.714  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:12:56.714  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 09:12:56.717  5625  5671 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
08-29 09:12:56.717  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
,08-29 09:12:56.719  5877  5893 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 09:12:56.719  5877  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:56.719  5877  5896 D BtGatt.ScanManager: stopping BLe Batch
,08-29 09:12:56.721  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-29 09:12:56.722  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
08-29 09:12:56.722  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 09:12:56.723  5877  5893 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 09:12:56.723  5877  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:56.724  5877  5896 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
,08-29 09:12:56.725  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 09:12:56.725  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 09:12:56.725  5625  5671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
08-29 09:12:56.726  5625  5671 D BluetoothAdapter: STATE_ON
08-29 09:12:56.727  5877  5916 D BtGatt.GattService: registerClient() - UUID=f211c55e-09be-4937-8e15-36329058ca8f
08-29 09:12:56.728  5877  5893 D BtGatt.GattService: onClientRegistered() - UUID=f211c55e-09be-4937-8e15-36329058ca8f, clientIf=5
08-29 09:12:56.728  5877  5893 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 09:12:56.728  5625  5636 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
08-29 09:12:56.728  5877  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 09:12:56.728  5877  5907 D BtGatt.GattService: start scan with filters
,08-29 09:12:56.731  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
,08-29 09:12:56.731  5877  5896 D BtGatt.ScanManager: handling starting scan
08-29 09:12:56.731  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
08-29 09:12:56.731  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 09:12:56.731  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 09:12:56.734  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 09:12:56.734  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 09:12:56.734  5625  5625 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 09:12:56.735  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
,08-29 09:12:56.736  5877  5893 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
,08-29 09:12:56.736  5877  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:56.736  5877  5896 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 09:12:56.738  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should affect listening to advertisements only
,08-29 09:12:56.738  5625  5671 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
08-29 09:12:56.739  5625  5671 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-29 09:12:56.739  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:12:56.739  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:12:56.739  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:56.739  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:56.739  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 09:12:56.740  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:12:56.740  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@24f259d removed from the list
,08-29 09:12:56.740  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:56.740  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d970a12 removed from the list
08-29 09:12:56.740  5625  5671 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:12:56.740  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:12:56.741  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:56.741  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
,08-29 09:12:56.741  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:56.741  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:12:56.741  5877  5893 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 09:12:56.741  5877  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:56.741  5877  5896 D BtGatt.ScanManager: Starting BLE batch scan
08-29 09:12:56.741  5877  5896 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 09:12:56.742  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:12:56.742  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:12:56.742  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:56.742  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@d970a12 not in the list
,08-29 09:12:56.742  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 09:12:56.742  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 09:12:56.742  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 09:12:56.742  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 09:12:56.743  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 09:12:56.746  5625  5671 D BluetoothAdapter: STATE_ON
,08-29 09:12:56.747  5877  5907 D BtGatt.GattService: stopScan() - queue size =1
08-29 09:12:56.748  5877  5888 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 09:12:56.748  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:12:56.748  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
,08-29 09:12:56.748  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
,08-29 09:12:56.748  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 09:12:56.748  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
08-29 09:12:56.750  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:12:56.750  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 09:12:56.750  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 09:12:56.750  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 09:12:56.750  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:56.751  5877  5893 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 09:12:56.751  5877  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:56.751  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:12:56.751  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:12:56.751  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
,08-29 09:12:56.751  5625  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:12:56.751  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@8fd7e99 removed from the list
08-29 09:12:56.751  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:56.751  5625  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:12:56.751  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:56.751  5625  5625 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:12:56.751  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:56.751  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-29 09:12:56.751  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@6420be0 removed from the list
08-29 09:12:56.752  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:12:56.752  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69e6b55 added. We now have 2 listener(s)
08-29 09:12:56.753  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 09:12:56.753  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:12:56.753  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:12:56.753  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:12:56.753  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee5c96a added. We now have 9 listener(s)
,08-29 09:12:56.753  5625  5671 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:12:56.754  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-29 09:12:56.754  5877  5893 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 09:12:56.754  5877  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:56.755  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:12:56.757  5625  5671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:12:56.757  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:56.757  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:56.757  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:12:56.757  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:12:56.757  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:12:56.757  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:12:56.757  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:12:56.759  5625  5671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:12:56.759  5877  5893 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 09:12:56.759  5877  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:56.759  5625  5671 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-29 09:12:56.759  5877  5896 D BtGatt.ScanManager: stopping BLe Batch
08-29 09:12:56.759  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:12:56.759  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45976f8 added. We now have 3 listener(s)
08-29 09:12:56.760  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:12:56.760  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 09:12:56.761  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:12:56.761  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:12:56.761  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:12:56.761  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82767d1 added. We now have 10 listener(s)
08-29 09:12:56.761  5625  5671 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:12:56.761  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:12:56.761  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-29 09:12:56.761  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
,08-29 09:12:56.761  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-29 09:12:56.761  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-29 09:12:56.762  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-29 09:12:56.763  5625  5671 V io.jxcore.node.ConnectionHelper: Received a request for permission "android.permission.ACCESS_COARSE_LOCATION", but we are expecting that all the required permissions have already been granted
,08-29 09:12:56.763  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-29 09:12:56.765  5877  5893 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 09:12:56.765  5877  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:56.765  5877  5896 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 09:12:56.766  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-29 09:12:56.766  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: applyAdditionalMarshmallowSettings
,08-29 09:12:56.766  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-29 09:12:56.768  5877  5893 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 09:12:56.768  5877  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 09:12:56.769  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: startScanner: Starting...
08-29 09:12:56.769  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: No service UUID, use manufacturer ID: true
08-29 09:12:56.769  5625  5671 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoveryUtils: createScanFilter: BluetoothLeScanFilter [mDeviceName=null, mDeviceAddress=null, mUuid=null, mUuidMask=null, mServiceDataUuid=null, mServiceData=null, mServiceDataMask=null, mManufacturerId=7413, mManufacturerData=null, mManufacturerDataMask=null]
,08-29 09:12:56.769  5625  5671 D BluetoothAdapter: STATE_ON
08-29 09:12:56.771  5877  5905 D BtGatt.GattService: registerClient() - UUID=55392062-559b-49c7-a560-50c0667e7297
08-29 09:12:56.771  5877  5893 D BtGatt.GattService: onClientRegistered() - UUID=55392062-559b-49c7-a560-50c0667e7297, clientIf=5
,08-29 09:12:56.771  5625  5635 D BluetoothLeScanner: onClientRegistered() - status=0 clientIf=5
,08-29 09:12:56.771  5877  5887 D BtGatt.GattService: start scan with filters
08-29 09:12:56.773  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from NOT_STARTED to RUNNING
08-29 09:12:56.773  5877  5896 D BtGatt.ScanManager: handling starting scan
08-29 09:12:56.773  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: true
,08-29 09:12:56.773  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [NOT_STARTED] to [SCANNING]
08-29 09:12:56.774  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [NOT_STARTED] -> [SCANNING]
,08-29 09:12:56.775  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: RUNNING_BLE, is discovering: true, is advertising: false
,08-29 09:12:56.775  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: startBlePeerDiscoverer: OK
08-29 09:12:56.775  5625  5625 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: RUNNING_BLE, is discovering: true, is advertising: false
08-29 09:12:56.776  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: OK
08-29 09:12:56.778  5877  5893 D BtGatt.GattService: onScanFilterEnableDisabled() - clientIf=5, status=0, action=1
08-29 09:12:56.778  5877  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:56.778  5877  5896 D BtGatt.ScanManager: configureFilterParamter 1500 10000 4 0
,08-29 09:12:56.779  5625  5671 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:12:56.780  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:12:56.780  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:12:56.780  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 09:12:56.780  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:56.780  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-29 09:12:56.780  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:12:56.780  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@69e6b55 removed from the list
08-29 09:12:56.780  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:56.780  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee5c96a removed from the list
08-29 09:12:56.780  5625  5671 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:12:56.780  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:12:56.783  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:56.783  5877  5893 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=0, availableSpace=31
08-29 09:12:56.783  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: 1 listener(s) left
08-29 09:12:56.783  5877  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:56.783  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:56.783  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:12:56.783  5877  5896 D BtGatt.ScanManager: Starting BLE batch scan
08-29 09:12:56.783  5877  5896 D BtGatt.ScanManager: configuring batch scan storage, appIf 5
,08-29 09:12:56.784  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:12:56.784  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:12:56.784  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:56.784  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@ee5c96a not in the list
08-29 09:12:56.784  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-29 09:12:56.784  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-29 09:12:56.784  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-29 09:12:56.784  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-29 09:12:56.784  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScanner: Stopping...
,08-29 09:12:56.788  5625  5671 D BluetoothAdapter: STATE_ON
,08-29 09:12:56.788  5877  5888 D BtGatt.GattService: stopScan() - queue size =1
08-29 09:12:56.789  5877  5905 D BtGatt.GattService: unregisterClient() - clientIf=5
08-29 09:12:56.789  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-29 09:12:56.789  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setState: State changed from RUNNING to NOT_STARTED
08-29 09:12:56.789  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: onIsScannerStartedChanged: false
08-29 09:12:56.789  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: updateState: State changed from [SCANNING] to [NOT_STARTED]
08-29 09:12:56.789  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: onBlePeerDiscovererStateChanged: [SCANNING] -> [NOT_STARTED]
,08-29 09:12:56.789  5877  5893 D BtGatt.GattService: onBatchScanStorageConfigured() - clientIf=5, status=0
08-29 09:12:56.790  5877  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:56.790  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:12:56.790  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: stop: Stopped
08-29 09:12:56.790  5625  5671 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-29 09:12:56.790  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-29 09:12:56.790  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:56.792  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:12:56.792  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:12:56.792  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:56.792  5625  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:12:56.792  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@82767d1 removed from the list
08-29 09:12:56.792  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:56.792  5625  5625 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-29 09:12:56.792  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:56.792  5625  5625 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-29 09:12:56.792  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:56.792  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:12:56.792  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@45976f8 removed from the list
08-29 09:12:56.793  5877  5893 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=1
08-29 09:12:56.793  5877  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:56.793  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:12:56.793  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a69b00d added. We now have 2 listener(s)
,08-29 09:12:56.794  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 09:12:56.795  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-29 09:12:56.795  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:12:56.795  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:12:56.795  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b21bc2 added. We now have 9 listener(s)
08-29 09:12:56.795  5625  5671 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:12:56.795  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-29 09:12:56.797  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-29 09:12:56.798  5877  5893 D BtGatt.GattService: onScanFilterParamsConfigured() - clientIf=5, status=0, action=1, availableSpace=32
08-29 09:12:56.798  5877  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:56.798  5877  5896 D BtGatt.ScanManager: stopping BLe Batch
08-29 09:12:56.800  5625  5671 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-29 09:12:56.800  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-29 09:12:56.800  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-29 09:12:56.800  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-29 09:12:56.800  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-29 09:12:56.800  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-29 09:12:56.800  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-29 09:12:56.800  5625  5671 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-29 09:12:56.802  5877  5893 D BtGatt.GattService: onBatchScanStartStopped() - clientIf=5, status=0, startStopAction=0
08-29 09:12:56.802  5877  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
08-29 09:12:56.802  5625  5671 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: ON, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-29 09:12:56.802  5877  5896 D BtGatt.ScanManager: flushPendingBatchResults - clientIf = 5
08-29 09:12:56.802  5625  5671 D io.jxcore.node.ConnectivityMonitor: start: OK
08-29 09:12:56.802  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-29 09:12:56.803  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7602d10 added. We now have 3 listener(s)
08-29 09:12:56.804  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "60:83:34:25:D7:C6"
08-29 09:12:56.804  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-29 09:12:56.804  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-29 09:12:56.804  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-29 09:12:56.804  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0e4009 added. We now have 10 listener(s)
08-29 09:12:56.804  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:12:56.804  5625  5671 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-29 09:12:56.804  5625  5671 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-29 09:12:56.804  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-29 09:12:56.804  5625  5671 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-29 09:12:56.804  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-29 09:12:56.804  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:56.804  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-29 09:12:56.804  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:12:56.804  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@a69b00d removed from the list
08-29 09:12:56.804  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:56.805  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b21bc2 removed from the list
08-29 09:12:56.805  5625  5625 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-29 09:12:56.805  5625  5671 D io.jxcore.node.ConnectivityMonitor: stop
08-29 09:12:56.805  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:56.806  5877  5893 D BtGatt.GattService: onBatchScanReports() - clientIf=5, status=0, reportType=2, numRecords=0
08-29 09:12:56.806  5877  5893 D BtGatt.ScanManager: callback done for clientIf - 5 status - 0
,08-29 09:12:56.807  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-29 09:12:56.807  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:56.807  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:12:56.807  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:12:56.807  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:56.808  5625  5671 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@9b21bc2 not in the list
08-29 09:12:56.808  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:56.808  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:56.808  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-29 09:12:56.808  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-29 09:12:56.809  5625  5671 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-29 09:12:56.809  5625  5671 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@c0e4009 removed from the list
08-29 09:12:56.809  5625  5671 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-29 09:12:56.809  5625  5671 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-29 09:12:56.809  5625  5671 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-29 09:12:56.809  5625  5671 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-29 09:12:56.809  5625  5671 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@7602d10 removed from the list
08-29 09:12:56.810  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-29 09:12:56.810  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-29 09:12:56.810  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-29 09:12:56.810  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-29 09:12:56.810  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-29 09:12:56.810  5625  5671 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-29 09:12:56.813  5625  5934 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 165, name: My test thread name)
08-29 09:12:56.814  5625  5934 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 165, thread name: My test thread name)
08-29 09:12:56.814  5625  5934 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 165, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 09:12:56.815  5625  5935 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 167, name: My test thread name)
08-29 09:12:56.815  5625  5935 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 167, thread name: My test thread name)
08-29 09:12:56.815  5625  5935 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 167, name: My test thread name), during the lifetime of the thread the total number of bytes read was 122 and the total number of bytes written 122
,08-29 09:12:56.817  5625  5671 D com.test.thalitest.ThaliTestRunner: Total number of executed tests: 80
08-29 09:12:56.817  5625  5671 D com.test.thalitest.ThaliTestRunner: Number of passed tests: 80
08-29 09:12:56.817  5625  5671 D com.test.thalitest.ThaliTestRunner: Number of failed tests:  0
08-29 09:12:56.817  5625  5671 D com.test.thalitest.ThaliTestRunner: Number of ignored tests: 0
08-29 09:12:56.817  5625  5671 D com.test.thalitest.ThaliTestRunner: Total duration: 23589 ms
,08-29 09:12:56.819  5625  5671 I jxcore-log: *Native tests were executed*
08-29 09:12:56.819  5625  5671 I jxcore-log: 
08-29 09:12:56.819  5625  5671 I jxcore-log: Total number of executed tests:  80
08-29 09:12:56.819  5625  5671 I jxcore-log: 
08-29 09:12:56.819  5625  5671 I jxcore-log: Number of passed tests:  80
08-29 09:12:56.819  5625  5671 I jxcore-log: 
08-29 09:12:56.819  5625  5671 I jxcore-log: Number of failed tests:  0
08-29 09:12:56.819  5625  5671 I jxcore-log: 
08-29 09:12:56.819  5625  5671 I jxcore-log: Number of ignored tests:  0
08-29 09:12:56.819  5625  5671 I jxcore-log: 
08-29 09:12:56.820  5625  5671 I jxcore-log: Total duration:  23589
08-29 09:12:56.820  5625  5671 I jxcore-log: 
08-29 09:12:56.820  5625  5671 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****
08-29 09:12:56.820  5625  5671 I jxcore-log: 
,08-29 09:12:56.822  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:12:56.822  5625  5671 I jxcore-log: 
08-29 09:12:56.825  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:12:56.825  5625  5671 I jxcore-log: 
08-29 09:12:56.826  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:12:56.826  5625  5671 I jxcore-log: 
08-29 09:12:56.827  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:12:56.827  5625  5671 I jxcore-log: 
08-29 09:12:56.828  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:12:56.828  5625  5671 I jxcore-log: 
08-29 09:12:56.829  5625  5625 I chromium: [INFO:CONSOLE(68)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (68)
08-29 09:12:56.830  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:12:56.830  5625  5671 I jxcore-log: 
08-29 09:12:56.832  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-29 09:12:56.832  5625  5671 I jxcore-log: 
08-29 09:12:56.834  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 09:12:56.834  5625  5671 I jxcore-log: 
08-29 09:12:56.835  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 09:12:56.835  5625  5671 I jxcore-log: 
08-29 09:12:56.836  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 09:12:56.836  5625  5671 I jxcore-log: 
08-29 09:12:56.837  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:12:56.837  5625  5671 I jxcore-log: 
08-29 09:12:56.838  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:12:56.838  5625  5671 I jxcore-log: 
08-29 09:12:56.839  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 09:12:56.839  5625  5671 I jxcore-log: 
08-29 09:12:56.839  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-29 09:12:56.839  5625  5671 I jxcore-log: 
08-29 09:12:56.840  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:12:56.840  5625  5671 I jxcore-log: 
,08-29 09:12:56.841  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:12:56.841  5625  5671 I jxcore-log: 
08-29 09:12:56.841  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 09:12:56.841  5625  5671 I jxcore-log: 
,08-29 09:12:56.842  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 09:12:56.842  5625  5671 I jxcore-log: 
08-29 09:12:56.843  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:12:56.843  5625  5671 I jxcore-log: 
,08-29 09:12:56.843  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"off","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-29 09:12:56.843  5625  5671 I jxcore-log: 
08-29 09:12:56.844  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 09:12:56.844  5625  5671 I jxcore-log: 
,08-29 09:12:56.845  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-29 09:12:56.845  5625  5671 I jxcore-log: 
08-29 09:12:56.845  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 09:12:56.845  5625  5671 I jxcore-log: 
,08-29 09:12:56.846  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 09:12:56.846  5625  5671 I jxcore-log: 
08-29 09:12:56.846  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 09:12:56.846  5625  5671 I jxcore-log: 
,08-29 09:12:56.847  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 09:12:56.847  5625  5671 I jxcore-log: 
,08-29 09:12:56.848  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 09:12:56.848  5625  5671 I jxcore-log: 
08-29 09:12:56.849  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 09:12:56.849  5625  5671 I jxcore-log: 
,08-29 09:12:56.849  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"on","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-29 09:12:56.849  5625  5671 I jxcore-log: 
,08-29 09:12:57.031   544   544 I ServiceManager: Waiting for service AtCmdFwd...
,08-29 09:12:57.195  5625  5625 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 09:12:57.199  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 09:12:57.199  5625  5671 I jxcore-log: 
,08-29 09:12:57.252  5625  5625 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 09:12:57.255  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 09:12:57.255  5625  5671 I jxcore-log: 
,08-29 09:12:57.261  5936  5936 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-29 09:12:57.267  5936  5936 D AndroidRuntime: CheckJNI is OFF
,08-29 09:12:57.293  5625  5625 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-29 09:12:57.291  5936  5936 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-29 09:12:57.296  5625  5671 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-29 09:12:57.296  5625  5671 I jxcore-log: 
,08-29 09:12:57.337  5936  5936 I Radio-JNI: register_android_hardware_Radio DONE
,08-29 09:12:57.352  5936  5936 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-29 09:12:57.358   930   943 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=-1: uninstall pkg
,08-29 09:12:57.359   930   943 I ActivityManager: Killing 5625:com.test.thalitest/u0a77 (adj 0): stop com.test.thalitest
,08-29 09:12:57.443   930  3549 I WindowState: WIN DEATH: Window{92e19c7 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-29 09:12:57.443   930  3157 D GraphicsStats: Buffer count: 2
08-29 09:12:57.444   930  2939 D WifiService: Client connection lost with reason: 4
,08-29 09:12:57.502   930   943 W ActivityManager: Failed trying to unstop package com.test.thalitest: java.lang.IllegalArgumentException: Unknown package: com.test.thalitest
,08-29 09:12:57.502   930   943 W PackageManager: Package com.test.thalitest is missing; assuming frozen
,08-29 09:12:57.503   930   953 I art     : Starting a blocking GC Explicit
,08-29 09:12:57.503   930   943 E ActivityManager: Failure starting process com.test.thalitest
08-29 09:12:57.503   930   943 E ActivityManager: java.lang.RuntimeException: Package com.test.thalitest is frozen!
08-29 09:12:57.503   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3272)
08-29 09:12:57.503   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3231)
08-29 09:12:57.503   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.startProcessLocked(ActivityManagerService.java:3110)
08-29 09:12:57.503   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.startSpecificActivityLocked(ActivityStackSupervisor.java:1395)
08-29 09:12:57.503   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityInnerLocked(ActivityStack.java:2007)
08-29 09:12:57.503   930   943 E ActivityManager: 	at com.android.server.am.ActivityStack.resumeTopActivityLocked(ActivityStack.java:1554)
08-29 09:12:57.503   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2735)
08-29 09:12:57.503   930   943 E ActivityManager: 	at com.android.server.am.ActivityStackSupervisor.resumeTopActivitiesLocked(ActivityStackSupervisor.java:2724)
08-29 09:12:57.503   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.handleAppDiedLocked(ActivityManagerService.java:4592)
08-29 09:12:57.503   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.removeProcessLocked(ActivityManagerService.java:5949)
08-29 09:12:57.503   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.killPackageProcessesLocked(ActivityManagerService.java:5608)
08-29 09:12:57.503   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.forceStopPackageLocked(ActivityManagerService.java:5757)
08-29 09:12:57.503   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService.-wrap1(ActivityManagerService.java)
08-29 09:12:57.503   930   943 E ActivityManager: 	at com.android.server.am.ActivityManagerService$MainHandler.handleMessage(ActivityManagerService.java:1730)
08-29 09:12:57.503   930   943 E ActivityManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-29 09:12:57.503   930   943 E ActivityManager: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:12:57.503   930   943 E ActivityManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-29 09:12:57.503   930   943 E ActivityManager: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
,08-29 09:12:57.503   930   943 I ActivityManager:   Force finishing activity ActivityRecord{1e3b500 u0 com.test.thalitest/.MainActivity t4}
,08-29 09:12:57.512   930  3530 W ActivityManager: Spurious death for ProcessRecord{9a8cecf 0:com.test.thalitest/u0a77}, curProc for 5625: null
,08-29 09:12:57.579   930   953 I art     : Explicit concurrent mark sweep GC freed 26266(1606KB) AllocSpace objects, 2(40KB) LOS objects, 33% free, 28MB/42MB, paused 1.555ms total 76.305ms
,08-29 09:12:57.600   930   953 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-29 09:12:57.602  5936  5936 I art     : System.exit called, status: 0
,08-29 09:12:57.603  5936  5936 I AndroidRuntime: VM exiting with result code 0.
,08-29 09:12:57.617   930   953 I ActivityManager: Start proc 5946:com.android.defcontainer/u0a7 for service com.android.defcontainer/.DefaultContainerService
,08-29 09:12:57.617   930   953 I ActivityManager: Force stopping com.test.thalitest appid=10077 user=0: pkg removed
,08-29 09:12:57.631   930   943 I ActivityManager: Exiting empty application process com.test.thalitest (null)
,08-29 09:12:57.633  3382  3382 I Keyboard.Facilitator: resetDictionaries() : en_US
08-29 09:12:57.634  5877  5877 D BluetoothMapAppObserver: onReceive
,08-29 09:12:57.634  5877  5877 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
08-29 09:12:57.637  3442  3869 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-29 09:12:57.649   930   943 I ActivityManager: Start proc 5959:android.process.acore/u0a2 for broadcast com.android.providers.contacts/.PackageIntentReceiver
,08-29 09:12:57.651   930  2903 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-29 09:12:57.656  3382  5958 I Keyboard.Facilitator.DecoderInitializer: run()
,08-29 09:12:57.671  3382  5958 I Decoder : createOrResetDecoder
,08-29 09:12:57.692  3504  3504 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-29 09:12:57.718  3576  3576 I ConfigService: onCreate
,08-29 09:12:57.723  5959  5959 W System  : ClassLoader referenced unknown path: /system/priv-app/ContactsProvider/lib/arm64
,08-29 09:12:57.702    28    28 W kworker/1:1: type=1400 audit(0.0:73): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 09:12:57.733   930   930 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-29 09:12:57.712    28    28 W kworker/1:1: type=1400 audit(0.0:74): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
08-29 09:12:57.734  3532  3642 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
,08-29 09:12:57.741  3382  5958 I Keyboard.Facilitator.MainLanguageModelLoader: run()
,08-29 09:12:57.747   930  3549 I ActivityManager: Start proc 5975:com.google.android.googlequicksearchbox:crash_report/u0a29 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
,--------- beginning of crash
08-29 09:12:57.748  3532  3642 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-29 09:12:57.748  3532  3642 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 3532
08-29 09:12:57.748  3532  3642 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-29 09:12:57.748  3532  3642 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-29 09:12:57.748  3532  3642 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-29 09:12:57.748  3532  3642 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-29 09:12:57.748  3532  3642 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-29 09:12:57.748  3532  3642 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-29 09:12:57.748  3532  3642 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-29 09:12:57.748  3532  3642 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-29 09:12:57.748  3532  3642 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-29 09:12:57.748  3532  3642 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-29 09:12:57.748  3532  3642 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-29 09:12:57.748  3532  3642 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-29 09:12:57.751   930  3157 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
,08-29 09:12:57.742    28    28 W kworker/1:1: type=1400 audit(0.0:75): avc: granted { setsched } for scontext=u:r:kernel:s0 tcontext=u:r:kernel:s0 tclass=process
,08-29 09:12:57.760  3532  3642 I Process : Sending signal. PID: 3532 SIG: 9
,08-29 09:12:57.801  3382  5958 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /system/app/LatinImeGoogle/LatinImeGoogle.apk (offset=3195532, length=4014912) with up to date LoudsLmContentVersion = 20150512
,08-29 09:12:57.803  3382  5958 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-29 09:12:57.803  3382  5958 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-29 09:12:57.806  3382  5958 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
,08-29 09:12:57.806  3382  5958 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-29 09:12:57.806  3382  5958 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-29 09:12:57.806  3382  5958 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-29 09:12:57.807  3382  5958 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-29 09:12:57.807  3382  5958 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-29 09:12:57.807  3382  5958 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-29 09:12:57.807  3382  5958 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-29 09:12:57.807  3382  5958 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-29 09:12:57.807  3382  5958 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
,08-29 09:12:57.817   385   481 I qdhwcomposer: handle_blank_event: dpy:0 panel power state: 0

```
