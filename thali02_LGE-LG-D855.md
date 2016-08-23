#### Test 82337235d68dad2_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-23 13:28:00.051  1588  1588 I [SystemUI]Clock: called onTimeUpdated()
08-23 13:28:00.059  1588  1588 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 13:28:00.059  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
08-23 13:28:00.062  1588  1588 I [SystemUI]DateView: called onTimeUpdated()
08-23 13:28:00.065  1588  1588 D KeyguardUpdateMonitor: handleTimeUpdate
,08-23 13:28:20.021  6735  6735 D AndroidRuntime: 
08-23 13:28:20.021  6735  6735 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-23 13:28:20.027  6735  6735 D AndroidRuntime: CheckJNI is OFF
08-23 13:28:20.148  6735  6735 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-23 13:28:20.153  1035  1050 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-23 13:28:20.163  1927  1943 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-23 13:28:20.166  1035  1050 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-23 13:28:20.167  1035  1050 D ActivityManager: setTaskToReturnTo : TaskRecord{193e2c7 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-23 13:28:20.167  1035  1050 D ActivityManager: setTaskToReturnTo : TaskRecord{193e2c7 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-23 13:28:20.168  1035  1050 D WindowStateEx: AppWindowTokenEx init.. 
08-23 13:28:20.169   339   350 E GBMv2   : DFP En is all cleared set to be enabled
08-23 13:28:20.188  1035  1050 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6750 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-23 13:28:20.189  6735  6735 D AndroidRuntime: Shutting down VM
08-23 13:28:20.256  1927  4004 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-23 13:28:20.257  1927  4004 D SplitWindowPolicy: topRunningActivity=ActivityInfo{31569c85 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-23 13:28:20.258  1927  1944 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-23 13:28:20.258  1927  1944 D SplitWindowPolicy: topRunningActivity=ActivityInfo{396f5ada co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-23 13:28:20.310  6750  6750 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-23 13:28:20.377  6750  6750 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-23 13:28:20.384  6750  6750 I LibraryLoader: Loading: webviewchromium
08-23 13:28:20.387  6750  6750 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 4351-4354)
,08-23 13:28:20.387  6750  6750 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 13:28:20.409  6750  6750 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3f720d7b}
08-23 13:28:20.410  6750  6750 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 13:28:20.410  6750  6750 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-23 13:28:20.417  6750  6750 I BrowserStartupController: Initializing chromium process, renderers=0
08-23 13:28:20.418  6750  6750 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 13:28:20.428   313  1768 V AudioPolicyService: registerClient() client 0xb558a7c0, uid 10118
08-23 13:28:20.429  6750  6750 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-23 13:28:20.429  6750  6750 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-23 13:28:20.430  6750  6750 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-23 13:28:20.431  1035  1106 D BluetoothManagerService: Message: 20
,08-23 13:28:20.431  1035  1106 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@350c5119:true
,08-23 13:28:20.446  6750  6750 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-23 13:28:20.446  6750  6750 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-23 13:28:20.446  6750  6750 I Adreno-EGL: Build Date: 12/12/14 금
08-23 13:28:20.446  6750  6750 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-23 13:28:20.446  6750  6750 I Adreno-EGL: Remote Branch: 
08-23 13:28:20.446  6750  6750 I Adreno-EGL: Local Patches: 
08-23 13:28:20.446  6750  6750 I Adreno-EGL: Reconstruct Branch: 
,08-23 13:28:20.501  6750  6785 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-23 13:28:20.503  6750  6750 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-23 13:28:20.520  6750  6750 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 13:28:20.527  6750  6750 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-23 13:28:20.530  6750  6750 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-23 13:28:20.533  6750  6750 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-23 13:28:20.533  6750  6750 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-23 13:28:20.547  6750  6750 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-23 13:28:20.553  6750  6750 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 13:28:20.553  6750  6750 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 13:28:20.601  6750  6797 D OpenGLRenderer: Render dirty regions requested: true
08-23 13:28:20.601  6750  6797 I OpenGLRenderer: Initialized EGL, version 1.4
,08-23 13:28:20.615  6750  6797 D OpenGLRenderer: Enabling debug mode 0
,08-23 13:28:20.625  6750  6750 D Atlas   : Validating map...
08-23 13:28:20.628  1035  1901 D SplitWindow: check instance of lgWin Window{273b52cb u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-23 13:28:20.662  6750  6795 D LgDataFeature: LgDataFeature() Constructor: none
08-23 13:28:20.662  6750  6795 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-23 13:28:20.775  1035  1107 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +519ms (total +605ms)
08-23 13:28:20.775  6750  6750 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@8dc0e86 time:164742
08-23 13:28:20.775  1035  1107 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{27fa60f4 u0 com.test.thalitest/.MainActivity t6} time:164743
,08-23 13:28:20.899  6750  6750 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 13:28:20.920  6750  6750 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-23 13:28:20.920  6750  6750 I chromium: 
,08-23 13:28:20.946  6750  6795 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-23 13:28:20.946  6750  6795 I chromium: 
,08-23 13:28:21.078  6750  6808 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435032064
,08-23 13:28:21.099  6750  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 13:28:21.099  6750  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 13:28:21.099  6750  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 13:28:21.099  6750  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 13:28:21.099  6750  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-23 13:28:21.099  6750  6808 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3336ac6a added. We now have 1 listener(s)
,08-23 13:28:21.109  1035  2033 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 13:28:21.111  6750  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-23 13:28:21.114  6750  6808 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-23 13:28:21.116  6750  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 13:28:21.117  6750  6808 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-23 13:28:21.126  6750  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 13:28:21.126  6750  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 13:28:21.126  6750  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 13:28:21.126  6750  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-23 13:28:21.126  6750  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 13:28:21.126  6750  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 13:28:21.126  6750  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 13:28:21.126  6750  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 13:28:21.126  6750  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 13:28:21.126  6750  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 13:28:21.126  6750  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 13:28:21.126  6750  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 13:28:21.126  6750  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 13:28:21.126  6750  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
,08-23 13:28:21.126  6750  6808 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@330be6d1 added. We now have 1 listener(s)
08-23 13:28:21.127  6750  6808 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 13:28:21.132  1035  1527 D WifiService: New client listening to asynchronous messages
08-23 13:28:21.136  6750  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 13:28:21.136  6750  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
,08-23 13:28:21.136  6750  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 13:28:21.137  6750  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 13:28:21.137  6750  6808 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-23 13:28:21.144  6750  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 13:28:21.144  1035  1633 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-23 13:28:21.146  6750  6808 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-23 13:28:21.156  6750  6808 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-23 13:28:21.156  6750  6808 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 13:28:21.156  6750  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 13:28:21.156  6750  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 13:28:21.156  6750  6808 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 13:28:21.156  6750  6808 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 13:28:21.156  6750  6808 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 13:28:21.156  6750  6808 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 13:28:21.156  6750  6808 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 13:28:21.156  6750  6808 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 13:28:21.157  6750  6808 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 13:28:21.158  6750  6808 I io.jxcore.node.LifeCycleMonitor: start: OK
08-23 13:28:21.159  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 13:28:21.160  6750  6750 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-23 13:28:21.194  6750  6750 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 13:28:21.929   339   352 E GBMv2   : DFP En is all cleared set to be enabled
08-23 13:28:21.930   339   352 E GBMv2   : Set value is all cleared set the max
08-23 13:28:21.930   339   352 I GBMv2   : DFP Enabled. Ignore VFP set
,08-23 13:28:21.980  6750  6811 W jxcore-log: Initializing JXcore engine
08-23 13:28:21.980  6750  6811 W jxcore-log: JXcore engine is ready
,08-23 13:28:22.011  6811  6811 W Thread-772: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[8341]" dev="sockfs" ino=8341 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-23 13:28:22.011  6811  6811 W Thread-772: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-23 13:28:22.011  6811  6811 W Thread-772: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7805]" dev="sockfs" ino=7805 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-23 13:28:22.011  6811  6811 W Thread-772: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-23 13:28:22.011  6811  6811 W Thread-772: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[33113]" dev="sockfs" ino=33113 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
,08-23 13:28:22.029  6750  6811 W jxcore-log: Starting JXcore engine
08-23 13:28:22.105  6750  6811 W jxcore-log: Platform android
08-23 13:28:22.105  6750  6811 W jxcore-log: 
08-23 13:28:22.105  6750  6811 W jxcore-log: Process ARCH arm
08-23 13:28:22.105  6750  6811 W jxcore-log: 
,08-23 13:28:22.426  6750  6811 I jxcore-log: JXcore Cordova bridge is ready!
08-23 13:28:22.426  6750  6811 I jxcore-log: 
08-23 13:28:22.426  6750  6811 W jxcore-log: JXcore engine is started
,08-23 13:28:22.434  6750  6808 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-23 13:28:22.437  6750  6750 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
08-23 13:28:22.461  6750  6811 E jxcore  : Error!: missing name after . operator
08-23 13:28:22.461  6750  6811 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"591","_columnNumber":"9","_msg":"    at $w.prototype._compile@module.js:591:9"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:260:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,08-23 13:28:22.473  6750  6750 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "missing name after . operator\nSyntaxError: missing name after . operator\n    at $w.prototype._compile@module.js:591:9\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at internal_methods.loadMainFile@main.js:260:5\n    at JXMobile.executeJSON@main.js:279:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (56)
08-23 13:28:22.475  6750  6750 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
,08-23 13:28:22.483  1035  1901 I ActivityManager: Killing 6227:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-23 13:28:22.508  1035  1050 W libprocessgroup: failed to open /acct/uid_10014/pid_6227/cgroup.procs: No such file or directory
08-23 13:28:22.508  6750  6808 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 31ms. Plugin should use CordovaInterface.getThreadPool().
,08-23 13:28:22.513  6750  6750 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-23 13:28:22.514  6750  6750 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-23 13:28:22.516  6750  6750 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 13:28:22.516  6750  6750 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 13:28:22.516  6750  6750 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 13:28:22.517  6750  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 13:28:22.517  6750  6750 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3336ac6a removed from the list
08-23 13:28:22.517  6750  6750 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 13:28:22.517  6750  6750 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@330be6d1 removed from the list
08-23 13:28:22.517  6750  6750 D io.jxcore.node.ConnectivityMonitor: stop
08-23 13:28:22.517  6750  6750 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,08-23 13:28:22.536   339   350 E GBMv2   : DFP En is all cleared set to be enabled
,08-23 13:28:22.543  1927  1944 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-23 13:28:22.544  6750  6750 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-23 13:28:22.544  1927  1944 D SplitWindowPolicy: topRunningActivity=ActivityInfo{b44b0b co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-23 13:28:22.545  1927  1943 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-23 13:28:22.545  1927  1943 D SplitWindowPolicy: topRunningActivity=ActivityInfo{11237de8 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-23 13:28:22.554  2018  2018 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-23 13:28:22.555  2018  2018 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-23 13:28:22.558  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-23 13:28:22.559  2018  2113 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-23 13:28:22.565  2018  2018 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-23 13:28:22.566  1891  1891 D ActionManagerService: notifyUserLog: 1000003
08-23 13:28:22.566  2018  2018 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-23 13:28:22.567  6750  6750 W ScreenOrientationListener: Removing an inexistent observer!
08-23 13:28:22.567  3863  4519 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-23 13:28:22.567  2018  2018 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-23 13:28:22.568  2018  2018 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,08-23 13:28:22.612  1035  1998 D InputDispatcher: Window went away: Window{273b52cb u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-23 13:28:22.636  1035  1098 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6818 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 13:28:22.638  2018  2018 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-23 13:28:22.639  1891  1891 D ActionManagerService: notifyUserLog: 1000004
08-23 13:28:22.640  3863  4519 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-23 13:28:22.641  3863  4516 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-23 13:28:22.644  2018  2018 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-23 13:28:22.644  2018  2018 I GBoardWebViewUtils: , create_time: 1430832262123
08-23 13:28:22.644  2018  2018 I GBoardWebViewUtils: , expire_time: 0
08-23 13:28:22.644  2018  2018 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-23 13:28:22.644  2018  2018 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-23 13:28:22.644  2018  2018 I GBoardWebViewUtils: , display: false
08-23 13:28:22.644  2018  2018 I GBoardWebViewUtils: , animation: false }
08-23 13:28:22.644  2018  2018 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-23 13:28:22.644  2018  2018 I GBoardWebViewUtils: , create_time: 1430832262287
08-23 13:28:22.644  2018  2018 I GBoardWebViewUtils: , expire_time: 0
08-23 13:28:22.644  2018  2018 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-23 13:28:22.644  2018  2018 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-23 13:28:22.644  2018  2018 I GBoardWebViewUtils: , display: false
08-23 13:28:22.644  2018  2018 I GBoardWebViewUtils: , animation: false }
08-23 13:28:22.644  2018  2018 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-23 13:28:22.644  2018  2018 I GBoardWebViewUtils: , create_time: 1471602816196
08-23 13:28:22.644  2018  2018 I GBoardWebViewUtils: , expire_time: 0
08-23 13:28:22.644  2018  2018 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-23 13:28:22.644  2018  2018 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-23 13:28:22.644  2018  2018 I GBoardWebViewUtils: , display: false
08-23 13:28:22.644  2018  2018 I GBoardWebViewUtils: , animation: false }
08-23 13:28:22.655  2018  6828 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-23 13:28:22.693  2018  2018 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-23 13:28:22.743  6812  6812 D AndroidRuntime: 
08-23 13:28:22.743  6812  6812 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-23 13:28:22.745  6812  6812 D AndroidRuntime: CheckJNI is OFF
,08-23 13:28:22.795  1035  1978 I art     : Explicit concurrent mark sweep GC freed 30349(1391KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.322ms total 83.031ms
,08-23 13:28:22.805  2018  2018 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-23 13:28:22.823  6818  6818 I art     : Almond Protected OAT
,08-23 13:28:22.855  6812  6812 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-23 13:28:22.859  6818  6818 D WeatherApplication: removeAccount
,08-23 13:28:22.860  6818  6818 D WeatherApplication: Account.length = 0
08-23 13:28:22.860  6818  6818 E WeatherApplication: OPERATOR:OPEN
08-23 13:28:22.865  6818  6818 D WeatherAncestor: 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 13:28:22
08-23 13:28:22.867  6818  6818 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-23 13:28:22.868  6818  6818 D Weather.Utils: 2 : All the weather widget is gone.
,08-23 13:28:22.870  1035  1098 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-23 13:28:22.870  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
08-23 13:28:22.870  1035  1098 I ActivityManager: Killing 6750:com.test.thalitest/u0a118 (adj 9): stop com.test.thalitest
08-23 13:28:22.872  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 13:28:22.874  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-23 13:28:22.875  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-23 13:28:22.876  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-23 13:28:22.877  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-23 13:28:22.879  6818  6818 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-23 13:28:22.891  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-23 13:28:22.892  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-23 13:28:22.894  2018  2155 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-23 13:28:22.896  2018  2155 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-23 13:28:22.901  1035  1527 D WifiService: Client connection lost with reason: 4
08-23 13:28:22.906  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-23 13:28:22.906  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-23 13:28:22.906  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-23 13:28:22.976  6818  6818 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-23 13:28:22.976  6818  6818 D Weather.Utils: 2 : All the weather widget is gone.
08-23 13:28:22.976  6818  6818 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 13:28:22
08-23 13:28:22.995  2018  2018 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
,08-23 13:28:23.007  1035  1126 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-23 13:28:23.030  1035  1684 W ActivityManager: Spurious death for ProcessRecord{3a508eec 6750:com.test.thalitest/u0a118}, curProc for 6750: null
08-23 13:28:23.030  2566  2566 D [Concierge]Service: onStartCommand(). Type : 8
08-23 13:28:23.030  2566  2566 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
,08-23 13:28:23.033  2566  2566 D [Concierge]Service: Update widget ID : 11
08-23 13:28:23.037  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
08-23 13:28:23.037  2018  2018 D [Concierge]WidgetView: change position of spinner
08-23 13:28:23.046  3922  3922 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-23 13:28:23.046  3922  3922 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-23 13:28:23.047  1981  1981 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-23 13:28:23.048  3863  3863 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-23 13:28:23.054  2494  2679 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
,08-23 13:28:23.055  4525  4525 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-23 13:28:23.056  4525  4525 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-23 13:28:23.056  4525  4525 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-23 13:28:23.056  4525  4525 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-23 13:28:23.056  4525  4525 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 13:28:23.056  4525  4525 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 13:28:23.056  4525  4525 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-23 13:28:23.056  4525  4525 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 13:28:23.056  4525  4525 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 13:28:23.056  4525  4525 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 13:28:23.056  4525  4525 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 13:28:23.056  4525  4525 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 13:28:23.095  1035  1097 W InputMethodInfo: Duplicated subtype definition found: , voice
08-23 13:28:23.096  1035  1924 V SIM_STK : Menu title from STK is T-Mobile
,08-23 13:28:23.116  4630  4630 I art     : Explicit concurrent mark sweep GC freed 1449(65KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 5.190ms total 101.148ms
,08-23 13:28:23.119  1035  1035 D administrator: Handling package changes for user 0
08-23 13:28:23.136  6448  6448 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-23 13:28:23.138  1035  1107 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3a176b18 u0 com.lge.launcher2/.Launcher t5} time:167106
,08-23 13:28:23.148  1803  1803 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-23 13:28:23.150  1855  1855 D SplitUIManager: split_name #11 / not available #0
08-23 13:28:23.150  2018  2018 I [Concierge]WidgetView: initWebView(). Time : 1471951703150
08-23 13:28:23.150  1588  1649 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-23 13:28:23.150  1588  1649 D KeyguardModel: createShortcutInfo...
08-23 13:28:23.150  2566  2566 D [Concierge]Service: onStartCommand(). Type : 0
08-23 13:28:23.150  1855  1855 D SplitUIService: removed split : 
08-23 13:28:23.154  1588  1588 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
,08-23 13:28:23.157  1588  1649 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-23 13:28:23.157  1588  1649 D KeyguardModel: createShortcutInfo...
08-23 13:28:23.165  1588  1649 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-23 13:28:23.166  1588  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 13:28:23.166  1588  1649 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
,08-23 13:28:23.167  1588  1649 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-23 13:28:23.182  1588  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 13:28:23.182  1588  1649 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-23 13:28:23.185  1588  1649 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-23 13:28:23.185  1588  1649 D KeyguardModel: createShortcutInfo...
,08-23 13:28:23.193  2204  2204 I ConfigService: onCreate
08-23 13:28:23.194  1588  1649 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-23 13:28:23.194  1588  1649 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-23 13:28:23.195  2204  2204 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-23 13:28:23.195  1588  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 13:28:23.195  1588  1649 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-23 13:28:23.198  2204  2204 I ConfigService: onBind returning update interface
,08-23 13:28:23.198  1588  1649 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-23 13:28:23.198  1588  1649 D KeyguardModel: createShortcutInfo...
,08-23 13:28:23.199  1588  1588 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-23 13:28:23.199  1588  1588 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-23 13:28:23.202  1035  1050 V SIM_STK : Menu title from STK is T-Mobile
08-23 13:28:23.202  1035  1050 V SIM_STK : Menu title from STK is T-Mobile
08-23 13:28:23.208  2204  2204 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-23 13:28:23.208  2204  2204 I ConfigService: onBind returning config service
08-23 13:28:23.209  1803  1803 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-23 13:28:23.210  1035  1412 I InputReader: Reconfiguring input devices.  changes=0x00000010
08-23 13:28:23.211  1588  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 13:28:23.211  1588  1649 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-23 13:28:23.211  1588  1649 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-23 13:28:23.211  1588  1649 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-23 13:28:23.215  2018  2018 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 974093822
08-23 13:28:23.215  2018  2018 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-23 13:28:23.216  2018  2018 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-23 13:28:23.218  1588  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 13:28:23.218  1855  1855 D SplitUIManager: split_name #11 / not available #0
08-23 13:28:23.218  1588  1649 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-23 13:28:23.218  1855  1855 I SplitUIService: split app #11
08-23 13:28:23.219  2018  2018 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3ab85301
08-23 13:28:23.219  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-23 13:28:23.219  1588  1649 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-23 13:28:23.219  1588  1649 D KeyguardModel: createShortcutInfo...
08-23 13:28:23.221  1803  1803 I ConfigFetchService: service connected
08-23 13:28:23.221  1803  1803 I ConfigClient: service connected
08-23 13:28:23.221  2018  2018 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-23 13:28:23.221  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 13:28:23.225  1588  1588 D KeyguardModel: handleShortcutListChanged...
08-23 13:28:23.225  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-23 13:28:23.227  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-23 13:28:23.228  2018  2018 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-23 13:28:23.228  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-23 13:28:23.228  2018  2018 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.PackageUpdateReceiver
,08-23 13:28:23.233  2018  2018 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-23 13:28:23.241  2018  2018 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471951563000, New one : 1471951703150
08-23 13:28:23.241  2018  2018 D [Concierge]WidgetView: Unregister all receivers
08-23 13:28:23.241  2018  2018 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-23 13:28:23.241  2018  2018 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.PackageUpdateReceiver
08-23 13:28:23.242  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 13:28:23.243  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
,08-23 13:28:23.245  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-23 13:28:23.245  2204  2204 I ConfigService: onDestroy
08-23 13:28:23.246  1588  1649 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-23 13:28:23.246  1588  1649 D KeyguardModel: createShortcutInfo...
08-23 13:28:23.248  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-23 13:28:23.248  1588  1649 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-23 13:28:23.248  1588  1649 D KeyguardModel: createShortcutInfo...
08-23 13:28:23.249  1588  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 13:28:23.249  1588  1649 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-23 13:28:23.249  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-23 13:28:23.249  1588  1649 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-23 13:28:23.249  1588  1649 D KeyguardModel: createShortcutInfo...
08-23 13:28:23.250  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-23 13:28:23.250  1588  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 13:28:23.250  1588  1649 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-23 13:28:23.252  1588  1649 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-23 13:28:23.252  1588  1649 D KeyguardModel: createShortcutInfo...
08-23 13:28:23.253  1588  1649 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 13:28:23.253  1588  1649 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-23 13:28:23.254  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 13:28:23.254  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 13:28:23.255  1588  1649 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-23 13:28:23.255  1588  1649 D KeyguardModel: createShortcutInfo...
,08-23 13:28:23.264  1803  6863 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-23 13:28:23.266  1035  1051 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-23 13:28:23.267  3922  3922 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-23 13:28:23.267  3922  3922 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-23 13:28:23.267  3922  3922 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-23 13:28:23.267  3922  3922 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-23 13:28:23.267  3922  3922 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-23 13:28:23.267  3922  3922 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-23 13:28:23.267  3922  3922 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-23 13:28:23.267  3922  3922 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-23 13:28:23.267  3922  3922 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-23 13:28:23.267  3922  3922 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-23 13:28:23.267  3922  3922 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-23 13:28:23.272  1035  1872 V SIM_STK : Menu title from STK is T-Mobile
08-23 13:28:23.275  1588  1588 D KeyguardModel: handleShortcutListChanged...
,08-23 13:28:23.275  1588  1588 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-23 13:28:23.290  2018  2018 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-23 13:28:23.298  2018  2018 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-23 13:28:23.298  2018  2018 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-23 13:28:23.299  2018  2018 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 13:28:23.309  5939  6868 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-23 13:28:23.320  2018  2018 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1bc1db2b time:167288
,08-23 13:28:23.322  1803  6870 I PeopleContactsSync: CP2 sync disabled
08-23 13:28:23.328  1035  1035 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-23 13:28:23.329  1035  1035 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-23 13:28:23.329  1803  4793 I Icing   : doRemovePackageData com.test.thalitest
08-23 13:28:23.329  1035  1035 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-23 13:28:23.333  1035  1562 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
,08-23 13:28:23.341  1803  6869 W GmsApplication: Using Auth Proxy for data requests.
08-23 13:28:23.344  1803  6869 W GmsApplication: Using Auth Proxy for data requests.
,08-23 13:28:23.358   326   425 I ThermalEngine: Thermal-Server: Thermal received msg from  override
,08-23 13:28:23.359  3176  6872 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-23 13:28:23.376  6011  6011 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-23 13:28:23.390  6539  6539 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
,08-23 13:28:23.392  2337  6874 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-23 13:28:23.429  1981  1981 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-23 13:28:23.429  1981  1981 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-23 13:28:23.431  1981  1981 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-23 13:28:23.432  1035  1097 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 13:28:23.439  1035  1097 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-23 13:28:23.440  6448  6448 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-23 13:28:23.440  2018  2018 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-23 13:28:23.470  1035  1633 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6877 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
08-23 13:28:23.471  1035  1126 I art     : Explicit concurrent mark sweep GC freed 23090(1684KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 1.626ms total 318.784ms
,08-23 13:28:23.503  6812  6812 D AndroidRuntime: Shutting down VM
,08-23 13:28:23.521  2018  2018 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-23 13:28:23.553  6877  6877 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
,08-23 13:28:23.553  6877  6877 W LG Account v2.2: No ProfileInfo entries
08-23 13:28:23.553  6877  6877 I LG Account v2.2: isEnabled: false
08-23 13:28:23.553  6877  6877 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-23 13:28:23.554  6877  6877 I Feature : [Lifetracker]Country: EU
08-23 13:28:23.554  6877  6877 I Feature : [Lifetracker]Operator: OPEN
08-23 13:28:23.554  6877  6877 I Feature : [Lifetracker]Ranking support: false
08-23 13:28:23.554  6877  6877 I Feature : [Lifetracker]Comfort support: false
08-23 13:28:23.554  6877  6877 I Feature : [Lifetracker]Accessory: true
08-23 13:28:23.554  6877  6877 I Feature : [Lifetracker]Health device: true
08-23 13:28:23.554  6877  6877 I Feature : [Lifetracker]Extra Pedometer: false
08-23 13:28:23.554  6877  6877 I Feature : [Lifetracker]Blood glucose device: false
08-23 13:28:23.554  6877  6877 I Feature : [Lifetracker]Device Number: 3
08-23 13:28:23.555  6877  6877 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-23 13:28:23.558  2018  2873 I GBoardtInterface: onReloaded()
08-23 13:28:23.560  2018  2018 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
,08-23 13:28:23.573  1035  1998 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6897 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-23 13:28:23.574  1035  1998 I ActivityManager: Killing 6489:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-23 13:28:23.574  3863  4516 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-23 13:28:23.602  1035  1579 W libprocessgroup: failed to open /acct/uid_10008/pid_6489/cgroup.procs: No such file or directory
,08-23 13:28:23.607  3863  3878 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-23 13:28:23.612  1891  1891 D ActionManagerService: notifyUserLog: 1000001
08-23 13:28:23.613  3863  4519 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-23 13:28:23.613  3863  4519 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-23 13:28:23.615  1891  1891 D ActionManagerService: notifyUserLog: 1000001
,08-23 13:28:23.616  3863  4519 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-23 13:28:23.616  3863  4519 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-23 13:28:23.616  3863  4519 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-23 13:28:23.616  3863  4519 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-23 13:28:23.617  6897  6897 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 13:28:23.617  6897  6897 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-23 13:28:23.617  3863  3878 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-23 13:28:23.617  6897  6897 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-23 13:28:23.617  6897  6897 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-23 13:28:23.618  6897  6897 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-23 13:28:23.618  6897  6897 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-23 13:28:23.619  2018  2018 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-23 13:28:23.619  2018  2018 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-23 13:28:23.621  2018  2018 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-23 13:28:23.621  2018  2018 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-23 13:28:23.623  2018  2018 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-23 13:28:23.623  2018  2018 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-23 13:28:23.690  6897  6897 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-23 13:28:23.695  6897  6897 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-23 13:28:23.695  6897  6897 D HideNavigationAppsReceiver: replacing : false
08-23 13:28:23.697  6897  6897 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-23 13:28:23.698  6897  6897 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-23 13:28:23.698  6897  6897 D ButtonCombinationReceiver: replacing : false
08-23 13:28:23.703  1035  2013 I ActivityManager: Killing 6574:com.google.android.apps.docs/u0a61 (adj 15): empty #17
,08-23 13:28:23.803  1035  1924 W libprocessgroup: failed to open /acct/uid_10061/pid_6574/cgroup.procs: No such file or directory
,08-23 13:28:23.809  4630  6916 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-23 13:28:23.830  1035  1050 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6917 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-23 13:28:23.831  1035  1684 V SIM_STK : Menu title from STK is T-Mobile
,08-23 13:28:23.840  4630  6916 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
08-23 13:28:23.841   343   343 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 198us total 10.798ms
--------- beginning of crash
08-23 13:28:23.842  4630  6916 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-23 13:28:23.842  4630  6916 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 4630
08-23 13:28:23.842  4630  6916 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 13:28:23.842  4630  6916 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 13:28:23.842  4630  6916 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-23 13:28:23.842  4630  6916 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-23 13:28:23.842  4630  6916 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-23 13:28:23.842  4630  6916 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-23 13:28:23.842  4630  6916 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-23 13:28:23.842  4630  6916 E AndroidRuntime: 	at csx.d(PG:186)
08-23 13:28:23.842  4630  6916 E AndroidRuntime: 	at cun.g(PG:594)
08-23 13:28:23.842  4630  6916 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
08-23 13:28:23.842  4630  6916 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
08-23 13:28:23.842  4630  6916 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1349)
08-23 13:28:23.842  4630  6916 E AndroidRuntime: 	at cuw.Tg(PG:368)
08-23 13:28:23.842  4630  6916 E AndroidRuntime: 	at cuy.ub(PG:301)
08-23 13:28:23.842  4630  6916 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
08-23 13:28:23.842  4630  6916 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
08-23 13:28:23.842  4630  6916 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 13:28:23.842  4630  6916 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 13:28:23.842  4630  6916 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-23 13:28:23.842  4630  6916 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 13:28:23.846  4630  6916 I Process : Sending signal. PID: 4630 SIG: 9
08-23 13:28:23.850   343   343 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 184us total 9.090ms

```
