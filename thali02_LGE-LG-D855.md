#### Test 821470465fdde63_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-22 10:51:00.100  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
08-22 10:51:00.110  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
08-22 10:51:00.110  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
08-22 10:51:00.114  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
08-22 10:51:00.114  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
,08-22 10:51:01.921  6649  6649 D AndroidRuntime: 
08-22 10:51:01.921  6649  6649 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-22 10:51:01.926  6649  6649 D AndroidRuntime: CheckJNI is OFF
08-22 10:51:02.050  6649  6649 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-22 10:51:02.055  1034  1983 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-22 10:51:02.064  1928  3977 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-22 10:51:02.068  1034  1983 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-22 10:51:02.069  1034  1983 D ActivityManager: setTaskToReturnTo : TaskRecord{12603304 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-22 10:51:02.069  1034  1983 D ActivityManager: setTaskToReturnTo : TaskRecord{12603304 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-22 10:51:02.071  1034  1983 D WindowStateEx: AppWindowTokenEx init.. 
08-22 10:51:02.071   335   339 E GBMv2   : DFP En is all cleared set to be enabled
08-22 10:51:02.103  1034  1983 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6664 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-22 10:51:02.110  6649  6649 D AndroidRuntime: Shutting down VM
08-22 10:51:02.155  1928  3977 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-22 10:51:02.155  1928  3977 D SplitWindowPolicy: topRunningActivity=ActivityInfo{39d4b46b co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-22 10:51:02.157  1928  3982 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-22 10:51:02.158  1928  3982 D SplitWindowPolicy: topRunningActivity=ActivityInfo{244b9bc8 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-22 10:51:02.215  6664  6664 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-22 10:51:02.313  6664  6664 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-22 10:51:02.322  6664  6664 I LibraryLoader: Loading: webviewchromium
08-22 10:51:02.325  6664  6664 I LibraryLoader: Time to load native libraries: 4 ms (timestamps 8969-8973)
08-22 10:51:02.326  6664  6664 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-22 10:51:02.342  6664  6664 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3f94ac51}
,08-22 10:51:02.343  6664  6664 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-22 10:51:02.344  6664  6664 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-22 10:51:02.354  6664  6664 I BrowserStartupController: Initializing chromium process, renderers=0
08-22 10:51:02.355  6664  6664 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 10:51:02.369  6664  6664 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-22 10:51:02.369  6664  6664 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-22 10:51:02.370  6664  6664 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-22 10:51:02.374   314   314 V AudioPolicyService: registerClient() client 0xb1007a40, uid 10118
08-22 10:51:02.383  6664  6664 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-22 10:51:02.383  6664  6664 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-22 10:51:02.383  6664  6664 I Adreno-EGL: Build Date: 12/12/14 금
08-22 10:51:02.383  6664  6664 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-22 10:51:02.383  6664  6664 I Adreno-EGL: Remote Branch: 
08-22 10:51:02.383  6664  6664 I Adreno-EGL: Local Patches: 
08-22 10:51:02.383  6664  6664 I Adreno-EGL: Reconstruct Branch: 
,08-22 10:51:02.387  1034  1105 D BluetoothManagerService: Message: 20
08-22 10:51:02.387  1034  1105 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@3677176e:true
08-22 10:51:02.472  6664  6704 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-22 10:51:02.475  6664  6664 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-22 10:51:02.502  6664  6664 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 10:51:02.507  6664  6664 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-22 10:51:02.511  6664  6664 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-22 10:51:02.515  6664  6664 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-22 10:51:02.515  6664  6664 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-22 10:51:02.532  6664  6664 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-22 10:51:02.540  6664  6664 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 10:51:02.540  6664  6664 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-22 10:51:02.643  6664  6714 D LgDataFeature: LgDataFeature() Constructor: none
08-22 10:51:02.643  6664  6714 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-22 10:51:02.653  1034  1101 W ActivityManager: Activity pause timeout for ActivityRecord{1b9920ed u0 com.test.thalitest/.MainActivity t6}
08-22 10:51:02.720  1034  1927 I art     : Explicit concurrent mark sweep GC freed 28554(1267KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.306ms total 154.269ms
,08-22 10:51:02.724  6664  6720 D OpenGLRenderer: Render dirty regions requested: true
08-22 10:51:02.724  6664  6720 I OpenGLRenderer: Initialized EGL, version 1.4
08-22 10:51:02.728  6664  6720 D OpenGLRenderer: Enabling debug mode 0
08-22 10:51:02.735  6664  6664 D Atlas   : Validating map...
,08-22 10:51:02.739  1034  1949 D SplitWindow: check instance of lgWin Window{23cde3b8 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-22 10:51:02.834  1034  1106 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +680ms (total +761ms)
08-22 10:51:02.834  1034  1106 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1b9920ed u0 com.test.thalitest/.MainActivity t6} time:169482
,08-22 10:51:02.849  6664  6664 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@12c07354 time:169497
,08-22 10:51:02.931  6664  6664 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-22 10:51:02.961  6664  6664 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-22 10:51:02.961  6664  6664 I chromium: 
,08-22 10:51:02.998  6664  6714 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-22 10:51:02.998  6664  6714 I chromium: 
,08-22 10:51:03.131  6664  6729 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435159040
,08-22 10:51:03.146  6664  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-22 10:51:03.146  6664  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-22 10:51:03.146  6664  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-22 10:51:03.146  6664  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-22 10:51:03.146  6664  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-22 10:51:03.147  6664  6729 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@2fde97d8 added. We now have 1 listener(s)
08-22 10:51:03.153  1034  1963 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 10:51:03.155  6664  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
,08-22 10:51:03.157  6664  6729 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-22 10:51:03.158  6664  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
,08-22 10:51:03.158  6664  6729 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-22 10:51:03.166  6664  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-22 10:51:03.166  6664  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-22 10:51:03.166  6664  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-22 10:51:03.166  6664  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-22 10:51:03.166  6664  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-22 10:51:03.166  6664  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-22 10:51:03.166  6664  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-22 10:51:03.166  6664  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-22 10:51:03.166  6664  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-22 10:51:03.166  6664  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-22 10:51:03.166  6664  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-22 10:51:03.166  6664  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-22 10:51:03.166  6664  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-22 10:51:03.166  6664  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-22 10:51:03.166  6664  6729 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@1b602397 added. We now have 1 listener(s)
08-22 10:51:03.167  6664  6729 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-22 10:51:03.171  1034  1531 D WifiService: New client listening to asynchronous messages
,08-22 10:51:03.175  6664  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-22 10:51:03.175  6664  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-22 10:51:03.175  6664  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-22 10:51:03.175  6664  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-22 10:51:03.175  6664  6729 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-22 10:51:03.179  6664  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-22 10:51:03.179  1034  1873 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-22 10:51:03.180  6664  6729 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-22 10:51:03.188  6664  6729 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-22 10:51:03.189  6664  6729 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-22 10:51:03.189  6664  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-22 10:51:03.189  6664  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-22 10:51:03.189  6664  6729 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-22 10:51:03.189  6664  6729 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-22 10:51:03.189  6664  6729 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-22 10:51:03.189  6664  6729 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-22 10:51:03.189  6664  6729 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-22 10:51:03.189  6664  6729 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-22 10:51:03.189  6664  6729 D io.jxcore.node.ConnectivityMonitor: start: OK
08-22 10:51:03.192  6664  6664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:51:03.194  6664  6664 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-22 10:51:03.194  6664  6729 I io.jxcore.node.LifeCycleMonitor: start: OK
08-22 10:51:03.235  6664  6664 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-22 10:51:03.261   335   341 E GBMv2   : DFP En is all cleared set to be enabled
08-22 10:51:03.261   335   341 E GBMv2   : Set value is all cleared set the max
08-22 10:51:03.261   335   341 I GBMv2   : DFP Enabled. Ignore VFP set
,08-22 10:51:04.309  6664  6732 W jxcore-log: Initializing JXcore engine
08-22 10:51:04.309  6664  6732 W jxcore-log: JXcore engine is ready
,08-22 10:51:04.346  6732  6732 W Thread-762: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[10254]" dev="sockfs" ino=10254 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-22 10:51:04.346  6732  6732 W Thread-762: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-22 10:51:04.346  6732  6732 W Thread-762: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7565]" dev="sockfs" ino=7565 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-22 10:51:04.346  6732  6732 W Thread-762: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
,08-22 10:51:04.346  6732  6732 W Thread-762: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[31481]" dev="sockfs" ino=31481 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-22 10:51:04.372  6664  6732 W jxcore-log: Starting JXcore engine
08-22 10:51:04.534  6664  6732 W jxcore-log: Platform android
08-22 10:51:04.534  6664  6732 W jxcore-log: 
08-22 10:51:04.534  6664  6732 W jxcore-log: Process ARCH arm
08-22 10:51:04.534  6664  6732 W jxcore-log: 
,08-22 10:51:04.815  6664  6732 I jxcore-log: JXcore Cordova bridge is ready!
08-22 10:51:04.815  6664  6732 I jxcore-log: 
08-22 10:51:04.816  6664  6732 W jxcore-log: JXcore engine is started
,08-22 10:51:04.831  6664  6729 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION

```
