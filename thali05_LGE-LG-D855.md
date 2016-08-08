#### Test 79689775d0c6cb6_thali05_LGE-LG-D855 Logs


```
--------- beginning of main
08-08 16:37:00.077  1604  1604 D KeyguardUpdateMonitor: handleTimeUpdate
,08-08 16:37:39.486  6645  6645 D AndroidRuntime: 
08-08 16:37:39.486  6645  6645 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-08 16:37:39.492  6645  6645 D AndroidRuntime: CheckJNI is OFF
08-08 16:37:39.616  6645  6645 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-08 16:37:39.621  1033  1923 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-08 16:37:39.631  1942  1958 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-08 16:37:39.634  1033  1923 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-08 16:37:39.635  1033  1923 D ActivityManager: setTaskToReturnTo : TaskRecord{22248c7f #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-08 16:37:39.635  1033  1923 D ActivityManager: setTaskToReturnTo : TaskRecord{22248c7f #40 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-08 16:37:39.636  1033  1923 D WindowStateEx: AppWindowTokenEx init.. 
08-08 16:37:39.637   342   370 E GBMv2   : DFP En is all cleared set to be enabled
08-08 16:37:39.656  1033  1923 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6660 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-08 16:37:39.658  6645  6645 D AndroidRuntime: Shutting down VM
08-08 16:37:39.720  1942  1959 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-08 16:37:39.720  1942  1959 D SplitWindowPolicy: topRunningActivity=ActivityInfo{35eab884 co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-08 16:37:39.723  1942  3946 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-08 16:37:39.724  1942  3946 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3340f86d co.....MainActivity}, taskId=40, activityType=0, bIsSplit=false
08-08 16:37:39.762  6660  6660 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-08 16:37:39.818  6660  6660 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
08-08 16:37:39.824  6660  6660 I LibraryLoader: Loading: webviewchromium
08-08 16:37:39.826  6660  6660 I LibraryLoader: Time to load native libraries: 2 ms (timestamps 4046-4048)
08-08 16:37:39.826  6660  6660 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-08 16:37:39.840  6660  6660 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {7ada4d2}
08-08 16:37:39.841  6660  6660 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-08 16:37:39.842  6660  6660 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-08 16:37:39.850  6660  6660 I BrowserStartupController: Initializing chromium process, renderers=0
08-08 16:37:39.850  6660  6660 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-08 16:37:39.864  6660  6660 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-08 16:37:39.864  6660  6660 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-08 16:37:39.864  6660  6660 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-08 16:37:39.882  6660  6660 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-08 16:37:39.882  6660  6660 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-08 16:37:39.882  6660  6660 I Adreno-EGL: Build Date: 12/12/14 금
08-08 16:37:39.882  6660  6660 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-08 16:37:39.882  6660  6660 I Adreno-EGL: Remote Branch: 
08-08 16:37:39.882  6660  6660 I Adreno-EGL: Local Patches: 
08-08 16:37:39.882  6660  6660 I Adreno-EGL: Reconstruct Branch: 
08-08 16:37:39.889   327  2153 V AudioPolicyService: registerClient() client 0xb57c0080, uid 10118
08-08 16:37:39.895  1033  1095 D BluetoothManagerService: Message: 20
08-08 16:37:39.895  1033  1095 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@d8eed11:true
08-08 16:37:39.982  6660  6707 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-08 16:37:39.984  6660  6660 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-08 16:37:40.005  6660  6660 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-08 16:37:40.012  6660  6660 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-08 16:37:40.023  6660  6660 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-08 16:37:40.030  6660  6660 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-08 16:37:40.031  6660  6660 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-08 16:37:40.052  6660  6660 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
08-08 16:37:40.061  6660  6660 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-08 16:37:40.061  6660  6660 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-08 16:37:40.110  6660  6726 D OpenGLRenderer: Render dirty regions requested: true
08-08 16:37:40.111  6660  6726 I OpenGLRenderer: Initialized EGL, version 1.4
08-08 16:37:40.128  6660  6726 D OpenGLRenderer: Enabling debug mode 0
08-08 16:37:40.137  6660  6660 D Atlas   : Validating map...
08-08 16:37:40.141  1033  1995 D SplitWindow: check instance of lgWin Window{299cd03 u0 com.test.thalitest/com.test.thalitest.MainActivity}
08-08 16:37:40.163  6660  6720 D LgDataFeature: LgDataFeature() Constructor: none
08-08 16:37:40.163  6660  6720 D LgDataFeature: LgDataFeature() Constructor Done, null
08-08 16:37:40.273  1033  1096 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +555ms (total +635ms)
08-08 16:37:40.273  1033  1096 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1598b44c u0 com.test.thalitest/.MainActivity t40} time:314496
08-08 16:37:40.280  6660  6660 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@103c99c9 time:314502
08-08 16:37:40.388  6660  6660 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
08-08 16:37:40.448  6660  6720 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-08 16:37:40.448  6660  6720 I chromium: 
08-08 16:37:40.580  6660  6736 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435197824
08-08 16:37:40.594  6660  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-08 16:37:40.594  6660  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-08 16:37:40.594  6660  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-08 16:37:40.594  6660  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-08 16:37:40.594  6660  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-08 16:37:40.595  6660  6736 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@d26e43d added. We now have 1 listener(s)
08-08 16:37:40.601  1033  1975 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-08 16:37:40.604  6660  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-08 16:37:40.605  6660  6736 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-08 16:37:40.606  6660  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-08 16:37:40.607  6660  6736 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-08 16:37:40.611  6660  6660 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-08 16:37:40.611  6660  6660 I chromium: 
08-08 16:37:40.619  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-08 16:37:40.619  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-08 16:37:40.619  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-08 16:37:40.619  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-08 16:37:40.619  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-08 16:37:40.619  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-08 16:37:40.619  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-08 16:37:40.619  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-08 16:37:40.619  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-08 16:37:40.619  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-08 16:37:40.619  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-08 16:37:40.619  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-08 16:37:40.619  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-08 16:37:40.619  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-08 16:37:40.619  6660  6736 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@34e95300 added. We now have 1 listener(s)
08-08 16:37:40.619  6660  6736 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-08 16:37:40.627  1033  1544 D WifiService: New client listening to asynchronous messages
08-08 16:37:40.632  6660  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-08 16:37:40.632  6660  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-08 16:37:40.634  6660  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-08 16:37:40.634  6660  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-08 16:37:40.634  6660  6736 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-08 16:37:40.638  6660  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-08 16:37:40.638  1033  1575 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-08 16:37:40.641  6660  6736 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
08-08 16:37:40.653  6660  6736 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-08 16:37:40.653  6660  6736 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-08 16:37:40.653  6660  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-08 16:37:40.653  6660  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-08 16:37:40.653  6660  6736 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-08 16:37:40.653  6660  6736 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-08 16:37:40.653  6660  6736 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-08 16:37:40.653  6660  6736 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-08 16:37:40.653  6660  6736 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-08 16:37:40.654  6660  6736 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-08 16:37:40.654  6660  6736 D io.jxcore.node.ConnectivityMonitor: start: OK
08-08 16:37:40.657  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 16:37:40.659  6660  6660 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-08 16:37:40.660  6660  6736 I io.jxcore.node.LifeCycleMonitor: start: OK
08-08 16:37:40.698  6660  6660 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-08 16:37:41.564   342   372 E GBMv2   : DFP En is all cleared set to be enabled
08-08 16:37:41.564   342   372 E GBMv2   : Set value is all cleared set the max
08-08 16:37:41.564   342   372 I GBMv2   : DFP Enabled. Ignore VFP set
,08-08 16:37:41.583  6660  6739 W jxcore-log: Initializing JXcore engine
08-08 16:37:41.583  6660  6739 W jxcore-log: JXcore engine is ready
,08-08 16:37:41.613  6739  6739 W Thread-768: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7449]" dev="sockfs" ino=7449 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-08 16:37:41.613  6739  6739 W Thread-768: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-08 16:37:41.613  6739  6739 W Thread-768: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[7584]" dev="sockfs" ino=7584 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-08 16:37:41.613  6739  6739 W Thread-768: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-08 16:37:41.613  6739  6739 W Thread-768: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31993]" dev="sockfs" ino=31993 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-08 16:37:41.633  6660  6739 W jxcore-log: Starting JXcore engine
,08-08 16:37:41.708  6660  6739 W jxcore-log: Platform android
08-08 16:37:41.708  6660  6739 W jxcore-log: 
08-08 16:37:41.708  6660  6739 W jxcore-log: Process ARCH arm
08-08 16:37:41.708  6660  6739 W jxcore-log: 
,08-08 16:37:41.925  6660  6739 I jxcore-log: JXcore Cordova bridge is ready!
08-08 16:37:41.925  6660  6739 I jxcore-log: 
08-08 16:37:41.926  6660  6739 W jxcore-log: JXcore engine is started
,08-08 16:37:41.938  6660  6736 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-08 16:37:41.946  6660  6660 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)

```
