#### Test 82337235c8e499b_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-23 13:41:16.810  2136  2136 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
08-23 13:41:16.815  2136  2136 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,08-23 13:41:41.011  6923  6923 D AndroidRuntime: 
08-23 13:41:41.011  6923  6923 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-23 13:41:41.016  6923  6923 D AndroidRuntime: CheckJNI is OFF
08-23 13:41:41.142  6923  6923 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-23 13:41:41.147  1036  2016 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-23 13:41:41.157  1945  1961 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-23 13:41:41.160  1036  2016 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-23 13:41:41.161  1036  2016 D ActivityManager: setTaskToReturnTo : TaskRecord{3c145479 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-23 13:41:41.161  1036  2016 D ActivityManager: setTaskToReturnTo : TaskRecord{3c145479 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-23 13:41:41.162  1036  2016 D WindowStateEx: AppWindowTokenEx init.. 
08-23 13:41:41.163   345   368 E GBMv2   : DFP En is all cleared set to be enabled
08-23 13:41:41.199  1036  2016 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6938 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-23 13:41:41.203  6923  6923 D AndroidRuntime: Shutting down VM
08-23 13:41:41.256  1945  1961 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-23 13:41:41.257  1945  1961 D SplitWindowPolicy: topRunningActivity=ActivityInfo{38913ec2 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-23 13:41:41.258  1945  1960 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-23 13:41:41.259  1945  1960 D SplitWindowPolicy: topRunningActivity=ActivityInfo{230304d3 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-23 13:41:41.305  6938  6938 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-23 13:41:41.402  6938  6938 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-23 13:41:41.420  6938  6938 I LibraryLoader: Loading: webviewchromium
,08-23 13:41:41.424  6938  6938 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 5725-5730)
08-23 13:41:41.424  6938  6938 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 13:41:41.445  6938  6938 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {14b77bc0}
08-23 13:41:41.446  6938  6938 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 13:41:41.447  6938  6938 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-23 13:41:41.459  6938  6938 I BrowserStartupController: Initializing chromium process, renderers=0
,08-23 13:41:41.461  6938  6938 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 13:41:41.473  6938  6938 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-23 13:41:41.475  6938  6938 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,08-23 13:41:41.475  6938  6938 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-23 13:41:41.477   330  1397 V AudioPolicyService: registerClient() client 0xb100a0e0, uid 10118
08-23 13:41:41.483  1036  1118 D BluetoothManagerService: Message: 20
08-23 13:41:41.483  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2d96653b:true
08-23 13:41:41.503  6938  6938 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-23 13:41:41.503  6938  6938 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-23 13:41:41.503  6938  6938 I Adreno-EGL: Build Date: 12/12/14 금
08-23 13:41:41.503  6938  6938 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-23 13:41:41.503  6938  6938 I Adreno-EGL: Remote Branch: 
08-23 13:41:41.503  6938  6938 I Adreno-EGL: Local Patches: 
08-23 13:41:41.503  6938  6938 I Adreno-EGL: Reconstruct Branch: 
,08-23 13:41:41.598  6938  6979 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-23 13:41:41.606  6938  6938 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-23 13:41:41.629  6938  6938 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 13:41:41.636  6938  6938 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-23 13:41:41.639  6938  6938 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-23 13:41:41.643  6938  6938 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-23 13:41:41.643  6938  6938 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-23 13:41:41.661  6938  6938 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-23 13:41:41.669  6938  6938 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 13:41:41.669  6938  6938 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 13:41:41.713  6938  6991 D OpenGLRenderer: Render dirty regions requested: true
08-23 13:41:41.713  6938  6991 I OpenGLRenderer: Initialized EGL, version 1.4
08-23 13:41:41.730  6938  6991 D OpenGLRenderer: Enabling debug mode 0
,08-23 13:41:41.746  6938  6938 D Atlas   : Validating map...
,08-23 13:41:41.747  1036  1114 W ActivityManager: Activity pause timeout for ActivityRecord{14fb05be u0 com.test.thalitest/.MainActivity t6}
08-23 13:41:41.751  1036  2015 D SplitWindow: check instance of lgWin Window{1ad85e5d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-23 13:41:41.826  6938  6989 D LgDataFeature: LgDataFeature() Constructor: none
08-23 13:41:41.826  6938  6989 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-23 13:41:41.856  1036  1119 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +609ms (total +692ms)
08-23 13:41:41.856  6938  6938 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@905758f time:166163
,08-23 13:41:41.856  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{14fb05be u0 com.test.thalitest/.MainActivity t6} time:166163
08-23 13:41:41.991  6938  6938 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-23 13:41:41.991  6938  6938 I chromium: 
,08-23 13:41:42.045  6938  6938 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 13:41:42.128  6938  6989 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-23 13:41:42.128  6938  6989 I chromium: 
,08-23 13:41:42.266  6938  7001 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435157504
,08-23 13:41:42.280  6938  7001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 13:41:42.280  6938  7001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 13:41:42.280  6938  7001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 13:41:42.280  6938  7001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 13:41:42.280  6938  7001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-23 13:41:42.280  6938  7001 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d401523 added. We now have 1 listener(s)
,08-23 13:41:42.287  1036  2016 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 13:41:42.294  6938  7001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,08-23 13:41:42.300  6938  7001 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-23 13:41:42.302  6938  7001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 13:41:42.302  6938  7001 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 13:41:42.311  6938  7001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 13:41:42.311  6938  7001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 13:41:42.311  6938  7001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 13:41:42.311  6938  7001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-23 13:41:42.311  6938  7001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 13:41:42.311  6938  7001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 13:41:42.311  6938  7001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 13:41:42.311  6938  7001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 13:41:42.311  6938  7001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 13:41:42.311  6938  7001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 13:41:42.311  6938  7001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 13:41:42.311  6938  7001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 13:41:42.311  6938  7001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 13:41:42.311  6938  7001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-23 13:41:42.312  6938  7001 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26efcd9e added. We now have 1 listener(s)
08-23 13:41:42.312  6938  7001 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-23 13:41:42.318  1036  1486 D WifiService: New client listening to asynchronous messages
08-23 13:41:42.323  6938  7001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 13:41:42.323  6938  7001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 13:41:42.325  6938  7001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 13:41:42.325  6938  7001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 13:41:42.325  6938  7001 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-23 13:41:42.337  6938  7001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
,08-23 13:41:42.338  1036  1944 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 13:41:42.339  6938  7001 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-23 13:41:42.352  6938  7001 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-23 13:41:42.352  6938  7001 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 13:41:42.352  6938  7001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 13:41:42.352  6938  7001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 13:41:42.352  6938  7001 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 13:41:42.352  6938  7001 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 13:41:42.352  6938  7001 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 13:41:42.352  6938  7001 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 13:41:42.352  6938  7001 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 13:41:42.352  6938  7001 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 13:41:42.352  6938  7001 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 13:41:42.357  6938  6938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 13:41:42.360  6938  6938 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 13:41:42.361  6938  7001 I io.jxcore.node.LifeCycleMonitor: start: OK
08-23 13:41:42.417  6938  6938 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 13:41:42.444   345   370 E GBMv2   : DFP En is all cleared set to be enabled
08-23 13:41:42.444   345   370 E GBMv2   : Set value is all cleared set the max
08-23 13:41:42.444   345   370 I GBMv2   : DFP Enabled. Ignore VFP set
,08-23 13:41:43.300  6938  7007 W jxcore-log: Initializing JXcore engine
,08-23 13:41:43.300  6938  7007 W jxcore-log: JXcore engine is ready
,08-23 13:41:43.333  7007  7007 W Thread-797: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[8341]" dev="sockfs" ino=8341 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-23 13:41:43.343  7007  7007 W Thread-797: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-23 13:41:43.343  7007  7007 W Thread-797: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[10480]" dev="sockfs" ino=10480 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-23 13:41:43.343  7007  7007 W Thread-797: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-23 13:41:43.343  7007  7007 W Thread-797: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33374]" dev="sockfs" ino=33374 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-23 13:41:43.373  6938  7007 W jxcore-log: Starting JXcore engine
,08-23 13:41:43.452  6938  7007 W jxcore-log: Platform android
08-23 13:41:43.452  6938  7007 W jxcore-log: 
08-23 13:41:43.452  6938  7007 W jxcore-log: Process ARCH arm
08-23 13:41:43.452  6938  7007 W jxcore-log: 
,08-23 13:41:43.641  6938  7007 I jxcore-log: JXcore Cordova bridge is ready!
08-23 13:41:43.641  6938  7007 I jxcore-log: 
,08-23 13:41:43.641  6938  7007 W jxcore-log: JXcore engine is started
,08-23 13:41:43.654  6938  7001 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-23 13:41:43.657  6938  6938 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 13:41:43.694  6938  7007 E jxcore  : Error!: missing name after . operator
08-23 13:41:43.694  6938  7007 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"591","_columnNumber":"9","_msg":"    at $w.prototype._compile@module.js:591:9"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:260:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,08-23 13:41:43.707  6938  6938 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "missing name after . operator\nSyntaxError: missing name after . operator\n    at $w.prototype._compile@module.js:591:9\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at internal_methods.loadMainFile@main.js:260:5\n    at JXMobile.executeJSON@main.js:279:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (56)
08-23 13:41:43.708  6938  6938 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
,08-23 13:41:43.718  1036  1051 I ActivityManager: Killing 6166:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-23 13:41:43.738  1036  1979 W libprocessgroup: failed to open /acct/uid_10014/pid_6166/cgroup.procs: No such file or directory
08-23 13:41:43.739  6938  7001 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 29ms. Plugin should use CordovaInterface.getThreadPool().
,08-23 13:41:43.748  6938  6938 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-23 13:41:43.751  6938  6938 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-23 13:41:43.752  6938  6938 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 13:41:43.752  6938  6938 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 13:41:43.752  6938  6938 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 13:41:43.753  6938  6938 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
,08-23 13:41:43.762  6938  6938 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d401523 removed from the list
08-23 13:41:43.762  6938  6938 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 13:41:43.762  6938  6938 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@26efcd9e removed from the list
08-23 13:41:43.762  6938  6938 D io.jxcore.node.ConnectivityMonitor: stop
08-23 13:41:43.762  6938  6938 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
08-23 13:41:43.779   345   368 E GBMv2   : DFP En is all cleared set to be enabled
,08-23 13:41:43.785  1945  1961 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-23 13:41:43.785  1945  1961 D SplitWindowPolicy: topRunningActivity=ActivityInfo{21f38810 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-23 13:41:43.791  1945  1960 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-23 13:41:43.791  1945  1960 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3485ff09 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
,08-23 13:41:43.793  6938  6938 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-23 13:41:43.804  6938  6938 W ScreenOrientationListener: Removing an inexistent observer!
,08-23 13:41:43.805  2035  2035 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-23 13:41:43.807  2035  2035 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-23 13:41:43.809  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-23 13:41:43.810  2035  2132 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
08-23 13:41:43.815  1909  1909 D ActionManagerService: notifyUserLog: 1000003
08-23 13:41:43.815  3774  4783 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-23 13:41:43.816  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-23 13:41:43.817  2035  2035 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-23 13:41:43.820  2035  2035 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
,08-23 13:41:43.857  1036  2015 D InputDispatcher: Window went away: Window{1ad85e5d u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-23 13:41:43.863  1036  1114 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7020 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-23 13:41:43.864  2035  2035 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-23 13:41:43.868  1909  1909 D ActionManagerService: notifyUserLog: 1000004
08-23 13:41:43.869  3774  4783 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-23 13:41:43.869  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,08-23 13:41:43.871  3774  3790 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-23 13:41:43.878  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-23 13:41:43.878  2035  2035 I GBoardWebViewUtils: , create_time: 1430832262123
08-23 13:41:43.878  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-23 13:41:43.878  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-23 13:41:43.878  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-23 13:41:43.878  2035  2035 I GBoardWebViewUtils: , display: false
08-23 13:41:43.878  2035  2035 I GBoardWebViewUtils: , animation: false }
08-23 13:41:43.879  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-23 13:41:43.879  2035  2035 I GBoardWebViewUtils: , create_time: 1430832262287
08-23 13:41:43.879  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-23 13:41:43.879  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-23 13:41:43.879  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-23 13:41:43.879  2035  2035 I GBoardWebViewUtils: , display: false
08-23 13:41:43.879  2035  2035 I GBoardWebViewUtils: , animation: false }
08-23 13:41:43.879  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-23 13:41:43.879  2035  2035 I GBoardWebViewUtils: , create_time: 1471602816196
08-23 13:41:43.879  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-23 13:41:43.879  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-23 13:41:43.879  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-23 13:41:43.879  2035  2035 I GBoardWebViewUtils: , display: false
08-23 13:41:43.879  2035  2035 I GBoardWebViewUtils: , animation: false }
08-23 13:41:43.884  2035  7036 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-23 13:41:43.894  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-23 13:41:43.921  7020  7020 I art     : Almond Protected OAT
,08-23 13:41:43.961  2035  2035 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-23 13:41:43.970  7008  7008 D AndroidRuntime: 
08-23 13:41:43.970  7008  7008 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-23 13:41:43.973  7008  7008 D AndroidRuntime: CheckJNI is OFF
,08-23 13:41:43.985  7020  7020 D WeatherApplication: removeAccount
08-23 13:41:43.985  7020  7020 D WeatherApplication: Account.length = 0
08-23 13:41:43.985  7020  7020 E WeatherApplication: OPERATOR:OPEN
08-23 13:41:43.988  7020  7020 D WeatherAncestor: 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 13:41:43
08-23 13:41:43.990  7020  7020 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-23 13:41:43.990  7020  7020 D Weather.Utils: 2 : All the weather widget is gone.
08-23 13:41:43.991  7020  7020 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-23 13:41:43.992  7020  7020 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-23 13:41:43.992  7020  7020 D Weather.Utils: 2 : All the weather widget is gone.
08-23 13:41:43.993  7020  7020 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 13:41:43
08-23 13:41:43.994  1036  1577 I ActivityManager: Killing 6324:com.android.defcontainer/u0a4 (adj 15): empty #17
08-23 13:41:44.030  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-23 13:41:44.035  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 13:41:44.039  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-23 13:41:44.041  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
,08-23 13:41:44.043  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-23 13:41:44.045  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-23 13:41:44.072  7008  7008 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-23 13:41:44.075  2035  2288 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-23 13:41:44.075  2035  2288 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-23 13:41:44.075  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-23 13:41:44.076  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 13:41:44.077  1036  1943 W libprocessgroup: failed to open /acct/uid_10004/pid_6324/cgroup.procs: No such file or directory
08-23 13:41:44.084  1036  1114 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-23 13:41:44.084  1036  1114 I ActivityManager: Killing 6938:com.test.thalitest/u0a118 (adj 9): stop com.test.thalitest
,08-23 13:41:44.102  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-23 13:41:44.103  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-23 13:41:44.103  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 13:41:44.107  1036  1486 D WifiService: Client connection lost with reason: 4
,08-23 13:41:44.140  2035  2035 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-23 13:41:44.197  1036  1733 W ActivityManager: Spurious death for ProcessRecord{38ca8ff6 6938:com.test.thalitest/u0a118}, curProc for 6938: null
,08-23 13:41:44.198  1036  1124 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-23 13:41:44.218  2692  2692 D [Concierge]Service: onStartCommand(). Type : 8
08-23 13:41:44.218  2692  2692 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-23 13:41:44.224  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-23 13:41:44.225  2692  2692 D [Concierge]Service: Update widget ID : 11
08-23 13:41:44.232  3774  3774 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-23 13:41:44.234  4137  4137 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-23 13:41:44.234  4137  4137 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-23 13:41:44.236  1998  1998 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-23 13:41:44.236  2493  2625 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-23 13:41:44.239  2035  2035 D [Concierge]WidgetView: change position of spinner
08-23 13:41:44.239  6435  6435 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-23 13:41:44.240  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{11772096 u0 com.lge.launcher2/.Launcher t5} time:168546
08-23 13:41:44.264  4884  4884 I art     : Explicit concurrent mark sweep GC freed 466(29KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 489us total 52.653ms
,08-23 13:41:44.269  1036  1113 W InputMethodInfo: Duplicated subtype definition found: , voice
08-23 13:41:44.273  1036  1908 V SIM_STK : Menu title from STK is T-Mobile
08-23 13:41:44.281  4784  4784 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-23 13:41:44.281  4784  4784 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
,08-23 13:41:44.281  4784  4784 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-23 13:41:44.281  4784  4784 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-23 13:41:44.281  4784  4784 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 13:41:44.281  4784  4784 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 13:41:44.281  4784  4784 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-23 13:41:44.281  4784  4784 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 13:41:44.281  4784  4784 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 13:41:44.281  4784  4784 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 13:41:44.281  4784  4784 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 13:41:44.281  4784  4784 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 13:41:44.296  1820  1820 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-23 13:41:44.299  2035  2035 I [Concierge]WidgetView: initWebView(). Time : 1471952504299
08-23 13:41:44.301  1605  1605 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-23 13:41:44.305  2692  2692 D [Concierge]Service: onStartCommand(). Type : 0
08-23 13:41:44.310  2201  2201 I ConfigService: onCreate
08-23 13:41:44.313  2201  2201 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
,08-23 13:41:44.318  1605  1656 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-23 13:41:44.318  1605  1656 D KeyguardModel: createShortcutInfo...
08-23 13:41:44.322  1820  1820 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-23 13:41:44.322  2035  2035 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 35785915
08-23 13:41:44.322  2035  2035 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-23 13:41:44.322  2035  2035 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-23 13:41:44.325  2035  2035 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3b8eb00e
08-23 13:41:44.326  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
,08-23 13:41:44.328  1605  1656 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-23 13:41:44.328  1605  1656 D KeyguardModel: createShortcutInfo...
08-23 13:41:44.331  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-23 13:41:44.331  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 13:41:44.332  1036  1577 V SIM_STK : Menu title from STK is T-Mobile
08-23 13:41:44.332  1036  1577 V SIM_STK : Menu title from STK is T-Mobile
08-23 13:41:44.332  1605  1656 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-23 13:41:44.333  1605  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 13:41:44.340  1872  1872 D SplitUIManager: split_name #11 / not available #0
08-23 13:41:44.341  1872  1872 D SplitUIService: removed split : 
08-23 13:41:44.342  1605  1656 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-23 13:41:44.344  1605  1656 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-23 13:41:44.344  1605  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 13:41:44.344  1605  1656 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-23 13:41:44.345  2201  2201 I ConfigService: onBind returning update interface
,08-23 13:41:44.346  2201  2201 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-23 13:41:44.346  2201  2201 I ConfigService: onBind returning config service
08-23 13:41:44.346  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-23 13:41:44.347  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-23 13:41:44.347  2035  2035 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.PackageUpdateReceiver
08-23 13:41:44.348  2035  2035 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-23 13:41:44.348  2201  2201 I ConfigService: onDestroy
08-23 13:41:44.349  2035  2035 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471952364861, New one : 1471952504299
08-23 13:41:44.349  2035  2035 D [Concierge]WidgetView: Unregister all receivers
08-23 13:41:44.349  2035  2035 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-23 13:41:44.349  2035  2035 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.PackageUpdateReceiver
08-23 13:41:44.350  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 13:41:44.350  1605  1656 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-23 13:41:44.350  1605  1656 D KeyguardModel: createShortcutInfo...
08-23 13:41:44.351  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-23 13:41:44.353  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-23 13:41:44.354  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-23 13:41:44.355  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-23 13:41:44.356  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-23 13:41:44.357  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 13:41:44.357  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 13:41:44.363  1605  1656 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-23 13:41:44.363  1605  1656 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-23 13:41:44.366  1605  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 13:41:44.366  1605  1656 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-23 13:41:44.367  1820  7059 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-23 13:41:44.368  1605  1656 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-23 13:41:44.368  1605  1656 D KeyguardModel: createShortcutInfo...
08-23 13:41:44.369  1605  1605 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-23 13:41:44.369  1605  1605 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-23 13:41:44.379  1036  2042 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-23 13:41:44.381  1872  1872 D SplitUIManager: split_name #11 / not available #0
08-23 13:41:44.381  1872  1872 I SplitUIService: split app #11
08-23 13:41:44.381  1605  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 13:41:44.381  1605  1656 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-23 13:41:44.382  1605  1656 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-23 13:41:44.382  1605  1656 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-23 13:41:44.383  1605  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 13:41:44.383  1605  1656 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-23 13:41:44.384  4137  4137 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-23 13:41:44.384  4137  4137 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-23 13:41:44.384  4137  4137 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-23 13:41:44.384  4137  4137 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-23 13:41:44.384  4137  4137 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-23 13:41:44.384  4137  4137 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-23 13:41:44.384  4137  4137 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-23 13:41:44.384  4137  4137 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-23 13:41:44.384  4137  4137 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-23 13:41:44.384  4137  4137 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-23 13:41:44.384  4137  4137 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-23 13:41:44.388  1605  1656 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-23 13:41:44.388  1605  1656 D KeyguardModel: createShortcutInfo...
08-23 13:41:44.398  1605  1605 D KeyguardModel: handleShortcutListChanged...
08-23 13:41:44.398  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-23 13:41:44.400  2035  2035 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-23 13:41:44.402  6203  7064 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-23 13:41:44.417  2035  2035 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-23 13:41:44.417  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-23 13:41:44.418  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 13:41:44.419  1605  1656 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-23 13:41:44.419  1605  1656 D KeyguardModel: createShortcutInfo...
08-23 13:41:44.421  1605  1656 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-23 13:41:44.421  1605  1656 D KeyguardModel: createShortcutInfo...
08-23 13:41:44.423  1605  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 13:41:44.423  1605  1656 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-23 13:41:44.424  1605  1656 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-23 13:41:44.424  1605  1656 D KeyguardModel: createShortcutInfo...
08-23 13:41:44.425  1605  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 13:41:44.425  1605  1656 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-23 13:41:44.425  1036  1381 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-23 13:41:44.428  1605  1656 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-23 13:41:44.428  1605  1656 D KeyguardModel: createShortcutInfo...
,08-23 13:41:44.429  1820  7066 I PeopleContactsSync: CP2 sync disabled
08-23 13:41:44.429  1605  1656 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 13:41:44.429  1605  1656 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-23 13:41:44.430  1605  1656 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-23 13:41:44.430  1605  1656 D KeyguardModel: createShortcutInfo...
08-23 13:41:44.440  2035  2035 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2c8d71b0 time:168747
08-23 13:41:44.442  1036  1036 I art     : Explicit concurrent mark sweep GC freed 28828(1679KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/65MB, paused 4.960ms total 217.771ms
,08-23 13:41:44.449  1036  2016 V SIM_STK : Menu title from STK is T-Mobile
08-23 13:41:44.458  3221  7067 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-23 13:41:44.458   339   428 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-23 13:41:44.461  1820  7065 W GmsApplication: Using Auth Proxy for data requests.
08-23 13:41:44.463  1036  1036 D administrator: Handling package changes for user 0
08-23 13:41:44.468  1820  7065 W GmsApplication: Using Auth Proxy for data requests.
08-23 13:41:44.469  1605  1605 D KeyguardModel: handleShortcutListChanged...
08-23 13:41:44.469  1605  1605 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-23 13:41:44.475  6541  6541 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-23 13:41:44.483  1820  5077 I Icing   : doRemovePackageData com.test.thalitest
08-23 13:41:44.518  1036  1036 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-23 13:41:44.519  1036  1036 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-23 13:41:44.519  6586  6586 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-23 13:41:44.519  1036  1036 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-23 13:41:44.520  2035  2035 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-23 13:41:44.523  1036  1580 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-23 13:41:44.525  2335  7070 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-23 13:41:44.535  1998  1998 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-23 13:41:44.535  1998  1998 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-23 13:41:44.536  1998  1998 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-23 13:41:44.541  6435  6435 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-23 13:41:44.572  1036  1888 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=7072 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-23 13:41:44.619  2035  2035 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-23 13:41:44.635  1036  1124 I art     : Explicit concurrent mark sweep GC freed 10038(758KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 1.895ms total 146.212ms
,08-23 13:41:44.673  2035  2950 I GBoardtInterface: onReloaded()
,08-23 13:41:44.675  2035  2035 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-23 13:41:44.676  3774  4005 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-23 13:41:44.678  3774  3789 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-23 13:41:44.680  7072  7072 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-23 13:41:44.681  7072  7072 W LG Account v2.2: No ProfileInfo entries
08-23 13:41:44.681  7072  7072 I LG Account v2.2: isEnabled: false
08-23 13:41:44.681  7072  7072 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-23 13:41:44.681  7072  7072 I Feature : [Lifetracker]Country: EU
08-23 13:41:44.681  7072  7072 I Feature : [Lifetracker]Operator: OPEN
08-23 13:41:44.681  7072  7072 I Feature : [Lifetracker]Ranking support: false
08-23 13:41:44.681  7072  7072 I Feature : [Lifetracker]Comfort support: false
08-23 13:41:44.681  7072  7072 I Feature : [Lifetracker]Accessory: true
08-23 13:41:44.681  7072  7072 I Feature : [Lifetracker]Health device: true
08-23 13:41:44.681  7072  7072 I Feature : [Lifetracker]Extra Pedometer: false
08-23 13:41:44.681  7072  7072 I Feature : [Lifetracker]Blood glucose device: false
08-23 13:41:44.681  7072  7072 I Feature : [Lifetracker]Device Number: 3
08-23 13:41:44.682  7072  7072 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-23 13:41:44.710  7008  7008 D AndroidRuntime: Shutting down VM
08-23 13:41:44.710  1036  1771 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=7092 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-23 13:41:44.713  1909  1909 D ActionManagerService: notifyUserLog: 1000001
08-23 13:41:44.714  3774  4783 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-23 13:41:44.714  3774  4783 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-23 13:41:44.716  1909  1909 D ActionManagerService: notifyUserLog: 1000001
08-23 13:41:44.717  3774  4783 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-23 13:41:44.717  3774  4783 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-23 13:41:44.717  3774  4783 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-23 13:41:44.717  3774  4783 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-23 13:41:44.718  3774  4005 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-23 13:41:44.720  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-23 13:41:44.720  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-23 13:41:44.721  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-23 13:41:44.721  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-23 13:41:44.724  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-23 13:41:44.724  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-23 13:41:44.741  7092  7092 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 13:41:44.742  7092  7092 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-23 13:41:44.742  7092  7092 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-23 13:41:44.742  7092  7092 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-23 13:41:44.743  7092  7092 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-23 13:41:44.744  7092  7092 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-23 13:41:44.744  1036  1113 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 13:41:44.749  1036  1113 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-23 13:41:44.754  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-23 13:41:44.815  7092  7092 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-23 13:41:44.821  7092  7092 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-23 13:41:44.821  7092  7092 D HideNavigationAppsReceiver: replacing : false
,08-23 13:41:44.823  7092  7092 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-23 13:41:44.825  7092  7092 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-23 13:41:44.825  7092  7092 D ButtonCombinationReceiver: replacing : false
,08-23 13:41:44.832  1036  2042 I ActivityManager: Killing 6479:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-23 13:41:44.894  1036  1943 W libprocessgroup: failed to open /acct/uid_10008/pid_6479/cgroup.procs: No such file or directory
,08-23 13:41:44.898  4884  7109 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-23 13:41:44.917  1036  1051 V SIM_STK : Menu title from STK is T-Mobile
,08-23 13:41:44.932  1036  1577 I ActivityManager: Start proc com.android.keychain for broadcast com.android.keychain/.KeyChainBroadcastReceiver: pid=7110 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-23 13:41:44.961  1036  1124 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=7127 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-23 13:41:44.984  2035  2950 I GBoardtInterface: exportHTML()
,08-23 13:41:44.986  7110  7110 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.keychain.KeyChainBroadcastReceiver.onReceive:12 android.app.ActivityThread.handleReceiver:2586 
,08-23 13:41:44.998  6729  6729 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-23 13:41:44.998  6729  6729 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-23 13:41:44.998  6729  6729 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-23 13:41:44.998  6729  6729 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-23 13:41:44.998  6729  6729 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-23 13:41:44.998  6729  6729 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
,08-23 13:41:45.010  5511  5511 D [BNRAppListMgrReceiver]: android.intent.action.PACKAGE_REMOVED : com.test.thalitest
08-23 13:41:45.015  7092  7092 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-23 13:41:45.016  2035  2950 I GBoardtInterface: exportHTML()
08-23 13:41:45.019  4884  7109 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 121 ms] updated apps [took 121 ms] 
08-23 13:41:45.044  2035  2950 I GBoardtInterface: exportHTML()
,08-23 13:41:45.054  1036  1051 I ActivityManager: Start proc com.android.documentsui for broadcast com.android.documentsui/.PackageReceiver: pid=7150 uid=10060 gids={50060, 9997, 1028, 4002} abi=armeabi-v7a
08-23 13:41:45.058  1036  1051 I ActivityManager: Killing 6790:com.lge.eula/1000 (adj 15): empty #17
,08-23 13:41:45.174  1036  1051 I ActivityManager: Killing 2136:com.lge.music/u0a34 (adj 15): empty #17

```
