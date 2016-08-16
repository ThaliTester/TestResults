#### Test 81418577c9cdf39_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-16 11:35:00.071  1603  1603 D KeyguardUpdateMonitor: handleTimeUpdate
,08-16 11:35:28.517  6867  6867 D AndroidRuntime: 
08-16 11:35:28.517  6867  6867 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 11:35:28.524  6867  6867 D AndroidRuntime: CheckJNI is OFF
08-16 11:35:28.725  6867  6867 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-16 11:35:28.736  1036  1978 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 11:35:28.750  1943  1959 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-16 11:35:28.756  1036  1978 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-16 11:35:28.758  1036  1978 D ActivityManager: setTaskToReturnTo : TaskRecord{3ebe453 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 11:35:28.758  1036  1978 D ActivityManager: setTaskToReturnTo : TaskRecord{3ebe453 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 11:35:28.760  1036  1978 D WindowStateEx: AppWindowTokenEx init.. 
08-16 11:35:28.761   340   358 E GBMv2   : DFP En is all cleared set to be enabled
08-16 11:35:28.790  1036  1978 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6882 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-16 11:35:28.793  6867  6867 D AndroidRuntime: Shutting down VM
08-16 11:35:28.845  1943  4004 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-16 11:35:28.845  1943  4004 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3a05025c co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 11:35:28.846  1943  1960 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-16 11:35:28.846  1943  1960 D SplitWindowPolicy: topRunningActivity=ActivityInfo{2a023965 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 11:35:28.905  6882  6882 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
,08-16 11:35:29.018  6882  6882 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-16 11:35:29.026  6882  6882 I LibraryLoader: Loading: webviewchromium
08-16 11:35:29.029  6882  6882 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 5674-5677)
,08-16 11:35:29.031  6882  6882 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 11:35:29.053  6882  6882 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {27bcc46a}
,08-16 11:35:29.054  6882  6882 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 11:35:29.055  6882  6882 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 11:35:29.069  6882  6882 I BrowserStartupController: Initializing chromium process, renderers=0
08-16 11:35:29.070  6882  6882 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 11:35:29.082   322  1398 V AudioPolicyService: registerClient() client 0xb558a480, uid 10118
,08-16 11:35:29.083  6882  6882 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-16 11:35:29.084  6882  6882 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
08-16 11:35:29.084  6882  6882 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
08-16 11:35:29.089  1036  1118 D BluetoothManagerService: Message: 20
08-16 11:35:29.090  1036  1118 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@1d7c6645:true
08-16 11:35:29.106  6882  6882 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 11:35:29.106  6882  6882 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 11:35:29.106  6882  6882 I Adreno-EGL: Build Date: 12/12/14 금
08-16 11:35:29.106  6882  6882 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 11:35:29.106  6882  6882 I Adreno-EGL: Remote Branch: 
08-16 11:35:29.106  6882  6882 I Adreno-EGL: Local Patches: 
08-16 11:35:29.106  6882  6882 I Adreno-EGL: Reconstruct Branch: 
,08-16 11:35:29.193  6882  6916 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
08-16 11:35:29.195  6882  6882 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
,08-16 11:35:29.215  6882  6882 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 11:35:29.221  6882  6882 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-16 11:35:29.225  6882  6882 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-16 11:35:29.228  6882  6882 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-16 11:35:29.228  6882  6882 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
,08-16 11:35:29.244  6882  6882 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-16 11:35:29.252  6882  6882 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 11:35:29.252  6882  6882 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 11:35:29.292  6882  6928 D OpenGLRenderer: Render dirty regions requested: true
,08-16 11:35:29.292  6882  6928 I OpenGLRenderer: Initialized EGL, version 1.4
08-16 11:35:29.299  6882  6928 D OpenGLRenderer: Enabling debug mode 0
08-16 11:35:29.308  6882  6882 D Atlas   : Validating map...
,08-16 11:35:29.313  1036  2053 D SplitWindow: check instance of lgWin Window{2a526997 u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 11:35:29.356  6882  6926 D LgDataFeature: LgDataFeature() Constructor: none
08-16 11:35:29.357  6882  6926 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 11:35:29.457  1036  1119 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +613ms (total +695ms)
08-16 11:35:29.458  1036  1119 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{3633b190 u0 com.test.thalitest/.MainActivity t6} time:176107
,08-16 11:35:29.464  6882  6882 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@36201e41 time:176113
08-16 11:35:29.581  6882  6882 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-16 11:35:29.581  6882  6882 I chromium: 
,08-16 11:35:29.627  6882  6882 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 11:35:29.693  6882  6926 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-16 11:35:29.693  6882  6926 I chromium: 
,08-16 11:35:29.883  6882  6940 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435046912
,08-16 11:35:29.907  6882  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 11:35:29.907  6882  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 11:35:29.907  6882  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 11:35:29.907  6882  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 11:35:29.907  6882  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
,08-16 11:35:29.907  6882  6940 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1a71bf35 added. We now have 1 listener(s)
08-16 11:35:29.913  1036  1987 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:35:29.916  6882  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-16 11:35:29.917  6882  6940 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 11:35:29.919  6882  6940 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 11:35:29.919  6882  6940 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
,08-16 11:35:29.928  6882  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 11:35:29.928  6882  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 11:35:29.928  6882  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 11:35:29.928  6882  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-16 11:35:29.928  6882  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 11:35:29.928  6882  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 11:35:29.928  6882  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 11:35:29.928  6882  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 11:35:29.928  6882  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 11:35:29.928  6882  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 11:35:29.928  6882  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 11:35:29.928  6882  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 11:35:29.928  6882  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 11:35:29.928  6882  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-16 11:35:29.928  6882  6940 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3ebc4458 added. We now have 1 listener(s)
08-16 11:35:29.928  6882  6940 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 11:35:29.932  1036  1477 D WifiService: New client listening to asynchronous messages
,08-16 11:35:29.937  6882  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 11:35:29.937  6882  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-16 11:35:29.937  6882  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 11:35:29.937  6882  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
08-16 11:35:29.938  6882  6940 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
08-16 11:35:29.943  6882  6940 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 11:35:29.943  1036  2010 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 11:35:29.944  6882  6940 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,08-16 11:35:29.955  6882  6940 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 11:35:29.956  6882  6940 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 11:35:29.956  6882  6940 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 11:35:29.956  6882  6940 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 11:35:29.956  6882  6940 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 11:35:29.956  6882  6940 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 11:35:29.956  6882  6940 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 11:35:29.956  6882  6940 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 11:35:29.956  6882  6940 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 11:35:29.956  6882  6940 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 11:35:29.956  6882  6940 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 11:35:29.957  6882  6940 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 11:35:29.958  6882  6882 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 11:35:29.960  6882  6882 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 11:35:29.995  6882  6882 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 11:35:30.217   340   360 E GBMv2   : DFP En is all cleared set to be enabled
08-16 11:35:30.217   340   360 E GBMv2   : Set value is all cleared set the max
,08-16 11:35:30.217   340   360 I GBMv2   : DFP Enabled. Ignore VFP set
08-16 11:35:30.886  6882  6943 W jxcore-log: Initializing JXcore engine
08-16 11:35:30.886  6882  6943 W jxcore-log: JXcore engine is ready
,08-16 11:35:30.918  6943  6943 W Thread-782: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[10280]" dev="sockfs" ino=10280 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-16 11:35:30.918  6943  6943 W Thread-782: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
,08-16 11:35:30.918  6943  6943 W Thread-782: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[8886]" dev="sockfs" ino=8886 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-16 11:35:30.918  6943  6943 W Thread-782: type=1400 audit(0.0:167): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-16 11:35:30.940  6882  6943 W jxcore-log: Starting JXcore engine
08-16 11:35:30.918  6943  6943 W Thread-782: type=1400 audit(0.0:168): avc: denied { ioctl } for path="socket:[31714]" dev="sockfs" ino=31714 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-16 11:35:31.099  6882  6943 W jxcore-log: Platform android
08-16 11:35:31.099  6882  6943 W jxcore-log: 
08-16 11:35:31.099  6882  6943 W jxcore-log: Process ARCH arm
08-16 11:35:31.099  6882  6943 W jxcore-log: 
,08-16 11:35:31.428  6882  6943 I jxcore-log: JXcore Cordova bridge is ready!
08-16 11:35:31.428  6882  6943 I jxcore-log: 
,08-16 11:35:31.429  6882  6943 W jxcore-log: JXcore engine is started
,08-16 11:35:31.440  6882  6940 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
08-16 11:35:31.447  6882  6882 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)

```
