#### Test 82337235c72b2f9_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-23 13:55:02.577  2162  2162 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Time is up to exit
08-23 13:55:02.584  2162  2162 I CloudHub: [CLIENT][CloudHubClientFactory$1|onFinish] Scheduler destroyed
,08-23 13:55:23.272  6785  6785 D AndroidRuntime: 
08-23 13:55:23.272  6785  6785 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-23 13:55:23.277  6785  6785 D AndroidRuntime: CheckJNI is OFF
08-23 13:55:23.479  6785  6785 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-23 13:55:23.490  1038  1564 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-23 13:55:23.505  1929  2689 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-23 13:55:23.511  1038  1564 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-23 13:55:23.512  1038  1564 D ActivityManager: setTaskToReturnTo : TaskRecord{3fd9716e #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-23 13:55:23.512  1038  1564 D ActivityManager: setTaskToReturnTo : TaskRecord{3fd9716e #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-23 13:55:23.514  1038  1564 D WindowStateEx: AppWindowTokenEx init.. 
08-23 13:55:23.515   350   403 E GBMv2   : DFP En is all cleared set to be enabled
08-23 13:55:23.543  1038  1564 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6800 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-23 13:55:23.546  6785  6785 D AndroidRuntime: Shutting down VM
08-23 13:55:23.600  1929  1944 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-23 13:55:23.600  1929  1944 D SplitWindowPolicy: topRunningActivity=ActivityInfo{12ee687d co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-23 13:55:23.602  1929  1945 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-23 13:55:23.602  1929  1945 D SplitWindowPolicy: topRunningActivity=ActivityInfo{106c372 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-23 13:55:23.648  6800  6800 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-23 13:55:23.720  6800  6800 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-23 13:55:23.734  6800  6800 I LibraryLoader: Loading: webviewchromium
,08-23 13:55:23.738  6800  6800 I LibraryLoader: Time to load native libraries: 8 ms (timestamps 3760-3768)
08-23 13:55:23.738  6800  6800 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 13:55:23.770  6800  6800 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {22809433}
08-23 13:55:23.771  6800  6800 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 13:55:23.771  6800  6800 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-23 13:55:23.781  6800  6800 I BrowserStartupController: Initializing chromium process, renderers=0
08-23 13:55:23.782  6800  6800 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 13:55:23.797  6800  6800 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-23 13:55:23.797  6800  6800 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-23 13:55:23.798  6800  6800 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-23 13:55:23.800   330  1385 V AudioPolicyService: registerClient() client 0xb57f66a0, uid 10118
08-23 13:55:23.807  1038  1120 D BluetoothManagerService: Message: 20
08-23 13:55:23.808  1038  1120 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@26b2d288:true
08-23 13:55:23.817  6800  6800 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-23 13:55:23.817  6800  6800 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-23 13:55:23.817  6800  6800 I Adreno-EGL: Build Date: 12/12/14 금
08-23 13:55:23.817  6800  6800 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-23 13:55:23.817  6800  6800 I Adreno-EGL: Remote Branch: 
08-23 13:55:23.817  6800  6800 I Adreno-EGL: Local Patches: 
08-23 13:55:23.817  6800  6800 I Adreno-EGL: Reconstruct Branch: 
,08-23 13:55:23.913  6800  6844 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-23 13:55:23.915  6800  6800 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-23 13:55:23.933  6800  6800 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 13:55:23.938  6800  6800 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-23 13:55:23.941  6800  6800 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-23 13:55:23.945  6800  6800 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-23 13:55:23.945  6800  6800 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-23 13:55:23.959  6800  6800 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-23 13:55:23.965  6800  6800 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 13:55:23.965  6800  6800 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 13:55:24.000  6800  6860 D OpenGLRenderer: Render dirty regions requested: true
08-23 13:55:24.001  6800  6860 I OpenGLRenderer: Initialized EGL, version 1.4
08-23 13:55:24.006  6800  6860 D OpenGLRenderer: Enabling debug mode 0
,08-23 13:55:24.015  6800  6800 D Atlas   : Validating map...
08-23 13:55:24.022  1038  1060 D SplitWindow: check instance of lgWin Window{adadc82 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-23 13:55:24.058  6800  6855 D LgDataFeature: LgDataFeature() Constructor: none
08-23 13:55:24.058  6800  6855 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-23 13:55:24.139  1038  1121 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +543ms (total +624ms)
08-23 13:55:24.140  1038  1121 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1939000f u0 com.test.thalitest/.MainActivity t6} time:164170
08-23 13:55:24.142  6800  6800 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@3aca49e time:164172
08-23 13:55:24.246  6800  6800 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 13:55:24.280  6800  6800 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-23 13:55:24.280  6800  6800 I chromium: 
,08-23 13:55:24.315  6800  6855 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-23 13:55:24.315  6800  6855 I chromium: 
,08-23 13:55:24.465  6800  6874 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435153408
,08-23 13:55:24.480  6800  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 13:55:24.480  6800  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 13:55:24.480  6800  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 13:55:24.480  6800  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 13:55:24.480  6800  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-23 13:55:24.481  6800  6874 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@380fe702 added. We now have 1 listener(s)
,08-23 13:55:24.486  1038  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 13:55:24.489  6800  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-23 13:55:24.491  6800  6874 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 13:55:24.493  6800  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 13:55:24.493  6800  6874 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 13:55:24.503  6800  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 13:55:24.503  6800  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 13:55:24.503  6800  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 13:55:24.503  6800  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-23 13:55:24.503  6800  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 13:55:24.503  6800  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 13:55:24.503  6800  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 13:55:24.503  6800  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 13:55:24.503  6800  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 13:55:24.503  6800  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 13:55:24.503  6800  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 13:55:24.503  6800  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 13:55:24.503  6800  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 13:55:24.503  6800  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-23 13:55:24.503  6800  6874 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e1f449 added. We now have 1 listener(s)
,08-23 13:55:24.504  6800  6874 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 13:55:24.510  1038  1466 D WifiService: New client listening to asynchronous messages
08-23 13:55:24.514  6800  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 13:55:24.514  6800  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-23 13:55:24.517  6800  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 13:55:24.517  6800  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 13:55:24.517  6800  6874 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-23 13:55:24.521  6800  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 13:55:24.522  1038  1911 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 13:55:24.524  6800  6874 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-23 13:55:24.534  6800  6874 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-23 13:55:24.535  6800  6874 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 13:55:24.535  6800  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 13:55:24.535  6800  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 13:55:24.535  6800  6874 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 13:55:24.535  6800  6874 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 13:55:24.535  6800  6874 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 13:55:24.535  6800  6874 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 13:55:24.535  6800  6874 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 13:55:24.535  6800  6874 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 13:55:24.535  6800  6874 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-23 13:55:24.540  6800  6800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 13:55:24.540  6800  6874 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-23 13:55:24.541  6800  6800 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 13:55:24.575  6800  6800 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 13:55:24.944   350   405 E GBMv2   : DFP En is all cleared set to be enabled
08-23 13:55:24.944   350   405 E GBMv2   : Set value is all cleared set the max
08-23 13:55:24.944   350   405 I GBMv2   : DFP Enabled. Ignore VFP set
,08-23 13:55:25.686  6800  6878 W jxcore-log: Initializing JXcore engine
08-23 13:55:25.686  6800  6878 W jxcore-log: JXcore engine is ready
,08-23 13:55:25.757  6878  6878 W Thread-807: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8472]" dev="sockfs" ino=8472 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-23 13:55:25.757  6878  6878 W Thread-807: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-23 13:55:25.757  6878  6878 W Thread-807: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9806]" dev="sockfs" ino=9806 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-23 13:55:25.757  6878  6878 W Thread-807: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-23 13:55:25.757  6878  6878 W Thread-807: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[33802]" dev="sockfs" ino=33802 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-23 13:55:25.792  6800  6878 W jxcore-log: Starting JXcore engine
,08-23 13:55:25.951  6800  6878 W jxcore-log: Platform android
08-23 13:55:25.951  6800  6878 W jxcore-log: 
08-23 13:55:25.951  6800  6878 W jxcore-log: Process ARCH arm
08-23 13:55:25.951  6800  6878 W jxcore-log: 
,08-23 13:55:26.358  6800  6878 I jxcore-log: JXcore Cordova bridge is ready!
08-23 13:55:26.358  6800  6878 I jxcore-log: 
,08-23 13:55:26.358  6800  6878 W jxcore-log: JXcore engine is started
,08-23 13:55:26.369  6800  6874 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-23 13:55:26.372  6800  6800 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 13:55:26.397  6800  6878 E jxcore  : Error!: missing name after . operator
08-23 13:55:26.397  6800  6878 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"591","_columnNumber":"9","_msg":"    at $w.prototype._compile@module.js:591:9"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:260:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,08-23 13:55:26.404  6800  6800 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "missing name after . operator\nSyntaxError: missing name after . operator\n    at $w.prototype._compile@module.js:591:9\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at internal_methods.loadMainFile@main.js:260:5\n    at JXMobile.executeJSON@main.js:279:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (56)
08-23 13:55:26.405  6800  6800 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
08-23 13:55:26.411  1038  1638 I ActivityManager: Killing 6182:com.android.providers.calendar/u0a14 (adj 15): empty #17
,08-23 13:55:26.469  1038  2019 W libprocessgroup: failed to open /acct/uid_10014/pid_6182/cgroup.procs: No such file or directory
,08-23 13:55:26.472  6800  6874 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 66ms. Plugin should use CordovaInterface.getThreadPool().
08-23 13:55:26.491  6800  6800 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
,08-23 13:55:26.501  6800  6800 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-23 13:55:26.504  6800  6800 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 13:55:26.504  6800  6800 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 13:55:26.505  6800  6800 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 13:55:26.505  6800  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 13:55:26.506  6800  6800 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@380fe702 removed from the list
08-23 13:55:26.506  6800  6800 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 13:55:26.507  6800  6800 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3e1f449 removed from the list
08-23 13:55:26.507  6800  6800 D io.jxcore.node.ConnectivityMonitor: stop
08-23 13:55:26.507  6800  6800 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
08-23 13:55:26.532   350   403 E GBMv2   : DFP En is all cleared set to be enabled
,08-23 13:55:26.540  1929  2689 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-23 13:55:26.541  1929  2689 D SplitWindowPolicy: topRunningActivity=ActivityInfo{1b9a23c3 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-23 13:55:26.544  1929  1944 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
,08-23 13:55:26.546  1929  1944 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2358d440 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-23 13:55:26.547  2021  2021 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-23 13:55:26.549  2021  2021 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
08-23 13:55:26.554  2021  2021 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
,08-23 13:55:26.558  2021  2069 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=1ms
08-23 13:55:26.565  1893  1893 D ActionManagerService: notifyUserLog: 1000003
08-23 13:55:26.565  2021  2021 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-23 13:55:26.567  6800  6800 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-23 13:55:26.569  2021  2021 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-23 13:55:26.569  3791  4936 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
,08-23 13:55:26.572  2021  2021 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-23 13:55:26.613  1038  1116 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6892 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 13:55:26.614  2021  2021 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-23 13:55:26.615  6800  6800 W ScreenOrientationListener: Removing an inexistent observer!
08-23 13:55:26.618  1893  1893 D ActionManagerService: notifyUserLog: 1000004
08-23 13:55:26.618  2021  2021 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-23 13:55:26.618  3791  4936 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-23 13:55:26.619  3791  4932 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-23 13:55:26.623  2021  2021 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-23 13:55:26.623  2021  2021 I GBoardWebViewUtils: , create_time: 1430832262123
08-23 13:55:26.623  2021  2021 I GBoardWebViewUtils: , expire_time: 0
08-23 13:55:26.623  2021  2021 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-23 13:55:26.623  2021  2021 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-23 13:55:26.623  2021  2021 I GBoardWebViewUtils: , display: false
08-23 13:55:26.623  2021  2021 I GBoardWebViewUtils: , animation: false }
08-23 13:55:26.623  2021  2021 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-23 13:55:26.623  2021  2021 I GBoardWebViewUtils: , create_time: 1430832262287
08-23 13:55:26.623  2021  2021 I GBoardWebViewUtils: , expire_time: 0
08-23 13:55:26.623  2021  2021 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-23 13:55:26.623  2021  2021 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-23 13:55:26.623  2021  2021 I GBoardWebViewUtils: , display: false
08-23 13:55:26.623  2021  2021 I GBoardWebViewUtils: , animation: false }
08-23 13:55:26.623  2021  2021 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-23 13:55:26.623  2021  2021 I GBoardWebViewUtils: , create_time: 1471602816196
08-23 13:55:26.623  2021  2021 I GBoardWebViewUtils: , expire_time: 0
08-23 13:55:26.623  2021  2021 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-23 13:55:26.623  2021  2021 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-23 13:55:26.623  2021  2021 I GBoardWebViewUtils: , display: false
08-23 13:55:26.623  2021  2021 I GBoardWebViewUtils: , animation: false }
08-23 13:55:26.627  2021  6908 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-23 13:55:26.668  6892  6892 I art     : Almond Protected OAT
,08-23 13:55:26.677  2021  2021 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-23 13:55:26.684  1038  2032 D InputDispatcher: Window went away: Window{adadc82 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-23 13:55:26.700  6879  6879 D AndroidRuntime: 
08-23 13:55:26.700  6879  6879 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-23 13:55:26.702  6879  6879 D AndroidRuntime: CheckJNI is OFF
,08-23 13:55:26.757  6892  6892 D WeatherApplication: removeAccount
,08-23 13:55:26.759  6892  6892 D WeatherApplication: Account.length = 0
08-23 13:55:26.759  6892  6892 E WeatherApplication: OPERATOR:OPEN
,08-23 13:55:26.762  6892  6892 D WeatherAncestor: 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 13:55:26
08-23 13:55:26.764  6892  6892 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-23 13:55:26.764  6892  6892 D Weather.Utils: 2 : All the weather widget is gone.
08-23 13:55:26.765  6892  6892 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-23 13:55:26.766  6892  6892 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-23 13:55:26.766  6892  6892 D Weather.Utils: 2 : All the weather widget is gone.
08-23 13:55:26.766  6892  6892 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 13:55:26
08-23 13:55:26.767  1038  1983 I ActivityManager: Killing 6245:com.android.defcontainer/u0a4 (adj 15): empty #17
08-23 13:55:26.833  6879  6879 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-23 13:55:26.861  1038  1061 W libprocessgroup: failed to open /acct/uid_10004/pid_6245/cgroup.procs: No such file or directory
,08-23 13:55:26.867  1038  1116 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-23 13:55:26.868  1038  1116 I ActivityManager: Killing 6800:com.test.thalitest/u0a118 (adj 9): stop com.test.thalitest
,08-23 13:55:26.869  2021  2021 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-23 13:55:26.916  1038  1466 D WifiService: Client connection lost with reason: 4
,08-23 13:55:26.966  2021  2021 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-23 13:55:26.970  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 13:55:26.973  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-23 13:55:26.974  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-23 13:55:26.976  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-23 13:55:26.977  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-23 13:55:27.001  2021  2021 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
,08-23 13:55:27.002  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 13:55:27.004  2021  2119 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-23 13:55:27.004  2021  2119 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-23 13:55:27.041  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-23 13:55:27.043  2021  2021 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-23 13:55:27.043  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 13:55:27.053  2021  2021 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-23 13:55:27.084  1038  2019 W ActivityManager: Spurious death for ProcessRecord{35fdefe7 6800:com.test.thalitest/u0a118}, curProc for 6800: null
,08-23 13:55:27.084  1038  1126 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-23 13:55:27.120  2581  2581 D [Concierge]Service: onStartCommand(). Type : 8
08-23 13:55:27.120  2581  2581 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-23 13:55:27.125  2021  2021 D [Concierge]WidgetView: change position of spinner
08-23 13:55:27.127  2581  2581 D [Concierge]Service: Update widget ID : 11
08-23 13:55:27.128  2021  2021 I [Concierge]WidgetView: initWebView(). Time : 1471953327128
08-23 13:55:27.131  1038  1121 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{b1a2a3b u0 com.lge.launcher2/.Launcher t5} time:167161
,08-23 13:55:27.134  2581  2581 D [Concierge]Service: onStartCommand(). Type : 0
08-23 13:55:27.138  1589  1589 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-23 13:55:27.145  4269  4269 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-23 13:55:27.145  4269  4269 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-23 13:55:27.146  3791  3791 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-23 13:55:27.146  2448  2659 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-23 13:55:27.146  1984  1984 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-23 13:55:27.149  4909  4909 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-23 13:55:27.149  4909  4909 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-23 13:55:27.149  4909  4909 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-23 13:55:27.149  4909  4909 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-23 13:55:27.149  4909  4909 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 13:55:27.149  4909  4909 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 13:55:27.149  4909  4909 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-23 13:55:27.149  4909  4909 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 13:55:27.149  4909  4909 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 13:55:27.149  4909  4909 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 13:55:27.149  4909  4909 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 13:55:27.149  4909  4909 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 13:55:27.162  1038  1366 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-23 13:55:27.163  5030  5030 I art     : Explicit concurrent mark sweep GC freed 464(29KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 424us total 66.889ms
,08-23 13:55:27.183  1038  1115 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-23 13:55:27.187  1038  1706 V SIM_STK : Menu title from STK is T-Mobile
08-23 13:55:27.195  1589  1589 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-23 13:55:27.203  1589  1655 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-23 13:55:27.203  1589  1655 D KeyguardModel: createShortcutInfo...
08-23 13:55:27.207  1589  1655 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-23 13:55:27.207  1589  1655 D KeyguardModel: createShortcutInfo...
,08-23 13:55:27.213  1589  1655 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-23 13:55:27.214  1589  1655 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 13:55:27.214  1589  1655 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-23 13:55:27.215  6377  6377 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-23 13:55:27.215  1589  1655 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-23 13:55:27.217  1589  1589 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
,08-23 13:55:27.220  1589  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 13:55:27.220  1589  1655 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-23 13:55:27.222  1589  1655 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-23 13:55:27.222  1589  1655 D KeyguardModel: createShortcutInfo...
08-23 13:55:27.226  1589  1655 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-23 13:55:27.226  1589  1655 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-23 13:55:27.227  1589  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 13:55:27.227  1589  1655 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-23 13:55:27.231  1589  1655 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-23 13:55:27.231  1589  1655 D KeyguardModel: createShortcutInfo...
,08-23 13:55:27.233  2021  2021 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 652086726
08-23 13:55:27.234  2021  2021 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-23 13:55:27.234  1589  1589 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-23 13:55:27.234  2021  2021 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-23 13:55:27.237  2021  2021 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2f8dc679
08-23 13:55:27.237  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-23 13:55:27.237  1807  1807 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-23 13:55:27.240  2021  2021 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-23 13:55:27.240  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 13:55:27.243  1589  1655 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 13:55:27.243  1589  1655 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-23 13:55:27.243  1589  1655 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-23 13:55:27.243  1589  1655 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-23 13:55:27.247  1038  1946 V SIM_STK : Menu title from STK is T-Mobile
08-23 13:55:27.247  1038  1946 V SIM_STK : Menu title from STK is T-Mobile
08-23 13:55:27.248  2123  2123 I ConfigService: onCreate
08-23 13:55:27.248  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-23 13:55:27.248  2123  2123 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-23 13:55:27.248  2021  2021 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-23 13:55:27.249  2021  2021 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.PackageUpdateReceiver
08-23 13:55:27.255  2123  2123 I ConfigService: onBind returning update interface
,08-23 13:55:27.256  2123  2123 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
,08-23 13:55:27.256  2123  2123 I ConfigService: onBind returning config service
08-23 13:55:27.257  2021  2021 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-23 13:55:27.257  1807  1807 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-23 13:55:27.257  2021  2021 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471953187893, New one : 1471953327128
08-23 13:55:27.257  2021  2021 D [Concierge]WidgetView: Unregister all receivers
08-23 13:55:27.257  2021  2021 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-23 13:55:27.257  2021  2021 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.PackageUpdateReceiver
08-23 13:55:27.257  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 13:55:27.259  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-23 13:55:27.260  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-23 13:55:27.261  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-23 13:55:27.262  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-23 13:55:27.263  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-23 13:55:27.264  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 13:55:27.264  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 13:55:27.265  1589  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 13:55:27.265  1589  1655 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-23 13:55:27.268  1589  1655 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-23 13:55:27.268  1589  1655 D KeyguardModel: createShortcutInfo...
,08-23 13:55:27.273  1589  1589 D KeyguardModel: handleShortcutListChanged...
08-23 13:55:27.273  1589  1589 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-23 13:55:27.283  1589  1655 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-23 13:55:27.283  1589  1655 D KeyguardModel: createShortcutInfo...
,08-23 13:55:27.288  1807  1807 I ConfigFetchService: service connected
08-23 13:55:27.288  1807  1807 I ConfigClient: service connected
08-23 13:55:27.291  2123  2123 I ConfigService: onDestroy
08-23 13:55:27.293  1589  1655 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-23 13:55:27.293  1589  1655 D KeyguardModel: createShortcutInfo...
08-23 13:55:27.294  1589  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 13:55:27.294  1589  1655 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-23 13:55:27.294  1859  1859 D SplitUIManager: split_name #11 / not available #0
08-23 13:55:27.295  1859  1859 D SplitUIService: removed split : 
08-23 13:55:27.301  1038  1638 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-23 13:55:27.302  4269  4269 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-23 13:55:27.302  4269  4269 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-23 13:55:27.302  4269  4269 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-23 13:55:27.302  4269  4269 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-23 13:55:27.302  4269  4269 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-23 13:55:27.302  4269  4269 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-23 13:55:27.302  4269  4269 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-23 13:55:27.302  4269  4269 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-23 13:55:27.302  4269  4269 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-23 13:55:27.302  4269  4269 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-23 13:55:27.302  4269  4269 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-23 13:55:27.303  1589  1655 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-23 13:55:27.303  1589  1655 D KeyguardModel: createShortcutInfo...
08-23 13:55:27.304  1807  6932 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-23 13:55:27.312  1589  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 13:55:27.312  1589  1655 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-23 13:55:27.312  1038  1038 I art     : Explicit concurrent mark sweep GC freed 27946(1726KB) AllocSpace objects, 3(48KB) LOS objects, 33% free, 43MB/64MB, paused 3.753ms total 198.420ms
08-23 13:55:27.317  1038  1126 I art     : WaitForGcToComplete blocked for 52.859ms for cause Explicit
08-23 13:55:27.319  2021  2021 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-23 13:55:27.329  2021  2021 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-23 13:55:27.329  2021  2021 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
,08-23 13:55:27.331  1589  1655 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-23 13:55:27.331  1589  1655 D KeyguardModel: createShortcutInfo...
08-23 13:55:27.331  2021  2021 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-23 13:55:27.332  2021  2021 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 13:55:27.350  1038  1061 V SIM_STK : Menu title from STK is T-Mobile
,08-23 13:55:27.365  1589  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 13:55:27.365  1589  1655 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
,08-23 13:55:27.367  2021  2021 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@2acaf7e3 time:167397
08-23 13:55:27.369  1589  1655 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-23 13:55:27.369  1589  1655 D KeyguardModel: createShortcutInfo...
08-23 13:55:27.372  2021  2037 I art     : Background partial concurrent mark sweep GC freed 17932(1030KB) AllocSpace objects, 21(21MB) LOS objects, 33% free, 63MB/95MB, paused 1.226ms total 133.605ms
08-23 13:55:27.375  1589  1589 D KeyguardModel: handleShortcutListChanged...
08-23 13:55:27.375  1589  1589 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-23 13:55:27.382  1038  1038 D administrator: Handling package changes for user 0
,08-23 13:55:27.397  1859  1859 D SplitUIManager: split_name #11 / not available #0
08-23 13:55:27.398  1859  1859 I SplitUIService: split app #11
,08-23 13:55:27.412   340   427 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-23 13:55:27.413  3252  6938 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-23 13:55:27.418  5846  6940 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-23 13:55:27.432  1807  6941 I PeopleContactsSync: CP2 sync disabled
,08-23 13:55:27.442  1807  6939 W GmsApplication: Using Auth Proxy for data requests.
08-23 13:55:27.451  1807  6939 W GmsApplication: Using Auth Proxy for data requests.
,08-23 13:55:27.463  1807  5174 I Icing   : doRemovePackageData com.test.thalitest
,08-23 13:55:27.466  6473  6473 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
08-23 13:55:27.476  1038  1038 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-23 13:55:27.477  1038  1038 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-23 13:55:27.477  1038  1038 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-23 13:55:27.482  1038  1565 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-23 13:55:27.488  6498  6498 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-23 13:55:27.494  2352  6944 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-23 13:55:27.514  1984  1984 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-23 13:55:27.514  1984  1984 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-23 13:55:27.515  1984  1984 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
,08-23 13:55:27.522  6377  6377 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
,08-23 13:55:27.524  2021  2021 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-23 13:55:27.550  1038  2019 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6946 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-23 13:55:27.569  2021  2850 I GBoardtInterface: onReloaded()
,08-23 13:55:27.572  2021  2021 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-23 13:55:27.577  3791  3808 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-23 13:55:27.579  3791  4932 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-23 13:55:27.582  1038  1115 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 13:55:27.586  1893  1893 D ActionManagerService: notifyUserLog: 1000001
08-23 13:55:27.589  1038  1115 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-23 13:55:27.591  3791  4936 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-23 13:55:27.591  3791  4936 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-23 13:55:27.591  1893  1893 D ActionManagerService: notifyUserLog: 1000001
08-23 13:55:27.591  3791  4932 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
,08-23 13:55:27.593  2021  2021 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-23 13:55:27.593  2021  2021 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-23 13:55:27.594  3791  4936 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-23 13:55:27.594  3791  4936 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-23 13:55:27.594  3791  4936 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-23 13:55:27.594  3791  4936 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-23 13:55:27.595  2021  2021 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-23 13:55:27.595  2021  2021 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-23 13:55:27.597  2021  2021 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-23 13:55:27.597  2021  2021 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-23 13:55:27.601  2021  2021 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-23 13:55:27.618  1038  1126 I art     : Explicit concurrent mark sweep GC freed 11320(703KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/64MB, paused 2.023ms total 295.373ms
,08-23 13:55:27.638  6946  6946 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-23 13:55:27.638  6946  6946 W LG Account v2.2: No ProfileInfo entries
08-23 13:55:27.638  6946  6946 I LG Account v2.2: isEnabled: false
08-23 13:55:27.638  6946  6946 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-23 13:55:27.638  6946  6946 I Feature : [Lifetracker]Country: EU
08-23 13:55:27.638  6946  6946 I Feature : [Lifetracker]Operator: OPEN
08-23 13:55:27.638  6946  6946 I Feature : [Lifetracker]Ranking support: false
08-23 13:55:27.638  6946  6946 I Feature : [Lifetracker]Comfort support: false
08-23 13:55:27.638  6946  6946 I Feature : [Lifetracker]Accessory: true
08-23 13:55:27.638  6946  6946 I Feature : [Lifetracker]Health device: true
08-23 13:55:27.638  6946  6946 I Feature : [Lifetracker]Extra Pedometer: false
08-23 13:55:27.638  6946  6946 I Feature : [Lifetracker]Blood glucose device: false
08-23 13:55:27.638  6946  6946 I Feature : [Lifetracker]Device Number: 3
08-23 13:55:27.639  6946  6946 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
,08-23 13:55:27.666  1038  1060 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6966 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-23 13:55:27.695  6966  6966 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-23 13:55:27.695  6966  6966 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-23 13:55:27.696  6966  6966 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-23 13:55:27.696  6966  6966 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-23 13:55:27.696  6966  6966 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-23 13:55:27.697  6966  6966 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-23 13:55:27.699  6879  6879 D AndroidRuntime: Shutting down VM
,08-23 13:55:27.723  1038  1126 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6983 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
,08-23 13:55:27.764  1038  1060 I ActivityManager: Killing 6439:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-23 13:55:27.830  1038  1983 W libprocessgroup: failed to open /acct/uid_10008/pid_6439/cgroup.procs: No such file or directory
,08-23 13:55:27.867  6966  6966 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-23 13:55:27.874  6966  6966 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
,08-23 13:55:27.874  6966  6966 D HideNavigationAppsReceiver: replacing : false
08-23 13:55:27.876  6966  6966 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-23 13:55:27.877  6966  6966 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-23 13:55:27.877  6966  6966 D ButtonCombinationReceiver: replacing : false
,08-23 13:55:27.883  1038  1061 I ActivityManager: Killing 6588:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-23 13:55:27.898  2021  2850 I GBoardtInterface: exportHTML()
,08-23 13:55:27.924  2021  2850 I GBoardtInterface: exportHTML()
,08-23 13:55:27.944   350   405 E GBMv2   : DFP En is all cleared set to be enabled
08-23 13:55:27.944   350   405 E GBMv2   : Set value is all cleared set the max
,08-23 13:55:27.944   350   405 I GBMv2   : DFP Enabled. Ignore VFP set
08-23 13:55:27.947  2021  2850 I GBoardtInterface: exportHTML()
08-23 13:55:27.950  1038  1983 W libprocessgroup: failed to open /acct/uid_10061/pid_6588/cgroup.procs: No such file or directory
08-23 13:55:27.954  5030  7001 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-23 13:55:27.985  1038  2019 V SIM_STK : Menu title from STK is T-Mobile
08-23 13:55:27.985  1038  1946 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=7003 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 13:55:27.993  5030  7001 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
--------- beginning of crash
08-23 13:55:27.996  5030  7001 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-23 13:55:27.996  5030  7001 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 5030
08-23 13:55:27.996  5030  7001 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 13:55:27.996  5030  7001 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 13:55:27.996  5030  7001 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-23 13:55:27.996  5030  7001 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-23 13:55:27.996  5030  7001 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-23 13:55:27.996  5030  7001 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-23 13:55:27.996  5030  7001 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-23 13:55:27.996  5030  7001 E AndroidRuntime: 	at csx.d(PG:186)
08-23 13:55:27.996  5030  7001 E AndroidRuntime: 	at cun.g(PG:594)
08-23 13:55:27.996  5030  7001 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
08-23 13:55:27.996  5030  7001 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
08-23 13:55:27.996  5030  7001 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1349)
08-23 13:55:27.996  5030  7001 E AndroidRuntime: 	at cuw.Tg(PG:368)
08-23 13:55:27.996  5030  7001 E AndroidRuntime: 	at cuy.ub(PG:301)
08-23 13:55:27.996  5030  7001 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
08-23 13:55:27.996  5030  7001 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
08-23 13:55:27.996  5030  7001 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 13:55:27.996  5030  7001 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:55:27.996  5030  7001 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-23 13:55:27.996  5030  7001 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 13:55:27.999  1038  7020 E DropBoxManagerService: Can't write: system_app_crash
08-23 13:55:27.999  1038  7020 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop113.tmp: open failed: EROFS (Read-only file system)
08-23 13:55:27.999  1038  7020 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 13:55:27.999  1038  7020 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 13:55:27.999  1038  7020 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 13:55:27.999  1038  7020 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 13:55:27.999  1038  7020 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-23 13:55:27.999  1038  7020 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-23 13:55:27.999  1038  7020 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 13:55:27.999  1038  7020 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 13:55:27.999  1038  7020 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 13:55:27.999  1038  7020 E DropBoxManagerService: 	at libcore.io.IoBridge.open,(IoBridge.java:442)
08-23 13:55:27.999  1038  7020 E DropBoxManagerService: 	... 5 more
08-23 13:55:28.001  5030  7001 I Process : Sending signal. PID: 5030 SIG: 9
08-23 13:55:28.012  1038  1466 D WifiService: Client connection lost with reason: 4
,08-23 13:55:28.079  1038  2032 I ActivityManager: Process com.google.android.googlequicksearchbox:search (pid 5030) has died
08-23 13:55:28.079  1038  2032 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.icingsync.UpdateIcingCorporaService in 1000ms
08-23 13:55:28.079  1038  2032 W ActivityManager: Scheduling restart of crashed service com.google.android.googlequicksearchbox/com.google.android.search.core.service.SearchService in 11000ms

```
