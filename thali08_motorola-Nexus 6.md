#### Test 794266502283b5d_thali08_motorola-Nexus 6 Logs


```
--------- beginning of main
08-04 11:16:42.903  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
,08-04 11:16:42.905  1522  1522 V GLSActivity: AuthDelegateWrapperCreated with selected intent: Intent { cmp=com.google.android.gms/.auth.DefaultAuthDelegateService }
08-04 11:16:42.919  3822  3899 V GoogleAuthProtoRequest: [336] a.<init>: mAccountName set to: thalitester@gmail.com
08-04 11:16:42.943  1522  2094 I GLSUser : [GLSUser] getTokenFromGoogle [account: <ELLIDED:1197869880>, callingPkg: com.google.android.apps.gcs, service: oauth2:https://www.googleapis.com/auth/nova
08-04 11:16:42.943  1522  2094 I GLSUser : [GLSUser] No secrets, returning BAD_AUTH for <ELLIDED:1197869880> oauth2:https://www.googleapis.com/auth/nova without consulting the cloud.
08-04 11:16:42.943  1522  2094 I GLSUser : [GLSUser] Extracting token using key: Auth
08-04 11:16:42.943  1522  2094 W GLSActivity: gms.StatusHelper Status from wire: BadAuthentication status: BAD_AUTHENTICATION
08-04 11:16:42.960  3822  3899 W ExperimentUpdateService: [336] ExperimentUpdateService.a: Error executing an experiment update request.  Rescheduling.
08-04 11:16:42.960  3822  3899 W ExperimentUpdateService: [336] ExperimentUpdateService.a: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-04 11:16:42.960  3822  3899 W ExperimentUpdateService: java.util.concurrent.ExecutionException: com.a.a.a: User needs to (re)enter credentials.
08-04 11:16:42.960  3822  3899 W ExperimentUpdateService: 	at com.a.a.a.k.a(SourceFile:117)
08-04 11:16:42.960  3822  3899 W ExperimentUpdateService: 	at com.a.a.a.k.get(SourceFile:97)
08-04 11:16:42.960  3822  3899 W ExperimentUpdateService: 	at com.google.android.flib.nova.experiment.ExperimentUpdateService.a(SourceFile:64)
08-04 11:16:42.960  3822  3899 W ExperimentUpdateService: 	at com.google.android.gms.gcm.d.run(Unknown Source)
08-04 11:16:42.960  3822  3899 W ExperimentUpdateService: Caused by: com.a.a.a: User needs to (re)enter credentials.
08-04 11:16:42.960  3822  3899 W ExperimentUpdateService: 	at com.google.android.flib.a.a.a(SourceFile:167)
08-04 11:16:42.960  3822  3899 W ExperimentUpdateService: 	at com.a.a.a.g.a(SourceFile:79)
08-04 11:16:42.960  3822  3899 W ExperimentUpdateService: 	at com.a.a.a.a.a(SourceFile:93)
08-04 11:16:42.960  3822  3899 W ExperimentUpdateService: 	at com.a.a.k.run(SourceFile:110)
08-04 11:16:43.512  3900  3900 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
08-04 11:16:43.516  3900  3900 D AndroidRuntime: CheckJNI is OFF
08-04 11:16:43.552  3900  3900 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
08-04 11:16:43.594  3900  3900 I Radio-JNI: register_android_hardware_Radio DONE
08-04 11:16:43.614  3900  3900 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-04 11:16:43.618   875  1760 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-04 11:16:43.671   875  1760 I ActivityManager: Start proc 3909:com.test.thalitest/u0a0 for activity com.test.thalitest/.MainActivity
08-04 11:16:43.681  3900  3900 D AndroidRuntime: Shutting down VM
08-04 11:16:43.800  3909  3909 I WebViewFactory: Loading com.google.android.webview version 44.0.2403.117 (code 246011700)
08-04 11:16:43.829  3909  3909 W System  : ClassLoader referenced unknown path: /system/app/WebViewGoogle/lib/arm
08-04 11:16:43.841  3909  3909 I LibraryLoader: Time to load native libraries: 8 ms (timestamps 3587-3595)
08-04 11:16:43.841  3909  3909 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 11:16:43.858  3909  3909 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {8e801f3}
08-04 11:16:43.858  3909  3909 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-04 11:16:43.859  3909  3909 I chromium: [INFO:library_loader_hooks.cc(120)] Chromium logging enabled: level = 0, default verbosity = 0
08-04 11:16:43.866  3909  3909 I BrowserStartupController: Initializing chromium process, singleProcess=true
08-04 11:16:43.867  3909  3909 E SysUtils: ApplicationContext is null in ApplicationStatus
08-04 11:16:43.888  3909  3909 W chromium: [WARNING:resource_bundle.cc(285)] locale_file_path.empty()
08-04 11:16:43.897  3909  3909 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-04 11:16:43.898  3909  3909 E libEGL  : validate_display:255 error 3008 (EGL_BAD_DISPLAY)
08-04 11:16:43.898  3909  3909 I Adreno  : QUALCOMM build                   : 52af4d2, I8366cd0437
08-04 11:16:43.898  3909  3909 I Adreno  : Build Date                       : 10/20/15
08-04 11:16:43.898  3909  3909 I Adreno  : OpenGL ES Shader Compiler Version: XE031.05.13.02
08-04 11:16:43.898  3909  3909 I Adreno  : Local Branch                     : M14
08-04 11:16:43.898  3909  3909 I Adreno  : Remote Branch                    : 
08-04 11:16:43.898  3909  3909 I Adreno  : Remote Branch                    : 
08-04 11:16:43.898  3909  3909 I Adreno  : Reconstruct Branch               : 
,08-04 11:16:43.970   875   892 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@955d115:true
,08-04 11:16:44.022  3909  3909 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-04 11:16:44.047  3909  3909 D SystemWebViewEngine: CordovaWebView is running on device made by: motorola
,08-04 11:16:44.119  3909  3947 D OpenGLRenderer: Use EGL_SWAP_BEHAVIOR_PRESERVED: true
,08-04 11:16:44.134  3909  3933 W chromium: [WARNING:data_reduction_proxy_config.cc(423)] SPDY proxy OFF at startup
,08-04 11:16:44.172  3909  3947 I OpenGLRenderer: Initialized EGL, version 1.4
,08-04 11:16:44.188  1636  1636 I Keyboard.Facilitator: onFinishInput()
,08-04 11:16:44.251   875   893 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +510ms (total +604ms)
,08-04 11:16:44.353  3909  3909 W BindingManager: Cannot call determinedVisibility() - never saw a connection for the pid: 3909
,08-04 11:16:44.532  3909  3909 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-04 11:16:44.792  3909  3950 D jxcore_app_log: JniHelper::setJavaVM(0xb4d3c000), pthread_self() = -1670710992
,08-04 11:16:44.796  3909  3950 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-04 11:16:44.796  3909  3950 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-04 11:16:44.796  3909  3950 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-04 11:16:44.796  3909  3950 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-04 11:16:44.796  3909  3950 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-04 11:16:44.796  3909  3950 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2099646 added. We now have 1 listener(s)
,08-04 11:16:44.798  3909  3950 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: F8:CF:C5:D9:E5:61
,08-04 11:16:44.799  3909  3950 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "F8:CF:C5:D9:E5:61"
08-04 11:16:44.799  3909  3950 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-04 11:16:44.799  3909  3950 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-04 11:16:44.802  3909  3950 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-04 11:16:44.802  3909  3950 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-04 11:16:44.802  3909  3950 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-04 11:16:44.802  3909  3950 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: F8:CF:C5:D9:E5:61
08-04 11:16:44.802  3909  3950 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-04 11:16:44.802  3909  3950 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-04 11:16:44.802  3909  3950 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-04 11:16:44.802  3909  3950 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-04 11:16:44.802  3909  3950 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-04 11:16:44.802  3909  3950 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-04 11:16:44.802  3909  3950 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-04 11:16:44.802  3909  3950 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-04 11:16:44.802  3909  3950 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-04 11:16:44.802  3909  3950 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-04 11:16:44.802  3909  3950 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@254cf5d added. We now have 1 listener(s)
08-04 11:16:44.802  3909  3950 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-04 11:16:44.808   875  1305 D WifiService: New client listening to asynchronous messages
,08-04 11:16:44.809  3909  3950 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-04 11:16:44.810  3909  3950 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-04 11:16:44.810  3909  3950 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-04 11:16:44.810  3909  3950 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-04 11:16:44.810  3909  3950 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-04 11:16:44.816  3909  3950 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-04 11:16:44.816  3909  3950 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is F8:CF:C5:D9:E5:61
,08-04 11:16:44.828  3909  3950 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (SUPPORTED) in persistent storage
,08-04 11:16:44.829  3909  3950 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-04 11:16:44.829  3909  3950 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-04 11:16:44.829  3909  3950 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: SUPPORTED
08-04 11:16:44.829  3909  3950 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-04 11:16:44.829  3909  3950 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-04 11:16:44.829  3909  3950 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-04 11:16:44.829  3909  3950 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-04 11:16:44.829  3909  3950 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-04 11:16:44.829  3909  3950 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
,08-04 11:16:44.830  3909  3950 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-04 11:16:44.833  3909  3950 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-04 11:16:44.833  3909  3909 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:16:44.842  3909  3909 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-04 11:16:44.880  3909  3909 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-04 11:16:45.523   875  1988 D NetlinkSocketObserver: NeighborEvent{elapsedMs=385277, 192.168.1.1, [F4F26D22993E], RTM_NEWNEIGH, NUD_STALE}
,08-04 11:16:46.408  3909  3956 W jxcore-log: Initializing JXcore engine
08-04 11:16:46.408  3909  3956 W jxcore-log: JXcore engine is ready
,08-04 11:16:46.439  3956  3956 W Thread-354: type=1400 audit(0.0:4): avc: denied { ioctl } for path="/dev/pmsg0" dev="tmpfs" ino=8950 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:pmsg_device:s0 tclass=chr_file permissive=0
08-04 11:16:46.443  3956  3956 W Thread-354: type=1400 audit(0.0:5): avc: denied { ioctl } for path="socket:[11581]" dev="sockfs" ino=11581 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket permissive=0
08-04 11:16:46.443  3956  3956 W Thread-354: type=1400 audit(0.0:6): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=4163 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:object_r:debugfs:s0 tclass=file permissive=0
08-04 11:16:46.443  3956  3956 W Thread-354: type=1400 audit(0.0:7): avc: denied { ioctl } for path="socket:[28913]" dev="sockfs" ino=28913 ioctlcmd=5451 scontext=u:r:untrusted_app:s0:c512,c768 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket permissive=0
,08-04 11:16:46.455  3909  3956 W jxcore-log: Starting JXcore engine
,08-04 11:16:46.531  3909  3956 W jxcore-log: Platform android
08-04 11:16:46.531  3909  3956 W jxcore-log: 
08-04 11:16:46.531  3909  3956 W jxcore-log: Process ARCH arm
08-04 11:16:46.531  3909  3956 W jxcore-log: 
,08-04 11:16:46.739  3909  3956 I jxcore-log: JXcore Cordova bridge is ready!
08-04 11:16:46.739  3909  3956 I jxcore-log: 
08-04 11:16:46.739  3909  3956 W jxcore-log: JXcore engine is started
,08-04 11:16:46.751  3909  3950 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-04 11:16:46.758  3909  3909 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-04 11:16:59.802  3909  3956 E jxcore  : Error!: Cannot find module '../thalilogger'
08-04 11:16:59.802  3909  3956 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w._oldRes","_lineNumber":"802","_columnNumber":"9","_msg":"    at $w._oldRes@module.js:802:9"},{"_fileName":"module.js","_functionName":"$w._resolveFilename","_lineNumber":"1771","_columnNumber":"1","_msg":"    at $w._resolveFilename@module.js:1771:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"362","_columnNumber":"4","_msg":"    at $w._load@module.js:362:4"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js","_functionName":"","_lineNumber":"5","_columnNumber":"14","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js:5:14"}]
,08-04 11:16:59.817  3909  3909 I chromium: [INFO:CONSOLE(57)] "app.js file failed to load : "Cannot find module '../thalilogger'\nError: Cannot find module '../thalilogger'\n    at $w._oldRes@module.js:802:9\n    at $w._resolveFilename@module.js:1771:1\n    at $w._load@module.js:362:4\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at @/data/data/com.test.thalitest/files/www/jxcore/node_modules/thali/NextGeneration/thaliMobile.js:5:14"", source: file:///android_asset/www/js/thali_main.js (57)
,08-04 11:16:59.819  3909  3909 I chromium: [INFO:CONSOLE(62)] "****TEST_LOGGER:[PROCESS_ON_EXIT_SUCCESS]****", source: file:///android_asset/www/js/thali_main.js (62)
,08-04 11:16:59.835   875   886 I ActivityManager: Killing 3247:com.android.providers.calendar/u0a3 (adj 15): empty #17
,08-04 11:16:59.882  3909  3909 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-04 11:16:59.883  3909  3909 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
,08-04 11:16:59.883  3909  3950 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 60ms. Plugin should use CordovaInterface.getThreadPool().
08-04 11:16:59.886  3909  3909 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-04 11:16:59.886  3909  3909 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-04 11:16:59.886  3909  3909 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-04 11:16:59.886  3909  3909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-04 11:16:59.886  3909  3909 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2099646 removed from the list
08-04 11:16:59.886  3909  3909 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-04 11:16:59.886  3909  3909 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@254cf5d removed from the list
08-04 11:16:59.886  3909  3909 D io.jxcore.node.ConnectivityMonitor: stop
08-04 11:16:59.887  3909  3909 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
08-04 11:16:59.888  3909  3909 I io.jxcore.node.LifeCycleMonitor: stop: OK
,08-04 11:17:01.094  3958  3958 D AndroidRuntime: >>>>>> START com.android.internal.os.RuntimeInit uid 2000 <<<<<<
,08-04 11:17:01.099  3958  3958 D AndroidRuntime: CheckJNI is OFF
,08-04 11:17:01.134  3958  3958 D ICU     : No timezone override file found: /data/misc/zoneinfo/current/icu/icu_tzdata.dat
,08-04 11:17:01.176  3958  3958 I Radio-JNI: register_android_hardware_Radio DONE
,08-04 11:17:01.197  3958  3958 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-04 11:17:01.211   875   888 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=-1: uninstall pkg
08-04 11:17:01.212   875   888 I ActivityManager: Killing 3909:com.test.thalitest/u0a0 (adj 9): stop com.test.thalitest
,08-04 11:17:01.311   875  1305 D WifiService: Client connection lost with reason: 4
08-04 11:17:01.311   875  1874 D GraphicsStats: Buffer count: 2
,08-04 11:17:01.317   875   898 W PackageSettings: Skipping PackageSetting{291fc7e com.example.hello/10273} due to missing metadata
,08-04 11:17:01.328   875  1760 W ActivityManager: Spurious death for ProcessRecord{cfdf300 0:com.test.thalitest/u0a0}, curProc for 3909: null
,08-04 11:17:01.353   875   898 I art     : Starting a blocking GC Explicit
,08-04 11:17:01.415   875   898 I art     : Explicit concurrent mark sweep GC freed 17135(1202KB) AllocSpace objects, 4(80KB) LOS objects, 33% free, 28MB/43MB, paused 809us total 61.244ms
,08-04 11:17:01.457   875   898 W PackageManager: Couldn't remove dex file for package:  at location /data/app/com.test.thalitest-1/base.apk, retcode=-1
,08-04 11:17:01.462  3958  3958 I art     : System.exit called, status: 0
08-04 11:17:01.463  3958  3958 I AndroidRuntime: VM exiting with result code 0.
,08-04 11:17:01.468   875   898 I ActivityManager: Force stopping com.test.thalitest appid=10000 user=0: pkg removed
,08-04 11:17:01.505  2649  2649 D BluetoothMapAppObserver: onReceive
,08-04 11:17:01.505  2649  2649 D BluetoothMapAppObserver: The removed package is: com.test.thalitest
,08-04 11:17:01.507  1636  1636 I Keyboard.Facilitator: resetDictionaries() : en_US
,08-04 11:17:01.510  1907  2018 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-04 11:17:01.512  3586  3586 D BuaReceiver: ====== got intent:Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.motorola.android.buacontactadapter/.BuaReceiver (has extras) }
,08-04 11:17:01.513   875  1296 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-04 11:17:01.526  1636  3969 I Keyboard.Facilitator.DecoderInitializer: run()
,08-04 11:17:01.528  1636  3969 I Decoder : createOrResetDecoder
,08-04 11:17:01.558  1735  1735 D CarrierServiceBindHelper: Receive action: android.intent.action.PACKAGE_REMOVED
,08-04 11:17:01.572  1522  1522 I ConfigService: onCreate
,08-04 11:17:01.588  3005  3973 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-04 11:17:01.608  3005  3973 E SQLiteLog: (3850) statement aborts at 18: [DELETE FROM calls WHERE (((source_package = 'com.test.thalitest'))) AND ((type = 4))] disk I/O error
,--------- beginning of crash
08-04 11:17:01.610  3005  3973 E AndroidRuntime: FATAL EXCEPTION: IntentService[VoicemailCleanupService]
08-04 11:17:01.610  3005  3973 E AndroidRuntime: Process: android.process.acore, PID: 3005
08-04 11:17:01.610  3005  3973 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-04 11:17:01.610  3005  3973 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-04 11:17:01.610  3005  3973 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-04 11:17:01.610  3005  3973 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-04 11:17:01.610  3005  3973 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-04 11:17:01.610  3005  3973 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-04 11:17:01.610  3005  3973 E AndroidRuntime: 	at com.android.providers.contacts.DbModifierWithNotification.delete(DbModifierWithNotification.java:197)
08-04 11:17:01.610  3005  3973 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentTable.delete(VoicemailContentTable.java:219)
08-04 11:17:01.610  3005  3973 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailContentProvider.delete(VoicemailContentProvider.java:137)
08-04 11:17:01.610  3005  3973 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-04 11:17:01.610  3005  3973 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-04 11:17:01.610  3005  3973 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.handleIntentInternal(VoicemailCleanupService.java:51)
08-04 11:17:01.610  3005  3973 E AndroidRuntime: 	at com.android.providers.contacts.VoicemailCleanupService.onHandleIntent(VoicemailCleanupService.java:40)
08-04 11:17:01.610  3005  3973 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-04 11:17:01.610  3005  3973 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:17:01.610  3005  3973 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-04 11:17:01.610  3005  3973 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-04 11:17:01.613   875  3975 E DropBoxManagerService: Can't write: system_app_crash
08-04 11:17:01.613   875  3975 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop109.tmp: open failed: EROFS (Read-only file system)
08-04 11:17:01.613   875  3975 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 11:17:01.613   875  3975 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 11:17:01.613   875  3975 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 11:17:01.613   875  3975 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 11:17:01.613   875  3975 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 11:17:01.613   875  3975 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-04 11:17:01.613   875  3975 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 11:17:01.613   875  3975 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 11:17:01.613   875  3975 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 11:17:01.613   875  3975 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 11:17:01.613   875  3975 E DropBoxManagerService: 	... 5 more
08-04 11:17:01.615   875   875 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-04 11:17:01.620  1636  3969 I Keyboard.Facilitator.MainLanguageModelLoader: run()
08-04 11:17:01.621  3005  3973 I Process : Sending signal. PID: 3005 SIG: 9
08-04 11:17:01.633  1747  1834 E SQLiteLog: (3850) statement aborts at 23: [DELETE FROM icons WHERE componentName LIKE ? AND profileId = ?] disk I/O error
08-04 11:17:01.635   875   887 W AtomicFile: Couldn't rename file /data/system/users/0/runtime-permissions.xml to backup file /data/system/users/0/runtime-permissions.xml.bak
08-04 11:17:01.637   875   887 E PackageManager: Failed to write settings, restoring backup
08-04 11:17:01.637   875   887 E PackageManager: java.io.IOException: Couldn't create directory /data/system/users/0/runtime-permissions.xml
08-04 11:17:01.637   875   887 E PackageManager: 	at android.util.AtomicFile.startWrite(AtomicFile.java:106)
08-04 11:17:01.637   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.writePermissionsSync(Settings.java:4615)
08-04 11:17:01.637   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence.-wrap1(Settings.java)
08-04 11:17:01.637   875   887 E PackageManager: 	at com.android.server.pm.Settings$RuntimePermissionPersistence$MyHandler.handleMessage(Settings.java:4830)
08-04 11:17:01.637   875   887 E PackageManager: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:17:01.637   875   887 E PackageManager: 	at android.os.Looper.loop(Looper.java:148)
08-04 11:17:01.637   875   887 E PackageManager: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 11:17:01.641   875   888 E DropBoxManagerService: Can't write: system_server_wtf
08-04 11:17:01.641   875   888 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop15.tmp: open failed: EROFS (Read-only file system)
08-04 11:17:01.641   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 11:17:01.641   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 11:17:01.641   875   888 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 11:17:01.641   875   888 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 11:17:01.641   875   888 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 11:17:01.641   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-04 11:17:01.641   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.addErrorToDropBox(ActivityManagerService.java:12543)
08-04 11:17:01.641   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService.handleApplicationWtfInner(ActivityManagerService.java:12356)
08-04 11:17:01.641   875   888 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$17.run(ActivityManagerService.java:12328)
08-04 11:17:01.641   875   888 E DropBoxManagerService: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 11:17:01.641   875   888 E DropBoxManagerService: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 11:17:01.641   875   888 E DropBoxManagerService: 	at android.os.Looper.loop(Looper.java:148)
08-04 11:17:01.641   875   888 E DropBoxManagerService: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 11:17:01.641   875   888 E DropBoxManagerService: 	at com.android.server.ServiceThread.run(ServiceThread.java:46)
08-04 11:17:01.641   875   888 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 11:17:01.641   875   888 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 11:17:01.641   875   888 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 11:17:01.641   875   888 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 11:17:01.641   875   888 E DropBoxManagerService: 	... 13 more
,08-04 11:17:01.645  1522  1522 E SQLiteLog: (3850) statement aborts at 26: [DELETE FROM registrations WHERE package_name = ? AND uid = ?] disk I/O error
08-04 11:17:01.646   875  3141 I ActivityManager: Start proc 3977:com.google.android.googlequicksearchbox:crash_report/u0a28 for service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.silentfeedback.SilentFeedbackService
08-04 11:17:01.646  1747  1834 E AndroidRuntime: FATAL EXCEPTION: launcher-loader
08-04 11:17:01.646  1747  1834 E AndroidRuntime: Process: com.google.android.googlequicksearchbox, PID: 1747
08-04 11:17:01.646  1747  1834 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-04 11:17:01.646  1747  1834 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-04 11:17:01.646  1747  1834 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-04 11:17:01.646  1747  1834 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-04 11:17:01.646  1747  1834 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-04 11:17:01.646  1747  1834 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-04 11:17:01.646  1747  1834 E AndroidRuntime: 	at com.android.launcher3.IconCache.removeIconsForPkg(IconCache.java:240)
08-04 11:17:01.646  1747  1834 E AndroidRuntime: 	at com.android.launcher3.LauncherModel$PackageUpdatedTask.run(LauncherModel.java:3039)
08-04 11:17:01.646  1747  1834 E AndroidRuntime: 	at android.os.Handler.handleCallback(Handler.java:739)
08-04 11:17:01.646  1747  1834 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-04 11:17:01.646  1747  1834 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-04 11:17:01.646  1747  1834 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-04 11:17:01.647  1522  1522 D AndroidRuntime: Shutting down VM
08-04 11:17:01.648   875  1376 W ActivityManager:   Force finishing activity com.google.android.googlequicksearchbox/com.google.android.launcher.GEL
08-04 11:17:01.648  1522  1522 E AndroidRuntime: FATAL EXCEPTION: main
08-04 11:17:01.648  1522  1522 E AndroidRuntime: Process: com.google.process.gapps, PID: 1522
08-04 11:17:01.648  1522  1522 E AndroidRuntime: java.lang.RuntimeException: Unable to start receiver com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-04 11:17:01.648  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2732)
08-04 11:17:01.648  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.-wrap14(ActivityThread.java)
08-04 11:17:01.648  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1421)
08-04 11:17:01.648  1522  1522 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:17:01.648  1522  1522 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-04 11:17:01.648  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 11:17:01.648  1522  1522 E AndroidRuntime: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:17:01.648  1522  1522 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 11:17:01.648  1522  1522 E AndroidRuntime: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 11:17:01.648  1522  1522 E AndroidRuntime: Caused by: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-04 11:17:01.648  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForChangedRowCount(Native Method)
08-04 11:17:01.648  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.executeForChangedRowCount(SQLiteConnection.java:732)
08-04 11:17:01.648  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.executeForChangedRowCount(SQLiteSession.java:754)
08-04 11:17:01.648  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteStatement.executeUpdateDelete(SQLiteStatement.java:64)
08-04 11:17:01.648  1522  1522 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.delete(SQLiteDatabase.java:1499)
08-04 11:17:01.648  1522  1522 E AndroidRuntime: 	at com.google.android.gms.gcm.bg.a(SourceFile:310)
08-04 11:17:01.648  1522  1522 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker.a(SourceFile:126)
08-04 11:17:01.648  1522  1522 E AndroidRuntime: 	at com.google.android.gms.gcm.GcmPackageTracker$GcmPackageChangeReceiver.onReceive(SourceFile:332)
08-04 11:17:01.648  1522  1522 E AndroidRuntime: 	at android.app.ActivityThread.handleReceiver(ActivityThread.java:2725)
08-04 11:17:01.648  1522  1522 E AndroidRuntime: 	... 8 more
08-04 11:17:01.650   875  3983 E DropBoxManagerService: Can't write: system_app_crash
08-04 11:17:01.650   875  3983 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop111.tmp: open failed: EROFS (Read-only file system)
08-04 11:17:01.650   875  3983 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 11:17:01.650   875  3983 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 11:17:01.650   875  3983 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 11:17:01.650   875  3983 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 11:17:01.650   875  3983 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 11:17:01.650   875  3983 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-04 11:17:01.650   875  3983 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 11:17:01.650   875  3983 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 11:17:01.650   875  3983 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 11:17:01.650   875  3983 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 11:17:01.650   875  3983 E DropBoxManagerService: 	... 5 more
08-04 11:17:01.652   875  3988 E DropBoxManagerService: Can't write: system_app_crash
08-04 11:17:01.652   875  3988 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-04 11:17:01.652   875  3988 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 11:17:01.652   875  3988 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 11:17:01.652   875  3988 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 11:17:01.652   875  3988 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 11:17:01.652   875  3988 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 11:17:01.652   875  3988 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-04 11:17:01.652   875  3988 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 11:17:01.652   875  3988 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 11:17:01.652   875  3988 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 11:17:01.652   875  3988 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 11:17:01.652   875  3988 E DropBoxManagerService: 	... 5 more
08-04 11:17:01.655  1747  1834 I Process : Sending signal. PID: 1747 SIG: 9
08-04 11:17:01.659  1522  1522 I Process : Sending signal. PID: 1522 SIG: 9
08-04 11:17:01.677  1636  3969 I Keyboard.Facilitator.MainLanguageModelLoader: loadStaticLm() : Loading File = /data/user/0/com.google.android.inputmethod.latin/files/dicts/en_US/main%00003aen_us (offset=0, length=4430832) with up to date LoudsLmContentVersion = 20160111
08-04 11:17:01.679  1636  3969 I Keyboard.Facilitator.DynamicLanguageModelLoader: run()
08-04 11:17:01.679  1636  3969 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = contacts
,08-04 11:17:01.688  1636  3969 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Contacts.dict
08-04 11:17:01.688  1636  3969 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = history
08-04 11:17:01.689  1636  3969 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loaded File = UserHistory.en_US.dict
08-04 11:17:01.689  1636  3969 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Loading LM = user
08-04 11:17:01.690  1636  3969 I Keyboard.Facilitator.DynamicLanguageModelLoader: run() : Missing File = Personal.en_US.dict
08-04 11:17:01.690  1636  3969 I Keyboard.Facilitator.PersonalDictionaryLoader: run() : Loaded (exit)
08-04 11:17:01.690  1636  3969 I Keyboard.Facilitator.Delight2FileSweeper: run()
08-04 11:17:01.690  1636  3969 I Keyboard.Facilitator.RecurringTaskScheduler: run()
08-04 11:17:01.690  1636  3969 I StatsUtilsManager: startPeriodStatsRecorder() : Success
08-04 11:17:01.691  1636  3969 I PeriodicStatsRecorder: shouldRecordStats() = Too Soon
08-04 11:17:01.705   875  1760 I ActivityManager: Process android.process.acore (pid 3005) has died
08-04 11:17:01.706   875  1760 W ActivityManager: Scheduling restart of crashed service com.android.providers.contacts/.VoicemailCleanupService in 1000ms
08-04 11:17:01.710   875   885 I WindowState: WIN DEATH: Window{cb1b8ee u0 com.google.android.googlequicksearchbox/com.google.android.launcher.GEL}
08-04 11:17:01.710   875  1874 D GraphicsStats: Buffer count: 1
08-04 11:17:01.719   875  1305 D WifiService: Client connection lost with reason: 4
,08-04 11:17:01.726   875   886 I ActivityManager: Process com.google.android.googlequicksearchbox (pid 1747) has died
,08-04 11:17:01.726   875   886 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.ReflectionService in 1000ms
,08-04 11:17:01.728   875  1760 I ActivityManager: Process com.google.process.gapps (pid 1522) has died
08-04 11:17:01.728   875  1760 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.gcm.GcmService in 1000ms
08-04 11:17:01.729   875  1760 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.config.ConfigService in 11000ms
08-04 11:17:01.729   875  1760 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.clearcut.service.ClearcutLoggerService in 21000ms
,08-04 11:17:01.737  1876  1876 W RocketImpressions: ClearcutLogger connection suspended: 1
,08-04 11:17:01.752   875  1758 I ActivityManager: Start proc 3994:com.google.process.gapps/u0a11 for service com.google.android.gms/.clearcut.service.ClearcutLoggerService
,08-04 11:17:01.765  1876  1876 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-04 11:17:01.765  1876  1876 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-04 11:17:01.769  1876  1876 D ChimeraCfgMgr: Loading module com.google.android.gms.games from APK com.google.android.play.games
08-04 11:17:01.769  1876  1876 D ChimeraModuleLdr: Module APK com.google.android.play.games already loaded
,08-04 11:17:01.798  1876  4004 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-04 11:17:01.810   875  1376 I ActivityManager: Start proc 4012:com.google.android.googlequicksearchbox/u0a28 for broadcast com.google.android.googlequicksearchbox/com.google.android.apps.gsa.reflection.AppLaunchReceiver
,08-04 11:17:01.811  1792  4003 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
,08-04 11:17:01.822  1876  4004 E AndroidRuntime: FATAL EXCEPTION: PlayGamesAsyncThread1
08-04 11:17:01.822  1876  4004 E AndroidRuntime: Process: com.google.android.gms, PID: 1876
08-04 11:17:01.822  1876  4004 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-04 11:17:01.822  1876  4004 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-04 11:17:01.822  1876  4004 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-04 11:17:01.822  1876  4004 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-04 11:17:01.822  1876  4004 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-04 11:17:01.822  1876  4004 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-04 11:17:01.822  1876  4004 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransactionWithListener(SQLiteDatabase.java:469)
08-04 11:17:01.822  1876  4004 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.deleteLocked(BaseGmsContentProvider.java:285)
08-04 11:17:01.822  1876  4004 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseGmsContentProvider.delete(BaseGmsContentProvider.java:275)
08-04 11:17:01.822  1876  4004 E AndroidRuntime: 	at com.google.android.chimera.ContentProviderProxy.delete(SourceFile:203)
08-04 11:17:01.822  1876  4004 E AndroidRuntime: 	at android.content.ContentProvider$Transport.delete(ContentProvider.java:339)
08-04 11:17:01.822  1876  4004 E AndroidRuntime: 	at android.content.ContentResolver.delete(ContentResolver.java:1327)
08-04 11:17:01.822  1876  4004 E AndroidRuntime: 	at com.google.android.gms.games.broker.DataBroker.clearPendingOps(DataBroker.java:3044)
08-04 11:17:01.822  1876  4004 E AndroidRuntime: 	at com.google.android.gms.games.service.operations.PackageModifiedOperation.execute(PackageModifiedOperation.java:26)
08-04 11:17:01.822  1876  4004 E AndroidRuntime: 	at com.google.android.gms.games.service.PlayGamesAsyncService$OperationAdapter.execute(PlayGamesAsyncService.java:920)
08-04 11:17:01.822  1876  4004 E AndroidRuntime: 	at com.google.android.gms.chimera.BaseAsyncOperationService$OperationTask.run(BaseAsyncOperationService.java:179)
08-04 11:17:01.822  1876  4004 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor.runWorker(ThreadPoolExecutor.java:1113)
08-04 11:17:01.822  1876  4004 E AndroidRuntime: 	at java.util.concurrent.ThreadPoolExecutor$Worker.run(ThreadPoolExecutor.java:588)
08-04 11:17:01.822  1876  4004 E AndroidRuntime: 	at java.lang.Thread.run(Thread.java:818)
,08-04 11:17:01.831  1876  4004 I Process : Sending signal. PID: 1876 SIG: 9
,08-04 11:17:01.834   875  4024 E DropBoxManagerService: Can't write: system_app_crash
08-04 11:17:01.834   875  4024 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-04 11:17:01.834   875  4024 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 11:17:01.834   875  4024 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 11:17:01.834   875  4024 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 11:17:01.834   875  4024 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 11:17:01.834   875  4024 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 11:17:01.834   875  4024 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-04 11:17:01.834   875  4024 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 11:17:01.834   875  4024 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 11:17:01.834   875  4024 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 11:17:01.834   875  4024 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 11:17:01.834   875  4024 E DropBoxManagerService: 	... 5 more
,08-04 11:17:01.858  1792  4003 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,08-04 11:17:01.865   278   278 E lowmemorykiller: Error writing /proc/1876/oom_score_adj; errno=22
,08-04 11:17:01.887  1792  4003 E SharedPreferencesImpl: Couldn't create directory for SharedPreferences file /data/user/0/com.google.android.googlequicksearchbox/shared_prefs/uncaught_exception_handler_stats.xml
,08-04 11:17:01.887  1792  4003 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-04 11:17:01.887  1792  4003 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 1792
08-04 11:17:01.887  1792  4003 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-04 11:17:01.887  1792  4003 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-04 11:17:01.887  1792  4003 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:553)
08-04 11:17:01.887  1792  4003 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-04 11:17:01.887  1792  4003 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-04 11:17:01.887  1792  4003 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-04 11:17:01.887  1792  4003 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-04 11:17:01.887  1792  4003 E AndroidRuntime: 	at com.google.android.apps.gsa.extradex.icingsync.b.a(ApplicationsHelperImpl.java:86)
08-04 11:17:01.887  1792  4003 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(InternalIcingCorporaProvider.java:3625)
08-04 11:17:01.887  1792  4003 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:355)
08-04 11:17:01.887  1792  4003 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1362)
08-04 11:17:01.887  1792  4003 E AndroidRuntime: 	at com.google.android.search.core.icingsync.e.BW(UpdateIcingCorporaService.java:408)
08-04 11:17:01.887  1792  4003 E AndroidRuntime: 	at com.google.android.search.core.icingsync.g.aOD(UpdateIcingCorporaService.java:347)
08-04 11:17:01.887  1792  4003 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(UpdateIcingCorporaService.java:320)
08-04 11:17:01.887  1792  4003 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(UpdateIcingCorporaService.java:1215)
08-04 11:17:01.887  1792  4003 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:66)
08-04 11:17:01.887  1792  4003 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:17:01.887  1792  4003 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:148)
08-04 11:17:01.887  1792  4003 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
,08-04 11:17:01.889   875  1884 W ActivityManager: Process com.google.android.googlequicksearchbox has crashed too many times: killing!
,08-04 11:17:01.890   875  1884 I ActivityManager: Killing 1792:com.google.android.googlequicksearchbox:search/u0a28 (adj 5): crash
,08-04 11:17:01.893   875  4025 E DropBoxManagerService: Can't write: system_app_crash
08-04 11:17:01.893   875  4025 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop114.tmp: open failed: EROFS (Read-only file system)
08-04 11:17:01.893   875  4025 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:452)
08-04 11:17:01.893   875  4025 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-04 11:17:01.893   875  4025 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-04 11:17:01.893   875  4025 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-04 11:17:01.893   875  4025 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:270)
08-04 11:17:01.893   875  4025 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$18.run(ActivityManagerService.java:12536)
08-04 11:17:01.893   875  4025 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-04 11:17:01.893   875  4025 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-04 11:17:01.893   875  4025 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-04 11:17:01.893   875  4025 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:438)
08-04 11:17:01.893   875  4025 E DropBoxManagerService: 	... 5 more
,08-04 11:17:01.910  3994  3994 W System  : ClassLoader referenced unknown path: /system/priv-app/PrebuiltGmsCore/lib/arm
,08-04 11:17:01.943  3994  3994 I MultiDex: VM with version 2.1.0 has multidex support
,08-04 11:17:01.943  3994  3994 I MultiDex: install
08-04 11:17:01.943  3994  3994 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-04 11:17:01.954  4012  4012 E SQLiteDatabase: Failed to open database '/data/user/0/com.google.android.googlequicksearchbox/databases/launcher.db'.
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:207)
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:191)
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:806)
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:791)
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:694)
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:571)
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:269)
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider$DatabaseHelper.<init>(LauncherProvider.java:482)
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: 	at com.android.launcher3.LauncherProvider.onCreate(LauncherProvider.java:89)
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1748)
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1723)
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5153)
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4748)
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4688)
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: 	at android.app.ActivityThread.-wrap1(ActivityThread.java)
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1405)
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:148)
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5417)
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:726)
08-04 11:17:01.954  4012  4012 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:616)
08-04 11:17:01.954  4012  4012 D AndroidRuntime: Shutting down VM
,08-04 11:17:01.964  3977  4000 W GmsClient: service died
,08-04 11:17:01.965   875  1376 D ConnectivityService: ConnectivityService NetworkRequestInfo binderDied(NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], android.os.BinderProxy@da729aa)
,08-04 11:17:01.966  3977  3977 E SilentFeedbackService: GoogleApiClient silent feedback connection failed with result: 8
,08-04 11:17:01.966   875  1306 D ConnectivityService: releasing NetworkRequest NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-04 11:17:01.969   875  1305 D WifiService: Client connection lost with reason: 4
,08-04 11:17:01.976   875  1306 E ConnectivityService: RemoteException caught trying to send a callback msg for NetworkRequest [ id=4, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
,08-04 11:17:01.981   875  1884 I ActivityManager: START u0 {act=android.intent.action.MAIN cat=[android.intent.category.HOME] flg=0x10000000 cmp=com.google.android.googlequicksearchbox/com.google.android.launcher.GEL} from uid 0 on display 0
,08-04 11:17:01.985   278   278 E lowmemorykiller: Error opening /proc/1876/oom_score_adj; errno=2
,08-04 11:17:01.991   875  3141 I ActivityManager: Process com.google.android.gms (pid 1876) has died
,08-04 11:17:01.992   875  3141 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.feedback.FeedbackService in 1000ms
,08-04 11:17:01.993   875  3141 W ActivityManager: Scheduling restart of crashed service com.google.android.gms/.games.chimera.GamesAsyncServiceProxy in 10999ms

```
