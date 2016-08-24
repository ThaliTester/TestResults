#### Test 82203060198550b_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-24 14:04:36.799  2246  2246 I ConfigService: onDestroy
,08-24 14:04:48.194  6686  6686 D AndroidRuntime: 
08-24 14:04:48.194  6686  6686 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-24 14:04:48.202  6686  6686 D AndroidRuntime: CheckJNI is OFF
08-24 14:04:48.403  6686  6686 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-24 14:04:48.414  1033  2049 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-24 14:04:48.429  1967  3982 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-24 14:04:48.435  1033  2049 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-24 14:04:48.437  1033  2049 D ActivityManager: setTaskToReturnTo : TaskRecord{1e6bc497 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-24 14:04:48.438  1033  2049 D ActivityManager: setTaskToReturnTo : TaskRecord{1e6bc497 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-24 14:04:48.439  1033  2049 D WindowStateEx: AppWindowTokenEx init.. 
08-24 14:04:48.440   329   343 E GBMv2   : DFP En is all cleared set to be enabled
08-24 14:04:48.468  1033  2049 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6701 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-24 14:04:48.469  6686  6686 D AndroidRuntime: Shutting down VM
08-24 14:04:48.597  1033  2094 I art     : Explicit concurrent mark sweep GC freed 28698(1291KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.778ms total 89.404ms
08-24 14:04:48.623  1967  3982 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-24 14:04:48.623  1967  3982 D SplitWindowPolicy: topRunningActivity=ActivityInfo{37eae9e1 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-24 14:04:48.625  1967  1984 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-24 14:04:48.625  1967  1984 D SplitWindowPolicy: topRunningActivity=ActivityInfo{274e5306 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-24 14:04:48.667  6701  6701 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-24 14:04:48.752  6701  6701 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-24 14:04:48.763  6701  6701 I LibraryLoader: Loading: webviewchromium
08-24 14:04:48.767  6701  6701 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 5764-5769)
,08-24 14:04:48.768  6701  6701 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 14:04:48.786  6701  6701 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {12170f37}
,08-24 14:04:48.789  6701  6701 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-24 14:04:48.789  6701  6701 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-24 14:04:48.804  6701  6701 I BrowserStartupController: Initializing chromium process, renderers=0
08-24 14:04:48.805  6701  6701 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 14:04:48.830  6701  6701 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-24 14:04:48.830  6701  6701 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-24 14:04:48.831  6701  6701 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-24 14:04:48.832   314  1380 V AudioPolicyService: registerClient() client 0xb14b7ce0, uid 10118
08-24 14:04:48.838  1033  1106 D BluetoothManagerService: Message: 20
08-24 14:04:48.838  1033  1106 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1f84a469:true
08-24 14:04:48.849  6701  6701 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-24 14:04:48.849  6701  6701 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-24 14:04:48.849  6701  6701 I Adreno-EGL: Build Date: 12/12/14 금
08-24 14:04:48.849  6701  6701 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
,08-24 14:04:48.849  6701  6701 I Adreno-EGL: Remote Branch: 
08-24 14:04:48.849  6701  6701 I Adreno-EGL: Local Patches: 
08-24 14:04:48.849  6701  6701 I Adreno-EGL: Reconstruct Branch: 
,08-24 14:04:48.940  6701  6742 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-24 14:04:48.947  6701  6701 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-24 14:04:48.973  6701  6701 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 14:04:48.979  6701  6701 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-24 14:04:48.982  6701  6701 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-24 14:04:48.986  6701  6701 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
,08-24 14:04:48.986  6701  6701 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-24 14:04:49.003  6701  6701 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-24 14:04:49.010  6701  6701 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 14:04:49.011  6701  6701 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-24 14:04:49.046  6701  6754 D OpenGLRenderer: Render dirty regions requested: true
08-24 14:04:49.046  6701  6754 I OpenGLRenderer: Initialized EGL, version 1.4
08-24 14:04:49.062  6701  6754 D OpenGLRenderer: Enabling debug mode 0
,08-24 14:04:49.076  6701  6701 D Atlas   : Validating map...
,08-24 14:04:49.081  1033  2048 D SplitWindow: check instance of lgWin Window{26bc5f9b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-24 14:04:49.131  6701  6752 D LgDataFeature: LgDataFeature() Constructor: none
,08-24 14:04:49.132  6701  6752 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-24 14:04:49.269  1033  1107 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +648ms (total +829ms)
08-24 14:04:49.271  6701  6701 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1d24ab72 time:166273
08-24 14:04:49.271  1033  1107 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{2d92e684 u0 com.test.thalitest/.MainActivity t6} time:166273
,08-24 14:04:49.445  6701  6701 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-24 14:04:49.529  6701  6752 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-24 14:04:49.529  6701  6752 I chromium: 
,08-24 14:04:49.683  6701  6768 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435161600
,08-24 14:04:49.699  6701  6701 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-24 14:04:49.699  6701  6701 I chromium: 
08-24 14:04:49.705  6701  6768 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-24 14:04:49.705  6701  6768 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-24 14:04:49.705  6701  6768 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-24 14:04:49.705  6701  6768 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-24 14:04:49.705  6701  6768 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-24 14:04:49.706  6701  6768 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@158cf596 added. We now have 1 listener(s)
,08-24 14:04:49.713  1033  1753 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:04:49.717  6701  6768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-24 14:04:49.721  6701  6768 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-24 14:04:49.724  6701  6768 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-24 14:04:49.724  6701  6768 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-24 14:04:49.733  6701  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-24 14:04:49.733  6701  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-24 14:04:49.733  6701  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-24 14:04:49.733  6701  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-24 14:04:49.733  6701  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-24 14:04:49.733  6701  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-24 14:04:49.733  6701  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-24 14:04:49.733  6701  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-24 14:04:49.733  6701  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-24 14:04:49.733  6701  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-24 14:04:49.733  6701  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-24 14:04:49.733  6701  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-24 14:04:49.733  6701  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-24 14:04:49.733  6701  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-24 14:04:49.733  6701  6768 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1245f2ed added. We now have 1 listener(s)
08-24 14:04:49.734  6701  6768 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-24 14:04:49.741  1033  1543 D WifiService: New client listening to asynchronous messages
08-24 14:04:49.746  6701  6768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-24 14:04:49.746  6701  6768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-24 14:04:49.746  6701  6768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-24 14:04:49.746  6701  6768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-24 14:04:49.746  6701  6768 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-24 14:04:49.749   329   345 E GBMv2   : DFP En is all cleared set to be enabled
08-24 14:04:49.749   329   345 E GBMv2   : Set value is all cleared set the max
08-24 14:04:49.750   329   345 I GBMv2   : DFP Enabled. Ignore VFP set
,08-24 14:04:49.753  6701  6768 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-24 14:04:49.754  1033  1737 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-24 14:04:49.755  6701  6768 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-24 14:04:49.764  6701  6768 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-24 14:04:49.765  6701  6768 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-24 14:04:49.765  6701  6768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-24 14:04:49.765  6701  6768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-24 14:04:49.765  6701  6768 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-24 14:04:49.765  6701  6768 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-24 14:04:49.765  6701  6768 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-24 14:04:49.765  6701  6768 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-24 14:04:49.765  6701  6768 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-24 14:04:49.765  6701  6768 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-24 14:04:49.765  6701  6768 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-24 14:04:49.768  6701  6701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:04:49.771  6701  6701 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-24 14:04:49.772  6701  6768 I io.jxcore.node.LifeCycleMonitor: start: OK
08-24 14:04:49.807  6701  6701 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-24 14:04:50.462  6701  6771 W jxcore-log: Initializing JXcore engine
08-24 14:04:50.462  6701  6771 W jxcore-log: JXcore engine is ready
,08-24 14:04:50.510  6771  6771 W Thread-772: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10290]" dev="sockfs" ino=10290 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-24 14:04:50.510  6771  6771 W Thread-772: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-24 14:04:50.510  6771  6771 W Thread-772: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[9850]" dev="sockfs" ino=9850 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-24 14:04:50.510  6771  6771 W Thread-772: type=1400 audit(0.0:169): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-24 14:04:50.510  6771  6771 W Thread-772: type=1400 audit(0.0:170): avc: denied { ioctl } for path="socket:[32245]" dev="sockfs" ino=32245 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-24 14:04:50.537  6701  6771 W jxcore-log: Starting JXcore engine
,08-24 14:04:50.616  6701  6771 W jxcore-log: Platform android
08-24 14:04:50.616  6701  6771 W jxcore-log: 
08-24 14:04:50.616  6701  6771 W jxcore-log: Process ARCH arm
08-24 14:04:50.616  6701  6771 W jxcore-log: 
,08-24 14:04:50.813  6701  6771 I jxcore-log: JXcore Cordova bridge is ready!
08-24 14:04:50.813  6701  6771 I jxcore-log: 
08-24 14:04:50.813  6701  6771 W jxcore-log: JXcore engine is started
,08-24 14:04:50.819  6701  6768 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-24 14:04:50.822  6701  6701 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-24 14:04:56.978  6701  6771 E jxcore  : Error!: syntax error
08-24 14:04:56.978  6701  6771 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"591","_columnNumber":"9","_msg":"    at $w.prototype._compile@module.js:591:9"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"/data/data/com.test.thalitest/files/www/jxcore/app.js","_functionName":"","_lineNumber":"14","_columnNumber":"19","_msg":"    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:14:19"},{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"621","_columnNumber":"8","_msg":"    at $w.prototype._compile@module.js:621:8"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"}]
,08-24 14:04:56.988  6701  6701 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "syntax error\nSyntaxError: syntax error\n    at $w.prototype._compile@module.js:591:9\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at @/data/data/com.test.thalitest/files/www/jxcore/app.js:14:19\n    at $w.prototype._compile@module.js:621:8\n    at $w._extensions[\".js\"]@module.js:651:1"", source: file:///android_asset/www/js/thali_main.js (56)
08-24 14:04:56.989  6701  6701 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
,08-24 14:04:57.006  1033  1982 I ActivityManager: Killing 6162:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-24 14:04:57.110  1033  1941 W libprocessgroup: failed to open /acct/uid_10014/pid_6162/cgroup.procs: No such file or directory
,08-24 14:04:57.123  6701  6768 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 134ms. Plugin should use CordovaInterface.getThreadPool().
08-24 14:04:57.131  6701  6701 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-24 14:04:57.132  6701  6701 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-24 14:04:57.133  6701  6701 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
,08-24 14:04:57.133  6701  6701 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-24 14:04:57.134  6701  6701 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-24 14:04:57.134  6701  6701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-24 14:04:57.134  6701  6701 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@158cf596 removed from the list
08-24 14:04:57.134  6701  6701 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-24 14:04:57.134  6701  6701 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1245f2ed removed from the list
08-24 14:04:57.134  6701  6701 D io.jxcore.node.ConnectivityMonitor: stop
08-24 14:04:57.134  6701  6701 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
08-24 14:04:57.160   329   343 E GBMv2   : DFP En is all cleared set to be enabled
,08-24 14:04:57.165  1967  3982 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-24 14:04:57.165  1967  3982 D SplitWindowPolicy: topRunningActivity=ActivityInfo{16495dc7 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-24 14:04:57.167  2076  2076 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-24 14:04:57.169  1967  1984 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-24 14:04:57.169  1967  1984 D SplitWindowPolicy: topRunningActivity=ActivityInfo{26b9bff4 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-24 14:04:57.171  2076  2076 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-24 14:04:57.174  2076  2076 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-24 14:04:57.175  2076  2173 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,08-24 14:04:57.181  1930  1930 D ActionManagerService: notifyUserLog: 1000003
08-24 14:04:57.181  2076  2076 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-24 14:04:57.183  2076  2076 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-24 14:04:57.186  2076  2076 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,08-24 14:04:57.191  3818  4481 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-24 14:04:57.231  1033  1090 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6785 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-24 14:04:57.233  2076  2076 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-24 14:04:57.234  6701  6701 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-24 14:04:57.238  2076  2076 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-24 14:04:57.239  1930  1930 D ActionManagerService: notifyUserLog: 1000004
08-24 14:04:57.240  3818  3834 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-24 14:04:57.242  3818  4481 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-24 14:04:57.244  2076  2076 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-24 14:04:57.244  2076  2076 I GBoardWebViewUtils: , create_time: 1430832262123
08-24 14:04:57.244  2076  2076 I GBoardWebViewUtils: , expire_time: 0
08-24 14:04:57.244  2076  2076 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-24 14:04:57.244  2076  2076 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-24 14:04:57.244  2076  2076 I GBoardWebViewUtils: , display: false
08-24 14:04:57.244  2076  2076 I GBoardWebViewUtils: , animation: false }
,08-24 14:04:57.244  2076  2076 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-24 14:04:57.244  2076  2076 I GBoardWebViewUtils: , create_time: 1430832262287
08-24 14:04:57.244  2076  2076 I GBoardWebViewUtils: , expire_time: 0
08-24 14:04:57.244  2076  2076 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-24 14:04:57.244  2076  2076 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-24 14:04:57.244  2076  2076 I GBoardWebViewUtils: , display: false
08-24 14:04:57.244  2076  2076 I GBoardWebViewUtils: , animation: false }
08-24 14:04:57.244  2076  2076 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-24 14:04:57.244  2076  2076 I GBoardWebViewUtils: , create_time: 1471602816196
08-24 14:04:57.244  2076  2076 I GBoardWebViewUtils: , expire_time: 0
08-24 14:04:57.244  2076  2076 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-24 14:04:57.244  2076  2076 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-24 14:04:57.244  2076  2076 I GBoardWebViewUtils: , display: false
08-24 14:04:57.244  2076  2076 I GBoardWebViewUtils: , animation: false }
08-24 14:04:57.248  2076  6801 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-24 14:04:57.252  6701  6701 W ScreenOrientationListener: Removing an inexistent observer!
,08-24 14:04:57.297  6785  6785 I art     : Almond Protected OAT
,08-24 14:04:57.299  2076  2076 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-24 14:04:57.317  1033  1753 D InputDispatcher: Window went away: Window{26bc5f9b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-24 14:04:57.332  6773  6773 D AndroidRuntime: 
08-24 14:04:57.332  6773  6773 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-24 14:04:57.338  6773  6773 D AndroidRuntime: CheckJNI is OFF
08-24 14:04:57.379  6785  6785 D WeatherApplication: removeAccount
,08-24 14:04:57.380  2076  2076 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-24 14:04:57.383  6785  6785 D WeatherApplication: Account.length = 0
08-24 14:04:57.383  6785  6785 E WeatherApplication: OPERATOR:OPEN
08-24 14:04:57.386  6785  6785 D WeatherAncestor: 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 14:4:57
08-24 14:04:57.389  6785  6785 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-24 14:04:57.389  6785  6785 D Weather.Utils: 2 : All the weather widget is gone.
08-24 14:04:57.390  6785  6785 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-24 14:04:57.391  6785  6785 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-24 14:04:57.391  6785  6785 D Weather.Utils: 2 : All the weather widget is gone.
08-24 14:04:57.392  6785  6785 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 14:4:57
,08-24 14:04:57.393  1033  1966 I ActivityManager: Killing 6262:com.android.defcontainer/u0a4 (adj 15): empty #17
08-24 14:04:57.444  6773  6773 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-24 14:04:57.469  1033  1375 W libprocessgroup: failed to open /acct/uid_10004/pid_6262/cgroup.procs: No such file or directory
,08-24 14:04:57.472  1033  1090 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-24 14:04:57.475  1033  1090 I ActivityManager: Killing 6701:com.test.thalitest/u0a118 (adj 9): stop com.test.thalitest
08-24 14:04:57.488  2076  2076 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-24 14:04:57.522  1033  1543 D WifiService: Client connection lost with reason: 4
,08-24 14:04:57.530  2076  2076 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 14:04:57.532  2076  2076 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
,08-24 14:04:57.533  2076  2076 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-24 14:04:57.534  2076  2076 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-24 14:04:57.535  2076  2076 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-24 14:04:57.554  2076  2076 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-24 14:04:57.554  2076  2076 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 14:04:57.554  2076  2237 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-24 14:04:57.555  2076  2237 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
,08-24 14:04:57.570  2076  2076 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-24 14:04:57.571  2076  2076 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-24 14:04:57.571  2076  2076 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-24 14:04:57.580  2076  2076 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-24 14:04:57.691  1033  2049 W ActivityManager: Spurious death for ProcessRecord{226d3e7c 6701:com.test.thalitest/u0a118}, curProc for 6701: null
,08-24 14:04:57.693  1033  1122 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-24 14:04:57.732  1033  1107 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{8923ca2 u0 com.lge.launcher2/.Launcher t5} time:174735
08-24 14:04:57.737  2571  2571 D [Concierge]Service: onStartCommand(). Type : 8
08-24 14:04:57.738  2571  2571 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,08-24 14:04:57.739  4602  4602 I art     : Explicit concurrent mark sweep GC freed 448(29KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 533us total 36.595ms
08-24 14:04:57.741  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-24 14:04:57.743  2076  2076 D [Concierge]WidgetView: change position of spinner
08-24 14:04:57.755  2571  2571 D [Concierge]Service: Update widget ID : 11
08-24 14:04:57.758  3876  3876 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-24 14:04:57.758  3876  3876 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-24 14:04:57.760  2028  2028 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-24 14:04:57.762  3818  3818 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
,08-24 14:04:57.768  2076  2076 I [Concierge]WidgetView: initWebView(). Time : 1472040297768
08-24 14:04:57.768  2571  2571 D [Concierge]Service: onStartCommand(). Type : 0
08-24 14:04:57.770  2499  2671 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-24 14:04:57.771  6367  6367 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-24 14:04:57.777  1033  1966 V SIM_STK : Menu title from STK is T-Mobile
,08-24 14:04:57.810  4501  4501 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-24 14:04:57.811  4501  4501 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-24 14:04:57.811  4501  4501 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-24 14:04:57.811  4501  4501 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-24 14:04:57.811  4501  4501 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-24 14:04:57.811  4501  4501 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-24 14:04:57.811  4501  4501 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-24 14:04:57.811  4501  4501 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-24 14:04:57.811  4501  4501 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-24 14:04:57.811  4501  4501 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-24 14:04:57.811  4501  4501 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-24 14:04:57.811  4501  4501 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-24 14:04:57.846  1839  1839 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-24 14:04:57.853  1601  1647 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-24 14:04:57.853  1601  1647 D KeyguardModel: createShortcutInfo...
08-24 14:04:57.856  1601  1601 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-24 14:04:57.858  1033  1460 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-24 14:04:57.867  1033  1089 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-24 14:04:57.868  1601  1647 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-24 14:04:57.868  1601  1647 D KeyguardModel: createShortcutInfo...
08-24 14:04:57.873  1601  1647 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-24 14:04:57.873  1601  1647 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 14:04:57.874  1601  1647 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-24 14:04:57.875  1601  1647 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-24 14:04:57.885  1601  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 14:04:57.885  1601  1647 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-24 14:04:57.888  2076  2076 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 1007539818
08-24 14:04:57.889  2076  2076 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-24 14:04:57.889  2076  2076 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-24 14:04:57.890  1601  1647 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-24 14:04:57.890  1601  1647 D KeyguardModel: createShortcutInfo...
,08-24 14:04:57.894  2076  2076 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@12635fd5
08-24 14:04:57.894  2076  2076 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-24 14:04:57.896  2076  2076 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-24 14:04:57.896  2076  2076 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 14:04:57.906  1601  1647 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-24 14:04:57.906  1601  1647 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-24 14:04:57.912  2076  2076 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-24 14:04:57.914  2076  2076 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-24 14:04:57.915  2076  2076 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.PackageUpdateReceiver
08-24 14:04:57.917  1033  1033 I art     : Explicit concurrent mark sweep GC freed 13429(1004KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 1.828ms total 194.271ms
08-24 14:04:57.918  1601  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 14:04:57.919  1601  1647 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-24 14:04:57.919  1601  1601 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-24 14:04:57.919  1601  1601 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-24 14:04:57.919  1033  1122 I art     : WaitForGcToComplete blocked for 39.833ms for cause Explicit
08-24 14:04:57.926  2076  2076 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
,08-24 14:04:57.933  1033  1928 V SIM_STK : Menu title from STK is T-Mobile
08-24 14:04:57.933  1601  1647 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-24 14:04:57.933  1601  1647 D KeyguardModel: createShortcutInfo...
08-24 14:04:57.933  1033  1928 V SIM_STK : Menu title from STK is T-Mobile
08-24 14:04:57.933  2076  2076 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1472040150964, New one : 1472040297768
08-24 14:04:57.934  2076  2076 D [Concierge]WidgetView: Unregister all receivers
08-24 14:04:57.934  2076  2076 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-24 14:04:57.934  2076  2076 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.PackageUpdateReceiver
08-24 14:04:57.934  2076  2076 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 14:04:57.936  2076  2076 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-24 14:04:57.938  2246  2246 I ConfigService: onCreate
,08-24 14:04:57.939  2246  2246 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-24 14:04:57.942  2246  2246 I ConfigService: onBind returning update interface
08-24 14:04:57.946  1839  1839 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-24 14:04:57.946  2076  2076 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-24 14:04:57.947  2246  2246 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-24 14:04:57.947  2246  2246 I ConfigService: onBind returning config service
08-24 14:04:57.947  1601  1647 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 14:04:57.947  1601  1647 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-24 14:04:57.947  1601  1647 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-24 14:04:57.947  1601  1647 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-24 14:04:57.948  2076  2076 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-24 14:04:57.949  2076  2076 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-24 14:04:57.949  1601  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 14:04:57.949  1601  1647 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-24 14:04:57.950  2076  2076 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
,08-24 14:04:57.952  1895  1895 D SplitUIManager: split_name #11 / not available #0
08-24 14:04:57.953  1895  1895 D SplitUIService: removed split : 
08-24 14:04:57.953  1601  1647 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-24 14:04:57.953  1601  1647 D KeyguardModel: createShortcutInfo...
08-24 14:04:57.955  1839  1839 I ConfigFetchService: service connected
08-24 14:04:57.955  2076  2076 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 14:04:57.955  2076  2076 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 14:04:57.962  2246  2246 I ConfigService: onDestroy
08-24 14:04:57.977  1839  6833 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-24 14:04:57.979  1895  1895 D SplitUIManager: split_name #11 / not available #0
08-24 14:04:57.979  1895  1895 I SplitUIService: split app #11
08-24 14:04:57.990  2076  2076 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-24 14:04:57.993  1601  1601 D KeyguardModel: handleShortcutListChanged...
08-24 14:04:57.993  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-24 14:04:57.999  2076  2076 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-24 14:04:57.999  2076  2076 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-24 14:04:58.000  2076  2076 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-24 14:04:58.004  1601  1647 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-24 14:04:58.004  1601  1647 D KeyguardModel: createShortcutInfo...
,08-24 14:04:58.006  1033  1966 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-24 14:04:58.007  3876  3876 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-24 14:04:58.008  3876  3876 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-24 14:04:58.008  3876  3876 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-24 14:04:58.008  3876  3876 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-24 14:04:58.008  3876  3876 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-24 14:04:58.008  3876  3876 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-24 14:04:58.008  3876  3876 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-24 14:04:58.008  3876  3876 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-24 14:04:58.008  3876  3876 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-24 14:04:58.008  1601  1647 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-24 14:04:58.008  3876  3876 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-24 14:04:58.008  1601  1647 D KeyguardModel: createShortcutInfo...
08-24 14:04:58.008  3876  3876 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-24 14:04:58.009  1601  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 14:04:58.009  1601  1647 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-24 14:04:58.010  5896  6838 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-24 14:04:58.013  1601  1647 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-24 14:04:58.013  1601  1647 D KeyguardModel: createShortcutInfo...
08-24 14:04:58.015  1033  1033 D administrator: Handling package changes for user 0
08-24 14:04:58.021  1839  6840 I PeopleContactsSync: CP2 sync disabled
08-24 14:04:58.021  1601  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 14:04:58.022  1601  1647 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
,08-24 14:04:58.027  2076  2076 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1d2ddfe7 time:175030
08-24 14:04:58.029  1601  1647 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-24 14:04:58.029  1601  1647 D KeyguardModel: createShortcutInfo...
08-24 14:04:58.030  1601  1647 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-24 14:04:58.030  1601  1647 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-24 14:04:58.031  1601  1647 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-24 14:04:58.031  1601  1647 D KeyguardModel: createShortcutInfo...
08-24 14:04:58.048  1601  1601 D KeyguardModel: handleShortcutListChanged...
,08-24 14:04:58.048  1601  1601 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-24 14:04:58.055  1839  6839 W GmsApplication: Using Auth Proxy for data requests.
08-24 14:04:58.059  1839  6839 W GmsApplication: Using Auth Proxy for data requests.
08-24 14:04:58.060  1033  2002 V SIM_STK : Menu title from STK is T-Mobile
08-24 14:04:58.101  1839  4745 I Icing   : doRemovePackageData com.test.thalitest
,08-24 14:04:58.105  1033  1033 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-24 14:04:58.105  1033  1033 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-24 14:04:58.106  1033  1033 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-24 14:04:58.107  2076  2076 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-24 14:04:58.107  1033  1576 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-24 14:04:58.108  5976  5976 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-24 14:04:58.127   323   407 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-24 14:04:58.128  3222  6843 I Thermal-Lib: Thermal-Lib-Client: Client request sent
,08-24 14:04:58.130  2297  6844 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-24 14:04:58.138  6472  6472 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-24 14:04:58.157  2028  2028 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-24 14:04:58.157  2028  2028 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-24 14:04:58.158  2028  2028 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-24 14:04:58.164  6367  6367 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-24 14:04:58.197  1033  2049 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6847 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-24 14:04:58.217  1033  1122 I art     : Explicit concurrent mark sweep GC freed 11389(771KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.929ms total 289.583ms
,08-24 14:04:58.234  2076  2076 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-24 14:04:58.256  1033  1089 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 14:04:58.262  1033  1089 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-24 14:04:58.267  2076  2076 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-24 14:04:58.275  6847  6847 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-24 14:04:58.275  6847  6847 W LG Account v2.2: No ProfileInfo entries
08-24 14:04:58.275  6847  6847 I LG Account v2.2: isEnabled: false
08-24 14:04:58.275  6847  6847 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-24 14:04:58.275  6847  6847 I Feature : [Lifetracker]Country: EU
08-24 14:04:58.275  6847  6847 I Feature : [Lifetracker]Operator: OPEN
08-24 14:04:58.275  6847  6847 I Feature : [Lifetracker]Ranking support: false
08-24 14:04:58.275  6847  6847 I Feature : [Lifetracker]Comfort support: false
08-24 14:04:58.275  6847  6847 I Feature : [Lifetracker]Accessory: true
08-24 14:04:58.275  6847  6847 I Feature : [Lifetracker]Health device: true
08-24 14:04:58.275  6847  6847 I Feature : [Lifetracker]Extra Pedometer: false
08-24 14:04:58.276  6847  6847 I Feature : [Lifetracker]Blood glucose device: false
08-24 14:04:58.276  6847  6847 I Feature : [Lifetracker]Device Number: 3
08-24 14:04:58.276  6773  6773 D AndroidRuntime: Shutting down VM
08-24 14:04:58.276  6847  6847 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-24 14:04:58.282  2076  2866 I GBoardtInterface: onReloaded()
08-24 14:04:58.284  2076  2076 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-24 14:04:58.296  1033  1049 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6866 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-24 14:04:58.298  3818  3833 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-24 14:04:58.300  3818  4476 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-24 14:04:58.305  1930  1930 D ActionManagerService: notifyUserLog: 1000001
08-24 14:04:58.305  3818  4481 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-24 14:04:58.306  3818  4481 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-24 14:04:58.308  1930  1930 D ActionManagerService: notifyUserLog: 1000001
,08-24 14:04:58.309  3818  4481 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-24 14:04:58.309  3818  4481 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-24 14:04:58.309  3818  4481 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-24 14:04:58.309  3818  4481 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-24 14:04:58.310  3818  3833 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-24 14:04:58.312  2076  2076 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-24 14:04:58.312  2076  2076 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-24 14:04:58.313  2076  2076 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-24 14:04:58.313  2076  2076 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-24 14:04:58.315  2076  2076 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-24 14:04:58.315  2076  2076 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-24 14:04:58.323  6866  6866 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-24 14:04:58.324  6866  6866 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-24 14:04:58.324  6866  6866 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-24 14:04:58.324  6866  6866 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-24 14:04:58.325  6866  6866 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-24 14:04:58.325  6866  6866 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-24 14:04:58.396  6866  6866 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-24 14:04:58.404  6866  6866 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-24 14:04:58.404  6866  6866 D HideNavigationAppsReceiver: replacing : false
,08-24 14:04:58.405  6866  6866 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-24 14:04:58.407  6866  6866 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-24 14:04:58.407  6866  6866 D ButtonCombinationReceiver: replacing : false
,08-24 14:04:58.412  1033  2094 I ActivityManager: Killing 6432:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-24 14:04:58.487  1033  1737 W libprocessgroup: failed to open /acct/uid_10008/pid_6432/cgroup.procs: No such file or directory
,08-24 14:04:58.527  1033  1122 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6884 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-24 14:04:58.533  4602  6894 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-24 14:04:58.536   352   352 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 199us total 14.681ms
08-24 14:04:58.546   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 182us total 8.784ms
,08-24 14:04:58.555   352   352 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 220us total 9.599ms
,08-24 14:04:58.578  1033  1049 V SIM_STK : Menu title from STK is T-Mobile
,08-24 14:04:58.586  4602  6894 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
--------- beginning of crash
08-24 14:04:58.589  4602  6894 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-24 14:04:58.589  4602  6894 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 4602
08-24 14:04:58.589  4602  6894 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-24 14:04:58.589  4602  6894 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-24 14:04:58.589  4602  6894 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-24 14:04:58.589  4602  6894 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-24 14:04:58.589  4602  6894 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-24 14:04:58.589  4602  6894 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-24 14:04:58.589  4602  6894 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-24 14:04:58.589  4602  6894 E AndroidRuntime: 	at csx.d(PG:186)
08-24 14:04:58.589  4602  6894 E AndroidRuntime: 	at cun.g(PG:594)
08-24 14:04:58.589  4602  6894 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
08-24 14:04:58.589  4602  6894 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
08-24 14:04:58.589  4602  6894 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1349)
08-24 14:04:58.589  4602  6894 E AndroidRuntime: 	at cuw.Tg(PG:368)
08-24 14:04:58.589  4602  6894 E AndroidRuntime: 	at cuy.ub(PG:301)
08-24 14:04:58.589  4602  6894 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
08-24 14:04:58.589  4602  6894 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
08-24 14:04:58.589  4602  6894 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-24 14:04:58.589  4602  6894 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-24 14:04:58.589  4602  6894 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-24 14:04:58.589  4602  6894 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-24 14:04:58.593  1033  1375 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=6903 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-24 14:04:58.597  4602  6894 I Process : Sending signal. PID: 4602 SIG: 9
08-24 14:04:58.599  1033  6913 E DropBoxManagerService: Can't write: system_app_crash
08-24 14:04:58.599  1033  6913 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-24 14:04:58.599  1033  6913 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-24 14:04:58.599  1033  6913 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-24 14:04:58.599  1033  6913 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-24 14:04:58.599  1033  6913 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-24 14:04:58.599  1033  6913 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-24 14:04:58.599  1033  6913 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-24 14:04:58.599  1033  6913 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-24 14:04:58.599  1033  6913 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-24 14:04:58.599  1033  6913 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-24 14:04:58.599  1033  6913 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-24 14:04:58.599  1033  6913 E DropBoxManagerService: 	... 5 more
08-24 14:04:58.600  1033  1966 I ActivityManager: Killing 6114:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-24 14:04:58.616  1033  1543 D WifiService: Client connection lost with reason: 4
,08-24 14:04:58.629  2076  2866 I GBoardtInterface: exportHTML()

```
