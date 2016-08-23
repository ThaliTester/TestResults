#### Test 8233723530fac5a_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-23 12:27:00.109  1606  1606 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-23 12:27:00.109  1606  1606 I KeyguardUpdateMonitor: called onTimeUpdated()
08-23 12:27:00.109  1606  1606 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-23 12:27:00.110  1606  1606 I [SystemUI]Clock: called onTimeUpdated()
,08-23 12:27:00.123  1606  1606 I LgeClockWidgetControlView: called onTimeUpdated()
08-23 12:27:00.123  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
08-23 12:27:00.125  1606  1606 I [SystemUI]DateView: called onTimeUpdated()
08-23 12:27:00.127  1606  1606 D KeyguardUpdateMonitor: handleTimeUpdate
08-23 12:27:00.415  6628  6628 D AndroidRuntime: 
08-23 12:27:00.415  6628  6628 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-23 12:27:00.419  6628  6628 D AndroidRuntime: CheckJNI is OFF
08-23 12:27:00.547  6628  6628 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-23 12:27:00.552  1037  1961 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-23 12:27:00.561  1943  3974 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-23 12:27:00.566  1037  1961 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-23 12:27:00.567  1037  1961 D ActivityManager: setTaskToReturnTo : TaskRecord{2c6b9237 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-23 12:27:00.567  1037  1961 D ActivityManager: setTaskToReturnTo : TaskRecord{2c6b9237 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-23 12:27:00.568  1037  1961 D WindowStateEx: AppWindowTokenEx init.. 
08-23 12:27:00.568   340   348 E GBMv2   : DFP En is all cleared set to be enabled
08-23 12:27:00.590  1037  1961 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6643 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-23 12:27:00.592  6628  6628 D AndroidRuntime: Shutting down VM
08-23 12:27:00.665  1943  3974 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-23 12:27:00.665  1943  3974 D SplitWindowPolicy: topRunningActivity=ActivityInfo{25eabedc co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-23 12:27:00.666  1943  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-23 12:27:00.666  1943  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{25427be5 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-23 12:27:00.725  6643  6643 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-23 12:27:00.843  6643  6643 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-23 12:27:00.867  6643  6643 I LibraryLoader: Loading: webviewchromium
,08-23 12:27:00.875  6643  6643 I LibraryLoader: Time to load native libraries: 9 ms (timestamps 5151-5160)
08-23 12:27:00.875  6643  6643 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 12:27:00.899  6643  6643 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {134834ea}
,08-23 12:27:00.901  6643  6643 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-23 12:27:00.902  6643  6643 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-23 12:27:00.916  6643  6643 I BrowserStartupController: Initializing chromium process, renderers=0
,08-23 12:27:00.917  6643  6643 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 12:27:00.935  6643  6643 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
,08-23 12:27:00.936  6643  6643 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-23 12:27:00.936  6643  6643 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-23 12:27:00.941   316   316 V AudioPolicyService: registerClient() client 0xb558ad80, uid 10118
08-23 12:27:00.959  1037  1119 D BluetoothManagerService: Message: 20
,08-23 12:27:00.959  1037  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1b50509:true
08-23 12:27:00.973  6643  6643 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-23 12:27:00.973  6643  6643 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-23 12:27:00.973  6643  6643 I Adreno-EGL: Build Date: 12/12/14 금
08-23 12:27:00.973  6643  6643 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-23 12:27:00.973  6643  6643 I Adreno-EGL: Remote Branch: 
08-23 12:27:00.973  6643  6643 I Adreno-EGL: Local Patches: 
08-23 12:27:00.973  6643  6643 I Adreno-EGL: Reconstruct Branch: 
,08-23 12:27:01.074  6643  6687 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-23 12:27:01.077  6643  6643 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-23 12:27:01.095  6643  6643 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-23 12:27:01.101  6643  6643 W AwContents: onDetachedFromWindow called when already detached. Ignoring
,08-23 12:27:01.104  6643  6643 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-23 12:27:01.107  6643  6643 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-23 12:27:01.107  6643  6643 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-23 12:27:01.120  6643  6643 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-23 12:27:01.130  6643  6643 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 12:27:01.130  6643  6643 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-23 12:27:01.155  1037  1093 W ActivityManager: Activity pause timeout for ActivityRecord{3de433a4 u0 com.test.thalitest/.MainActivity t6}
,08-23 12:27:01.169  6643  6704 D OpenGLRenderer: Render dirty regions requested: true
,08-23 12:27:01.169  6643  6704 I OpenGLRenderer: Initialized EGL, version 1.4
,08-23 12:27:01.176  6643  6704 D OpenGLRenderer: Enabling debug mode 0
08-23 12:27:01.184  6643  6643 D Atlas   : Validating map...
,08-23 12:27:01.188  1037  1782 D SplitWindow: check instance of lgWin Window{363ee33b u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-23 12:27:01.240  6643  6643 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@324c48c1 time:195526
,08-23 12:27:01.252  6643  6702 D LgDataFeature: LgDataFeature() Constructor: none
08-23 12:27:01.252  6643  6702 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-23 12:27:01.263  1037  1120 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +608ms (total +694ms)
,08-23 12:27:01.264  1037  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3de433a4 u0 com.test.thalitest/.MainActivity t6} time:195549
08-23 12:27:01.400  6643  6643 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-23 12:27:01.400  6643  6643 I chromium: 
,08-23 12:27:01.432  6643  6643 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-23 12:27:01.593  6643  6717 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435169792
,08-23 12:27:01.610  6643  6717 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-23 12:27:01.610  6643  6717 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-23 12:27:01.610  6643  6717 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-23 12:27:01.610  6643  6717 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-23 12:27:01.610  6643  6717 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-23 12:27:01.610  6643  6717 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e5de1b5 added. We now have 1 listener(s)
08-23 12:27:01.616  1037  1053 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-23 12:27:01.620  6643  6717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-23 12:27:01.622  6643  6717 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-23 12:27:01.623  6643  6717 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-23 12:27:01.623  6643  6717 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-23 12:27:01.632  6643  6717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-23 12:27:01.632  6643  6717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-23 12:27:01.632  6643  6717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-23 12:27:01.632  6643  6717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-23 12:27:01.632  6643  6717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-23 12:27:01.632  6643  6717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-23 12:27:01.632  6643  6717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-23 12:27:01.632  6643  6717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-23 12:27:01.632  6643  6717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-23 12:27:01.632  6643  6717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-23 12:27:01.632  6643  6717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-23 12:27:01.632  6643  6717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-23 12:27:01.632  6643  6717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-23 12:27:01.632  6643  6717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-23 12:27:01.632  6643  6717 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@686a8d8 added. We now have 1 listener(s)
08-23 12:27:01.632  6643  6717 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-23 12:27:01.640  1037  1547 D WifiService: New client listening to asynchronous messages
,08-23 12:27:01.645  6643  6717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-23 12:27:01.646  6643  6717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-23 12:27:01.647  6643  6717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-23 12:27:01.648  6643  6717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-23 12:27:01.648  6643  6717 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-23 12:27:01.655  6643  6717 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-23 12:27:01.655  1037  1782 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-23 12:27:01.660  6643  6717 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-23 12:27:01.675  6643  6717 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-23 12:27:01.675  6643  6717 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-23 12:27:01.675  6643  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-23 12:27:01.675  6643  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-23 12:27:01.675  6643  6717 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-23 12:27:01.675  6643  6717 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-23 12:27:01.675  6643  6717 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-23 12:27:01.675  6643  6717 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-23 12:27:01.675  6643  6717 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-23 12:27:01.675  6643  6717 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-23 12:27:01.676  6643  6717 D io.jxcore.node.ConnectivityMonitor: start: OK
08-23 12:27:01.678  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:27:01.678  6643  6717 I io.jxcore.node.LifeCycleMonitor: start: OK
08-23 12:27:01.680  6643  6643 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-23 12:27:01.714  6643  6702 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-23 12:27:01.714  6643  6702 I chromium: 
,08-23 12:27:01.792  6643  6643 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-23 12:27:02.422  6643  6720 W jxcore-log: Initializing JXcore engine
08-23 12:27:02.422  6643  6720 W jxcore-log: JXcore engine is ready
,08-23 12:27:02.457   340   350 E GBMv2   : DFP En is all cleared set to be enabled
08-23 12:27:02.458   340   350 E GBMv2   : Set value is all cleared set the max
08-23 12:27:02.458   340   350 I GBMv2   : DFP Enabled. Ignore VFP set
,08-23 12:27:02.453  6720  6720 W Thread-762: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[9344]" dev="sockfs" ino=9344 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-23 12:27:02.453  6720  6720 W Thread-762: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-23 12:27:02.453  6720  6720 W Thread-762: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[9061]" dev="sockfs" ino=9061 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-23 12:27:02.453  6720  6720 W Thread-762: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-23 12:27:02.453  6720  6720 W Thread-762: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[33079]" dev="sockfs" ino=33079 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-23 12:27:02.475  6643  6720 W jxcore-log: Starting JXcore engine
,08-23 12:27:02.550  6643  6720 W jxcore-log: Platform android
08-23 12:27:02.550  6643  6720 W jxcore-log: 
08-23 12:27:02.551  6643  6720 W jxcore-log: Process ARCH arm
08-23 12:27:02.551  6643  6720 W jxcore-log: 
,08-23 12:27:02.745  6643  6720 I jxcore-log: JXcore Cordova bridge is ready!
08-23 12:27:02.745  6643  6720 I jxcore-log: 
08-23 12:27:02.746  6643  6720 W jxcore-log: JXcore engine is started
,08-23 12:27:02.756  6643  6717 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-23 12:27:02.759  6643  6643 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-23 12:27:02.777  6643  6720 E jxcore  : Error!: missing name after . operator
08-23 12:27:02.777  6643  6720 E jxcore  : Stack: [{"_fileName":"module.js","_functionName":"$w.prototype._compile","_lineNumber":"591","_columnNumber":"9","_msg":"    at $w.prototype._compile@module.js:591:9"},{"_fileName":"module.js","_functionName":"$w._extensions[\".js\"]","_lineNumber":"651","_columnNumber":"1","_msg":"    at $w._extensions[\".js\"]@module.js:651:1"},{"_fileName":"module.js","_functionName":"$w.prototype.load","_lineNumber":"442","_columnNumber":"1","_msg":"    at $w.prototype.load@module.js:442:1"},{"_fileName":"module.js","_functionName":"$w._load","_lineNumber":"407","_columnNumber":"1","_msg":"    at $w._load@module.js:407:1"},{"_fileName":"module.js","_functionName":"$w.prototype.require","_lineNumber":"477","_columnNumber":"8","_msg":"    at $w.prototype.require@module.js:477:8"},{"_fileName":"module.js","_functionName":"require","_lineNumber":"495","_columnNumber":"8","_msg":"    at require@module.js:495:8"},{"_fileName":"main.js","_functionName":"internal_methods.loadMainFile","_lineNumber":"260","_columnNumber":"5","_msg":"    at internal_methods.loadMainFile@main.js:260:5"},{"_fileName":"main.js","_functionName":"JXMobile.executeJSON","_lineNumber":"279","_columnNumber":"7","_msg":"    at JXMobile.executeJSON@main.js:279:7"},{"_fileName":"JX_Evaluate","_functionName":"","_lineNumber":"1","_columnNumber":"1","_msg":"    at @JX_Evaluate:1:1"}]
,08-23 12:27:02.782  6643  6643 I chromium: [INFO:CONSOLE(56)] "app.js file failed to load : "missing name after . operator\nSyntaxError: missing name after . operator\n    at $w.prototype._compile@module.js:591:9\n    at $w._extensions[\".js\"]@module.js:651:1\n    at $w.prototype.load@module.js:442:1\n    at $w._load@module.js:407:1\n    at $w.prototype.require@module.js:477:8\n    at require@module.js:495:8\n    at internal_methods.loadMainFile@main.js:260:5\n    at JXMobile.executeJSON@main.js:279:7\n    at @JX_Evaluate:1:1"", source: file:///android_asset/www/js/thali_main.js (56)
08-23 12:27:02.783  6643  6643 I chromium: [INFO:CONSOLE(72)] "****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****", source: file:///android_asset/www/js/thali_main.js (72)
08-23 12:27:02.787  1037  1052 I ActivityManager: Killing 5910:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-23 12:27:02.811  1037  2015 W libprocessgroup: failed to open /acct/uid_10014/pid_5910/cgroup.procs: No such file or directory
08-23 12:27:02.811  6643  6643 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-23 12:27:02.812  6643  6643 D io.jxcore.node.JXcoreExtension: onActivityLifeCycleEvent: DESTROYED
08-23 12:27:02.812  6643  6643 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-23 12:27:02.812  6643  6643 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-23 12:27:02.812  6643  6643 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 1 listener(s) left
08-23 12:27:02.812  6643  6643 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-23 12:27:02.812  6643  6643 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1e5de1b5 removed from the list
08-23 12:27:02.812  6643  6643 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-23 12:27:02.812  6643  6643 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@686a8d8 removed from the list
08-23 12:27:02.813  6643  6643 D io.jxcore.node.ConnectivityMonitor: stop
08-23 12:27:02.813  6643  6643 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: No more listeners, de-initializing...
,08-23 12:27:02.817  6643  6717 W PluginManager: THREAD WARNING: exec() call to CoreAndroid.exitApp blocked the main thread for 33ms. Plugin should use CordovaInterface.getThreadPool().
08-23 12:27:02.828   340   348 E GBMv2   : DFP En is all cleared set to be enabled
,08-23 12:27:02.836  1943  1958 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-23 12:27:02.836  1943  1958 D SplitWindowPolicy: topRunningActivity=ActivityInfo{172cb6ba co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-23 12:27:02.837  6643  6643 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-23 12:27:02.838  1943  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-23 12:27:02.838  1943  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{b92a96b co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-23 12:27:02.839  6643  6643 W ScreenOrientationListener: Removing an inexistent observer!
,08-23 12:27:02.861  2035  2035 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-23 12:27:02.862  2035  2035 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-23 12:27:02.867  1037  1924 D InputDispatcher: Window went away: Window{363ee33b u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-23 12:27:02.869  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-23 12:27:02.870  2035  2127 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
,08-23 12:27:02.873  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-23 12:27:02.873  1907  1907 D ActionManagerService: notifyUserLog: 1000003
,08-23 12:27:02.874  3821  4470 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-23 12:27:02.875  2035  2035 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-23 12:27:02.878  2035  2035 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-23 12:27:02.904  1037  1093 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=6723 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 12:27:02.909  2035  2035 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
08-23 12:27:02.912  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
08-23 12:27:02.913  3821  3837 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-23 12:27:02.914  1907  1907 D ActionManagerService: notifyUserLog: 1000004
08-23 12:27:02.915  3821  4470 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
,08-23 12:27:02.919  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-23 12:27:02.919  2035  2035 I GBoardWebViewUtils: , create_time: 1430832262123
08-23 12:27:02.919  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-23 12:27:02.919  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-23 12:27:02.919  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-23 12:27:02.919  2035  2035 I GBoardWebViewUtils: , display: false
08-23 12:27:02.919  2035  2035 I GBoardWebViewUtils: , animation: false }
08-23 12:27:02.919  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-23 12:27:02.919  2035  2035 I GBoardWebViewUtils: , create_time: 1430832262287
08-23 12:27:02.919  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-23 12:27:02.919  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-23 12:27:02.919  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-23 12:27:02.919  2035  2035 I GBoardWebViewUtils: , display: false
08-23 12:27:02.919  2035  2035 I GBoardWebViewUtils: , animation: false }
08-23 12:27:02.919  2035  2035 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471602815280
08-23 12:27:02.919  2035  2035 I GBoardWebViewUtils: , create_time: 1471602816196
08-23 12:27:02.919  2035  2035 I GBoardWebViewUtils: , expire_time: 0
08-23 12:27:02.919  2035  2035 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-23 12:27:02.919  2035  2035 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-23 12:27:02.919  2035  2035 I GBoardWebViewUtils: , display: false
08-23 12:27:02.919  2035  2035 I GBoardWebViewUtils: , animation: false }
08-23 12:27:02.940  2035  6741 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
,08-23 12:27:02.952  2035  2035 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
,08-23 12:27:03.036  6721  6721 D AndroidRuntime: 
08-23 12:27:03.036  6721  6721 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-23 12:27:03.039  6721  6721 D AndroidRuntime: CheckJNI is OFF
08-23 12:27:03.039  2035  2035 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
08-23 12:27:03.056  1037  1578 I art     : Explicit concurrent mark sweep GC freed 29587(1430KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 1.936ms total 81.218ms
,08-23 12:27:03.067  6723  6723 I art     : Almond Protected OAT
,08-23 12:27:03.095  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-23 12:27:03.098  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 12:27:03.099  6723  6723 D WeatherApplication: removeAccount
08-23 12:27:03.100  6723  6723 D WeatherApplication: Account.length = 0
08-23 12:27:03.100  6723  6723 E WeatherApplication: OPERATOR:OPEN
08-23 12:27:03.101  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-23 12:27:03.102  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-23 12:27:03.103  6723  6723 D WeatherAncestor: 2 : onReceive, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 12:27:3
08-23 12:27:03.103  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-23 12:27:03.104  6723  6723 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-23 12:27:03.104  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-23 12:27:03.104  6723  6723 D Weather.Utils: 2 : All the weather widget is gone.
08-23 12:27:03.105  6723  6723 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-23 12:27:03.106  6723  6723 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-23 12:27:03.106  6723  6723 D Weather.Utils: 2 : All the weather widget is gone.
,08-23 12:27:03.107  6723  6723 D WeatherAncestor: 2 : onReceive has processed, action: com.lge.launcher2.RESUME, Time(hour:min:sec) 12:27:3
08-23 12:27:03.108  1037  1997 I ActivityManager: Killing 6204:com.android.defcontainer/u0a4 (adj 15): empty #17
08-23 12:27:03.119  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-23 12:27:03.119  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-23 12:27:03.121  2035  2196 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-23 12:27:03.121  2035  2196 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-23 12:27:03.133  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
,08-23 12:27:03.134  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-23 12:27:03.134  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 12:27:03.139  2035  2035 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-23 12:27:03.147  6721  6721 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-23 12:27:03.186  1037  1782 W libprocessgroup: failed to open /acct/uid_10004/pid_6204/cgroup.procs: No such file or directory
,08-23 12:27:03.242  2561  2561 D [Concierge]Service: onStartCommand(). Type : 8
08-23 12:27:03.242  2561  2561 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-23 12:27:03.243  1037  1093 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-23 12:27:03.244  1037  1093 I ActivityManager: Killing 6643:com.test.thalitest/u0a118 (adj 9): stop com.test.thalitest
08-23 12:27:03.245  2561  2561 D [Concierge]Service: Update widget ID : 11
08-23 12:27:03.260  2035  2035 D [Concierge]WidgetView: change position of spinner
,08-23 12:27:03.279  1037  1547 D WifiService: Client connection lost with reason: 4
,08-23 12:27:03.362  1037  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{7f9c41a u0 com.lge.launcher2/.Launcher t5} time:197648
,08-23 12:27:03.365  1037  1785 W ActivityManager: Spurious death for ProcessRecord{20b61f9c 6643:com.test.thalitest/u0a118}, curProc for 6643: null
08-23 12:27:03.365  2035  2035 I [Concierge]WidgetView: initWebView(). Time : 1471948023365
08-23 12:27:03.366  1037  1125 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
08-23 12:27:03.368  2561  2561 D [Concierge]Service: onStartCommand(). Type : 0
,08-23 12:27:03.390   308   308 I rmt_storage: rmt_storage_connect_cb: clnt_h=0x6 conn_h=0xb6403090
08-23 12:27:03.390   308   308 I rmt_storage: rmt_storage_rw_iovec_cb: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: R/W request received
08-23 12:27:03.390   308   308 I rmt_storage: wakelock acquired: 1, error no: 42
08-23 12:27:03.390   308   915 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 Unblock worker thread (th_id: -1236807552)
08-23 12:27:03.407  1606  1606 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-23 12:27:03.417  3880  3880 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-23 12:27:03.417  3880  3880 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-23 12:27:03.423  6336  6336 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-23 12:27:03.429  1998  1998 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
,08-23 12:27:03.430  3821  3821 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-23 12:27:03.433  4477  4477 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-23 12:27:03.434  4477  4477 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-23 12:27:03.434  4477  4477 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-23 12:27:03.434  4477  4477 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-23 12:27:03.434  4477  4477 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-23 12:27:03.434  4477  4477 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-23 12:27:03.434  4477  4477 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-23 12:27:03.434  4477  4477 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-23 12:27:03.434  4477  4477 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-23 12:27:03.434  4477  4477 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-23 12:27:03.434  4477  4477 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-23 12:27:03.434  4477  4477 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-23 12:27:03.438  2489  2654 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-23 12:27:03.444  1037  1475 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-23 12:27:03.447  4583  4583 I art     : Explicit concurrent mark sweep GC freed 479(32KB) AllocSpace objects, 0(0B) LOS objects, 34% free, 30MB/46MB, paused 427us total 67.383ms
08-23 12:27:03.456  1037  1092 W InputMethodInfo: Duplicated subtype definition found: , voice
08-23 12:27:03.462  1037  1961 V SIM_STK : Menu title from STK is T-Mobile
08-23 12:27:03.488  1821  1821 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
,08-23 12:27:03.520  1037  1037 D administrator: Handling package changes for user 0
,08-23 12:27:03.526  1606  1606 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-23 12:27:03.527  1606  1655 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-23 12:27:03.527  1606  1655 D KeyguardModel: createShortcutInfo...
08-23 12:27:03.531  2174  2174 I ConfigService: onCreate
08-23 12:27:03.531  2174  2174 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-23 12:27:03.537  2174  2174 I ConfigService: onBind returning update interface
,08-23 12:27:03.547  1821  1821 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-23 12:27:03.555  2174  2174 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-23 12:27:03.555  2174  2174 I ConfigService: onBind returning config service
,08-23 12:27:03.555  1606  1655 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-23 12:27:03.555  1606  1655 D KeyguardModel: createShortcutInfo...
08-23 12:27:03.564  1606  1655 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-23 12:27:03.564  1606  1655 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 12:27:03.564  1606  1655 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-23 12:27:03.565   308   915 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Bytes written = 1572864
08-23 12:27:03.565   308   915 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1: req_h=0xa msg_id=3: Send response: res=0 err=0
08-23 12:27:03.565   308   915 I rmt_storage: rmt_storage_client_thread: /boot/modem_fs1: clnt_h=0x1 About to block rmt_storage client thread (th_id: -1236807552) wakelock released: 1, error no: 22
08-23 12:27:03.565   308   915 I rmt_storage: 
08-23 12:27:03.565  1606  1655 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-23 12:27:03.566  1606  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 12:27:03.566  1606  1655 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-23 12:27:03.567   308   308 I rmt_storage: rmt_storage_disconnect_cb: clnt_h=0x0x6 conn_h=0x0xb6403090
08-23 12:27:03.567   907   914 E Diag_Lib: [IMS_FATAL]| 3347 | 914 |ims-rtp-daemon ims_rtp_qmi_handler_thread_func waiting on select thread>
,08-23 12:27:03.571  1606  1655 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-23 12:27:03.571  1606  1655 D KeyguardModel: createShortcutInfo...
08-23 12:27:03.575  1037  1782 V SIM_STK : Menu title from STK is T-Mobile
,08-23 12:27:03.575  1037  1782 V SIM_STK : Menu title from STK is T-Mobile
08-23 12:27:03.576  1606  1655 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-23 12:27:03.576  1606  1655 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-23 12:27:03.579  1821  1821 I ConfigFetchService: service connected
,08-23 12:27:03.580  2035  2035 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 200476441
08-23 12:27:03.580  2035  2035 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-23 12:27:03.581  2035  2035 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-23 12:27:03.581  1606  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 12:27:03.581  1606  1655 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-23 12:27:03.583  2174  2174 I ConfigService: onDestroy
08-23 12:27:03.583  2035  2035 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@3f23fc8
08-23 12:27:03.583  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-23 12:27:03.585  2035  2035 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-23 12:27:03.585  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 12:27:03.586  1037  1785 V SIM_STK : Menu title from STK is T-Mobile
08-23 12:27:03.589  1873  1873 D SplitUIManager: split_name #11 / not available #0
08-23 12:27:03.589  1606  1655 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-23 12:27:03.589  1606  1655 D KeyguardModel: createShortcutInfo...
08-23 12:27:03.589  1873  1873 D SplitUIService: removed split : 
08-23 12:27:03.589  1606  1606 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-23 12:27:03.589  1606  1606 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-23 12:27:03.591  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-23 12:27:03.592  2035  2035 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-23 12:27:03.592  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-23 12:27:03.592  2035  2035 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.PackageUpdateReceiver
,08-23 12:27:03.597  1606  1655 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 12:27:03.597  1606  1655 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-23 12:27:03.598  1606  1655 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-23 12:27:03.598  1606  1655 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-23 12:27:03.599  1606  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 12:27:03.599  1606  1655 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-23 12:27:03.601  1606  1655 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-23 12:27:03.601  1606  1655 D KeyguardModel: createShortcutInfo...
08-23 12:27:03.608  2035  2035 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-23 12:27:03.609  1606  1606 D KeyguardModel: handleShortcutListChanged...
08-23 12:27:03.609  1606  1606 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-23 12:27:03.610  2035  2035 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471947853985, New one : 1471948023365
08-23 12:27:03.610  2035  2035 D [Concierge]WidgetView: Unregister all receivers
08-23 12:27:03.610  2035  2035 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-23 12:27:03.610  2035  2035 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.PackageUpdateReceiver
08-23 12:27:03.610  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 12:27:03.612  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-23 12:27:03.613  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-23 12:27:03.614  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
,08-23 12:27:03.615  1606  1655 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-23 12:27:03.615  1606  1655 D KeyguardModel: createShortcutInfo...
08-23 12:27:03.615  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-23 12:27:03.616  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-23 12:27:03.617  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 12:27:03.617  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 12:27:03.619   334   415 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-23 12:27:03.619  3204  6773 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-23 12:27:03.631  1606  1655 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-23 12:27:03.631  1606  1655 D KeyguardModel: createShortcutInfo...
08-23 12:27:03.634  1606  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 12:27:03.634  1606  1655 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-23 12:27:03.636  1037  1924 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-23 12:27:03.636  1873  1873 D SplitUIManager: split_name #11 / not available #0
08-23 12:27:03.636  1873  1873 I SplitUIService: split app #11
08-23 12:27:03.636  3880  3880 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-23 12:27:03.636  3880  3880 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-23 12:27:03.637  3880  3880 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-23 12:27:03.637  3880  3880 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-23 12:27:03.637  3880  3880 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-23 12:27:03.637  3880  3880 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-23 12:27:03.637  3880  3880 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-23 12:27:03.637  3880  3880 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-23 12:27:03.637  3880  3880 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-23 12:27:03.637  3880  3880 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-23 12:27:03.637  3880  3880 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-23 12:27:03.639  1606  1655 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-23 12:27:03.639  1606  1655 D KeyguardModel: createShortcutInfo...
08-23 12:27:03.640  1606  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 12:27:03.640  1606  1655 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-23 12:27:03.641  1821  6772 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
08-23 12:27:03.642  1606  1655 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-23 12:27:03.643  1606  1655 D KeyguardModel: createShortcutInfo...
08-23 12:27:03.645  1606  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-23 12:27:03.645  1606  1655 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-23 12:27:03.657  1606  1655 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-23 12:27:03.657  1606  1655 D KeyguardModel: createShortcutInfo...
08-23 12:27:03.663  2035  2035 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
,08-23 12:27:03.665  1037  1037 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-23 12:27:03.665  1037  1037 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-23 12:27:03.665  1037  1037 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
08-23 12:27:03.667  1037  1580 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-23 12:27:03.670  5938  6779 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-23 12:27:03.679  2035  2035 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-23 12:27:03.679  2035  2035 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-23 12:27:03.685  2035  2035 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-23 12:27:03.694  1606  1606 D KeyguardModel: handleShortcutListChanged...
08-23 12:27:03.694  1606  1606 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-23 12:27:03.701  1821  6780 I PeopleContactsSync: CP2 sync disabled
08-23 12:27:03.706  1821  4728 I Icing   : doRemovePackageData com.test.thalitest
08-23 12:27:03.719  2035  2035 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@850835a time:198005
,08-23 12:27:03.729  1821  6778 W GmsApplication: Using Auth Proxy for data requests.
08-23 12:27:03.733  1821  6778 W GmsApplication: Using Auth Proxy for data requests.
08-23 12:27:03.755  6013  6013 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-23 12:27:03.770  6421  6421 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-23 12:27:03.770  2320  6783 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
,08-23 12:27:03.790  1998  1998 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-23 12:27:03.790  1998  1998 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
,08-23 12:27:03.790  1998  1998 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-23 12:27:03.798  1037  1125 I art     : Explicit concurrent mark sweep GC freed 22595(1669KB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/65MB, paused 1.379ms total 268.701ms
08-23 12:27:03.799  6336  6336 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-23 12:27:03.818  1037  1784 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=6785 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-23 12:27:03.880  1037  1092 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 12:27:03.881  2035  2035 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
08-23 12:27:03.883  1037  1092 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
,08-23 12:27:03.891  6721  6721 D AndroidRuntime: Shutting down VM
,08-23 12:27:03.920  1037  1125 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=6805 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-23 12:27:03.921  6785  6785 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-23 12:27:03.921  2035  2035 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-23 12:27:03.922  6785  6785 W LG Account v2.2: No ProfileInfo entries
08-23 12:27:03.922  6785  6785 I LG Account v2.2: isEnabled: false
08-23 12:27:03.922  2035  2859 I GBoardtInterface: onReloaded()
08-23 12:27:03.923  6785  6785 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-23 12:27:03.923  6785  6785 I Feature : [Lifetracker]Country: EU
08-23 12:27:03.923  6785  6785 I Feature : [Lifetracker]Operator: OPEN
08-23 12:27:03.923  6785  6785 I Feature : [Lifetracker]Ranking support: false
08-23 12:27:03.923  6785  6785 I Feature : [Lifetracker]Comfort support: false
08-23 12:27:03.923  6785  6785 I Feature : [Lifetracker]Accessory: true
08-23 12:27:03.923  6785  6785 I Feature : [Lifetracker]Health device: true
08-23 12:27:03.923  6785  6785 I Feature : [Lifetracker]Extra Pedometer: false
08-23 12:27:03.923  6785  6785 I Feature : [Lifetracker]Blood glucose device: false
08-23 12:27:03.923  6785  6785 I Feature : [Lifetracker]Device Number: 3
08-23 12:27:03.924  6785  6785 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
08-23 12:27:03.924  2035  2035 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-23 12:27:03.952  1037  1924 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=6822 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-23 12:27:03.956  3821  3836 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-23 12:27:03.958  3821  4464 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-23 12:27:03.964  1907  1907 D ActionManagerService: notifyUserLog: 1000001
08-23 12:27:03.964  3821  4470 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-23 12:27:03.965  3821  4470 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
,08-23 12:27:03.967  1907  1907 D ActionManagerService: notifyUserLog: 1000001
08-23 12:27:03.968  3821  4470 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-23 12:27:03.968  3821  4470 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-23 12:27:03.968  3821  4470 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-23 12:27:03.968  3821  4470 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-23 12:27:03.969  3821  3836 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-23 12:27:03.972  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-23 12:27:03.972  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-23 12:27:03.974  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-23 12:27:03.974  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-23 12:27:03.976  2035  2035 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-23 12:27:03.976  2035  2035 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/0/userguide2.html?id=guide_1111111111116_1471602815280&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
,08-23 12:27:03.981  1037  1924 I ActivityManager: Killing 6372:com.google.android.partnersetup/u0a8 (adj 15): empty #17
08-23 12:27:03.993  6822  6822 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-23 12:27:03.993  6822  6822 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-23 12:27:03.993  6822  6822 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-23 12:27:03.994  6822  6822 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
,08-23 12:27:03.994  6822  6822 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-23 12:27:03.995  6822  6822 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-23 12:27:04.045  1037  2034 W libprocessgroup: failed to open /acct/uid_10008/pid_6372/cgroup.procs: No such file or directory
,08-23 12:27:04.082  6822  6822 D PackageIntentReceiver: Not supported Hotkey customization function 
,08-23 12:27:04.088  6822  6822 D HideNavigationAppsReceiver: Receive package name : com.test.thalitest, replacing=false, action=android.intent.action.PACKAGE_REMOVED
08-23 12:27:04.088  6822  6822 D HideNavigationAppsReceiver: replacing : false
08-23 12:27:04.090  6822  6822 D HideNavigationAppsReceiver: Delete mPackageMame : com.test.thalitest
08-23 12:27:04.092  6822  6822 D ButtonCombinationReceiver: Receive package name : com.test.thalitest
08-23 12:27:04.092  6822  6822 D ButtonCombinationReceiver: replacing : false
,08-23 12:27:04.099  1037  1924 I ActivityManager: Killing 6459:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-23 12:27:04.155  1037  2034 W libprocessgroup: failed to open /acct/uid_10061/pid_6459/cgroup.procs: No such file or directory
,08-23 12:27:04.160  4583  6841 I UpdateIcingCorporaServi: Updating corpora: APPS=com.test.thalitest, CONTACTS=MAYBE
08-23 12:27:04.184  1037  1578 V SIM_STK : Menu title from STK is T-Mobile
,08-23 12:27:04.189  1037  1053 I ActivityManager: Start proc com.google.android.apps.docs for broadcast com.google.android.apps.docs/.receivers.AppPackageAddRemoveReceiver: pid=6842 uid=10061 gids={50061, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-23 12:27:04.198  4583  6841 E SQLiteLog: (3850) statement aborts at 1: [BEGIN EXCLUSIVE;] disk I/O error
,--------- beginning of crash
08-23 12:27:04.201  4583  6841 E AndroidRuntime: FATAL EXCEPTION: IntentService[UpdateCorporaService]
08-23 12:27:04.201  4583  6841 E AndroidRuntime: Process: com.google.android.googlequicksearchbox:search, PID: 4583
08-23 12:27:04.201  4583  6841 E AndroidRuntime: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 3850)
08-23 12:27:04.201  4583  6841 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.nativeExecute(Native Method)
08-23 12:27:04.201  4583  6841 E AndroidRuntime: 	at android.database.sqlite.SQLiteConnection.execute(SQLiteConnection.java:560)
08-23 12:27:04.201  4583  6841 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransactionUnchecked(SQLiteSession.java:323)
08-23 12:27:04.201  4583  6841 E AndroidRuntime: 	at android.database.sqlite.SQLiteSession.beginTransaction(SQLiteSession.java:298)
08-23 12:27:04.201  4583  6841 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:505)
08-23 12:27:04.201  4583  6841 E AndroidRuntime: 	at android.database.sqlite.SQLiteDatabase.beginTransaction(SQLiteDatabase.java:416)
08-23 12:27:04.201  4583  6841 E AndroidRuntime: 	at csx.d(PG:186)
08-23 12:27:04.201  4583  6841 E AndroidRuntime: 	at cun.g(PG:594)
08-23 12:27:04.201  4583  6841 E AndroidRuntime: 	at com.google.android.search.core.icingsync.InternalIcingCorporaProvider.update(PG:301)
08-23 12:27:04.201  4583  6841 E AndroidRuntime: 	at android.content.ContentProvider$Transport.update(ContentProvider.java:328)
08-23 12:27:04.201  4583  6841 E AndroidRuntime: 	at android.content.ContentResolver.update(ContentResolver.java:1349)
08-23 12:27:04.201  4583  6841 E AndroidRuntime: 	at cuw.Tg(PG:368)
08-23 12:27:04.201  4583  6841 E AndroidRuntime: 	at cuy.ub(PG:301)
08-23 12:27:04.201  4583  6841 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.a(PG:268)
08-23 12:27:04.201  4583  6841 E AndroidRuntime: 	at com.google.android.search.core.icingsync.UpdateIcingCorporaService.onHandleIntent(PG:186)
08-23 12:27:04.201  4583  6841 E AndroidRuntime: 	at android.app.IntentService$ServiceHandler.handleMessage(IntentService.java:65)
08-23 12:27:04.201  4583  6841 E AndroidRuntime: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:27:04.201  4583  6841 E AndroidRuntime: 	at android.os.Looper.loop(Looper.java:135)
08-23 12:27:04.201  4583  6841 E AndroidRuntime: 	at android.os.HandlerThread.run(HandlerThread.java:61)
08-23 12:27:04.204  4583  6841 I Process : Sending signal. PID: 4583 SIG: 9
08-23 12:27:04.206  1037  6855 E DropBoxManagerService: Can't write: system_app_crash
08-23 12:27:04.206  1037  6855 E DropBoxManagerService: java.io.FileNotFoundException: /data/system/dropbox/drop112.tmp: open failed: EROFS (Read-only file system)
08-23 12:27:04.206  1037  6855 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:456)
08-23 12:27:04.206  1037  6855 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:87)
08-23 12:27:04.206  1037  6855 E DropBoxManagerService: 	at java.io.FileOutputStream.<init>(FileOutputStream.java:72)
08-23 12:27:04.206  1037  6855 E DropBoxManagerService: 	at com.android.server.DropBoxManagerService.add(DropBoxManagerService.java:211)
08-23 12:27:04.206  1037  6855 E DropBoxManagerService: 	at android.os.DropBoxManager.addText(DropBoxManager.java:269)
08-23 12:27:04.206  1037  6855 E DropBoxManagerService: 	at com.android.server.am.ActivityManagerService$20.run(ActivityManagerService.java:12437)
08-23 12:27:04.206  1037  6855 E DropBoxManagerService: Caused by: android.system.ErrnoException: open failed: EROFS (Read-only file system)
08-23 12:27:04.206  1037  6855 E DropBoxManagerService: 	at libcore.io.Posix.open(Native Method)
08-23 12:27:04.206  1037  6855 E DropBoxManagerService: 	at libcore.io.BlockGuardOs.open(BlockGuardOs.java:186)
08-23 12:27:04.206  1037  6855 E DropBoxManagerService: 	at libcore.io.IoBridge.open(IoBridge.java:442)
08-23 12:27,:04.206  1037  6855 E DropBoxManagerService: 	... 5 more
08-23 12:27:04.225  1037  1547 D WifiService: Client connection lost with reason: 4
08-23 12:27:04.244  2035  2859 I GBoardtInterface: exportHTML()
,08-23 12:27:04.253  4477  4504 E SQLiteDatabase: Error inserting f004=20 f005=4583 f002=1471948024220 f003= f006=-1
08-23 12:27:04.253  4477  4504 E SQLiteDatabase: android.database.sqlite.SQLiteDiskIOException: disk I/O error (code 778)
08-23 12:27:04.253  4477  4504 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeExecuteForLastInsertedRowId(Native Method)
08-23 12:27:04.253  4477  4504 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.executeForLastInsertedRowId(SQLiteConnection.java:787)
08-23 12:27:04.253  4477  4504 E SQLiteDatabase: 	at android.database.sqlite.SQLiteSession.executeForLastInsertedRowId(SQLiteSession.java:926)
08-23 12:27:04.253  4477  4504 E SQLiteDatabase: 	at android.database.sqlite.SQLiteStatement.executeInsert(SQLiteStatement.java:86)
08-23 12:27:04.253  4477  4504 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insertWithOnConflict(SQLiteDatabase.java:1572)
08-23 12:27:04.253  4477  4504 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.insert(SQLiteDatabase.java:1442)
08-23 12:27:04.253  4477  4504 E SQLiteDatabase: 	at com.lge.mlt.MptCommonLogProvider.insert(MptCommonLogProvider.java:706)
08-23 12:27:04.253  4477  4504 E SQLiteDatabase: 	at android.content.ContentProvider$Transport.insert(ContentProvider.java:238)
08-23 12:27:04.253  4477  4504 E SQLiteDatabase: 	at android.content.ContentResolver.insert(ContentResolver.java:1223)
08-23 12:27:04.253  4477  4504 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.insertProcessInfoLog(MltMonitorService.java:2584)
08-23 12:27:04.253  4477  4504 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService.access$2700(MltMonitorService.java:38)
08-23 12:27:04.253  4477  4504 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager$1.handleMessage(MltMonitorService.java:3409)
08-23 12:27:04.253  4477  4504 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-23 12:27:04.253  4477  4504 E SQLiteDatabase: 	at android.os.Looper.loop(Looper.java:135)
08-23 12:27:04.253  4477  4504 E SQLiteDatabase: 	at com.lge.mlt.MltMonitorService$DbFlushManager.run(MltMonitorService.java:3518)
08-23 12:27:04.270  2035  2859 I GBoardtInterface: exportHTML()

```
