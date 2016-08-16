#### Test 80761374e4349a7_thali02_LGE-LG-D855 Logs


```
--------- beginning of main
08-16 15:25:31.953  2173  2173 I ConfigService: onDestroy
,08-16 15:25:36.426  6955  6955 D AndroidRuntime: 
08-16 15:25:36.426  6955  6955 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
08-16 15:25:36.429  6955  6955 D AndroidRuntime: CheckJNI is OFF
08-16 15:25:36.554  6955  6955 D AndroidRuntime: Calling main entry com.android.commands.am.Am
--------- beginning of system
08-16 15:25:36.559  1044  1977 I ActivityManager: START u0 {flg=0x10000000 cmp=com.test.thalitest/.MainActivity} from uid 2000 on display 0
08-16 15:25:36.570  1927  4381 V SplitWindowPolicy: checkScreen => return. sourceIntent is null or not support SplitWindow component: ComponentInfo{co..../co.....MainActivity}
08-16 15:25:36.573  1044  1977 D SplitInfo: new ActivitySplitInfo : ActivitySplitInfo [screenZone=0/ flag=0/ state=NATIVE]
08-16 15:25:36.575  1044  1977 D ActivityManager: setTaskToReturnTo : TaskRecord{21da03e9 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 15:25:36.575  1044  1977 D ActivityManager: setTaskToReturnTo : TaskRecord{21da03e9 #6 A=com.test.thalitest U=0 sz=0} / mTaskToReturnTo = 1
08-16 15:25:36.576  1044  1977 D WindowStateEx: AppWindowTokenEx init.. 
08-16 15:25:36.576   347   373 E GBMv2   : DFP En is all cleared set to be enabled
08-16 15:25:36.617  1044  1977 I ActivityManager: Start proc com.test.thalitest for activity com.test.thalitest/.MainActivity: pid=6974 uid=10118 gids={50118, 9997, 3003, 3001, 3002, 1028, 1015} abi=armeabi-v7a
08-16 15:25:36.619  6955  6955 D AndroidRuntime: Shutting down VM
08-16 15:25:36.656  1927  1944 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=1, isScreenFull=true
08-16 15:25:36.656  1927  1944 D SplitWindowPolicy: topRunningActivity=ActivityInfo{37ea3680 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 15:25:36.657  1927  1943 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=1, isScreenFull=true
08-16 15:25:36.658  1927  1943 D SplitWindowPolicy: topRunningActivity=ActivityInfo{125464b9 co.....MainActivity}, taskId=6, activityType=0, bIsSplit=false
08-16 15:25:36.727  6974  6974 D ContextHelper: convertTheme. context->name=com.test.thalitest themeResourceId=16974121
08-16 15:25:36.795  6974  6974 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-16 15:25:36.803  6974  6974 I LibraryLoader: Loading: webviewchromium
08-16 15:25:36.806  6974  6974 I LibraryLoader: Time to load native libraries: 3 ms (timestamps 7828-7831)
08-16 15:25:36.806  6974  6974 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 15:25:36.825  6974  6974 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {37a4402e}
08-16 15:25:36.828  6974  6974 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 15:25:36.832  6974  6974 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 15:25:36.856  6974  6974 I BrowserStartupController: Initializing chromium process, renderers=0
,08-16 15:25:36.858  6974  6974 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 15:25:36.867  6974  6974 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-16 15:25:36.868  6974  6974 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=32 off=46780 len=2953
,08-16 15:25:36.868  6974  6974 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:33 off:229536 len:643667
,08-16 15:25:36.872   326   326 V AudioPolicyService: registerClient() client 0xb558af20, uid 10118
08-16 15:25:36.878  1044  1119 D BluetoothManagerService: Message: 20
08-16 15:25:36.878  1044  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@2dbd192b:true
,08-16 15:25:36.887  6974  6974 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 15:25:36.887  6974  6974 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 15:25:36.887  6974  6974 I Adreno-EGL: Build Date: 12/12/14 금
08-16 15:25:36.887  6974  6974 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 15:25:36.887  6974  6974 I Adreno-EGL: Remote Branch: 
08-16 15:25:36.887  6974  6974 I Adreno-EGL: Local Patches: 
08-16 15:25:36.887  6974  6974 I Adreno-EGL: Reconstruct Branch: 
08-16 15:25:36.989  6974  7005 W chromium: [WARNING:proxy_service.cc(901)] PAC support disabled because there is no system implementation
,08-16 15:25:36.994  6974  6974 W chromium: [WARNING:data_reduction_proxy_settings.cc(403)] SPDY proxy OFF at startup
08-16 15:25:37.009  6974  6974 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 15:25:37.013  6974  6974 W AwContents: onDetachedFromWindow called when already detached. Ignoring
08-16 15:25:37.017  6974  6974 I PhoneWindow: [generateLayout] setColorNavigationBar => color=0x ff000001
08-16 15:25:37.019  6974  6974 D PhoneWindowEx: [LMJ][PWEx][generateLayout] setNavigationBarColor2 : colors=0xfff5f5f5
08-16 15:25:37.019  6974  6974 I PhoneWindow: [setNavigationBarColor2] color=0x fff5f5f5
08-16 15:25:37.032  6974  6974 D SystemWebViewEngine: CordovaWebView is running on device made by: LGE
,08-16 15:25:37.038  6974  6974 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 15:25:37.038  6974  6974 W art     : Attempt to remove local handle scope entry from IRT, ignoring
,08-16 15:25:37.072  6974  7017 D OpenGLRenderer: Render dirty regions requested: true
08-16 15:25:37.072  6974  7017 I OpenGLRenderer: Initialized EGL, version 1.4
08-16 15:25:37.077  6974  7017 D OpenGLRenderer: Enabling debug mode 0
,08-16 15:25:37.087  6974  6974 D Atlas   : Validating map...
08-16 15:25:37.091  1044  1981 D SplitWindow: check instance of lgWin Window{10e9eecd u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 15:25:37.133  6974  7015 D LgDataFeature: LgDataFeature() Constructor: none
08-16 15:25:37.134  6974  7015 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 15:25:37.204  1044  1120 I ActivityManager: Displayed com.test.thalitest/.MainActivity: +549ms (total +626ms)
08-16 15:25:37.204  6974  6974 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@13bc1cd5 time:298230
08-16 15:25:37.205  1044  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{63ad86e u0 com.test.thalitest/.MainActivity t6} time:298231
,08-16 15:25:37.326  6974  6974 I chromium: [INFO:SkUtilsArm.cpp(179)] Device supports ARM NEON instructions!
08-16 15:25:37.326  6974  6974 I chromium: 
,08-16 15:25:37.363  6974  6974 D JsMessageQueue: Set native->JS mode to OnlineEventsBridgeMode
,08-16 15:25:37.535  6974  7028 D jxcore_app_log: JniHelper::setJavaVM(0xb487c280), pthread_self() = -1435137024
,08-16 15:25:37.553  6974  7028 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: 
08-16 15:25:37.553  6974  7028 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Connection timeout in milliseconds: 15000
08-16 15:25:37.553  6974  7028 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Insecure RFCOMM socket port number: -1
08-16 15:25:37.553  6974  7028 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Maximum number of connection attempt retries: 0
08-16 15:25:37.553  6974  7028 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings:     - Handshake required: true
08-16 15:25:37.554  6974  7028 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c853989 added. We now have 1 listener(s)
08-16 15:25:37.560  1044  1916 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 15:25:37.565  6974  7028 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBluetoothMacAddress: 58:3F:54:73:BA:17
08-16 15:25:37.570  6974  7028 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 15:25:37.571  6974  7028 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 15:25:37.572  6974  7028 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 15:25:37.581  6974  7028 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: 
08-16 15:25:37.581  6974  7028 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Automate Bluetooth MAC address resolution: true
08-16 15:25:37.581  6974  7028 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Provide Bluetooth MAC address timeout in milliseconds: 40000
08-16 15:25:37.581  6974  7028 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Bluetooth MAC address: 58:3F:54:73:BA:17
08-16 15:25:37.581  6974  7028 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Discovery mode: BLE
08-16 15:25:37.581  6974  7028 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Peer expiration time in milliseconds: 60000
08-16 15:25:37.581  6974  7028 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Manufacturer ID: 76
08-16 15:25:37.581  6974  7028 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad length and type: 533
08-16 15:25:37.581  6974  7028 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Beacon ad extra information: 0
08-16 15:25:37.581  6974  7028 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertisement data type: DO_NOT_CARE
08-16 15:25:37.581  6974  7028 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise mode: 1
08-16 15:25:37.581  6974  7028 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Advertise TX power level: 2
08-16 15:25:37.581  6974  7028 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan mode: 1
08-16 15:25:37.581  6974  7028 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings:     - Scan report delay in milliseconds: 500
08-16 15:25:37.581  6974  7028 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@3f5b71bc added. We now have 1 listener(s)
,08-16 15:25:37.582  6974  7028 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 15:25:37.586  1044  1530 D WifiService: New client listening to asynchronous messages
08-16 15:25:37.591  6974  7028 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 15:25:37.591  6974  7028 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setManufacturerId: 76 -> 7413
08-16 15:25:37.593  6974  7028 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise mode: 1 -> 2
08-16 15:25:37.593  6974  7028 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Advertise TX power level: 2 -> 3
,08-16 15:25:37.594  6974  7028 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setAdvertiseScanModeAndTxPowerLevel: Scan mode: 1 -> 2
,08-16 15:25:37.603  6974  7028 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 15:25:37.603  1044  1638 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:25:37.604  6974  7028 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: initialize: My bluetooth address is 58:3F:54:73:BA:17
,08-16 15:25:37.620  6974  7028 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Storing the value (NOT_SUPPORTED) in persistent storage
,08-16 15:25:37.620  6974  7028 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 15:25:37.620  6974  7028 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:25:37.620  6974  7028 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:25:37.620  6974  7028 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:25:37.620  6974  7028 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:25:37.620  6974  7028 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:25:37.620  6974  7028 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:25:37.620  6974  7028 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 15:25:37.621  6974  7028 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: Not registered for event "networkChanged" and will not notify, in JS call method "didRegisterToNative" with argument "networkChanged" to register
08-16 15:25:37.621  6974  7028 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 15:25:37.625  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:25:37.628  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:25:37.629  6974  7028 I io.jxcore.node.LifeCycleMonitor: start: OK
,08-16 15:25:37.673  6974  7015 I chromium: [INFO:SkFontConfigInterface_android.cpp(247)] ---- failed to open </system/fonts/CutiveMono.ttf> as a font
08-16 15:25:37.673  6974  7015 I chromium: 
,08-16 15:25:37.777  6974  6974 I chromium: [INFO:CONSOLE(41)] "Uncaught TypeError: Cannot read property 'querySelector' of null", source: file:///android_asset/www/js/index.js (41)
,08-16 15:25:37.905   347   376 E GBMv2   : DFP En is all cleared set to be enabled
08-16 15:25:37.906   347   376 E GBMv2   : Set value is all cleared set the max
08-16 15:25:37.906   347   376 I GBMv2   : DFP Enabled. Ignore VFP set
,08-16 15:25:38.619  6974  7031 W jxcore-log: Initializing JXcore engine
08-16 15:25:38.619  6974  7031 W jxcore-log: JXcore engine is ready
,08-16 15:25:38.649  7031  7031 W Thread-812: type=1400 audit(0.0:162): avc: denied { ioctl } for path="socket:[7567]" dev="sockfs" ino=7567 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
,08-16 15:25:38.649  7031  7031 W Thread-812: type=1400 audit(0.0:163): avc: denied { ioctl } for path="/sys/kernel/debug/tracing/trace_marker" dev="debugfs" ino=3222 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:debugfs:s0 tclass=file
08-16 15:25:38.649  7031  7031 W Thread-812: type=1400 audit(0.0:164): avc: denied { ioctl } for path="socket:[7724]" dev="sockfs" ino=7724 scontext=u:r:untrusted_app:s0 tcontext=u:r:zygote:s0 tclass=unix_dgram_socket
08-16 15:25:38.649  7031  7031 W Thread-812: type=1400 audit(0.0:165): avc: denied { ioctl } for path="/cust" dev="mmcblk0p42" ino=2 scontext=u:r:untrusted_app:s0 tcontext=u:object_r:cust_data_file:s0 tclass=dir
08-16 15:25:38.649  7031  7031 W Thread-812: type=1400 audit(0.0:166): avc: denied { ioctl } for path="socket:[33988]" dev="sockfs" ino=33988 scontext=u:r:untrusted_app:s0 tcontext=u:r:surfaceflinger:s0 tclass=unix_stream_socket
08-16 15:25:38.674  6974  7031 W jxcore-log: Starting JXcore engine
,08-16 15:25:38.755  6974  7031 W jxcore-log: Platform android
08-16 15:25:38.755  6974  7031 W jxcore-log: 
08-16 15:25:38.755  6974  7031 W jxcore-log: Process ARCH arm
08-16 15:25:38.755  6974  7031 W jxcore-log: 
,08-16 15:25:38.984  6974  7031 I jxcore-log: JXcore Cordova bridge is ready!
08-16 15:25:38.984  6974  7031 I jxcore-log: 
08-16 15:25:38.984  6974  7031 W jxcore-log: JXcore engine is started
,08-16 15:25:38.990  6974  7028 I org.thaliproject.p2p.ThaliPermissions: execute: REQUEST_ACCESS_COARSE_LOCATION
,08-16 15:25:38.992  6974  6974 I chromium: [INFO:CONSOLE(41)] "Application has the required permission.", source: file:///android_asset/www/js/thali_main.js (41)
,08-16 15:25:54.812  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method peerAvailabilityChanged registered to native
08-16 15:25:54.812  6974  7031 I jxcore-log: 
,08-16 15:25:54.814  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method discoveryAdvertisingStateUpdateNonTCP registered to native
08-16 15:25:54.814  6974  7031 I jxcore-log: 
08-16 15:25:54.818  6974  7031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 15:25:54.818  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:25:54.818  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:25:54.818  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:25:54.818  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:25:54.818  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:25:54.818  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:25:54.818  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 15:25:54.821  6974  7031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 15:25:54.823  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method networkChanged registered to native
08-16 15:25:54.823  6974  7031 I jxcore-log: 
08-16 15:25:54.824  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: Method incomingConnectionToPortNumberFailed registered to native
08-16 15:25:54.824  6974  7031 I jxcore-log: 
,08-16 15:25:55.164  6974  7031 I jxcore-log: Running unit tests
08-16 15:25:55.164  6974  7031 I jxcore-log: 
08-16 15:25:55.165  6974  7031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
,08-16 15:25:55.165  6974  7031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@82bea9b added. We now have 2 listener(s)
08-16 15:25:55.165  1044  1886 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:25:55.167  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 15:25:55.167  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 15:25:55.167  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 15:25:55.167  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 15:25:55.167  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@2b104e38 added. We now have 2 listener(s)
08-16 15:25:55.167  6974  7031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 15:25:55.167  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 15:25:55.171  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 15:25:55.175  6974  7031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 15:25:55.175  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:25:55.175  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:25:55.175  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:25:55.175  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:25:55.175  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:25:55.175  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:25:55.175  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 15:25:55.177  6974  7031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 15:25:55.177  6974  7031 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 15:25:55.177  6974  7031 D ExecuteNativeTests: Running unit tests
08-16 15:25:55.181  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:25:55.188  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:25:55.255  6974  7031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 15:25:55.256  6974  7031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@207e0e26 added. We now have 3 listener(s)
08-16 15:25:55.256  1044  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:25:55.258  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 15:25:55.258  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 15:25:55.258  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 15:25:55.258  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 15:25:55.258  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 added. We now have 3 listener(s)
08-16 15:25:55.258  6974  7031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 15:25:55.259  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 15:25:55.261  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 15:25:55.266  6974  7031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 15:25:55.266  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:25:55.266  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:25:55.266  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:25:55.266  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:25:55.266  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:25:55.266  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:25:55.266  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 15:25:55.268  6974  7031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 15:25:55.268  6974  7031 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 15:25:55.269  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:25:55.270  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:25:55.272  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 15:25:55.272  6974  7031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 15:25:55.272  6974  7031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 15:25:55.272  6974  7031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 15:25:55.274  6974  7031 E io.jxcore.node.ConnectionHelper: onConnectionTimeout: Connection attempt with peer [<no peer name> 00:11:22:33:44:55] timed out
08-16 15:25:55.274  6974  7031 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 15:25:55.274  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 15:25:55.274  6974  7031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 15:25:55.274  6974  7031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 15:25:55.274  6974  7031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 15:25:55.275  6974  7031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:25:55.277  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:25:55.277  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:25:55.278  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:25:55.279  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:25:55.279  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 15:25:55.279  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 15:25:55.281  6974  7031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@207e0e26 removed from the list
08-16 15:25:55.281  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:25:55.281  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 removed from the list
08-16 15:25:55.281  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:25:55.281  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:25:55.284  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:25:55.284  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:25:55.286  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:25:55.286  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:25:55.286  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:25:55.286  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:25:55.291  6974  7031 D io.jxcore.node.ConnectionHelper: onBluetoothMacAddressResolved: 00:11:22:33:44:55 - Bro Mode is not supported
08-16 15:25:55.291  6974  7031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:25:55.291  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:25:55.291  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:25:55.291  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:25:55.291  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:25:55.291  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:25:55.291  6974  7031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@207e0e26 not in the list
08-16 15:25:55.291  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:25:55.291  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:25:55.291  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:25:55.291  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:25:55.292  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:25:55.292  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:25:55.292  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:25:55.292  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:25:55.292  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:25:55.292  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:25:55.292  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
,08-16 15:25:55.299  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 15:25:55.299  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 15:25:55.299  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 15:25:55.299  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 15:25:55.299  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 15:25:55.299  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 15:25:55.299  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 15:25:55.299  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 15:25:55.299  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
08-16 15:25:55.299  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 15:25:55.299  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 15:25:55.299  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 15:25:55.299  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 15:25:55.299  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 15:25:55.299  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 15:25:55.299  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 15:25:55.299  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 15:25:55.299  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 15:25:55.299  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 15:25:55.299  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 15:25:55.299  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 15:25:55.299  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 15:25:55.299  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 15:25:55.299  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 15:25:55.299  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 15:25:55.300  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 15:25:55.300  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 3,5:2510:2510:2510:2510:2510]
08-16 15:25:55.300  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 15:25:55.300  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 15:25:55.300  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 15:25:55.300  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 15:25:55.300  6974  7031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:25:55.300  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:25:55.300  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:25:55.301  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:25:55.301  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:25:55.301  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:25:55.301  6974  7031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@207e0e26 not in the list
08-16 15:25:55.301  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:25:55.301  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:25:55.301  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:25:55.301  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:25:55.301  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:25:55.301  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:25:55.301  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:25:55.302  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:25:55.302  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:25:55.302  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:25:55.302  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:25:55.303  6974  7031 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
08-16 15:25:55.304  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 15:25:55.306  6974  7031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 15:25:55.306  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:25:55.306  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:25:55.306  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:25:55.306  6974  7031 V io.jxcore.node.Conne,ctivityMonitor:     - is Bluetooth enabled: true
08-16 15:25:55.306  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:25:55.306  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:25:55.306  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 15:25:55.308  6974  7031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 15:25:55.308  6974  7031 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 15:25:55.308  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 15:25:55.308  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 15:25:55.308  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 15:25:55.308  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 15:25:55.308  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
,08-16 15:25:55.311  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:25:55.313  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:25:55.315  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 15:25:55.316  1044  1773 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:25:55.321  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 15:25:55.328  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 15:25:55.330  6974  7031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded filtering: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 15:25:55.331  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 15:25:55.331  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 15:25:55.333  6974  7031 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 15:25:55.333  6974  7031 I io.jxcore.node.ConnectionHelper: start: OK
08-16 15:26:00.063  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-16 15:26:00.063  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
08-16 15:26:00.063  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-16 15:26:00.064  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,08-16 15:26:00.077  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
08-16 15:26:00.077  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
08-16 15:26:00.078  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
08-16 15:26:00.079  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
08-16 15:26:00.346  6974  7031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 15:26:00.349  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:26:00.349  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:26:00.349  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:26:00.349  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:00.349  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 15:26:00.350  6974  7031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@207e0e26 not in the list
08-16 15:26:00.350  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:00.350  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:00.350  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:26:00.350  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:05.351  6974  7031 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 15:26:05.366  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 15:26:05.371  6974  7031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 15:26:05.371  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:05.371  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:05.371  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:26:05.371  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:26:05.371  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:26:05.371  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:26:05.371  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 15:26:05.374  6974  7031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 15:26:05.374  6974  7031 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 15:26:05.377  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:05.378  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:05.379  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 15:26:05.379  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 15:26:05.379  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 15:26:05.379  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 15:26:05.379  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 15:26:05.385  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 15:26:05.387  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 15:26:05.389  6974  7031 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 15:26:05.389  6974  7031 I io.jxcore.node.ConnectionHelper: start: OK
08-16 15:26:05.392  6974  7031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:26:05.392  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:26:05.392  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:26:05.393  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:26:05.393  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:05.393  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 15:26:05.393  6974  7031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@207e0e26 not in the list
08-16 15:26:05.393  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:05.393  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:05.393  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:26:05.393  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:05.394  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:05.394  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:05.395  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:26:05.395  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:26:05.397  6974  7031 D BluetoothLeScanner: could not find callback wrapper
08-16 15:26:05.397  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 15:26:05.397  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:05.397  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:05.398  6974  7031 I io.jxcore.node.ConnectionHelper: start: Port number: 1111, start advertisements: false
,08-16 15:26:05.404  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 15:26:05.408  6974  7031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 15:26:05.408  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:05.408  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:05.408  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:26:05.408  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:26:05.408  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:26:05.408  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:26:05.408  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 15:26:05.410  6974  7031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 15:26:05.410  6974  7031 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 15:26:05.412  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:26:05.416  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:05.417  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 15:26:05.417  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 15:26:05.417  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 15:26:05.417  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 15:26:05.417  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 15:26:05.422  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 15:26:05.424  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
,08-16 15:26:05.427  6974  7031 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 15:26:05.428  6974  7031 I io.jxcore.node.ConnectionHelper: start: OK
08-16 15:26:10.429  6974  7031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:26:10.429  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:26:10.429  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 15:26:13.445  1044  3454 I LocationManagerService: remove 3c50d748
08-16 15:26:13.446  1044  3454 D LocationManagerService: provider request: passive ProviderRequest[ON interval=0]
08-16 15:26:13.447  1044  3454 D LocationManagerService: getAllProviders()=[passive, gps, network]
,08-16 15:26:13.448  1044  3454 D LocationManagerService: getLastLocation: Request[POWER_NONE passive fastest=0 num=1]
08-16 15:26:13.449  1044  3454 D LocationManagerService: getLastLocation: Request[ACCURACY_FINE gps requested=0 fastest=0 num=1]
08-16 15:26:13.450  1044  3454 D LocationManagerService: getLastLocation: Request[POWER_LOW network requested=0 fastest=0 num=1]
,08-16 15:26:15.440  6974  7031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:26:15.441  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:26:15.441  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 15:26:15.448  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:26:15.448  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.449  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 15:26:15.449  6974  7031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@207e0e26 not in the list
08-16 15:26:15.449  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:15.449  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:15.449  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:26:15.449  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.452  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.452  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.455  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:26:15.456  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 15:26:15.458  6974  7031 D BluetoothLeScanner: could not find callback wrapper
08-16 15:26:15.458  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 15:26:15.458  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:15.459  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:15.460  6974  7031 D io.jxcore.node.ConnectionHelper: onPeerReadyToProvideBluetoothMacAddress: Bro Mode is not supported
08-16 15:26:15.460  6974  7031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:26:15.460  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:26:15.460  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:26:15.461  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:26:15.461  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.461  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.461  6974  7031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@207e0e26 not in the list
08-16 15:26:15.461  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:15.461  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:15.461  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:26:15.461  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.461  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.461  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.462  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.463  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:26:15.463  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:26:15.464  6974  7031 D BluetoothLeScanner: could not find callback wrapper
08-16 15:26:15.464  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 15:26:15.464  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:15.464  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:15.465  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 15:26:15.466  6974  7031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:26:15.466  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:26:15.466  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: ,The current state already matches the desired outcome of this operation, skipping...
08-16 15:26:15.466  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:26:15.466  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.466  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.466  6974  7031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@207e0e26 not in the list
08-16 15:26:15.466  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:15.467  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:15.467  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:26:15.467  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.467  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.467  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.467  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.468  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:26:15.468  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 15:26:15.474  6974  7031 D BluetoothLeScanner: could not find callback wrapper
08-16 15:26:15.474  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 15:26:15.474  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:15.474  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:15.476  6974  7031 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: null
08-16 15:26:15.477  6974  7031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:26:15.477  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:26:15.477  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:26:15.477  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:26:15.478  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.478  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.478  6974  7031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@207e0e26 not in the list
08-16 15:26:15.478  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:15.478  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:15.478  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:26:15.478  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.478  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.478  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.478  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.479  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:26:15.479  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:26:15.481  6974  7031 D BluetoothLeScanner: could not find callback wrapper
08-16 15:26:15.481  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 15:26:15.481  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:15.481  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:15.482  6974  7031 V io.jxcore.node.ConnectionHelper: Received a request for permission "randomString", but we are expecting that all the required permissions have already been granted
08-16 15:26:15.482  6974  7031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:26:15.482  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:26:15.482  6974  7031 V io.jxcore.node.StartStopOperationH,andler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 15:26:15.486  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:26:15.486  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.486  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.486  6974  7031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@207e0e26 not in the list
08-16 15:26:15.486  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:15.486  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:15.486  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:26:15.486  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
,08-16 15:26:15.486  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.486  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.486  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.488  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:26:15.488  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:26:15.489  6974  7031 D BluetoothLeScanner: could not find callback wrapper
,08-16 15:26:15.489  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 15:26:15.489  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:15.489  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:15.490  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 15:26:15.493  6974  7031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 15:26:15.493  6974  7031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 15:26:15.493  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 15:26:15.493  6974  7031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 15:26:15.495  6974  7031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
,08-16 15:26:15.500  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port 1 when trying to connect
08-16 15:26:15.500  6974  7031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 15:26:15.500  6974  7031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: -1 -> 1
08-16 15:26:15.500  6974  7031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:26:15.500  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:26:15.500  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:26:15.502  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:26:15.502  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.502  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.502  6974  7031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@207e0e26 not in the list
08-16 15:26:15.502  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:15.502  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:15.502  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:26:15.502  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.502  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.502  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.502  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.507  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:26:15.507  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:26:15.511  6974  7031 D BluetoothLeScanner: could not find callback wrapper
08-16 15:26:15.511  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 15:26:15.511  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:15.511  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
,08-16 15:26:15.516  6974  7031 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 15:26:15.517  6974  7031 E io.jxcore.node.ConnectionHelper: connect: We already have an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 15:26:15.517  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 00:11:22:33:44:55]
08-16 15:26:15.521  6974  7031 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 15:26:15.521  6974  7031 E io.jxcore.node.ConnectionHelper: connect: Maximum number of peer connections (30) reached, please try again after disconnecting a peer
08-16 15:26:15.521  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 10:010:010:010:010:010]
08-16 15:26:15.521  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 11:110:110:110:110:110]
08-16 15:26:15.521  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 12:210:210:210:210:210]
08-16 15:26:15.521  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 13:310:310:310:310:310]
08-16 15:26:15.521  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 14:410:410:410:410:410]
08-16 15:26:15.521  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 15:510:510:510:510:510]
08-16 15:26:15.521  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 16:610:610:610:610:610]
08-16 15:26:15.522  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 17:710:710:710:710:710]
,08-16 15:26:15.522  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 18:810:810:810:810:810]
08-16 15:26:15.522  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 19:910:910:910:910:910]
08-16 15:26:15.522  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 20:1010:1010:1010:1010:1010]
08-16 15:26:15.522  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 21:1110:1110:1110:1110:1110]
08-16 15:26:15.522  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 22:1210:1210:1210:1210:1210]
08-16 15:26:15.522  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 23:1310:1310:1310:1310:1310]
08-16 15:26:15.522  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 24:1410:1410:1410:1410:1410]
08-16 15:26:15.522  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 25:1510:1510:1510:1510:1510]
08-16 15:26:15.522  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 26:1610:1610:1610:1610:1610]
08-16 15:26:15.522  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 27:1710:1710:1710:1710:1710]
08-16 15:26:15.522  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 28:1810:1810:1810:1810:1810]
08-16 15:26:15.522  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 29:1910:1910:1910:1910:1910]
08-16 15:26:15.522  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 30:2010:2010:2010:2010:2010]
08-16 15:26:15.522  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 31:2110:2110:2110:2110:2110]
08-16 15:26:15.522  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 32:2210:2210:2210:2210:2210]
08-16 15:26:15.522  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 33:2310:2310:2310:2310:2310]
08-16 15:26:15.522  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 34:2410:2410:2410:2410:2410]
08-16 15:26:15.522  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 35:2510:2510:2510:2510:2510]
08-16 15:26:15.522  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 36:2610:2610:2610:2610:2610]
08-16 15:26:15.522  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 37:2710:2710:2710:2710:2710]
08-16 15:26:15.523  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 38:2810:2810:2810:2810:2810]
08-16 15:26:15.523  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> 39:2910:2910:2910:2910:2910]
08-16 15:26:15.523  6974  7031 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID abcd
08-16 15:26:15.523  6974  7031 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 15:26:15.523  6974  7031 E io.jxcore.node.ConnectionHelper: connect: Invalid Bluetooth MAC address: abcd
08-16 15:26:15.523  6974  7031 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 15:26:15.523  6974  7031 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 15:26:15.523  6974  7,031 E io.jxcore.node.ConnectionHelper: connect: Failed to add the callback for the connection
08-16 15:26:15.523  6974  7031 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 15:26:15.523  6974  7031 W io.jxcore.node.ConnectionHelper: connect: The peer to connect to is not amongst the discovered peers, but trying anyway...
08-16 15:26:15.524  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: connect: [<no peer name> 00:11:22:33:44:55]
08-16 15:26:15.528  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Trying to start connecting to null in address 00:11:22:33:44:55
08-16 15:26:15.529  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setInsecureRfcommSocketPortNumber: Using port -1
08-16 15:26:15.529  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: setMaxNumberOfRetries: 0
08-16 15:26:15.530  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: onConnecting: null 00:11:22:33:44:55
08-16 15:26:15.530  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: connect: Started connecting to null in address 00:11:22:33:44:55
08-16 15:26:15.530  6974  7031 I io.jxcore.node.ConnectionHelper: connect: Connection process successfully started (peer ID: 00:11:22:33:44:55)
08-16 15:26:15.531  6974  7031 I io.jxcore.node.ConnectionHelper: connect: Trying to connect to peer with ID 00:11:22:33:44:55
08-16 15:26:15.531  6974  7031 E io.jxcore.node.ConnectionHelper: connect: Callback is null
08-16 15:26:15.531  6974  7031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:26:15.531  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:26:15.531  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 15:26:15.537  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:26:15.537  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.537  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.540  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: cancelAllConnectionAttempts: Shutting down 1 client threads
08-16 15:26:15.541  6974  7031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@207e0e26 not in the list
08-16 15:26:15.541  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:15.541  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:15.541  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:26:15.541  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.541  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.541  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.541  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.543  6974  7036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Trying to connect to peer with address 00:11:22:33:44:55 (thread ID: 876)
08-16 15:26:15.545  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:26:15.545  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 15:26:15.547  6974  7031 D BluetoothLeScanner: could not find callback wrapper
08-16 15:26:15.547  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 15:26:15.547  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:15.547  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:15.549  6974  7031 E io.jxcore.node.ConnectionHelper: onProvideBluetoothMacAddressRequest: Request ID: 1111 - Bro Mode is not supported
08-16 15:26:15.549  6974  7031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:26:15.549  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:26:15.549  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:26:15.555  6974  7037 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: shutdown: Thread ID: 876
08-16 15:26:15.555  6974  7037 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Trying to close the Bluetooth socket... (thread ID: 876)
08-16 15:26:15.556  6974  7037 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: close: Bluetooth socket closed (thread ID: 876)
08-16 15:26:15.556  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:26:15.556  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.556  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.556  6974  7031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@207e0e26 not in the list
08-16 15:26:15.556  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:15.556  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:15.556  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:26:15.556  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.556  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.556  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.556  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:26:15.560  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:26:15.560  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:26:15.561  6974  7031 D BluetoothLeScanner: could not find callback wrapper
08-16 15:26:15.561  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 15:26:15.561  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:15.561  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:15.563  6974  7031 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: true, is advertising: true
08-16 15:26:15.564  6974  7031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:26:15.564  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:26:15.564  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:26:15.564  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:26:15.565  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.565  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.565  6974  7031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@207e0e26 not in the list
08-16 15:26:15.565  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:15.565  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:15.565  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:26:15.565  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.565  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.565  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.565  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.566  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:26:15.566  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:26:15.567  6974  7031 D BluetoothLeScanner: could not find callback wrapper
08-16 15:26:15.567  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 15:26:15.567  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:15.567  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:15.574  6974  7031 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID randomString
08-16 15:26:15.575  6974  7031 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID randomString
08-16 15:26:15.575  6974,  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 15:26:15.575  6974  7031 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: randomString), either no such connection or failed to close the connection
08-16 15:26:15.575  6974  7031 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 15:26:15.575  6974  7031 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: 00:11:22:33:44:55
08-16 15:26:15.575  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 15:26:15.575  6974  7031 I io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Successfully disconnected (peer ID: 00:11:22:33:44:55
08-16 15:26:15.575  6974  7031 D io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Trying to close connection to peer with ID 00:11:22:33:44:55
08-16 15:26:15.575  6974  7031 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID 00:11:22:33:44:55
08-16 15:26:15.575  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 15:26:15.576  6974  7031 W io.jxcore.node.ConnectionHelper: disconnectOutgoingConnection: Failed to disconnect (peer ID: 00:11:22:33:44:55), either no such connection or failed to close the connection
08-16 15:26:15.576  6974  7031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:26:15.576  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:26:15.576  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 15:26:15.581  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:26:15.581  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.581  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.581  6974  7031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@207e0e26 not in the list
08-16 15:26:15.581  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:15.581  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:15.581  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:26:15.581  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.581  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.581  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.581  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.583  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:26:15.583  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:26:15.584  6974  7031 D BluetoothLeScanner: could not find callback wrapper
08-16 15:26:15.584  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 15:26:15.584  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:15.584  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:15.585  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:26:15.585  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.585  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.585  6974  7031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@207e0e26 not in the list
08-16 15:26:15.585  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:15.585  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:15.585  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:26:15.585  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:15.585  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:15.675  6974  7036 W LGMDMUISystemServiceAdapter: checkBluetoothPairing btPolicy: false
08-16 15:26:15.675  6974  7036 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothClientThread: Exiting thread (thread ID: 876)
,08-16 15:26:20.587  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose,
08-16 15:26:20.587  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:20.587  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:26:20.587  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:20.587  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:20.587  6974  7031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@207e0e26 not in the list
08-16 15:26:20.588  6974  7031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:26:20.588  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:26:20.588  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 15:26:20.597  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:26:20.597  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:20.598  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:20.598  6974  7031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@207e0e26 not in the list
08-16 15:26:20.598  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:20.598  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:20.598  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:26:20.598  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:20.598  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:20.598  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:20.599  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:20.605  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
,08-16 15:26:20.607  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:26:20.608  6974  7031 D BluetoothLeScanner: could not find callback wrapper
08-16 15:26:20.608  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 15:26:20.608  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:20.608  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:20.611  6974  7031 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 15:26:20.612  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 15:26:20.613  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
08-16 15:26:20.614  6974  7031 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 15:26:20.614  6974  7031 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 15:26:20.615  6974  6974 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 15:26:20.615  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 15:26:20.615  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 15:26:20.617  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:26:20.617  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 15:26:20.617  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 15:26:20.617  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 15:26:20.617  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:20.617  6974  7031 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 15:26:20.619  6974  7055 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 15:26:20.619  6974  7055 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
,08-16 15:26:20.624  6974  6974 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 15:26:20.624  6974  7031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@207e0e26 not in the list
08-16 15:26:20.624  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:20.625  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stop: Stopping peer discovery...
08-16 15:26:20.625  6974  7031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopForRestart
08-16 15:26:20.625  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.BluetoothMacAddressResolutionHelper: stopProvideBluetoothMacAddressMode
08-16 15:26:20.627  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BlePeerDiscoverer: stopScannerAndAdvertiser
08-16 15:26:20.628  6974  7031 D BluetoothLeScanner: could not find callback wrapper
08-16 15:26:20.628  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 15:26:20.628  6974  7031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopBlePeerDiscoverer: Stopped
08-16 15:26:20.628  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:20.628  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:20.630  6974  7031 D org.thaliproject.p2p.btconnectorlib.DiscoveryManager: updateState: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 15:26:20.631  6974  6974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 15:26:20.631  6974  6974 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
08-16 15:26:20.631  6974  6974 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: false
08-16 15:26:20.631  6974  6974 I io.jxcore.node.ConnectionHelper: onDiscoveryManagerStateChanged: State: NOT_STARTED, is discovering: false, is advertising: false
08-16 15:26:20.633  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:20.633  6974  7031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:26:20.633  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:26:20.633  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 15:26:20.635  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:26:20.636  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:20.636  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:20.636  6974  7031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@207e0e26 not in the list
08-16 15:26:20.636  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:20.636  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:20.636  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:26:20.636  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:20.636  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:20.636  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:20.636  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:20.637  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:26:20.637  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:26:20.637  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:20.637  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:20.639  6974  7031 E io.jxcore.node.ConnectionHelper: onConnectionFailed: Peer properties: [<no peer name> 00:11:22:33:44:55], error message: ErrorMessage
08-16 15:26:20.639  6974  7031 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "00:11:22:33:44:55" removed
08-16 15:26:20.639  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: setInsecureRfcommSocketPortNumber: Will use port -1 when trying to connect
08-16 15:26:20.641  6974  7031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 15:26:20.641  6974  7031 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setInsecureRfcommSocketPort: 1 -> -1
08-16 15:26:20.642  6974  7031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:26:20.642  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:26:20.642  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:26:20.643  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:26:20.644  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:20.645  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:20.645  6974  7031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@207e0e26 not in the list
08-16 15:26:20.645  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:20.645  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:20.645  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:26:20.645  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:20.645  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:20.645  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:20.645  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:26:20.652  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:26:20.652  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:26:20.652  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:20.652  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:20.655  1044  1942 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:26:20.657  1044  1907 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 15:26:20.659  1044  1638 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:26:20.660  6974  7031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:26:20.660  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:26:20.660  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:26:20.660  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:26:20.660  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:20.660  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:20.661  6974  7031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@207e0e26 not in the list
08-16 15:26:20.661  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:20.661  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:20.661  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:26:20.661  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:20.661  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:20.661  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:20.661  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:20.662  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:26:20.662  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:26:20.662  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:20.662  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:20.663  6974  7031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:26:20.664  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:26:20.664  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:26:20.664  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:26:20.665  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:20.665  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:20.665  6974  7031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@207e0e26 not in the list
08-16 15:26:20.665  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:20.665  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:20.665  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:26:20.665  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:20.665  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:20.665  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:20.665  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:20.666  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:26:20.666  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:26:20.666  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:20.666  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@155fca67 not in the list
08-16 15:26:20.668  6974  7031 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing
08-16 15:26:20.668  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 15:26:20.668  6974  7031 E io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Failed to find an outgoing connection to peer with ID outgoing
08-16 15:26:20.668  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 1 outgoing connection(s) left
08-16 15:26:20.669  6974  7031 I io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: Closing connection, peer ID: outgoing2
08-16 15:26:20.669  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveOutgoingConnectionThread: 0 outgoing connection(s) left
08-16 15:26:20.671  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllIncomingConnections: Peer: [<no peer name> incoming]
08-16 15:26:20.671  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveAllOutgoingConnections: Peer: [<no peer name> outgoing]
08-16 15:26:20.672  6974  7031 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 1
,08-16 15:26:20.672  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 15:26:20.672  6974  7031 E io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Failed to find an incoming connection thread with ID 1
08-16 15:26:20.672  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 1 incoming connection(s) left
08-16 15:26:20.672  6974  7031 I io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: Closing and removing incoming connection thread with ID 2
08-16 15:26:20.673  6974  7031 D io.jxcore.node.ConnectionModel: closeAndRemoveIncomingConnectionThread: 0 incoming connection(s) left
08-16 15:26:20.673  6974  7031 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing1" removed
08-16 15:26:20.673  6974  7031 D io.jxcore.node.ConnectionModel: removeOutgoingConnectionCallback: Callback associated with Bluetooth MAC address "outgoing2" removed
08-16 15:26:20.676  6974  7031 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID id
08-16 15:26:20.676  6974  7031 D io.jxcore.node.ConnectionModel: hasConnection: No connection with peer with ID outgoing
08-16 15:26:20.677  6974  7031 D io.jxcore.node.ConnectionModel: hasConnection: We have an incoming connection with peer with ID incoming
08-16 15:26:20.677  6974  7031 D io.jxcore.node.ConnectionModel: hasConnection: We have an outgoing connection with peer with ID outgoing
08-16 15:26:20.678  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 15:26:20.678  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@13a9fdac added. We now have 3 listener(s)
08-16 15:26:20.678  6974  7031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 15:26:20.688  6974  7031 D BluetoothAdapter: enable(): BT is already enabled..!
08-16 15:26:20.690  1044  1949 D WifiServiceImplEx: setWifiEnabled: true pid=6974, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 15:26:20.691  1044  1949 D WifiService: setWifiEnabled: true pid=6974, uid=10118
08-16 15:26:20.691  1044  1949 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 15:26:21.134  6974  6974 V io.jxcore.node.ConnectionHelper: Notifying discovery manager state change: is discovering: false, is advertising: false
,08-16 15:26:25.700  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 15:26:25.700  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9b39a75 added. We now have 4 listener(s)
08-16 15:26:25.700  6974  7031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 15:26:25.717  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:25.717  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@9b39a75 removed from the list
08-16 15:26:25.717  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:26:25.717  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:25.718  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:26:25.721  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 15:26:25.721  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6069a0a added. We now have 4 listener(s)
08-16 15:26:25.721  6974  7031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 15:26:25.723  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:25.723  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@6069a0a removed from the list
08-16 15:26:25.724  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:26:25.724  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:25.724  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:25.725  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 15:26:25.725  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@17ad27b added. We now have 4 listener(s)
08-16 15:26:25.725  6974  7031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 15:26:25.728  1044  1949 D WifiServiceImplEx: setWifiEnabled: false pid=6974, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 15:26:25.728  1044  1949 D WifiService: setWifiEnabled: false pid=6974, uid=10118
08-16 15:26:25.728  1044  1949 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 15:26:25.752  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 15:26:25.752  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 15:26:25.752  1044  1044 D Ulp_jni : JNI:system_update. Event-4
08-16 15:26:25.754  1044  1525 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 15:26:25.755  1044  1525 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 15:26:25.755  1044  1525 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-16 15:26:25.755  1044  1525 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-16 15:26:25.756  1044  1525 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-16 15:26:25.756  1044  1525 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 15:26:25.756  1044  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 15:26:25.756  1044  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 15:26:25.757  1044  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 15:26:25.757  1044  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 15:26:25.760  1044  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:26:25.760  1044  2036 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@10069e73 mBinding = false
,08-16 15:26:25.768  1044  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 15:26:25.768  1044  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:25.769  1044  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:25.769  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 15:26:25.769  2727  2727 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 15:26:25.770  1044  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 15:26:25.771  1044  1525 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 15:26:25.772  1044  1525 D WifiNative-wlan0: SET ps 1: returned true
,08-16 15:26:25.777  1044  1119 D BluetoothManagerService: Message: 2
08-16 15:26:25.778  1044  1119 D BluetoothManagerService: Sending off request.
08-16 15:26:25.779  4280  4301 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 15:26:25.780  4280  4358 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-16 15:26:25.780  4280  4358 D BluetoothAdapterProperties: Setting state to 13
08-16 15:26:25.780  4280  4358 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 15:26:25.781  4280  4358 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 15:26:25.781  4280  4358 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 15:26:25.786  4280  4365 D BluetoothAdapterProperties: Scan Mode:20
,08-16 15:26:25.791  4280  4358 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 15:26:25.792  4280  4358 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 15:26:25.795  4280  4730 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 15:26:25.795  4280  4789 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 15:26:25.795  4280  4791 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 15:26:25.796  4280  4797 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 15:26:25.797  4280  4728 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-16 15:26:25.797  4280  4728 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 15:26:25.797  4280  4728 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-16 15:26:25.797  4280  4728 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-16 15:26:25.797  4280  4728 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-16 15:26:25.797  4280  4728 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-16 15:26:25.797  4280  4728 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-16 15:26:25.797  4280  4728 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-16 15:26:25.798  4280  4528 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-16 15:26:25.798  4280  4528 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
,08-16 15:26:25.805  4280  4528 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 15:26:25.806  4280  4528 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 15:26:25.806  4280  4528 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 15:26:25.806  4280  4528 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 15:26:25.806  4280  4528 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 15:26:25.806  4280  4528 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 15:26:25.806  4280  4528 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 15:26:25.806  4280  4528 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 15:26:25.806  4280  4528 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 15:26:25.806  4280  4528 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-16 15:26:25.806  4280  4528 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-16 15:26:25.806  4280  4528 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 15:26:25.811  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:25.811  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:26:25.811  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:25.811  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:25.811  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:26:25.811  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:26:25.811  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:26:25.811  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:26:25.811  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 15:26:25.815  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:25.815  6974  6974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 15:26:25.832  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:25.832  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:26:25.832  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:25.832  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:25.832  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:26:25.832  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:26:25.832  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:26:25.832  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:26:25.832  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 15:26:25.835  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:25.835  6974  6974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 15:26:25.836  1044  1119 D BluetoothManagerService: Message: 60
08-16 15:26:25.836  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-16 15:26:25.836  1044  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-16 15:26:25.837  1044  2854 D DhcpStateMachine: RunningState{ when=-65ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:25.845   321   903 D CommandListener: Clearing all IP addresses on wlan0
,08-16 15:26:25.888  1044  1115 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7068 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-16 15:26:25.893  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:25.894  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 15:26:25.894  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 15:26:25.896  4280  4280 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:25.897  4280  4280 D BluetoothMapService: STATE_TURNING_OFF
08-16 15:26:25.897  4280  4280 V BtOppService: Receiver DISABLED_ACTION 
08-16 15:26:25.897  4280  4280 V BluetoothMapService: Handler(): got msg=4
08-16 15:26:25.897  4280  4280 D BluetoothMapService: MAP Service closeService in
08-16 15:26:25.897  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:25.897  6974  7031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 15:26:25.897  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:25.897  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:25.897  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:26:25.897  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:26:25.897  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:26:25.897  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:26:25.897  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 15:26:25.897  4280  4280 D BluetoothMapMasInstance: MAP Service shutdown
08-16 15:26:25.898  4280  4280 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 15:26:25.898  4280  4280 V BluetoothMapService: MAP Service closeService out
08-16 15:26:25.898  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:25.898  6974  7031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 15:26:25.898  4280  4280 I BtOppRfcommListener: stopping Accept Thread
08-16 15:26:25.898  4280  4280 V BtOppRfcommListener: close mBtServerSocket
08-16 15:26:25.898  6974  7031 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 15:26:25.898  4280  4280 V BtOppRfcommListener: waiting for thread to terminate
08-16 15:26:25.898  4280  4789 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 15:26:25.899  4280  4280 V BtOppRfcommListener: done waiting for thread to terminate
08-16 15:26:25.901  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:26:25.903  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:25.905  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:25.931  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 15:26:25.931  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
,08-16 15:26:25.932  1044  1044 D Ulp_jni : JNI:system_update. Event-4
08-16 15:26:25.940  1044  1981 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 100]) by 10005
08-16 15:26:25.940  1044  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:25.940  1044  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:25.940  1044  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 15:26:25.940  1044  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:25.940  1044  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 15:26:25.942  1044  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 15:26:25.942  1044  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 100] got DISCONNECTED, was satisfying 2
,08-16 15:26:25.945  1044  1115 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.bluetooth.DockEventReceiver: pid=7091 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 15:26:25.948  4280  4280 V BtOppService: onDestroy
08-16 15:26:25.953  1044  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 15:26:25.953  1044  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 15:26:25.954  1044  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 15:26:25.954  1044  1524 D LGWifiP2pService: InactiveState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:25.954  1044  1524 D LGWifiP2pService: P2pEnabledState{ when=-2ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:25.954  1044  1524 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@cb7c87c
08-16 15:26:25.954   321  7095 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 15:26:25.955  1044  1524 D LGWifiP2pService: P2pDisablingState
08-16 15:26:25.955  1044  1524 D LGWifiP2pService: P2pDisablingState{ when=0 what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:25.955  1044  1524 D LGWifiP2pService: p2p socket connection lost
08-16 15:26:25.955  1044  1524 D LGWifiP2pService: P2pDisabledState
08-16 15:26:25.956  1044  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 15:26:25.956  1044  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 15:26:25.956  1044  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
,08-16 15:26:25.957  1044  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 15:26:25.958  1044  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 15:26:25.958  1044  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 15:26:25.958  1044  1525 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
08-16 15:26:25.959  1044  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-16 15:26:25.959  1044  1524 D LGWifiP2pService: P2pDisabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 15:26:25.959  1044  1524 D LGWifiP2pService: DefaultState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:25.959  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 15:26:25.960  2727  2727 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 15:26:25.961  1044  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-16 15:26:25.961  1044  1117 D DSQN    : Dns fail occured do internet check.
08-16 15:26:25.961  1044  1044 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
08-16 15:26:25.961  1044  1044 D DSQN    : try Internet connection check
08-16 15:26:25.962  1044  1044 D WifiHS20: hidePasspointNotification off =false
08-16 15:26:25.965  1044  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 15:26:25.965  1044  1525 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 15:26:25.965  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:25.965  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:26:25.965  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:25.965  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:25.965  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:26:25.965  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:26:25.965  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:26:25.965  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:26:25.965  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 15:26:25.965  1044  1525 D WifiNative-wlan0: SET ps 1: returned true
08-16 15:26:25.965  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-16 15:26:25.966  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:25.966  6974  6974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:26:25.968  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:25.969  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:25.971  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:25.972  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 15:26:25.972  1044  1044 D WifiHS20: hidePasspointNotification off =false
08-16 15:26:25.972  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:25.972  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:25.972  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 15:26:25.972  1044  1044 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 15:26:25.972  1044  1044 D RttService: SCAN_AVAILABLE : 1
08-16 15:26:25.972  1044  1543 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.andr,oid.internal.util.StateMachine$SmHandler }
08-16 15:26:25.973  1044  1544 D RttService: EnabledState got{ when=-1ms what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:25.976  4280  4280 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-16 15:26:25.978  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 15:26:25.978  1927  1927 D WfdsService: WifiP2pState is changed : false
08-16 15:26:25.978  1927  2207 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-16 15:26:25.979  1927  2207 D WfdsService: Set the WFDS Monitor: false
08-16 15:26:25.979  1927  2207 D WfdsMonitor: WFDS Monitor is stopped
08-16 15:26:25.979  1927  2207 D WfdsService: STATE : WfdsDisabledState - enter
08-16 15:26:25.980  1927  2766 D CtrlSupplicant: Received on exit socket, terminate
08-16 15:26:25.980  1927  2766 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-16 15:26:25.980  1927  2766 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-16 15:26:25.980  1927  2766 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-16 15:26:25.980  1927  2207 W WfdsService: DefaultState - msg [9445378] is not handled
08-16 15:26:25.984  1927  2228 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-16 15:26:25.987  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:26:25.987  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 15:26:25.988   321   903 D CommandListener: Clearing all IP addresses on wlan0
08-16 15:26:25.989  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:25.989  1044  1531 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-16 15:26:25.989  1044  1531 D DSQN    : disableDataServiceNotify
08-16 15:26:25.989  1044  1531 D DSQN    : stop dsqn bin
08-16 15:26:25.989   321  7116 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 15:26:25.990  1044  7111 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
08-16 15:26:25.990  1044  7106 D DSQN    : ThreadInternetCheck internet check NOK 
08-16 15:26:25.991  1044  7106 D DSQN    : InternetcheckProgress is not set don't send DS quality intent
08-16 15:26:25.992  1044  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 15:26:25.992  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:26:25.992  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 15:26:25.992  1044  1525 D WifiNative-p2p0: doBoolean: TERMINATE
08-16 15:26:25.993  1044  1044 D WifiHS20: hidePasspointNotification off =false
08-16 15:26:25.993  1044  1525 D WifiNative-p2p0: TERMINATE: returned true
08-16 15:26:25.993  1044  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 15:26:25.993  1044  1525 E WifiStateMachine: useWiFiOffloading() : false
08-16 15:26:25.993  1044  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 15:26:25.994  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:25.994  1044  1531 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 100]
08-16 15:26:25.994  1044  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:26:25.994  1044  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 15:26:25.995  1044  1531 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 15:26:25.995  1044  1531 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-16 15:26:25.995  1589  2063 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 15:26:25.995  1044  1531 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{100}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-16 15:26:25.995  1044  1531 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 100] isDefaultNetwork=true
08-16 15:26:25.995  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:25.996  1044  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 15:26:25.996  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Setting,s.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:25.996  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 15:26:25.996  1044  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:25.996  1044  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:25.996  1044  2851 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-16 15:26:25.997  1044  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 15:26:25.997  1044  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 15:26:25.997  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-16 15:26:25.998  1044  1523 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 15:26:26.000  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:26.000  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:26:26.000  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:26.000  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:26.000  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:26:26.000  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:26:26.000  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:26:26.000  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:26:26.000  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 15:26:26.001  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:26.001  6974  6974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:26:26.002  1044  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 15:26:26.003  1044  1531 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:26:26.003  1044  1531 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:26:26.003  1044  1523 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 15:26:26.003  1044  1525 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:26:26.003  1044  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 15:26:26.003  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:26.003  1839  1839 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:26:26.003  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:26:26.003  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:26.003  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:26.003  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:26:26.003  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:26:26.003  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:26:26.003  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:26:26.003  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 15:26:26.003  1044  1531 D NetworkManagementService: Removing idletimer
08-16 15:26:26.003  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 15:26:26.003  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:26.004  6974  6974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:26:26.004  1044  1531 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:26.004  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-16 15:26:26.004  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 15:26:26.004  1044  1044 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-16 15:26:26.004  1044  1044 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 15:26:26.004  1044  1531 E ConnectivityService: EVENT_NETWORK_INFO_CHANGED from unknown NetworkAgent
08-16 15:26:26.004  1044  1044 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 15:26:26.004  1044  1044 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 15:26:26.005  1044  1044 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 15:26:26.005  1044  1044 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 15:26:26.005  1044  1044 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 15:26:26.005  1044  1044 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 15:26:26.005  1044  1044 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 15:26:26.006  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:26.006  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:26:26.006  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:26.006  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:26.006  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:26:26.006  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:26:26.006  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:26:26.006  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:26:26.006  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 15:26:26.007  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:26.007  6974  6974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:26:26.016  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 15:26:26.016  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 15:26:26.017  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:26.018  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:26.037  7091  7091 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 15:26:26.037  7091  7091 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
,08-16 15:26:26.038  7091  7091 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 15:26:26.038  7091  7091 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-16 15:26:26.039  7091  7091 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 15:26:26.040  7091  7091 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 15:26:26.040  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 15:26:26.041  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:26.042  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:26.053  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 15:26:26.054  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:26.054  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:26.064  7068  7068 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-16 15:26:26.064  7068  7068 W LG Account v2.2: No ProfileInfo entries
08-16 15:26:26.065  7068  7068 I LG Account v2.2: isEnabled: false
08-16 15:26:26.065  7068  7068 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 15:26:26.065  7068  7068 I Feature : [Lifetracker]Country: EU
08-16 15:26:26.065  7068  7068 I Feature : [Lifetracker]Operator: OPEN
08-16 15:26:26.065  7068  7068 I Feature : [Lifetracker]Ranking support: false
08-16 15:26:26.065  7068  7068 I Feature : [Lifetracker]Comfort support: false
08-16 15:26:26.065  7068  7068 I Feature : [Lifetracker]Accessory: true
08-16 15:26:26.065  7068  7068 I Feature : [Lifetracker]Health device: true
08-16 15:26:26.065  7068  7068 I Feature : [Lifetracker]Extra Pedometer: false
08-16 15:26:26.065  7068  7068 I Feature : [Lifetracker]Blood glucose device: false
08-16 15:26:26.065  7068  7068 I Feature : [Lifetracker]Device Number: 3
,08-16 15:26:26.073  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 15:26:26.107  2727  2727 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 15:26:26.107  2727  2727 I wpa_supplicant: monitor socket send errors count : 1
08-16 15:26:26.107  2727  2727 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1927-2\x00 that cannot receive messages
08-16 15:26:26.108  1044  1638 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=7123 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 15:26:26.109  1044  1638 I ActivityManager: Killing 6264:com.android.providers.calendar/u0a14 (adj 15): empty #17
08-16 15:26:26.109  1044  2763 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
,08-16 15:26:26.109  1044  2763 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 15:26:26.144  2727  2727 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 15:26:26.145  2727  2727 W wpa_supplicant: USIM:  scard_deinit function
08-16 15:26:26.145  1044  2763 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-16 15:26:26.145  1044  2763 E WifiMonitor: WifiMonitor:wlan0 cnt=20 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 15:26:26.145  1044  2763 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 15:26:26.146  1044  1119 D Tethering: InitialState.processMessage what=4
08-16 15:26:26.146  1044  2763 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-16 15:26:26.146  1044  2763 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 15:26:26.146  1044  2763 E WifiMonitor: WifiMonitor:wlan0 cnt=21 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-16 15:26:26.146  1044  1525 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=347157
,08-16 15:26:26.147  1044  1525 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=347158
08-16 15:26:26.147  1044  1525 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=347158  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 15:26:26.148  1044  2854 D DhcpStateMachine: StoppedState
08-16 15:26:26.148  1044  1525 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 21 0 rt=347159  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 15:26:26.148  1044  2854 D DhcpStateMachine: StoppedState{ when=-182ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:26.161  7091  7091 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-16 15:26:26.166  1044  1060 W libprocessgroup: failed to open /acct/uid_10014/pid_6264/cgroup.procs: No such file or directory
08-16 15:26:26.170  1044  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 15:26:26.170  1044  1525 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-16 15:26:26.170  1044  1525 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-16 15:26:26.172  1044  1525 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-16 15:26:26.173  1044  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 15:26:26.174  4280  4280 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 15:26:26.174  4280  4280 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:26.174  4280  4280 V BluetoothPbapReceiver: ***********state = 13
,08-16 15:26:26.175  4280  4280 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-16 15:26:26.176  4280  4280 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:26.176  4280  4280 V BluetoothPbapService: state: 13
08-16 15:26:26.176  4280  4280 V BluetoothPbapService: Pbap Service closeService in
08-16 15:26:26.178  4280  4280 V BluetoothPbapService: successfully stopped pbap service
08-16 15:26:26.178  2173  2173 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 15:26:26.178  4280  4280 V BluetoothPbapService: Pbap Service closeService out
08-16 15:26:26.178  4280  4280 V BluetoothPbapService: Pbap Service onDestroy
08-16 15:26:26.178  4280  4280 V BluetoothPbapService: Pbap Service closeService in
08-16 15:26:26.178  4280  4280 V BluetoothPbapService: Pbap Service closeService out
08-16 15:26:26.178  4280  4280 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-16 15:26:26.182  1044  1119 D BluetoothManagerService: Message: 20
08-16 15:26:26.182  1044  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@22fcc43a:true
08-16 15:26:26.193  1044  1119 D BluetoothManagerService: Message: 30
,08-16 15:26:26.195  2727  2727 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
08-16 15:26:26.196  1044  2763 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-16 15:26:26.196  1044  2763 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-TERMINATING 
08-16 15:26:26.196  1044  2763 D WifiMonitor: Disconnecting from the supplicant, no more events
08-16 15:26:26.196  1044  1525 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 22 0
08-16 15:26:26.199  1044  1119 D BluetoothManagerService: Message: 30
08-16 15:26:26.201  7091  7091 D LocalBluetoothProfileManager: Adding local MAP profile
08-16 15:26:26.202  7091  7091 D BluetoothMap: Create BluetoothMap proxy object
08-16 15:26:26.202  1044  1119 D BluetoothManagerService: Message: 30
08-16 15:26:26.206  1044  1119 D BluetoothManagerService: Message: 30
08-16 15:26:26.207  7091  7091 D LocalBluetoothProfileManager: LocalBluetoothProfileManager construction complete
08-16 15:26:26.208  7091  7091 D LGBluetoothFeatureConfig:  get() - isFeatureLoaded : false
,08-16 15:26:26.213  7123  7123 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 15:26:26.216  7123  7123 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 15:26:26.216  7123  7123 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 15:26:26.218  1044  1942 I ActivityManager: Killing 6384:com.android.defcontainer/u0a4 (adj 15): empty #17
08-16 15:26:26.257  1044  1638 W libprocessgroup: failed to open /acct/uid_10004/pid_6384/cgroup.procs: No such file or directory
,08-16 15:26:26.264  7091  7091 D LGBluetoothUserBindClient: [BTUI] initUserBindClient
08-16 15:26:26.271  7091  7091 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.android.settings.bluetooth.LGBluetoothUserBindClient.initUserBindClient:90 com.android.settings.bluetooth.LGBluetoothUserBindClient.<init>:55 com.android.settings.bluetooth.LGBluetoothUserBindClient.getInstance:47 
,08-16 15:26:26.290  7091  7091 D DockEventReceiver: finishStartingService: stopping service
,08-16 15:26:26.299  1044  1525 D WifiOffDelayIfNotUsed: stopMonitoring
08-16 15:26:26.299  1927  1927 D WfdsService: Supplicant Connection state is changed : false
08-16 15:26:26.299  1044  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 15:26:26.299  1044  1525 E WifiStateMachine: useWiFiOffloading() : false
08-16 15:26:26.299  1044  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 15:26:26.299  1927  2207 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-16 15:26:26.299  1927  2207 D WfdsService: Set the WFDS Monitor: false
08-16 15:26:26.299  1927  2207 D WfdsMonitor: WFDS Monitor is stopped
08-16 15:26:26.303  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 15:26:26.305  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:26.306  2470  2470 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:26.307  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
,08-16 15:26:26.308  1044  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-16 15:26:26.308  1044  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-16 15:26:26.314  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:26.314  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:26:26.314  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:26.314  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:26.314  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:26:26.314  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:26:26.314  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:26:26.314  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:26:26.314  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:26:26.316  7091  7091 D BluetoothInputDevice: Proxy object connected
08-16 15:26:26.317  7091  7091 D HidProfile: Bluetooth service connected
08-16 15:26:26.319  7091  7091 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 15:26:26.320  7091  7091 D PanProfile: Bluetooth service connected
08-16 15:26:26.322  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:26.322  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:26:26.322  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:26.322  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:26.322  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:26:26.322  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:26:26.322  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:26:26.322  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:26:26.322  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:26:26.323  7091  7091 D BluetoothMap: Proxy object connected
,08-16 15:26:26.326  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 15:26:26.326  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:26:26.326  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:26.326  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:26.326  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:26:26.326  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:26:26.326  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:26:26.326  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:26:26.326  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:26:26.326  7091  7091 D MapProfile: Bluetooth service connected
08-16 15:26:26.326  7091  7091 D BluetoothMap: getConnectedDevices()
08-16 15:26:26.328  7091  7091 D BluetoothMap: Bluetooth is Not enabled
08-16 15:26:26.350  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 15:26:26.395  7091  7091 D LgDataFeature: LgDataFeature() Constructor: none
08-16 15:26:26.396  7091  7091 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 15:26:26.412  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 15:26:26.413  7091  7091 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
,08-16 15:26:26.418  7091  7091 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 15:26:26.433  7091  7091 D BluetoothPermissionRequest: onReceive
,08-16 15:26:26.438  7091  7091 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 15:26:26.453  1044  1562 I ActivityManager: Killing 6531:com.google.android.partnersetup/u0a8 (adj 15): empty #17
,08-16 15:26:26.456  7091  7091 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 15:26:26.508  4280  4280 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-16 15:26:26.509  4280  4280 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-16 15:26:26.510  4280  4280 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-16 15:26:26.511  1044  2009 W libprocessgroup: failed to open /acct/uid_10008/pid_6531/cgroup.procs: No such file or directory
08-16 15:26:26.600  1044  1942 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.settings.WiFiStateReceiver: pid=7152 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
,08-16 15:26:26.605  4280  4280 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-16 15:26:26.606  4280  4280 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 15:26:26.608  4280  4280 V BluetoothFtpService: Ftp Service onStartCommand
08-16 15:26:26.608  4280  4280 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:26.609  4280  4280 V BluetoothFtpService: Ftp Service closeService
08-16 15:26:26.609  4280  4280 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-16 15:26:26.610  4280  4280 V BluetoothFtpService: successfully stopped ftp service
08-16 15:26:26.611  4280  4280 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 15:26:26.611  4280  4280 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 15:26:26.611  4280  4280 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 15:26:26.612  4280  4280 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:26.612  4280  4280 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-16 15:26:26.612  4280  4280 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 15:26:26.615  4280  4280 V BluetoothFtpService: Ftp Service onDestroy
08-16 15:26:26.615  4280  4280 V BluetoothFtpService: Ftp Service closeService
,08-16 15:26:26.679  1044  1981 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7169 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 15:26:26.680  4280  4280 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
,08-16 15:26:26.680  4280  4280 V BluetoothSapService: state: 13
08-16 15:26:26.680  4280  4280 V BluetoothSapService: Stopping SAP server process
08-16 15:26:26.681  4280  4280 V BluetoothSapService: Sap Service closeSapService in
08-16 15:26:26.681  4280  4280 V BluetoothSapService: Close listen Socket : 
08-16 15:26:26.681  4280  4280 V BluetoothSapService: Close rfcomm Socket : 
08-16 15:26:26.681  4280  4280 V BluetoothSapService: Close sapd  Socket : 
08-16 15:26:26.687  4280  4280 V BluetoothSapService: Sap Service closeSapService out
08-16 15:26:26.687  4280  4280 V BluetoothSapService: Sap Service onDestroy
08-16 15:26:26.687  4280  4280 V BluetoothSapService: Sap Service closeSapService in
,08-16 15:26:26.687  4280  4280 V BluetoothSapService: Close listen Socket : 
08-16 15:26:26.687  4280  4280 V BluetoothSapService: Close rfcomm Socket : 
08-16 15:26:26.687  4280  4280 V BluetoothSapService: Close sapd  Socket : 
08-16 15:26:26.688  4280  4280 V BluetoothSapService: Sap Service closeSapService out
08-16 15:26:26.709  7152  7152 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 15:26:26.733  7152  7152 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-16 15:26:26.757  7169  7169 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 15:26:26.767  7152  7152 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-16 15:26:26.768  7152  7152 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
08-16 15:26:26.768  7152  7152 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
08-16 15:26:26.768  7152  7152 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
,08-16 15:26:26.769  7152  7152 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-16 15:26:26.772  1044  1981 I ActivityManager: Killing 6581:com.lge.appbox.client/u0a11 (adj 15): empty #17
08-16 15:26:26.772  7152  7152 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-16 15:26:26.778  7152  7152 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-16 15:26:26.802  4280  4528 W bt-btif : ag scb idx 1 not allocated
08-16 15:26:26.802  4280  4528 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 15:26:26.802  4280  4528 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 15:26:26.802  4280  4528 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 15:26:26.802  4280  4365 D bt_hci_bdroid: cleanup
08-16 15:26:26.802  4280  4528 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 15:26:26.802  4280  4528 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 15:26:26.802  4280  4528 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 15:26:26.802  4280  4528 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 15:26:26.802  4280  4528 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 15:26:26.802  4280  4528 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 15:26:26.802  4280  4528 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 15:26:26.802  4280  4528 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 15:26:26.802  4280  4528 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 15:26:26.802  4280  4528 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 15:26:26.802  4280  4528 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 15:26:26.802  4280  4528 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 15:26:26.802  4280  4528 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 15:26:26.802  4280  4528 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 15:26:26.802  4280  4528 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 15:26:26.802  4280  4528 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
,08-16 15:26:26.802  4280  4528 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 15:26:26.803  4280  4551 I bt_lpm  : LPM is already off!!!
08-16 15:26:26.804  4280  4688 I bt_userial_mct: exiting userial_read_thread
08-16 15:26:26.804  4280  4688 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 15:26:26.804  4280  4365 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 15:26:26.804  4280  4551 I bt_vendor: hw_epilog_process
08-16 15:26:26.805  4280  4365 D bt_hci_bdroid: cleanup Finalizing cleanup
08-16 15:26:26.805  4280  4365 D bt_userial_mct: userial_close
08-16 15:26:26.805  4280  4365 E bt_userial_mct: pthread_join() FAILED result:3
08-16 15:26:26.805  4280  4365 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-16 15:26:26.823  1044  1916 W libprocessgroup: failed to open /acct/uid_10011/pid_6581/cgroup.procs: No such file or directory
,08-16 15:26:26.835  7152  7152 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 15:26:26.841  7152  7152 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 15:26:26.874  4280  4365 D bt_hci_bdroid: set_power 0
08-16 15:26:26.874  4280  4365 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 15:26:26.874  4280  4365 I bt_vendor: bluetooth satus is on
08-16 15:26:26.874  4280  4365 I bt_vendor: bt-vendor : resetting BT status
,08-16 15:26:26.875  4280  4365 I bt_vendor: Starting hciattach daemon
08-16 15:26:26.875  4280  4365 I bt_vendor: try to set false
08-16 15:26:26.876  7152  7152 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 15:26:26.876  4280  4365 I bt_vendor: Starting hciattach daemon
08-16 15:26:26.876  4280  4365 I bt_vendor: try to set false
08-16 15:26:26.877  4280  4365 I bt_vendor: cleanup
08-16 15:26:26.878  4280  4528 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 15:26:26.879  4280  4365 I GKI_LINUX: GKI_exit_task 0 done
08-16 15:26:26.879  4280  4365 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-16 15:26:26.880  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 15:26:26.881  7152  7152 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-16 15:26:26.883  4280  4358 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-16 15:26:26.884  7152  7152 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-16 15:26:26.891  7123  7123 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 15:26:26.891  7123  7123 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 15:26:26.891  7123  7123 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 15:26:26.895  4280  4280 D HeadsetService: Received stop request...Stopping profile...
08-16 15:26:26.897  4280  4280 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 15:26:26.897  4280  4280 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 15:26:26.897  4280  4280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e1187cf
08-16 15:26:26.897  4280  4459 D HeadsetStateMachine: Exit Disconnected: -1
08-16 15:26:26.901  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-16 15:26:26.901  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-16 15:26:26.901  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-16 15:26:26.902  1044  1044 D BluetoothHeadset: Proxy object disconnected
,08-16 15:26:26.902  1044  1044 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-16 15:26:26.902  4280  4280 D A2dpService: Received stop request...Stopping profile...
08-16 15:26:26.902  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 15:26:26.903  4280  4518 D A2dpStateMachine: Exit Disconnected: -1
08-16 15:26:26.903  4280  4280 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-16 15:26:26.909  4280  4280 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-16 15:26:26.909  4280  4280 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 15:26:26.909  4280  4280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e1187cf
08-16 15:26:26.910  4280  4358 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 15:26:26.910  1044  1044 D BluetoothA2dp: Proxy object disconnected
08-16 15:26:26.910  1044  1044 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-16 15:26:26.911  4280  4280 D HidService: Received stop request...Stopping profile...
08-16 15:26:26.911  4280  4280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e1187cf
08-16 15:26:26.912  4280  4280 D HealthService: Received stop request...Stopping profile...
08-16 15:26:26.912  4280  4280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e1187cf
08-16 15:26:26.913  4280  4280 D HeadsetStateMachine: Unbinding service...
08-16 15:26:26.914  4280  4280 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 15:26:26.914  4280  4280 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
,08-16 15:26:26.914  4280  4280 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 15:26:26.914  4280  4280 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 15:26:26.914  4280  4280 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 15:26:26.914  4280  4280 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 15:26:26.914  4280  4280 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 15:26:26.915  4280  4280 D PanService: Received stop request...Stopping profile...
08-16 15:26:26.915  4280  4280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e1187cf
08-16 15:26:26.915  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:26:26.916  4280  4280 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 15:26:26.917  4280  4280 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 15:26:26.917  4280  4280 D BtGatt.GattService: stop()
08-16 15:26:26.917  4280  4280 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 15:26:26.920  4280  4280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e1187cf
08-16 15:26:26.920  7091  7091 D BluetoothInputDevice: Proxy object disconnected
08-16 15:26:26.920  7091  7091 D HidProfile: Bluetooth service disconnected
08-16 15:26:26.920  7091  7091 D BluetoothPan: BluetoothPAN Proxy object disconnected
08-16 15:26:26.920  7091  7091 D PanProfile: Bluetooth service disconnected
08-16 15:26:26.922  4280  4280 I BluetoothA2dpServiceJni: cleanupNative
08-16 15:26:26.922  4280  4519 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 15:26:26.922  4280  4280 I GKI_LINUX: GKI_exit_task 2 done
08-16 15:26:26.922  4280  4280 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 15:26:26.923  4280  4280 D BluetoothMapService: Received stop request...Stopping profile...
08-16 15:26:26.923  4280  4280 D BluetoothMapService: stop()
08-16 15:26:26.929  4280  4280 D BluetoothMapEmailAppObserver: deinitObservers()
08-16 15:26:26.929  4280  4280 D BluetoothMapEmailAppObserver: removeReceiver()
08-16 15:26:26.929  7152  7152 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 15:26:26.930  7152  7152 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 15:26:26.931  4280  4280 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@e1187cf
08-16 15:26:26.932  7152  7152 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 15:26:26.933  7091  7091 D BluetoothMap: Proxy object disconnected
08-16 15:26:26.933  7091  7091 D MapProfile: Bluetooth service disconnected
08-16 15:26:26.934  4280  4280 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 15:26:26.934  4280  4280 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 15:26:26.934  4280  4280 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 15:26:26.935  4280  4280 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 15:26:26.935  4280  4280 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 15:26:26.935  4280  4280 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 15:26:26.935  4280  4280 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 15:26:26.936  4280  4280 V BluetoothMapService: Handler(): got msg=4
08-16 15:26:26.936  4280  4280 D BluetoothMapService: MAP Service closeService in
08-16 15:26:26.936  4280  4280 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 15:26:26.936  4280  4280 V BluetoothMapService: MAP Service closeService out
08-16 15:26:26.937  4280  4358 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-16 15:26:26.937  4280  4358 D BluetoothAdapterProperties: Setting state to 10
08-16 15:26:26.937  4280  4358 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
08-16 15:26:26.937  1044  1119 D BluetoothManagerService: Message: 60
08-16 15:26:26.937  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-16 15:26:26.937  1044  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 9 receivers.
08-16 15:26:26.937  1044  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 15:26:26.937  4280  4358 I BluetoothAdapterState: Entering OffState
08-16 15:26:26.937  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 15:26:26.937  4280  4280 D BluetoothMapService: cleanup()
08-16 15:26:26.937  4280  4280 D BluetoothMapService: MAP Service closeService in
08-16 15:26:26.937  4280  4280 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 15:26:26.937  4280  4280 V BluetoothMapService: MAP Service closeService out
08-16 15:26:26.938  1839  2447 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 15:26:26.939  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 15:26:26.939  7091  7119 D BluetoothMap: onBluetoothStateChange: up=false
08-16 15:26:26.940  7091  7118 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 15:26:26.941  7091  7190 D BluetoothPan: onBluetoothStateChange on: false
08-16 15:26:26.945  7123  7123 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 15:26:26.945  7123  7123 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 15:26:26.945  7123  7123 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 15:26:26.947  7091  7119 D BluetoothInputDevice: onBluetoothStateChange: up=false
08-16 15:26:26.950  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 15:26:26.951  1044  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 15:26:26.951  1839  1854 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 15:26:26.953  1044  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-16 15:26:26.953  1044  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-16 15:26:26.956  1044  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-16 15:26:26.956  1044  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-16 15:26:26.956  1044  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@10069e73 mBinding = false
08-16 15:26:26.957  1044  1119 D BluetoothManagerService: Sending unbind request.
08-16 15:26:26.958  1044  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
,08-16 15:26:26.960  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 15:26:26.960  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:26.961  1927  2069 D LGBluetoothAPIService: Message: 2
08-16 15:26:26.961  1927  2069 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@24b570fe mBinding = false
08-16 15:26:26.961  1927  2069 D LGBluetoothAPIService: Sending unbind request.
08-16 15:26:26.963  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:26:26.964  7091  7091 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 15:26:26.965  7091  7091 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-16 15:26:26.965  7091  7091 D LGBluetoothEventManager: [BTUI] clear device connection state
08-16 15:26:26.967  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:26.967  1589  1589 D BluetoothAdapter: 533506119: getState() :  mService = null. Returning STATE_OFF
08-16 15:26:26.967  1589  1589 D BluetoothAdapter: 533506119: getState() :  mService = null. Returning STATE_OFF
08-16 15:26:26.968  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:26.969  4280  4365 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
08-16 15:26:26.969  4280  4280 I GKI_LINUX: GKI_exit_task 1 done
08-16 15:26:26.969  4280  4280 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 15:26:26.970  4280  4280 I BluetoothServiceJni: cleanupNative: return from cleanup
,08-16 15:26:26.970  4280  4280 I art     : --- WEIRD: removing null entry 246
08-16 15:26:26.970  4280  4280 W art     : JNI WARNING: DeleteGlobalRef(0x2003da) failed to find entry
08-16 15:26:26.970  4280  4280 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
08-16 15:26:26.971  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:26.973  7091  7091 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 15:26:26.975  4280  4280 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-16 15:26:26.978  4280  4280 I art     : System.exit called, status: 0
08-16 15:26:26.978  4280  4280 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-16 15:26:26.982  7091  7091 D DockEventReceiver: finishStartingService: stopping service
,08-16 15:26:26.989  7152  7152 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 15:26:26.989  7152  7152 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 15:26:26.990  1044  1044 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
08-16 15:26:26.991  7152  7152 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 15:26:27.004   326  2146 V AudioFlinger: 4280 died, releasing its sessions
08-16 15:26:27.004   326  2146 V AudioFlinger:  pid 1839 @ 0
08-16 15:26:27.004   326  2146 V AudioFlinger:  pid 3304 @ 1
08-16 15:26:27.004   326  2146 V AudioFlinger:  pid 3304 @ 2
08-16 15:26:27.005  7091  7091 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
,08-16 15:26:27.045  1044  1949 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=7193 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-16 15:26:27.074  1044  2036 I ActivityManager: Process com.android.bluetooth (pid 4280) has died
08-16 15:26:27.075  1044  2036 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 1000ms
,08-16 15:26:27.083  2173  2173 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 15:26:27.104  7091  7091 D BluetoothPermissionRequest: onReceive
,08-16 15:26:27.107  7091  7091 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 15:26:27.107  7091  7091 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-16 15:26:27.111  7091  7091 D LGBluetoothResetSettingReceiver: return without doing reset settings.
,08-16 15:26:27.165  1044  1949 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.opp.BluetoothOppReceiver: pid=7210 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-16 15:26:27.184  7123  7123 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 15:26:27.188   353   353 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 390us total 20.564ms
08-16 15:26:27.189  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 15:26:27.202  7193  7229 W FormManager: Network not available. Please check & try again.
,08-16 15:26:27.206   353   353 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 364us total 17.113ms
08-16 15:26:27.209  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 15:26:27.222   353   353 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 284us total 13.737ms
08-16 15:26:27.232  7193  7230 V FormManager: Network unavailable.
,08-16 15:26:27.234  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 15:26:27.234  7091  7091 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 15:26:27.234  7091  7091 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 15:26:27.235  7091  7091 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 15:26:27.235  7193  7230 V FormManager: Network unavailable.
08-16 15:26:27.235  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-16 15:26:27.236  7210  7210 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
08-16 15:26:27.237  7210  7210 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 15:26:27.237  7210  7210 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
08-16 15:26:27.238  7210  7210 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 15:26:27.244  7091  7091 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 15:26:27.245  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 15:26:27.245  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 15:26:27.245  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 15:26:27.245  7091  7091 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 15:26:27.245  7091  7091 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 15:26:27.246  1044  1562 I ActivityManager: Killing 6066:com.android.contacts/u0a19 (adj 15): empty #17
,08-16 15:26:27.255  7210  7210 D BluetoothAdapterApp: Loading JNI Library
08-16 15:26:27.288  7210  7210 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@27dc51c4 Instance Count = 1
,08-16 15:26:27.348  1044  1060 W libprocessgroup: failed to open /acct/uid_10019/pid_6066/cgroup.procs: No such file or directory
,08-16 15:26:27.350  4739  4739 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 15:26:27.352  4739  4739 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 15:26:27.356  1044  1363 D PowerManagerServiceEx: acquireWakeLockInternal: lock=293336886, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1044
08-16 15:26:27.357  1044  1363 V AlarmManager: ELAPSED_WAKEUP set : Alarm{1fe96445 type 2 when 348312 com.google.android.gms} when 348312
08-16 15:26:27.357  4739  4739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 15:26:27.358  7210  7210 D BluetoothAdapterApp: onCreate
08-16 15:26:27.365  4739  4739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 15:26:27.379  7123  7123 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,08-16 15:26:27.380  7123  7123 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 15:26:27.380  7123  7123 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 15:26:27.385  4739  7233 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 15:26:27.386  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 15:26:27.388  7210  7210 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-16 15:26:27.389  7210  7210 D ProfileConfigQcom: Adding HeadsetService
08-16 15:26:27.389  7210  7210 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-16 15:26:27.389  7210  7210 D ProfileConfigQcom: Adding A2dpService
08-16 15:26:27.389  7210  7210 D ProfileConfigQcom: [BTUI] HidService is supported
08-16 15:26:27.389  7210  7210 D ProfileConfigQcom: Adding HidService
08-16 15:26:27.390  7210  7210 D ProfileConfigQcom: [BTUI] HealthService is supported
08-16 15:26:27.390  7210  7210 D ProfileConfigQcom: Adding HealthService
08-16 15:26:27.390  4739  7235 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 15:26:27.390  7210  7210 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-16 15:26:27.390  4739  7235 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 15:26:27.391  7210  7210 D ProfileConfigQcom: [BTUI] PanService is supported
08-16 15:26:27.391  7210  7210 D ProfileConfigQcom: Adding PanService
08-16 15:26:27.391  7210  7210 D ProfileConfigQcom: [BTUI] GattService is supported
08-16 15:26:27.391  7210  7210 D ProfileConfigQcom: Adding GattService
08-16 15:26:27.392  7210  7210 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-16 15:26:27.392  7210  7210 D ProfileConfigQcom: Adding BluetoothMapService
08-16 15:26:27.392  7210  7210 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-16 15:26:27.394  7210  7210 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-16 15:26:27.401  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:26:27.401  7091  7091 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-16 15:26:27.405  7210  7210 V LGMDMManagerInternal: Create singleton instance
08-16 15:26:27.410  7193  7238 W FormManager: Network not available. Please check & try again.
08-16 15:26:27.419  7193  7239 V FormManager: Network unavailable.
,08-16 15:26:27.421  7193  7239 V FormManager: Network unavailable.
08-16 15:26:27.423  7152  7152 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 15:26:27.424  7152  7152 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 15:26:27.425  7152  7152 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
08-16 15:26:27.459  7152  7152 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 15:26:27.459  7152  7152 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 15:26:27.465  7152  7152 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-16 15:26:27.466  7152  7152 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
08-16 15:26:27.466  7152  7152 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-16 15:26:27.466  7152  7152 V SoundPool: doLoad: loading sample sampleID=1
08-16 15:26:27.467  7152  7152 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 15:26:27.468  7152  7242 V SoundPool: Start decode
08-16 15:26:27.468  7152  7242 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-16 15:26:27.469   326  2145 V MediaPlayerService: decode(22, 10857164, 17813)
08-16 15:26:27.469   326  2145 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-16 15:26:27.470   326  2145 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-16 15:26:27.470   326  2145 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
08-16 15:26:27.470   326  2145 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-16 15:26:27.470   326  2145 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-16 15:26:27.470   326  2145 V MediaPlayerService: player type = 3
08-16 15:26:27.470   326  2145 V AwesomePlayer: AwesomePlayer create()
08-16 15:26:27.471   326  2145 V AwesomePlayer: reset_l() 
08-16 15:26:27.471   326  2145 V AwesomePlayer: cancelPlayerEvents
08-16 15:26:27.471   326  2145 V AwesomePlayer: setAudioSink() 
08-16 15:26:27.471   326  2145 V AwesomePlayer: reset_l() 
08-16 15:26:27.471   326  2145 V AudioCache: notify(0xb5474a40, 8, 0, 0)
08-16 15:26:27.471   326  2145 V AudioCache: ignored
08-16 15:26:27.471   326  2145 V AwesomePlayer: cancelPlayerEvents
08-16 15:26:27.471   326  2145 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-16 15:26:27.472   326  2145 V AwesomePlayer: setDataSource_l dataSource
08-16 15:26:27.472   326  2145 V LGParserOSAL: SniffLGParser start
08-16 15:26:27.472   326  2145 V LGParserOSAL: MainType:5, SubType=0
08-16 15:26:27.472   326  2145 V LGParserOSAL: #### check Mime : application/ogg
08-16 15:26:27.472   326  2145 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-16 15:26:27.472   326  2145 E MediaExtractor: Use LGExtractor :application/ogg 
08-16 15:26:27.476  7152  7152 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-16 15:26:27.476  6818  6818 D UEI.SmartControl: QS Service created
,08-16 15:26:27.480  7152  7152 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 15:26:27.480  7152  7152 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 15:26:27.486  6818  6818 I UEI.SmartControl: Service initServices...
08-16 15:26:27.486  6818  6818 D UEI.SmartControl: QS start get config
08-16 15:26:27.489  7152  7152 V LGMDMManager: Create singleton instance
08-16 15:26:27.501  7210  7210 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-16 15:26:27.506  7210  7210 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 15:26:27.507  7210  7210 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 15:26:27.507  7210  7210 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 15:26:27.508  7210  7210 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:27.508  7210  7210 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
08-16 15:26:27.516  7169  7169 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
,08-16 15:26:27.523   326  2145 V LGParserOSAL: supported mime: application/ogg
08-16 15:26:27.523   326  2145 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-16 15:26:27.523   326  2145 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-16 15:26:27.523   326  2145 V AwesomePlayer: mBitrate = -1 bits/sec
08-16 15:26:27.523   326  2145 V AwesomePlayer: AudioTrack Setting
08-16 15:26:27.523   326  2145 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-16 15:26:27.523   326  2145 V AwesomePlayer: setAudioSource() 
08-16 15:26:27.523   326  2145 V MediaPlayerService: prepare
08-16 15:26:27.523   326  2145 V AwesomePlayer: prepareAsync_l() 
08-16 15:26:27.524   326  2145 V MediaPlayerService: wait for prepare
08-16 15:26:27.524   326  7244 V AwesomePlayer: onPrepareAsyncEvent() 
08-16 15:26:27.524   326  7244 V AwesomePlayer: initAudioDecoder() 
08-16 15:26:27.524   326  7244 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 15:26:27.524   326  7244 V AudioSystem: isOffloadSupported()
08-16 15:26:27.524   326  7244 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 15:26:27.524   326  7244 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 15:26:27.524   326  7244 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 15:26:27.524   326  7244 V AwesomePlayer: getUseOffload() = 0 
08-16 15:26:27.524   326  7244 V OMXCodec: OMXCodec::Create
08-16 15:26:27.524   326  7244 V OMXCodec: findMatchingCodecs()
08-16 15:26:27.524   326  7244 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-16 15:26:27.524   326  7244 V OMXCodec: matchingCodecs.size()=1
08-16 15:26:27.524   326  7244 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-16 15:26:27.534   326  7244 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-16 15:26:27.534   326  7244 V LGCodecAdapter: LG Codec Adapter start
08-16 15:26:27.534   326  7244 V OMXCodec: OMXCodec Createtor
08-16 15:26:27.534   326  7244 V OMXCodec: setComponentRole
08-16 15:26:27.534   326  7244 V OMXCodec: configureCodec protected=0
08-16 15:26:27.534   326  7244 V LGCodecAdapter: called getLGCodecSpecificData
08-16 15:26:27.534   326  7244 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-16 15:26:27.534   326  7244 V LGCodecOSAL: Called LGconfigureCodecMETA
08-16 15:26:27.534   326  7244 V LGCodecOSAL: Called LGconfigureCodecMSG
08-16 15:26:27.534   326  7244 V LGCodecOSAL: Not support LGCodec
08-16 15:26:27.534   326  7244 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 15:26:27.534   326  7244 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-16 15:26:27.534   326  7244 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-16 15:26:27.534   326  7244 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-16 15:26:27.534   326  7244 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 15:26:27.534   326  7244 V AudioSystem: isOffloadSupported()
08-16 15:26:27.534   326  7244 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 15:26:27.534   326  7244 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 15:26:27.534   326  7244 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-16 15:26:27.534   326  7244 V OMXCodec: init()
08-16 15:26:27.534   326  7244 V OMXCodec: [OMX.google.vorbis.decoder] set,State mState=1 , newState=2
08-16 15:26:27.534   326  7244 V OMXCodec: allocateBuffers
08-16 15:26:27.534   326  7244 V OMXCodec: allocateBuffersOnPort portIndex=0
08-16 15:26:27.534   326  7244 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-16 15:26:27.535   326  7244 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on input port
08-16 15:26:27.535   326  7244 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b00 on input port
08-16 15:26:27.535   326  7244 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on input port
08-16 15:26:27.535   326  7244 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on input port
08-16 15:26:27.535   326  7244 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 15:26:27.535   326  7244 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
,08-16 15:26:27.535   326  7244 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
08-16 15:26:27.535   326  7244 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb555f2e0 on output port
08-16 15:26:27.535   326  7244 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb555f470 on output port
08-16 15:26:27.535   326  7244 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb555f6f0 on output port
08-16 15:26:27.535   326  7244 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 15:26:27.535   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 15:26:27.535   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 15:26:27.535   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-16 15:26:27.535   326  7244 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 15:26:27.538   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-16 15:26:27.538   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-16 15:26:27.538   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-16 15:26:27.538   326  7244 V OMXCodec: init() mAsyncCompletion wait free! 
08-16 15:26:27.538   326  7244 V AwesomePlayer: finishAsyncPrepare_l() 
08-16 15:26:27.538   326  7244 V AudioCache: notify(0xb5474a40, 5, 0, 0)
08-16 15:26:27.538   326  7244 V AudioCache: ignored
08-16 15:26:27.538   326  7244 V AudioCache: notify(0xb5474a40, 1, 0, 0)
08-16 15:26:27.538   326  7244 V AudioCache: prepared
08-16 15:26:27.538   326  2145 V AudioCache: wait - success
08-16 15:26:27.538   326  2145 V MediaPlayerService: start
08-16 15:26:27.538   326  2145 V AwesomePlayer: play_l() 
08-16 15:26:27.538   326  2145 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-16 15:26:27.538   326  2145 V AwesomePlayer: createAudioPlayer_l
08-16 15:26:27.538   326  2145 V AwesomePlayer: seekAudioIfNecessary_l() 
08-16 15:26:27.538   326  2145 V AwesomePlayer: startAudioPlayer_l() 
08-16 15:26:27.538   326  2145 D AudioPlayer: start of Playback, useOffload 0
08-16 15:26:27.539   326  2145 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 15:26:27.539   326  2145 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 15:26:27.542   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-16 15:26:27.542   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-16 15:26:27.542   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-16 15:26:27.542   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-16 15:26:27.542   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-16 15:26:27.542   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 15:26:27.542   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886128
08-16 15:26:27.542   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 15:26:27.542   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3042308832
08-16 15:26:27.542   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 15:26:27.542   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3042309232
08-16 15:26:27.542   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 15:26:27.542   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3042309872
08-16 15:26:27.542   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 15:26:27.542   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-16 15:26:27.542   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 15:26:27.542   3,26  7246 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-16 15:26:27.542   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-16 15:26:27.542   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-16 15:26:27.542   326  7246 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 15:26:27.542   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 15:26:27.543   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb555f470 on output port
08-16 15:26:27.543   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb555f2e0 on output port
08-16 15:26:27.543   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
08-16 15:26:27.543   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb555f830 on output port
08-16 15:26:27.543   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-16 15:26:27.543   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-16 15:26:27.544   326  2145 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-16 15:26:27.546   326  2145 V AudioCache: notify(0xb5474a40, 6, 0, 0)
08-16 15:26:27.546   326  2145 V AudioCache: ignored
08-16 15:26:27.546  2589  2589 D [Concierge]Service: onStartCommand(). Type : 9
08-16 15:26:27.546   326  2145 V MediaPlayerService: wait for playback complete
,08-16 15:26:27.549   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.549   326  7247 V AudioCache: memcpy(0xac300000, 0xb16e0000, 4096)
08-16 15:26:27.554   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.554   326  7247 V AudioCache: memcpy(0xac301000, 0xb16e0000, 4096)
08-16 15:26:27.554   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.554   326  7247 V AudioCache: memcpy(0xac302000, 0xb16e0000, 4096)
08-16 15:26:27.554   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.554   326  7247 V AudioCache: memcpy(0xac303000, 0xb16e0000, 4096)
08-16 15:26:27.555   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.555   326  7247 V AudioCache: memcpy(0xac304000, 0xb16e0000, 4096)
08-16 15:26:27.555   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.555   326  7247 V AudioCache: memcpy(0xac305000, 0xb16e0000, 4096)
08-16 15:26:27.555   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.555   326  7247 V AudioCache: memcpy(0xac306000, 0xb16e0000, 4096)
08-16 15:26:27.555   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.555   326  7247 V AudioCache: memcpy(0xac307000, 0xb16e0000, 4096)
08-16 15:26:27.556   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.556   326  7247 V AudioCache: memcpy(0xac308000, 0xb16e0000, 4096)
08-16 15:26:27.557   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.558   326  7247 V AudioCache: memcpy(0xac309000, 0xb16e0000, 4096)
08-16 15:26:27.558   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.558   326  7247 V AudioCache: memcpy(0xac30a000, 0xb16e0000, 4096)
08-16 15:26:27.558   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.558   326  7247 V AudioCache: memcpy(0xac30b000, 0xb16e0000, 4096)
08-16 15:26:27.558   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.558   326  7247 V AudioCache: memcpy(0xac30c000, 0xb16e0000, 4096)
,08-16 15:26:27.559   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.559   326  7247 V AudioCache: memcpy(0xac30d000, 0xb16e0000, 4096)
08-16 15:26:27.559   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.559   326  7247 V AudioCache: memcpy(0xac30e000, 0xb16e0000, 4096)
08-16 15:26:27.559   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.559   326  7247 V AudioCache: memcpy(0xac30f000, 0xb16e0000, 4096)
08-16 15:26:27.559   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.559   326  7247 V AudioCache: memcpy(0xac310000, 0xb16e0000, 4096)
08-16 15:26:27.560   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.560   326  7247 V AudioCache: memcpy(0xac311000, 0xb16e0000, 4096)
08-16 15:26:27.560   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.560   326  7247 V AudioCache: memcpy(0xac312000, 0xb16e0000, 4096)
08-16 15:26:27.560   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.560   326  7247 V AudioCache: memcpy(0xac313000, 0xb16e0000, 4096)
08-16 15:26:27.560   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.560   326  7247 V AudioCache: memcpy(0xac314000, 0xb16e0000, 4096)
08-16 15:26:27.561   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.561   326  7247 V AudioCache: memcpy(0xac315000, 0xb16e0000, 4096)
08-16 15:26:27.561   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.561   326  7247 V AudioCache: memcpy(0xac316000, 0xb16e0000, 4096)
08-16 15:26:27.561   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.561   326  7247 V AudioCache: memcpy(0xac317000, 0xb16e0000, 4096)
08-16 15:26:27.561   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.561   326  7247 V AudioCache: memcpy(0xac318000, 0xb16e0000, 4096)
08-16 15:26:27.561   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.561   326  7247 V AudioCache: memcpy(0xac319000, 0xb16e0000, 4096)
08-16 15:26:27.562   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.562   326  7247 V AudioCache: memcpy(0xac31a000, 0xb16e0000, 4096)
08-16 15:26:27.562   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.562   326  7247 V AudioCache: memcpy(0xac31b000, 0xb16e0000, 4096)
08-16 15:26:27.562   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.562   326  7247 V AudioCache: memcpy(0xac31c000, 0xb16e0000, 4096)
08-16 15:26:27.562   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.562   326  7247 V AudioCache: memcpy(0xac31d000, 0xb16e0000, 4096)
08-16 15:26:27.563   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.563   326  7247 V AudioCache: memcpy(0xac31e000, 0xb16e0000, 4096)
08-16 15:26:27.563   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.563   326  7247 V AudioCache: memcpy(0xac31f000, 0xb16e0000, 4096)
08-16 15:26:27.563   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.563   326  7247 V AudioCache: memcpy(0xac320000, 0xb16e0000, 4096)
08-16 15:26:27.563   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.563   326  7247 V AudioCache: memcpy(0xac321000, 0xb16e0000, 4096)
08-16 15:26:27.563   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.563   326  7247 V AudioCache: memcpy(0xac322000, 0xb16e0000, 4096)
08-16 15:26:27.564   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.564   326  7247 V AudioCache: memcpy(0xac323000, 0xb16e0000, 4096)
08-16 15:26:27.564   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.564   326  7247 V AudioCache: memcpy(0xac324000, 0xb16e0000, 4096),
08-16 15:26:27.564   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.564   326  7247 V AudioCache: memcpy(0xac325000, 0xb16e0000, 4096)
08-16 15:26:27.565   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.565   326  7247 V AudioCache: memcpy(0xac326000, 0xb16e0000, 4096)
08-16 15:26:27.565   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.565   326  7247 V AudioCache: memcpy(0xac327000, 0xb16e0000, 4096)
08-16 15:26:27.565   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.565   326  7247 V AudioCache: memcpy(0xac328000, 0xb16e0000, 4096)
08-16 15:26:27.565   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.565   326  7247 V AudioCache: memcpy(0xac329000, 0xb16e0000, 4096)
08-16 15:26:27.566   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.566   326  7247 V AudioCache: memcpy(0xac32a000, 0xb16e0000, 4096)
08-16 15:26:27.566   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.566   326  7247 V AudioCache: memcpy(0xac32b000, 0xb16e0000, 4096)
08-16 15:26:27.566   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.566   326  7247 V AudioCache: memcpy(0xac32c000, 0xb16e0000, 4096)
08-16 15:26:27.566   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.566   326  7247 V AudioCache: memcpy(0xac32d000, 0xb16e0000, 4096)
08-16 15:26:27.566   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.566   326  7247 V AudioCache: memcpy(0xac32e000, 0xb16e0000, 4096)
08-16 15:26:27.567  7152  7152 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
,08-16 15:26:27.567  7152  7152 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
08-16 15:26:27.568   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-16 15:26:27.568   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.568   326  7247 V AudioCache: memcpy(0xac32f000, 0xb16e0000, 4096)
08-16 15:26:27.568   326  7247 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 15:26:27.568   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.568   326  7247 V AudioCache: memcpy(0xac330000, 0xb16e0000, 4096)
08-16 15:26:27.568   326  7247 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
,08-16 15:26:27.568   326  7247 V AudioCache: write(0xb16e0000, 4096)
08-16 15:26:27.568   326  7247 V AudioCache: memcpy(0xac331000, 0xb16e0000, 4096)
08-16 15:26:27.568   326  7247 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 15:26:27.568   326  7247 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 15:26:27.568   326  7247 V AwesomePlayer: postAudioEOS() 
08-16 15:26:27.568   326  7247 V AudioCache: write(0xb16e0000, 280)
08-16 15:26:27.568   326  7247 V AudioCache: memcpy(0xac332000, 0xb16e0000, 280)
08-16 15:26:27.569  7152  7152 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:5104
08-16 15:26:27.571   326  7244 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-16 15:26:27.571   326  7244 V AwesomePlayer: onStreamDone
08-16 15:26:27.571   326  7244 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-16 15:26:27.571   326  7244 V AudioCache: notify(0xb5474a40, 2, 0, 0)
08-16 15:26:27.571   326  7244 V AudioCache: playback complete
,08-16 15:26:27.571   326  7244 V AwesomePlayer: pause_l() 
08-16 15:26:27.571   326  2145 V AudioCache: wait - success
08-16 15:26:27.571   326  7244 V AudioCache: notify(0xb5474a40, 7, 0, 0)
08-16 15:26:27.571   326  2145 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-16 15:26:27.571   326  7244 V AudioCache: ignored
,08-16 15:26:27.571   326  7244 V AwesomePlayer: cancelPlayerEvents
08-16 15:26:27.571   326  7244 D AudioPlayer: Pause Playback at 1068125
08-16 15:26:27.572   326  2145 V AwesomePlayer: reset_l() 
08-16 15:26:27.572   326  2145 V AudioCache: notify(0xb5474a40, 8, 0, 0)
08-16 15:26:27.572   326  2145 V AudioCache: ignored
,08-16 15:26:27.572   326  2145 V AwesomePlayer: cancelPlayerEvents
08-16 15:26:27.572   326  2145 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-16 15:26:27.572   326  2145 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-16 15:26:27.572   326  2145 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-16 15:26:27.572   326  2145 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
,08-16 15:26:27.572   326  2145 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 15:26:27.572   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 15:26:27.572   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 15:26:27.572   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-16 15:26:27.572   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 0
08-16 15:26:27.572   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-16 15:26:27.572   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 0
08-16 15:26:27.572   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-16 15:26:27.572   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b00 on port 0
08-16 15:26:27.572   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-16 15:26:27.572   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 0
08-16 15:26:27.572   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-16 15:26:27.572   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 15:26:27.572   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb555f830 on port 1
08-16 15:26:27.572   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-16 15:26:27.572   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7fb0 on port 1
08-16 15:26:27.572   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-16 15:26:27.572   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb555f2e0 on port 1
08-16 15:26:27.572   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-16 15:26:27.572   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb555f470 on port 1
08-16 15:26:27.572   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 15:26:27.573   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-16 15:26:27.573   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-16 15:26:27.573   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-16 15:26:27.573   326  7246 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-16 15:26:27.573  1044  1044 D PowerManagerServiceEx: releaseWakeLockInternal: lock=293336886 [*alarm*], flags=0x0
08-16 15:26:27.573   326  2145 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 15:26:27.573   326  2145 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-16 15:26:27.573   326  2145 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-16 15:26:27.574   326  2145 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-16 15:26:27.574   326  2145 D AudioPlayer: AudioPlayer releasing audio source
08-16 15:26:27.574   326  2145 D AudioPlayer: AudioPlayer done releasing audio source
08-16 15:26:27.575   326  2145 V AwesomePlayer: reset_l() 
08-16 15:26:27.575   326  2145 V AwesomePlayer: cancelPlayerEvents
08-16 15:26:27.575   326  2145 V AwesomePlayer: ~AwesomePlayer call
,08-16 15:26:27.575   321  7249 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 15:26:27.575  1044  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 15:26:27.575   326  2145 V AwesomePlayer: reset_l() 
08-16 15:26:27.575   326  2145 V AwesomePlayer: cancelPlayerEvents
08-16 15:26:27.575  7152  7242 V SoundPool: close(31)
08-16 15:26:27.575  7152  7242 V SoundPool: pointer = 0x9fe9f000, size = 205080, sampleRate = 48000, numChannels = 2
08-16 15:26:27.734  6818  6818 I UEI.SmartControl: Supports setup maps: true
,08-16 15:26:27.737  6818  6818 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 15:26:27.737  6818  6818 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 15:26:27.737  6818  6818 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 15:26:27.737  6818  6818 I UEI.SmartControl: ### init IR Blaster...
08-16 15:26:27.741  6818  6818 D serial_port: Configuring serial port
08-16 15:26:27.741  6818  6818 E UEI.SmartControl: UEIBLaster setting for 616
08-16 15:26:27.741  6818  6818 I UEI.SmartControl: Setting serial record hearder size = 2
,08-16 15:26:27.741  6818  6818 I UEI.SmartControl: configuring settings for MAXQ616
08-16 15:26:27.741  6818  6818 I UEI.SmartControl: Get version...
,08-16 15:26:27.760  6818  7250 D UEI.SmartControl: serial port data available: 21,
,08-16 15:26:27.789  6818  6818 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-16 15:26:27.789  6818  6818 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-16 15:26:27.789  6818  6818 I UEI.SmartControl: QS saving settings...
08-16 15:26:27.791  6818  6818 D UEI.SmartControl: IR Blaster version: 25672567
,08-16 15:26:27.809  6818  7250 D UEI.SmartControl: serial port data available: 4
,08-16 15:26:27.840  6818  7253 I UEI.SmartControl: Device manager: loading config....
08-16 15:26:27.841  6818  7253 D UEI.SmartControl: ----------- loading internal config...
08-16 15:26:27.842  6818  6818 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-16 15:26:27.846  6818  6818 E UEI.SmartControl: Services init done
08-16 15:26:27.846  6818  6818 D UEI.SmartControl: QS Service init finished
08-16 15:26:27.847  6818  6818 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 15:26:27.848  6818  6818 D UEI.SmartControl: QS Service version code: 201091
08-16 15:26:27.848  6818  6818 D UEI.SmartControl: Service requested: Control
08-16 15:26:27.850  6818  7253 E UEI.SmartControl: Loading SETTINGS...
08-16 15:26:27.853  6818  6818 D UEI.SmartControl: Request IControl service: devices are loaded...
08-16 15:26:27.857  6818  6818 D UEI.SmartControl: Internal service binding...
08-16 15:26:27.858  7152  7152 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-16 15:26:27.861  6818  6833 I UEI.SmartControl: ------ IControl API: 11
08-16 15:26:27.862  6818  6833 D UEI.SmartControl: File observer start...
08-16 15:26:27.863  6818  6833 E UEI.SmartControl: IR Port is disabled: false
,08-16 15:26:27.863  6818  6833 D UEI.SmartControl: Starting file observer...
08-16 15:26:27.866  6818  7253 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-16 15:26:27.867  6818  6833 I UEI.SmartControl: Registering callback...
08-16 15:26:27.868  6818  6834 I UEI.SmartControl: ------ IControl API: 19
,08-16 15:26:27.871  6818  6834 I UEI.SmartControl: Registering Services Ready callback...
,08-16 15:26:27.900  6818  7252 I UEI.SmartControl: Notify AllClients services are ready: 0,
,08-16 15:26:27.901  7152  7168 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-16 15:26:27.902  6818  7252 D UEI.SmartControl: -----service ready thread exits
08-16 15:26:27.905  7152  7240 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-16 15:26:27.906  7152  7240 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-16 15:26:27.907  7152  7152 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-16 15:26:27.908  7152  7152 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-16 15:26:27.909  6818  6833 I UEI.SmartControl: ------ IControl API: 8
08-16 15:26:27.912  7152  7152 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-16 15:26:27.913  7152  7152 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-16 15:26:27.914  7152  7152 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-16 15:26:27.915  7152  7152 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
,08-16 15:26:27.918  7152  7152 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-16 15:26:27.919  7152  7152 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-16 15:26:27.923  7152  7152 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
08-16 15:26:27.929  7152  7152 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
,08-16 15:26:27.932  7152  7152 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 15:26:27.934  7152  7152 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-16 15:26:27.935  7152  7152 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 15:26:27.936  7152  7152 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 15:26:27.938  7152  7152 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-16 15:26:27.938  7152  7152 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading,
08-16 15:26:27.940  7152  7152 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471353987939]
08-16 15:26:27.943  7152  7152 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
,08-16 15:26:27.947  1044  1060 I ActivityManager: Killing 6640:com.android.gallery3d/u0a27 (adj 15): empty #17
08-16 15:26:27.976  7152  7255 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-16 15:26:27.994  1044  1060 I ActivityManager: Killing 6607:com.lge.email/u0a23 (adj 15): empty #18
,08-16 15:26:28.026  1044  1562 W libprocessgroup: failed to open /acct/uid_10027/pid_6640/cgroup.procs: No such file or directory
,08-16 15:26:28.039  1044  1949 W libprocessgroup: failed to open /acct/uid_10023/pid_6607/cgroup.procs: No such file or directory
08-16 15:26:28.042  7152  7152 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-16 15:26:28.044  7152  7152 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
,08-16 15:26:28.045  7152  7152 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
,08-16 15:26:28.046  7152  7152 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-16 15:26:28.047  7152  7152 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-16 15:26:28.048  7152  7152 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-16 15:26:28.049  7152  7152 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-16 15:26:28.069  7152  7152 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-16 15:26:29.000  1044  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 15:26:29.016  1044  1119 D Tethering: MasterInitialState.processMessage what=3
08-16 15:26:29.028  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:26:29.033  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:29.036  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:29.038  1044  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 15:26:29.041  1044  1119 D Tethering: MasterInitialState.processMessage what=3
,08-16 15:26:29.051  1044  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 15:26:29.053  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:26:29.058  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:29.059  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:29.061  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 15:26:29.064  6486  7122 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 15:26:29.071  5808  5808 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 15:26:29.088  5808  5808 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
08-16 15:26:29.116  2173  2173 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 15:26:29.147  1044  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 15:26:29.201  1044  2036 I ActivityManager: Start proc com.lge.appbox.client for broadcast com.lge.appbox.client/com.lge.appbox.receiver.NetworkStateForAutoUpdateMonitor: pid=7278 uid=10011 gids={50011, 9997, 3003, 1028, 1015, 2001} abi=armeabi-v7a
,08-16 15:26:29.205  1044  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:26:29.205  1044  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 15:26:29.270  7278  7278 I AppUp4:AppBoxCP: onCreate
,08-16 15:26:29.271  7278  7278 W AppUp4:DB:  [AppBoxDatabaseHelper] construct
,08-16 15:26:29.282  7278  7278 I AppUp4:DB:  setFingerPrint start
08-16 15:26:29.282  7278  7278 I AppUp4:DB:  newfinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys SDK version = 21
,08-16 15:26:29.291  7278  7278 I AppUp4:DB:  beforefinger = lge/g3_global_com/g3:5.0/LRX21R.A1421650137/1421650137:user/release-keys
08-16 15:26:29.291  7278  7278 I AppUp4:DB:  SDK version = 21
08-16 15:26:29.291  7278  7278 I AppUp4:DB:  beforefinger == newfinger no write in DB
08-16 15:26:29.293  7278  7278 D AppUp4:AppBoxApplication: AppBoxApplication onCreate()
08-16 15:26:29.295  7278  7278 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 15:26:29.295  7278  7278 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 15:26:29.297  7278  7278 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 15:26:29.298  7278  7278 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 15:26:29.304  7278  7278 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 15:26:29.347  7278  7278 D LgDataFeature: LgDataFeature() Constructor: none
08-16 15:26:29.347  7278  7278 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 15:26:29.355  7278  7278 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@37a4402e
08-16 15:26:29.355  7278  7278 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 15:26:29.355  7278  7278 D AppUp4:CustFacade: isPhone : true
08-16 15:26:29.356  7278  7278 D AppUp4:CustModeStarterReceiver: begin check event
08-16 15:26:29.356  7278  7278 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity
08-16 15:26:29.356  7278  7278 D AppUp4:CustModeStarterReceiver: runCustWithNotification goAsync : ReceiverData{intent=Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.lge.appbox.client/com.lge.appbox.cust.CustModeStarterReceiver (has extras) } packageName=com.lge.appbox.client resultCode=0 resultData=null resultExtras=null}
08-16 15:26:29.357  7278  7300 D AppUp4:CustModeStarterReceiver: call method handleAsyncCustNotification.
08-16 15:26:29.357  7278  7300 D AppUp4:CustModeStarterReceiver: handleAsync isTriedOnce : false
08-16 15:26:29.358  7278  7300 E AppUp4:CustModeStarterReceiver: handleAsyncCustNotification do not startCustService
08-16 15:26:29.359  1044  1774 I ActivityManager: Killing 6705:com.google.android.apps.docs/u0a61 (adj 15): empty #17
08-16 15:26:29.388  1044  1562 W libprocessgroup: failed to open /acct/uid_10061/pid_6705/cgroup.procs: No such file or directory
08-16 15:26:29.390  4739  4739 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 15:26:29.391  4739  4739 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
,08-16 15:26:29.395  4739  4739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 15:26:29.400  4739  4739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 15:26:29.415  4739  7302 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 15:26:29.419  4739  7303 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 15:26:29.420  4739  7303 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 15:26:29.470  1044  1886 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=7307 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-16 15:26:29.560  7307  7307 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 15:26:29.560  7307  7307 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 15:26:29.562  7307  7307 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 15:26:29.562  7307  7307 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-16 15:26:29.872  1044  2036 I art     : Explicit concurrent mark sweep GC freed 57940(2MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 3.187ms total 219.034ms
,08-16 15:26:29.877  7307  7307 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
08-16 15:26:29.891  7307  7307 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-16 15:26:29.930  7307  7307 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 15:26:29.966  7307  7307 D LgDataFeature: LgDataFeature() Constructor: none
08-16 15:26:29.966  7307  7307 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 15:26:30.086  7307  7307 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 15:26:30.121  3304  3304 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 15:26:30.121  3304  3304 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 15:26:30.121  3304  3304 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-16 15:26:30.125  7307  7307 I HubEmail: JNI_OnLoad()
08-16 15:26:30.125  7307  7307 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 15:26:30.125  7307  7307 I HubEmail: registerNatives()
08-16 15:26:30.125  7307  7307 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 15:26:30.125  7307  7307 I HubEmail: registerNativeMethods()
08-16 15:26:30.125  7307  7307 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 15:26:30.126  7307  7307 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
08-16 15:26:30.167  1044  1949 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=7336 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-16 15:26:30.181  7307  7333 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:30.187  7193  7335 V FormManager: Network unavailable.
,08-16 15:26:30.191  7193  7335 V FormManager: Network unavailable.
08-16 15:26:30.195  7193  7334 W FormManager: Network not available. Please check & try again.
08-16 15:26:30.200  1044  2009 I ActivityManager: Killing 6743:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
,08-16 15:26:30.226  1044  1059 W libprocessgroup: failed to open /acct/uid_10080/pid_6743/cgroup.procs: No such file or directory
,08-16 15:26:30.298  7336  7336 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 15:26:30.298  7336  7336 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 15:26:30.301  7336  7336 D PhoneMonitor: Register our PhoneStateListener
,08-16 15:26:30.322  7336  7336 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 15:26:30.324  7336  7336 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-16 15:26:30.341  7336  7336 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
08-16 15:26:30.341  7336  7336 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-16 15:26:30.342  7336  7336 D TelephonyAutoProfiling: [parse] Load xml
08-16 15:26:30.347  7336  7336 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-16 15:26:30.347  7336  7336 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-16 15:26:30.347  7336  7336 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-16 15:26:30.347  7336  7336 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
,08-16 15:26:30.347  7336  7336 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-16 15:26:30.347  7336  7336 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-16 15:26:30.347  7336  7336 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-16 15:26:30.347  7336  7336 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-16 15:26:30.348  7336  7336 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-16 15:26:30.348  7336  7336 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-16 15:26:30.348  7336  7336 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-16 15:26:30.348  7336  7336 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-16 15:26:30.348  7336  7336 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-16 15:26:30.348  7336  7336 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-16 15:26:30.348  7336  7336 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-16 15:26:30.348  7336  7336 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-16 15:26:30.348  7336  7336 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-16 15:26:30.356  7336  7336 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-16 15:26:30.370  1044  1562 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=7355 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 15:26:30.371  1044  1562 I ActivityManager: Killing 6176:com.google.android.apps.plus/u0a97 (adj 15): empty #17
08-16 15:26:30.456  1044  1774 W libprocessgroup: failed to open /acct/uid_10097/pid_6176/cgroup.procs: No such file or directory
,08-16 15:26:30.653  1044  1562 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=7378 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-16 15:26:30.655  1044  1562 I ActivityManager: Killing 6773:com.lge.eula/1000 (adj 15): empty #17
08-16 15:26:30.696  1044  1060 W libprocessgroup: failed to open /acct/uid_1000/pid_6773/cgroup.procs: No such file or directory
,08-16 15:26:30.855  1044  1942 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=7396 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 15:26:30.857  1044  1942 I ActivityManager: Killing 6797:com.lge.bnr/1000 (adj 15): empty #17
08-16 15:26:30.905  1044  1562 W libprocessgroup: failed to open /acct/uid_1000/pid_6797/cgroup.procs: No such file or directory
,08-16 15:26:30.913  1044  1977 D WifiServiceImplEx: setWifiEnabled: true pid=6974, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
,08-16 15:26:30.914  1044  1977 D WifiService: setWifiEnabled: true pid=6974, uid=10118
08-16 15:26:30.914  1044  1977 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 15:26:30.933  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 15:26:30.934  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 15:26:30.934  1044  1044 D Ulp_jni : JNI:system_update. Event-4
08-16 15:26:30.934  1044  1525 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-16 15:26:30.934  1044  1525 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-16 15:26:30.938  1044  1525 E WifiUtil: wfc_util_ffile_check_copy(): pid[1044] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-16 15:26:30.938  1044  1525 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 15:26:30.938  1044  1525 E WifiUtil: wfc_util_ffile_check_copy(): pid[1044] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-16 15:26:30.938  1044  1525 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 15:26:30.939  1044  1525 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-16 15:26:30.939  1044  1525 E WifiHW  : unknown target_country: EU , set to default
08-16 15:26:30.939  1044  1525 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-16 15:26:30.939  1044  1525 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-16 15:26:30.939  1044  1525 I WifiUtil: gEnableBmps=1
,08-16 15:26:30.941  7396  7396 I art     : Almond Protected OAT
08-16 15:26:30.960  1044  1524 D LGWifiP2pService: P2pDisabledState{ when=-5ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:30.960  1044  1524 D LGWifiP2pService: DefaultState{ when=-6ms what=143366 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 15:26:31.001  7396  7396 D WeatherApplication: removeAccount
08-16 15:26:31.003  7396  7396 D WeatherApplication: Account.length = 0
08-16 15:26:31.003  7396  7396 E WeatherApplication: OPERATOR:OPEN
,08-16 15:26:31.011  7396  7396 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:26:31
,08-16 15:26:31.015  7396  7396 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 15:26:31.015  7396  7396 D Weather.Utils: 2 : All the weather widget is gone.
08-16 15:26:31.017  7396  7396 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 15:26:31.026  7396  7396 D WeatherAncestor: connectivity changed - connection : true
08-16 15:26:31.028  7396  7396 D WeatherService: 2 : isServiceAlived():false forecastCache:null
,08-16 15:26:31.041  7396  7396 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
,08-16 15:26:31.041  7396  7396 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 15:26:31.041  7396  7396 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
08-16 15:26:31.064  7396  7396 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-16 15:26:31.066  7396  7396 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:26:31
08-16 15:26:31.149  1044  1907 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=7415 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 15:26:31.152  1044  1907 I ActivityManager: Killing 2147:com.lge.music/u0a34 (adj 15): empty #17
08-16 15:26:31.176   326  1370 V AudioFlinger: 2147 died, releasing its sessions
08-16 15:26:31.176   326  1370 V AudioFlinger:  pid 1839 @ 0
08-16 15:26:31.176   326  1370 V AudioFlinger:  pid 3304 @ 1
08-16 15:26:31.176   326  1370 V AudioFlinger:  pid 3304 @ 2
,08-16 15:26:31.206  1044  1942 W libprocessgroup: failed to open /acct/uid_10034/pid_2147/cgroup.procs: No such file or directory
,08-16 15:26:31.318   280   358 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 15:26:31.318   280   358 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,08-16 15:26:31.319   280   358 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 15:26:31.320  7415  7433 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-16 15:26:31.327   280   358 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 15:26:31.327   280   358 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 15:26:31.327   280   358 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 15:26:31.328  7415  7433 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 15:26:31.335   280   358 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 15:26:31.335   280   358 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 15:26:31.335   280   358 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 15:26:31.336  7415  7437 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
,08-16 15:26:31.340   280   358 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 15:26:31.340   280   358 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 15:26:31.340   280   358 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 15:26:31.341  7415  7437 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 15:26:31.619  7415  7415 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-16 15:26:31.633  7415  7415 I LibraryLoader: Loading: webviewchromium
,08-16 15:26:31.636  7415  7415 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 2657-2662)
08-16 15:26:31.637  7415  7415 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 15:26:31.651  7415  7415 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {3e260bdb}
08-16 15:26:31.653  7415  7415 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 15:26:31.654  7415  7415 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
,08-16 15:26:31.663  1044  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 15:26:31.667   321   903 D SoftapController: Softap fwReload - Ok
,08-16 15:26:31.675  1044  1525 E NetdConnector: NDC Command {53 softap fwreload wlan0 STA} took too long (725ms)
08-16 15:26:31.676  1044  1119 D Tethering: InitialState.processMessage what=4
08-16 15:26:31.681  1044  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-16 15:26:31.685   321   903 D CommandListener: Setting iface cfg
08-16 15:26:31.685   321   903 D CommandListener: Trying to bring down wlan0
08-16 15:26:31.686   321   903 D CommandListener: Clearing all IP addresses on wlan0
08-16 15:26:31.688  1044  1525 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-16 15:26:31.679  7463  7463 W wpa_supplicant: type=1400 audit(0.0:167): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 15:26:31.679  7463  7463 W wpa_supplicant: type=1400 audit(0.0:168): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 15:26:31.696  1044  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 15:26:31.696  1044  1525 E WifiStateMachine: useWiFiOffloading() : false
08-16 15:26:31.696  1044  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-16 15:26:31.700  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:31.702  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-16 15:26:31.706  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:31.708  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:26:31.710  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:31.710  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
08-16 15:26:31.711  1044  1525 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-16 15:26:31.711  1044  1525 D WifiMonitor: connecting to supplicant
08-16 15:26:31.736  7463  7463 I wpa_supplicant: Successfully initialized wpa_supplicant
,08-16 15:26:31.772  7463  7463 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 15:26:31.773  7463  7463 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
,08-16 15:26:31.775  7415  7415 I BrowserStartupController: Initializing chromium process, renderers=0
08-16 15:26:31.776  7415  7415 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 15:26:31.787  7415  7415 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-16 15:26:31.787   326  2146 V AudioPolicyService: registerClient() client 0xb558ade0, uid 10093
08-16 15:26:31.788  7415  7415 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-16 15:26:31.788  7415  7415 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-16 15:26:31.788  7415  7479 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-16 15:26:31.801  7415  7415 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 15:26:31.801  7415  7415 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 15:26:31.801  7415  7415 I Adreno-EGL: Build Date: 12/12/14 금
08-16 15:26:31.801  7415  7415 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 15:26:31.801  7415  7415 I Adreno-EGL: Remote Branch: 
08-16 15:26:31.801  7415  7415 I Adreno-EGL: Local Patches: 
08-16 15:26:31.801  7415  7415 I Adreno-EGL: Reconstruct Branch: 
08-16 15:26:31.870  7463  7463 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 15:26:31.877  7415  7415 I NSApplication: Starting up...
08-16 15:26:31.913  7463  7463 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
,08-16 15:26:31.933  7463  7463 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
08-16 15:26:31.933  1044  1525 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-16 15:26:31.933  7463  7463 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-16 15:26:31.933  1044  7493 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-16 15:26:31.933  1044  7493 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 15:26:31.933  1044  7493 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-16 15:26:31.933  1044  7493 E WifiMonitor: WifiMonitor:wlan0 cnt=22 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-16 15:26:31.933  1044  7493 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-16 15:26:31.933  1044  7493 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-16 15:26:31.934  1044  1525 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-16 15:26:31.935  1044  1525 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-16 15:26:31.936  1044  1525 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
,08-16 15:26:31.937  1044  1525 E WifiStateMachine:  SupplicantStartingState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 15:26:31.939  1044  1525 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 1 0
08-16 15:26:31.940  1044  1525 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 15:26:31.941  1044  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 15:26:31.943  1044  1525 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 15:26:31.944  1044  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 15:26:31.945  1044  1525 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-16 15:26:31.945  1044  1525 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-16 15:26:31.946  1044  1525 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-16 15:26:31.946  1044  1525 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-16 15:26:31.946  1044  1525 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-16 15:26:31.970  1044  2018 I ActivityManager: Start proc com.google.android.apps.plus for broadcast com.google.android.apps.plus/.service.ConnectivityReceiver: pid=7494 uid=10097 gids={50097, 9997, 3003, 3002, 1028, 1015} abi=armeabi-v7a
08-16 15:26:31.972  1044  1886 I ActivityManager: Killing 6660:com.android.vending/u0a44 (adj 15): empty #17
,08-16 15:26:32.027  1044  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 15:26:32.027  1044  1525 E WifiStateMachine: useWiFiOffloading() : false
08-16 15:26:32.027  1044  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-16 15:26:32.028  1044  1525 D WifiNative-wlan0: doBoolean: SET update_config 1
08-16 15:26:32.028  1044  1562 W libprocessgroup: failed to open /acct/uid_10044/pid_6660/cgroup.procs: No such file or directory
,08-16 15:26:32.029  1044  1525 D WifiNative-wlan0: SET update_config 1: returned true
08-16 15:26:32.029  1044  1525 D WifiConfigStore: Loading config and enabling all networks 
08-16 15:26:32.029  1044  1525 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-16 15:26:32.030  1044  1525 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-16 15:26:32.036  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:32.036  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:32.036  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:32.036  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:32.036  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 15:26:32.037  1044  1525 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-16 15:26:32.037  1927  1927 D WfdService: Waiting for WifiP2p enabling
08-16 15:26:32.043  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
08-16 15:26:32.043  1044  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-16 15:26:32.043  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:32.044  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:32.045  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:26:32.045  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:32.045  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:32.045  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:26:32.045  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:26:32.045  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:26:32.045  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:26:32.045  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:26:32.045  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 15:26:32.045  6974  6974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:26:32.046  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:32.046  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:26:32.046  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:32.046  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:32.046  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:26:32.046  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:26:32.046  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:26:32.046  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:26:32.046  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:26:32.046  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:32.046  6974  6974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
,08-16 15:26:32.046  1044  1525 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-16 15:26:32.047  1044  1525 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-16 15:26:32.047  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:32.047  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:26:32.047  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:32.047  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:32.047  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:26:32.047  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:26:32.047  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:26:32.047  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:26:32.047  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:26:32.047  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:32.047  6974  6974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:26:32.048  1044  1525 D WifiStateMachine: enableVerboseLogging : level 2
08-16 15:26:32.048  1044  1525 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-16 15:26:32.048  1044  1525 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-16 15:26:32.048  1044  1525 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-16 15:26:32.049  1044  1525 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-16 15:26:32.049  1044  1525 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-16 15:26:32.049  1044  1525 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-16 15:26:32.049  1044  1525 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-16 15:26:32.050  1044  1525 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-16 15:26:32.050  1044  1525 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-16 15:26:32.050  1044  1525 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-16 15:26:32.050  1044  1525 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
08-16 15:26:32.051  1044  1525 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-16 15:26:32.051  1044  1525 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-16 15:26:32.051  1044  1525 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-16 15:26:32.053  1927  1927 D WfdsService: Supplicant Connection state is changed : true
08-16 15:26:32.053  1044  1525 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 15:26:32.053  1044  1525 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-16 15:26:32.053  1927  2207 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-16 15:26:32.053  1927  2207 D WfdsService: Set the WFDS Monitor: true
,08-16 15:26:32.053  1927  2207 D WfdsMonitor: WfdsMonitorThread create
08-16 15:26:32.053  1927  2207 D WfdsMonitor: WFDS Monitor is created and started
08-16 15:26:32.053  1927  2207 D WfdsService: WiFi: Supplicant connection re-established
08-16 15:26:32.054  1044  1525 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-16 15:26:32.054  1044  1525 D WifiNative-HAL: Setting external_sim to 1
08-16 15:26:32.054  1044  1525 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-16 15:26:32.054  1044  1525 D WifiNative-wlan0: SET external_sim 1: returned true
08-16 15:26:32.054  1044  1525 I WifiNative-HAL: startHal
08-16 15:26:32.054  1044  1525 D wifi    : setting scan oui 0xaf6fc200
08-16 15:26:32.055  1044  1525 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 15:26:32.055  1044  1525 I WifiNative-HAL: startHal
08-16 15:26:32.055  1044  1525 D wifi    : setting scan oui 0xaf6fc200
08-16 15:26:32.055  1927  7511 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-16 15:26:32.055  1044  1525 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-16 15:26:32.056  1044  1525 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-16 15:26:32.056  1927  7511 E CtrlSupplicant: Succeed to open control connection
08-16 15:26:32.056  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-16 15:26:32.056  1927  7511 E CtrlSupplicant: Succeed to open monitor connection
08-16 15:26:32.056  7463  7463 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-16 15:26:32.056  1927  7511 D WfdsMonitor: Supplicant connection established
08-16 15:26:32.056  1044  1525 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-16 15:26:32.056  1927  2207 D WfdsService: Connected to the supplicant for wfds
08-16 15:26:32.057  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 15:26:32.057  7463  7463 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 15:26:32.057  1044  1525 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 15:26:32.057  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-16 15:26:32.057  7463  7463 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-16 15:26:32.057  1044  1525 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-16 15:26:32.058  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 15:26:32.058  7463  7463 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 15:26:32.058  1044  1525 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 15:26:32.058  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 15:26:32.058  7463  7463 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 15:26:32.058  1044  1525 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 15:26:32.058  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-16 15:26:32.059  7463  7463 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-16 15:26:32.059  1044  1525 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 2: returned true
08-16 15:26:32.059  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 15:26:32.059  7463  7463 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 15:26:32.059  1044  1525 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 15:26:32.060  1044  1525 E WifiNative: : [353,071,021 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-16 15:26:32.060  1044  1525 D WifiNative-wlan0: doBoolean: RECONNECT
08-16 15:26:32.061  1044  1525 D WifiNative-wlan0: RECONNECT: returned true
08-16 15:26:32.061  1044  1525 D WifiNative-wlan0: doString: [STATUS]
08-16 15:26:32.061  1044  7493 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 15:26:32.062  1044  7493 E WifiMonitor: WifiMonitor:wlan0 cnt=23 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 15:26:32.062  1044  1525 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 15:26:32.062  1044  1525 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 15:26:32.063  1044  1525 D WifiNative-wlan0: SET ps 1: returned true
08-16 15:26:32.063  1044  1524 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=131203 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 15:26:32.065  1044  1525 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-16 15:26:32.065  1044  1044 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 15:26:32.065  1044  1044 D RttService: SCAN_AVAILABLE : 3
08-16 15:26:32.065  1044  1543 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:32.065  1044  1543 I WifiNative-HAL: startHal
08-16 15:26:32.065  1044  1543 D wifi    : getting scan capabilities on interface[1] = 0xaf6fc200
08-16 15:26:32.065  1044  1543 D wifi    : failed to get capabilities : -3
08-16 15:26:32.065  1044  1543 E WifiScanningService: could not get scan capabilities
08-16 15:26:32.066  1044  1544 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:32.067   321   903 D CommandListener: Setting iface cfg
08-16 15:26:32.067   321   903 D CommandListener: Trying to bring up p2p0
08-16 15:26:32.068  1044  1524 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 15:26:32.068  1044  1524 D LGWifiP2pService: P2pEnablingState
08-16 15:26:32.068  1044  1524 D LGWifiP2pService: P2pEnablingState{ when=-1ms what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:32.068  1044  1524 D LGWifiP2pService: P2p socket connection successful
08-16 15:26:32.068  1044  1524 D LGWifiP2pService: P2pEnabledState
08-16 15:26:32.069  1044  1525 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-16 15:26:32.069  1044  1524 D LGWifiP2pService: sending p2p connection changed broadcast
08-16 15:26:32.069  1044  1525 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-16 15:26:32.069  1044  1524 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-16 15:26:32.070  1044  1525 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-16 15:26:32.070  1044  1525 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-16 15:26:32.070  1044  1524 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
,08-16 15:26:32.070  1044  1524 D WifiNative-p2p0: doBoolean: SET device_name G3
08-16 15:26:32.070  1044  1525 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-16 15:26:32.071  1044  1525 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-16 15:26:32.071  1044  1525 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-16 15:26:32.071  7463  7463 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-16 15:26:32.071  7494  7494 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 15:26:32.072  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-16 15:26:32.072  1927  1927 D WfdsService: WifiP2pState is changed : true
08-16 15:26:32.072  1044  1525 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-16 15:26:32.072  1927  2207 D WfdsService: Receive the WFDS_ENABLE Method
08-16 15:26:32.072  1927  2207 D WfdsService: Set the WFDS Monitor: true
08-16 15:26:32.072  1927  2207 D WfdsService: Connected to the supplicant for wfds
08-16 15:26:32.072  1927  2207 D WfdsJNI : doCommand: WFDS_SET TRUE
08-16 15:26:32.072  1927  1927 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
08-16 15:26:32.072  1044  1525 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-16 15:26:32.072  7463  7463 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-16 15:26:32.072  1927  2207 D WfdsService: selectPreferredScanChannel [36]
08-16 15:26:32.072  1927  2207 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-16 15:26:32.072  1044  1525 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-16 15:26:32.072  1927  1927 D WfdsService: isConnected: false
08-16 15:26:32.072  1044  1525 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-16 15:26:32.073  1044  1524 D WifiNative-p2p0: SET device_name G3: returned true
08-16 15:26:32.073  1044  1524 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-16 15:26:32.073  7463  7463 E wpa_supplicant: disconnect_rssi_lvl: -100
08-16 15:26:32.073  1044  1524 D LGWifiP2pService: before postfix = G3
08-16 15:26:32.073  1044  1524 D WifiServerServiceExt: postfix byte check : 2
08-16 15:26:32.073  1044  1524 D LGWifiP2pService: after postfix = G3
08-16 15:26:32.073  1044  1524 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-16 15:26:32.073  1044  1524 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-16 15:26:32.073  1044  1524 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-16 15:26:32.073  1044  1524 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-16 15:26:32.074  1044  1524 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-16 15:26:32.074  1044  1525 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 15:26:32.075  1044  1525 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 15:26:32.075  1044  1525 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 2 0 cz
08-16 15:26:32.075  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-16 15:26:32.075  1044  1524 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-16 15:26:32.075  1044  1524 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
08-16 15:26:32.076  7463  7463 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 15:26:32.077  7463  7463 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 15:26:32.077  7463  7463 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 15:26:32.077  7463  7463 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:26:32.078  7463  7463 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-16 15:26:32.079  1927  7511 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 15:26:32.079  1927  7511 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 15:26:32.079  1044  7493 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 15:26:32.079  1044  7493 E WifiMonitor: WifiMonitor:wlan0 cnt=24 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 15:26:32.079  1044  7493 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 15:26:32.079  1044  7493 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 15:26:32.079  1044  7493 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 15:26:32.079  1044  7493 E WifiMonitor: WifiMonitor:p2p0 cnt=25 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:26:32.079  1044  7493 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:26:32.080  1044  7493 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:26:32.080  1044  7493 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 15:26:32.080  1044  7493 E WifiMonitor: WifiMonitor:p2p0 cnt=26 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:26:32.080  1044  7493 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:26:32.080  1044  7493 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:26:32.080  1044  1525 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-16 15:26:32.080  1044  1525 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-16 15:26:32.081  1044  1524 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-16 15:26:32.081  1044  1524 D WifiNative-HAL: p2pGetDeviceAddress
08-16 15:26:32.081  1044  1524 D WifiNative-HAL: p2pGetDeviceAddress returning 02:9a:02:7f:fb:5d
08-16 15:26:32.082  1044  1524 D LGWifiP2pService: DeviceAddress: 02:9a:02:7f:fb:5d
08-16 15:26:32.082  1044  1524 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-16 15:26:32.082  1044  1524 D WifiNative-p2p0: P2P_FLUSH: returned true
08-16 15:26:32.082  1044  1524 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-16 15:26:32.083  1044  1524 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-16 15:26:32.083  1927  1927 I WfdStateTracker: handleP2pThisDeviceChanged
08-16 15:26:32.083  1044  1524 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-16 15:26:32.083  1927  1927 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-16 15:26:32.082  1044  1525 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-16 15:26:32.083  1927  1927 D WfdsService: Update P2p Interface State: 3
08-16 15:26:32.083  1044  1524 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-16 15:26:32.083  1044  1524 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-16 15:26:32.083  1044  1525 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-16 15:26:32.083  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-16 15:26:32.093  1044  1524 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-16 15:26:32.093  1044  1524 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-16 15:26:32.093  7463  7463 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-16 15:26:32.093  1044  1524 D LGWifiP2pService: InactiveState
08-16 15:26:32.093  7463  7463 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 15:26:32.093  1044  1524 D LGWifiP2pService: InactiveState{ when=-13ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
,08-16 15:26:32.094  1044  1524 D LGWifiP2pService: P2pEnabledState{ when=-13ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:32.094  1044  1524 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-16 15:26:32.094  1044  7493 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-16 15:26:32.094  1044  7493 E WifiMonitor: WifiMonitor:wlan0 cnt=27 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 15:26:32.094  1044  7493 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 15:26:32.094  1044  7493 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 15:26:32.094  1044  1525 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
,08-16 15:26:32.094  1044  1525 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
,08-16 15:26:32.098  1044  1525 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-16 15:26:32.098  1044  1525 D WifiNative-wlan0: doBoolean: SCAN
08-16 15:26:32.100  7463  7463 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 15:26:32.101  7463  7463 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 15:26:32.101  1044  7493 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 15:26:32.101  1927  7511 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 15:26:32.101  1044  7493 E WifiMonitor: WifiMonitor:p2p0 cnt=28 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 15:26:32.101  1044  7493 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 15:26:32.102  1044  7493 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 15:26:32.102  7463  7463 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 15:26:32.102  7463  7463 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:26:32.102  1927  7511 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 15:26:32.102  1044  1524 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-16 15:26:32.103  1044  1524 D LGWifiP2pService: InactiveState{ when=-20ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:32.103  1044  1524 D LGWifiP2pService: P2pEnabledState{ when=-20ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:32.103  7463  7463 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:26:32.103  1044  1524 D LGWifiP2pService: InactiveState{ when=-9ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:32.103  1044  1524 D LGWifiP2pService: P2pEnabledState{ when=-9ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:32.103  1044  1525 D WifiNative-wlan0: SCAN: returned false
08-16 15:26:32.103  1044  1524 D LGWifiP2pService: DefaultState{ when=-10ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:32.103  1044  1524 D LGWifiP2pService: InactiveState{ when=-10ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:32.103  1044  1524 D LGWifiP2pService: P2pEnabledState{ when=-10ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:32.103  1044  1524 D LGWifiP2pService: DefaultState{ when=-10ms what=139285 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:32.103  1044  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=353114  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 15:26:32.103  1044  1524 D LGWifiP2pService: InactiveState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:32.103  1044  1524 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:32.103  1044  7493 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 15:26:32.103  1044  1524 D LGWifiP2pService: DefaultState{ when=-1ms what=139287 arg2=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:32.104  1044  7493 E WifiMonitor: WifiMonitor:p2p0 cnt=29 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:26:32.104  1044  7493 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:26:32.104  1044  1524 D LGWifiP2pService: InactiveState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:32.104  1044  7493 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:26:32.104  1044  1524 D LGWifiP2,pService: P2pEnabledState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:32.104  1044  7493 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 15:26:32.104  1044  1524 D LGWifiP2pService: DefaultState{ when=-1ms what=139283 arg2=4 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:32.104  1044  7493 E WifiMonitor: WifiMonitor:p2p0 cnt=30 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:26:32.104  1044  7493 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:26:32.104  1927  7511 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 15:26:32.104  1044  7493 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:26:32.104  1044  1044 E WifiServerServiceExt: No p2p device connected
08-16 15:26:32.105  1044  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 23 0 rt=353116  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
,08-16 15:26:32.106  1927  2207 W WfdsService: DefaultState - msg [9441285] is not handled
08-16 15:26:32.106  1044  1525 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 15:26:32.107  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:26:32.107  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 15:26:32.107  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:32.107  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:32.107  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 15:26:32.108  1044  1525 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 15:26:32.108  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:32.109  1044  1525 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 15:26:32.109  1044  1525 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 15:26:32.109  1044  1525 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 15:26:32.110  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 15:26:32.110  1044  1044 D WifiServerServiceExt: setSupplicantStateSCANNING
08-16 15:26:32.340  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 15:26:32.343  6486  7122 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-16 15:26:32.368  2173  2173 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 15:26:32.386  7278  7278 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 15:26:32.386  7278  7278 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-16 15:26:32.386  7278  7278 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 15:26:32.386  7278  7278 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 15:26:32.388  7278  7278 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 15:26:32.393  7278  7278 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@37a4402e
08-16 15:26:32.393  7278  7278 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 15:26:32.393  7278  7278 D AppUp4:CustFacade: isPhone : true
08-16 15:26:32.393  7278  7278 D AppUp4:CustModeStarterReceiver: begin check event
08-16 15:26:32.394  7278  7278 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 15:26:32.398  4739  4739 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 15:26:32.398  4739  4739 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 15:26:32.400  4739  4739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 15:26:32.403  4739  4739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 15:26:32.410  4739  7521 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 15:26:32.411  7307  7307 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 15:26:32.415  4739  7522 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 15:26:32.416  4739  7522 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 15:26:32.434  7307  7525 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 15:26:32.441  3304  3304 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 15:26:32.441  3304  3304 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 15:26:32.441  3304  3304 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 15:26:32.449  7336  7336 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-16 15:26:32.449  7336  7336 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 15:26:32.451  7193  7528 W FormManager: Network not available. Please check & try again.
,08-16 15:26:32.462  7396  7396 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:26:32
,08-16 15:26:32.464  7193  7529 V FormManager: Network unavailable.
,08-16 15:26:32.466  1044  7493 E WifiMonitor: WifiMonitor:wlan0 cnt=31 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
08-16 15:26:32.466  1044  7493 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-16 15:26:32.466  1044  7493 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-16 15:26:32.466  1044  7493 E WifiMonitor: WifiMonitor:wlan0 cnt=32 dispatchEvent: WPS-AP-AVAILABLE 
08-16 15:26:32.466  7463  7463 E wpa_supplicant: USIM:  scard_init function
08-16 15:26:32.466  1044  7493 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-16 15:26:32.466  7463  7463 I wpa_supplicant: Trying to associate with SSID 'NG700'
08-16 15:26:32.466  1044  1525 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 15:26:32.467  1044  1525 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 15:26:32.467  1044  1525 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 15:26:32.468  1044  1525 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=8 bcn=0
08-16 15:26:32.468  1044  1525 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-16 15:26:32.468  1044  7493 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
08-16 15:26:32.469  1044  7493 E WifiMonitor: WifiMonitor:wlan0 cnt=33 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-16 15:26:32.470  7193  7529 V FormManager: Network unavailable.
08-16 15:26:32.470  7396  7396 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 15:26:32.470  7396  7396 D Weather.Utils: 2 : All the weather widget is gone.
08-16 15:26:32.472  7396  7396 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 15:26:32.474  7396  7396 D WeatherAncestor: connectivity changed - connection : true
08-16 15:26:32.474  7396  7396 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2df2155c
08-16 15:26:32.475  7396  7396 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 15:26:32.475  7396  7396 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 15:26:32.475  7396  7396 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 15:26:32.475  7396  7396 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 15:26:32.475  7396  7396 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:26:32
,08-16 15:26:32.477  1044  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=353488  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 15:26:32.482  1044  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 33 0 rt=353494  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 15:26:32.485  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:26:32.485  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 15:26:32.486  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:32.486  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:32.486  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 15:26:32.487  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:32.490  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:32.490  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:32.490  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 15:26:32.490  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 15:26:32.490  1044  1044 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-16 15:26:32.516  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:26:32.517  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 15:26:32.518  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:32.519  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
,08-16 15:26:32.519  7091  7091 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 15:26:32.519  7091  7091 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 15:26:32.519  7091  7091 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 15:26:32.520  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 15:26:32.520  7091  7091 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 15:26:32.520  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 15:26:32.520  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 15:26:32.520  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 15:26:32.521  7091  7091 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 15:26:32.521  7091  7091 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 15:26:32.528  7123  7123 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 15:26:32.531  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 15:26:32.538  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:26:32.543  7193  7532 W FormManager: Network not available. Please check & try again.
,08-16 15:26:32.556  7193  7533 V FormManager: Network unavailable.
,08-16 15:26:32.559  7123  7123 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 15:26:32.561  7193  7533 V FormManager: Network unavailable.
08-16 15:26:32.565  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 15:26:32.571  7193  7534 W FormManager: Network not available. Please check & try again.
,08-16 15:26:32.574  7463  7463 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
08-16 15:26:32.574  1044  7493 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-16 15:26:32.574  1044  7493 E WifiMonitor: WifiMonitor:wlan0 cnt=34 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-16 15:26:32.574  1044  7493 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-16 15:26:32.574  1044  7493 E WifiMonitor: WifiMonitor:wlan0 cnt=35 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-16 15:26:32.575  1044  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=353586  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 15:26:32.576  1044  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 34 0 rt=353587  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 15:26:32.576  1044  1525 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=353588
08-16 15:26:32.577  1044  1525 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=353588
08-16 15:26:32.577  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:26:32.577  1044  7493 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 15:26:32.577  1044  7493 E WifiMonitor: WifiMonitor:wlan0 cnt=36 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 15:26:32.578  1044  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 15:26:32.578  1044  1525 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=353589
08-16 15:26:32.579  1044  1525 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=353590
08-16 15:26:32.579  1044  1525 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 35 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=353590
,08-16 15:26:32.583  7193  7535 V FormManager: Network unavailable.
08-16 15:26:32.584  7463  7463 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 15:26:32.584  7463  7463 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 15:26:32.586  1044  7493 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 15:26:32.586  1044  7493 E WifiMonitor: WifiMonitor:wlan0 cnt=37 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 15:26:32.586  1044  7493 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-16 15:26:32.586  1044  7493 E WifiMonitor: WifiMonitor:wlan0 cnt=38 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 15:26:32.586  1044  7493 W WifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 15:26:32.586  1044  7493 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-16 15:26:32.586  1044  7493 E WifiMonitor: WifiMonitor:wlan0 cnt=39 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 15:26:32.586  1044  7493 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 15:26:32.586  1044  7493 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 15:26:32.587  1044  7493 E WifiMonitor: WifiMonitor:wlan0 cnt=40 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 15:26:32.588  1044  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=353599  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 15:26:32.589  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 15:26:32.589  1044  1044 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-16 15:26:32.591  7193  7535 V FormManager: Network unavailable.
08-16 15:26:32.593  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:32.593  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:32.593  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 15:26:32.593  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:26:32.593  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 15:26:32.595  1044  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 36 0 rt=353606  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 15:26:32.596  1044  1525 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-16 15:26:32.596  1044  1525 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-16 15:26:32.597  1044  1525 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 15:26:32.597  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:32.597  1044  1525 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 15:26:32.597  1044  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 15:26:32.600  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:32.601  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:32.601  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-16 15:26:32.601  1044  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=353612  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 15:26:32.602  1044  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 37 0 rt=353613  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 15:26:32.602  1044  1525 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=353613
08-16 15:26:32.603  1044  1525 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=353614
08-16 15:26:32.603  1044  1525 D WifiNative-wlan0: doString: [STATUS]
08-16 15:26:32.604  1044  7493 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 15:26:32.604  1044  7493 E WifiMonitor: WifiMonitor:wlan0 cnt=41 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 15:26:32.604  1044  1525 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 15:26:32.606  1044  1525 I WifiServiceExtension: setVHTCapabilityType  : false
,08-16 15:26:32.607  4739  4739 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 15:26:32.607  4739  4739 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 15:26:32.609  4739  4739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 15:26:32.611  1044  1525 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,08-16 15:26:32.611  1044  1525 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-16 15:26:32.612  4739  4739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 15:26:32.619  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:32.619  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:32.619  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:26:32.619  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 15:26:32.619  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
,08-16 15:26:32.620  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:32.621  4739  7536 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 15:26:32.623  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:26:32.623  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 15:26:32.624  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:32.626  4739  7537 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 15:26:32.626  4739  7537 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 15:26:32.683  1044  1981 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=7538 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-16 15:26:32.693  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:26:32.693  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 15:26:32.695  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:32.696  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:32.696  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:32.696  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 15:26:32.699  1044  1525 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
,08-16 15:26:32.699  1044  1531 D ConnectivityService: Got NetworkAgent Messenger
08-16 15:26:32.699  1044  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 15:26:32.699  1044  1531 D ConnectivityService: NetworkAgent connected
08-16 15:26:32.699  1044  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 15:26:32.700  1044  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 15:26:32.700  1044  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
,08-16 15:26:32.700  1044  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 15:26:32.707  1044  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 15:26:32.707  1044  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 15:26:32.707  1044  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 15:26:32.708  1044  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 15:26:32.708  1044  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 15:26:32.713  1044  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 15:26:32.715   321   903 D CommandListener: Setting iface cfg
,08-16 15:26:32.719  1044  7555 D DhcpStateMachine: StoppedState
08-16 15:26:32.719  1044  1525 E WifiStateMachine: Start Dhcp Watchdog 2
08-16 15:26:32.719  1044  7555 D DhcpStateMachine: StoppedState{ when=-1ms what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:32.719  1044  7555 D DhcpStateMachine: WaitBeforeStartState
08-16 15:26:32.720  1044  1525 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=353731  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 15:26:32.721  1044  1525 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=353732  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 15:26:32.722  1044  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 40 0 rt=353733  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 15:26:32.723  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 15:26:32.723  1044  1044 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-16 15:26:32.725  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 15:26:32.725  1044  1044 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-16 15:26:32.726  1044  1525 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=353737  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 15:26:32.727  1044  1525 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=353738  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 15:26:32.728  1044  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 41 0 rt=353739  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 15:26:32.730  1044  1525 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:307134] from screen [on:0 period:-1819789798] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 15:26:32.733  1044  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1819789796] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 15:26:32.733  1044  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 15:26:32.739  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:32.740  1044  1531 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 101] to 60
08-16 15:26:32.740  1044  1525 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
,08-16 15:26:32.740  1044  1525 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 15:26:32.741  1044  1525 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 15:26:32.741  1044  1525 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 15:26:32.742  1044  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 15:26:32.742  1044  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 15:26:32.743  1044  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 15:26:32.743  1044  1525 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=143,0,0
08-16 15:26:32.743  1044  1525 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=143,0,0
08-16 15:26:32.743  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-16 15:26:32.744  7463  7463 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-16 15:26:32.744  1044  1525 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-16 15:26:32.744  1044  1525 D WifiNative-wlan0: doBoolean: SET ps 0
08-16 15:26:32.745  1044  1525 D WifiNative-wlan0: SET ps 0: returned true
08-16 15:26:32.745  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-16 15:26:32.745  7463  7463 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-16 15:26:32.745  1044  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-16 15:26:32.746  1044  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3234da0c target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:32.746  1044  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@3234da0c target=com.android.internal.util.StateMachine$SmHandler }
,08-16 15:26:32.746  1044  1525 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-16 15:26:32.746  1044  7555 D DhcpStateMachine: WaitBeforeStartState{ when=0 what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:32.746  1044  1525 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 15:26:32.746  1044  7555 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-16 15:26:32.746  1044  1525 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 15:26:32.747   321   903 D CommandListener: Setting iface cfg
08-16 15:26:32.747   321   903 D CommandListener: Trying to bring up wlan0
08-16 15:26:32.749  1044  1525 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-16 15:26:32.749  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 15:26:32.749  1044  1044 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 15:26:32.750  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 15:26:32.750  1044  1044 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 15:26:32.750  1044  1525 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 15:26:32.751  1044  1525 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 15:26:32.751  1044  1525 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 15:26:32.751  1044  1525 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 15:26:32.752  1044  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 15:26:32.752  1044  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 15:26:32.753  1044  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 15:26:32.754  1044  1525 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 15:26:32.754  1044  1525 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK  v4
08-16 15:26:32.755  1044  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:32.755  1044  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:32.755  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 15:26:32.755  7463  7463 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 15:26:32.755  1044  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 15:26:32.755  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-16 15:26:32.756  7463  7463 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-16 15:26:32.756  1044  1525 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-16 15:26:32.756  1044  1525 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 15:26:32.772  1044  1525 D WifiNative-wlan0: SET ps 1: returned true
08-16 15:26:32.772  1044  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=false
08-16 15:26:32.773  1044  1525 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 15:26:32.773  1044  1525 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 15:26:32.773  1044  1525 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 15:26:32.774  1044  1531 D ConnectivityService: ignoring duplicate network state non-change
08-16 15:26:32.776  1044  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
,08-16 15:26:32.778  1044  1531 D ConnectivityService: Adding iface wlan0 to network 101
08-16 15:26:32.784  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:26:32.784  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 15:26:32.785  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:32.788  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:32.789  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:32.789  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-16 15:26:32.796  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:32.796  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:32.796  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 15:26:32.798  1044  1525 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 15:26:32.799  1044  1044 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 15:26:32.800  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 1
,08-16 15:26:32.804  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:32.805  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:32.805  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 15:26:32.805  1044  1044 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 15:26:32.806  1044  1531 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 15:26:32.806  1044  1531 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 101
08-16 15:26:32.807  1044  1531 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 101
08-16 15:26:32.808   321   903 E Netd    : netlink response contains error (File exists)
08-16 15:26:32.808  1044  1531 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 101
08-16 15:26:32.808  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:32.808  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:32.808  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 15:26:32.809  1044  1531 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-16 15:26:32.809  1044  1531 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 101
08-16 15:26:32.809  1044  1531 D ConnectivityService: Setting Dns servers for network 101 to [/192.168.1.1]
08-16 15:26:32.810  1044  1531 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 15:26:32.810  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:26:32.810  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 15:26:32.810  1044  1531 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 15:26:32.811  1044  1531 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 101]
,08-16 15:26:32.814  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:32.815  1044  7548 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-4ms what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:32.815  1044  7548 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-16 15:26:32.815  1044  7548 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:32.815  1044  7548 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 15:26:32.816  1044  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 15:26:32.816  1044  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 15:26:32.816  1044  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 15:26:32.816  1044  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 15:26:32.816  1044  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:26:32.817  1044  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-16 15:26:32.817  1044  1531 D ConnectivityService: currentScore = 0, newScore = 20
08-16 15:26:32.817  1044  1531 D ConnectivityService:    accepting network in place of null
08-16 15:26:32.817  1044  1531 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:26:32.817   321  7560 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 28
08-16 15:26:32.818  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:26:32.818  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 15:26:32.818  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:32.819  1044  1525 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:26:32.819  1839  1839 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:26:32.819  1044  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 15:26:32.820  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 15:26:32.821  1044  1531 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048,576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 15:26:32.821  1044  1531 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 15:26:32.821  7538  7538 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 15:26:32.821  1044  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 15:26:32.821  7538  7538 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
08-16 15:26:32.821  1044  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 15:26:32.821  1044  1531 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-16 15:26:32.822  1044  1044 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-16 15:26:32.822  1044  1044 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 15:26:32.822  1044  1044 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 15:26:32.822  1044  1044 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 15:26:32.823  1044  1531 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-16 15:26:32.823  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:26:32.823  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 15:26:32.823  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:32.824  1044  1531 D ConnectivityService: validation of new default Network = false
08-16 15:26:32.824  1044  1531 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-16 15:26:32.824  1044  1531 D DSQN    : enableDataServiceNotify 
08-16 15:26:32.824  1044  1531 D DSQN    : start dsqn bin
08-16 15:26:32.827  7538  7538 V [BNRBootReceiver]: Boot Receiver Return
08-16 15:26:32.827  7538  7538 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
,08-16 15:26:32.831  1044  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 15:26:32.831  1044  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:26:32.831  1044  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 15:26:32.831  1044  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 15:26:32.832  1589  2063 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 15:26:32.819  7562  7562 W dsqn    : type=1400 audit(0.0:169): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 15:26:32.819  7562  7562 W dsqn    : type=1400 audit(0.0:170): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 15:26:32.840  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 15:26:32.843  6818  7254 D UEI.SmartControl: Internal timer expired: 2
08-16 15:26:32.843  6818  7254 D UEI.SmartControl: unbind internal service
08-16 15:26:32.845  7562  7562 E DSQN    : DSQN ssw
,08-16 15:26:32.854  1803  7566 I CheckinService: active receiver: enabled
,08-16 15:26:32.861  1803  7566 I CheckinService: Preparing to send checkin request
08-16 15:26:32.861  1803  7566 I EventLogService: Accumulating logs since 1471353683726
08-16 15:26:32.863  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 15:26:32.865  1044  1523 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
,08-16 15:26:32.866   321  7560 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-16 15:26:32.871  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:26:32.876  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 15:26:32.877  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:32.878  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 15:26:32.879  7152  7152 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 15:26:32.879  7152  7152 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 15:26:32.880  7152  7152 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 15:26:32.881  1044  1942 I ActivityManager: Killing 7068:com.lge.lifetracker/u0a37 (adj 15): empty #17
08-16 15:26:32.905   321  7560 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-16 15:26:32.908  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-16 15:26:32.908  1044  1638 W libprocessgroup: failed to open /acct/uid_10037/pid_7068/cgroup.procs: No such file or directory
08-16 15:26:32.912  7091  7091 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-16 15:26:32.916  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 15:26:32.924  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 15:26:32.930  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:26:32.936  7152  7152 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 15:26:32.936  7152  7152 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 15:26:32.937  7152  7152 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 15:26:32.940  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 15:26:32.942   321   902 D LGDataListener: argv[0]=dsqncommand
08-16 15:26:32.942   321   902 D LGDataListener: argv[1]=wlan0
08-16 15:26:32.942   321   902 D LGDataListener: argv[2]=1
08-16 15:26:32.942   321   902 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-16 15:26:32.942  1044  1117 D DSQN    : DSQM DsqnNotification wlan0  1
08-16 15:26:32.943  1044  1117 D DSQN    : start to monitor internet connection
08-16 15:26:32.948  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 15:26:32.949  1044  7555 D DhcpStateMachine: DHCPV4 request on wlan0
08-16 15:26:32.949  1044  7555 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-16 15:26:32.949  1044  7555 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-16 15:26:32.939  7571  7571 W dhcpcd  : type=1400 audit(0.0:171): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 15:26:32.939  7571  7571 W dhcpcd  : type=1400 audit(0.0:172): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
,08-16 15:26:32.956  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:26:32.960  7571  7571 I dhcpcd  : version 5.5.6 starting
08-16 15:26:32.961  7152  7152 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 15:26:32.961  7152  7152 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 15:26:32.961  7152  7152 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 15:26:32.962  7571  7571 E dhcpcd  : get_duid: m
08-16 15:26:32.962  7571  7571 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-16 15:26:32.962  7571  7571 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
08-16 15:26:32.964  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 15:26:32.964  7091  7091 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 15:26:32.964  7091  7091 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 15:26:32.964  7091  7091 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 15:26:32.964  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-16 15:26:32.965  7091  7091 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 15:26:32.965  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
08-16 15:26:32.965  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 15:26:32.965  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 15:26:32.965  7091  7091 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 15:26:32.965  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 15:26:32.966  7091  7091 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 15:26:32.969  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 15:26:32.974  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 15:26:32.979  1044  7548 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 13:26:32 GMT], X-Android-Received-Millis=[1471353992978], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471353992942]}
08-16 15:26:32.979  1044  7548 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 15:26:32.979  1044  7548 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 15:26:32.979  1044  1531 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 101]
08-16 15:26:32.980  1044  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 101]
08-16 15:26:32.980  1044  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 15:26:32.980  1044  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 15:26:32.980  1044  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
,08-16 15:26:32.980  1044  1531 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 101] was already satisfying request 1. No change.
08-16 15:26:32.980  1044  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 101]
08-16 15:26:32.980  1044  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:26:32.980  1044  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 15:26:32.980  6818  7251 D serial_port: close(fd = 24)
08-16 15:26:32.980  1044  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 15:26:32.980  1044  1531 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:26:32.981  1044  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 15:26:32.981  1589  2063 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 15:26:32.981  1044  1525 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:26:32.981  1044  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 15:26:32.981  1839  1839 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:26:32.981  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 15:26:32.984  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:26:32.986  6818  7251 I UEI.SmartControl: Serial port is closed.
08-16 15:26:32.992  7152  7152 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 15:26:32.992  7152  7152 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 15:26:32.992  7152  7152 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 15:26:33.001  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 15:26:33.009  1803  7566 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-16 15:26:33.009  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 15:26:33.013  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 15:26:33.014  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:33.014  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:33.017  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:26:33.022  7152  7152 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 15:26:33.022  7152  7152 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 15:26:33.022  7152  7152 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 15:26:33.026  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 15:26:33.031  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 15:26:33.036  7571  7571 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 15:26:33.036  7571  7571 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 15:26:33.036  7571  7571 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 15:26:33.036  7571  7571 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-16 15:26:33.036  7571  7571 D dhcpcd  : wlan0: sending REQUEST (xid 0x3b3348be), next in 4.64 seconds
,08-16 15:26:33.037  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:26:33.042  7152  7152 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 15:26:33.042  7152  7152 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 15:26:33.042  7152  7152 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 15:26:33.044  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 15:26:33.051  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 15:26:33.055  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:26:33.060  7152  7152 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 15:26:33.060  7152  7152 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 15:26:33.060  7152  7152 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 15:26:33.064  7571  7571 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-16 15:26:33.065  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 15:26:33.073  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 15:26:33.079  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:26:33.084  7152  7152 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 15:26:33.084  7571  7571 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-16 15:26:33.084  7571  7571 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-16 15:26:33.084  7152  7152 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 15:26:33.084  7571  7571 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-16 15:26:33.085  7571  7571 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-16 15:26:33.085  7571  7571 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 15:26:33.085  7571  7571 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 15:26:33.085  7571  7571 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 15:26:33.085  7571  7571 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-16 15:26:33.090  7152  7152 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 15:26:33.128  1044  1059 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=7583 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
,08-16 15:26:33.131  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 15:26:33.138  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 15:26:33.142  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:26:33.147  7152  7152 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 15:26:33.148  7152  7152 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 15:26:33.148  7152  7152 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 15:26:33.156  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 15:26:33.161  7123  7123 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 15:26:33.171  7123  7123 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 15:26:33.173  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 15:26:33.184  7583  7583 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
08-16 15:26:33.184  7583  7583 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-16 15:26:33.185  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:26:33.191  7152  7152 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 15:26:33.191  7152  7152 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 15:26:33.192  7152  7152 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 15:26:33.192  7152  7152 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 15:26:33.192  7152  7152 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 15:26:33.197  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 15:26:33.199  7123  7123 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 15:26:33.200  7123  7123 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 15:26:33.202  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 15:26:33.206  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:26:33.216  7152  7152 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 15:26:33.216  7152  7152 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 15:26:33.216  7152  7152 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 15:26:33.217  7152  7152 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 15:26:33.217  7152  7152 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 15:26:33.218  7583  7583 I MultiDex: VM with version 2.1.0 has multidex support
08-16 15:26:33.218  7583  7583 I MultiDex: install
08-16 15:26:33.218  7583  7583 I MultiDex: VM has multidex support, MultiDex support library is disabled.
,08-16 15:26:33.225  7583  7583 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
08-16 15:26:33.228  2173  2173 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
08-16 15:26:33.235  2173  2173 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
08-16 15:26:33.235  2173  2173 D c       : Getting all permits...
08-16 15:26:33.235  2173  2173 D a       : Opening database...
,08-16 15:26:33.241  2173  2173 D a       : Opening database auth.proximity.permit_store...
08-16 15:26:33.241  2173  2173 D a       : Closing database...
08-16 15:26:33.353  1044  7555 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-16 15:26:33.355  1044  7555 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-16 15:26:33.356  1044  7555 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 15:26:33.357  1044  7555 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-16 15:26:33.357  1044  7555 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-16 15:26:33.357  1044  7555 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 15:26:33.357  1044  7555 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-16 15:26:33.357  1044  7555 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-16 15:26:33.358  1044  7555 D DhcpStateMachine: RunningState
08-16 15:26:33.546  7583  7600 D LgDataFeature: LgDataFeature() Constructor: none
08-16 15:26:33.546  7583  7600 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 15:26:33.600  7630  7630 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-16 15:26:33.655  7630  7630 I dex2oat : dex2oat took 54.669ms (threads: 4)
,08-16 15:26:33.674  7583  7600 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 15:26:33.674  7583  7600 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 15:26:33.674  7583  7600 I Adreno-EGL: Build Date: 12/12/14 금
08-16 15:26:33.674  7583  7600 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 15:26:33.674  7583  7600 I Adreno-EGL: Remote Branch: 
08-16 15:26:33.674  7583  7600 I Adreno-EGL: Local Patches: 
08-16 15:26:33.674  7583  7600 I Adreno-EGL: Reconstruct Branch: 
,08-16 15:26:33.813  7583  7600 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 15:26:33.813  7583  7600 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 15:26:33.813  7583  7600 I Adreno-EGL: Build Date: 12/12/14 금
08-16 15:26:33.813  7583  7600 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 15:26:33.813  7583  7600 I Adreno-EGL: Remote Branch: 
08-16 15:26:33.813  7583  7600 I Adreno-EGL: Local Patches: 
08-16 15:26:33.813  7583  7600 I Adreno-EGL: Reconstruct Branch: 
,08-16 15:26:33.832  1044  1531 D ConnectivityService: NetTransition Wakelock (NetworkAgentInfo [WIFI () - 100] cleared because we found a replacement network
,08-16 15:26:33.895  7583  7600 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 15:26:33.895  7583  7600 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 15:26:33.895  7583  7600 I Adreno-EGL: Build Date: 12/12/14 금
08-16 15:26:33.895  7583  7600 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 15:26:33.895  7583  7600 I Adreno-EGL: Remote Branch: 
08-16 15:26:33.895  7583  7600 I Adreno-EGL: Local Patches: 
08-16 15:26:33.895  7583  7600 I Adreno-EGL: Reconstruct Branch: 
,08-16 15:26:34.125   321  7637 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-16 15:26:34.125   321  7637 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
08-16 15:26:34.691  1044  1525 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 15:26:34.693  1044  1525 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-16 15:26:34.704  1044  1525 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-16 15:26:34.706  1044  1525 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 15:26:34.706  1044  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 15:26:34.707  1044  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 15:26:34.708  1044  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 101]; created=true
08-16 15:26:34.708  1044  1531 D ConnectivityService: identical MTU - not setting
08-16 15:26:34.708  1044  1531 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 15:26:34.708  1044  1531 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 101]
08-16 15:26:34.708  1044  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:26:34.708  1044  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 15:26:34.709  1044  1531 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 15:26:34.710  1589  2063 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
08-16 15:26:35.311   321  7637 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-16 15:26:35.742  1044  1525 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=71.5, 0.0, 0.0  rx=77.0 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1819786787] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 15:26:35.743  1044  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 4 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=71.5, 0.0, 0.0  rx=77.0 bcn=0 [on:0 tx:0 rx:0 period:2] from screen [on:0 period:-1819786785] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 15:26:35.743  1044  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 15:26:35.750  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 15:26:35.802  1044  1526 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-16 15:26:35.822  1044  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 15:26:35.829  1044  1119 D Tethering: MasterInitialState.processMessage what=3
,08-16 15:26:35.878  1044  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 15:26:35.885  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:35.885  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:26:35.885  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:35.885  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:35.885  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:26:35.885  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:26:35.885  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:26:35.885  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:26:35.885  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 15:26:35.886  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:35.886  6974  6974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 15:26:35.891  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:35.891  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:26:35.891  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:35.891  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:35.891  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:26:35.891  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:26:35.891  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:26:35.891  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:26:35.891  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 15:26:35.891  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:35.891  6974  6974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 15:26:35.893  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:35.893  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:26:35.893  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:35.893  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:35.893  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:26:35.893  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:26:35.893  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:26:35.893  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active net,work: true
08-16 15:26:35.893  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 15:26:35.893  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:35.893  6974  6974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 15:26:35.905  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 15:26:35.907  6486  7122 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-16 15:26:35.930  5808  5808 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-16 15:26:35.935  1044  1977 D WifiServiceImplEx: setWifiEnabled: false pid=6974, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 15:26:35.935  1044  1977 D WifiService: setWifiEnabled: false pid=6974, uid=10118
08-16 15:26:35.935  1044  1977 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 15:26:35.947  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 15:26:35.947  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 15:26:35.948  1044  1044 D Ulp_jni : JNI:system_update. Event-4
,08-16 15:26:35.951  1044  1525 E WifiStateMachine:  ConnectedState CMD_STOP_SUPPLICANT 0 0
08-16 15:26:35.952  1044  1525 E WifiStateMachine:  L2ConnectedState CMD_STOP_SUPPLICANT 0 0
,08-16 15:26:35.952  1044  1525 E WifiStateMachine:  ConnectModeState CMD_STOP_SUPPLICANT 0 0
08-16 15:26:35.953  1044  1525 E WifiStateMachine:  DriverStartedState CMD_STOP_SUPPLICANT 0 0
08-16 15:26:35.953  1044  1525 E WifiStateMachine:  SupplicantStartedState CMD_STOP_SUPPLICANT 0 0
08-16 15:26:35.953  1044  1525 E WifiStateMachine: WifiStateMachine: Leaving Connected state
08-16 15:26:35.953  1044  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 15:26:35.953  1044  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
08-16 15:26:35.957  1044  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 15:26:35.957  1044  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
,08-16 15:26:35.969  1044  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 15:26:35.969  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 15:26:35.970  7463  7463 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 15:26:35.970  1044  1524 D LGWifiP2pService: InactiveState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:35.970  1044  1524 D LGWifiP2pService: P2pEnabledState{ when=-1ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:35.970  1044  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 15:26:35.970  1044  1525 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 15:26:35.971  1044  1525 D WifiNative-wlan0: SET ps 1: returned true
08-16 15:26:35.972  1044  7555 D DhcpStateMachine: RunningState{ when=0 what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:35.972   321   903 D CommandListener: Clearing all IP addresses on wlan0
08-16 15:26:35.973  1044  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:26:36.004  2173  2173 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 15:26:36.014   321  7661 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 15:26:36.016  1044  1117 D DSQN    : Dns fail occured do internet check.
08-16 15:26:36.017  7278  7278 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 15:26:36.017  7278  7278 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 15:26:36.017  1044  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 15:26:36.017  7278  7278 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 15:26:36.017  7278  7278 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 15:26:36.017  1044  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 15:26:36.018  1044  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 15:26:36.018  1044  1044 D DSQN    : EVENT_INTERNET_CHECK_REQUEST received
08-16 15:26:36.018  1044  1044 D DSQN    : try Internet connection check
08-16 15:26:36.018  1044  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] EVENT_NETWORK_INFO_CHANGED, going from CONNECTED to DISCONNECTED
08-16 15:26:36.018  1044  1531 D ConnectivityService: ignoring duplicate network state non-change
08-16 15:26:36.018  1044  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 101] got DISCONNECTED, was satisfying 2
08-16 15:26:36.019  1044  1524 D LGWifiP2pService: InactiveState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:36.019  1044  1524 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=131204 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:36.019  1044  1524 D WifiMonitor: stopMonitoring(p2p0) = com.android.server.wifi.p2p.LGWifiP2pServiceImpl$P2pStateMachine@cb7c87c
08-16 15:26:36.019  1044  1525 D WifiNetworkAgent: NetworkAgent: NetworkAgent channel lost
,08-16 15:26:36.020  1044  1044 D WifiHS20: hidePasspointNotification off =false
08-16 15:26:36.023  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 0
08-16 15:26:36.023  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:26:36.023  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 15:26:36.024  1044  1907 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 101]) by 10005
08-16 15:26:36.024  1044  7548 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:36.024  1044  7548 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:36.024  1044  7548 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 15:26:36.024  1044  7548 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:36.025  1044  7548 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on <unknown ssid>
08-16 15:26:36.035  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:36.036  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:36.036  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
,08-16 15:26:36.037  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:36.040  1044  1044 D WifiHS20: hidePasspointNotification off =false
,08-16 15:26:36.041  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:26:36.041  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 15:26:36.042  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:36.042  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:36.042  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 15:26:36.042  1044  1044 D WifiScanningService: SCAN_AVAILABLE : 1
08-16 15:26:36.042  1044  1044 D RttService: SCAN_AVAILABLE : 1
08-16 15:26:36.042  1044  1543 D WifiScanningService: DefaultState got{ when=0 what=160007 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:36.043  1044  1544 D RttService: EnabledState got{ when=0 what=160513 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:36.043  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:36.045  7278  7278 I AppUp4:CustModeStarterReceiver: onReceive
08-16 15:26:36.046  1044  1524 D LGWifiP2pService: P2pDisablingState
08-16 15:26:36.046  1044  1524 D LGWifiP2pService: P2pDisablingState{ when=-27ms what=147458 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:36.047  1044  1524 D LGWifiP2pService: p2p socket connection lost
08-16 15:26:36.047  1044  1524 D LGWifiP2pService: P2pDisabledState
08-16 15:26:36.047  1044  1525 E WifiStateMachine:  WaitForP2pDisableState CMD_DISABLE_P2P_RSP uid=1000 0 0
08-16 15:26:36.047  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 15:26:36.048  7463  7463 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 15:26:36.048  1044  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 15:26:36.048  1044  1525 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 15:26:36.048  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 15:26:36.048  1927  1927 D WfdsService: WifiP2pState is changed : false
08-16 15:26:36.048  1927  2207 D WfdsService: WfdsEnabledState: Receive the WFDS_DISABLE message
08-16 15:26:36.049  1927  2207 D WfdsService: Set the WFDS Monitor: false
08-16 15:26:36.050  1927  2207 D WfdsMonitor: WFDS Monitor is stopped
08-16 15:26:36.050  1927  2207 D WfdsService: STATE : WfdsDisabledState - enter
08-16 15:26:36.050  1927  7511 D CtrlSupplicant: Received on exit socket, terminate
08-16 15:26:36.050  1927  7511 E CtrlSupplicant: wfds_wait_for_event: buf = CTRL-EVENT-TERMINATING  - connection closed
08-16 15:26:36.050  1044  1524 D LGWifiP2pService: P2pDisabledState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:36.050  1927  7511 D WfdsMonitor: Event [CTRL-EVENT-TERMINATING  - connection closed]
08-16 15:26:36.050  1044  1524 D LGWifiP2pService: DefaultState{ when=-3ms what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:36.050  1927  7511 D WfdsMonitor: WfdsMonitorThread is received the interrupt - closing
08-16 15:26:36.051  1927  2228 W WfdsSession:Controller: DefaultState - msg [9441355] is not handled
08-16 15:26:36.051  1927  2207 W WfdsService: DefaultState - msg [9445378] is not handled
08-16 15:26:36.051  1044  1525 D WifiNative-wlan0: SET ps 1: returned true
08-16 15:26:36.051  7278  7278 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@37a4402e
08-16 15:26:36.051  7278  7278 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 15:26:36.051  7278  7278 D AppUp4:CustFacade: isPhone : true
08-16 15:26:36.052  7278  7278 D AppUp4:CustModeStarterReceiver: b,egin check event
08-16 15:26:36.052  7278  7278 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 15:26:36.057  4739  4739 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 15:26:36.057  4739  4739 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 15:26:36.058  4739  4739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 15:26:36.062  4739  4739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 15:26:36.068  7307  7307 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 15:26:36.071   321   903 D CommandListener: Clearing all IP addresses on wlan0
08-16 15:26:36.071  1044  1531 D ConnectivityService: Default network via Wi-Fi disconnect. stop DSQN
08-16 15:26:36.071  1044  1531 D DSQN    : disableDataServiceNotify
08-16 15:26:36.071  1044  1531 D DSQN    : stop dsqn bin
08-16 15:26:36.071  4739  7668 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 15:26:36.072   321  7671 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 15:26:36.072  1044  7664 D DSQN    : ThreadTCPConnectionCheck DNS fail internet is not possible
08-16 15:26:36.072   321  7670 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=0
08-16 15:26:36.072  1044  7662 D DSQN    : ThreadInternetCheck internet check NOK 
08-16 15:26:36.072  1044  7662 D DSQN    : InternetcheckProgress is not set don't send DS quality intent
08-16 15:26:36.073  1044  7548 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Probably not a portal: exception java.net.UnknownHostException: Unable to resolve host "clients3.google.com": No address associated with hostname
08-16 15:26:36.074  1803  7566 E CheckinTask: Checkin failed: https://android.clients.google.com/checkin (request #0): java.net.ConnectException: failed to connect to android.clients.google.com/216.58.214.46 (port 443) after 120000ms: connect failed: ENETUNREACH (Network is unreachable)
08-16 15:26:36.074  1044  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 15:26:36.074  1044  1117 D DSQN    : DNSproblemNotiEnabled is disabled ignore DNS fail CB
08-16 15:26:36.074  1044  1525 D WifiNative-p2p0: doBoolean: TERMINATE
08-16 15:26:36.075  4739  7669 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 15:26:36.075  4739  7669 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 15:26:36.076  1044  1044 D WifiHS20: hidePasspointNotification off =false
08-16 15:26:36.077  1044  1531 D ConnectivityService: notifyType LOST for NetworkAgentInfo [WIFI () - 101]
08-16 15:26:36.077  1044  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:26:36.077  1044  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 15:26:36.078  1044  1531 D ConnectivityService: sending notification LOST for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 15:26:36.078  1044  1531 D Nat464Xlat: requiresClat: netType=1, connected=false, hasIPv4Address=true, hasInternetCapability=true
08-16 15:26:36.078  1589  2063 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524292
08-16 15:26:36.078  1044  1531 D CSLegacyTypeTracker: [lge_data] remove agent NetworkAgentInfo{ ni{[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{101}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,fe80::c69a:2ff:fe7f:fb5d/64,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{60} validated{true} created{true} explicitlySelected{false} } list []  wasFirstNetwork :true
08-16 15:26:36.078  1044  1531 D CSLegacyTypeTracker: Sending disconnected broadcast for type 1 NetworkAgentInfo [WIFI () - 101] isDefaultNetwork=true
08-16 15:26:36.078  1044  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 15:26:36.079  1044  7548 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:36.079  1044  7548 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-1ms what=532487 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:36.079  1044  7548 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Disconnected - quitting
08-16 15:26:36.079  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:36.079  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:36.079  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 15:26:36.080  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: false, isConnectedToProvisioningNetwork: false]
08-16 15:26:36.080  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 15:26:36.082  1044  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 15:26:36.082  1044  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 15:26:36.082  1044  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 15:26:36.082  1044  1531 D ConnectivityService: Checking for replacement network to handle request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:26:36.082  1044  1531 D ConnectivityService: sending new Min Network Score(0): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:26:36.083  1044  1531 D NetworkManagementService: Removing idletimer
08-16 15:26:36.083  1044  1531 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:36.083  1839  1839 D TelephonyNetworkFactory-1: new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:26:36.083  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 15:26:36.084  1044  1523 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 15:26:36.084  1044  1525 D WifiNative-p2p0: TERMINATE: returned true
08-16 15:26:36.084  1044  1044 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 15:26:36.084  1044  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 15:26:36.084  1044  1525 E WifiStateMachine: useWiFiOffloading() : false
08-16 15:26:36.084  1044  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 15:26:36.084  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:36.084  1044  1044 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 15:26:36.084  1044  1044 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 15:26:36.084  1044  1044 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 15:26:36.086  1044  1523 V NetworkPolicy: [LG_RESTRICTED] !!!isConnected  type  :1
08-16 15:26:36.086  1044  1044 D LocSvc_java: Sending msg: 4 arg1:0 arg2:1
08-16 15:26:36.087  1044  1525 D WIFI    : new score 0 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:26:36.087  1044  1044 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 15:26:36.087  1044  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 15:26:36.087  1044  1044 D LocSvc_java: updateNetworkState connTyp: 4 unavailable info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 15:26:36.087  1044  1044 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 15:26:36.089  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 6
08-16 15:26:36.091  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [0]
08-16 15:26:36.091  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 15:26:36.091  1044  1044 D WifiServerServiceExt: setSupplicantStateDISCONNECTED
08-16 15:26:36.092  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:36.092  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:26:36.092  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:36.092  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:36.092  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:26:36.092  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:26:36.092  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:26:36.092  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:26:36.092  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:26:36.092  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:36.092  6974  6974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:26:36.093  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:36.093  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:26:36.093  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:36.093  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:36.093  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:26:36.093  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:26:36.093  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:26:36.093  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:26:36.093  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:26:36.093  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:36.093  6974  6974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:26:36.094  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:36.094  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:26:36.094  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:36.094  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:36.094  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:26:36.094  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:26:36.094  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:26:36.094  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:26:36.094  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:26:36.094  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:36.094  6974  6974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:26:36.096  7307  7672 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:36.101  1803  7566 I CheckinService: active receiver: disabled
08-16 15:26:36.109  3304  3304 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 15:26:36.109  3304  3304 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 15:26:36.109  3304  3304 I LgeMiscReceiver: networkInfo.isConnected() = true
08-16 15:26:36.109  3304  3304 D PhoneState: setPdpRejectCasuse : false
08-16 15:26:36.114  7336  7336 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 15:26:36.114  7336  7336 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 15:26:36.116  7193  7676 W FormManager: Network not available. Please check & try again.
,08-16 15:26:36.123  1803  7678 I CheckinService: active receiver: disabled
08-16 15:26:36.123  7193  7677 V FormManager: Network unavailable.
08-16 15:26:36.126  7396  7396 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:26:36
08-16 15:26:36.127  7396  7396 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 15:26:36.127  7396  7396 D Weather.Utils: 2 : All the weather widget is gone.
08-16 15:26:36.128  7396  7396 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 15:26:36.128  7396  7396 D WeatherAncestor: connectivity changed - connection : true
08-16 15:26:36.128  7396  7396 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2df2155c
08-16 15:26:36.128  7396  7396 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 15:26:36.128  7396  7396 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 15:26:36.128  7396  7396 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 15:26:36.128  7396  7396 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 15:26:36.128  7396  7396 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:26:36
08-16 15:26:36.133  7193  7677 V FormManager: Network unavailable.
08-16 15:26:36.138  7463  7463 I wpa_supplicant: p2p0: CTRL-EVENT-TERMINATING 
08-16 15:26:36.138  7463  7463 I wpa_supplicant: monitor socket send errors count : 1
08-16 15:26:36.138  7463  7463 I wpa_supplicant: CTRL_IFACE: Detach monitor /data/misc/wifi/sockets/wpa_ctrl_1927-4\x00 that cannot receive messages
08-16 15:26:36.139  1044  7493 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-TERMINATING ]
08-16 15:26:36.139  1044  7493 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 15:26:36.141  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 15:26:36.143  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:36.143  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:36.151  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 15:26:36.154  7123  7123 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 15:26:36.154  7123  7123 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 15:26:36.154  7123  7123 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 15:26:36.157  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 15:26:36.161  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:26:36.166  7152  7152 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 15:26:36.166  7152  7152 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 15:26:36.169  7152  7152 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 15:26:36.172  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 15:26:36.175  7123  7123 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 15:26:36.175  7123  7123 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 15:26:36.175  7123  7123 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 15:26:36.177  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 15:26:36.183  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 15:26:36.183  7463  7463 I wpa_supplicant: wlan0: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 15:26:36.184  1044  7493 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1]
08-16 15:26:36.184  1044  7493 E WifiMonitor: WifiMonitor:wlan0 cnt=42 dispatchEvent: CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 15:26:36.184  1044  7493 E WifiMonitor: handleEvent 2  CTRL-EVENT-DISCONNECTED bssid=f4:f2:6d:22:99:3e reason=3 locally_generated=1
08-16 15:26:36.184  7463  7463 W wpa_supplicant: USIM:  scard_deinit function
08-16 15:26:36.184  1044  7493 E WifiMonitor: WifiMonitor notify network disconnect: f4:f2:6d:22:99:3e reason=3
08-16 15:26:36.185  1044  7493 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 15:26:36.185  1044  7493 E WifiMonitor: WifiMonitor:wlan0 cnt=43 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=0 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 15:26:36.185  1044  1525 E WifiStateMachine:  SupplicantStoppingState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=357196
08-16 15:26:36.185  1044  1525 E WifiStateMachine:  DefaultState NETWORK_DISCONNECTION_EVENT f4:f2:6d:22:99:3e nid=1 reason=3 rt=357196
08-16 15:26:36.185  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:36.186  1044  1525 E WifiStateMachine:  SupplicantStoppingState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=357197  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 15:26:36.186  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:36.186  1044  1525 E WifiStateMachine:  DefaultState SUPPLICANT_STATE_CHANGE_EVENT 43 0 rt=357197  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: DISCONNECTED
08-16 15:26:36.186  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:36.186  1044  7555 D DhcpStateMachine: StoppedState
08-16 15:26:36.187  1044  7555 D DhcpStateMachine: StoppedState{ when=-135ms what=196610 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:36.187  1044  1119 D Tethering: InitialState.processMessage what=4
08-16 15:26:36.188  1044  1525 E WifiStateMachine:  SupplicantStoppingState CMD_ON_QUIT 0 0
08-16 15:26:36.188  1044  1525 E WifiStateMachine:  DefaultState CMD_ON_QUIT 0 0
08-16 15:26:36.188  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 15:26:36.189  1044  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
08-16 15:26:36.189  1044  1525 E WifiStateMachine:  SupplicantStoppingState CMD_TETHER_STATE_CHANGE 0 0
08-16 15:26:36.189  1044  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
,08-16 15:26:36.196  7152  7152 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 15:26:36.197  7152  7152 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 15:26:36.198  7152  7152 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 15:26:36.200  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 15:26:36.203  7123  7123 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : DISCONNECTED/IDLE
08-16 15:26:36.203  7123  7123 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 15:26:36.203  7123  7123 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 15:26:36.207  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 15:26:36.211  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:26:36.217  7152  7152 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 15:26:36.217  7152  7152 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 15:26:36.218  7152  7152 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
,08-16 15:26:36.225  7123  7123 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 15:26:36.229  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 15:26:36.231  7193  7681 W FormManager: Network not available. Please check & try again.
,08-16 15:26:36.235  7193  7682 V FormManager: Network unavailable.
08-16 15:26:36.236  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:26:36.240  7193  7682 V FormManager: Network unavailable.
08-16 15:26:36.253  2173  2173 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-16 15:26:36.255  7463  7463 I wpa_supplicant: wlan0: CTRL-EVENT-TERMINATING 
,08-16 15:26:36.256  1044  7493 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-TERMINATING ]
08-16 15:26:36.256  1044  7493 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-TERMINATING 
08-16 15:26:36.256  1044  7493 D WifiMonitor: Disconnecting from the supplicant, no more events
08-16 15:26:36.258  1044  1525 E WifiStateMachine:  SupplicantStoppingState SUP_DISCONNECTION_EVENT 44 0
08-16 15:26:36.266  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 15:26:36.266  7091  7091 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 15:26:36.266  7091  7091 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 15:26:36.266  7091  7091 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 15:26:36.267  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 15:26:36.267  7091  7091 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 15:26:36.267  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 15:26:36.267  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 15:26:36.267  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 15:26:36.268  7091  7091 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 15:26:36.268  7091  7091 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-16 15:26:36.331  7415  7435 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-16 15:26:36.358  1044  1525 D WifiOffDelayIfNotUsed: stopMonitoring
08-16 15:26:36.358  1044  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 15:26:36.358  1044  1525 E WifiStateMachine: useWiFiOffloading() : false
08-16 15:26:36.358  1044  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-16 15:26:36.361  1927  1927 D WfdsService: Supplicant Connection state is changed : false
08-16 15:26:36.361  1927  2207 D WfdsService: DefaultState - WIFI_SUPPLICANT_DISCONNECTED
08-16 15:26:36.361  1927  2207 D WfdsService: Set the WFDS Monitor: false
,08-16 15:26:36.361  1927  2207 D WfdsMonitor: WFDS Monitor is stopped
08-16 15:26:36.365  4739  4739 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 15:26:36.366  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:26:36.366  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 0
08-16 15:26:36.366  4739  4739 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 15:26:36.368  2470  2470 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:36.371  4739  4739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 15:26:36.372  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:36.373  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:26:36.375  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:36.379  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [1]
08-16 15:26:36.379  1044  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:1
08-16 15:26:36.379  1044  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : this is not treated
08-16 15:26:36.380  4739  4739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 15:26:36.391  7123  7123 I PCSuite : [StartReceiver]WIFI_STATE_CHANGED_ACTION : WIFI_STATE_DISABLED
,08-16 15:26:36.391  7123  7123 D PCSuite : [StartReceiver][getUpdateNecessity]update = false
08-16 15:26:36.391  7123  7123 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 15:26:36.395  4739  7685 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 15:26:36.396  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 15:26:36.397  4739  7689 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 15:26:36.397  4739  7689 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 15:26:36.405  7193  7688 V FormManager: Network unavailable.
08-16 15:26:36.406  7193  7687 W FormManager: Network not available. Please check & try again.
08-16 15:26:36.407  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:26:36.407  7193  7688 V FormManager: Network unavailable.
08-16 15:26:36.732  1044  1115 W ProcessCpuTracker: Skipping unknown process pid 7646
,08-16 15:26:36.734  1044  1115 W ProcessCpuTracker: Skipping unknown process pid 7649
08-16 15:26:37.073  1044  1044 D DSQN    : EVENT_INTERNET_CHECK_ENABLE received
,08-16 15:26:37.326  1044  2018 I ActivityManager: Killing 7169:com.lge.settings.easy/1000 (adj 15): empty #17
,08-16 15:26:37.358  1044  2009 W libprocessgroup: failed to open /acct/uid_1000/pid_7169/cgroup.procs: No such file or directory
,08-16 15:26:38.757  1044  1525 E WifiStateMachine:  InitialState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1819783772] gl rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 15:26:38.759  1044  1525 E WifiStateMachine:  DefaultState CMD_RSSI_POLL 4 0 <unknown ssid> rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1819783769] gl rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 15:26:39.086  1044  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 15:26:39.100  1044  1119 D Tethering: MasterInitialState.processMessage what=3
08-16 15:26:39.113  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:26:39.118  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:39.120  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:39.122  1044  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
08-16 15:26:39.129  1044  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 15:26:39.132  1044  1119 D Tethering: MasterInitialState.processMessage what=3
08-16 15:26:39.141  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:26:39.145  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:39.146  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:39.149  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 15:26:39.150  6486  7122 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 15:26:39.165  5808  5808 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 15:26:39.173  5808  5808 I NetworkMonitor: type=WIFI subType= reason=null isConnected=false
,08-16 15:26:39.191  2173  2173 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 15:26:39.209  7278  7278 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 15:26:39.209  7278  7278 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 15:26:39.209  7278  7278 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 15:26:39.209  7278  7278 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
,08-16 15:26:39.214  7278  7278 I AppUp4:CustModeStarterReceiver: onReceive
08-16 15:26:39.217  7278  7278 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@37a4402e
08-16 15:26:39.217  7278  7278 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 15:26:39.218  7278  7278 D AppUp4:CustFacade: isPhone : true
08-16 15:26:39.218  7278  7278 D AppUp4:CustModeStarterReceiver: begin check event
08-16 15:26:39.218  7278  7278 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 15:26:39.223  4739  4739 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 15:26:39.223  4739  4739 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 15:26:39.225  4739  4739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 15:26:39.230  4739  4739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 15:26:39.238  7307  7307 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 15:26:39.272  4739  7707 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 15:26:39.274  1044  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
08-16 15:26:39.274  7307  7709 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:39.275  1044  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:26:39.275  1044  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: DISCONNECTED/DISCONNECTED, reason: (unspecified), extra: (none), roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:26:39.284  4739  7712 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 15:26:39.284  4739  7712 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 15:26:39.290  7193  7713 W FormManager: Network not available. Please check & try again.
,08-16 15:26:39.297  7193  7714 V FormManager: Network unavailable.
08-16 15:26:39.300  7193  7714 V FormManager: Network unavailable.
08-16 15:26:39.384  1044  1562 I art     : Explicit concurrent mark sweep GC freed 135369(6MB) AllocSpace objects, 4(64KB) LOS objects, 33% free, 43MB/64MB, paused 2.055ms total 125.736ms
,08-16 15:26:39.399  1044  1942 I ActivityManager: Killing 7538:com.lge.bnr/1000 (adj 15): empty #17
,08-16 15:26:39.458  3304  3304 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 15:26:39.458  3304  3304 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 15:26:39.459  3304  3304 I LgeMiscReceiver: networkInfo.isConnected() = false
08-16 15:26:39.460  1044  1060 W libprocessgroup: failed to open /acct/uid_1000/pid_7538/cgroup.procs: No such file or directory
,08-16 15:26:39.472  7336  7336 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-16 15:26:39.473  7336  7336 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-16 15:26:39.491  7396  7396 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:26:39
,08-16 15:26:39.494  7396  7396 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
,08-16 15:26:39.494  7396  7396 D Weather.Utils: 2 : All the weather widget is gone.
08-16 15:26:39.495  7396  7396 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 15:26:39.495  7396  7396 D WeatherAncestor: connectivity changed - connection : true
08-16 15:26:39.495  7396  7396 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2df2155c
,08-16 15:26:39.496  7396  7396 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 15:26:39.496  7396  7396 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 15:26:39.496  7396  7396 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 15:26:39.496  7396  7396 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 15:26:39.496  7396  7396 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:26:39
08-16 15:26:39.525  6486  6486 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
,08-16 15:26:39.529  6486  7122 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
,08-16 15:26:39.545  2173  2173 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 15:26:39.562  7278  7278 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
,08-16 15:26:39.562  7278  7278 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
,08-16 15:26:39.562  7278  7278 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 15:26:39.562  7278  7278 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 15:26:39.564  7278  7278 I AppUp4:CustModeStarterReceiver: onReceive
08-16 15:26:39.568  7278  7278 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@37a4402e
08-16 15:26:39.568  7278  7278 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 15:26:39.568  7278  7278 D AppUp4:CustFacade: isPhone : true
08-16 15:26:39.569  7278  7278 D AppUp4:CustModeStarterReceiver: begin check event
08-16 15:26:39.569  7278  7278 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 15:26:39.572  4739  4739 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 15:26:39.573  4739  4739 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 15:26:39.574  4739  4739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 15:26:39.578  4739  4739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 15:26:39.586  7307  7307 D eas_req : ---addEventToQueue() easCode=1, requestId=0 (at EasSupport.java addEventToQueue 69)
08-16 15:26:39.586  4739  7717 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 15:26:39.588  4739  7718 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 15:26:39.588  4739  7718 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
,08-16 15:26:39.607  7307  7720 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 15:26:39.613  7193  7722 W FormManager: Network not available. Please check & try again.
08-16 15:26:39.618  3304  3304 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 15:26:39.618  3304  3304 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 15:26:39.618  3304  3304 I LgeMiscReceiver: networkInfo.isConnected() = false
,08-16 15:26:39.623  7336  7336 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
08-16 15:26:39.623  7336  7336 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
08-16 15:26:39.623  7193  7723 V FormManager: Network unavailable.
08-16 15:26:39.638  7396  7396 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:26:39
,08-16 15:26:39.639  7193  7723 V FormManager: Network unavailable.
,08-16 15:26:39.640  7396  7396 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 15:26:39.640  7396  7396 D Weather.Utils: 2 : All the weather widget is gone.
08-16 15:26:39.641  7396  7396 D UpdateThreadPoolManager: 2 : This is isUpdating : false
08-16 15:26:39.641  7396  7396 D WeatherAncestor: connectivity changed - connection : true
08-16 15:26:39.641  7396  7396 D WeatherService: 2 : isServiceAlived():false forecastCache:com.lge.sizechangable.weather.data.core.ForecastDataCache@2df2155c
08-16 15:26:39.642  7396  7396 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 15:26:39.642  7396  7396 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 15:26:39.642  7396  7396 D ForecastDataCache: 2 : Cache is up-to-date, count: 0
08-16 15:26:39.642  7396  7396 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
08-16 15:26:39.642  7396  7396 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:26:39
08-16 15:26:40.989  1044  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:26:40.990  1044  2036 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
,08-16 15:26:41.015  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 15:26:41.016  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 15:26:41.016  1044  1044 D Ulp_jni : JNI:system_update. Event-4
,08-16 15:26:41.019  1044  1119 D BluetoothManagerService: Message: 1
08-16 15:26:41.019  1044  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-16 15:26:41.048  1044  1524 D LGWifiP2pService: P2pDisabledState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:26:41.048  1044  1524 D LGWifiP2pService: DefaultState{ when=-1ms what=143366 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 15:26:41.051  1044  1119 D BluetoothManagerService: Message: 20
08-16 15:26:41.051  1044  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@101a836e:true
08-16 15:26:41.053  7210  7210 D BluetoothAdapterState: make
08-16 15:26:41.058  7210  7210 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-16 15:26:41.058  7210  7210 I bluedroid-qcom: init
08-16 15:26:41.059  7210  7732 I BluetoothAdapterState: Entering OffState
08-16 15:26:41.061  7210  7210 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 15:26:41.061  7210  7210 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 15:26:41.061  7210  7210 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 15:26:41.061  7210  7210 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 15:26:41.061  7210  7210 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
,08-16 15:26:41.065  7210  7210 I bluedroid-qcom: get_profile_interface socket
08-16 15:26:41.065  7210  7210 I bluedroid-qcom: get_profile_interface map_client
08-16 15:26:41.067  7210  7736 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-16 15:26:41.069  7210  7736 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 15:26:41.059  7735  7735 W bdaddr_loader: type=1400 audit(0.0:173): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 15:26:41.059  7735  7735 W bdaddr_loader: type=1400 audit(0.0:174): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 15:26:41.083  7735  7735 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-16 15:26:41.083  7735  7735 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-16 15:26:41.083  7735  7735 I LGFTMITEM: [GET_FTM][id=8], offset=16384
,08-16 15:26:41.087  1044  1525 E WifiStateMachine:  InitialState CMD_STOP_SUPPLICANT_FAILED 2 0
08-16 15:26:41.088  1044  1525 E WifiStateMachine:  DefaultState CMD_STOP_SUPPLICANT_FAILED 2 0
08-16 15:26:41.088  1044  1044 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 15:26:41.088  1044  1044 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 15:26:41.090  1044  1044 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-16 15:26:41.090  1044  1119 D BluetoothManagerService: Message: 40
08-16 15:26:41.090  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-16 15:26:41.091  7210  7228 I bluedroid-qcom: config_hci_snoop_log
08-16 15:26:41.092  1044  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-16 15:26:41.092  1044  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-16 15:26:41.093  7735  7735 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
08-16 15:26:41.101  7735  7735 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-16 15:26:41.101  7735  7735 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
,08-16 15:26:41.106  7210  7732 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-16 15:26:41.106  7210  7736 D BluetoothAdapterProperties: Name is: G3
08-16 15:26:41.106  7210  7732 D BluetoothAdapterProperties: Setting state to 11
08-16 15:26:41.107  7210  7732 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
08-16 15:26:41.107  1044  1119 D BluetoothManagerService: Message: 60
08-16 15:26:41.107  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-16 15:26:41.107  1044  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-16 15:26:41.112  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:41.112  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 15:26:41.116  7091  7091 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
,08-16 15:26:41.123  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:41.124  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:41.128  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:41.135  7210  7210 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 15:26:41.136  7210  7210 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:41.136  7210  7210 V BluetoothPbapReceiver: ***********state = 11
,08-16 15:26:41.142  2173  2173 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 15:26:41.153  7210  7732 I LGBluetoothServiceJni: classInitNative: succeeds
,08-16 15:26:41.204  1044  1562 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.receiver.HealthDeviceReceiver: pid=7752 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-16 15:26:41.208  7210  7732 D BluetoothBondStateMachine: make
08-16 15:26:41.218  7210  7732 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
,08-16 15:26:41.220  7210  7732 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-16 15:26:41.220  7210  7732 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:41.220  7210  7732 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-16 15:26:41.223  7210  7732 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-16 15:26:41.224  7210  7765 I BluetoothBondStateMachine: StableState(): Entering Off State
08-16 15:26:41.226   353   353 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 418us total 21.094ms
08-16 15:26:41.229  7210  7732 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 15:26:41.238  7210  7210 D HeadsetService: Received start request. Starting profile...
08-16 15:26:41.239  7210  7210 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
,08-16 15:26:41.239  7210  7210 D LGBluetoothHfpAdapter: Version 1.6
08-16 15:26:41.242  7210  7210 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 15:26:41.243   353   353 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 374us total 16.879ms
08-16 15:26:41.243  7210  7210 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 15:26:41.244  7210  7210 D HeadsetStateMachine: make
08-16 15:26:41.250  7210  7732 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 15:26:41.258   353   353 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 287us total 14.044ms
08-16 15:26:41.258  7210  7732 E BluetoothAdapterService: File transfer profiles supported!!
08-16 15:26:41.263  7210  7732 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 15:26:41.268  7210  7732 E BluetoothAdapterService: File transfer profiles supported!!
08-16 15:26:41.272  7210  7210 D LgDataFeature: LgDataFeature() Constructor: none
08-16 15:26:41.272  7210  7210 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 15:26:41.273  7210  7732 E BluetoothAdapterService: File transfer profiles supported!!
08-16 15:26:41.276  7210  7210 D HeadsetStateMachine: max_hf_connections = 1
08-16 15:26:41.276  7210  7210 I bluedroid-qcom: get_profile_interface handsfree
,08-16 15:26:41.277  7210  7210 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-16 15:26:41.278   326  2145 V AudioPolicyService: registerClient() client 0xb558ace0, uid 1002
08-16 15:26:41.278  7210  7732 E BluetoothAdapterService: File transfer profiles supported!!
08-16 15:26:41.278   326  2145 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-16 15:26:41.278   326  2145 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 15:26:41.278   326  2145 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 15:26:41.278  7210  7210 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
08-16 15:26:41.279   326  2146 V AudioFlinger: registerClient() client 0xb55741f0, pid 7210
08-16 15:26:41.279   326  1365 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 15:26:41.279   326  1365 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 15:26:41.280  1044  1942 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 15:26:41.280  1044  1942 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 15:26:41.280  1589  1610 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 15:26:41.280  1589  1610 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 15:26:41.280  1839  2447 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 15:26:41.280  1839  2447 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 15:26:41.280  3304  3329 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 15:26:41.280  3304  3329 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 15:26:41.280   326  1364 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 15:26:41.280   326  1364 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 15:26:41.280  7210  7210 V ToneGenerator: Create Track: 0xb4928080
08-16 15:26:41.280  7210  7210 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-16 15:26:41.280  7210  7210 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-16 15:26:41.280  1044  1907 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 15:26:41.280  1044  1907 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 15:26:41.280  1589  2075 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 15:26:41.280  7210  7228 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 15:26:41.280  1589  2075 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 15:26:41.281  7210  7228 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-16 15:26:41.281  7210  7228 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 15:26:41.281  7210  7228 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-16 15:26:41.281   326  1369 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 15:26:41.281   326  1369 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-16 15:26:41.281  1839  1855 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 15:26:41.281   326  1369 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 15:26:41.281  1839  1855 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 15:26:41.281   326  1369 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 15:26:41.281   326  1369 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 15:26:41.281  3304  3330 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 15:26:41.281  3304  3330 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 15:26:41.281   326   326 V AudioPolicyManager: getOutputForAttr() ,usage=3, content=4, tag= flags=00000000
08-16 15:26:41.281   326   326 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-16 15:26:41.281   326   326 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 15:26:41.281   326   326 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 15:26:41.281  7210  7210 V AudioSystem: getLatency() output 2, latency 50
08-16 15:26:41.281  7210  7210 V AudioSystem: getFrameCount() output 2, frameCount 960
08-16 15:26:41.281  7210  7210 V AudioTrack: createTrack_l() output 2 afLatency 50
08-16 15:26:41.282   326  2145 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 15:26:41.282   326  2145 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 15:26:41.282   326  2145 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 15:26:41.282   326  2145 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 15:26:41.282   326  2145 V AudioFlinger: createTrack() lSessionId: 22
08-16 15:26:41.282  7210  7210 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-16 15:26:41.284   326  2145 V AudioFlinger: acquiring 22 from 7210, for 7210
08-16 15:26:41.284   326  2145 V AudioFlinger:  added new entry for 22
08-16 15:26:41.284  7210  7210 V ToneGenerator: ToneGenerator INIT OK, time: 362309
08-16 15:26:41.284  7210  7210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:41.285  7210  7772 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-16 15:26:41.285  7210  7772 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 15:26:41.285  7210  7210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:41.286  7210  7772 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 15:26:41.286  7210  7772 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-16 15:26:41.286   326  2146 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 7210
08-16 15:26:41.286   326  2146 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-16 15:26:41.286   326  2146 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-16 15:26:41.286   326  2146 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-16 15:26:41.286   326  2146 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-16 15:26:41.286   326  2146 V voice   : voice_set_parameters: exit with code(0)
08-16 15:26:41.286   326  2146 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-16 15:26:41.286   326  2146 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-16 15:26:41.286   326  2146 V msm8974_platform: platform_set_parameters: exit with code(0)
08-16 15:26:41.286   326  2146 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-16 15:26:41.286   326  2146 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-16 15:26:41.286   326  2146 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-16 15:26:41.287  7210  7772 V ToneGenerator: ToneGenerator destructor
08-16 15:26:41.287  7210  7772 V ToneGenerator: stopTone
08-16 15:26:41.287  7210  7772 V ToneGenerator: Delete Track: 0xb4928080
08-16 15:26:41.287  7210  7210 D A2dpService: Received start request. Starting profile...
08-16 15:26:41.287  7210  7772 V AudioTrack: ~AudioTrack, releasing session id from 7210 on behalf of 7210
08-16 15:26:41.287   326   326 V AudioFlinger: releasing 22 from 7210 for 7210
08-16 15:26:41.287   326  1370 V AudioPolicyService: AudioCommandThread() adding release output 2
08-16 15:26:41.287   326   326 V AudioFlinger:  decremented refcount to 0
08-16 15:26:41.287   326   3,26 V AudioFlinger: purging stale effects
08-16 15:26:41.287   326  1370 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-16 15:26:41.287   326  1370 V AudioFlinger: PlaybackThread::Track destructor
08-16 15:26:41.287   326  1272 V AudioPolicyService: AudioCommandThread() waking up
08-16 15:26:41.287   326  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
08-16 15:26:41.287   326  1370 V AudioFlinger: removeClient_l() pid 7210, calling pid 326
08-16 15:26:41.287   326  1272 V AudioPolicyManager: releaseOutput() 2
08-16 15:26:41.287   326  1272 V AudioPolicyService: AudioCommandThread() going to sleep
08-16 15:26:41.288  7210  7210 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 15:26:41.289  7210  7210 V Avrcp   : make
08-16 15:26:41.290  7210  7210 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-16 15:26:41.290  7210  7210 I bluedroid-qcom: get_profile_interface avrcp
08-16 15:26:41.299  7210  7210 V AudioManager: registerRemoteController: size of Media player list: 0
08-16 15:26:41.300  7210  7210 E AudioManager: No RCC entry present to update
08-16 15:26:41.300  7210  7210 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
,08-16 15:26:41.304  7210  7210 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
08-16 15:26:41.305  7210  7210 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-16 15:26:41.305  7210  7210 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-16 15:26:41.305  7210  7732 V LGMDMManager: Create singleton instance
08-16 15:26:41.307  7752  7752 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-16 15:26:41.307  7752  7752 W LG Account v2.2: No ProfileInfo entries
08-16 15:26:41.308  7752  7752 I LG Account v2.2: isEnabled: false
08-16 15:26:41.308  7210  7210 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 15:26:41.308  7752  7752 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 15:26:41.308  7752  7752 I Feature : [Lifetracker]Country: EU
08-16 15:26:41.308  7752  7752 I Feature : [Lifetracker]Operator: OPEN
08-16 15:26:41.308  7752  7752 I Feature : [Lifetracker]Ranking support: false
08-16 15:26:41.308  7752  7752 I Feature : [Lifetracker]Comfort support: false
08-16 15:26:41.308  7752  7752 I Feature : [Lifetracker]Accessory: true
08-16 15:26:41.308  7752  7752 I Feature : [Lifetracker]Health device: true
08-16 15:26:41.308  7210  7732 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 15:26:41.308  7752  7752 I Feature : [Lifetracker]Extra Pedometer: false
08-16 15:26:41.308  7752  7752 I Feature : [Lifetracker]Blood glucose device: false
08-16 15:26:41.308  7752  7752 I Feature : [Lifetracker]Device Number: 3
08-16 15:26:41.349  7091  7091 D BluetoothPermissionRequest: onReceive
,08-16 15:26:41.356  7091  7091 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 15:26:41.411  1044  1638 V SIM_STK : Menu title from STK is T-Mobile
08-16 15:26:41.412  1044  1638 V SIM_STK : Menu title from STK is T-Mobile
,08-16 15:26:41.528  1044  1060 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-16 15:26:41.552  7210  7210 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-16 15:26:41.557  7210  7210 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
,08-16 15:26:41.558  7210  7210 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 15:26:41.558  7210  7210 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 15:26:41.558  7210  7210 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 15:26:41.558  7210  7210 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 15:26:41.558  7210  7210 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 15:26:41.558  7210  7210 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 15:26:41.558  7210  7210 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 15:26:41.558  7210  7210 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 15:26:41.558  7210  7210 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 15:26:41.559  7210  7210 I BluetoothA2dpServiceJni: classInitNative
08-16 15:26:41.559  7210  7210 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 15:26:41.559  7210  7210 D A2dpStateMachine: make
08-16 15:26:41.561  7210  7210 I bluedroid-qcom: get_profile_interface a2dp
08-16 15:26:41.561  7210  7784 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 15:26:41.563  7210  7210 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-16 15:26:41.563  7210  7210 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-16 15:26:41.564  7210  7210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:41.564  7210  7783 D A2dpStateMachine: Enter Disconnected: -2
08-16 15:26:41.564  7210  7210 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 15:26:41.566  7210  7210 D HidService: Received start request. Starting profile...
08-16 15:26:41.566  7210  7210 I bluedroid-qcom: get_profile_interface hidhost
08-16 15:26:41.566  7210  7210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:41.567  7210  7210 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 15:26:41.568  7210  7210 D HealthService: Received start request. Starting profile...
,08-16 15:26:41.569  7210  7210 I bluedroid-qcom: get_profile_interface health
08-16 15:26:41.569  7210  7210 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-16 15:26:41.569  7210  7210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:41.570  7210  7210 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 15:26:41.571  7210  7210 D PanService: Received start request. Starting profile...
08-16 15:26:41.571  7210  7210 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 15:26:41.571  7210  7210 I bluedroid-qcom: get_profile_interface pan
08-16 15:26:41.577  7210  7210 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-16 15:26:41.577  7210  7210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:41.578  7210  7210 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
08-16 15:26:41.582  7210  7210 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 15:26:41.582  7210  7210 D BtGatt.GattService: Received start request. Starting profile...
08-16 15:26:41.582  7210  7210 D BtGatt.GattService: start()
08-16 15:26:41.582  7210  7210 I bluedroid-qcom: get_profile_interface gatt
08-16 15:26:41.583  7210  7210 D BtGatt.AdvertiseManager: advertise manager created
,08-16 15:26:41.588  7210  7210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:41.589  7210  7210 D HeadsetStateMachine: Proxy object connected
08-16 15:26:41.589  7210  7210 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-16 15:26:41.589  7210  7210 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-16 15:26:41.592  7210  7210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:41.592  7210  7210 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
08-16 15:26:41.593  7210  7210 V BluetoothMapService: BluetoothMapBinder()
08-16 15:26:41.593  7210  7210 D BluetoothMapService: Received start request. Starting profile...
08-16 15:26:41.593  7210  7210 D BluetoothMapService: start()
08-16 15:26:41.596  7210  7210 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-16 15:26:41.596  7210  7210 D BluetoothMapEmailAppObserver: createReceiver()
,08-16 15:26:41.596  7210  7210 D BluetoothMapEmailAppObserver: initObservers()
08-16 15:26:41.597  7210  7210 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-16 15:26:41.602  7210  7210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:41.606  7210  7210 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 15:26:41.607  7210  7772 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 15:26:41.607  7210  7772 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 15:26:41.608  7210  7772 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-16 15:26:41.613  7210  7210 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 15:26:41.617  7210  7210 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 15:26:41.619  7210  7210 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 15:26:41.620  7210  7210 V PanService: [BTUI] SIM Extra State :ABSENT
08-16 15:26:41.623  7210  7210 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 15:26:41.625  7210  7210 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
08-16 15:26:41.626  7210  7210 V BluetoothMapService: Handler(): got msg=1
08-16 15:26:41.627  7210  7732 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-16 15:26:41.627  7210  7732 I bluedroid-qcom: enable
08-16 15:26:41.627  7210  7210 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
,08-16 15:26:41.628  7210  7732 I bt_hci_bdroid: init
08-16 15:26:41.630  7210  7732 I bt_vendor: bt-vendor : init
08-16 15:26:41.630  7210  7732 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 15:26:41.630  7210  7732 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 15:26:41.630  7210  7732 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-16 15:26:41.630  7210  7732 D bt_userial_mct: userial_init
08-16 15:26:41.632  7210  7732 D bt_hci_bdroid: set_power 1
08-16 15:26:41.632  7210  7732 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 15:26:41.632  7210  7732 I bt_vendor: Starting hciattach daemon
08-16 15:26:41.632  7210  7732 I bt_vendor: try to set true
08-16 15:26:41.634  7210  7210 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 15:26:41.634  7210  7210 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 15:26:41.634  7210  7210 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 15:26:41.634  7210  7210 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:41.634  7210  7210 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-16 15:26:41.634  7210  7791 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 15:26:41.634  7210  7791 I bt-btu  : btu_task pending for preload complete event
08-16 15:26:41.629  7794  7794 W sh      : type=1400 audit(0.0:175): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 15:26:41.629  7794  7794 W sh      : type=1400 audit(0.0:176): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 15:26:41.651  7795  7795 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 15:26:41.686  1044  1886 I ActivityManager: Start proc com.lge.settings.easy for broadcast com.lge.settings.easy/com.lge.settings.bluetooth.LGBluetoothProfileConnectionReceiver: pid=7798 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 15:26:41.725  7818  7818 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-16 15:26:41.736  7819  7819 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 15:26:41.746  7798  7798 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 15:26:41.759  7821  7821 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 15:26:41.769  7822  7822 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
,08-16 15:26:41.770  1044  1949 I ActivityManager: Killing 6818:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-16 15:26:41.780  7823  7823 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 15:26:41.787  7152  7152 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-16 15:26:41.788  7152  7152 W System.err: android.os.DeadObjectException
08-16 15:26:41.788  7152  7152 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 15:26:41.788  7152  7152 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 15:26:41.788  7152  7152 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-16 15:26:41.788  7152  7152 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-16 15:26:41.788  7152  7152 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 15:26:41.788  7152  7152 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 15:26:41.789  7152  7152 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 15:26:41.789  7152  7152 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 15:26:41.789  7152  7152 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 15:26:41.789  7152  7152 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 15:26:41.789  7152  7152 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 15:26:41.789  7152  7152 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 15:26:41.789  7152  7152 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 15:26:41.789  7152  7152 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 15:26:41.789  7152  7152 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-16 15:26:41.790  7152  7152 W System.err: android.os.DeadObjectException
08-16 15:26:41.790  7152  7152 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 15:26:41.790  7152  7152 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 15:26:41.790  7152  7152 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
,08-16 15:26:41.790  7152  7152 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-16 15:26:41.790  7152  7152 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 15:26:41.790  7152  7152 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 15:26:41.790  7152  7152 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 15:26:41.790  7152  7152 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 15:26:41.791  7152  7152 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 15:26:41.791  7152  7152 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 15:26:41.791  7152  7152 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 15:26:41.791  7152  7152 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 15:26:41.791  7152  7152 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 15:26:41.791  7152  7152 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 15:26:41.791  7152  7152 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-16 15:26:41.791  7824  7824 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
08-16 15:26:41.791  7152  7152 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-16 15:26:41.815  7827  7827 I libmdmdetect: ESOC framework not supported
,08-16 15:26:41.816  7827  7827 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
08-16 15:26:41.825  7827  7827 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-16 15:26:41.826  7827  7827 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
08-16 15:26:41.826  7827  7827 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-16 15:26:41.826  7827  7827 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-16 15:26:41.826  7827  7827 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-16 15:26:41.826  7827  7827 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-16 15:26:41.826  7827  7827 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-16 15:26:41.867  7827  7828 E QC-QMI  : qmi_client [7827] 14: failed to locate client data
08-16 15:26:41.870   481   481 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-16 15:26:41.870   481   481 E QC-QMI  : QMUX qmux_client_id=14 not found in qmux client list, unable to remove
,08-16 15:26:41.900  1044  1981 W libprocessgroup: failed to open /acct/uid_1000/pid_6818/cgroup.procs: No such file or directory
08-16 15:26:41.900  1044  1981 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-16 15:26:41.910  7152  7152 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-16 15:26:41.911  7152  7152 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 15:26:41.948  7829  7829 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-16 15:26:41.975  7830  7830 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 15:26:41.981  1044  1060 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=7831 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 15:26:41.982  7152  7152 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-16 15:26:42.035  7210  7732 I bt_vendor: bluetooth satus is on
08-16 15:26:42.035  7210  7732 D bt_hci_bdroid: preload
08-16 15:26:42.035  7210  7793 D bt_userial_mct: userial_open(port:0)
08-16 15:26:42.035  7210  7793 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-16 15:26:42.039  7210  7793 I bt_vendor: Done intiailizing UART
08-16 15:26:42.040  7210  7793 I bt_vendor: Done intiailizing UART
08-16 15:26:42.040  7210  7793 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 15:26:42.040  7210  7793 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 15:26:42.040  7210  7791 I bt-btu  : btu_task received preload complete event
08-16 15:26:42.041  7210  7849 D bt_userial_mct: Entering userial_read_thread()
08-16 15:26:42.041  7210  7791 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-16 15:26:42.041  7210  7791 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-16 15:26:42.044  7210  7791 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-16 15:26:42.048  7210  7791 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 15:26:42.048  7210  7791 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 15:26:42.048  7210  7791 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 15:26:42.048  7210  7791 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 15:26:42.048  7210  7791 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 15:26:42.048  7210  7791 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 15:26:42.048  7210  7791 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 15:26:42.048  7210  7791 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 15:26:42.049  7210  7791 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-16 15:26:42.049  7210  7791 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 15:26:42.049  7210  7791 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 15:26:42.049  7210  7791 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 15:26:42.049  7210  7791 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 15:26:42.049  7210  7791 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 15:26:42.049  7210  7791 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 15:26:42.049  7210  7791 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 15:26:42.056  7831  7831 D UEI.SmartControl: Quickset Services start...
08-16 15:26:42.059  7831  7831 I UEI.SmartControl: Manufacture = LGE
08-16 15:26:42.059  7831  7831 D UEI.SmartControl: Id = LGNevo
08-16 15:26:42.061  7831  7831 D UEI.SmartControl: File observer start...
08-16 15:26:42.061  7831  7831 E UEI.SmartControl: IR Port is disabled: false
,08-16 15:26:42.062  7831  7831 D UEI.SmartControl: Starting file observer...
08-16 15:26:42.062  7831  7831 D UEI.SmartControl: Extracting JNI libs...
08-16 15:26:42.062  7831  7831 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-16 15:26:42.115  7210  7791 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
08-16 15:26:42.115  7210  7791 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01b5061 
08-16 15:26:42.115  7210  7791 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01b5061 
,08-16 15:26:42.156  7210  7736 E bt-btif : Calling BTA_HhEnable
08-16 15:26:42.156  7210  7736 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
08-16 15:26:42.156  7210  7736 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
08-16 15:26:42.156  7210  7791 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-16 15:26:42.156  7210  7791 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-16 15:26:42.156  7210  7791 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-16 15:26:42.157  7210  7791 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-16 15:26:42.157  7210  7791 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
,08-16 15:26:42.158  7210  7736 D BluetoothAdapterProperties: Name is: G3
,08-16 15:26:42.159  1044  1044 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 15:26:42.159  1044  1044 D BluetoothManagerService: Stored Bluetooth name: G3
,08-16 15:26:42.164  7210  7736 D BluetoothAdapterProperties: Scan Mode:20
08-16 15:26:42.164  7210  7736 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 15:26:42.164  7210  7736 D bt_hci_bdroid: postload
08-16 15:26:42.166  7210  7736 D bte_conf: Device ID record 1 : primary
08-16 15:26:42.166  7210  7736 D bte_conf:   vendorId            = 00c4
08-16 15:26:42.166  7210  7736 D bte_conf:   vendorIdSource      = 0001
08-16 15:26:42.166  7210  7736 D bte_conf:   product             = 13a1
08-16 15:26:42.166  7210  7736 D bte_conf:   version             = 1000
08-16 15:26:42.166  7210  7736 D bte_conf:   clientExecutableURL = 
08-16 15:26:42.166  7210  7736 D bte_conf:   serviceDescription  = 
08-16 15:26:42.166  7210  7736 D bte_conf:   documentationURL    = 
08-16 15:26:42.166  7210  7736 D bte_conf: bte_load_did_conf no section named DID2.
08-16 15:26:42.167  7210  7791 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-16 15:26:42.167  7210  7793 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 15:26:42.169  7210  7732 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-16 15:26:42.169  7210  7732 D BluetoothAdapterProperties: ScanMode =  20
08-16 15:26:42.169  7210  7732 D BluetoothAdapterProperties: State =  11
08-16 15:26:42.169  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:42.169  7210  7732 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-16 15:26:42.170  7210  7732 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-16 15:26:42.170  7210  7732 D BluetoothAdapterProperties: Setting state to 12
08-16 15:26:42.170  7210  7732 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 15:26:42.171  7210  7736 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 15:26:42.171  7210  7736 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 15:26:42.172  1044  1119 D BluetoothManagerService: Message: 60
08-16 15:26:42.172  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-16 15:26:42.172  1044  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 9 receivers.
08-16 15:26:42.172  1044  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 15:26:42.176  7210  7791 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 15:26:42.176  7210  7791 W bt-smp  : Plain text(LSB ~ MSB) = b8 43 7d 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 15:26:42.176  7210  7791 W bt-smp  : Encrypted text(LSB ~ MSB) = e5 3d 35 75 eb 8e 7f 81 26 89 4b 1a f4 57 4a 04 
08-16 15:26:42.176  7210  7791 W bt-btm  : Stopping oneshot timer
08-16 15:26:42.176  7210  7793 D bt_hci_bdroid: Used up Tx Cmd credits
,08-16 15:26:42.159  7852  7852 W sh      : type=1400 audit(0.0:177): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 15:26:42.159  7852  7852 W sh      : type=1400 audit(0.0:178): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 15:26:42.178  7210  7793 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 15:26:42.178  7210  7793 D bt_hci_bdroid: Used up Tx Cmd credits
,08-16 15:26:42.182  7210  7793 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 15:26:42.182  7210  7849 E bt_mct  : hci lib postload completed
08-16 15:26:42.186  7210  7736 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 15:26:42.186  7210  7736 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
08-16 15:26:42.188  7210  7732 I BluetoothAdapterState: Entering On State
08-16 15:26:42.195  7210  7732 D LGBluetoothServiceAdapter: [BTUI] OnState
08-16 15:26:42.195  7210  7732 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-16 15:26:42.195  7210  7732 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
,08-16 15:26:42.196  7210  7791 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 15:26:42.196  7210  7791 W bt-smp  : Plain text(LSB ~ MSB) = 35 e4 66 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 15:26:42.196  7210  7791 W bt-smp  : Encrypted text(LSB ~ MSB) = 90 e9 a0 6d 25 de f1 52 17 90 c5 7b 44 66 8e b9 
08-16 15:26:42.196  7210  7791 W bt-btm  : Stopping oneshot timer
08-16 15:26:42.197  7210  7732 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-16 15:26:42.197  1839  2463 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 15:26:42.198  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:26:42.198  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:42.198  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:42.198  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:26:42.198  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:26:42.198  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:26:42.198  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:26:42.198  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:26:42.200  6974  6974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:26:42.202  1839  1839 D BluetoothHeadset: Proxy object connected
08-16 15:26:42.202  1044  1044 D BluetoothHeadset: Proxy object connected
08-16 15:26:42.203  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 15:26:42.205  1839  1839 D BluetoothHeadset: Proxy object connected
08-16 15:26:42.206  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:26:42.206  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:42.206  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:42.206  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:26:42.206  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:26:42.206  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:26:42.206  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:26:42.206  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:26:42.206  7091  7118 D BluetoothMap: onBluetoothStateChange: up=true
08-16 15:26:42.208  7210  7791 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 15:26:42.208  7210  7791 W bt-smp  : Plain text(LSB ~ MSB) = 0d b1 6a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 15:26:42.208  7210  7791 W bt-smp  : Encrypted text(LSB ~ MSB) = c8 a5 75 96 9a 49 62 2a 2d 27 63 8f d8 d0 a8 b5 
08-16 15:26:42.209  7210  7791 W bt-btm  : Stopping oneshot timer
08-16 15:26:42.209  6974  6974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 15:26:42.211  7091  7118 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 15:26:42.212  7831  7831 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-16 15:26:42.213  7831  7831 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-16 15:26:42.213  7831  7831 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
08-16 15:26:42.214  7091  7190 D BluetoothPan: onBluetoothStateChange on: true
08-16 15:26:42.214  7091  7190 D BluetoothPan: onBluetoothStateChange call bindService
08-16 15:26:42.216  7091  7118 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 15:26:42.216  7091  7091 D BluetoothMap: Proxy object connected
08-16 15:26:42.216  7091  7091 D MapProfile: Bluetooth service connected
08-16 15:26:42.216  7091  7091 D BluetoothMap: getConnectedDevices()
08-16 15:26:42.218  7210  7791 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 15:26:42.218  7210  7791 W bt-smp  : Plain text(LSB ~ MSB) = b6 4d 68 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 15:26:42.218  7210  7791 W bt-smp  : Encrypted text(LSB ~ MSB) = 8c 20 bc 97 fc 7a 4d de da f6 f8 89 c3 35 a2 0c 
08-16 15:26:42.218  7210  7791 W bt-btm  : Stopping oneshot timer
08-16 15:26:42.227  7210  7791 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 15:26:42.227  7210  7791 W bt-smp  : Plain text(LSB ~ MSB) = 3c 92 60 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 15:26:42.227  7210  7791 W bt-smp  : Encrypted text(LSB ~ MSB) = b6 16 09 05 8e c2 ed 81 04 49 b3 a1 b2 31 8d 29 
08-16 15:26:42.227  7210  7791 W bt-btm  : Stopping oneshot timer
,08-16 15:26:42.228  1044  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 15:26:42.230  1839  2447 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 15:26:42.231  1044  1044 D BluetoothA2dp: Proxy object connected
08-16 15:26:42.234  1839  1839 D BluetoothHeadset: Proxy object connected
08-16 15:26:42.237  7210  7732 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
08-16 15:26:42.238  1044  1044 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-16 15:26:42.238  1044  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-16 15:26:42.238  1044  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-16 15:26:42.239  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 15:26:42.240  1927  2069 D LGBluetoothAPIService: Message: 1
08-16 15:26:42.240  1927  2069 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-16 15:26:42.242  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 15:26:42.244  7857  7857 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-16 15:26:42.247  6974  6974 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for offloaded scan batching: Storing the value (NOT_SUPPORTED) in persistent storage
08-16 15:26:42.253  7210  7228 V BluetoothMapService: getConnectedDevices()
08-16 15:26:42.253  1044  1119 D BluetoothManagerService: Message: 40
08-16 15:26:42.253  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
,08-16 15:26:42.256  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:26:42.256  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:42.256  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:42.256  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:26:42.256  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:26:42.256  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:26:42.256  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:26:42.256  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:26:42.256  1927  2069 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-16 15:26:42.258  7210  7210 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:42.258  6974  6974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:26:42.258  7210  7210 D BluetoothMapService: STATE_ON
08-16 15:26:42.259  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:42.260  7091  7091 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 15:26:42.260  7091  7091 D PanProfile: Bluetooth service connected
08-16 15:26:42.261  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:42.261  7210  7210 D LGBluetoothAPIServer: [BTUI] onCreate()
08-16 15:26:42.261  7210  7210 V BluetoothMapService: Handler(): got msg=1
08-16 15:26:42.261  7210  7210 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-16 15:26:42.262  7091  7091 D BluetoothInputDevice: Proxy object connected
08-16 15:26:42.262  7091  7091 D HidProfile: Bluetooth service connected
08-16 15:26:42.263  7210  7210 D LGBluetoothAPIServer: [BTUI] onBind()
08-16 15:26:42.264  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-16 15:26:42.264  7210  7860 D BluetoothMapMasInstance: MAS initSocket()
08-16 15:26:42.264  1927  2069 D LGBluetoothAPIService: Message: 100
08-16 15:26:42.264  1927  2069 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
08-16 15:26:42.265  7210  7860 D BluetoothMapMasInstance:   masId = 00
08-16 15:26:42.265  7210  7860 D BluetoothMapMasInstance:   msgTypes = 0e
08-16 15:26:42.265  7210  7860 D BluetoothMapMasInstance:   masName = SMS/MMS
08-16 15:26:42.265  7210  7860 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-16 15:26:42.266  7091  7091 D LocalBluetoothProfileManager: Adding local A2DP profile
08-16 15:26:42.266  1044  1977 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:26:42.267  7210  7860 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 15:26:42.268  1044  1119 D BluetoothManagerService: Message: 30
08-16 15:26:42.269  7210  7860 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-16 15:26:42.269  7210  7860 V BluetoothMapMasInstance: Succeed to create listening socket 
08-16 15:26:42.269  7210  7860 D BluetoothMapMasInstance: Accepting socket connection...
08-16 15:26:42.270  7210  7736 D BluetoothAdapterProperties: Scan Mode:21
08-16 15:26:42.271  7210  7736 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-16 15:26:42.272  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:26:42.274  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:42.275  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:42.279  7091  7091 D LocalBluetoothProfileManager: Adding local HEADSET profile
08-16 15:26:42.282  1044  1119 D BluetoothManagerService: Message: 30
08-16 15:26:42.284  7831  7831 I UEI.SmartControl: --- Selecting new region: 6
,08-16 15:26:42.287  7091  7091 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-16 15:26:42.287  7210  7210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:42.288  7210  7210 V BluetoothPbapService: Pbap Service onCreate
08-16 15:26:42.288  7210  7210 V BluetoothPbapService: Starting PBAP service
08-16 15:26:42.288  7831  7831 I UEI.SmartControl: Model = LG-D855
08-16 15:26:42.289  7091  7091 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 15:26:42.289  7831  7831 D UEI.SmartControl: QS Service created
08-16 15:26:42.292  7091  7091 D BluetoothA2dp: Proxy object connected
08-16 15:26:42.292  7210  7210 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-16 15:26:42.292  7210  7210 V BluetoothPbapService: Pbap Service onBind
08-16 15:26:42.293  7091  7091 D A2dpProfile: Bluetooth service connected
08-16 15:26:42.294  7210  7210 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:42.294  7210  7210 V BluetoothPbapService: state: 12
08-16 15:26:42.294  7210  7210 V BluetoothPbapService: Handler(): got msg=1
08-16 15:26:42.294  7210  7210 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-16 15:26:42.295  7210  7210 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 15:26:42.295  7210  7210 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:42.296  7210  7210 V BluetoothPbapReceiver: ***********state = 12
08-16 15:26:42.296  7210  7866 V BluetoothPbapService: Pbap Service initSocket
08-16 15:26:42.296  1044  1916 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:26:42.297  7091  7091 D BluetoothHeadset: Proxy object connected
08-16 15:26:42.297  7091  7091 D HeadsetProfile: Bluetooth service connected
08-16 15:26:42.298  7210  7866 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 15:26:42.299  2173  2173 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 15:26:42.300  7210  7866 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-16 15:26:42.300  7210  7866 V BluetoothPbapService: Succeed to create listening socket 
08-16 15:26:42.300  7210  7866 V BluetoothPbapService: Accepting socket connection...
08-16 15:26:42.300  2173  2173 D c       : Getting all permits...
08-16 15:26:42.300  2173  2173 D a       : Opening database...
08-16 15:26:42.303  7091  7091 D DockEventReceiver: finishStartingService: stopping service
08-16 15:26:42.303  7091  7091 D BluetoothPbap: Proxy object connected
08-16 15:26:42.304  2173  2173 D a       : Opening database auth.proximity.permit_store...
08-16 15:26:42.304  7091  7091 D PbapServerProfile: Bluetooth service connected
08-16 15:26:42.305  2173  2173 D a       : Closing database...
08-16 15:26:42.310  7831  7831 I UEI.SmartControl: Service initServices...
,08-16 15:26:42.314  7831  7831 D UEI.SmartControl: QS start get config
08-16 15:26:42.316  7091  7091 D BluetoothPermissionRequest: onReceive
08-16 15:26:42.317  7091  7091 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 15:26:42.318  7091  7091 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 15:26:42.321  7210  7210 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-16 15:26:42.322  7210  7210 I LGBluetoothOppAdapter: [BTUI] startOppService()
,08-16 15:26:42.328  7210  7210 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-16 15:26:42.347  7210  7210 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
,08-16 15:26:42.347  7210  7210 V BtOppService: onCreate
08-16 15:26:42.352  7210  7210 V BluetoothOppNotification: send message
08-16 15:26:42.354  7210  7210 V BtOppService: Starting RfcommListener
08-16 15:26:42.358  7210  7210 D BluetoothOppPreference: Dumping Names:  
08-16 15:26:42.358  7210  7210 D BluetoothOppPreference: {}
08-16 15:26:42.358  7210  7210 D BluetoothOppPreference: Dumping Channels:  
08-16 15:26:42.358  7210  7210 D BluetoothOppPreference: {}
08-16 15:26:42.359  7210  7210 V BtOppService: onStartCommand
,08-16 15:26:42.361  7831  7831 D UEI.SmartControl: Loading JNI Libs...
08-16 15:26:42.363  7210  7873 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 15:26:42.363  7210  7210 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:42.364  7210  7210 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 15:26:42.364  7210  7873 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 15:26:42.364  7210  7870 V BtOppService: Deleted complete outbound shares, number =  0
08-16 15:26:42.366  7210  7870 V BtOppService: Deleted complete inbound failed shares, number = 0
08-16 15:26:42.366  7210  7210 V BluetoothOppNotification: new notify threadi!
08-16 15:26:42.367  7210  7870 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-16 15:26:42.367  7210  7873 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@241b2c31 on behalf of 
08-16 15:26:42.367  7210  7210 V BluetoothOppNotification: send delay message
08-16 15:26:42.368  7210  7210 V BtOppService: start RfcommListener
08-16 15:26:42.368  7210  7874 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 15:26:42.370  7210  7210 V BtOppService: RfcommListener started
,08-16 15:26:42.370  7210  7210 V BtOppService: ContentObserver received notification
,08-16 15:26:42.371  7210  7875 V BtOppRfcommListener: Starting RFCOMM listener....
08-16 15:26:42.372  1044  2036 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:26:42.374  7210  7870 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5eeef16 on behalf of 
08-16 15:26:42.375  7210  7874 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1498b097 on behalf of 
08-16 15:26:42.376  7210  7874 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 15:26:42.376  7210  7875 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 15:26:42.376  7210  7874 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 15:26:42.377  7210  7875 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=79 mFd=75
08-16 15:26:42.378  7210  7874 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@369b6284 on behalf of 
08-16 15:26:42.378  7210  7875 V BtOppRfcommListener: Started RFCOMM listener....
08-16 15:26:42.378  7210  7875 I BtOppRfcommListener: Accept thread started.
08-16 15:26:42.378  7210  7875 V BtOppRfcommListener: Accepting connection...
08-16 15:26:42.378  7210  7874 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-16 15:26:42.378  7210  7873 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 15:26:42.379  7210  7873 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 15:26:42.380  7210  7873 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e455a6d on behalf of 
08-16 15:26:42.381  7210  7873 V BluetoothOppNotification: update too frequent, put in queue
08-16 15:26:42.381  7210  7874 V BluetoothOppNotification: outbound notification was removed.
08-16 15:26:42.382  7210  7874 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 15:26:42.382  7210  7873 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 15:26:42.383  7210  7874 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1262e6a2 on behalf of 
08-16 15:26:42.384  7210  7210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:42.384  7210  7210 V BluetoothFtpService: Ftp Service onCreate
08-16 15:26:42.384  7210  7210 I BluetoothFtpService: Ftp Service onCreate
08-16 15:26:42.384  7210  7874 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 15:26:42.384  7210  7210 V BluetoothFtpService: Ftp Service onStartCommand
08-16 15:26:42.384  7210  7210 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:42.385  7210  7210 V BluetoothFtpService: Starting Listening on sockets
08-16 15:26:42.385  7210  7210 V BtOppService: ContentObserver received notification
08-16 15:26:42.385  7210  7210 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 15:26:42.385  7210  7876 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 15:26:42.386  7210  7210 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 15:26:42.386  7210  7210 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 15:26:42.386  7210  7876 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 15:26:42.386  7210  7210 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:42.386  7210  7210 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-16 15:26:42.386  7210  7210 V BluetoothSapReceiver: Calling SAP service start service with action = null
,08-16 15:26:42.388  7210  7876 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13ae22f0 on behalf of 
,08-16 15:26:42.388  7210  7210 V BluetoothFtpService: Handler(): got msg=1
08-16 15:26:42.388  7210  7876 V BluetoothOppNotification: update too frequent, put in queue
08-16 15:26:42.392  7210  7876 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 15:26:42.392  7210  7210 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-16 15:26:42.392  7210  7210 V BluetoothFtpService: Ftp Service initSocket
08-16 15:26:42.393  7210  7874 V BluetoothOppNotification: inbound notification was removed.
08-16 15:26:42.394  7210  7874 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 15:26:42.395  1044  1638 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:26:42.396  7210  7874 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@256a3069 on behalf of 
08-16 15:26:42.396  7210  7210 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 15:26:42.397  7210  7210 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=81 mFd=79
08-16 15:26:42.397  7210  7210 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-16 15:26:42.399  7210  7877 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-16 15:26:42.410  7210  7210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
,08-16 15:26:42.410  7210  7210 V BluetoothSapService: Sap Service onCreate
08-16 15:26:42.412  7210  7210 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:42.412  7210  7210 V BluetoothSapService: state: 12
08-16 15:26:42.412  7210  7210 V BluetoothSapService: Starting SAP server process
08-16 15:26:42.413  7210  7210 V BluetoothSapService: SAP Service startRfcommListenerThread
08-16 15:26:42.414  7210  7879 V BluetoothSapService: Sap Service initRfcommSocket
,08-16 15:26:42.415  1044  1059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:26:42.399  7878  7878 W sapd    : type=1400 audit(0.0:179): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 15:26:42.399  7878  7878 W sapd    : type=1400 audit(0.0:180): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 15:26:42.416  7210  7879 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 15:26:42.416  7210  7879 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=81
08-16 15:26:42.417  7210  7879 V BluetoothSapService: Succeed to create listening socket 
08-16 15:26:42.417  7210  7879 V BluetoothSapService: Accepting socket connection...
08-16 15:26:42.425  7878  7878 V BT_SAP  : Event pipe created
08-16 15:26:42.425  7878  7878 V BT_SAP  : create_server_socket qcom.sap.server
08-16 15:26:42.425  7878  7878 V BT_SAP  : created socket fd 6
,08-16 15:26:42.589  7831  7831 I UEI.SmartControl: Supports setup maps: true
,08-16 15:26:42.592  7831  7831 D UEI.SmartControl: QS start statue = true Error code = 0
,08-16 15:26:42.592  7831  7831 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 15:26:42.592  7831  7831 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-16 15:26:42.592  7831  7831 I UEI.SmartControl: ### init IR Blaster...
08-16 15:26:42.597  7831  7831 D serial_port: Configuring serial port
08-16 15:26:42.600  7831  7831 E UEI.SmartControl: UEIBLaster setting for 616
08-16 15:26:42.600  7831  7831 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 15:26:42.600  7831  7831 I UEI.SmartControl: configuring settings for MAXQ616
08-16 15:26:42.600  7831  7831 I UEI.SmartControl: Get version...
08-16 15:26:42.617  7831  7881 D UEI.SmartControl: serial port data available: 21
,08-16 15:26:42.646  7831  7831 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-16 15:26:42.646  7831  7831 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-16 15:26:42.647  7831  7831 I UEI.SmartControl: QS saving settings...
08-16 15:26:42.649  7831  7831 D UEI.SmartControl: IR Blaster version: 25672567
08-16 15:26:42.666  7831  7881 D UEI.SmartControl: serial port data available: 4
,08-16 15:26:42.701  7831  7887 I UEI.SmartControl: Device manager: loading config....
,08-16 15:26:42.704  7831  7887 D UEI.SmartControl: ----------- loading internal config...
08-16 15:26:42.707  7831  7831 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-16 15:26:42.709  7831  7831 E UEI.SmartControl: Services init done
08-16 15:26:42.709  7831  7831 D UEI.SmartControl: QS Service init finished
08-16 15:26:42.711  7831  7831 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 15:26:42.711  7831  7831 D UEI.SmartControl: QS Service version code: 201091
08-16 15:26:42.711  7831  7831 D UEI.SmartControl: Service requested: Control
,08-16 15:26:42.721  7831  7887 E UEI.SmartControl: Loading SETTINGS...
08-16 15:26:42.724  7831  7831 D UEI.SmartControl: Request IControl service: devices are loaded...
,08-16 15:26:42.730  1044  2036 I ActivityManager: Killing 7152:com.lge.qremote/u0a112 (adj 15): empty #17
08-16 15:26:42.742  7831  7887 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
,08-16 15:26:42.761  7831  7886 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-16 15:26:42.761  7831  7886 D UEI.SmartControl: -----service ready thread exits
,08-16 15:26:42.786  1044  1981 W libprocessgroup: failed to open /acct/uid_10112/pid_7152/cgroup.procs: No such file or directory
,08-16 15:26:42.787  7831  7831 D UEI.SmartControl: Internal service binding...
08-16 15:26:42.930  1589  1589 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-16 15:26:42.970  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 15:26:42.988  1044  1044 D administrator: Handling package changes for user 0
,08-16 15:26:43.022  1044  1419 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 15:26:43.047   353   353 I art     : Background concurrent mark sweep GC freed 788(33KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 10.660ms total 42.407ms
,08-16 15:26:43.077  1044  1115 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=7904 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-16 15:26:43.085  1589  1589 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
08-16 15:26:43.088  1589  1589 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-16 15:26:43.130  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 15:26:43.163  7904  7904 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 15:26:43.191  1044  1044 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
,08-16 15:26:43.191  1044  1044 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 15:26:43.247  1044  1114 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 15:26:43.249  7904  7904 D LgDataFeature: LgDataFeature() Constructor: none
08-16 15:26:43.249  7904  7904 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 15:26:43.252  1044  1114 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-16 15:26:43.259  2470  2470 V GmsNetworkLocationProvi: DISABLE
08-16 15:26:43.260  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-16 15:26:43.288  1044  1114 D LocationProviderProxy: applying state to connected service
,08-16 15:26:43.290  2470  2470 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-16 15:26:43.368  7210  7210 V BluetoothOppNotification: new notify threadi!
08-16 15:26:43.368  7210  7210 V BluetoothOppNotification: send delay message
,08-16 15:26:43.371  7210  7939 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 15:26:43.375  7210  7939 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ec6a25 on behalf of 
08-16 15:26:43.376  7210  7939 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 15:26:43.378  7210  7939 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 15:26:43.385  7210  7939 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a9ea7fa on behalf of 
08-16 15:26:43.387  7210  7939 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-16 15:26:43.391  7210  7939 V BluetoothOppNotification: outbound notification was removed.
08-16 15:26:43.391  7210  7939 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 15:26:43.392  7210  7939 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2217e1ab on behalf of 
08-16 15:26:43.393  7210  7939 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 15:26:43.394  7210  7939 V BluetoothOppNotification: inbound notification was removed.
08-16 15:26:43.394  7210  7939 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 15:26:43.398  7210  7939 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f6008 on behalf of 
,08-16 15:26:43.405  7904  7943 I Babel   : MmsConfig: mnc/mcc: 0/0
,08-16 15:26:43.405  7904  7943 I Babel   : MmsConfig.loadMmsSettings
08-16 15:26:43.422  7904  7943 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-16 15:26:43.422  7904  7943 I Babel   : MmsConfig.loadFromDatabase
,08-16 15:26:43.451  7904  7904 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:26:43.454  7904  7943 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-16 15:26:43.454  7904  7943 I Babel   : MmsConfig.loadFromResources
08-16 15:26:43.459  7904  7943 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-16 15:26:43.459  7904  7943 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-16 15:26:43.462  7904  7941 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 15:26:43.466  7904  7941 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 15:26:43.469  7904  7941 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
08-16 15:26:43.483  1803  7948 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-16 15:26:43.483  1803  7948 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
,08-16 15:26:43.487  7278  7278 I AppUp4:CustModeStarterReceiver: onReceive
08-16 15:26:43.492  7278  7278 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@37a4402e
08-16 15:26:43.492  7278  7278 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 15:26:43.492  7278  7278 D AppUp4:CustFacade: isPhone : true
08-16 15:26:43.493  7278  7278 D AppUp4:CustModeStarterReceiver: begin check event
08-16 15:26:43.493  7278  7278 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-16 15:26:43.497  7904  7941 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
08-16 15:26:43.498  7904  7941 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 15:26:43.499  7904  7941 W AudioCapabilities: Unsupported mime audio/evrc
,08-16 15:26:43.515  1803  5203 I Icing   : updateResources: need to parse e{com.google.android.gms}
,08-16 15:26:43.535  1044  1942 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=7954 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-16 15:26:43.537  7904  7941 W VideoCapabilities: Unsupported mime video/x-ms-wmv
,08-16 15:26:43.540  7904  7941 W VideoCapabilities: Unsupported mime video/divx
08-16 15:26:43.543  7904  7941 W VideoCapabilities: Unsupported mime video/divx311
08-16 15:26:43.545  7904  7941 W VideoCapabilities: Unsupported mime video/divx4
,08-16 15:26:43.575  7904  7941 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-16 15:26:43.580  1044  1774 I ActivityManager: Killing 7123:com.lge.sync/1000 (adj 15): empty #17
08-16 15:26:43.594  7904  7941 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-16 15:26:43.596  7954  7954 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 15:26:43.597  7954  7954 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 15:26:43.597  7954  7954 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 15:26:43.598  7904  7941 W AudioCapabilities: Unsupported mime audio/eac3
08-16 15:26:43.599  7954  7954 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-16 15:26:43.599  7954  7954 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 15:26:43.599  7904  7941 W AudioCapabilities: Unsupported mime audio/ac3
08-16 15:26:43.600  7904  7941 W AudioCapabilities: Unsupported mime audio/g726
08-16 15:26:43.601  7904  7941 W AudioCapabilities: Unsupported mime audio/wma-voice
08-16 15:26:43.602  7904  7941 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-16 15:26:43.603  7904  7941 W AudioCapabilities: Unsupported mime audio/adpcm
08-16 15:26:43.604  7904  7941 W VideoCapabilities: Unsupported mime video/theora
08-16 15:26:43.606  7904  7941 W VideoCapabilities: Unsupported mime video/mjpg
08-16 15:26:43.646  1044  1942 W libprocessgroup: failed to open /acct/uid_1000/pid_7123/cgroup.procs: No such file or directory
,08-16 15:26:43.686  7954  7954 I SystemConfig: BUILD Country: EU
08-16 15:26:43.686  7954  7954 I SystemConfig: BUILD Operator: OPEN
,08-16 15:26:43.736  1044  1773 I ActivityManager: Killing 7583:com.google.android.gms.unstable/u0a5 (adj 15): empty #17
,08-16 15:26:43.887  1044  2009 W libprocessgroup: failed to open /acct/uid_10005/pid_7583/cgroup.procs: No such file or directory
,08-16 15:26:43.897  7954  7975 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-16 15:26:43.898  7954  7975 I SystemConfig: existFile = false
08-16 15:26:43.900  7954  7975 I SystemConfig: canReadFile = false
08-16 15:26:43.900  7954  7975 I SystemConfig: systemFeature RCS result false
08-16 15:26:43.900  7954  7975 D SystemConfig: refreshRcsSupport() :false
08-16 15:26:43.928  1044  1949 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=7980 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-16 15:26:43.982  7980  7980 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 15:26:43.982  7980  7980 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 15:26:43.982  7980  7980 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 15:26:43.982  7980  7980 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 15:26:44.050  7980  7980 I AppConfig: Total System Memory = 2995761152
,08-16 15:26:44.057  7980  7980 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-16 15:26:44.130  1044  2018 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=7999 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 15:26:44.135  1044  2018 I ActivityManager: Killing 7307:com.lge.email/u0a23 (adj 15): empty #17
08-16 15:26:44.175  1044  1977 W libprocessgroup: failed to open /acct/uid_10023/pid_7307/cgroup.procs: No such file or directory
,08-16 15:26:44.377  7999  7999 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-16 15:26:44.496  7999  7999 D LgDataFeature: LgDataFeature() Constructor: none
08-16 15:26:44.497  7999  7999 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 15:26:44.570  7999  7999 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-16 15:26:44.594  7999  7999 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 15:26:44.597  7999  7999 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 15:26:44.613  7999  7999 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 15:26:44.613  7999  7999 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-16 15:26:44.631  1044  1059 I ActivityManager: Killing 7193:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-16 15:26:44.663  1044  1916 W libprocessgroup: failed to open /acct/uid_10026/pid_7193/cgroup.procs: No such file or directory
,08-16 15:26:44.669  5023  8039 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-16 15:26:44.672  2826  2844 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
,08-16 15:26:44.728  1044  1981 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8040 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-16 15:26:44.817  1044  1907 I art     : Explicit concurrent mark sweep GC freed 37018(1821KB) AllocSpace objects, 0(0B) LOS objects, 33% free, 43MB/64MB, paused 2.621ms total 143.492ms
,08-16 15:26:44.825  2826  2844 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@10fe7f43 on behalf of 7999
08-16 15:26:44.836  7999  7999 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
,08-16 15:26:44.863  7999  7999 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
,08-16 15:26:44.878  8040  8040 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
,08-16 15:26:44.895  8040  8040 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
,08-16 15:26:44.895  8040  8040 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
,08-16 15:26:44.895  8040  8040 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-16 15:26:44.895  8040  8040 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
08-16 15:26:44.895  8040  8040 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-16 15:26:44.895  8040  8040 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-16 15:26:44.909  1044  1949 I ActivityManager: Killing 6486:com.wsandroid.suite.lge/1000 (adj 15): empty #17
,08-16 15:26:44.938  1044  1942 W libprocessgroup: failed to open /acct/uid_1000/pid_6486/cgroup.procs: No such file or directory
,08-16 15:26:45.127  1044  1638 V SIM_STK : Menu title from STK is T-Mobile
,08-16 15:26:45.165  5023  8039 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 496 ms] updated apps [took 496 ms] 
,08-16 15:26:46.038  1044  1059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
,08-16 15:26:46.038  1044  1059 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2eebb999 mBinding = false
,08-16 15:26:46.067  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 15:26:46.067  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 15:26:46.067  1044  1044 D Ulp_jni : JNI:system_update. Event-4
,08-16 15:26:46.070  1044  1119 D BluetoothManagerService: Message: 2
08-16 15:26:46.071  1044  1119 D BluetoothManagerService: Sending off request.
08-16 15:26:46.072  7210  7227 D LGBluetoothServiceAdapter: [BTUI] Precleanup
08-16 15:26:46.073  7210  7732 D BluetoothAdapterState: CURRENT_STATE=ON, MESSAGE = USER_TURN_OFF
08-16 15:26:46.073  7210  7732 D BluetoothAdapterProperties: Setting state to 13
08-16 15:26:46.073  7210  7732 I BluetoothAdapterState: Bluetooth adapter state changed: 12-> 13
08-16 15:26:46.074  7210  7732 D BluetoothAdapterProperties: onBluetoothDisable()
08-16 15:26:46.074  7210  7732 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=false, isTurningOff()=true
08-16 15:26:46.076  7210  7736 D BluetoothAdapterProperties: Scan Mode:20
08-16 15:26:46.077  7210  7732 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = BEGIN_DISABLE, isTurningOn=false, isTurningOff=true
08-16 15:26:46.079  7210  7860 V BluetoothMapMasInstance: Accept exception: (expected at shutdown)
08-16 15:26:46.079  7210  7860 V BluetoothMapMasInstance: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 15:26:46.079  7210  7860 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.readAll(BluetoothSocket.java:586)
08-16 15:26:46.079  7210  7860 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.waitSocketSignal(BluetoothSocket.java:563)
08-16 15:26:46.079  7210  7860 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothSocket.accept(BluetoothSocket.java:418)
08-16 15:26:46.079  7210  7860 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:130)
08-16 15:26:46.079  7210  7860 V BluetoothMapMasInstance: 	at android.bluetooth.BluetoothServerSocket.accept(BluetoothServerSocket.java:116)
08-16 15:26:46.079  7210  7860 V BluetoothMapMasInstance: 	at com.android.bluetooth.map.BluetoothMapMasInstance$SocketAcceptThread.run(BluetoothMapMasInstance.java:133)
08-16 15:26:46.081  7210  7866 V BluetoothPbapService: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
,08-16 15:26:46.084  7210  7877 V BluetoothFtpService:RfcommSocketAcceptThread: Accept exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 15:26:46.086  1044  1531 D ConnectivityService: Failed to find a new network - expiring NetTransition Wakelock
08-16 15:26:46.086  7210  7791 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x000f
08-16 15:26:46.087  7210  7879 V BluetoothSapService: Accept thread exception: java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 15:26:46.087  7210  7875 E BtOppRfcommListener: Error accept connection java.io.IOException: read failed, socket might closed or timeout, read ret: -1
08-16 15:26:46.087  7210  7791 W bt-btif : bta_dm_disable BTA_DISABLE_DELAY set to 1000 ms
08-16 15:26:46.089  7210  7791 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 15:26:46.089  7210  7791 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 15:26:46.089  7210  7791 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 15:26:46.089  7210  7791 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 15:26:46.089  7210  7791 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 15:26:46.089  7210  7791 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 15:26:46.089  7210  7791 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 15:26:46.089  7210  7791 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 15:26:46.089  7210  7791 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 15:26:46.089  7210  7791 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0011
08-16 15:26:46.089  7210  7791 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0013
08-16 15:26:46.089  7210  7791 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 15:26:46.090  7210  7732 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
08-16 15:26:46.095  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
,08-16 15:26:46.106  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:26:46.106  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:46.106  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:46.106  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:26:46.106  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:26:46.106  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:26:46.106  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:26:46.106  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:26:46.107  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:46.107  6974  6974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:26:46.112  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:46.112  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:26:46.112  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:46.112  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:46.112  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:26:46.112  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:26:46.112  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:26:46.112  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:26:46.112  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 15:26:46.116  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:46.116  6974  6974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:26:46.118  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:46.118  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:26:46.118  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:46.118  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:46.118  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:26:46.118  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: false
08-16 15:26:46.118  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:26:46.118  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:26:46.118  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:26:46.119  6974  6974 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: Checking support for multiple advertisement: Cannot do the check when the Bluetooth is disabled - will return stored value
08-16 15:26:46.119  6974  6974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: OFF, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:26:46.121  1044  1119 D BluetoothManagerService: Message: 60
08-16 15:26:46.121  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 12, newState=13
08-16 15:26:46.121  1044  1119 D BluetoothManagerService: Bluetooth State Change Intent: 12 -> 13
08-16 15:26:46.123  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 15:26:46.125  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 15:26:46.133  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:46.136  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:46.137  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:26:46.140  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:26:46.140  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:46.151  7210  7210 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:46.151  7210  7210 D BluetoothMapService: STATE_TURNING_OFF
08-16 15:26:46.151  7210  7210 V BluetoothMapService: Handler(): got msg=4
08-16 15:26:46.151  7210  7210 D BluetoothMapService: MAP Service closeService in
08-16 15:26:46.151  7210  7210 D BluetoothMapMasInstance: MAP Service shutdown
08-16 15:26:46.151  7210  7210 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 15:26:46.151  7210  7210 V BluetoothMapService: MAP Service closeService out
,08-16 15:26:46.156  7210  7210 V BtOppService: Receiver DISABLED_ACTION 
08-16 15:26:46.157  7210  7210 I BtOppRfcommListener: stopping Accept Thread
08-16 15:26:46.157  7210  7210 V BtOppRfcommListener: close mBtServerSocket
08-16 15:26:46.157  7210  7875 I BtOppRfcommListener: BluetoothSocket listen thread finished
08-16 15:26:46.159  7210  7210 V BtOppRfcommListener: waiting for thread to terminate
08-16 15:26:46.159  7210  7210 V BtOppRfcommListener: done waiting for thread to terminate
08-16 15:26:46.163  7091  7091 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_OFF
08-16 15:26:46.167  7091  7091 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
,08-16 15:26:46.177  7210  7210 V BtOppService: onDestroy
08-16 15:26:46.180  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:46.180  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@17ad27b removed from the list
08-16 15:26:46.180  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:26:46.180  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:46.180  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:46.181  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 15:26:46.181  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@39b068f1 added. We now have 4 listener(s)
08-16 15:26:46.181  6974  7031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 15:26:46.184  7210  7210 D LGBluetoothOppAdapter: [BTUI] LGBluetoothOppAdapter cleanup
08-16 15:26:46.188  7210  7210 V BluetoothPbapReceiver: PbapReceiver onReceive 
,08-16 15:26:46.188  7210  7210 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:46.188  7210  7210 V BluetoothPbapReceiver: ***********state = 13
08-16 15:26:46.190  7210  7210 V BluetoothPbapReceiver: ***********Calling start service!!!! with action = null
08-16 15:26:46.193  7210  7210 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:46.193  7210  7210 V BluetoothPbapService: state: 13
08-16 15:26:46.193  7210  7210 V BluetoothPbapService: Pbap Service closeService in
,08-16 15:26:46.201  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:46.201  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@39b068f1 removed from the list
08-16 15:26:46.201  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:26:46.201  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:46.201  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:46.203  2173  2173 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 15:26:46.205  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
,08-16 15:26:46.205  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b7c4cd6 added. We now have 4 listener(s)
08-16 15:26:46.205  6974  7031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 15:26:46.206  7210  7210 V BluetoothPbapService: successfully stopped pbap service
08-16 15:26:46.206  7210  7210 V BluetoothPbapService: Pbap Service closeService out
08-16 15:26:46.207  7210  7210 V BluetoothPbapService: Pbap Service onDestroy
08-16 15:26:46.207  7210  7210 V BluetoothPbapService: Pbap Service closeService in
08-16 15:26:46.207  7210  7210 V BluetoothPbapService: Pbap Service closeService out
08-16 15:26:46.207  7210  7210 D LGBluetoothPbapAdapter: [BTUI] cleanup
08-16 15:26:46.210  7091  7091 D DockEventReceiver: finishStartingService: stopping service
08-16 15:26:46.211  7091  7091 D BluetoothPbap: Proxy object disconnected
08-16 15:26:46.212  7091  7091 D PbapServerProfile: Bluetooth service disconnected
,08-16 15:26:46.224  1044  1949 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:26:46.224  1044  1949 D BluetoothManagerService: disable(): mBluetooth = android.bluetooth.IBluetooth$Stub$Proxy@2eebb999 mBinding = false
08-16 15:26:46.224  1044  1119 D BluetoothManagerService: Message: 2
08-16 15:26:46.224  1044  1119 D BluetoothManagerService: Sending off request.
08-16 15:26:46.226  7210  7228 D LGBluetoothServiceAdapter: [BTUI] Precleanup
,08-16 15:26:46.226  7210  7228 D BluetoothAdapterService: disable() : BT State is not STATE_ON. Can't disable BT
08-16 15:26:46.226  1044  1119 E BluetoothManagerService: IBluetooth.disable() returned false
08-16 15:26:46.236  7091  7091 D LGBluetoothAuthorization: [BTUI] cancel All Notification
,08-16 15:26:46.242  7091  7091 D BluetoothPermissionRequest: onReceive
08-16 15:26:46.242  7091  7091 D LGBluetoothAuthorization: [BTUI] cancel All Notification,
08-16 15:26:46.247  7091  7091 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 15:26:46.252  7210  7210 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_TURNING_OFF
08-16 15:26:46.252  7210  7210 D BluetoothOppNotification: [BTUI] cancel opp incoming file confirm notification
,08-16 15:26:46.253  7210  7210 D BluetoothOppNotification: [BTUI] cancel opp active transfer file notification
08-16 15:26:46.257  7210  7210 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:46.258  7210  7210 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
,08-16 15:26:46.259  7210  7210 V BluetoothFtpService: Ftp Service onStartCommand
08-16 15:26:46.259  7210  7210 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:46.259  7210  7210 V BluetoothFtpService: Ftp Service closeService
08-16 15:26:46.259  7210  7210 E BluetoothFtpService:RfcommSocketAcceptThread: Shutdown
08-16 15:26:46.260  7210  7210 V BluetoothFtpService: successfully stopped ftp service
08-16 15:26:46.261  7210  7210 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 15:26:46.261  7210  7210 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 15:26:46.261  7210  7210 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 15:26:46.262  7210  7210 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:46.262  7210  7210 V BluetoothSapReceiver:  Bluetooth Adapter state = 13
08-16 15:26:46.262  7210  7210 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 15:26:46.263  7210  7210 V BluetoothFtpService: Ftp Service onDestroy
08-16 15:26:46.263  7210  7210 V BluetoothFtpService: Ftp Service closeService
08-16 15:26:46.267  7210  7210 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:46.267  7210  7210 V BluetoothSapService: state: 13
08-16 15:26:46.267  7210  7210 V BluetoothSapService: Stopping SAP server process
08-16 15:26:46.269  7210  7210 V BluetoothSapService: Sap Service closeSapService in
08-16 15:26:46.269  7210  7210 V BluetoothSapService: Close listen Socket : 
08-16 15:26:46.269  7210  7210 V BluetoothSapService: Close rfcomm Socket : 
08-16 15:26:46.270  7210  7210 V BluetoothSapService: Close sapd  Socket : 
,08-16 15:26:46.271  7210  7210 V BluetoothSapService: Sap Service closeSapService out
08-16 15:26:46.271  7210  7210 V BluetoothSapService: Sap Service onDestroy
08-16 15:26:46.271  7210  7210 V BluetoothSapService: Sap Service closeSapService in
08-16 15:26:46.271  7210  7210 V BluetoothSapService: Close listen Socket : 
08-16 15:26:46.271  7210  7210 V BluetoothSapService: Close rfcomm Socket : 
08-16 15:26:46.271  7210  7210 V BluetoothSapService: Close sapd  Socket : 
08-16 15:26:46.272  7210  7210 V BluetoothSapService: Sap Service closeSapService out
08-16 15:26:47.063  7210  7736 D bt_hci_bdroid: cleanup
,08-16 15:26:47.066  7210  7793 I bt_lpm  : LPM is already off!!!
08-16 15:26:47.066  7210  7849 I bt_userial_mct: exiting userial_read_thread
08-16 15:26:47.067  7210  7849 D bt_userial_mct: Leaving userial_evt_read_thread()
08-16 15:26:47.067  7210  7791 W bt-btif : ag scb idx 1 not allocated
08-16 15:26:47.067  7210  7791 E bt-btif : BTA AG is already disabled, ignoring ...
08-16 15:26:47.067  7210  7791 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 15:26:47.067  7210  7791 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 15:26:47.067  7210  7791 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 15:26:47.067  7210  7791 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 15:26:47.067  7210  7791 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 15:26:47.067  7210  7791 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 15:26:47.068  7210  7791 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 15:26:47.068  7210  7791 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 15:26:47.068  7210  7791 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 15:26:47.068  7210  7791 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 15:26:47.068  7210  7791 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 15:26:47.068  7210  7791 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 15:26:47.068  7210  7791 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0019
08-16 15:26:47.068  7210  7791 W bt-l2cap: L2CAP - PSM: 0x0019 not found for deregistration
08-16 15:26:47.068  7210  7791 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x0017
08-16 15:26:47.068  7210  7791 W bt-l2cap: L2CAP - PSM: 0x0017 not found for deregistration
08-16 15:26:47.068  7210  7791 W bt-l2cap: L2CAP - L2CA_Deregister() called for PSM: 0x001b
08-16 15:26:47.068  7210  7791 W bt-l2cap: L2CAP - PSM: 0x001b not found for deregistration
08-16 15:26:47.068  7210  7791 E bt-btif : bta_gattc_deregister Deregister Failedm unknown client cif
08-16 15:26:47.068  7210  7736 D bt_userial_mct: userial_close_reader Joined userial reader thread: 0
08-16 15:26:47.069  7210  7793 I bt_vendor: hw_epilog_process
08-16 15:26:47.069  7210  7736 D bt_hci_bdroid: cleanup Finalizing cleanup
08-16 15:26:47.069  7210  7736 D bt_userial_mct: userial_close
08-16 15:26:47.069  7210  7736 E bt_userial_mct: pthread_join() FAILED result:3
08-16 15:26:47.069  7210  7736 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_CLOSE btSocType: 0
08-16 15:26:47.085  7210  7736 D bt_hci_bdroid: set_power 0
08-16 15:26:47.085  7210  7736 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: Off
08-16 15:26:47.085  7210  7736 I bt_vendor: bluetooth satus is on
08-16 15:26:47.085  7210  7736 I bt_vendor: bt-vendor : resetting BT status
08-16 15:26:47.085  7210  7736 I bt_vendor: Starting hciattach daemon
08-16 15:26:47.085  7210  7736 I bt_vendor: try to set false
,08-16 15:26:47.092  7210  7736 I bt_vendor: Starting hciattach daemon
08-16 15:26:47.092  7210  7736 I bt_vendor: try to set false
08-16 15:26:47.093  7210  7736 I bt_vendor: cleanup
08-16 15:26:47.095  7210  7791 I GKI_LINUX: gki_task task_id=0 [BTU] terminating
08-16 15:26:47.095  7210  7736 I GKI_LINUX: GKI_exit_task 0 done
08-16 15:26:47.095  7210  7736 I GKI_LINUX: GKI_shutdown(): task [BTU] terminated
08-16 15:26:47.097  7210  7732 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = DISABLED, isTurningOn=false, isTurningOff=true
08-16 15:26:47.101  7210  7210 D HeadsetService: Received stop request...Stopping profile...
,08-16 15:26:47.106  7210  7210 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
08-16 15:26:47.106  7210  7210 W LGBluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 15:26:47.106  7210  7210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:47.107  7210  7772 D HeadsetStateMachine: Exit Disconnected: -1
08-16 15:26:47.110  1044  1044 D BluetoothHeadset: Proxy object disconnected
08-16 15:26:47.110  1044  1044 D AudioService: onServiceDisconnected: Bluetooth profile: 1
08-16 15:26:47.111  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-16 15:26:47.111  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-16 15:26:47.111  1839  1839 D BluetoothHeadset: Proxy object disconnected
08-16 15:26:47.112  7210  7210 D A2dpService: Received stop request...Stopping profile...
08-16 15:26:47.113  7210  7783 D A2dpStateMachine: Exit Disconnected: -1
08-16 15:26:47.115  7210  7210 D LGBluetoothAvrcpQcomAdapter: [BTUI] cleanup
,08-16 15:26:47.122  7210  7732 D BluetoothAdapterState: Stopping profile services that were post enabled
08-16 15:26:47.122  7210  7210 D LGBluetoothA2dpAdapter: [BTUI] LGBluetoothA2dpAdapter cleanup
08-16 15:26:47.122  7210  7210 W LGBluetoothA2dpServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 15:26:47.122  7210  7210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:47.125  1044  1044 D BluetoothA2dp: Proxy object disconnected
08-16 15:26:47.125  1044  1044 D AudioService: onServiceDisconnected: Bluetooth profile: 2
08-16 15:26:47.125  7210  7210 D HidService: Received stop request...Stopping profile...
08-16 15:26:47.125  7210  7210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:47.127  7210  7210 D HeadsetStateMachine: Unbinding service...
08-16 15:26:47.129  7210  7210 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 15:26:47.129  7210  7210 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 15:26:47.129  7210  7210 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 15:26:47.130  7210  7210 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 15:26:47.130  7210  7210 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree Interface...
08-16 15:26:47.130  7210  7210 W BluetoothHeadsetServiceJni: Cleaning up Bluetooth Handsfree callback object
08-16 15:26:47.130  7210  7210 I LGBluetoothHfpAdapter: [BTUI] LGBluetoothHfpAdapter cleanup
,08-16 15:26:47.133  7210  7210 D HealthService: Received stop request...Stopping profile...
08-16 15:26:47.133  7210  7210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:47.135  7210  7210 D PanService: Received stop request...Stopping profile...
08-16 15:26:47.136  7210  7210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:47.137  7210  7210 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 15:26:47.138  7210  7210 D BtGatt.GattService: Received stop request...Stopping profile...
08-16 15:26:47.138  7210  7210 D BtGatt.GattService: stop()
08-16 15:26:47.138  7210  7210 D BtGatt.AdvertiseManager: advertise clients cleared
08-16 15:26:47.139  7210  7210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:47.142  7210  7210 D BluetoothMapService: Received stop request...Stopping profile...
08-16 15:26:47.142  7210  7210 D BluetoothMapService: stop()
,08-16 15:26:47.145  7210  7210 D BluetoothMapEmailAppObserver: deinitObservers()
08-16 15:26:47.145  7210  7210 D BluetoothMapEmailAppObserver: removeReceiver()
08-16 15:26:47.146  7210  7210 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:47.147  7210  7210 I BluetoothA2dpServiceJni: cleanupNative
08-16 15:26:47.147  7210  7784 I GKI_LINUX: gki_task task_id=2 [A2DP-MEDIA] terminating
08-16 15:26:47.148  7210  7210 I GKI_LINUX: GKI_exit_task 2 done
08-16 15:26:47.148  7210  7210 I GKI_LINUX: GKI_shutdown(): task [A2DP-MEDIA] terminated
08-16 15:26:47.148  7210  7210 W BluetoothHidServiceJni: Cleaning up Bluetooth HID Interface...
08-16 15:26:47.148  7210  7210 W BluetoothHidServiceJni: Cleaning up Bluetooth GID callback object
08-16 15:26:47.148  7210  7210 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health Interface...
08-16 15:26:47.149  7210  7210 W BluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 15:26:47.149  7210  7210 W LGBluetoothHealthServiceJni: Cleaning up Bluetooth Health object
08-16 15:26:47.149  7210  7210 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN Interface...
08-16 15:26:47.149  7210  7210 W BluetoothPanServiceJni: Cleaning up Bluetooth PAN callback object
08-16 15:26:47.152  7210  7210 V BluetoothMapService: Handler(): got msg=4
08-16 15:26:47.152  7210  7210 D BluetoothMapService: MAP Service closeService in
08-16 15:26:47.152  7210  7210 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 15:26:47.152  7210  7210 V BluetoothMapService: MAP Service closeService out
08-16 15:26:47.154  7210  7732 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STOPPED, isTurningOn=false, isTurningOff=true
08-16 15:26:47.155  7210  7732 D BluetoothAdapterProperties: Setting state to 10
08-16 15:26:47.155  7210  7732 I BluetoothAdapterState: Bluetooth adapter state changed: 13-> 10
,08-16 15:26:47.157  7210  7210 D BluetoothMapService: cleanup()
08-16 15:26:47.157  7210  7210 D BluetoothMapService: MAP Service closeService in
08-16 15:26:47.157  7210  7210 D LGBluetoothMapAdapter: [BTUI] LGBluetoothMapAdapter cleanup
08-16 15:26:47.157  7210  7210 V BluetoothMapService: MAP Service closeService out
08-16 15:26:47.159  1044  1119 D BluetoothManagerService: Message: 60
08-16 15:26:47.159  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 13, newState=10
08-16 15:26:47.159  1044  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(false) to 11 receivers.
08-16 15:26:47.159  1044  1119 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 15:26:47.159  7210  7732 I BluetoothAdapterState: Entering OffState
08-16 15:26:47.160  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 15:26:47.160  1839  2447 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 15:26:47.163  7091  7190 D BluetoothMap: onBluetoothStateChange: up=false
08-16 15:26:47.164  7091  7190 D BluetoothPbap: onBluetoothStateChange: up=false
08-16 15:26:47.164  7091  7190 D BluetoothPan: onBluetoothStateChange on: false
08-16 15:26:47.166  7091  7190 D BluetoothInputDevice: onBluetoothStateChange: up=false
,08-16 15:26:47.168  1044  1119 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 15:26:47.169  1839  1854 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 15:26:47.169  7091  7190 D BluetoothA2dp: onBluetoothStateChange: up=false
08-16 15:26:47.170  7091  7190 D BluetoothHeadset: onBluetoothStateChange: up=false
08-16 15:26:47.171  1044  1119 D BluetoothManagerService: Calling onBluetoothServiceDown callbacks
08-16 15:26:47.171  1044  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceDown() to 8 receivers.
08-16 15:26:47.174  1044  1119 D BluetoothManagerService: Calling onQBluetoothServiceDown callbacks
08-16 15:26:47.174  1044  1119 D BluetoothManagerService: Broadcasting onQBluetoothServiceDown() to 0 receivers.
08-16 15:26:47.174  1044  1119 D BluetoothManagerService: unbindAndFinish(): android.bluetooth.IBluetooth$Stub$Proxy@2eebb999 mBinding = false
08-16 15:26:47.175  1044  1119 D BluetoothManagerService: Sending unbind request.
08-16 15:26:47.179  7210  7736 I GKI_LINUX: gki_task task_id=1 [BTIF] terminating
,08-16 15:26:47.182  7210  7210 I GKI_LINUX: GKI_exit_task 1 done
08-16 15:26:47.182  7210  7210 I GKI_LINUX: GKI_shutdown(): task [BTIF] terminated
08-16 15:26:47.183  7210  7210 I BluetoothServiceJni: cleanupNative: return from cleanup
08-16 15:26:47.183  7210  7210 I art     : --- WEIRD: removing null entry 248
,08-16 15:26:47.183  7210  7210 W art     : JNI WARNING: DeleteGlobalRef(0x2003e2) failed to find entry
08-16 15:26:47.183  7210  7210 W LGBluetoothServiceJni: Cleaning up Bluetooth Service callback object
,08-16 15:26:47.184  7210  7210 D LGBluetoothSettingsDBObserver: [BTUI] unregister observer for LG device name DB
08-16 15:26:47.185  1044  1119 D BluetoothManagerService: Bluetooth State Change Intent: 13 -> 10
08-16 15:26:47.187  7210  7210 I art     : System.exit called, status: 0
08-16 15:26:47.188  7210  7210 I AndroidRuntime: VM exiting with result code 0, cleanup skipped.
08-16 15:26:47.202  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:47.203  1927  2069 D LGBluetoothAPIService: Message: 2
08-16 15:26:47.203  1927  2069 D LGBluetoothAPIService: unbindAndFinish(): com.lge.bluetooth.ILGBluetoothAPIAdapter$Stub$Proxy@64d9375 mBinding = false
08-16 15:26:47.203  1927  2069 D LGBluetoothAPIService: Sending unbind request.
,08-16 15:26:47.208  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
,08-16 15:26:47.217   326   326 V AudioFlinger: 7210 died, releasing its sessions
08-16 15:26:47.217   326   326 V AudioFlinger:  pid 1839 @ 0
08-16 15:26:47.218   326   326 V AudioFlinger:  pid 3304 @ 1
08-16 15:26:47.218   326   326 V AudioFlinger:  pid 3304 @ 2
08-16 15:26:47.218  1044  1907 W ActivityManager: Exception when unbinding service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothAPIServer
08-16 15:26:47.218  1044  1907 W ActivityManager: android.os.DeadObjectException
08-16 15:26:47.218  1044  1907 W ActivityManager: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 15:26:47.218  1044  1907 W ActivityManager: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 15:26:47.218  1044  1907 W ActivityManager: 	at android.app.ApplicationThreadProxy.scheduleUnbindService(ApplicationThreadNative.java:917)
08-16 15:26:47.218  1044  1907 W ActivityManager: 	at com.android.server.am.ActiveServices.removeConnectionLocked(ActiveServices.java:1776)
08-16 15:26:47.218  1044  1907 W ActivityManager: 	at com.android.server.am.ActiveServices.unbindServiceLocked(ActiveServices.java:901)
08-16 15:26:47.218  1044  1907 W ActivityManager: 	at com.android.server.am.ActivityManagerService.unbindService(ActivityManagerService.java:15417)
08-16 15:26:47.218  1044  1907 W ActivityManager: 	at android.app.ActivityManagerNative.onTransact(ActivityManagerNative.java:963)
08-16 15:26:47.218  1044  1907 W ActivityManager: 	at com.android.server.am.ActivityManagerService.onTransact(ActivityManagerService.java:2560)
08-16 15:26:47.218  1044  1907 W ActivityManager: 	at com.android.server.am.ActivityManagerServiceEx.onTransact(ActivityManagerServiceEx.java:421)
08-16 15:26:47.218  1044  1907 W ActivityManager: 	at android.os.Binder.execTransact(Binder.java:446)
,08-16 15:26:47.220  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:47.222  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:47.222  7091  7091 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_OFF
08-16 15:26:47.222  7091  7091 D LGBluetoothEventManager: [BTUI] clear device connection state
08-16 15:26:47.222  1589  1589 D BluetoothAdapter: 533506119: getState() :  mService = null. Returning STATE_OFF
08-16 15:26:47.222  1589  1589 D BluetoothAdapter: 533506119: getState() :  mService = null. Returning STATE_OFF
08-16 15:26:47.222  7091  7091 D LGBluetoothUserBindClient: [BTUI] onServiceDisconnected
08-16 15:26:47.224  7091  7091 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 15:26:47.275  1044  1981 I ActivityManager: Process com.android.bluetooth (pid 7210) has died
08-16 15:26:47.275  1044  1981 W ActivityManager: Scheduling restart of crashed service com.android.bluetooth/com.lge.bluetooth.app.LGBluetoothUserBindServer in 4000ms
,08-16 15:26:47.351  1044  2018 I ActivityManager: Start proc com.android.bluetooth for broadcast com.android.bluetooth/.pbap.BluetoothPbapReceiver: pid=8137 uid=1002 gids={41002, 9997, 3003, 3002, 3001, 1028, 1015, 3005, 1016, 3008, 4002, 1023} abi=armeabi-v7a
,08-16 15:26:47.354  7091  7091 D DockEventReceiver: finishStartingService: stopping service
,08-16 15:26:47.452  8137  8137 W ResourcesManager: Asset path '/system/framework/javax.obex.jar' does not exist or contains no resources.
,08-16 15:26:47.453  8137  8137 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 15:26:47.454  8137  8137 W ResourcesManager: Asset path '/system/framework/com.qcom.bluetooth.jar' does not exist or contains no resources.
,08-16 15:26:47.455  8137  8137 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
,08-16 15:26:47.477  8137  8137 D BluetoothAdapterApp: Loading JNI Library
,08-16 15:26:47.513  8137  8137 D BluetoothAdapterApp: REFCOUNT: Constructed com.android.bluetooth.btservice.AdapterApp@27dc51c4 Instance Count = 1
,08-16 15:26:47.518  8137  8137 D BluetoothAdapterApp: onCreate
08-16 15:26:47.538  8137  8137 D ProfileConfigQcom: [BTUI] HeadsetService is supported
08-16 15:26:47.538  8137  8137 D ProfileConfigQcom: Adding HeadsetService
08-16 15:26:47.538  8137  8137 D ProfileConfigQcom: [BTUI] A2dpService is supported
08-16 15:26:47.538  8137  8137 D ProfileConfigQcom: Adding A2dpService
,08-16 15:26:47.538  8137  8137 D ProfileConfigQcom: [BTUI] HidService is supported
,08-16 15:26:47.539  8137  8137 D ProfileConfigQcom: Adding HidService
08-16 15:26:47.539  8137  8137 D ProfileConfigQcom: [BTUI] HealthService is supported
08-16 15:26:47.539  8137  8137 D ProfileConfigQcom: Adding HealthService
,08-16 15:26:47.539  8137  8137 D LGBluetoothFeatureConfig: isSupportPan() :  mTargetOp=OPEN
08-16 15:26:47.540  8137  8137 D ProfileConfigQcom: [BTUI] PanService is supported
08-16 15:26:47.540  8137  8137 D ProfileConfigQcom: Adding PanService
08-16 15:26:47.540  8137  8137 D ProfileConfigQcom: [BTUI] GattService is supported
08-16 15:26:47.540  8137  8137 D ProfileConfigQcom: Adding GattService
08-16 15:26:47.541  8137  8137 D ProfileConfigQcom: [BTUI] BluetoothMapService is supported
08-16 15:26:47.541  8137  8137 D ProfileConfigQcom: Adding BluetoothMapService
08-16 15:26:47.541  8137  8137 D ProfileConfigQcom: [BTUI] HeadsetClientService is NOT supported
08-16 15:26:47.542  8137  8137 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 15:26:47.542  8137  8137 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:47.543  8137  8137 V BluetoothPbapReceiver: ***********state = 10
,08-16 15:26:47.544  8137  8137 V LGMDMManagerInternal: Create singleton instance,
08-16 15:26:47.602  2173  2173 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
,08-16 15:26:47.612  7091  7091 D LGBluetoothUserBindClient: [BTUI] onServiceConnected
08-16 15:26:47.615  7091  7091 D BluetoothPermissionRequest: onReceive
08-16 15:26:47.617  7091  7091 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 15:26:47.617  7091  7091 D BluetoothDiscoverableTimeoutReceiver: cancelDiscoverableAlarm(): Enter
08-16 15:26:47.621  7091  7091 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 15:26:47.631  8137  8137 D LGBluetoothOppAdapter: [BTUI] getInstance : create [LGBluetoothOppAdapter]
,08-16 15:26:47.639  8137  8137 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:47.644  8137  8137 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 15:26:47.644  8137  8137 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 15:26:47.644  8137  8137 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 15:26:47.645  8137  8137 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:47.645  8137  8137 V BluetoothSapReceiver:  Bluetooth Adapter state = 10
,08-16 15:26:47.656  7798  7798 D LGBluetoothProfileConnectionReceiver_EasySetting: [BTUI] STATE_OFF : reset connected device information EasySettings
08-16 15:26:47.661  1044  1907 I ActivityManager: Killing 7336:com.google.android.setupwizard/u0a46 (adj 15): empty #17
,08-16 15:26:47.706  7831  7888 D UEI.SmartControl: Internal timer expired: 1
08-16 15:26:47.707  7831  7888 D UEI.SmartControl: unbind internal service
,08-16 15:26:47.722  1044  1949 W libprocessgroup: failed to open /acct/uid_10046/pid_7336/cgroup.procs: No such file or directory
,08-16 15:26:47.731  7831  7831 D UEI.SmartControl: Service.onUnbind: IControl
08-16 15:26:47.732  7831  7831 D UEI.SmartControl: Service.onDestroy
08-16 15:26:47.732  7831  7831 D UEI.SmartControl: Lock is in USE false
08-16 15:26:47.732  7831  7831 D UEI.SmartControl: unbind internal service
08-16 15:26:47.732  7831  7831 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@938313a
,08-16 15:26:47.733  7831  7831 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-16 15:26:47.733  7831  7831 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-16 15:26:47.733  7831  7831 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-16 15:26:47.733  7831  7831 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-16 15:26:47.733  7831  7831 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-16 15:26:47.733  7831  7831 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-16 15:26:47.733  7831  7831 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-16 15:26:47.733  7831  7831 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-16 15:26:47.733  7831  7831 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 15:26:47.733  7831  7831 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 15:26:47.733  7831  7831 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 15:26:47.733  7831  7831 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 15:26:47.733  7831  7831 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 15:26:47.733  7831  7831 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 15:26:47.733  7831  7831 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 15:26:47.733  7831  7831 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@938313a
08-16 15:26:47.735  7831  7831 D serial_port: close(fd = 25)
,08-16 15:26:47.742  7831  7831 I UEI.SmartControl: Serial port is closed.
08-16 15:26:47.743  7831  7831 I UEI.SmartControl: Serial port is closed.
08-16 15:26:47.743  7831  7831 D UEI.SmartControl: Blaster closed
08-16 15:26:47.744  7831  7831 D UEI.SmartControl: Shut down QS...
08-16 15:26:47.745  7831  7831 D UEI.SmartControl: Stopping QS lib
08-16 15:26:47.745  7831  7831 D UEI.SmartControl: QS lib stop result = true
08-16 15:26:47.745  7831  7831 D UEI.SmartControl: Stopped QS lib
08-16 15:26:47.746  7831  7831 D UEI.SmartControl: Stopped file observer...
08-16 15:26:47.746  7831  7831 D UEI.SmartControl: QS shutdown complete
08-16 15:26:47.805  1589  1589 I [SystemUI]LGPowerUI: onReceive = com.lge.android.intent.action.BATTERYEX
08-16 15:26:47.806  1589  1589 I [SystemUI]LGPowerUI: On Skip Timer : true
,08-16 15:26:47.816  1044  1530 D WifiController: battery changed pluggedType: 2
,08-16 15:26:47.819  1927  2059 D LEDHandler: ACTION_BATTERY_CHANGED : plugged type=2
,08-16 15:26:47.819  1927  2059 D LEDHandler: Battery Level Remaining: 100%
08-16 15:26:47.819  1927  2059 D LEDHandler: Battery Temp: 285, mChargingStatus=5, mChargingStop=false
08-16 15:26:47.821  1589  1589 D KeyguardUpdateMonitor: Intent.ACTION_BATTERY_CHANGED status : 5 ,plugged : 2 ,level : 100 ,temperature : 285
08-16 15:26:47.821  1589  1589 I [SystemUI]LGPowerUI: onReceive = android.intent.action.BATTERY_CHANGED
08-16 15:26:47.822  1589  1589 I [SystemUI]BatterySaverHandler: onReceive = android.intent.action.BATTERY_CHANGED
08-16 15:26:51.232  6974  7031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:26:51.244  1044  1059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:26:51.245  1044  1059 D BluetoothManagerService: enable():  mBluetooth =null mBinding = false
08-16 15:26:51.257  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 15:26:51.257  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 0, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 0,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 15:26:51.257  1044  1044 D Ulp_jni : JNI:system_update. Event-4
,08-16 15:26:51.261  1044  1119 D BluetoothManagerService: Message: 1
08-16 15:26:51.261  1044  1119 D BluetoothManagerService: MESSAGE_ENABLE: mBluetooth = null
,08-16 15:26:51.293  1044  1119 D BluetoothManagerService: Message: 20
08-16 15:26:51.293  1044  1119 D BluetoothManagerService: Added callback: android.bluetooth.IBluetoothManagerCallback$Stub$Proxy@26219df8:true
,08-16 15:26:51.296  8137  8137 D BluetoothAdapterState: make
08-16 15:26:51.301  8137  8137 I LGFMServiceAdapter: [FM] LGFMServiceAdapter : create
08-16 15:26:51.301  8137  8137 I bluedroid-qcom: init
08-16 15:26:51.303  8137  8169 I BluetoothAdapterState: Entering OffState
08-16 15:26:51.303  8137  8137 I bte_conf: bte_load_conf attempt to load stack conf from /etc/bluetooth/bt_stack.conf
08-16 15:26:51.303  8137  8137 I bte_conf: bte_load_ble_conf attempt to load ble stack conf from /etc/bluetooth/ble_stack.conf
08-16 15:26:51.303  8137  8137 E bt_osi_config: config_new unable to open file '/etc/bluetooth/ble_stack.conf': No such file or directory
08-16 15:26:51.303  8137  8137 I bte_conf: bte_load_ble_conf file >/etc/bluetooth/ble_stack.conf< not found
08-16 15:26:51.303  8137  8137 D BTIF_CORE: [BTUI] lge_load_bluetooth_address
08-16 15:26:51.306  8137  8137 I bluedroid-qcom: get_profile_interface socket
08-16 15:26:51.306  8137  8137 I bluedroid-qcom: get_profile_interface map_client
,08-16 15:26:51.310  8137  8173 I GKI_LINUX: gki_task_entry task_id=1 [BTIF] starting
08-16 15:26:51.300  8172  8172 W bdaddr_loader: type=1400 audit(0.0:181): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 15:26:51.309  8172  8172 W bdaddr_loader: type=1400 audit(0.0:182): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bdaddr_loader:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 15:26:51.321  8137  8173 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-16 15:26:51.329  8172  8172 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: START
08-16 15:26:51.329  8172  8172 D lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress
08-16 15:26:51.329  8172  8172 I LGFTMITEM: [GET_FTM][id=8], offset=16384
08-16 15:26:51.331  1044  1044 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.btservice.AdapterService
08-16 15:26:51.331  1044  1119 D BluetoothManagerService: Message: 40
08-16 15:26:51.331  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 1
08-16 15:26:51.333  1044  1044 D BluetoothManagerService: Bluetooth Adapter name changed to G3
08-16 15:26:51.333  1044  1044 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 15:26:51.336  8172  8172 D lge_bdaddr_loader: [BTUI] bdaddr to set in property : 58:3F:54:73:BA:17
,08-16 15:26:51.338  8137  8153 I bluedroid-qcom: config_hci_snoop_log
08-16 15:26:51.343  1044  1119 D BluetoothManagerService: Calling onBluetoothServiceUp callbacks
08-16 15:26:51.343  1044  1119 D BluetoothManagerService: Broadcasting onBluetoothServiceUp() to 8 receivers.
08-16 15:26:51.344  8137  8173 D BluetoothAdapterProperties: Name is: G3
08-16 15:26:51.354  8137  8169 D BluetoothAdapterState: CURRENT_STATE=OFF, MESSAGE = USER_TURN_ON
08-16 15:26:51.354  8137  8169 D BluetoothAdapterProperties: Setting state to 11
08-16 15:26:51.355  8137  8169 I BluetoothAdapterState: Bluetooth adapter state changed: 10-> 11
,08-16 15:26:51.359  1044  1119 D BluetoothManagerService: Message: 60
08-16 15:26:51.359  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 10, newState=11
08-16 15:26:51.359  1044  1119 D BluetoothManagerService: Bluetooth State Change Intent: 10 -> 11
08-16 15:26:51.361  8137  8169 I LGBluetoothServiceJni: classInitNative: succeeds
08-16 15:26:51.362  8172  8172 E lge_bdaddr_loader: [BTUI] bluetooth_load_bdaddress : OK => 58:3F:54:73:BA:17
08-16 15:26:51.362  8172  8172 D lge_bdaddr_loader: [BTUI] bdaddr_loader ::: END
08-16 15:26:51.367  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
,08-16 15:26:51.370  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 15:26:51.372  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:51.374  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:51.376  7091  7091 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_TURNING_ON
08-16 15:26:51.395  8137  8137 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 15:26:51.396  8137  8137 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:51.396  8137  8137 V BluetoothPbapReceiver: ***********state = 11
,08-16 15:26:51.404  2173  2173 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 15:26:51.416  8137  8169 D BluetoothBondStateMachine: make
08-16 15:26:51.417  7091  7091 D BluetoothPermissionRequest: onReceive
,08-16 15:26:51.418  8137  8169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
,08-16 15:26:51.419  8137  8169 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - false.
08-16 15:26:51.419  8137  8169 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:51.419  8137  8169 D LGBluetoothServiceAdapter: [BTUI] check adapter is available - true : set adapter available.
08-16 15:26:51.419  8137  8169 D LGBluetoothSettingsDBObserver: [BTUI] register observer for LG device name DB
08-16 15:26:51.421  8137  8189 I BluetoothBondStateMachine: StableState(): Entering Off State
08-16 15:26:51.421  7091  7091 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 15:26:51.423  8137  8169 E BluetoothAdapterService: File transfer profiles supported!!
08-16 15:26:51.429  8137  8169 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 15:26:51.432  8137  8137 D HeadsetService: Received start request. Starting profile...
08-16 15:26:51.432  8137  8137 I LGBluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 15:26:51.432  8137  8137 D LGBluetoothHfpAdapter: Version 1.6
08-16 15:26:51.436  8137  8169 E BluetoothAdapterService: File transfer profiles supported!!
08-16 15:26:51.436  8137  8137 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 15:26:51.437  8137  8137 I BluetoothHeadsetServiceJni: classInitNative: succeeds
08-16 15:26:51.438  8137  8137 D HeadsetStateMachine: make
08-16 15:26:51.441  8137  8169 E BluetoothAdapterService: File transfer profiles supported!!
08-16 15:26:51.447  8137  8169 E BluetoothAdapterService: File transfer profiles supported!!
,08-16 15:26:51.454  8137  8169 E BluetoothAdapterService: File transfer profiles supported!!
08-16 15:26:51.459  8137  8169 E BluetoothAdapterService: File transfer profiles supported!!
08-16 15:26:51.472  8137  8137 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 15:26:51.472  8137  8137 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 15:26:51.477  8137  8137 D HeadsetStateMachine: max_hf_connections = 1
08-16 15:26:51.477  8137  8137 I bluedroid-qcom: get_profile_interface handsfree
08-16 15:26:51.477  8137  8169 V LGMDMManager: Create singleton instance
08-16 15:26:51.478  8137  8137 V ToneGenerator: ToneGenerator constructor: streamType=8, volume=1.000000
08-16 15:26:51.479   326  1369 V AudioPolicyService: registerClient() client 0xb1427160, uid 1002
08-16 15:26:51.479   326  1369 V AudioPolicyManager: getOutput() device 2, stream 8, samplingRate 0, format 0, channelMask 3, flags 0
08-16 15:26:51.479   326  1369 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 15:26:51.479   326  1369 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 15:26:51.479  8137  8169 I BluetoothAdapterState: Entering PendingCommandState State: isTurningOn()=true, isTurningOff()=false
08-16 15:26:51.479  8137  8137 V AudioSystem: getOutputSamplingRate() no output descriptor for output 2 in gOutputs
,08-16 15:26:51.480   326  1370 V AudioFlinger: registerClient() client 0xb55815f8, pid 8137
08-16 15:26:51.480   326  1364 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 15:26:51.480   326  1364 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 15:26:51.480  1589  1607 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 15:26:51.480  1589  1607 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 15:26:51.481  1044  1638 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 15:26:51.481  1839  2463 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
,08-16 15:26:51.481  1839  2463 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 15:26:51.481  1044  1638 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 15:26:51.481  3304  3329 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 15:26:51.481  3304  3329 V AudioSystem: ioConfigChanged() opening already existing output! 2
08-16 15:26:51.481   326  1365 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 15:26:51.481  8137  8137 V ToneGenerator: Create Track: 0xb4928080
08-16 15:26:51.481   326  1365 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 15:26:51.481  8137  8137 V AudioTrack: set(): streamType 8, sampleRate 0, format 0x1, channelMask 0x1, frameCount 0, flags #4, notificationFrames 0, sessionId 0, transferType 1
08-16 15:26:51.481  8137  8137 V AudioTrack: set() streamType 8, sampleRate 0, format 1, frameCount 0, flags 0004
08-16 15:26:51.481   326  1369 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 15:26:51.481   326  1369 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 0, format 0, channelMask 3, flags 0
08-16 15:26:51.481   326  1369 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 15:26:51.481  8137  8153 V AudioSystem: ioConfigChanged() event 0, ioHandle 2
08-16 15:26:51.481   326  1369 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 15:26:51.481  8137  8153 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x5 channel mask 0x3 frameCount 960 latency 50
08-16 15:26:51.481  1839  1855 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 15:26:51.481  1839  1855 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 15:26:51.481   326  1370 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 15:26:51.481  8137  8153 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 15:26:51.481  8137  8153 V AudioSystem: ioConfigChanged() new output samplingRate 48000, format 0x1 channel mask 0x3 frameCount 960 latency 80
08-16 15:26:51.482   326   326 V AudioPolicyManager: getOutputForAttr() usage=3, content=4, tag= flags=00000000
08-16 15:26:51.482   326   326 V AudioPolicyManager: getOutputForAttr() device 2, samplingRate 48000, format 1, channelMask 1, flags 4
08-16 15:26:51.482  1589  2075 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 15:26:51.482   326   326 V AudioPolicyManagerEx: AudioPolicyManagerEx: getOutputForDevice
08-16 15:26:51.482  1589  2075 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 15:26:51.482   326   326 V AudioPolicyManagerEx: getOutput() returns output 2
08-16 15:26:51.482  8137  8137 V AudioSystem: getLatency() output 2, latency 50
08-16 15:26:51.482  8137  8137 V AudioSystem: getFrameCount() output 2, frameCount 960
08-16 15:26:51.482  8137  8137 V AudioTrack: createTrack_l() output 2 afLatency 50
08-16 15:26:51.482  1044  1886 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 15:26:51.482  3304  3330 V AudioSystem: ioConfigChanged() event 0, ioHandle 4
08-16 15:26:51.482  1044  1886 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 15:26:51.482  3304  3330 V AudioSystem: ioConfigChanged() opening already existing output! 4
08-16 15:26:51.482   326  1369 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 15:26:51.482   326  1369 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 15:26:51.482   326  1369 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLEnable(), enable = 0 
08-16 15:26:51.482   326  1369 V AudioFlinger: [MABL_AudioFlinger] PlaybackThread::setMABLControl(), curLvl = 31 
08-16 15:26:51.482   326  1369 V AudioFlinger: createTrack() lSessionId: 23
08-16 15:26:51.483  8137  8137 V AudioTrack: AUDIO_OUTPUT_FLAG_FAST successful; frameCount 480
08-16 15:26:51.483   326  1369 V AudioFlinger: acquiring 23 from 8137, for 8137
08-16 15:26:51.483   326  1369 V AudioFlinge,r:  added new entry for 23
08-16 15:26:51.483  8137  8137 V ToneGenerator: ToneGenerator INIT OK, time: 372509
08-16 15:26:51.483  8137  8137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:51.484  8137  8191 D HeadsetStateMachine: Enter Disconnected: -2, size: 0
08-16 15:26:51.484  8137  8191 D HeadsetPhoneState: [BTUI] listenForPhoneState : start = false
08-16 15:26:51.484  8137  8137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:51.485  8137  8191 D LGBluetoothHfpManager: [BTUI] listenForMultiSimPhoneState : start = false
08-16 15:26:51.485  8137  8191 D HeadsetStateMachine: [BTUI] change sampling rate to 8000 when device is disconnected
08-16 15:26:51.485   326  2146 V AudioFlinger: setParameters(): io 0, keyvalue bt_samplerate=8000, calling pid 8137
08-16 15:26:51.485   326  2146 D audio_hw_primary: adev_set_parameters: enter: bt_samplerate=8000
08-16 15:26:51.485   326  2146 V voice   : voice_set_parameters: enter: bt_samplerate=8000
08-16 15:26:51.485   326  2146 V compress_voip: voice_extn_compress_voip_set_parameters: enter: bt_samplerate=8000
08-16 15:26:51.485   326  2146 V compress_voip: voice_extn_compress_voip_set_parameters: exit
08-16 15:26:51.486   326  2146 V voice   : voice_set_parameters: exit with code(0)
08-16 15:26:51.486   326  2146 V msm8974_platform_lge: LGE_platform_set_parameters: enter: bt_samplerate=8000
08-16 15:26:51.486   326  2146 V msm8974_platform: platform_set_parameters: enter: bt_samplerate=8000
08-16 15:26:51.486   326  2146 V msm8974_platform: platform_set_parameters: exit with code(0)
08-16 15:26:51.486   326  2146 V lge_audio_loopback: lge_platform_set_loopback_parameters: enter: 
08-16 15:26:51.486   326  2146 V audio_hw_primary: adev_set_parameters: exit with code(0)
08-16 15:26:51.486   326  2146 E audio_a2dp_hw: adev_set_parameters: ERROR: set param called even when stream out is null
08-16 15:26:51.486  8137  8137 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:51.486  8137  8191 V ToneGenerator: ToneGenerator destructor
08-16 15:26:51.486  8137  8191 V ToneGenerator: stopTone
08-16 15:26:51.486  8137  8191 V ToneGenerator: Delete Track: 0xb4928080
08-16 15:26:51.486  8137  8191 V AudioTrack: ~AudioTrack, releasing session id from 8137 on behalf of 8137
08-16 15:26:51.486   326   326 V AudioFlinger: releasing 23 from 8137 for 8137
08-16 15:26:51.486   326   326 V AudioFlinger:  decremented refcount to 0
08-16 15:26:51.486   326   326 V AudioFlinger: purging stale effects
08-16 15:26:51.486   326   326 V AudioPolicyService: AudioCommandThread() adding release output 2
08-16 15:26:51.487   326   326 V AudioPolicyService: inserting command: 6 at index 0, num commands 0
08-16 15:26:51.487   326  1272 V AudioPolicyService: AudioCommandThread() waking up
08-16 15:26:51.487   326  1272 V AudioPolicyService: AudioCommandThread() processing release output 2
08-16 15:26:51.487   326  1272 V AudioPolicyManager: releaseOutput() 2
08-16 15:26:51.487   326  1272 V AudioPolicyService: AudioCommandThread() going to sleep
08-16 15:26:51.487   326   326 V AudioFlinger: PlaybackThread::Track destructor
08-16 15:26:51.487   326   326 V AudioFlinger: removeClient_l() pid 8137, calling pid 326
08-16 15:26:51.489  8137  8137 D A2dpService: Received start request. Starting profile...
08-16 15:26:51.489  8137  8137 I BluetoothAvrcpServiceJni: classInitNative: succeeds
08-16 15:26:51.490  8137  8137 V Avrcp   : make
08-16 15:26:51.491  8137  8137 D Avrcp   : [BTUI] Use Native AVRCP : init jni
08-16 15:26:51.491  8137  8137 I bluedroid-qcom: get_profile_interface avrcp
08-16 15:26:51.491  1044  1942 W Process : Unable to open /proc/8192/status
08-16 15:26:51.499  8137  8137 V AudioManager: registerRemoteController: size of Media player list: 0
,08-16 15:26:51.500  8137  8137 E AudioManager: No RCC entry present to update
,08-16 15:26:51.500  8137  8137 E RemoteController: Cannot set synchronization mode on an unregistered RemoteController
08-16 15:26:51.503  8137  8137 I BluetoothAvrcpQcomServiceJni: classInitQcomNative: succeeds
,08-16 15:26:51.504  8137  8137 D LGBluetoothAvrcpQcomAdapter: [BTUI] Use QCOM AVRCP 1.5 : init jni, browsing = false
08-16 15:26:51.504  8137  8137 I BluetoothAvrcpQcomServiceJni: initQcomNative: succeeds
08-16 15:26:51.507  8137  8137 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
08-16 15:26:51.630  1044  1949 V SIM_STK : Menu title from STK is T-Mobile
08-16 15:26:51.630  1044  1949 V SIM_STK : Menu title from STK is T-Mobile
,08-16 15:26:51.735  1044  1886 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
,08-16 15:26:51.758  8137  8137 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
,08-16 15:26:51.768  8137  8137 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 15:26:51.769  8137  8137 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
,08-16 15:26:51.769  8137  8137 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 15:26:51.769  8137  8137 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 15:26:51.769  8137  8137 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 15:26:51.770  8137  8137 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 15:26:51.770  8137  8137 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 15:26:51.770  8137  8137 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 15:26:51.770  8137  8137 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 15:26:51.770  8137  8137 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
,08-16 15:26:51.770  8137  8137 I BluetoothA2dpServiceJni: classInitNative
08-16 15:26:51.770  8137  8137 I BluetoothA2dpServiceJni: classInitNative: succeeds
08-16 15:26:51.771  8137  8137 D A2dpStateMachine: make
08-16 15:26:51.772  8137  8137 I bluedroid-qcom: get_profile_interface a2dp
08-16 15:26:51.773  8137  8201 I GKI_LINUX: gki_task_entry task_id=2 [A2DP-MEDIA] starting
08-16 15:26:51.775  8137  8137 I LGBluetoothA2dpServiceJni: classInitNative: succeeds
08-16 15:26:51.775  8137  8137 I LGBluetoothA2dpAdapter: [BTUI] getInstance : create [LGBluetoothA2dpAdapter]
08-16 15:26:51.777  8137  8137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:51.777  8137  8200 D A2dpStateMachine: Enter Disconnected: -2
08-16 15:26:51.778  8137  8137 I BluetoothHidServiceJni: classInitNative: succeeds
08-16 15:26:51.780  8137  8137 D HidService: Received start request. Starting profile...
08-16 15:26:51.780  8137  8137 I bluedroid-qcom: get_profile_interface hidhost
08-16 15:26:51.780  8137  8137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:51.781  8137  8137 I BluetoothHealthServiceJni: classInitNative: succeeds
08-16 15:26:51.782  8137  8137 D HealthService: Received start request. Starting profile...
08-16 15:26:51.786  8137  8137 I bluedroid-qcom: get_profile_interface health
,08-16 15:26:51.786  8137  8137 I LGBluetoothHealthServiceJni: classInitNative: succeeds
08-16 15:26:51.786  8137  8137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:51.787  8137  8137 I BluetoothPanServiceJni: classInitNative(L105): succeeds
08-16 15:26:51.789  8137  8137 D PanService: Received start request. Starting profile...
08-16 15:26:51.789  8137  8137 D BluetoothPanServiceJni: initializeNative(L110): pan
08-16 15:26:51.789  8137  8137 I bluedroid-qcom: get_profile_interface pan
08-16 15:26:51.795  8137  8137 I LGBluetoothPanAdapter: [BTUI] getInstance : create [LGBluetoothPanAdapter]
08-16 15:26:51.795  8137  8137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:51.799  8137  8137 I BtGatt.JNI: classInitNative(L901): classInitNative: Success!
,08-16 15:26:51.805  8137  8137 D BtGatt.DebugUtils: handleDebugAction() action=null
08-16 15:26:51.805  8137  8137 D BtGatt.GattService: Received start request. Starting profile...
08-16 15:26:51.805  8137  8137 D BtGatt.GattService: start()
08-16 15:26:51.805  8137  8137 I bluedroid-qcom: get_profile_interface gatt
08-16 15:26:51.806  8137  8137 D BtGatt.AdvertiseManager: advertise manager created
08-16 15:26:51.810  8137  8137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:51.813  8137  8137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:51.813  8137  8137 I LGBluetoothMapAdapter: [BTUI] getInstance : create [LGBluetoothMapAdapter]
,08-16 15:26:51.814  8137  8137 V BluetoothMapService: BluetoothMapBinder()
08-16 15:26:51.815  8137  8137 D BluetoothMapService: Received start request. Starting profile...
08-16 15:26:51.815  8137  8137 D BluetoothMapService: start()
08-16 15:26:51.818  8137  8137 D BluetoothMapEmailSettingsLoader: Found 0 applications
08-16 15:26:51.818  8137  8137 D BluetoothMapEmailAppObserver: createReceiver()
08-16 15:26:51.819  8137  8137 D BluetoothMapEmailAppObserver: initObservers()
08-16 15:26:51.819  8137  8137 D BluetoothMapEmailAppObserver: getEnabledAccountItems()
08-16 15:26:51.827  8137  8137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
,08-16 15:26:51.828  8137  8137 D HeadsetStateMachine: Proxy object connected
08-16 15:26:51.828  8137  8137 D LGBluetoothHfpAdapter: [BTUI] queryPhoneState
08-16 15:26:51.828  8137  8137 D LGBluetoothHfpAdapter: Try to query the phonestate on bind
08-16 15:26:51.832  8137  8137 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 15:26:51.833  8137  8191 D HeadsetStateMachine: Disconnected process message: 10, size: 0
08-16 15:26:51.833  8137  8191 D HeadsetPhoneState: sendDeviceStateChanged. mService=0 mSignal=0 mRoam=0 mBatteryCharge=5
08-16 15:26:51.834  8137  8191 D HeadsetStateMachine: Disconnected process message: 11, size: 0
08-16 15:26:51.834  8137  8137 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 15:26:51.834  8137  8137 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 15:26:51.834  8137  8137 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 15:26:51.834  8137  8137 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:51.834  8137  8137 V BluetoothSapReceiver:  Bluetooth Adapter state = 11
08-16 15:26:51.840  8137  8137 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
,08-16 15:26:51.845  8137  8137 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 15:26:51.848  8137  8137 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 15:26:51.849  8137  8137 V PanService: [BTUI] SIM Extra State :ABSENT
08-16 15:26:51.852  8137  8137 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.gatt.GattService
08-16 15:26:51.854  8137  8137 D BluetoothAdapterService: Profile still not running:com.android.bluetooth.map.BluetoothMapService
,08-16 15:26:51.855  8137  8137 V BluetoothMapService: Handler(): got msg=1
,08-16 15:26:51.856  8137  8169 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = STARTED, isTurningOn=true, isTurningOff=false
08-16 15:26:51.856  8137  8169 I bluedroid-qcom: enable
08-16 15:26:51.856  8137  8169 I bt_hci_bdroid: init
08-16 15:26:51.858  8137  8169 I bt_vendor: bt-vendor : init
08-16 15:26:51.858  8137  8169 I bt_vendor: bt-vendor : get_bt_soc_type
08-16 15:26:51.858  8137  8169 E bt_vendor: get_bt_soc_type: Failed to get soc type
08-16 15:26:51.858  8137  8169 I bt_vendor: init: Local BD Address : 17:ba:73:54:3f:58
08-16 15:26:51.858  8137  8169 D bt_userial_mct: userial_init
08-16 15:26:51.858  8137  8211 I GKI_LINUX: gki_task_entry task_id=0 [BTU] starting
08-16 15:26:51.858  8137  8211 I bt-btu  : btu_task pending for preload complete event
08-16 15:26:51.858  8137  8169 D bt_hci_bdroid: set_power 1
08-16 15:26:51.858  8137  8169 I bt_vendor: bt-vendor : BT_VND_OP_POWER_CTRL: On
08-16 15:26:51.858  8137  8169 I bt_vendor: Starting hciattach daemon
08-16 15:26:51.858  8137  8169 I bt_vendor: try to set true
08-16 15:26:51.849  8214  8214 W sh      : type=1400 audit(0.0:183): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 15:26:51.849  8214  8214 W sh      : type=1400 audit(0.0:184): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 15:26:51.882  8215  8215 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: init.qcom.bt.sh config =  
,08-16 15:26:51.953  8221  8221 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Transport : smd 
,08-16 15:26:51.966  8222  8222 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
08-16 15:26:51.992  8224  8224 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: Ignored. Default(1) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 15:26:52.004  8225  8225 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Power Class: To override, Before turning BT ON; setprop qcom.bt.dev_power_class <1 or 2 or 3> 
08-16 15:26:52.017  8226  8226 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: Ignored. Default(2) used (1-CLASS1/2-CLASS2/3-CUSTOM) 
,08-16 15:26:52.042  8227  8227 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: LE Power Class: To override, Before turning BT ON; setprop qcom.bt.le_dev_pwr_class <1 or 2 or 3> 
,08-16 15:26:52.064  8229  8229 I libmdmdetect: ESOC framework not supported
,08-16 15:26:52.065  8229  8229 E Diag_Lib:  Diag_LSM_Init: Failed to open handle to diag driver, error = 13
,08-16 15:26:52.073  8229  8229 D bthci_qcomm_linux: [BTUI] bt_hci_qcomm_pfal_get_bdaddress: Get BDADDR from bluedroid prop (58:3F:54:73:BA:17)
08-16 15:26:52.073  8229  8229 D bthci_qcomm_common: [BTUI] bt_hci_qcomm_init:
,08-16 15:26:52.073  8229  8229 D bthci_qcomm_common: [BTUI]     BDADDR: 58:3F:54:73:BA:17
08-16 15:26:52.073  8229  8229 D bthci_qcomm_common: [BTUI]     BR/EDR: Class 1
08-16 15:26:52.073  8229  8229 D bthci_qcomm_common: [BTUI]     LE: Class 2
08-16 15:26:52.073  8229  8229 D bthci_qcomm_common: [BTUI]     Ref Clock: 32M
08-16 15:26:52.074  8229  8229 D btqsocnvmtags: [BTUI] init_riva_entries: set NORMAL power settings
08-16 15:26:52.114  8229  8230 E QC-QMI  : qmi_client [8229] 15: failed to locate client data
08-16 15:26:52.115   481   481 E QC-QMI  : qmuxd: RX on fd=32 returned error=0 errno[2:No such file or directory]
08-16 15:26:52.115   481   481 E QC-QMI  : QMUX qmux_client_id=15 not found in qmux client list, unable to remove
,08-16 15:26:52.156  8231  8231 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: Bluetooth QSoC firmware download succeeded, /dev/ttyHS0 qualcomm 3000000 58:3f:54:73:ba:17 
,08-16 15:26:52.181  8232  8232 I qcom-bluetooth: /system/etc/init.qcom.bt.sh: ** Bluedroid stack ** 
,08-16 15:26:52.210  8137  8169 I bt_vendor: bluetooth satus is on
,08-16 15:26:52.210  8137  8169 D bt_hci_bdroid: preload
08-16 15:26:52.211  8137  8213 D bt_userial_mct: userial_open(port:0)
08-16 15:26:52.211  8137  8213 I bt_vendor: bt-vendor : BT_VND_OP_USERIAL_OPEN
,08-16 15:26:52.214  8137  8213 I bt_vendor: Done intiailizing UART
08-16 15:26:52.215  8137  8213 I bt_vendor: Done intiailizing UART
08-16 15:26:52.215  8137  8213 I bt_userial_mct: CMD=66, EVT=66, ACL_Out=67, ACL_In=67
08-16 15:26:52.215  8137  8213 I bt_vendor: Bluetooth Firmware and transport layer are initialized
08-16 15:26:52.215  8137  8211 I bt-btu  : btu_task received preload complete event
08-16 15:26:52.216  8137  8234 D bt_userial_mct: Entering userial_read_thread()
08-16 15:26:52.217  8137  8211 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0001
08-16 15:26:52.217  8137  8211 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001f
08-16 15:26:52.222  8137  8211 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0003
08-16 15:26:52.230  8137  8211 I         : BTE_InitTraceLevels -- TRC_HCI
08-16 15:26:52.230  8137  8211 I         : BTE_InitTraceLevels -- TRC_L2CAP
08-16 15:26:52.230  8137  8211 I         : BTE_InitTraceLevels -- TRC_RFCOMM
08-16 15:26:52.230  8137  8211 I         : BTE_InitTraceLevels -- TRC_AVDT
08-16 15:26:52.230  8137  8211 I         : BTE_InitTraceLevels -- TRC_AVRC
08-16 15:26:52.230  8137  8211 I         : BTE_InitTraceLevels -- TRC_A2D
08-16 15:26:52.230  8137  8211 I         : BTE_InitTraceLevels -- TRC_BNEP
08-16 15:26:52.230  8137  8211 I         : BTE_InitTraceLevels -- TRC_BTM
08-16 15:26:52.230  8137  8211 I         : BTE_InitTraceLevels -- TRC_HID_HOST
08-16 15:26:52.230  8137  8211 I         : BTE_InitTraceLevels -- TRC_GAP
08-16 15:26:52.230  8137  8211 I         : BTE_InitTraceLevels -- TRC_PAN
08-16 15:26:52.230  8137  8211 I         : BTE_InitTraceLevels -- TRC_SDP
08-16 15:26:52.230  8137  8211 I         : BTE_InitTraceLevels -- TRC_GATT
08-16 15:26:52.230  8137  8211 I         : BTE_InitTraceLevels -- TRC_SMP
08-16 15:26:52.230  8137  8211 I         : BTE_InitTraceLevels -- TRC_BTAPP
08-16 15:26:52.230  8137  8211 I         : BTE_InitTraceLevels -- TRC_BTIF
,08-16 15:26:52.346  8137  8211 W bt-btm  : btm_decode_ext_features_page Secure conn Controller support Enabled
,08-16 15:26:52.346  8137  8211 E bt-btm  : BTM_SecRegister:p_cb_info->p_le_callback == 0xa01b5061 
08-16 15:26:52.347  8137  8211 E bt-btm  : BTM_SecRegister: btm_cb.api.p_le_callback = 0xa01b5061 
,08-16 15:26:52.400  8137  8173 E bt-btif : Calling BTA_HhEnable
,08-16 15:26:52.400  8137  8173 E bt-btif : btif_storage_get_adapter_property service_mask:0x2140040
,08-16 15:26:52.401  8137  8173 D BluetoothAdapterProperties: Address is:58:3F:54:73:BA:17
,08-16 15:26:52.413  1044  1044 D BluetoothManagerService: Bluetooth Adapter name changed to G3
,08-16 15:26:52.415  8137  8173 D BluetoothAdapterProperties: Name is: G3
08-16 15:26:52.419  8137  8173 D BluetoothAdapterProperties: Scan Mode:20
08-16 15:26:52.419  8137  8173 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 15:26:52.420  8137  8173 D bt_hci_bdroid: postload
,08-16 15:26:52.429  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:52.430  8137  8173 D bte_conf: Device ID record 1 : primary
08-16 15:26:52.430  8137  8173 D bte_conf:   vendorId            = 00c4
08-16 15:26:52.430  8137  8173 D bte_conf:   vendorIdSource      = 0001
08-16 15:26:52.430  8137  8173 D bte_conf:   product             = 13a1
08-16 15:26:52.430  8137  8173 D bte_conf:   version             = 1000
08-16 15:26:52.430  8137  8173 D bte_conf:   clientExecutableURL = 
08-16 15:26:52.430  8137  8173 D bte_conf:   serviceDescription  = 
08-16 15:26:52.430  8137  8173 D bte_conf:   documentationURL    = 
08-16 15:26:52.430  8137  8173 D bte_conf: bte_load_did_conf no section named DID2.
08-16 15:26:52.434  8137  8169 D BluetoothAdapterState: CURRENT_STATE=PENDING, MESSAGE = ENABLE_READY, isTurningOn=true, isTurningOff=false
08-16 15:26:52.434  8137  8169 D BluetoothAdapterProperties: ScanMode =  20
08-16 15:26:52.434  8137  8169 D BluetoothAdapterProperties: State =  11
08-16 15:26:52.435  8137  8169 D BluetoothAdapterProperties: mDiscoverableTimeout = 120
08-16 15:26:52.435  8137  8169 V LGBluetoothServiceAdapter: [BTUI] state:11, scanmode:20, timeout:120
08-16 15:26:52.435  8137  8169 D BluetoothAdapterProperties: Setting state to 12
08-16 15:26:52.435  8137  8169 I BluetoothAdapterState: Bluetooth adapter state changed: 11-> 12
08-16 15:26:52.438  8137  8173 D btif_config_util: btif_config_save_file(L188): in file name:/data/misc/bluedroid/bt_config.new
,08-16 15:26:52.429  8239  8239 W sh      : type=1400 audit(0.0:185): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 15:26:52.429  8239  8239 W sh      : type=1400 audit(0.0:186): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:init_shell:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 15:26:52.444  1044  1119 D BluetoothManagerService: Message: 60
08-16 15:26:52.444  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_STATE_CHANGE: prevState = 11, newState=12
08-16 15:26:52.445  1044  1119 D BluetoothManagerService: Broadcasting onBluetoothStateChange(true) to 11 receivers.
08-16 15:26:52.445  1044  1119 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 15:26:52.446  8137  8169 I BluetoothAdapterState: Entering On State
08-16 15:26:52.466  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:26:52.466  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:52.466  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:52.466  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:26:52.466  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:26:52.466  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:26:52.466  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:26:52.466  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 15:26:52.477  6974  6974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:26:52.477  1044  1044 D BluetoothManagerService: Stored Bluetooth name: G3
08-16 15:26:52.479  8137  8173 D BluetoothAdapterProperties: Discoverable Timeout:120
08-16 15:26:52.479  8137  8173 D LGBluetoothDeviceModeControllManager: adapterPropertyChangedCallback on  LGAdapter : do nothing - 9
,08-16 15:26:52.488  8137  8213 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 15:26:52.488  8137  8213 D bt_hci_bdroid: Used up Tx Cmd credits
08-16 15:26:52.496  1044  1044 D BluetoothHeadset: Proxy object connected
,08-16 15:26:52.506  1839  1854 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 15:26:52.507  8137  8169 D LGBluetoothServiceAdapter: [BTUI] OnState
08-16 15:26:52.507  8137  8169 D LGBluetoothServiceAdapter: [BTUI]         global_name: G3
08-16 15:26:52.507  8137  8169 D LGBluetoothServiceAdapter: [BTUI]         local_name: G3
08-16 15:26:52.508  8137  8169 D BluetoothAdapterService: [BTUI] autoConnect() : not allowed
08-16 15:26:52.508  8137  8169 D LGBluetoothDeviceModeControllManager: [BTUI] checkDeviceModeAndSet, sinkMode : false
,08-16 15:26:52.517  1839  1839 D BluetoothHeadset: Proxy object connected
08-16 15:26:52.517  1839  1855 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 15:26:52.521  8137  8234 E bt_mct  : hci lib postload completed
,08-16 15:26:52.531  8137  8211 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0019
08-16 15:26:52.531  8137  8211 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0017
08-16 15:26:52.531  8137  8211 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x001b
08-16 15:26:52.532  8137  8211 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0011
08-16 15:26:52.532  8137  8211 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x0013
08-16 15:26:52.532  8137  8211 W bt-l2cap: L2CAP - L2CA_Register() called for PSM: 0x000f
08-16 15:26:52.532  8137  8173 D BluetoothPanServiceJni: control_state_callback(L61): state:0, local_role:3, ifname:bt-pan
08-16 15:26:52.548  1839  1839 D BluetoothHeadset: Proxy object connected
,08-16 15:26:52.570  7091  7119 D BluetoothMap: onBluetoothStateChange: up=true
,08-16 15:26:52.571  8244  8244 I qcom-bt-wlan-coex: /system/etc/init.qcom.coex.sh: btwlancoex/abtfilt not available 
08-16 15:26:52.577  8137  8211 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 15:26:52.577  8137  8211 W bt-smp  : Plain text(LSB ~ MSB) = d1 4b 73 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 15:26:52.577  8137  8211 W bt-smp  : Encrypted text(LSB ~ MSB) = f1 d7 89 68 8c f7 29 97 41 e3 65 3f f3 ed b9 23 
,08-16 15:26:52.577  8137  8211 W bt-btm  : Stopping oneshot timer
08-16 15:26:52.581  7091  7091 D BluetoothMap: Proxy object connected
08-16 15:26:52.581  7091  7091 D MapProfile: Bluetooth service connected
08-16 15:26:52.581  7091  7091 D BluetoothMap: getConnectedDevices()
08-16 15:26:52.581  7091  7119 D BluetoothPbap: onBluetoothStateChange: up=true
08-16 15:26:52.582  8137  8152 V BluetoothMapService: getConnectedDevices()
,08-16 15:26:52.586  7091  7118 D BluetoothPan: onBluetoothStateChange on: true
08-16 15:26:52.586  7091  7118 D BluetoothPan: onBluetoothStateChange call bindService
08-16 15:26:52.590  7091  7091 D BluetoothPan: BluetoothPAN Proxy object connected
08-16 15:26:52.590  7091  7119 D BluetoothInputDevice: onBluetoothStateChange: up=true
08-16 15:26:52.590  7091  7091 D PanProfile: Bluetooth service connected
08-16 15:26:52.594  1044  1119 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 15:26:52.595  1839  2463 D BluetoothHeadset: onBluetoothStateChange: up=true
08-16 15:26:52.595  8137  8211 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 15:26:52.595  8137  8211 W bt-smp  : Plain text(LSB ~ MSB) = 05 41 70 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 15:26:52.595  8137  8211 W bt-smp  : Encrypted text(LSB ~ MSB) = 98 f7 f8 28 9b e8 72 e9 3a 7f 97 5e 6f f2 a4 00 
08-16 15:26:52.595  8137  8211 W bt-btm  : Stopping oneshot timer
08-16 15:26:52.596  7091  7091 D BluetoothInputDevice: Proxy object connected
08-16 15:26:52.596  7091  7091 D HidProfile: Bluetooth service connected
,08-16 15:26:52.598  1044  1044 D BluetoothA2dp: Proxy object connected
08-16 15:26:52.600  1839  1839 D BluetoothHeadset: Proxy object connected
08-16 15:26:52.600  7091  7118 D BluetoothA2dp: onBluetoothStateChange: up=true
08-16 15:26:52.602  7091  7190 D BluetoothHeadset: onBluetoothStateChange: up=true
,08-16 15:26:52.603  7091  7091 D BluetoothA2dp: Proxy object connected
08-16 15:26:52.603  7091  7091 D A2dpProfile: Bluetooth service connected
08-16 15:26:52.605  1044  1119 E BluetoothManagerService: Fail to bind to: Intent { act=android.bluetooth.IQBluetooth }
08-16 15:26:52.605  1044  1119 D BluetoothManagerService: Bluetooth State Change Intent: 11 -> 12
08-16 15:26:52.608  8137  8211 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 15:26:52.608  8137  8211 W bt-smp  : Plain text(LSB ~ MSB) = 0d f3 4a 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 15:26:52.608  8137  8211 W bt-smp  : Encrypted text(LSB ~ MSB) = 5a 4c a3 48 5b 67 17 6d b5 6d 3d 4f 80 84 5a f3 
08-16 15:26:52.608  8137  8211 W bt-btm  : Stopping oneshot timer
,08-16 15:26:52.611  1589  1589 I [SystemUI]BluetoothHandler: Receive : BluetoothAdapter.ACTION_STATE_CHANGED
08-16 15:26:52.614  1927  1927 D LGBluetoothAPIService: [BTUI] onReceive action : android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:52.614  1927  2069 D LGBluetoothAPIService: Message: 1
08-16 15:26:52.614  1927  2069 D LGBluetoothAPIService: MESSAGE_BOOT_COMPLETED
08-16 15:26:52.618  1044  1044 D BluetoothManagerService: BluetoothServiceConnection: com.android.bluetooth.gatt.GattService
08-16 15:26:52.618  1044  1119 D BluetoothManagerService: Message: 40
08-16 15:26:52.618  1044  1119 D BluetoothManagerService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED: 2
08-16 15:26:52.620  7091  7091 D BluetoothHeadset: Proxy object connected
08-16 15:26:52.620  7091  7091 D HeadsetProfile: Bluetooth service connected
,08-16 15:26:52.620  1927  2069 I LGBluetoothAPIService: [BTUI] LGBluetoothAPIService Binding Success
08-16 15:26:52.622  8137  8137 I BluetoothMapService: onReceive: android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:52.622  8137  8137 D BluetoothMapService: STATE_ON
08-16 15:26:52.622  8137  8211 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 15:26:52.622  8137  8211 W bt-smp  : Plain text(LSB ~ MSB) = a9 43 4f 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 15:26:52.622  8137  8211 W bt-smp  : Encrypted text(LSB ~ MSB) = 2e a8 df 69 e2 f1 96 bf 57 72 d1 f0 56 9c ea ed 
08-16 15:26:52.622  8137  8211 W bt-btm  : Stopping oneshot timer
08-16 15:26:52.625  8137  8137 D LGBluetoothAPIServer: [BTUI] onCreate()
08-16 15:26:52.625  8137  8137 D LGBluetoothAPIServer: [BTUI] onBind()
08-16 15:26:52.626  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:26:52.626  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:52.626  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:26:52.626  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:26:52.626  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:26:52.626  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:26:52.626  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:26:52.626  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:26:52.629  6974  6974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:26:52.630  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:52.630  1927  1927 D LGBluetoothAPIService: [BTUI] LGBluetoothAPIServiceConnection: connected to LGBluetoothAPIAdapter
08-16 15:26:52.631  1927  2069 D LGBluetoothAPIService: Message: 100
08-16 15:26:52.631  1927  2069 D LGBluetoothAPIService: MESSAGE_BLUETOOTH_SERVICE_CONNECTED
,08-16 15:26:52.632  7091  7091 E LGBluetoothEventManager: [BTUI] onReceive()... android.bluetooth.adapter.action.STATE_CHANGED==> STATE_ON
08-16 15:26:52.633  8137  8211 W bt-smp  : Key(LSB ~ MSB) = 43 9b 41 48 e8 28 7c f1 e4 65 8c 1a ba c0 47 f5 
08-16 15:26:52.633  8137  8211 W bt-smp  : Plain text(LSB ~ MSB) = 27 bb 75 00 00 00 00 00 00 00 00 00 00 00 00 00 
08-16 15:26:52.633  8137  8211 W bt-smp  : Encrypted text(LSB ~ MSB) = dc 16 26 9f 89 75 c7 14 d0 71 3c 0e 3d 76 89 26 
08-16 15:26:52.633  8137  8211 W bt-btm  : Stopping oneshot timer
08-16 15:26:52.634  7091  7091 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 android.content.ContextWrapper.startService:515 com.android.settings.bluetooth.DockEventReceiver.beginStartingService:138 com.android.settings.bluetooth.DockEventReceiver.onReceive:119 
08-16 15:26:52.642  7091  7091 D DockEventReceiver: finishStartingService: stopping service
08-16 15:26:52.643  8137  8137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:52.643  8137  8137 V BluetoothPbapService: Pbap Service onCreate
,08-16 15:26:52.643  8137  8137 V BluetoothPbapService: Starting PBAP service
08-16 15:26:52.645  8137  8137 D LGBluetoothPbapAdapter: [BTUI] getInstance : create
08-16 15:26:52.645  8137  8137 V BluetoothMapService: Handler(): got msg=1
08-16 15:26:52.647  8137  8137 D BluetoothMapMasInstance: Map Service startRfcommSocketListener
08-16 15:26:52.648  8137  8137 V BluetoothPbapService: Pbap Service onBind
08-16 15:26:52.649  8137  8137 V BluetoothPbapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:52.649  7091  7091 D BluetoothPbap: Proxy object connected
08-16 15:26:52.649  7091  7091 D PbapServerProfile: Bluetooth service connected
08-16 15:26:52.649  8137  8137 V BluetoothPbapService: state: 12
08-16 15:26:52.649  8137  8137 V BluetoothPbapReceiver: PbapReceiver onReceive 
08-16 15:26:52.649  8137  8264 D BluetoothMapMasInstance: MAS initSocket()
08-16 15:26:52.649  8137  8137 V BluetoothPbapReceiver: ***********action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:52.649  8137  8137 V BluetoothPbapReceiver: ***********state = 12
08-16 15:26:52.650  8137  8264 D BluetoothMapMasInstance:   masId = 00
08-16 15:26:52.650  8137  8264 D BluetoothMapMasInstance:   msgTypes = 0e
08-16 15:26:52.650  8137  8264 D BluetoothMapMasInstance:   masName = SMS/MMS
08-16 15:26:52.650  8137  8264 D BluetoothMapMasInstance:   SDP string = 000eSMS/MMS
08-16 15:26:52.651  8137  8137 V BluetoothPbapService: Handler(): got msg=1
08-16 15:26:52.651  8137  8137 V BluetoothPbapService: Pbap Service startRfcommSocketListener
08-16 15:26:52.653  8137  8265 V BluetoothPbapService: Pbap Service initSocket
08-16 15:26:52.653  1044  1562 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:26:52.654  2173  2173 D AuthorizationBluetoothService: Received Bluetooth event: Intent { act=android.bluetooth.adapter.action.STATE_CHANGED flg=0x14000010 cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$BluetoothStateChangeReceiver (has extras) }.
08-16 15:26:52.655  1044  1773 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:26:52.655  2173  2173 D c       : Getting all permits...
08-16 15:26:52.655  2173  2173 D a       : Opening database...
,08-16 15:26:52.656  8137  8264 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 15:26:52.656  8137  8265 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 15:26:52.657  8137  8265 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=73 mFd=0
08-16 15:26:52.658  8137  8265 V BluetoothPbapService: Succeed to create listening socket 
08-16 15:26:52.658  8137  8265 V BluetoothPbapService: Accepting socket connection...
08-16 15:26:52.659  8137  8173 D BluetoothAdapterProperties: Scan Mode:21
08-16 15:26:52.659  8137  8173 D LGBluetoothDeviceModeControllManager: getDeviceMode  deviceMode 0
08-16 15:26:52.659  8137  8264 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=75 mFd=73
08-16 15:26:52.660  8137  8264 V BluetoothMapMasInstance: Succeed to create listening socket 
08-16 15:26:52.660  8137  8264 D BluetoothMapMasInstance: Accepting socket connection...
08-16 15:26:52.660  2173  2173 D a       : Opening database auth.proximity.permit_store...
08-16 15:26:52.661  2173  2173 D a       : Closing database...
08-16 15:26:52.661  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:52.663  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:26:52.669  7091  7091 D BluetoothPermissionRequest: onReceive
,08-16 15:26:52.671  7091  7091 D LGBluetoothUtils: [BTUI] FileNotFound: readProperty
08-16 15:26:52.673  7091  7091 D LGBluetoothResetSettingReceiver: return without doing reset settings.
08-16 15:26:52.676  8137  8137 V BluetoothOppReceiver: Received BLUETOOTH_STATE_CHANGED_ACTION, BLUETOOTH_STATE_ON
08-16 15:26:52.677  8137  8137 I LGBluetoothOppAdapter: [BTUI] startOppService()
08-16 15:26:52.682  8137  8137 V BluetoothOppManager: restoreApplicationData! falsefalsenullnull
,08-16 15:26:52.699  8137  8137 D LGBluetoothFeatureConfig: isPrivacyLogsEnabled : true
08-16 15:26:52.699  8137  8137 V BtOppService: onCreate
,08-16 15:26:52.704  8137  8137 V BluetoothOppNotification: send message
08-16 15:26:52.707  8137  8137 V BtOppService: Starting RfcommListener
08-16 15:26:52.715  8137  8137 D BluetoothOppPreference: Dumping Names:  
08-16 15:26:52.715  8137  8137 D BluetoothOppPreference: {}
08-16 15:26:52.715  8137  8137 D BluetoothOppPreference: Dumping Channels:  
08-16 15:26:52.715  8137  8137 D BluetoothOppPreference: {}
,08-16 15:26:52.719  8137  8137 V BtOppService: onStartCommand
08-16 15:26:52.721  8137  8274 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 15:26:52.723  8137  8271 V BtOppService: Deleted complete outbound shares, number =  0
08-16 15:26:52.724  8137  8271 V BtOppService: Deleted complete inbound failed shares, number = 0
08-16 15:26:52.725  8137  8271 V BluetoothOppProvider: starting query, database is not null; projection[0] is _id; selection is direction=1 AND status=200 AND visibility=1; selectionArgs is null; sort is _id.
08-16 15:26:52.725  8137  8274 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 15:26:52.725  8137  8137 V BluetoothFtpReceiver: BluetoothFtpReceiver onReceive :android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:52.726  8137  8137 V BluetoothFtpReceiver: BluetoothFtpReceiver Start Service
08-16 15:26:52.726  8137  8271 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@241b2c31 on behalf of 
08-16 15:26:52.727  8137  8274 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@5eeef16 on behalf of 
08-16 15:26:52.728  8137  8274 V BluetoothOppNotification: update too frequent, put in queue
,08-16 15:26:52.731  8137  8137 V BluetoothOppNotification: new notify threadi!
08-16 15:26:52.732  8137  8274 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 15:26:52.732  8137  8137 V BluetoothOppNotification: send delay message
08-16 15:26:52.732  8137  8274 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 15:26:52.733  8137  8137 V BtOppService: start RfcommListener
08-16 15:26:52.735  8137  8274 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1498b097 on behalf of 
08-16 15:26:52.735  8137  8275 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 15:26:52.735  8137  8137 V BtOppService: RfcommListener started
08-16 15:26:52.736  8137  8137 V BtOppService: ContentObserver received notification
08-16 15:26:52.736  8137  8137 V BtOppService: ContentObserver received notification
08-16 15:26:52.738  8137  8276 V BtOppRfcommListener: Starting RFCOMM listener....
08-16 15:26:52.738  8137  8275 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@369b6284 on behalf of 
08-16 15:26:52.738  8137  8274 V BtOppService: pendingUpdate is true keepUpdateThread is false sListenStarted is true
08-16 15:26:52.739  8137  8274 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is _id.
08-16 15:26:52.739  1044  2009 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:26:52.739  8137  8275 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 15:26:52.741  8137  8274 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@e455a6d on behalf of 
,08-16 15:26:52.741  8137  8276 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 15:26:52.741  8137  8274 V BluetoothOppNotification: update too frequent, put in queue
08-16 15:26:52.742  8137  8274 V BtOppService: pendingUpdate is false keepUpdateThread is false sListenStarted is true
08-16 15:26:52.743  8137  8275 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 15:26:52.745  8137  8276 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=78 mFd=75
08-16 15:26:52.745  8137  8276 V BtOppRfcommListener: Started RFCOMM listener....
08-16 15:26:52.745  8137  8276 I BtOppRfcommListener: Accept thread started.
08-16 15:26:52.745  8137  8275 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@1262e6a2 on behalf of 
08-16 15:26:52.745  8137  8276 V BtOppRfcommListener: Accepting connection...
08-16 15:26:52.746  8137  8275 V BluetoothOppNotification: outbound: succ-0  fail-0
08-16 15:26:52.749  8137  8137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:52.749  8137  8137 V BluetoothFtpService: Ftp Service onCreate
08-16 15:26:52.749  8137  8137 I BluetoothFtpService: Ftp Service onCreate
08-16 15:26:52.749  8137  8137 V BluetoothFtpService: Ftp Service onStartCommand
08-16 15:26:52.750  8137  8137 V BluetoothFtpService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:52.750  8137  8137 V BluetoothFtpService: Starting Listening on sockets
08-16 15:26:52.750  8137  8137 V BluetoothSapReceiver: [BTUI] checkServiceStart
08-16 15:26:52.750  8137  8137 V BluetoothSapReceiver: [BTUI] region:EU country:EU
08-16 15:26:52.750  8137  8137 V BluetoothSapReceiver: SapReceiver onReceive 
08-16 15:26:52.750  8137  8137 V BluetoothSapReceiver: action = android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:52.750  8137  8137 V BluetoothSapReceiver:  Bluetooth Adapter state = 12
08-16 15:26:52.750  8137  8137 V BluetoothSapReceiver: Calling SAP service start service with action = null
08-16 15:26:52.753  8137  8137 V BluetoothFtpService: Handler(): got msg=1
08-16 15:26:52.753  8137  8275 V BluetoothOppNotification: outbound notification was removed.
08-16 15:26:52.753  8137  8275 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
08-16 15:26:52.755  8137  8137 V BluetoothFtpService: Ftp Service startRfcommSocketListener
08-16 15:26:52.755  8137  8137 V BluetoothFtpService: Ftp Service initSocket
08-16 15:26:52.755  8137  8275 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@13ae22f0 on behalf of 
,08-16 15:26:52.758  8137  8275 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 15:26:52.760  1044  1059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:26:52.761  8137  8137 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 15:26:52.762  8137  8275 V BluetoothOppNotification: inbound notification was removed.
08-16 15:26:52.763  8137  8275 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.
08-16 15:26:52.764  8137  8137 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=80 mFd=78
08-16 15:26:52.764  8137  8137 V BluetoothFtpService: Succeed to create listening socket on channel 20
08-16 15:26:52.765  8137  8275 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@256a3069 on behalf of 
08-16 15:26:52.766  8137  8277 V BluetoothFtpService:RfcommSocketAcceptThread: Run Accept thread
,08-16 15:26:52.777  8137  8137 D BluetoothAdapterService: getAdapterService() - returning com.android.bluetooth.btservice.AdapterService@2df2155c
08-16 15:26:52.777  8137  8137 V BluetoothSapService: Sap Service onCreate
08-16 15:26:52.779  8137  8137 V BluetoothSapService: action: android.bluetooth.adapter.action.STATE_CHANGED
08-16 15:26:52.779  8137  8137 V BluetoothSapService: state: 12
08-16 15:26:52.779  8137  8137 V BluetoothSapService: Starting SAP server process
,08-16 15:26:52.781  8137  8137 V BluetoothSapService: SAP Service startRfcommListenerThread
08-16 15:26:52.769  8278  8278 W sapd    : type=1400 audit(0.0:187): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 15:26:52.769  8278  8278 W sapd    : type=1400 audit(0.0:188): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:bt-sap:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 15:26:52.783  8137  8279 V BluetoothSapService: Sap Service initRfcommSocket
08-16 15:26:52.783  1044  1916 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:26:52.785  8137  8279 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
08-16 15:26:52.786  8137  8279 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=82 mFd=80
08-16 15:26:52.786  8137  8279 V BluetoothSapService: Succeed to create listening socket 
08-16 15:26:52.786  8137  8279 V BluetoothSapService: Accepting socket connection...
08-16 15:26:52.807  8278  8278 V BT_SAP  : Event pipe created
08-16 15:26:52.807  8278  8278 V BT_SAP  : create_server_socket qcom.sap.server
08-16 15:26:52.807  8278  8278 V BT_SAP  : created socket fd 6
,08-16 15:26:53.735  8137  8137 V BluetoothOppNotification: new notify threadi!
,08-16 15:26:53.736  8137  8137 V BluetoothOppNotification: send delay message
,08-16 15:26:53.747  8137  8289 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is (status == '192') AND (visibility IS NULL OR visibility == '0') AND (confirm == '1' OR confirm == '2' OR confirm == '5'); selectionArgs is null; sort is _id.
08-16 15:26:53.748  8137  8289 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@ec6a25 on behalf of 
08-16 15:26:53.749  8137  8289 V BluetoothOppNotification: mUpdateCompleteNotification = true
08-16 15:26:53.750  8137  8289 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 0); selectionArgs is null; sort is timestamp DESC.
08-16 15:26:53.752  8137  8289 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2a9ea7fa on behalf of 
08-16 15:26:53.753  8137  8289 V BluetoothOppNotification: outbound: succ-0  fail-0
,08-16 15:26:53.756  8137  8289 V BluetoothOppNotification: outbound notification was removed.
,08-16 15:26:53.756  8137  8289 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is status >= '200' AND (visibility IS NULL OR visibility == '0') AND (confirm != '5') AND (direction == 1); selectionArgs is null; sort is timestamp DESC.
,08-16 15:26:53.757  8137  8289 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2217e1ab on behalf of 
08-16 15:26:53.758  8137  8289 V BluetoothOppNotification: inbound: succ-0  fail-0
08-16 15:26:53.760  8137  8289 V BluetoothOppNotification: inbound notification was removed.
,08-16 15:26:53.760  8137  8289 V BluetoothOppProvider: starting query, database is not null; projection is null; selection is confirm == '0' AND (visibility IS NULL OR visibility == '0'); selectionArgs is null; sort is _id.,
08-16 15:26:53.761  8137  8289 V BluetoothOppProvider: created cursor android.database.sqlite.SQLiteCursor@2f6008 on behalf of 
08-16 15:26:56.295  6974  7031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:26:56.295  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:26:56.295  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED,
08-16 15:26:56.295  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: false
08-16 15:26:56.295  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:26:56.295  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:26:56.295  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:26:56.295  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
,08-16 15:26:56.310  6974  7031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: OFF, cellular: DO_NOT_CARE, BSSID name: null
,08-16 15:26:56.312  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:26:56.312  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@2b7c4cd6 removed from the list
08-16 15:26:56.312  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
,08-16 15:26:56.312  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:26:56.312  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:26:56.313  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 15:26:56.313  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@26da1b57 added. We now have 4 listener(s)
08-16 15:26:56.313  6974  7031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 15:26:56.316  1044  1773 D WifiServiceImplEx: setWifiEnabled: false pid=6974, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 15:26:56.316  1044  1773 D WifiService: setWifiEnabled: false pid=6974, uid=10118
08-16 15:26:56.316  1044  1773 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
,08-16 15:27:00.003  1044  1363 D PowerManagerServiceEx: acquireWakeLockInternal: lock=293336886, flags=0x40000001, tag="*alarm*", ws=WorkSource{1000}, historyTag=*alarm*:android.intent.action.TIME_TICK, uid=1000, pid=1044
,08-16 15:27:00.054  1589  1589 I [SystemUI]TimeTickManager: setTimeTickHandler, called onTimeChanged()
08-16 15:27:00.054  1589  1589 I KeyguardUpdateMonitor: called onTimeUpdated()
,08-16 15:27:00.054  1589  1589 I [SystemUI]KeyguardIndicationController: called onTimeUpdated()
08-16 15:27:00.054  1589  1589 I [SystemUI]Clock: called onTimeUpdated()
,08-16 15:27:00.060  1589  1589 I LgeClockWidgetControlView: called onTimeUpdated()
08-16 15:27:00.060  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
08-16 15:27:00.061  1589  1589 I [SystemUI]DateView: called onTimeUpdated()
08-16 15:27:00.062  1589  1589 D KeyguardUpdateMonitor: handleTimeUpdate
08-16 15:27:00.067  1044  1115 I ActivityManager: Start proc com.lge.qremote for broadcast com.lge.qremote/.appwidget.RemoteAppWidgetProvider: pid=8291 uid=10112 gids={50112, 9997, 1028, 1015, 3003, 3002} abi=armeabi
08-16 15:27:00.110  2589  2589 D [Concierge]Service: onStartCommand(). Type : 9
,08-16 15:27:00.203  8291  8291 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 15:27:00.226  8291  8291 D QRemote : [QRemoteApplication.java:230:onCreate()] oooooo QRemoteApp onCreate....
,08-16 15:27:00.274  8291  8291 D QRemote : [CarrierUtils.java:858:getHardwareSettings()] oooooo qremote android.os.Build.MODEL = LG-D855
08-16 15:27:00.275  8291  8291 I QRemote : [CarrierUtils.java:859:getHardwareSettings()] oooooo getCountry :: EU
,08-16 15:27:00.275  8291  8291 I QRemote : [CarrierUtils.java:860:getHardwareSettings()] oooooo getCarrier :: OPEN
,08-16 15:27:00.275  8291  8291 I QRemote : [CarrierUtils.java:861:getHardwareSettings()] oooooo getArea :: COM
,08-16 15:27:00.276  8291  8291 D QRemote : [CarrierUtils.java:862:getHardwareSettings()] oooooo Loading Config...
08-16 15:27:00.278  8291  8291 D QRemote : [CarrierUtils.java:876:getHardwareSettings()] oooooo qremote configuration file = R.xml.qremote_conf
08-16 15:27:00.284  8291  8291 D QRemote : [QRemoteApplication.java:701:updateWidget()] oooooo Widget count is [1]. send broadcast
08-16 15:27:00.300  8291  8291 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.wait_loading
08-16 15:27:00.301  8291  8291 D QRemote : [RemoteAppWidgetProvider.java:211:onReceive()] oooooo 140514:alarm msg received!:5104
08-16 15:27:00.304  1044  1044 D PowerManagerServiceEx: releaseWakeLockInternal: lock=293336886 [*alarm*], flags=0x0
,08-16 15:27:00.313  8291  8291 D QRemote : [QRemoteService.java:196:onCreate()] oooooo 140526:onCreate
08-16 15:27:00.319  8291  8291 D QRemote : [QRemoteService.java:217:onStartCommand()] oooooo 140526:onStartCommand:action:action.application.oncreate. startId:1, flags:0
08-16 15:27:00.319  8291  8291 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 15:27:00.321  8291  8291 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 15:27:00.321  8291  8291 D QRemote : [QRemoteApplication.java:86:getControlManager()] oooooo mControlManager is null. make new RemoteControlManager
,08-16 15:27:00.359  8291  8291 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 15:27:00.359  8291  8291 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 15:27:00.368  8291  8291 V SoundPool: SoundPool constructor: maxChannels=2, attr.usage=13, attr.flags=0x0, attr.tags=
08-16 15:27:00.369  8291  8291 V SoundPool: load: fd=30, offset=10857164, length=17813, priority=1
,08-16 15:27:00.369  8291  8291 V SoundPool: create sampleID=1, fd=31, offset=17813 length=10857164
08-16 15:27:00.369  8291  8291 V SoundPool: doLoad: loading sample sampleID=1
08-16 15:27:00.369  8291  8291 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 15:27:00.373  7831  7831 D UEI.SmartControl: QS Service created
,08-16 15:27:00.373  8291  8328 V SoundPool: Start decode
,08-16 15:27:00.374  8291  8328 V MediaPlayer[Native]: decode(31, 10857164, 17813)
08-16 15:27:00.376   326   326 V MediaPlayerService: decode(22, 10857164, 17813)
08-16 15:27:00.376   326   326 W BrunchPlayerTypeImpl: [SelectPlayer] LocalType
08-16 15:27:00.376   326   326 W BrunchPlayerTypeImpl: [getMediaType] EXTEND_MEDIA_MIMETYPE = application/ogg
08-16 15:27:00.376   326   326 W BrunchPlayerTypeImpl: [FindUsePlayer] type = [application/ogg]
,08-16 15:27:00.376   326   326 W BrunchPlayerTypeImpl: [FindUsePlayer] componentName = [9101]
08-16 15:27:00.376   326   326 W MediaPlayerFactory: [getPlayerType:fd] nType = 3
08-16 15:27:00.376   326   326 V MediaPlayerService: player type = 3
08-16 15:27:00.376   326   326 V AwesomePlayer: AwesomePlayer create()
08-16 15:27:00.376  8291  8291 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
08-16 15:27:00.377   326   326 V AwesomePlayer: reset_l() 
08-16 15:27:00.377   326   326 V AwesomePlayer: cancelPlayerEvents
08-16 15:27:00.377   326   326 V AwesomePlayer: setAudioSink() 
08-16 15:27:00.377   326   326 V AwesomePlayer: reset_l() 
08-16 15:27:00.377   326   326 V AudioCache: notify(0xb16a67c0, 8, 0, 0)
08-16 15:27:00.377   326   326 V AudioCache: ignored
08-16 15:27:00.377   326   326 V AwesomePlayer: cancelPlayerEvents
08-16 15:27:00.377   326   326 D Utils   : printFileName fd(23) -> /data/preload/LGQRemote/LGQRemote.apk
08-16 15:27:00.377   326   326 V AwesomePlayer: setDataSource_l dataSource
08-16 15:27:00.377   326   326 V LGParserOSAL: SniffLGParser start
08-16 15:27:00.378   326   326 V LGParserOSAL: MainType:5, SubType=0
08-16 15:27:00.378   326   326 V LGParserOSAL: #### check Mime : application/ogg
08-16 15:27:00.378   326   326 V LGParserOSAL: Detector mimeType:application/ogg, Confidence=1.000000
08-16 15:27:00.378   326   326 E MediaExtractor: Use LGExtractor :application/ogg 
08-16 15:27:00.381  8291  8291 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 15:27:00.382  8291  8291 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
08-16 15:27:00.403  8291  8291 V LGMDMManager: Create singleton instance
08-16 15:27:00.404  7831  7831 I UEI.SmartControl: Service initServices...
08-16 15:27:00.405  7831  7831 D UEI.SmartControl: QS start get config
,08-16 15:27:00.417   326   326 V LGParserOSAL: supported mime: application/ogg
08-16 15:27:00.417   326   326 V AwesomePlayer: setDataSource_l() extractor countTracks=1
08-16 15:27:00.417   326   326 V AwesomePlayer: track of type 'audio/vorbis' does not publish bitrate
08-16 15:27:00.417   326   326 V AwesomePlayer: mBitrate = -1 bits/sec
08-16 15:27:00.417   326   326 V AwesomePlayer: AudioTrack Setting
08-16 15:27:00.417   326   326 V AwesomePlayer: AudioTrack Setting channelCount = 2
08-16 15:27:00.417   326   326 V AwesomePlayer: setAudioSource() 
08-16 15:27:00.417   326   326 V MediaPlayerService: prepare
08-16 15:27:00.417   326   326 V AwesomePlayer: prepareAsync_l() 
08-16 15:27:00.417   326   326 V MediaPlayerService: wait for prepare
08-16 15:27:00.420   326  8331 V AwesomePlayer: onPrepareAsyncEvent() 
08-16 15:27:00.420   326  8331 V AwesomePlayer: initAudioDecoder() 
08-16 15:27:00.421   326  8331 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 15:27:00.421   326  8331 V AudioSystem: isOffloadSupported()
08-16 15:27:00.421   326  8331 V AudioPolicyManager: isOffloadSupported: SR=48000, CM=0x3, Format=0x7000000, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 15:27:00.422   326  8331 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 15:27:00.422   326  8331 I AudioFlinger: isAudioPlaybackHookOn() false
08-16 15:27:00.422   326  8331 V AwesomePlayer: getUseOffload() = 0 
08-16 15:27:00.424   326  8331 V OMXCodec: OMXCodec::Create
08-16 15:27:00.424   326  8331 V OMXCodec: findMatchingCodecs()
08-16 15:27:00.424   326  8331 V OMXCodec: matching 'OMX.google.vorbis.decoder' quirks 0x00000000
08-16 15:27:00.424   326  8331 V OMXCodec: matchingCodecs.size()=1
08-16 15:27:00.424   326  8331 V OMXCodec: Attempting to allocate OMX node 'OMX.google.vorbis.decoder'
08-16 15:27:00.429   326  8331 D OMXCodec: Successfully allocated OMX node 'OMX.google.vorbis.decoder'
08-16 15:27:00.429   326  8331 V LGCodecAdapter: LG Codec Adapter start
08-16 15:27:00.429   326  8331 V OMXCodec: OMXCodec Createtor
08-16 15:27:00.429   326  8331 V OMXCodec: setComponentRole
08-16 15:27:00.429   326  8331 V OMXCodec: configureCodec protected=0
08-16 15:27:00.429   326  8331 V LGCodecAdapter: called getLGCodecSpecificData
08-16 15:27:00.429   326  8331 V LGCodecOSAL: Called LGgetCodecSpecificDataMETA
08-16 15:27:00.429   326  8331 V LGCodecOSAL: Called LGconfigureCodecMETA
08-16 15:27:00.429   326  8331 V LGCodecOSAL: Called LGconfigureCodecMSG
08-16 15:27:00.430   326  8331 V LGCodecOSAL: Not support LGCodec
08-16 15:27:00.430   326  8331 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 15:27:00.430   326  8331 V OMXCodec: Codec outputs a different number of channels than the input stream contains (contains 2 channels, codec outputs 1 channels).
08-16 15:27:00.430   326  8331 V OMXCodec: Codec outputs at different sampling rate than what the input stream contains (contains data at 48000 Hz, codec outputs 44100 Hz)
08-16 15:27:00.430   326  8331 I AwesomePlayer: Could not offload audio decode, try pcm offload
08-16 15:27:00.430   326  8331 W Utils   : bool android::canOffloadStream(const android::sp<android::MetaData>&, bool, const android::sp<android::MetaData>&, bool, audio_stream_type_t) No Sample Bit info in meta data
08-16 15:27:00.430   326  8331 V AudioSystem: isOffloadSupported()
08-16 15:27:00.430   326  8331 V AudioPolicyManager: isOffloadSupported: SR=44100, CM=0x1, Format=0x1c000001, StreamType=-1, BitRate=4294967295, duration=1068125 us, has_video=0
08-16 15:27:00.430   326  8331 D AudioPolicyManager: isOffloadSupported: stream_type != MUSIC, returning false
08-16 15:27:00.430   326  8331 V OMXCodec: [OMX.google.vorbis.decoder] start mState=1
08-16 15:27:00.430   326  8331 V OMXCodec: init()
08-16 15:27:00.430   326  8331 V OMXCodec: [OMX.google.vorbis.decoder] set,State mState=1 , newState=2
08-16 15:27:00.431   326  8331 V OMXCodec: allocateBuffers
08-16 15:27:00.431   326  8331 V OMXCodec: allocateBuffersOnPort portIndex=0
08-16 15:27:00.431   326  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 8192 on input port
08-16 15:27:00.431   326  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f76f0 on input port
08-16 15:27:00.431   326  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7740 on input port
08-16 15:27:00.431   326  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f77e0 on input port
08-16 15:27:00.432   326  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7a60 on input port
08-16 15:27:00.432   326  8331 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 15:27:00.432   326  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 15:27:00.432   326  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-16 15:27:00.432   326  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-16 15:27:00.432   326  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-16 15:27:00.432   326  8331 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7fb0 on output port
08-16 15:27:00.432   326  8331 V OMXCodec: init() mAsyncCompletion wait!!! 
08-16 15:27:00.433   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 15:27:00.433   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 15:27:00.433   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=2 , newState=3
08-16 15:27:00.433   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 3
08-16 15:27:00.433   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] Now Executing.
08-16 15:27:00.433   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=3 , newState=4
08-16 15:27:00.433   326  8331 V OMXCodec: init() mAsyncCompletion wait free! 
08-16 15:27:00.433   326  8331 V AwesomePlayer: finishAsyncPrepare_l() 
08-16 15:27:00.433   326  8331 V AudioCache: notify(0xb16a67c0, 5, 0, 0)
08-16 15:27:00.433   326  8331 V AudioCache: ignored
08-16 15:27:00.433   326  8331 V AudioCache: notify(0xb16a67c0, 1, 0, 0)
08-16 15:27:00.433   326  8331 V AudioCache: prepared
08-16 15:27:00.433   326   326 V AudioCache: wait - success
08-16 15:27:00.433   326   326 V MediaPlayerService: start
08-16 15:27:00.433   326   326 V AwesomePlayer: play_l() 
08-16 15:27:00.433   326   326 V AwesomePlayer: play_l m_isDivXDRM=0, bpurchasefile:0
08-16 15:27:00.433   326   326 V AwesomePlayer: createAudioPlayer_l
08-16 15:27:00.433   326   326 V AwesomePlayer: seekAudioIfNecessary_l() 
08-16 15:27:00.433   326   326 V AwesomePlayer: startAudioPlayer_l() 
08-16 15:27:00.433   326   326 D AudioPlayer: start of Playback, useOffload 0
08-16 15:27:00.433   326   326 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 15:27:00.433   326   326 V OMXCodec: [OMX.google.vorbis.decoder] calling emptyBuffer with codec specific data
08-16 15:27:00.435   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] OMX_EventPortSettingsChanged(port=1, data2=0x00000000)
08-16 15:27:00.435   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] PORT_SETTINGS_CHANGED(1)
08-16 15:27:00.435   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=7
08-16 15:27:00.435   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] disablePortAsync portIndex=1
08-16 15:27:00.435   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortDisable(1)
08-16 15:27:00.435   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 15:27:00.435   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041884848
08-16 15:27:00.435   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 15:27:00.435   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885008
08-16 15:27:00.435   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 15:27:00.435   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041885088
08-16 15:27:00.435   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 15:27:00.435   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] Port is disabled, freeing buffer 3041886128
08-16 15:27:00.435   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 15:27:00.435   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] PORT_DISABLED(1)
08-16 15:27:00.435   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] initOutputFormat()
08-16 15:27:00.435   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] reconfig handling, formatHasNotablyChanged
08-16 15:27:00.435   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] enablePortAsync portIndex=1
08-16 15:27:00.435   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] sending OMX_CommandPortEnable(1)
08-16 15:27:00.435   326  8333 V OMXCodec: allocateBuffersOnPort portIndex=1
08-16 15:27:00.435   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] allocating 4 buffers of size 32768 on output port
08-16 15:27:00.436   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ba0 on output port
08-16 15:27:00.436   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7b50 on output port
08-16 15:27:00.436   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb54f7ab0 on output port
08-16 15:27:00.436   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] allocated buffer 0xb040f920 on output port
08-16 15:27:00.436   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] PORT_ENABLED(1)
08-16 15:27:00.436   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=7 , newState=4
08-16 15:27:00.437   326   326 V AudioCache: open(48000, 2, 0x0, 1, 4)
08-16 15:27:00.437   326   326 V AudioCache: notify(0xb16a67c0, 6, 0, 0)
08-16 15:27:00.437   326   326 V AudioCache: ignored
08-16 15:27:00.438   326   326 V MediaPlayerService: wait for playback complete
08-16 15:27:00.438   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.438   326  8334 V AudioCache: memcpy(0xabe08000, 0xb16b7000, 4096)
08-16 15:27:00.440   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.440   326  8334 V AudioCache: memcpy(0xabe09000, 0xb16b7000, 4096)
08-16 15:27:00.440   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.440   326  8334 V AudioCache: memcpy(0xabe0a000, 0xb16b7000, 4096)
08-16 15:27:00.441   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.441   326  8334 V AudioCache: memcpy(0xabe0b000, 0xb16b7000, 4096)
08-16 15:27:00.442   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.442   326  8334 V AudioCache: memcpy(0xabe0c000, 0xb16b7000, 4096)
08-16 15:27:00.443   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.443   326  8334 V AudioCache: memcpy(0xabe0d000, 0xb16b7000, 4096)
08-16 15:27:00.443   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.444   326  8334 V AudioCache: memcpy(0xabe0e000, 0xb16b7000, 4096)
08-16 15:27:00.445   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.445   326  8334 V AudioCache: memcpy(0xabe0f000, 0xb16b7000, 4096)
08-16 15:27:00.446   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.446   326  8334 V AudioCache: memcpy(0xabe10000, 0xb16b7000, 4096)
08-16 15:27:00.447   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.447   326  8334 V AudioCache: memcpy(0xabe11000, 0xb16b7000, 4096)
08-16 15:27:00.447   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.447   326  8334 V AudioCache: memcpy(0xabe12000, 0xb16b7000, 4096)
08-16 15:27:00.448   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.448   326  8334 V AudioCache: memcpy(0xabe13000, 0xb16b7000, 4096)
08-16 15:27:00.448   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.448   326  8334 V AudioCache: memcpy(0xabe14000, 0xb16b7000, 4096)
08-16 15:27:00.449   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.449   326  8334 V AudioCache: memcpy(0xabe15000, 0xb16b7000, 4096)
08-16 15:27:00.449   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.449   326  8334 V AudioCache: memcpy(0xabe16000, 0xb16b7000, 4096)
08-16 15:27:00.450   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.450   326  8334 V AudioCache: memcpy(0xabe17000, 0xb16b7000, 4096)
08-16 15:27:00.450   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.450   326  8334 V AudioCache: memcpy(0xabe18000, 0xb16b7000, 4096)
08-16 15:27:00.451   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.451   326  8334 V AudioCache: memcpy(0xabe19000, 0xb16b7000, 4096)
08-16 15:27:00.451   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.451   326  8334 V AudioCache: memcpy(0xabe1a000, 0xb16b7000, 4096)
08-16 15:27:00.452   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.452   326  8334 V AudioCache: memcpy(0xabe1b000, 0xb16b7000, 4096)
08-16 15:27:00.453   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.453   326  8334 V AudioCache: memcpy(0xabe1c000, 0xb16b7000, 4096)
08-16 15:27:00.453   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.453   326  8334 V AudioCache: memcpy(0xabe1d000, 0xb16b7000, 4096)
08-16 15:27:00.454   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.454   326  8334 V AudioCache: memcpy(0xabe1e000, 0xb16b7000, 4096)
08-16 15:27:00.455   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.455   326  8334 V AudioCache: memcpy(0xabe1f000, 0xb16b7000, 4096)
08-16 15:27:00.455   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.455   326  8334 V AudioCache: memcpy(0xabe20000, 0xb16b7000, 4096)
08-16 15:27:00.456   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.456   326  8334 V AudioCache: memcpy(0xabe21000, 0xb16b7000, 4096)
08-16 15:27:00.456   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.456   326  8334 V AudioCache: memcpy(0xabe22000, 0xb16b7000, 4096)
08-16 15:27:00.457   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.457   326  8334 V AudioCache: memcpy(0xabe23000, 0xb16b7000, 4096)
08-16 15:27:00.457   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.457   326  8334 V AudioCache: memcpy(0xabe24000, 0xb16b7000, 4096)
08-16 15:27:00.458   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.458   326  8334 V AudioCache: memcpy(0xabe25000, 0xb16b7000, 4096)
08-16 15:27:00.458   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.458   326  8334 V AudioCache: memcpy(0xabe26000, 0xb16b7000, 4096)
08-16 15:27:00.458   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.459   326  8334 V AudioCache: memcpy(0xabe27000, 0xb16b7000, 4096)
08-16 15:27:00.459   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.459   326  8334 V AudioCache: memcpy(0xabe28000, 0xb16b7000, 4096)
08-16 15:27:00.459   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.459   326  8334 V AudioCache: memcpy(0xabe29000, 0xb16b7000, 4096)
08-16 15:27:00.460   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.460   326  8334 V AudioCache: memcpy(0xabe2a000, 0xb16b7000, 4096)
08-16 15:27:00.460   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.460   326  8334 V AudioCache: memcpy(0xabe2b000, 0xb16b7000, 4096)
08-16 15:27:00.461   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.461   326  8334 V AudioCache: memcpy(0xabe2c000, 0xb16b7000, 4096)
08-16 15:27:00.461   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.461   326  8334 V AudioCache: memcpy(0xabe2d000, 0xb16b7000, 4096)
08-16 15:27:00.462   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.462   326  8334 V AudioCache: memcpy(0xabe2e000, 0xb16b7000, 4096)
08-16 15:27:00.462   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.462   326  8334 V AudioCache: memcpy(0xabe2f000, 0xb16b7000, 4096)
08-16 15:27:00.462   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.463   326  8334 V AudioCache: memcpy(0xabe30000, 0xb16b7000, 4096)
08-16 15:27:00.463   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.463   326  8334 V AudioCache: memcpy(0xabe31000, 0xb16b7000, 4096)
08-16 15:27:00.463   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.463   326  8334 V AudioCache: memcpy(0xabe32000, 0xb16b7000, 4096)
08-16 15:27:00.464   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.464   326  8334 V AudioCache: memcpy(0xabe33000, 0xb16b7000, 4096)
08-16 15:27:00.464   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.464   326  8334 V AudioCache: memcpy(0xabe34000, 0xb16b7000, 4096)
08-16 15:27:00.465   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.465   326  8334 V AudioCache: memcpy(0xabe35000, 0xb16b7000, 4096)
08-16 15:27:00.465   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.465   326  8334 V AudioCache: memcpy(0xabe36000, 0xb16b7000, 4096)
,08-16 15:27:00.466   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.466   326  8334 V AudioCache: memcpy(0xabe37000, 0xb16b7000, 4096)
08-16 15:27:00.466   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.466   326  8334 V AudioCache: memcpy(0xabe38000, 0xb16b7000, 4096)
08-16 15:27:00.467   326  8334 V AudioCache: write(0xb16b7000, 4096)
08-16 15:27:00.467   326  8334 V AudioCache: memcpy(0xabe39000, 0xb16b7000, 4096)
08-16 15:27:00.467   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] No more output data.
08-16 15:27:00.467   326  8334 V OMXCodec: [OMX.google.vorbis.decoder] There is no more output data available, not calling fillOutputBuffer
08-16 15:27:00.467   326  8334 V AwesomePlayer: postAudioEOS() 
08-16 15:27:00.467   326  8334 V AudioCache: write(0xb16b7000, 280)
08-16 15:27:00.467   326  8334 V AudioCache: memcpy(0xabe3a000, 0xb16b7000, 280)
08-16 15:27:00.470   326  8331 V AwesomePlayer: postStreamDoneEvent_l() -> status:-1011 
08-16 15:27:00.470   326  8331 V AwesomePlayer: onStreamDone
08-16 15:27:00.470   326  8331 V AwesomePlayer: MEDIA_PLAYBACK_COMPLETE
08-16 15:27:00.470   326  8331 V AudioCache: notify(0xb16a67c0, 2, 0, 0)
08-16 15:27:00.470   326  8331 V AudioCache: playback complete
08-16 15:27:00.470   326  8331 V AwesomePlayer: pause_l() 
08-16 15:27:00.471   326  8331 V AudioCache: notify(0xb16a67c0, 7, 0, 0)
08-16 15:27:00.471   326  8331 V AudioCache: ignored
08-16 15:27:00.471   326  8331 V AwesomePlayer: cancelPlayerEvents
08-16 15:27:00.471   326   326 V AudioCache: wait - success
08-16 15:27:00.471   326   326 V MediaPlayerService: return size 205080, sampleRate=48000, channelCount = 2, format = 1
08-16 15:27:00.471   326  8331 D AudioPlayer: Pause Playback at 1068125
08-16 15:27:00.471   326   326 V AwesomePlayer: reset_l() 
08-16 15:27:00.471   326   326 V AudioCache: notify(0xb16a67c0, 8, 0, 0)
08-16 15:27:00.471   326   326 V AudioCache: ignored
08-16 15:27:00.471   326   326 V AwesomePlayer: cancelPlayerEvents
08-16 15:27:00.471   326   326 D AudioPlayer: reset: mPlaying=0 mReachedEOS=1 useOffload=0
08-16 15:27:00.471   326   326 V OMXCodec: [OMX.google.vorbis.decoder] stop mState=4
08-16 15:27:00.471   326   326 V OMXCodec: [OMX.google.vorbis.decoder] stopOmxComponent_l mState=4
08-16 15:27:00.471   326   326 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=4 , newState=5
08-16 15:27:00.471   326   326 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 15:27:00.472   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 2
08-16 15:27:00.472   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] Now Idle.
08-16 15:27:00.472   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=0
08-16 15:27:00.472   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7a60 on port 0
08-16 15:27:00.472   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=3
08-16 15:27:00.472   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f77e0 on port 0
08-16 15:27:00.472   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=2
08-16 15:27:00.472   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7740 on port 0
08-16 15:27:00.472   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=1
08-16 15:27:00.472   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f76f0 on port 0
08-16 15:27:00.472   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=0,bufIndex=0
08-16 15:27:00.472   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffersOnPort portIndex=1
08-16 15:27:00.472   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb040f920 on port 1
08-16 15:27:00.472   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=3
08-16 15:27:00.472   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ab0 on port 1
08-16 15:27:00.472   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=2
08-16 15:27:00.473   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7b50 on port 1
08-16 15:27:00.473   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=1
08-16 15:27:00.473   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeing buffer 0xb54f7ba0 on port 1
08-16 15:27:00.473   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] freeBuffer portIndex=1,bufIndex=0
08-16 15:27:00.473   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=5 , newState=6
08-16 15:27:00.473   326   326 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 15:27:00.473   326   326 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait lock!!
08-16 15:27:00.473   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] onStateChange 1
08-16 15:27:00.473   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] Now Loaded.
08-16 15:27:00.473   326  8333 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=6 , newState=1
08-16 15:27:00.473   326   326 V OMXCodec: [OMX.google.vorbis.decoder] mAsyncCompletion wait free!!
08-16 15:27:00.473   326   326 V OMXCodec: [OMX.google.vorbis.decoder] stopped in state 1
08-16 15:27:00.473   326   326 V OMXCodec: [OMX.google.vorbis.decoder] ~OMXCodec mstate =1
08-16 15:27:00.474   326   326 V OMXCodec: [OMX.google.vorbis.decoder] setState mState=1 , newState=0
08-16 15:27:00.475   326   326 D AudioPlayer: AudioPlayer releasing audio source
08-16 15:27:00.475   326   326 D AudioPlayer: AudioPlayer done releasing audio source
08-16 15:27:00.475   326   326 V AwesomePlayer: reset_l() 
08-16 15:27:00.475   326   326 V AwesomePlayer: cancelPlayerEvents
08-16 15:27:00.475   326   326 V AwesomePlayer: ~AwesomePlayer call
08-16 15:27:00.475   326   326 V AwesomePlayer: reset_l() 
08-16 15:27:00.475   326   326 V AwesomePlayer: cancelPlayerEvents
08-16 15:27:00.475  8291  8291 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 15:27:00.475  8291  8328 V SoundPool: close(31)
08-16 15:27:00.475  8291  8328 V SoundPool: pointer = 0x9fea9000, size = 205080, sampleRate = 48000, numChannels = 2
08-16 15:27:00.484  8291  8291 D QRemote : [RemoteAppWidgetProvider.java:486:onUpdate()] oooooo 140510:RetrieveDevices is not complete. Just waiting
,08-16 15:27:00.486  8291  8291 D QRemote : [RemoteAppWidgetProvider.java:499:onUpdate()] oooooo 140514:alarm set after 5000ms:3735
,08-16 15:27:00.694  7831  7831 I UEI.SmartControl: Supports setup maps: true
,08-16 15:27:00.697  7831  7831 D UEI.SmartControl: QS start statue = true Error code = 0
,08-16 15:27:00.697  7831  7831 I UEI.SmartControl: QS version = v2.7.10.1_RC1
,08-16 15:27:00.697  7831  7831 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
,08-16 15:27:00.698  7831  7831 I UEI.SmartControl: ### init IR Blaster...
,08-16 15:27:00.701  7831  7831 D serial_port: Configuring serial port
08-16 15:27:00.702  7831  7831 E UEI.SmartControl: UEIBLaster setting for 616
,08-16 15:27:00.702  7831  7831 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 15:27:00.702  7831  7831 I UEI.SmartControl: configuring settings for MAXQ616
08-16 15:27:00.702  7831  7831 I UEI.SmartControl: Get version...
08-16 15:27:00.721  7831  8335 D UEI.SmartControl: serial port data available: 21
,08-16 15:27:00.747  7831  7831 D UEI.SmartControl: MAXQ616 A2-X4 software.
,08-16 15:27:00.747  7831  7831 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-16 15:27:00.747  7831  7831 I UEI.SmartControl: QS saving settings...
08-16 15:27:00.749  7831  7831 D UEI.SmartControl: IR Blaster version: 25672567
08-16 15:27:00.771  7831  8335 D UEI.SmartControl: serial port data available: 4
,08-16 15:27:00.811  7831  8344 I UEI.SmartControl: Device manager: loading config....
,08-16 15:27:00.812  7831  8344 D UEI.SmartControl: ----------- loading internal config...
,08-16 15:27:00.813  7831  7831 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
,08-16 15:27:00.821  7831  7831 E UEI.SmartControl: Services init done
,08-16 15:27:00.821  7831  7831 D UEI.SmartControl: QS Service init finished
08-16 15:27:00.827  7831  7831 D UEI.SmartControl: QS Service version name: 2.1.91
,08-16 15:27:00.834  7831  7831 D UEI.SmartControl: QS Service version code: 201091
08-16 15:27:00.836  7831  7831 D UEI.SmartControl: Service requested: Control
08-16 15:27:00.837  7831  8344 E UEI.SmartControl: Loading SETTINGS...
08-16 15:27:00.841  7831  7831 D UEI.SmartControl: Request IControl service: devices are loaded...
08-16 15:27:00.844  8291  8291 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
,08-16 15:27:00.846  7831  7831 D UEI.SmartControl: Internal service binding...
08-16 15:27:00.848  7831  7889 I UEI.SmartControl: ------ IControl API: 11
08-16 15:27:00.848  7831  7889 D UEI.SmartControl: File observer start...
08-16 15:27:00.848  7831  7889 E UEI.SmartControl: IR Port is disabled: false
08-16 15:27:00.848  7831  7889 D UEI.SmartControl: Starting file observer...
08-16 15:27:00.849  7831  7889 I UEI.SmartControl: Registering callback...
08-16 15:27:00.850  7831  7847 I UEI.SmartControl: ------ IControl API: 19
08-16 15:27:00.851  7831  7847 I UEI.SmartControl: Registering Services Ready callback...
08-16 15:27:00.852  7831  8344 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-16 15:27:00.873  7831  8343 I UEI.SmartControl: Notify AllClients services are ready: 0
,08-16 15:27:00.877  8291  8307 I QRemote : [RemoteControlManager.java:660:QSSetupIsReady()] oooooo 140517:sdkIsReady callback... get functions. Result:0
08-16 15:27:00.878  8291  8326 D QRemote : [RemoteControlManager.java:388:handleMessage()] oooooo 140510:START_SESSION
08-16 15:27:00.878  8291  8326 D QRemote : [RemoteControlManager.java:394:handleMessage()] oooooo 140510:send retrieve msg
08-16 15:27:00.878  8291  8291 D QRemote : [RemoteControlManager.java:322:handleMessage()] oooooo 140510:handler call retrieveDevices
08-16 15:27:00.879  8291  8291 D QRemote : [RemoteControlManager.java:336:retrieveDevices()] oooooo retrieveDevices: start
08-16 15:27:00.879  7831  7848 I UEI.SmartControl: ------ IControl API: 8
08-16 15:27:00.880  7831  8343 D UEI.SmartControl: -----service ready thread exits
08-16 15:27:00.881  8291  8291 D QRemote : [RemoteControlManager.java:340:retrieveDevices()] oooooo retrieveDevices: 0
08-16 15:27:00.881  8291  8291 D QRemote : [RemoteControlManager.java:345:retrieveDevices()] oooooo retrieveDevices complete:true
08-16 15:27:00.882  8291  8291 D QRemote : [RemoteControlManager.java:353:retrieveDevices()] oooooo retrieveDevices: notifyDataSetChanged()
08-16 15:27:00.883  8291  8291 D QRemote : [QRemoteApplication.java:145:onRemoteControlStateChanged()] oooooo onRemoteControlStateChanged called in QRemoteApp
08-16 15:27:00.883  8291  8291 D QRemote : [QRemoteApplication.java:158:onRemoteControlStateChanged()] oooooo Widget count is [1]. send broadcast
08-16 15:27:00.884  8291  8291 D QRemote : [QRemoteApplication.java:160:onRemoteControlStateChanged()] oooooo Widget[0]:3
08-16 15:27:00.889  8291  8291 D QRemote : [QRemoteApplication.java:188:onRemoteControlStateChanged()] oooooo 140526:onRemoteControlStateChanged&sdkIsReady. stop Service
,08-16 15:27:00.897  8291  8291 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : android.appwidget.action.APPWIDGET_UPDATE
08-16 15:27:00.899  8291  8291 D QRemote : [RemoteAppWidgetProvider.java:449:onUpdate()] oooooo onUpdate()
08-16 15:27:00.905  8291  8291 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 15:27:00.905  8291  8291 D QRemote : [RemoteAppWidgetProvider.java:457:onUpdate()] oooooo onUpdate orientation:true
,08-16 15:27:00.909  8291  8291 D QRemote : [RemoteAppWidgetProvider.java:480:onUpdate()] oooooo updateAppWidget to loading view
08-16 15:27:00.910  8291  8291 D QRemote : [RemoteAppWidgetProvider.java:506:onUpdate()] oooooo 140510:RetrieveDevices complete. Start loading
08-16 15:27:00.910  8291  8291 D QRemote : [RemoteAppWidgetProvider.java:508:onUpdate()] oooooo 140510:appWidgetIds[0]:3 loading
08-16 15:27:00.911  8291  8291 D QRemote : [RemoteAppWidgetManager.java:41:startLoading()] oooooo 140518:widgetId[3] loading start at [1471354020911]
08-16 15:27:00.914  8291  8291 D QRemote : [QRemoteService.java:207:onDestroy()] oooooo 140526:onDestroy
08-16 15:27:00.958  8291  8349 D QRemote : [RemoteAppWidgetManager.java:239:doInBackground()] oooooo 140407:doinBack arr:0
,08-16 15:27:00.966  8291  8291 V QRemote : [RemoteAppWidgetProvider.java:154:onReceive()] oooooo action name : com.lge.qremote.action.widget_ui_update
08-16 15:27:00.967  8291  8291 E QRemote : [RemoteAppWidgetProvider.java:406:isLimitationView()] oooooo rotation : 0
08-16 15:27:00.967  8291  8291 D QRemote : [RemoteAppWidgetProvider.java:171:onReceive()] oooooo total:0
08-16 15:27:00.968  8291  8291 D QRemote : [RemoteAppWidgetProvider.java:172:onReceive()] oooooo selected:0
08-16 15:27:00.968  8291  8291 D QRemote : [RemoteAppWidgetProvider.java:173:onReceive()] oooooo arr:[]
08-16 15:27:00.968  8291  8291 D QRemote : [RemoteAppWidgetProvider.java:174:onReceive()] oooooo appWidgetId:3
08-16 15:27:00.969  8291  8291 D QRemote : [RemoteAppWidgetProvider.java:815:updateRemoteViews()] oooooo UpdateRemoteViews3:widgetId:3
08-16 15:27:00.988  8291  8291 D QRemote : [RemoteAppWidgetProvider.java:986:updateRemoteViews()] oooooo updateAppWidget5:widgetId:3]
,08-16 15:27:01.327  6974  7031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:27:01.339  1044  1886 D WifiServiceImplEx: setWifiEnabled: true pid=6974, uid=10118, package= com.test.thalitest, App Lable : ThaliTest
08-16 15:27:01.340  1044  1886 D WifiService: setWifiEnabled: true pid=6974, uid=10118
08-16 15:27:01.341  1044  1886 E WifiService: Invoking mWifiStateMachine.setWifiEnabled
08-16 15:27:01.368  1044  1044 D LocationManagerService: getAllProviders()=[passive, gps, network]
08-16 15:27:01.368  1044  1044 D Ulp_jni : JNI:In update_settings:currentContextType 4, currentGpsSetting 0, currentAgpsSetting 1,currentNetworkProvSetting 0,currentWifiSetting 1,currentBatteryCharging 0,currentEnhLocationServicesSetting 0 currentPipUserSetting 0 
08-16 15:27:01.368  1044  1044 D Ulp_jni : JNI:system_update. Event-4
,08-16 15:27:01.373  1044  1525 E WifiStateMachine:  InitialState CMD_START_SUPPLICANT 0 0
08-16 15:27:01.373  1044  1525 I LGFTMITEM: [GET_FTM][id=6], offset=12288
08-16 15:27:01.382  1044  1525 E WifiUtil: wfc_util_ffile_check_copy(): pid[1044] pDestFName[/data/misc/wifi/WCNSS_qcom_cfg.ini] pSourceFName[/system/etc/wifi/WCNSS_qcom_cfg.ini]
08-16 15:27:01.382  1044  1525 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 15:27:01.382  1044  1525 E WifiUtil: wfc_util_ffile_check_copy(): pid[1044] pDestFName[/data/misc/wifi/WCNSS_qcom_wlan_nv.bin] pSourceFName[/system/etc/wifi/WCNSS_qcom_wlan_nv.bin]
08-16 15:27:01.382  1044  1525 E WifiUtil: wfc_util_ffile_check_copy(): mode[432] uID[1000] gID[1010]
08-16 15:27:01.382  1044  1525 I WifiUtil: Intf0MacAddress=C49A027FFB5D
08-16 15:27:01.382  1044  1525 E WifiHW  : unknown target_country: EU , set to default
08-16 15:27:01.382  1044  1525 E WifiHW  : [wifi_ensure_config_files] default country1 = GB
08-16 15:27:01.382  1044  1525 E WifiHW  : [wifi_ensure_config_files] default country2 = GB
08-16 15:27:01.382  1044  1525 I WifiUtil: gEnableBmps=1
,08-16 15:27:01.981   321   903 D SoftapController: Softap fwReload - Ok
,08-16 15:27:01.987  1044  1525 E NetdConnector: NDC Command {84 softap fwreload wlan0 STA} took too long (594ms)
08-16 15:27:01.990   321   903 D CommandListener: Setting iface cfg
08-16 15:27:01.990   321   903 D CommandListener: Trying to bring down wlan0
08-16 15:27:01.990   321   903 D CommandListener: Clearing all IP addresses on wlan0
,08-16 15:27:02.013  1044  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 15:27:02.016  1044  1525 E WifiHW  : Cannot open "/system/etc/wifi/autojoinconfig.txt": No such file or directory
08-16 15:27:02.035  1044  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 15:27:02.035  1044  1525 E WifiStateMachine: useWiFiOffloading() : false
08-16 15:27:02.035  1044  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
,08-16 15:27:02.029  8359  8359 W wpa_supplicant: type=1400 audit(0.0:189): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 15:27:02.029  8359  8359 W wpa_supplicant: type=1400 audit(0.0:190): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:wpa:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 15:27:02.052  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [2]
,08-16 15:27:02.057  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:27:02.058  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 1
08-16 15:27:02.075  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
,08-16 15:27:02.079  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:27:02.081  1044  1525 D WifiMonitor: startMonitoring(wlan0) with mConnected = false
08-16 15:27:02.081  1044  1525 D WifiMonitor: connecting to supplicant
08-16 15:27:02.092  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 15:27:02.092  7091  7091 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 15:27:02.092  7091  7091 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 15:27:02.093  7091  7091 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 15:27:02.094  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-16 15:27:02.097  7091  7091 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 15:27:02.097  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
,08-16 15:27:02.097  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 15:27:02.098  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 15:27:02.098  7091  7091 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 15:27:02.098  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 15:27:02.098  7091  7091 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 15:27:02.103  8359  8359 I wpa_supplicant: Successfully initialized wpa_supplicant
08-16 15:27:02.138  8359  8359 I wpa_supplicant: rfkill: Cannot open RFKILL control device
08-16 15:27:02.139  8359  8359 I wpa_supplicant: [LGE_PATCH] unset P2P_CAPABLE to ifname wlan0
08-16 15:27:02.141  1044  1119 D Tethering: InitialState.processMessage what=4
,08-16 15:27:02.150  1044  1638 I ActivityManager: Start proc com.lge.formmanager for broadcast com.lge.formmanager/.FormServiceReceiver: pid=8376 uid=10026 gids={50026, 9997, 3003, 1028} abi=armeabi-v7a
08-16 15:27:02.151  1044  1119 D Tethering: sendTetherStateChangedBroadcast 0, 0, 0
,08-16 15:27:02.207  8359  8359 I wpa_supplicant: rfkill: Cannot open RFKILL control device
,08-16 15:27:02.253  1044  2018 I ActivityManager: Start proc com.lge.sync for broadcast com.lge.sync/.StartReceiver: pid=8397 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 15:27:02.256  8376  8396 W FormManager: Network not available. Please check & try again.
08-16 15:27:02.264   353   353 I art     : Explicit concurrent mark sweep GC freed 709(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 453us total 15.414ms
08-16 15:27:02.269  8376  8404 V FormManager: Network unavailable.
,08-16 15:27:02.276  8376  8404 V FormManager: Network unavailable.
08-16 15:27:02.277  8359  8359 I wpa_supplicant: [LGE_WLAN_PATCH]P2P 5GHz support level:2(0:no 1:gconly 2:gconly_UNII1 3:full)
08-16 15:27:02.282  8359  8359 I wpa_supplicant: p2p0: CTRL-EVENT-AVOID-FREQ ranges=
,08-16 15:27:02.282  8359  8359 I wpa_supplicant: wlan0: CTRL-EVENT-SCAN-STARTED 
08-16 15:27:02.284  1044  1525 E WifiStateMachine:  SupplicantStartingState CMD_SET_OPERATIONAL_MODE 1 0
08-16 15:27:02.284  1044  1525 E WifiStateMachine:  SupplicantStartingState CMD_START_DRIVER 0 0
08-16 15:27:02.284  1044  1525 E WifiStateMachine:  SupplicantStartingState CMD_SET_HIGH_PERF_MODE 0 0
08-16 15:27:02.284  1044  8417 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-AVOID-FREQ ranges=]
08-16 15:27:02.284  1044  8417 D WifiMonitor: Dropping event because (p2p0) is stopped
08-16 15:27:02.284  1044  8417 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-SCAN-STARTED ]
08-16 15:27:02.284  1044  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=44 dispatchEvent: CTRL-EVENT-SCAN-STARTED 
08-16 15:27:02.284  1044  8417 E WifiMonitor: handleEvent 14  CTRL-EVENT-SCAN-STARTED 
08-16 15:27:02.284  1044  1525 E WifiStateMachine:  DefaultState CMD_SET_HIGH_PERF_MODE 0 0
08-16 15:27:02.284  1044  8417 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-SCAN-STARTED 
08-16 15:27:02.285  1044  1525 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 15:27:02.285  1044  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 15:27:02.285  1044  1525 E WifiStateMachine:  SupplicantStartingState CMD_TETHER_STATE_CHANGE 0 0
08-16 15:27:02.286  1044  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 15:27:02.286  1044  1525 E WifiStateMachine:  SupplicantStartingState SUP_CONNECTION_EVENT 0 0
08-16 15:27:02.286  1044  1525 D WifiNative-wlan0: doString: [DRIVER MACADDR]
08-16 15:27:02.286  1044  1525 D WifiNative-wlan0:    returned Macaddr = c4:9a:02:7f:fb:5d
08-16 15:27:02.286  1044  1525 D WifiStateMachine: MAC Addr from driver = c4:9a:02:7f:fb:5d
08-16 15:27:02.286  1044  1525 D WifiOffDelayIfNotUsed: setPowerSaveActivated(false)
08-16 15:27:02.287  1044  1525 E WifiStateMachine: Couldn't get getWiFiOffloadingIface : 
08-16 15:27:02.287  1044  1525 E WifiStateMachine: useWiFiOffloading() : false
08-16 15:27:02.287  1044  1525 E WifiStateMachine: CONFIG_LGE_WLAN_PATH : true
08-16 15:27:02.287  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:27:02.287  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:27:02.287  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:27:02.287  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:27:02.287  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [DISCONNECTED]
08-16 15:27:02.291   353   353 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 371us total 25.982ms
08-16 15:27:02.292  1044  1525 D WifiNative-wlan0: doBoolean: SET update_config 1
08-16 15:27:02.292  1044  1525 D WifiNative-wlan0: SET update_config 1: returned true
08-16 15:27:02.292  1044  1525 D WifiConfigStore: Loading config and enabling all networks 
08-16 15:27:02.292  1044  1525 D WifiNative-wlan0: doString: [LIST_NETWORKS]
08-16 15:27:02.292  1044  1525 D WifiNative-wlan0:    returned network id / ssid / bssid / flags 0	NG700	any	
08-16 15:27:02.293  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:27:02.294  1927  1927 D WfdService: Waiting for WifiP2p enabling
,08-16 15:27:02.296  1044  1525 E WifiConfigStore: readNetworkVariablesFromSupplicantFile key=psk
08-16 15:27:02.297  1044  1044 I WifiServerServiceExt: WIFI_STATE_CHANGED_ACTION [3]
,08-16 15:27:02.297  1044  1529 I WifiServerServiceExt: batteryPsActivateMsgHandler : state:0 event:3
08-16 15:27:02.301  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:27:02.301  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:27:02.301  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:27:02.301  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:27:02.301  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:27:02.301  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:27:02.301  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:27:02.301  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:27:02.302  6974  6974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:27:02.303  1044  1525 E WifiConfigStore: readNetworkVariableFromSupplicantFile ssid=["NG700"] key=psk
08-16 15:27:02.303  1044  1525 E WifiConfigStore: Error parsing configuration: java.io.FileNotFoundException: /data/misc/wifi/ipconfig.txt: open failed: ENOENT (No such file or directory)
08-16 15:27:02.303  1044  1525 D WifiStateMachine: enableVerboseLogging : level 2
08-16 15:27:02.303  1044  1525 D WifiNative-wlan0: doBoolean: SET device_name g3_global_com
08-16 15:27:02.304  1044  1525 D WifiNative-wlan0: SET device_name g3_global_com: returned true
08-16 15:27:02.304  1044  1525 D WifiNative-wlan0: doBoolean: SET manufacturer LGE
08-16 15:27:02.304  1044  1525 D WifiNative-wlan0: SET manufacturer LGE: returned true
08-16 15:27:02.304  1044  1525 D WifiNative-wlan0: doBoolean: SET model_name LG-D855
08-16 15:27:02.305  1044  1525 D WifiNative-wlan0: SET model_name LG-D855: returned true
08-16 15:27:02.305  1044  1525 D WifiNative-wlan0: doBoolean: SET model_number LG-D855
08-16 15:27:02.305  1044  1525 D WifiNative-wlan0: SET model_number LG-D855: returned true
08-16 15:27:02.305  1044  1525 D WifiNative-wlan0: doBoolean: SET serial_number LGD855a6933058
08-16 15:27:02.305  1044  1525 D WifiNative-wlan0: SET serial_number LGD855a6933058: returned true
08-16 15:27:02.305  1044  1525 D WifiNative-wlan0: doBoolean: SET config_methods physical_display virtual_push_button
,08-16 15:27:02.306  1044  1525 D WifiNative-wlan0: SET config_methods physical_display virtual_push_button: returned true
08-16 15:27:02.306  1044  1525 D WifiNative-wlan0: doBoolean: SET device_type 10-0050F204-5
08-16 15:27:02.306  1044  1525 D WifiNative-wlan0: SET device_type 10-0050F204-5: returned true
08-16 15:27:02.307   353   353 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 283us total 15.301ms
08-16 15:27:02.307  1927  1927 D WfdsService: Supplicant Connection state is changed : true
08-16 15:27:02.307  1927  2207 D WfdsService: DefaultState - WIFI_SUPPLICANT_CONNECTED
08-16 15:27:02.307  1044  1525 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 15:27:02.307  1927  2207 D WfdsService: Set the WFDS Monitor: true
08-16 15:27:02.307  1044  1525 D WifiNative-wlan0: doBoolean: SCAN_INTERVAL 120
08-16 15:27:02.307  1927  2207 D WfdsMonitor: WfdsMonitorThread create
,08-16 15:27:02.307  1927  2207 D WfdsMonitor: WFDS Monitor is created and started
08-16 15:27:02.307  1927  2207 D WfdsService: WiFi: Supplicant connection re-established
08-16 15:27:02.308  1044  1525 D WifiNative-wlan0: SCAN_INTERVAL 120: returned true
08-16 15:27:02.308  1044  1525 D WifiNative-HAL: Setting external_sim to 1
08-16 15:27:02.308  1044  1525 D WifiNative-wlan0: doBoolean: SET external_sim 1
08-16 15:27:02.308  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:27:02.308  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:27:02.308  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:27:02.308  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:27:02.308  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:27:02.308  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: null
08-16 15:27:02.308  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: false
08-16 15:27:02.308  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: false
08-16 15:27:02.308  1044  1525 D WifiNative-wlan0: SET external_sim 1: returned true
08-16 15:27:02.308  1044  1525 I WifiNative-HAL: startHal
08-16 15:27:02.308  1044  1525 D wifi    : setting scan oui 0xaf6fc200
08-16 15:27:02.308  1044  1525 D WifiStateMachine: Setting OUI to DA-A1-19
08-16 15:27:02.308  1044  1525 I WifiNative-HAL: startHal
08-16 15:27:02.308  1044  1525 D wifi    : setting scan oui 0xaf6fc200
08-16 15:27:02.308  1044  1525 D WifiNative-wlan0: doBoolean: STA_AUTOCONNECT 1
08-16 15:27:02.309  1044  1525 D WifiNative-wlan0: STA_AUTOCONNECT 1: returned true
08-16 15:27:02.309  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXSCAN-STOP
08-16 15:27:02.309  1927  8418 E CtrlSupplicant: Access OK "@android:wpa_wlan0"
08-16 15:27:02.309  8359  8359 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXSCAN-STOP
08-16 15:27:02.309  1044  1525 D WifiNative-wlan0: DRIVER BTCOEXSCAN-STOP: returned true
08-16 15:27:02.309  6974  6974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: null
08-16 15:27:02.309  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 15:27:02.309  1927  8418 E CtrlSupplicant: Succeed to open control connection
08-16 15:27:02.309  8359  8359 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 15:27:02.309  1927  8418 E CtrlSupplicant: Succeed to open monitor connection
08-16 15:27:02.309  1044  1525 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 15:27:02.309  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 3
08-16 15:27:02.309  8359  8359 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-REMOVE 3
08-16 15:27:02.309  1927  8418 D WfdsMonitor: Supplicant connection established
08-16 15:27:02.310  1927  2207 D WfdsService: Connected to the supplicant for wfds
08-16 15:27:02.310  1044  1525 D WifiNative-wlan0: DRIVER RXFILTER-REMOVE 3: returned true
08-16 15:27:02.310  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 15:27:02.310  8359  8359 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 15:27:02.310  1044  1525 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 15:27:02.310  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-STOP
08-16 15:27:02.310  8359  8359 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-STOP
08-16 15:27:02.310  1044  1525 D WifiNative-wlan0: DRIVER RXFILTER-STOP: returned true
08-16 15:27:02.310  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-REMOVE 2
08-16 15:27:02.310  8359  8359 I wpa_supplicant: android_multicast_filter_startstop : multicast filter set
08-16 15:27:02.310  1044  1525 D WifiNative-wlan0,: DRIVER RXFILTER-REMOVE 2: returned true
08-16 15:27:02.310  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER RXFILTER-START
08-16 15:27:02.310  8359  8359 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd RXFILTER-START
08-16 15:27:02.311  1044  1525 D WifiNative-wlan0: DRIVER RXFILTER-START: returned true
08-16 15:27:02.311  1044  1525 E WifiNative: : [383,322,330 us] RECONNECT  stack:logDbg - reconnect - enter - invokeEnterMethods - performTransitions
08-16 15:27:02.311  1044  1525 D WifiNative-wlan0: doBoolean: RECONNECT
08-16 15:27:02.311  7904  7904 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:27:02.311  1044  1525 D WifiNative-wlan0: RECONNECT: returned true
08-16 15:27:02.311  1044  1525 D WifiNative-wlan0: doString: [STATUS]
08-16 15:27:02.312  1044  8417 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=]
08-16 15:27:02.312  1044  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=45 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=3 BSSID=00:00:00:00:00:00 SSID=
08-16 15:27:02.312  1044  1525 D WifiNative-wlan0:    returned wpa_state=SCANNING p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 15:27:02.312  1044  1525 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 15:27:02.312  1044  1525 D WifiNative-wlan0: SET ps 1: returned true
08-16 15:27:02.312  1044  1524 D LGWifiP2pService: P2pDisabledState{ when=0 what=131203 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:02.313  1044  2018 I ActivityManager: Killing 7355:com.android.chrome/u0a57 (adj 15): empty #17
08-16 15:27:02.313   321   903 D CommandListener: Setting iface cfg
08-16 15:27:02.313   321   903 D CommandListener: Trying to bring up p2p0
08-16 15:27:02.314  1044  1524 D WifiMonitor: startMonitoring(p2p0) with mConnected = true
08-16 15:27:02.314  1044  1524 D LGWifiP2pService: P2pEnablingState
08-16 15:27:02.314  1044  1524 D LGWifiP2pService: P2pEnablingState{ when=0 what=147457 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:02.314  1044  1524 D LGWifiP2pService: P2p socket connection successful
08-16 15:27:02.314  1044  1524 D LGWifiP2pService: P2pEnabledState
08-16 15:27:02.325  8397  8397 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
,08-16 15:27:02.346  1044  1773 W libprocessgroup: failed to open /acct/uid_10057/pid_7355/cgroup.procs: No such file or directory
08-16 15:27:02.346  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
,08-16 15:27:02.348  1044  1524 D LGWifiP2pService: sending p2p connection changed broadcast
08-16 15:27:02.348  1044  1044 D WifiScanningService: SCAN_AVAILABLE : 3
08-16 15:27:02.348  1044  1044 D RttService: SCAN_AVAILABLE : 3
,08-16 15:27:02.349  1044  1544 D RttService: DefaultState got{ when=0 what=160512 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:02.349  1044  1543 D WifiScanningService: DefaultState got{ when=0 what=160006 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:02.349  1044  1543 I WifiNative-HAL: startHal
08-16 15:27:02.349  1044  1543 D wifi    : getting scan capabilities on interface[1] = 0xaf6fc200
08-16 15:27:02.349  1044  1543 D wifi    : failed to get capabilities : -3
08-16 15:27:02.349  1044  1543 E WifiScanningService: could not get scan capabilities
08-16 15:27:02.349  1927  1927 V WfdStateTracker: WfdStateTracker handleDirectStateChangedEvent: 2
08-16 15:27:02.349  1044  1524 D WifiNative-p2p0: doBoolean: SET persistent_reconnect 1
08-16 15:27:02.349  1927  1927 D WfdsService: WifiP2pState is changed : true
08-16 15:27:02.349  1044  1525 E WifiStateMachine:  DisconnectedState CMD_SET_OPERATIONAL_MODE 1 0
08-16 15:27:02.349  1044  1525 E WifiStateMachine:  DisconnectedState CMD_START_DRIVER 0 0
08-16 15:27:02.349  1044  1524 D WifiNative-p2p0: SET persistent_reconnect 1: returned true
08-16 15:27:02.349  1927  2207 D WfdsService: Receive the WFDS_ENABLE Method
08-16 15:27:02.350  1927  2207 D WfdsService: Set the WFDS Monitor: true
08-16 15:27:02.350  1044  1524 D WifiNative-p2p0: doBoolean: SET device_name G3
08-16 15:27:02.350  1927  2207 D WfdsService: Connected to the supplicant for wfds
08-16 15:27:02.350  1927  2207 D WfdsJNI : doCommand: WFDS_SET TRUE
08-16 15:27:02.350  1044  1525 E WifiStateMachine:  ConnectModeState CMD_START_DRIVER 0 0
08-16 15:27:02.350  8359  8359 I wpa_supplicant: WFDS: wfds_supplicant_wfds_cmd: cmd = SET TRUE
08-16 15:27:02.350  1044  1525 E WifiStateMachine:  DriverStartedState CMD_START_DRIVER 0 0
08-16 15:27:02.350  1927  2207 D WfdsService: selectPreferredScanChannel [36]
08-16 15:27:02.350  1927  2207 D WfdsService: STATE : WfdsEnabledState - enter: this device mac 02:9a:02:7f:fb:5d
08-16 15:27:02.350  1044  1525 E WifiStateMachine:  DisconnectedState what:132106 1 0
08-16 15:27:02.350  1044  1524 D WifiNative-p2p0: SET device_name G3: returned true
08-16 15:27:02.350  1044  1524 D LGWifiP2pService: [LGE_P2P] initializeP2pSettings() check postfix
08-16 15:27:02.350  1044  1524 D LGWifiP2pService: before postfix = G3
08-16 15:27:02.350  1044  1524 D WifiServerServiceExt: postfix byte check : 2
08-16 15:27:02.350  1044  1524 D LGWifiP2pService: after postfix = G3
08-16 15:27:02.350  1044  1524 D WifiNative-p2p0: doBoolean: SET p2p_ssid_postfix -G3
08-16 15:27:02.350  1044  1525 E WifiStateMachine:  ConnectModeState what:132106 1 0
08-16 15:27:02.350  1044  1525 E WifiStateMachine:  DriverStartedState what:132106 1 0
08-16 15:27:02.350  1044  1524 D WifiNative-p2p0: SET p2p_ssid_postfix -G3: returned true
08-16 15:27:02.350  1044  1525 I WifiServerServiceExt: setWifiDualbandAPConnection band : 1
08-16 15:27:02.351  8359  8359 E wpa_supplicant: nWIFIDualbandAPConnection: 1
08-16 15:27:02.351  1044  1524 D WifiNative-p2p0: doBoolean: SET device_type 10-0050F204-5
08-16 15:27:02.351  1044  1524 D WifiNative-p2p0: SET device_type 10-0050F204-5: returned true
08-16 15:27:02.351  1044  1524 D WifiNative-p2p0: doBoolean: SET config_methods virtual_push_button physical_display keypad
08-16 15:27:02.351  1044  1524 D WifiNative-p2p0: SET config_methods virtual_push_button physical_display keypad: returned true
08-16 15:27:02.351  1044  1524 D WifiNative-p2p0: doBoolean: P2P_SET conc_pref p2p
,08-16 15:27:02.351  1927  1927 D WfdsService: WIFI_P2P_CONNECTION_CHANGED_ACTION
,08-16 15:27:02.351  1044  1524 D WifiNative-p2p0: P2P_SET conc_pref p2p: returned true
08-16 15:27:02.352  1044  1524 D WifiNative-HAL: p2pGetDeviceAddress
08-16 15:27:02.352  1044  1524 D WifiNative-HAL: p2pGetDeviceAddress returning 
08-16 15:27:02.352  1927  1927 D WfdsService: isConnected: false
08-16 15:27:02.352  1044  1524 D LGWifiP2pService: DeviceAddress: 
08-16 15:27:02.352  1044  1524 D WifiNative-p2p0: doBoolean: P2P_FLUSH
08-16 15:27:02.352  1044  1524 D WifiNative-p2p0: P2P_FLUSH: returned true
08-16 15:27:02.352  1044  1525 E WifiStateMachine:  DisconnectedState what:132096 -100 0
08-16 15:27:02.352  1927  1927 I WfdStateTracker: handleP2pThisDeviceChanged
08-16 15:27:02.352  1044  1524 D WifiNative-p2p0: doBoolean: P2P_SERVICE_FLUSH
08-16 15:27:02.353  1927  1927 D WfdsService: WIFI_P2P_THIS_DEVICE_CHANGED_ATCION
08-16 15:27:02.353  1927  1927 D WfdsService: Update P2p Interface State: 3
08-16 15:27:02.353  1044  1525 E WifiStateMachine:  ConnectModeState what:132096 -100 0
08-16 15:27:02.353  1044  1525 E WifiStateMachine:  DriverStartedState what:132096 -100 0
08-16 15:27:02.353  1044  1525 I WifiServerServiceExt: set CMD_DISCONNECT_RSSI_LVL : -100
08-16 15:27:02.353  8359  8359 E wpa_supplicant: disconnect_rssi_lvl: -100
08-16 15:27:02.353  1044  1524 D WifiNative-p2p0: P2P_SERVICE_FLUSH: returned true
08-16 15:27:02.353  1044  1524 D WifiNative-p2p0: doString: [LIST_NETWORKS]
08-16 15:27:02.353  1044  1525 E WifiStateMachine:  DisconnectedState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 15:27:02.353  1044  1524 D WifiNative-p2p0:    returned network id / ssid / bssid / flags
08-16 15:27:02.354  1044  1524 D WifiNative-p2p0: doBoolean: SAVE_CONFIG
08-16 15:27:02.354  1044  1525 E WifiStateMachine:  ConnectModeState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 15:27:02.355  1044  1525 E WifiStateMachine:  DriverStartedState CMD_SET_COUNTRY_CODE 3 0 cz
08-16 15:27:02.355  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER COUNTRY CZ
08-16 15:27:02.356  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:27:02.357  1044  1059 I ActivityManager: Killing 7378:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-16 15:27:02.370  1044  1524 D WifiNative-p2p0: SAVE_CONFIG: returned true
08-16 15:27:02.370  1044  1524 D LGWifiP2pService: sending p2p persistent groups changed broadcast
08-16 15:27:02.371  8359  8359 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 15:27:02.371  8359  8359 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 15:27:02.371  1044  8417 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 15:27:02.371  1044  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=46 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
,08-16 15:27:02.371  1044  8417 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 15:27:02.371  1044  8417 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 15:27:02.372  8359  8359 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 15:27:02.372  8359  8359 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:27:02.372  1044  8417 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 15:27:02.372  1044  8417 E WifiMonitor: WifiMonitor:p2p0 cnt=47 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:27:02.372  1044  8417 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:27:02.372  1044  8417 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:27:02.372  8359  8359 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:27:02.372  1044  8417 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 15:27:02.372  1044  8417 E WifiMonitor: WifiMonitor:p2p0 cnt=48 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
,08-16 15:27:02.373  1044  8417 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:27:02.373  1044  8417 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:27:02.373  1044  1525 D WifiNative-wlan0: DRIVER COUNTRY CZ: returned true
08-16 15:27:02.374  1044  1525 E WifiStateMachine:  DisconnectedState CMD_SET_FREQUENCY_BAND 0 0
08-16 15:27:02.374  1927  8418 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 15:27:02.374  1927  8418 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 15:27:02.374  1044  1525 E WifiStateMachine:  ConnectModeState CMD_SET_FREQUENCY_BAND 0 0
08-16 15:27:02.375  1044  1525 E WifiStateMachine:  DriverStartedState CMD_SET_FREQUENCY_BAND 0 0
08-16 15:27:02.375  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER SETBAND 0
08-16 15:27:02.375  8359  8359 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETBAND 0 - interface name wlan0
08-16 15:27:02.375  8359  8359 I wpa_supplicant: wlan0: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-16 15:27:02.375  1044  8417 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN]
08-16 15:27:02.375  1044  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=49 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 15:27:02.375  1044  8417 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
08-16 15:27:02.375  1044  8417 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=CORE type=UNKNOWN
,08-16 15:27:02.376  1044  1525 D WifiNative-wlan0: DRIVER SETBAND 0: returned true
08-16 15:27:02.376  1044  1525 D WifiNative-wlan0: doBoolean: BSS_FLUSH 0
,08-16 15:27:02.377  1044  1525 D WifiNative-wlan0: BSS_FLUSH 0: returned true
08-16 15:27:02.377  1044  1525 D WifiNative-wlan0: doBoolean: SCAN
08-16 15:27:02.377  1044  1525 D WifiNative-wlan0: SCAN: returned false
08-16 15:27:02.378  1044  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=383389  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 15:27:02.386  1044  1942 W libprocessgroup: failed to open /acct/uid_10062/pid_7378/cgroup.procs: No such file or directory
08-16 15:27:02.388  1044  1524 D LGWifiP2pService: InactiveState
,08-16 15:27:02.388  1044  1524 D LGWifiP2pService: InactiveState{ when=-35ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:02.388  1044  1524 D LGWifiP2pService: P2pEnabledState{ when=-35ms what=143376 obj=cz target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:02.388  1044  1524 D WifiNative-p2p0: doBoolean: DRIVER COUNTRY CZ
08-16 15:27:02.389  8359  8359 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd COUNTRY CZ
08-16 15:27:02.390  8359  8359 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 15:27:02.390  1044  8417 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 15:27:02.390  1044  8417 E WifiMonitor: WifiMonitor:p2p0 cnt=50 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 15:27:02.390  1044  8417 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 15:27:02.390  1044  8417 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ
08-16 15:27:02.390  8359  8359 I wpa_supplicant: [LGE_PATCH] driver_cmd() country:CZ
08-16 15:27:02.390  8359  8359 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:27:02.390  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: <unknown ssid>, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:27:02.390  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 15:27:02.391  8359  8359 I wpa_supplicant: p2p0: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:27:02.391  1044  1524 D WifiNative-p2p0: DRIVER COUNTRY CZ: returned true
08-16 15:27:02.391  1044  1524 D LGWifiP2pService: InactiveState{ when=-18ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:02.391  1044  1524 D LGWifiP2pService: P2pEnabledState{ when=-18ms what=143376 obj=CZ target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:02.391  1044  1524 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:02.391  1044  1524 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:02.391  1044  1524 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:02.391  1927  8418 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=USER type=COUNTRY alpha2=CZ]
08-16 15:27:02.391  1044  1524 D LGWifiP2pService: InactiveState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:02.391  1044  1524 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:02.391  1927  8418 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 15:27:02.391  1044  1524 D LGWifiP2pService: DefaultState{ when=-3ms what=139285 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:02.391  1927  8418 D WfdsMonitor: Event [CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 15:27:02.391  1044  1524 D LGWifiP2pService: InactiveState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:02.392  1044  1524 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:02.392  1044  1524 D LGWifiP2pService: DefaultState{ when=-3ms what=139287 arg2=5 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:02.392  1044  1524 D LGWifiP2pService: InactiveState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:02.392  1044  1524 D LGWifiP2pService: P2pEnabledState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:02.392  1044  1524 D LGWifiP2pService: DefaultState{ when=-3ms what=139283 arg2=6 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:02.392  1044  8417 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 15:27:02.392  1044  1044 E WifiServerServiceExt: No p2p device connected
08-16 15:27:02.392  1044  8417 E WifiMonitor: WifiMonitor:p2p0 cnt=51 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:27:02.392  1927  2207 W WfdsService: DefaultState - msg [9441285] is not handled
08-16 15:27:02.392  1044  8417 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:27:02.392  1044  8417 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:27:02.392  1044  8417 D WifiMonitor: Event [IFNAME=p2p0 CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD]
08-16 15:27:02.392  1044  8417 E WifiMonitor: WifiMonitor:p2p0 cnt=52 dispatchEvent: CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:27:02.392  1044  8417 E WifiMonitor: handleEvent 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:27:02.392  1044  8417 E WifiMonitor: handleEvent unknown: 14  CTRL-EVENT-REGDOM-CHANGE init=DRIVER type=WORLD
08-16 15:27:02.392  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:27:02.392  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Sett,ings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:27:02.392  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 15:27:02.392  1044  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 45 0 rt=383404  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: SCANNING
08-16 15:27:02.393  1044  1525 E WifiStateMachine:  DisconnectedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 15:27:02.393  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:27:02.393  1044  1525 E WifiStateMachine:  ConnectModeState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 15:27:02.394  1044  1525 E WifiStateMachine:  DriverStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 15:27:02.394  1044  1525 E WifiStateMachine:  SupplicantStartedState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 15:27:02.395  1044  1525 E WifiStateMachine:  DefaultState P2P_CONNECTION_CHANGED uid=1000 0 0 st=UNKNOWN/IDLE
08-16 15:27:02.395  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 15:27:02.395  1044  1044 D WifiServerServiceExt: setSupplicantStateSCANNING
08-16 15:27:02.399  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 15:27:02.399  7091  7091 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 15:27:02.399  7091  7091 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 15:27:02.399  7091  7091 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 15:27:02.399  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
08-16 15:27:02.400  7091  7091 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
08-16 15:27:02.400  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[]
08-16 15:27:02.400  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 15:27:02.400  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 15:27:02.400  7091  7091 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 15:27:02.400  7091  7091 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
,08-16 15:27:02.408  8397  8397 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]false, [HOTSPOT]false, [OBEXSERVICE]false
08-16 15:27:02.409  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.WIFI_STATE_CHANGED
08-16 15:27:02.411  8376  8422 W FormManager: Network not available. Please check & try again.
08-16 15:27:02.413  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 15:27:02.426  8376  8423 V FormManager: Network unavailable.
,08-16 15:27:02.429  8376  8423 V FormManager: Network unavailable.
,08-16 15:27:02.433  4739  4739 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 15:27:02.433  4739  4739 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 15:27:02.435  4739  4739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 15:27:02.437  4739  4739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 15:27:02.443  4739  8424 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
,08-16 15:27:02.445  4739  8425 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.wifi.supplicant.CONNECTION_CHANGE
08-16 15:27:02.445  4739  8425 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 15:27:02.502  1044  2009 I ActivityManager: Start proc com.lge.bnr for broadcast com.lge.bnr/.service.BNRBootReceiver: pid=8426 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi
,08-16 15:27:02.625  8426  8426 V [BNRBootReceiver]: boot receiver action = android.net.wifi.p2p.CONNECTION_STATE_CHANGE
08-16 15:27:02.626  8426  8426 D BNRAndroBeam: [BnR DirectBeam] Android Direct Beam(NFC) Connection changed
,08-16 15:27:02.635  8426  8426 V [BNRBootReceiver]: Boot Receiver Return
08-16 15:27:02.636  8426  8426 W MainApplication: onReceive intent : Intent { act=android.intent.action.BATTERY_CHANGED flg=0x60000010 (has extras) }
08-16 15:27:02.699  1044  2036 I ActivityManager: Start proc com.wsandroid.suite.lge for broadcast com.wsandroid.suite.lge/com.wavesecure.core.WSAndroidSystemIntentReceiver: pid=8444 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 15:27:02.701  1044  2036 I ActivityManager: Killing 7396:com.lge.sizechangable.weather/u0a85 (adj 15): empty #17
,08-16 15:27:02.746  1044  2018 W libprocessgroup: failed to open /acct/uid_10085/pid_7396/cgroup.procs: No such file or directory
,08-16 15:27:02.792  8444  8444 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 15:27:02.819  8444  8444 D PluginManager: init()
,08-16 15:27:02.869  1044  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=53 dispatchEvent: CTRL-EVENT-SCAN-RESULTS 
,08-16 15:27:02.869  1044  8417 E WifiMonitor: handleEvent 4  CTRL-EVENT-SCAN-RESULTS 
08-16 15:27:02.869  1044  8417 D WifiMonitor: Event [IFNAME=wlan0 WPS-AP-AVAILABLE ]
08-16 15:27:02.869  1044  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=54 dispatchEvent: WPS-AP-AVAILABLE 
08-16 15:27:02.869  1044  8417 W WifiMonitor: couldn't identify event type - WPS-AP-AVAILABLE 
08-16 15:27:02.870  8359  8359 E wpa_supplicant: USIM:  scard_init function
08-16 15:27:02.871  1044  1525 E WifiStateMachine:  DisconnectedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-16 15:27:02.871  8359  8359 I wpa_supplicant: Trying to associate with SSID 'NG700'
,08-16 15:27:02.872  1044  1525 E WifiStateMachine:  ConnectModeState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-16 15:27:02.873  1044  1525 E WifiStateMachine:  DriverStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
,08-16 15:27:02.874  1044  8417 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=]
,08-16 15:27:02.874  1044  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=55 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=-1 state=5 BSSID=00:00:00:00:00:00 SSID=
08-16 15:27:02.875  1044  1525 E WifiStateMachine:  SupplicantStartedState SCAN_RESULTS_EVENT 0 0 found=0 known=0 got=10 bcn=0
08-16 15:27:02.875  1044  1525 D WifiNative-wlan0: doString: [BSS RANGE=0- MASK=0x21987]
08-16 15:27:02.891  1044  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=383902  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
,08-16 15:27:02.899  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: DISCONNECTED/SCANNING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:27:02.899  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 15:27:02.900  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:27:02.900  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:27:02.900  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [SCANNING]
08-16 15:27:02.901  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:27:02.908  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:27:02.908  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:27:02.908  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 15:27:02.909  1044  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 55 0 rt=383920  SSID:  BSSID: 00:00:00:00:00:00 nid: -1 state: ASSOCIATING
08-16 15:27:02.910  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 15:27:02.910  1044  1044 D WifiServerServiceExt: setSupplicantStateASSOCIATING
,08-16 15:27:02.921  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: 0x, roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:27:02.921  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 15:27:02.922  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 15:27:02.993  8359  8359 I wpa_supplicant: wlan0: Associated with f4:f2:6d:22:99:3e
,08-16 15:27:02.993  1044  8417 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700]
08-16 15:27:02.993  1044  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=56 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=6 BSSID=00:00:00:00:00:00 SSID=NG700
08-16 15:27:02.994  1044  8417 D WifiMonitor: Event [IFNAME=wlan0 Associated with f4:f2:6d:22:99:3e]
08-16 15:27:02.994  1044  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=57 dispatchEvent: Associated with f4:f2:6d:22:99:3e
08-16 15:27:02.994  1044  8417 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 15:27:02.994  1044  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=58 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=7 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 15:27:02.995  1044  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=384006  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 15:27:02.995  1044  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 56 0 rt=384007  SSID: NG700 BSSID: 00:00:00:00:00:00 nid: 0 state: ASSOCIATED
08-16 15:27:02.996  1044  1525 E WifiStateMachine:  DisconnectedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=384007
08-16 15:27:02.996  1044  1525 E WifiStateMachine:  ConnectModeState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=384007
08-16 15:27:02.997  1044  1525 E WifiStateMachine:  DriverStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=384008
08-16 15:27:02.997  1044  1525 E WifiStateMachine:  SupplicantStartedState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=384008
08-16 15:27:02.997  1044  1525 E WifiStateMachine:  DefaultState CMD_ASSOCIATED_BSSID 57 0 BSSID=f4:f2:6d:22:99:3e Target=any roam=0 rt=384008
08-16 15:27:02.998  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 15:27:02.998  1044  1044 D WifiServerServiceExt: setSupplicantStateASSOCIATED
08-16 15:27:02.999  1044  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=384010  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 15:27:03.002  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:27:03.002  8359  8359 I wpa_supplicant: wlan0: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 15:27:03.002  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:27:03.002  8359  8359 I wpa_supplicant: wlan0: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 15:27:03.002  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTING]
08-16 15:27:03.002  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CONNECTING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:27:03.003  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 15:27:03.003  1044  1119 D Tethering: sendTetherStateChangedBroadcast 1, 0, 0
08-16 15:27:03.003  1044  8417 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 15:27:03.003  1044  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=59 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=8 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 15:27:03.004  1044  8417 D WifiMonitor: Event [IFNAME=wlan0 WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]]
08-16 15:27:03.004  1044  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=60 dispatchEvent: WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 15:27:03.004  1044  8417 W W,ifiMonitor: couldn't identify event type - WPA: Key negotiation completed with f4:f2:6d:22:99:3e [PTK=CCMP GTK=CCMP]
08-16 15:27:03.004  1044  8417 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]]
08-16 15:27:03.004  1044  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=61 dispatchEvent: CTRL-EVENT-CONNECTED - Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 15:27:03.004  1044  8417 E WifiMonitor: handleEvent 1  Connection to f4:f2:6d:22:99:3e completed [id=0 id_str=]
08-16 15:27:03.005  1044  8417 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 15:27:03.005  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:27:03.005  1044  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=62 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
,08-16 15:27:03.009  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:27:03.009  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:27:03.009  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [AUTHENTICATING]
08-16 15:27:03.010  1044  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 58 0 rt=384021  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: FOUR_WAY_HANDSHAKE
08-16 15:27:03.010  1044  1525 E WifiStateMachine:  DisconnectedState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=384021  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 15:27:03.011  1044  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 59 0 rt=384022  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: GROUP_HANDSHAKE
08-16 15:27:03.011  1044  1525 E WifiStateMachine:  DisconnectedState CMD_TETHER_STATE_CHANGE 0 0
08-16 15:27:03.011  1044  1525 E WifiStateMachine:  ConnectModeState CMD_TETHER_STATE_CHANGE 0 0
08-16 15:27:03.012  1044  1525 E WifiStateMachine:  DriverStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 15:27:03.012  1044  1525 E WifiStateMachine:  SupplicantStartedState CMD_TETHER_STATE_CHANGE 0 0
08-16 15:27:03.012  1044  1525 E WifiStateMachine:  DefaultState CMD_TETHER_STATE_CHANGE 0 0
08-16 15:27:03.012  1044  1525 E WifiStateMachine:  DisconnectedState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=384023
08-16 15:27:03.013  1044  1525 E WifiStateMachine:  ConnectModeState NETWORK_CONNECTION_EVENT 0 0 null nid=-1 rt=384024
08-16 15:27:03.013  1044  1525 D WifiNative-wlan0: doString: [STATUS]
08-16 15:27:03.013  1044  8417 D WifiMonitor: Event [IFNAME=wlan0 CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700]
08-16 15:27:03.013  1044  1525 D WifiNative-wlan0:    returned bssid=f4:f2:6d:22:99:3e ssid=NG700 id=0 mode=station pairwise_cipher=CCMP group_cipher=CCMP key_mgmt=WPA2-PSK wpa_state=COMPLETED p2p_device_address=02:9a:02:7f:fb:5d address=c4:9a:02:7f:fb:5d uuid=db50a6cb-8457-5827-b861-ec7a05ef48b4
08-16 15:27:03.013  1044  8417 E WifiMonitor: WifiMonitor:wlan0 cnt=63 dispatchEvent: CTRL-EVENT-STATE-CHANGE id=0 state=9 BSSID=f4:f2:6d:22:99:3e SSID=NG700
08-16 15:27:03.015  1044  1525 I WifiServiceExtension: setVHTCapabilityType  : false
08-16 15:27:03.025  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/AUTHENTICATING, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:27:03.025  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 15:27:03.026  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 15:27:03.111  1044  1525 I WifiServerServiceExt: wifiInfo ==> Freq: 0, DevMode: station, KeyMgmt: WPA2-PSK, Cipher: CCMP, EAPMETHOD: empty, SECTYPE: WPA2-PSK
,08-16 15:27:03.111  1044  1525 I WifiServerServiceExt: setKeepAlivePacketInterval msec : 60
08-16 15:27:03.118  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:27:03.118  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 15:27:03.119  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:27:03.122  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 15:27:03.122  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:27:03.123  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 15:27:03.128  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:27:03.128  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:27:03.128  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [OBTAINING_IPADDR]
08-16 15:27:03.139  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:27:03.139  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
,08-16 15:27:03.140  1044  1525 D ConnectivityService: registerNetworkAgent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTING/OBTAINING_IPADDR, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{null}  lp{{LinkAddresses: []  Routes: [] DnsAddresses: [] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{false} explicitlySelected{false} }
08-16 15:27:03.140  1044  1531 D ConnectivityService: Got NetworkAgent Messenger
08-16 15:27:03.140  1044  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from null to CONNECTING
08-16 15:27:03.140  1044  1531 D ConnectivityService: NetworkAgent connected
08-16 15:27:03.140  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:27:03.140  1044  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 15:27:03.140  1044  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-16 15:27:03.144  1044  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 15:27:03.144  1044  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 15:27:03.150  1044  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 15:27:03.150  1044  1525 E WifiConfigStore: saveWifiConfigBSSID Setting BSSID for "NG700"WPA_PSK to any
08-16 15:27:03.150  1044  1525 D WifiNative-wlan0: doBoolean: SET_NETWORK 0 bssid any
,08-16 15:27:03.154  1044  1525 D WifiNative-wlan0: SET_NETWORK 0 bssid any: returned true
08-16 15:27:03.154  1044  1525 D WifiNative-wlan0: doBoolean: SAVE_CONFIG
08-16 15:27:03.157  1044  1525 D WifiNative-wlan0: SAVE_CONFIG: returned true
08-16 15:27:03.157   321   903 D CommandListener: Setting iface cfg
08-16 15:27:03.159  1044  1525 E WifiStateMachine: Start Dhcp Watchdog 3
08-16 15:27:03.159  1044  8471 D DhcpStateMachine: StoppedState
08-16 15:27:03.159  1044  8471 D DhcpStateMachine: StoppedState{ when=0 what=196609 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:03.160  1044  8471 D DhcpStateMachine: WaitBeforeStartState
08-16 15:27:03.160  1044  1525 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=384171  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 15:27:03.160  1044  1525 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=384171  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 15:27:03.160  1044  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 62 0 rt=384171  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 15:27:03.161  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 15:27:03.161  1044  1044 D WifiServerServiceExt: setSupplicantStateFOUR_WAY_HANDSHAKE
08-16 15:27:03.161  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 15:27:03.161  1044  1044 D WifiServerServiceExt: setSupplicantStateGROUP_HANDSHAKE
08-16 15:27:03.162  1044  1525 E WifiStateMachine:  ObtainingIpState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=384173  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
,08-16 15:27:03.162  1044  1525 E WifiStateMachine:  L2ConnectedState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=384173  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 15:27:03.162  1044  1525 E WifiStateMachine:  ConnectModeState SUPPLICANT_STATE_CHANGE_EVENT 63 0 rt=384173  SSID: NG700 BSSID: f4:f2:6d:22:99:3e nid: 0 state: COMPLETED
08-16 15:27:03.163  1044  1525 E WifiStateMachine:  ObtainingIpState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:24403] from screen [on:0 period:-1819759365] gl rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 15:27:03.164  1044  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-127 f=-1 sc=0 link=-1 tx=0.0, 0.0, 0.0  rx=0.0 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1819759364] gl rssi=-53 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 15:27:03.164  1044  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 15:27:03.167  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:27:03.167  1044  1531 D ConnectivityService: updateNetworkScore for NetworkAgentInfo [WIFI () - 102] to 60
08-16 15:27:03.167  1044  1525 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 15:27:03.167  1044  1525 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 15:27:03.167  1044  1525 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 15:27:03.168  1044  1525 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 15:27:03.168  1044  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 15:27:03.168  1044  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0
08-16 15:27:03.168  1044  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 15:27:03.168  1044  1525 E WifiStateMachine:  ObtainingIpState CMD_PRE_DHCP_ACTION 0 0 txpkts=164,0,0
08-16 15:27:03.169  1044  1525 E WifiStateMachine:  L2ConnectedState CMD_PRE_DHCP_ACTION 0 0 txpkts=164,0,0
08-16 15:27:03.169  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 0
08-16 15:27:03.169  8359  8359 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 0
08-16 15:27:03.169  1044  1525 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 0: returned true
08-16 15:27:03.169  1044  1525 D WifiNative-wlan0: doBoolean: SET ps 0
08-16 15:27:03.169  1044  1525 D WifiNative-wlan0: SET ps 0: returned true
08-16 15:27:03.169  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 1
08-16 15:27:03.169  8359  8359 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 1
08-16 15:27:03.170  1044  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 1: returned true
08-16 15:27:03.170  1044  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@249c4842 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:03.170  1044  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 arg1=1 arg2=196615 obj=android.net.DhcpStateMachine@249c4842 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:03.170  1044  1525 E WifiStateMachine: CheckDhcpInfoCacheList : DhcpStateMachine.CMD_PRE_DHCP_ACTION[ConnectingState]
08-16 15:27:03.170  1044  1525 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 15:27:03.170  1044  1525 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 15:27:03.170  1044  8471 D DhcpStateMachine: WaitBeforeStartState{ when=-1ms what=196615 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:03.170  1044  8471 D DhcpStateMachine: DHCP Start wake lock is acquired.
08-16 15:27:03.171   321   903 D CommandListener: Setting iface cfg
08-16 15:27:03.171   321   903 D CommandListener: Trying to bring up wlan0
08-16 15:27:03.171  1044  152,5 V LgDhcpStateMachineHelper: setInterfaceUpWithDhcpInfo: IP configuration succeeded: IP address 192.168.1.135/24 Gateway 192.168.1.1  DNS servers: [ 192.168.1.1 ] Domains DHCP server /192.168.1.1 Vendor info  lease 172800 seconds
08-16 15:27:03.172  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 15:27:03.172  1044  1044 D WifiServerServiceExt: setSupplicantStateCOMPLETED
08-16 15:27:03.173  1044  1044 D WifiServerServiceExt: SUPPLICANT_STATE_CHANGED_ACTION
08-16 15:27:03.173  1044  1044 D WifiServerServiceExt: setSupplicantStateCOMPLETED
,08-16 15:27:03.174  1044  1525 E WifiStateMachine:  ObtainingIpState CMD_POST_DHCP_ACTION 1 0 OK 
08-16 15:27:03.175  1044  1525 E WifiStateMachine:  L2ConnectedState CMD_POST_DHCP_ACTION 1 0 OK 
,08-16 15:27:03.175  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER BTCOEXMODE 2
08-16 15:27:03.175  1044  1524 D LGWifiP2pService: InactiveState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:03.175  8359  8359 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd BTCOEXMODE 2
08-16 15:27:03.176  1044  1525 D WifiNative-wlan0: DRIVER BTCOEXMODE 2: returned true
08-16 15:27:03.176  1044  1525 D WifiNative-wlan0: doBoolean: DRIVER SETSUSPENDMODE 1
08-16 15:27:03.176  1044  1524 D LGWifiP2pService: P2pEnabledState{ when=0 what=143375 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:03.176  8359  8359 I wpa_supplicant: wpa_driver_nl80211_ext_driver_cmd SETSUSPENDMODE 1
08-16 15:27:03.177  1044  1525 D WifiNative-wlan0: DRIVER SETSUSPENDMODE 1: returned true
08-16 15:27:03.177  1044  1525 D WifiNative-wlan0: doBoolean: SET ps 1
08-16 15:27:03.196  1044  1525 D WifiNative-wlan0: SET ps 1: returned true
08-16 15:27:03.197  1044  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 15:27:03.197  1044  1525 E WifiStateMachine:  ObtainingIpState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 15:27:03.198  1044  1525 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-16 15:27:03.198  1044  1525 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 15:27:03.199  1044  1525 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 15:27:03.199  1044  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 15:27:03.200  1044  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 15:27:03.201  1044  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=false
08-16 15:27:03.201  1044  1525 E WifiStateMachine:  ObtainingIpState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 15:27:03.202  1044  1525 E WifiStateMachine:  L2ConnectedState CMD_IP_CONFIGURATION_SUCCESSFUL 0 0
08-16 15:27:03.202  1044  1525 E WifiStateMachine: WifiStateMachine: handleSuccessfulIpConfiguration and no scan results"NG700"WPA_PSK
08-16 15:27:03.203  1044  1531 D ConnectivityService: ignoring duplicate network state non-change
08-16 15:27:03.206  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:27:03.206  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 15:27:03.208  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:27:03.214  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:27:03.214  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:27:03.215  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
,08-16 15:27:03.217  1044  1531 D ConnectivityService: NetworkAgentInfo [WIFI () - 102] EVENT_NETWORK_INFO_CHANGED, going from CONNECTING to CONNECTED
08-16 15:27:03.219  1044  1531 D ConnectivityService: Adding iface wlan0 to network 102
08-16 15:27:03.219  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:27:03.219  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:27:03.219  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CAPTIVE_PORTAL_CHECK]
08-16 15:27:03.219  8444  8444 W ExternalStrings: load override strings
08-16 15:27:03.219  8444  8444 W ExternalStrings: java.lang.RuntimeException: Unexpected tag, got eat-comment
08-16 15:27:03.219  8444  8444 W ExternalStrings: 	at com.mcafee.plugin.af.a(Unknown Source)
08-16 15:27:03.219  8444  8444 W ExternalStrings: 	at com.mcafee.plugin.ac.b(Unknown Source)
08-16 15:27:03.219  8444  8444 W ExternalStrings: 	at com.mcafee.plugin.ak.d(Unknown Source)
08-16 15:27:03.219  8444  8444 W ExternalStrings: 	at com.mcafee.plugin.ak.a(Unknown Source)
08-16 15:27:03.219  8444  8444 W ExternalStrings: 	at com.mcafee.app.s.getClassLoader(Unknown Source)
08-16 15:27:03.219  8444  8444 W ExternalStrings: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5001)
08-16 15:27:03.219  8444  8444 W ExternalStrings: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-16 15:27:03.219  8444  8444 W ExternalStrings: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-16 15:27:03.219  8444  8444 W ExternalStrings: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-16 15:27:03.219  8444  8444 W ExternalStrings: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-16 15:27:03.219  8444  8444 W ExternalStrings: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 15:27:03.219  8444  8444 W ExternalStrings: 	at android.os.Looper.loop(Looper.java:135)
08-16 15:27:03.219  8444  8444 W ExternalStrings: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 15:27:03.219  8444  8444 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 15:27:03.219  8444  8444 W ExternalStrings: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 15:27:03.219  8444  8444 W ExternalStrings: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 15:27:03.219  8444  8444 W ExternalStrings: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 15:27:03.220  8444  8444 D StatusProvider: onCreate
08-16 15:27:03.221  1927  1927 V WfdStateTracker: handleWifiStateChangedEvent: 1
08-16 15:27:03.221  1044  1044 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 15:27:03.222  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:27:03.222  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:27:03.222  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
08-16 15:27:03.224  1044  1044 D WifiHS20: [PASSPOINT] passpointNotification: hs20AP list is checked
08-16 15:27:03.225  1044  1044 W Settings: Setting stay_on_while_plugged_in has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:27:03.225  1044  1044 W Settings: Setting wifi_sleep_policy has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
08-16 15:27:03.225  1044  1044 D WifiOffDelayIfNotUsed: NETWORK_STATE_CHANGED_ACTION [CONNECTED]
,08-16 15:27:03.228  1044  1525 E WifiStateMachine: Did not find remoteAddress {192.168.1.1} in /proc/net/arp
08-16 15:27:03.231  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTING/CAPTIVE_PORTAL_CHECK, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:27:03.231  1589  1589 I StatusBar.NetworkController: mWifiConnected = false, mWifiLevel = 0
08-16 15:27:03.232  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:27:03.234  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:27:03.234  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 15:27:03.235  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:27:03.237  1589  1589 I StatusBar.NetworkController: networkInfo=[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
08-16 15:27:03.237  1589  1589 I StatusBar.NetworkController: mWifiConnected = true, mWifiLevel = 3
08-16 15:27:03.237  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 15:27:03.260  8444  8444 V Signer  : override build config not found
,08-16 15:27:03.260  8444  8444 D Signer  : value of property debug is false
08-16 15:27:03.266  1044  1531 E ConnectivityService: Unexpected mtu value: 0, wlan0
08-16 15:27:03.266  1044  1531 D ConnectivityService: Adding Route [fe80::/64 -> :: wlan0] to network 102
08-16 15:27:03.275  1044  1531 D ConnectivityService: Adding Route [192.168.1.0/24 -> 0.0.0.0 wlan0] to network 102
,08-16 15:27:03.276   321   903 E Netd    : netlink response contains error (File exists)
08-16 15:27:03.277  1044  1531 D ConnectivityService: Adding Route [0.0.0.0/0 -> 192.168.1.1 wlan0] to network 102
08-16 15:27:03.277  1044  1531 D ConnectivityService: addLocalRoutetoDefaultNetwork
08-16 15:27:03.277  1044  1531 D ConnectivityService: defaultNAI is null or Wi-Fi no need to add Loacal route to default network. WiFi netid = 102
08-16 15:27:03.277  1044  1531 D ConnectivityService: Setting Dns servers for network 102 to [/192.168.1.1]
08-16 15:27:03.278  1044  1531 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 15:27:03.278  1044  1531 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 15:27:03.278  1044  1531 D ConnectivityService: notifyType PRECHECK for NetworkAgentInfo [WIFI () - 102]
08-16 15:27:03.278  1044  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 15:27:03.278  1044  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 15:27:03.278  1044  8470 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=0 what=532481 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:03.278  1044  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 15:27:03.278  1044  8470 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Connected
08-16 15:27:03.278  1044  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 15:27:03.278  1044  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:27:03.278  1044  8470 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=1 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:03.278  1044  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ], isRequest:true
08-16 15:27:03.278  1044  1531 D ConnectivityService: currentScore = 0, newScore = 20
08-16 15:27:03.278  1044  1531 D ConnectivityService:    accepting network in place of null
08-16 15:27:03.278  1044  1531 D ConnectivityService: sending new Min Network Score(20): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:27:03.278  1044  8470 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 15:27:03.279  1044  1531 E ConnectivityService: [lg_data] Adding agent NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} } for legacy network type 1
08-16 15:27:03.279  1044  1531 D CSLegacyTypeTracker: Sending connected broadcast for type 1 NetworkAgentInfo [WIFI () - 102] isDefaultNetwork=true
08-16 15:27:03.279  1044  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE_IMMEDIATE
08-16 15:27:03.279  1839  1839 D TelephonyNetworkFactory-1: new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:27:03.280  10,44  1525 D WIFI    : new score 20 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:27:03.280  1044  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 15:27:03.280  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 15:27:03.281  1044  1531 D ConnectivityService: sendStickyBroadcastDelayed: delayMs=3000, action=android.net.conn.CONNECTIVITY_CHANGE
08-16 15:27:03.281  1044  1531 D CSLegacyTypeTracker: [e] list.add(nai) empty : false size: 1
08-16 15:27:03.282  1044  1531 D ConnectivityService: Switching to new default network: NetworkAgentInfo{ ni{[type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]}  network{102}  lp{{InterfaceName: wlan0 LinkAddresses: [192.168.1.135/24,]  Routes: [fe80::/64 -> :: wlan0,192.168.1.0/24 -> 0.0.0.0 wlan0,0.0.0.0/0 -> 192.168.1.1 wlan0,] DnsAddresses: [192.168.1.1,] Domains: null MTU: 0 TcpBufferSizes: 524288,1048576,2097152,262144,524288,1048576}}  nc{[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]}  Score{20} validated{false} created{true} explicitlySelected{false} }
08-16 15:27:03.283  1044  1044 D LocSvc_java: Sending msg: 4 arg1:1 arg2:1
08-16 15:27:03.283  1044  1044 D LocSvc_java: getAGpsConnectionInfo connType - 4
08-16 15:27:03.283  1044  1044 D LocSvc_java: updateNetworkState connTyp: 4 available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false] info.getType():1
08-16 15:27:03.283  1044  1044 D LocSvc_java: ignore wifi update if we are not in OPENING or CLOSING
08-16 15:27:03.286  1044  1531 D ConnectivityService: validation of new default Network = false
08-16 15:27:03.286  1044  1531 D ConnectivityService: Default network via Wi-Fi connected. start DSQN
08-16 15:27:03.286  1044  1531 D DSQN    : enableDataServiceNotify 
08-16 15:27:03.286  1044  1531 D DSQN    : start dsqn bin
08-16 15:27:03.286   321  8475 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 15:27:03.286   321  8475 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-16 15:27:03.287  8444  8444 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DataWipe'.
08-16 15:27:03.287  8444  8444 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$DownloadMode'.
08-16 15:27:03.287  8444  8444 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardReset'.
08-16 15:27:03.287  8444  8444 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$HardwareKeyReset'.
08-16 15:27:03.287  8444  8444 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$RemoveDeviceAdmin'.
08-16 15:27:03.287  8444  8444 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UnknownSourceInstallation'.
08-16 15:27:03.287  8444  8444 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$Usb'.
08-16 15:27:03.288  8444  8444 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbDebugging'.
08-16 15:27:03.288  8444  8444 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbHostStorage'.
08-16 15:27:03.288  8444  8444 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbMediaTransfer'.
08-16 15:27:03.288  8444  8444 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbPictureTransfer'.
08-16 15:27:03.288  8444  8444 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbStorage'.
08-16 15:27:03.288  8444  8444 D LGMDMWrapper: Found class 'com.mcafee.lgmdm.LGMDMWrapper$UsbTethering'.
08-16 15:27:03.291 , 1044  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 15:27:03.291  1044  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:27:03.291  1044  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 15:27:03.291  1044  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 15:27:03.292  1589  2063 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 15:27:03.279  8476  8476 W dsqn    : type=1400 audit(0.0:191): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 15:27:03.279  8476  8476 W dsqn    : type=1400 audit(0.0:192): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dsqn:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 15:27:03.296  8444  8444 V LGMDMManager: Create singleton instance
08-16 15:27:03.296  1044  1523 V NetworkPolicy: [LG_RESTRICTED] checkMobilePolicy_type()
08-16 15:27:03.305  8476  8476 E DSQN    : DSQN ssw
,08-16 15:27:03.315  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 15:27:03.316  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:27:03.316  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:27:03.336   321  8475 D libc-netbsd: res_queryN name = clients3.google.com succeed
,08-16 15:27:03.348  8444  8444 D LGMDMWrapper: LG MDM library v4.0.0 is available on this device.
,08-16 15:27:03.372   321   902 D LGDataListener: argv[0]=dsqncommand
08-16 15:27:03.372   321   902 D LGDataListener: argv[1]=wlan0
08-16 15:27:03.372   321   902 D LGDataListener: argv[2]=1
08-16 15:27:03.372   321   902 D LGDataListener: notifyDSQN DSQN STARTMONITOR wlan0 1
08-16 15:27:03.373  1044  1117 D DSQN    : DSQM DsqnNotification wlan0  1
,08-16 15:27:03.373  1044  1117 D DSQN    : start to monitor internet connection
08-16 15:27:03.374  1044  8471 D DhcpStateMachine: DHCPV4 request on wlan0
08-16 15:27:03.375  1044  8471 V LgDhcpStateMachineHelper: [bssid] hash key :f4:f2:6d:22:99:3e
08-16 15:27:03.375  1044  8471 D LgDhcpStateMachineHelper: dhcp.ap.macaddress = f4:f2:6d:22:99:3e
08-16 15:27:03.369  8483  8483 W dhcpcd  : type=1400 audit(0.0:193): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 15:27:03.369  8483  8483 W dhcpcd  : type=1400 audit(0.0:194): avc: denied { read write } for path="/dev/block/mmcblk0" dev="tmpfs" ino=6849 scontext=u:r:dhcp:s0 tcontext=u:object_r:mmc_block_device:s0 tclass=blk_file
08-16 15:27:03.389  8444  8444 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 15:27:03.389  8444  8485 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 15:27:03.394  8483  8483 I dhcpcd  : version 5.5.6 starting
08-16 15:27:03.395  8483  8483 E dhcpcd  : get_duid: m
08-16 15:27:03.395  8483  8483 D dhcpcd  : wlan0: using ClientID 01:c4:9a:02:7f:fb:5d
08-16 15:27:03.395  8483  8483 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason PREINIT
,08-16 15:27:03.401  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 15:27:03.404  1044  8470 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 13:27:03 GMT], X-Android-Received-Millis=[1471354023404], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471354023371]}
08-16 15:27:03.404  1044  8470 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 15:27:03.405  1044  8470 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 15:27:03.405  1044  1531 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-16 15:27:03.405  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:27:03.405  1044  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 15:27:03.405  1044  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 15:27:03.405  1044  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 15:27:03.406  1044  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 15:27:03.406  1044  1531 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-16 15:27:03.406  1044  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 15:27:03.406  1044  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:27:03.406  1044  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 15:27:03.407  1044  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 15:27:03.408  1589  2063 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 15:27:03.408  1044  1531 D ConnectivityService: sending new Min Network Score(60): NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:27:03.408  1839  1839 D TelephonyNetworkFactory-1: new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:27:03.408  1044  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.INET_CONDITION_ACTION
08-16 15:27:03.409  1839  1839 D TelephonyNetworkFactory-1:   my score=50, my filter=[ Transports: CELLULAR Capabilities: MMS&SUPL&DUN&FOTA&IMS&CBS&IA&RCS&XCAP&EIMS&NOT_RESTRICTED&TRUSTED&NOT_VPN&TETHERING&BIP&ADMIN&VZWAPP&VZW800 Specifier: <-1>]
08-16 15:27:03.409  1044  1525 D WIFI    : new score 60 for exisiting request NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:27:03.410  1044  1525 D WIFI    :   my score=60, my filter=[ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 15:27:03.412  8291  8291 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 15:27:03.415  8291  8291 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 15:27:03.429  1589  1589 D TelephonyIcons: null signal icon name: drawable/stat_sys_signal_null
08-16 15:27:03.430  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
08-16 15:27:03.431  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 15:27:03.439  8291  8291 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 15:27:03.441  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.SCAN_RESULTS
08-16 15:27:03.442  7091  7091 D WiFiOffLoadBroadcast: Not supported operator for automatic switch
08-16 15:27:03.449  8444  8444 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 15:27:03.450  8444  8485 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 15:27:03.455  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 15:27:03.459  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:27:03.463  8483  8483 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 15:27:03.463  8483  8483 D dhcpcd  : [read_lease] unlink /data/misc/dhcp/dhcpcd-wlan0.lease, link /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 15:27:03.463  8483  8483 D dhcpcd  : wlan0: reading lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 15:27:03.463  8291  8291 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 15:27:03.463  8483  8483 I dhcpcd  : wlan0: rebinding lease of 192.168.1.135
08-16 15:27:03.463  8483  8483 D dhcpcd  : wlan0: sending REQUEST (xid 0x39a0820d), next in 3.42 seconds
08-16 15:27:03.464  8291  8291 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
,08-16 15:27:03.466  8291  8291 I QRemote : [WiFiStateReceiver.java:199:onReceive()] oooooo The network is disconnected.
08-16 15:27:03.469  8444  8444 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 15:27:03.469  8444  8485 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 15:27:03.473  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 15:27:03.477  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:27:03.482  8291  8291 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
,08-16 15:27:03.482  8291  8291 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 15:27:03.483  8291  8291 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 15:27:03.487  8444  8444 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 15:27:03.487  8444  8485 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 15:27:03.493  8483  8483 I dhcpcd  : wlan0: acknowledged 192.168.1.135 from 192.168.1.1
08-16 15:27:03.495  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 15:27:03.501  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:27:03.505  8291  8291 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 15:27:03.506  8291  8291 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 15:27:03.506  8291  8291 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 15:27:03.508  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : action = android.net.conn.TETHER_STATE_CHANGED
08-16 15:27:03.509  7091  7091 D UsbSettingsReceiver: [AUTORUN] sys.usb.config = ptp_only,adb
08-16 15:27:03.509  7091  7091 D UsbSettingsReceiver: [AUTORUN] sys.usb.state = ptp_only,adb
08-16 15:27:03.509  7091  7091 D UsbSettingsReceiver: [AUTORUN] persist.sys.usb.config = ptp_only,adb
08-16 15:27:03.509  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : app userid = 0, current userid = 0
,08-16 15:27:03.510  7091  7091 D UsbSettingsControl: [AUTORUN] getUsbConnected() : connected=true
,08-16 15:27:03.510  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : availableList=[wlan0]
,08-16 15:27:03.510  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : activeList=[]
08-16 15:27:03.510  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : errorList=[]
08-16 15:27:03.510  7091  7091 D UsbSettingsControl: [AUTORUN] isAutorunTimer() : mAutorunChanging=false
08-16 15:27:03.510  7091  7091 D UsbSettingsReceiver: [AUTORUN] onReceive() : TetherState Changed=wlan0
08-16 15:27:03.511  7091  7091 D UsbSettingsControl: [AUTORUN] setTetherStatus() : status=false
08-16 15:27:03.514  8483  8483 I dhcpcd  : wlan0: leased 192.168.1.135 for 172800 seconds
08-16 15:27:03.514  8483  8483 D dhcpcd  : wlan0: adding IP address 192.168.1.135/24
08-16 15:27:03.514  8483  8483 D dhcpcd  : wlan0: adding route to 192.168.1.0/24
08-16 15:27:03.514  8483  8483 D dhcpcd  : wlan0: adding default route via 192.168.1.1
08-16 15:27:03.514  8483  8483 D dhcpcd  : wlan0: writing lease `/data/misc/dhcp/dhcpcd-wlan0.lease'
08-16 15:27:03.515  8483  8483 D dhcpcd  : getUsingAPMacAddress: f4:f2:6d:22:99:3e , return 1
08-16 15:27:03.515  8483  8483 D dhcpcd  : write_lease_ext: /data/misc/dhcp/dhcpcd-wlan0-f4:f2:6d:22:99:3e.lease2
08-16 15:27:03.515  8483  8483 D dhcpcd  : wlan0: executing `/system/etc/dhcpcd/dhcpcd-run-hooks', reason REBOOT
08-16 15:27:03.605  8444  8444 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
,08-16 15:27:03.606  8444  8485 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 15:27:03.609  8444  8484 W ActivityThread: ClassLoader.getResources: The class loader returned by Thread.getContextClassLoader() may fail for processes that host multiple applications. You should explicitly specify a context class loader. For example: Thread.setContextClassLoader(getClass().getClassLoader());
08-16 15:27:03.619  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 15:27:03.627  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:27:03.632  8291  8291 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 15:27:03.633  8291  8291 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 15:27:03.633  8291  8291 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 15:27:03.636  8444  8485 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 15:27:03.637  8444  8444 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 15:27:03.648  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 15:27:03.653  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:27:03.658  8291  8291 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 15:27:03.658  8291  8291 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 15:27:03.659  8291  8291 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 15:27:03.661  8444  8444 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 15:27:03.662  8444  8485 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 15:27:03.671  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 15:27:03.676  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:27:03.680  8291  8291 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 15:27:03.681  8291  8291 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 15:27:03.681  8291  8291 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 15:27:03.689  8444  8444 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 15:27:03.689  8444  8485 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 15:27:03.701  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 15:27:03.706  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
,08-16 15:27:03.711  8291  8291 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 15:27:03.712  8291  8291 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 15:27:03.717  8291  8291 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
,08-16 15:27:03.722  8444  8444 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 15:27:03.722  8444  8485 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
08-16 15:27:03.726  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 15:27:03.732  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:27:03.737  8291  8291 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 15:27:03.737  8291  8291 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 15:27:03.738  8291  8291 I QRemote : [WiFiStateReceiver.java:201:onReceive()] oooooo The network is not connected. Don't handle that intent.
08-16 15:27:03.741  8444  8444 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 15:27:03.741  8444  8485 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 15:27:03.746  8397  8397 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 15:27:03.750  8397  8397 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 15:27:03.752  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
,08-16 15:27:03.756  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:27:03.762  8291  8291 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 15:27:03.762  8291  8291 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 15:27:03.763  8291  8291 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 15:27:03.764  8291  8291 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 15:27:03.764  8291  8291 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 15:27:03.769  8444  8444 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'android.net.wifi.STATE_CHANGE'.
08-16 15:27:03.769  8444  8485 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.framework.a.run:-1 java.lang.Thread.run:818 
,08-16 15:27:03.774  8397  8397 I PCSuite : [StartReceiver]NETWORK_STATE_CHANGED_ACTION : CONNECTED
08-16 15:27:03.775  8397  8397 D PCSuite : [StartReceiver][LGSW]false, [WIFIUI]false, [WIFI]true, [HOTSPOT]false, [OBEXSERVICE]false
08-16 15:27:03.777  7091  7091 V WiFiOffLoadBroadcast: WiFiOffLoadBroadcast: android.net.wifi.STATE_CHANGE
08-16 15:27:03.780  1044  8471 D DhcpStateMachine: DHCPV4 succeeded on wlan0
,08-16 15:27:03.781  1044  8471 D LgDhcpStateMachineHelper: CheckDhcpDirectory [Lease File Count] : 3
08-16 15:27:03.781  1044  8471 V LgDhcpStateMachineHelper: [bssid + ssid] hash key :f4:f2:6d:22:99:3e"NG700"
08-16 15:27:03.781  7091  7091 D WiFiOffLoadBroadcast: MCCMNC not supported: null
08-16 15:27:03.781  1044  8471 D LgDhcpStateMachineHelper: checkAutoIpWithDhcpInfo + ipaddr = 192.168.1.135
08-16 15:27:03.781  1044  8471 V LgDhcpStateMachineHelper: Don't need to update mDhcpResultsCacheList
08-16 15:27:03.781  1044  8471 V DhcpStateMachine: Current State is mWaitBeforeStartState.
08-16 15:27:03.781  1044  8471 V LgDhcpStateMachineHelper: bShouldSendDhcpAction Result: false
08-16 15:27:03.782  1044  8471 D DhcpStateMachine: DHCP Start/Renew wake lock is released.
08-16 15:27:03.782  1044  8471 D DhcpStateMachine: RunningState
08-16 15:27:03.788  8291  8291 D QRemote : [WiFiStateReceiver.java:50:onReceive()] oooooo 140626:action:android.net.wifi.STATE_CHANGE
08-16 15:27:03.788  8291  8291 D QRemote : [WiFiStateReceiver.java:118:onReceive()] oooooo NETWORK_STATE_CHANGED_ACTION
08-16 15:27:03.789  8291  8291 D QRemote : [WiFiStateReceiver.java:123:onReceive()] oooooo The network is connected.
08-16 15:27:03.789  8291  8291 I QRemote : [Constants.java:311:getHomeWifiIdList()] oooooo There are not stored home Wi-Fi networks.
08-16 15:27:03.789  8291  8291 I QRemote : [WiFiStateReceiver.java:178:onReceive()] oooooo There are no stored BSSIDs.
08-16 15:27:03.791  8444  8484 D LgDataFeature: LgDataFeature() Constructor: none
08-16 15:27:03.791  8444  8484 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 15:27:03.792  8444  8444 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 15:27:03.795  8444  8444 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-16 15:27:03.797  8444  8444 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 15:27:03.799  8444  8444 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 15:27:03.801  8444  8444 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 15:27:03.802  8444  8444 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 15:27:03.804  8444  8444 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 15:27:03.806  8444  8444 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 15:27:03.808  8444  8444 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
,08-16 15:27:03.809  8444  8444 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 15:27:03.811  8444  8444 D PostponalbeReceiver: WSAndroidSystemIntentReceiver has postponed processing the broadcast action 'null'.
08-16 15:27:03.813  1044  1949 I ActivityManager: Killing 7415:com.google.android.apps.magazines/u0a93 (adj 15): empty #17
08-16 15:27:03.882  8444  8484 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.sendBroadcast:1392 android.content.ContextWrapper.sendBroadcast:376 com.mcafee.vsmandroid.gh.h:-1 com.mcafee.vsm.ext.common.a.d.a:-1 com.mcafee.vsm.ext.common.api.ExtUtils.stopApp:-1 
,08-16 15:27:03.923  1044  1981 W libprocessgroup: failed to open /acct/uid_10093/pid_7415/cgroup.procs: No such file or directory
,08-16 15:27:03.953  8444  8484 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.google.android.browser/com.android.browser.BrowserActivity not supported
,08-16 15:27:03.965  8444  8484 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.amazon.cloud9/com.amazon.cloud9.BrowserActivity not supported
08-16 15:27:03.965  8444  8484 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-16 15:27:03.966  8444  8484 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.sec.android.app.sbrowser/com.sec.android.app.sbrowser.SBrowserMainActivity not supported
08-16 15:27:03.967  8444  8484 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Browser component :com.htc.sense.browser/com.htc.sense.browser.BrowserActivity not supported
08-16 15:27:03.967  8444  8484 I SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Loading supported browsers: com.android.browser/com.android.browser.BrowserActivity; com.android.chrome/com.android.chrome.Main; 
,08-16 15:27:03.975  8444  8484 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here is the storedCurrentAppVersion: 3.1.2.1430
08-16 15:27:03.979  8444  8484 D SiteAdvisor: com.mcafee.android.b.a.a(Unknown Source): 'BackgroundWoker-TemporaryThread-1': Here about to commit perfs
,08-16 15:27:04.256  1044  1774 I art     : Explicit concurrent mark sweep GC freed 75345(3MB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/64MB, paused 2.629ms total 155.822ms
,08-16 15:27:04.802  1044  1525 E WifiStateMachine:  ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-16 15:27:04.803  1044  1525 E WifiStateMachine:  L2ConnectedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
,08-16 15:27:04.815  1044  1525 E WifiStateMachine:  ConnectModeState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 15:27:04.816  1044  1525 E WifiStateMachine:  DriverStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 15:27:04.818  1044  1525 E WifiStateMachine:  SupplicantStartedState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 15:27:04.819  1044  1525 E WifiStateMachine:  DefaultState CMD_UPDATE_LINKPROPERTIES 0 0 v4 v4r v4dns
08-16 15:27:04.822  1044  1531 D ConnectivityService: Update of LinkProperties for NetworkAgentInfo [WIFI () - 102]; created=true
08-16 15:27:04.822  1044  1531 D ConnectivityService: identical MTU - not setting
08-16 15:27:04.822  1044  1531 D Nat464Xlat: requiresClat: netType=1, connected=true, hasIPv4Address=true, hasInternetCapability=true
08-16 15:27:04.822  1044  1531 D ConnectivityService: notifyType IP_CHANGED for NetworkAgentInfo [WIFI () - 102]
08-16 15:27:04.823  1044  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:27:04.823  1044  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 15:27:04.827  1044  1531 D ConnectivityService: sending notification IP_CHANGED for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-16 15:27:04.830  1589  2063 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524295
,08-16 15:27:05.812  7831  8345 D UEI.SmartControl: Internal timer expired: 2
08-16 15:27:05.812  7831  8345 D UEI.SmartControl: unbind internal service
,08-16 15:27:05.948  7831  8339 D serial_port: close(fd = 24)
,08-16 15:27:05.957  7831  8339 I UEI.SmartControl: Serial port is closed.
,08-16 15:27:06.171  1044  1525 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=82.0, 0.0, 0.0  rx=85.5 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1819756357] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 15:27:06.182  1044  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=82.0, 0.0, 0.0  rx=85.5 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1819756347] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 15:27:06.182  1044  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 15:27:06.198  1589  1589 D StatusBar.NetworkController: refreshViews: Data not connected!! Set no data type icon / Roaming
,08-16 15:27:06.225  1044  1526 V WifiInternetCheck: Single check msg out of sync, ignoring.
,08-16 15:27:06.284  1044  1531 D ConnectivityService: sendStickyBroadcast: action=android.net.conn.CONNECTIVITY_CHANGE
,08-16 15:27:06.300  1044  1119 D Tethering: MasterInitialState.processMessage what=3
08-16 15:27:06.321  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:27:06.321  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:27:06.321  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:27:06.321  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:27:06.321  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:27:06.321  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:27:06.321  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:27:06.321  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 15:27:06.326  6974  6974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 15:27:06.330  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:27:06.330  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:27:06.330  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:27:06.330  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:27:06.330  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:27:06.330  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:27:06.330  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:27:06.330  6974  6974 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 15:27:06.332  6974  6974 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 15:27:06.337  1044  1114 D GpsLocationProvider: receive broadcast intent, action: android.net.conn.CONNECTIVITY_CHANGE
,08-16 15:27:06.343  8444  8444 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.net.conn.CONNECTIVITY_CHANGE'.
08-16 15:27:06.352  5808  5808 I NetworkMonitor: type=WIFI subType= reason=null isConnected=true
,08-16 15:27:06.374  1044  1114 D GpsLocationProvider: updateNetworkState available info: [type: WIFI[], state: CONNECTED/CONNECTED, reason: (unspecified), extra: "NG700", roaming: false, failover: false, isAvailable: true, isConnectedToProvisioningNetwork: false]
,08-16 15:27:06.381  6974  7031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: State changed:
08-16 15:27:06.381  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:27:06.381  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:27:06.381  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:27:06.381  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:27:06.381  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:27:06.381  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:27:06.381  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 15:27:06.383  6974  7031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 15:27:06.383  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:27:06.383  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener io.jxcore.node.ConnectivityMonitorTest$DiscoveryManagerMock@26da1b57 removed from the list
08-16 15:27:06.383  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:27:06.383  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:27:06.383  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:27:06.389  6974  8540 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 47775
08-16 15:27:06.389  6974  8540 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
,08-16 15:27:06.400  8444  8484 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.wavesecure.core.r.run:-1 java.util.concurrent.Executors$RunnableAdapter.call:422 java.util.concurrent.FutureTask.run:237 
08-16 15:27:06.413  2173  2173 D GCM     : GcmService start Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.gms/.gcm.GcmService (has extras) } android.net.conn.CONNECTIVITY_CHANGE
,08-16 15:27:06.429  1044  1774 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
,08-16 15:27:06.431  1044  8470 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
,08-16 15:27:06.431  1044  8470 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-2ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:06.431  1044  8470 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 15:27:06.431  1044  8470 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=2 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:06.431  1044  8470 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 15:27:06.438   321  8548 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 15:27:06.439   321  8548 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-16 15:27:06.451  7278  7278 I NetworkStateForAutoUpdateMonitor: [onReceive] BroadcastReceiver onReceive
08-16 15:27:06.451  7278  7278 I NetworkStateForAutoUpdateMonitor: [onReceive] intent action : android.net.conn.CONNECTIVITY_CHANGE
08-16 15:27:06.451  7278  7278 I NetworkStateForAutoUpdateMonitor: [onReceive] connect :true
08-16 15:27:06.452  7278  7278 I NetworkStateForAutoUpdateMonitor: [onReceive] request level :IDLE....
08-16 15:27:06.453  7278  7278 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 15:27:06.458  7278  7278 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@37a4402e
08-16 15:27:06.458  7278  7278 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 15:27:06.458  7278  7278 D AppUp4:CustFacade: isPhone : true
08-16 15:27:06.459  7278  7278 D AppUp4:CustModeStarterReceiver: begin check event
08-16 15:27:06.459  7278  7278 I AppUp4:CustModeStarterReceiver: Event For GoodConnectivity, noConnectivity : false, but skip! 
08-16 15:27:06.464  4739  4739 D LGDMClient: [DmDeviceActionReceiver.java] [onReceive()] : [128] : Device Action Receiver android.net.conn.CONNECTIVITY_CHANGE
08-16 15:27:06.465  4739  4739 D LGDMClient: [DmDeviceActionReceiver.java] [doAction()] : [60] : Device Action doAction
08-16 15:27:06.467  4739  4739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:78 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
,08-16 15:27:06.469  4739  4739 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.doAction:82 com.lge.lgdmsclient.dmclient.agent.DmDeviceActionReceiver.onReceive:132 android.app.ActivityThread.handleReceiver:2586 
08-16 15:27:06.473  2826  2826 V DownloadManager: Received broadcast intent for android.net.conn.CONNECTIVITY_CHANGE
08-16 15:27:06.475  2826  2826 V DownloadManager: DownloadService onCreate
08-16 15:27:06.475  1044  8470 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 13:27:06 GMT], X-Android-Received-Millis=[1471354026475], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471354026435]}
08-16 15:27:06.475  1044  8470 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 15:27:06.476  1044  8470 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
08-16 15:27:06.476   321  8548 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-16 15:27:06.477  1044  1531 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
08-16 15:27:06.477  4739  8559 D LGDMClient: [DmUtil.java] [getServiceTypeBasedOnAgentState()] : [672] : iAgentState=0, isUserType=0
08-16 15:27:06.477  1044  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
08-16 15:27:06.477  1044  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 15:27:06.477  1044  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 15:27:06.477  1044  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 15:27:06.477  1044  1531 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-16 15:27:06.477  1044  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 15:27:06.477  1044  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:27:06.477  1044  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 15:27:06.477  1044  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 15:27:06.478  2826  8560 I DownloadManager: in removeSpuriousFiles
08-16 15:27:06.479  2826  8560 V DownloadManager: starting query, database is not null; projection[0] is _data; selection is null; selectionArgs is null; sort is null.
08-16 15:27:06.482  1589  2063 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 15:27:06.483  2826  8560 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@37f4c9c0 on behalf of 2826
08-16 15:27:06.484  4739  8562 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [47] : Intent : android.net.conn.CONNECTIVITY_CHANGE
08-16 15:27:06.484  4739  8562 D LGDMClient: [GCMRegisterService.java] [onHandleIntent()] : [56] : ConnectivityManager is not null
08-16 15:27:06.484  2826  8560 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGMyGuide_4.40.09_COM_COM_20150430011620058_RELG-D855.apk
08-16 15:27:06.484  2826  8560 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGEIME_5.1.29_release_repacked_ARM_XT9_MYSCRIPT_20160317004155539.apk
08-16 15:27:06.484  2826  8560 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGBackup_5.1.24_COM_COM(9012_VDF)_20160401022656759.apk
08-16 15:27:06.484  2826  8560 I DownloadManager: in removeSpuriousFiles, pre,serving file /storage/emulated/0/.dwnld/CalendarProvider_4.2.8_COM_COM_20150304234552863_RELG-D855.apk
08-16 15:27:06.485  2826  8560 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calendar_4.40.16_COM_COM_20150304234554754_RELG-D855.apk
08-16 15:27:06.485  2826  8560 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/Calculator_4.40.11_COM_COM_v2_20150911144028620_RELG-D855_21.apk
08-16 15:27:06.485  2826  8560 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQMemoplus(LG-D855_user)_20150902050954661.apk
08-16 15:27:06.485  2826  8560 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/ConciergeBoard_4.40.12_COM_COM(VDF)_20160126234417577.apk
08-16 15:27:06.485  2826  8560 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/RemoteCall_4.1.10_COM_COM_20150817053748728.apk
08-16 15:27:06.485  2826  8560 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/LGQVoiceplusN_2.3.3_COM_COM_20150604065210803.apk
08-16 15:27:06.485  2826  8560 I DownloadManager: in removeSpuriousFiles, preserving file /storage/emulated/0/.dwnld/rspermlge(6713)_20150901080430397.apk
,08-16 15:27:06.487  2826  8560 I DownloadManager: in trimDatabase
08-16 15:27:06.487  2826  8560 V DownloadManager: starting query, database is not null; projection[0] is _id; selection is status >= '200'; selectionArgs is null; sort is lastmod.
08-16 15:27:06.488  2826  8560 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@333296f9 on behalf of 2826
08-16 15:27:06.490  4739  8559 I LGDMClient: [DmServiceProcessor.java] [processNetworkChanged()] : [91] : networkStateChanged [DeviceServiceType:Full Mode]--> NetworkType : WIFI is connected.
08-16 15:27:06.544  1044  2009 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.adapter.eas.EasBroadcastReceiver: pid=8566 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
,08-16 15:27:06.550  2826  2826 V DownloadManager: DownloadService onStartCommand
08-16 15:27:06.550  2826  8561 V DownloadManager: starting query, database is not null; projection is null; selection is null; selectionArgs is null; sort is null.
08-16 15:27:06.553  4739  8559 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.startService:1757 android.content.ContextWrapper.startService:515 com.lge.lgdmsclient.service.DmServiceProcessor.processNetworkChanged:141 com.lge.lgdmsclient.service.DmServiceProcessor.onHandleIntent:180 android.app.IntentService$ServiceHandler.handleMessage:65 
08-16 15:27:06.553  2826  8561 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@383cc1ec on behalf of 2826
08-16 15:27:06.558  4739  4739 E LGDMClient: [DmNotiService.java] [onCreate()] : [148] : DmNotiService.onCreate()
08-16 15:27:06.558  4739  4739 D LGDMClient: [DmNotiService.java] [onStartCommand()] : [182] : in the new onStartCommand()
08-16 15:27:06.559  4739  4739 D LGDMClient: [DmNotiService.java] [handleStart()] : [203] : IN SERVICE IntentActioncom.lge.dm.dmclient.intent.SYSTEM_NETWORK_CHANGED
08-16 15:27:06.559  2826  8561 V DownloadManager: processing inserted download 1
08-16 15:27:06.560  2826  8561 V DownloadManager: processing inserted download 4
,08-16 15:27:06.562  4739  4739 D LGDMClient: [DmNotiService.java] [actionSystemNetworkChanged()] : [274] : DmConstants.DMAgentState.DMA_STATE_IDLE
,08-16 15:27:06.564  2826  8561 V DownloadManager: processing inserted download 7
08-16 15:27:06.566  2826  8561 V DownloadManager: processing inserted download 8
08-16 15:27:06.567  2826  8561 V DownloadManager: processing inserted download 9
08-16 15:27:06.568  2826  8561 V DownloadManager: processing inserted download 10
08-16 15:27:06.569  2826  8561 V DownloadManager: processing inserted download 11
08-16 15:27:06.571  2826  8561 V DownloadManager: processing inserted download 12
08-16 15:27:06.572  4739  4739 D LGDMClient: [DmNotiService.java] [OneDayWiFiCheck()] : [659] : agentmodeOnOff is OFF. Finish OneDayWiFiCheck
08-16 15:27:06.572  2826  8561 V DownloadManager: processing inserted download 13
,08-16 15:27:06.574  2826  8561 V DownloadManager: processing inserted download 14
08-16 15:27:06.576  2826  8561 V DownloadManager: processing inserted download 16
08-16 15:27:06.578  2826  2826 V DownloadManager: DownloadService onDestroy
,08-16 15:27:06.610  8566  8566 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 15:27:06.611  8566  8566 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 15:27:06.612  8566  8566 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 15:27:06.613  8566  8566 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-16 15:27:06.705  8566  8566 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-16 15:27:06.719  8566  8566 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
,08-16 15:27:06.769  8566  8566 W ResourceType: No package identifier when getting value for resource number 0x00000000
,08-16 15:27:06.807  8566  8566 D LgDataFeature: LgDataFeature() Constructor: none
,08-16 15:27:06.807  8566  8566 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 15:27:06.946  8566  8566 D eas_req : ---addEventToQueue() easCode=2, requestId=0 (at EasSupport.java addEventToQueue 69)
,08-16 15:27:06.994  8566  8566 I HubEmail: JNI_OnLoad()
08-16 15:27:06.994  8566  8566 I HubEmail: -- called from 1935 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 15:27:06.994  8566  8566 I HubEmail: registerNatives()
08-16 15:27:06.994  8566  8566 I HubEmail: -- called from 1905 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 15:27:06.994  8566  8566 I HubEmail: registerNativeMethods()
08-16 15:27:06.994  8566  8566 I HubEmail: -- called from 1774 ../../Build/Android_r4/../../SDK/Native/EmailCoreLinkJni.cpp
08-16 15:27:06.995  8566  8566 W art     : JNI RegisterNativeMethods: attempt to register 0 native methods for com.lge.email.jni.EmailCoreLink
,08-16 15:27:07.016  8566  8599 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 15:27:07.022  3304  3304 I LgeMiscReceiver: intent = Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.android.mms/.transaction.LgeMiscReceiver (has extras) }
08-16 15:27:07.022  3304  3304 I LgeMiscReceiver: action = android.net.conn.CONNECTIVITY_CHANGE
08-16 15:27:07.022  3304  3304 I LgeMiscReceiver: networkInfo.isConnected() = true
08-16 15:27:07.022  3304  3304 D PhoneState: setPdpRejectCasuse : false
,08-16 15:27:07.047   321  8603 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-16 15:27:07.049   321  8603 D libc-netbsd: res_queryN name = static-avc.lglime.com, class = 1, type = 1
08-16 15:27:07.064  1044  1059 I ActivityManager: Start proc com.google.android.setupwizard for broadcast com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver: pid=8604 uid=10046 gids={50046, 9997, 3003} abi=armeabi-v7a
,08-16 15:27:07.096   321  8603 D libc-netbsd: res_queryN name = static-avc.lglime.com succeed
,08-16 15:27:07.135  8376  8600 V FormManager: There are no updated forms. The schedule will be deleted.
,08-16 15:27:07.138  8376  8600 V FormManager: Alarm would be updated, because LastCheckTime has been updated.
08-16 15:27:07.161  1044  1060 I ActivityManager: Killing 7904:com.google.android.talk/u0a72 (adj 15): empty #17
,08-16 15:27:07.192  8604  8604 D LgDataFeature: LgDataFeature() Constructor: none
08-16 15:27:07.193  8604  8604 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 15:27:07.196  8604  8604 D PhoneMonitor: Register our PhoneStateListener
08-16 15:27:07.216  1044  1977 W libprocessgroup: failed to open /acct/uid_10072/pid_7904/cgroup.procs: No such file or directory
,08-16 15:27:07.233  8604  8604 D MobileConnectivityChangeReceiver: onReceive Intent { act=android.net.conn.CONNECTIVITY_CHANGE flg=0x4000010 cmp=com.google.android.setupwizard/.carrier.MobileConnectivityChangeReceiver (has extras) }
,08-16 15:27:07.235  8604  8604 D MobileConnectivityChangeReceiver: onReceive CONNECTIVITY_CHANGE networkType=1
,08-16 15:27:07.249  8604  8604 D PhoneMonitor: onServiceStateChanged state="2 1 home null null null  Unknown Unknown CSS not supported -1 -1 RoamInd=-1 DefRoamInd=-1 EmergOnly=truevoice roaming=false Data Roaming=false mIsVoiceSearching=true mIsDataSearching=true mVoiceNetworkName=null mDataNetworkName=null Check64QAM0 Dual carrier0 Ril Voice Regist state: 0 Ril Data Regist state: 0 mProprietaryDataRadioTechnology: 0 mCdmaNetWorkMode: 0" SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNINITIALIZED(0) HFA_ACTIVATED=false
,08-16 15:27:07.250  8604  8604 V TelephonyAutoProfiling: [loadFeatureFromXml] *** start feature loading from xml
08-16 15:27:07.250  8604  8604 D TelephonyAutoProfiling: [parse] Load xml
,08-16 15:27:07.254  8604  8604 V TelephonyAutoProfiling: [getMatchedProfile] selected file : /cust/OPEN_EU/config/featureset.xml
08-16 15:27:07.254  8604  8604 D TelephonyAutoProfiling: [profileToMap] add - key : handle8bit, value : true
08-16 15:27:07.254  8604  8604 D TelephonyAutoProfiling: [profileToMap] add - key : ConcatMTCheckTimestamp, value : true
08-16 15:27:07.254  8604  8604 D TelephonyAutoProfiling: [profileToMap] add - key : allow_sending_empty_sms, value : true
08-16 15:27:07.254  8604  8604 D TelephonyAutoProfiling: [profileToMap] add - key : retry_to_enable_cb, value : true
08-16 15:27:07.254  8604  8604 D TelephonyAutoProfiling: [profileToMap] add - key : copy_submit_to_uicc, value : true
08-16 15:27:07.254  8604  8604 D TelephonyAutoProfiling: [profileToMap] add - key : spam, value : true
08-16 15:27:07.254  8604  8604 D TelephonyAutoProfiling: [profileToMap] add - key : MANUAL_SELECTION_WITH_RAT, value : true
08-16 15:27:07.254  8604  8604 D TelephonyAutoProfiling: [profileToMap] add - key : SUPPORT_LOG_RF_INFO, value : true
08-16 15:27:07.254  8604  8604 D TelephonyAutoProfiling: [profileToMap] add - key : seperate_processing_sms_uicc, value : true
08-16 15:27:07.254  8604  8604 D TelephonyAutoProfiling: [profileToMap] add - key : KRWapPushWithSpam, value : true
08-16 15:27:07.254  8604  8604 D TelephonyAutoProfiling: [profileToMap] add - key : GLOBALspam, value : true
08-16 15:27:07.254  8604  8604 D TelephonyAutoProfiling: [profileToMap] add - key : support_emoji_in_concat_message, value : true
08-16 15:27:07.257  8604  8604 D TelephonyAutoProfiling: [profileToMap] add - key : KSC5601Decoding, value : true
08-16 15:27:07.257  8604  8604 D TelephonyAutoProfiling: [profileToMap] add - key : KR_Modem_Item, value : true
08-16 15:27:07.257  8604  8604 D TelephonyAutoProfiling: [profileToMap] add - key : OperatorMessage, value : true
08-16 15:27:07.257  8604  8604 V TelephonyAutoProfiling: [loadFeatureFromXml] load feature from xml complete : {handle8bit=true, ConcatMTCheckTimestamp=true, retry_to_enable_cb=true, allow_sending_empty_sms=true, copy_submit_to_uicc=true, spam=true, MANUAL_SELECTION_WITH_RAT=true, seperate_processing_sms_uicc=true, SUPPORT_LOG_RF_INFO=true, KRWapPushWithSpam=true, GLOBALspam=true, KSC5601Decoding=true, support_emoji_in_concat_message=true, KR_Modem_Item=true, OperatorMessage=true}
,08-16 15:27:07.269  8604  8604 D PhoneMonitor: onOtaspChanged SIM_STATE_ABSENT(1) PHONE_TYPE_GSM(1) "UNKNOWN" mcc0mnc0 V:STATE_EMERGENCY_ONLY(2) D:STATE_OUT_OF_SERVICE(1) DATA_DISCONNECTED(0) OTASP_UNKNOWN(1) HFA_ACTIVATED=false
08-16 15:27:07.293  1044  1638 I ActivityManager: Start proc com.android.chrome for broadcast com.android.chrome/com.google.android.apps.chrome.precache.PrecacheServiceLauncher: pid=8629 uid=10057 gids={50057, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 15:27:07.297  1044  1638 I ActivityManager: Killing 7954:com.android.contacts/u0a19 (adj 15): empty #17
,08-16 15:27:07.343  1044  1916 W libprocessgroup: failed to open /acct/uid_10019/pid_7954/cgroup.procs: No such file or directory
,08-16 15:27:07.366  1803  8646 I CheckinService: active receiver: enabled
08-16 15:27:07.378  1803  8646 I CheckinService: Preparing to send checkin request
08-16 15:27:07.378  1803  8646 I EventLogService: Accumulating logs since 1471353992862
,08-16 15:27:07.427  1803  8646 I GoogleHttpClient: Falling back to old SSLCertificateSocketFactory
,08-16 15:27:07.431   321  8649 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 15:27:07.431   321  8649 D libc-netbsd: res_queryN name = www.google.com, class = 1, type = 1
,08-16 15:27:07.462   321  8649 D libc-netbsd: res_queryN name = www.google.com succeed
08-16 15:27:07.466   321  8651 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
08-16 15:27:07.467   321  8651 D libc-netbsd: res_queryN name = clients3.google.com, class = 1, type = 1
08-16 15:27:07.467   321  8651 D libc-netbsd: res_queryN name = clients3.google.com succeed
08-16 15:27:07.531  1044  1527 V WifiInternetCheck: isHttpConnectionAvailable - We got a valid response : 204
08-16 15:27:07.532  1044  1981 I ActivityManager: Start proc com.lge.drmservice for broadcast com.lge.drmservice/.DrmBroadcastReceiver: pid=8652 uid=10062 gids={50062, 9997, 4002, 3003, 1028} abi=armeabi-v7a
,08-16 15:27:07.534  1044  1981 I ActivityManager: Killing 7980:com.android.gallery3d/u0a27 (adj 15): empty #17
,08-16 15:27:07.657  1044  1059 I ActivityManager: Start proc com.google.android.gms.unstable for service com.google.android.gms/.droidguard.DroidGuardService: pid=8669 uid=10005 gids={50005, 9997, 2001, 3003, 1007, 3006, 3007, 1028, 1015, 3002, 3001, 1005} abi=armeabi-v7a
08-16 15:27:07.658  1044  1638 W libprocessgroup: failed to open /acct/uid_10027/pid_7980/cgroup.procs: No such file or directory
,08-16 15:27:07.730  8669  8669 W ResourcesManager: Asset path '/system/framework/com.android.media.remotedisplay.jar' does not exist or contains no resources.
,08-16 15:27:07.730  8669  8669 W ResourcesManager: Asset path '/system/framework/com.android.location.provider.jar' does not exist or contains no resources.
,08-16 15:27:07.751  1044  2009 I ActivityManager: Start proc com.lge.sizechangable.weather for broadcast com.lge.sizechangable.weather/.layout.WeatherWidget: pid=8686 uid=10085 gids={50085, 9997, 3003, 1028, 1015} abi=armeabi-v7a
,08-16 15:27:07.751  1044  2009 I ActivityManager: Killing 8040:com.lge.lockscreensettings/u0a80 (adj 15): empty #17
08-16 15:27:07.764  8669  8669 I MultiDex: VM with version 2.1.0 has multidex support
,08-16 15:27:07.764  8669  8669 I MultiDex: install
08-16 15:27:07.764  8669  8669 I MultiDex: VM has multidex support, MultiDex support library is disabled.
08-16 15:27:07.838  1044  1060 W libprocessgroup: failed to open /acct/uid_10080/pid_8040/cgroup.procs: No such file or directory
,08-16 15:27:07.852  8669  8669 I ProviderInstaller: Insert disabled by gate 'gms:security:enable_conscrypt_in_gms_application'
,08-16 15:27:07.876  8686  8686 I art     : Almond Protected OAT
,08-16 15:27:07.928  8686  8686 D WeatherApplication: removeAccount
,08-16 15:27:07.929  8686  8686 D WeatherApplication: Account.length = 0
08-16 15:27:07.930  8686  8686 E WeatherApplication: OPERATOR:OPEN
08-16 15:27:07.934  8686  8686 D WeatherAncestor: 2 : onReceive, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:27:7
08-16 15:27:07.937  8686  8686 D Weather.Utils: 2 : the weather widgets(using time tick) are gone.
08-16 15:27:07.937  8686  8686 D Weather.Utils: 2 : All the weather widget is gone.
08-16 15:27:07.938  8686  8686 D UpdateThreadPoolManager: 2 : This is isUpdating : false
,08-16 15:27:07.941  8686  8686 D WeatherAncestor: connectivity changed - connection : true
08-16 15:27:07.942  8686  8686 D WeatherService: 2 : isServiceAlived():false forecastCache:null
08-16 15:27:07.949  8686  8686 D ForecastDataCache: 2 : lastUpdatedTime: 1430832249415
08-16 15:27:07.949  8686  8686 D ForecastDataCache: 2 : currentPackageVersion: 4.40.4
08-16 15:27:07.950  8686  8686 D ForecastDataCache: 2 : Cache is not up-to-date, count: 0
,08-16 15:27:07.967  8686  8686 D Weather_cast: 2 : isUpdateNeedForAlarm : no city return false
,08-16 15:27:07.967  8686  8686 D WeatherAncestor: 2 : onReceive has processed, action: android.net.conn.CONNECTIVITY_CHANGE, Time(hour:min:sec) 15:27:7
,08-16 15:27:08.013  1044  1942 I ActivityManager: Start proc com.google.android.apps.magazines for broadcast com.google.android.apps.magazines/com.google.apps.dots.android.newsstand.appwidget.NewsWidgetProvider: pid=8706 uid=10093 gids={50093, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 15:27:08.014  1044  1942 I ActivityManager: Killing 7999:com.android.vending/u0a44 (adj 15): empty #17
,08-16 15:27:08.115  1044  1638 W libprocessgroup: failed to open /acct/uid_10044/pid_7999/cgroup.procs: No such file or directory
,08-16 15:27:08.194   280   358 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 15:27:08.194   280   358 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
,08-16 15:27:08.194   280   358 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 15:27:08.194  8706  8724 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-16 15:27:08.205   280   358 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 15:27:08.205   280   358 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 15:27:08.205   280   358 W Vold    : Returning OperationFailed - no handler for errno 0
,08-16 15:27:08.206  8706  8724 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 15:27:08.210   280   358 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 15:27:08.210   280   358 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/cache/
08-16 15:27:08.210   280   358 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 15:27:08.211  8706  8728 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/cache
08-16 15:27:08.212   280   358 E VoldCmdListener: [LGE][VOLD][CommandListener.cpp][VolumeCmd::runCommand()] argv[0]:volume, argv[1]:mkdirs, argc:3
08-16 15:27:08.212   280   358 E Vold    : Failed to find mounted volume for /storage/external_SD/Android/data/com.google.android.apps.magazines/files/
08-16 15:27:08.212   280   358 W Vold    : Returning OperationFailed - no handler for errno 0
08-16 15:27:08.212  8706  8728 W ContextImpl: Failed to ensure directory: /storage/external_SD/Android/data/com.google.android.apps.magazines/files
08-16 15:27:08.310  8669  8685 D LgDataFeature: LgDataFeature() Constructor: none
08-16 15:27:08.310  8669  8685 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 15:27:08.356  8742  8742 I dex2oat : /system/bin/dex2oat --runtime-arg -classpath --runtime-arg  --instruction-set=arm --instruction-set-features=div --runtime-arg -Xrelocate --boot-image=/system/framework/boot.art --dex-file=/data/data/com.google.android.gms/app_fb/f.apk --oat-fd=32 --oat-location=/data/data/com.google.android.gms/app_fb/f.dex --runtime-arg -Xms64m --runtime-arg -Xmx512m
,08-16 15:27:08.406  8742  8742 I dex2oat : dex2oat took 49.034ms (threads: 4)
,08-16 15:27:08.419  8669  8685 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 15:27:08.419  8669  8685 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 15:27:08.419  8669  8685 I Adreno-EGL: Build Date: 12/12/14 금
08-16 15:27:08.419  8669  8685 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 15:27:08.419  8669  8685 I Adreno-EGL: Remote Branch: 
08-16 15:27:08.419  8669  8685 I Adreno-EGL: Local Patches: 
08-16 15:27:08.419  8669  8685 I Adreno-EGL: Reconstruct Branch: 
08-16 15:27:08.437  8706  8706 I WebViewFactory: Loading com.google.android.webview version 37 (1589900-arm) (code 110601)
,08-16 15:27:08.447  8706  8706 I LibraryLoader: Loading: webviewchromium
,08-16 15:27:08.451  8706  8706 I LibraryLoader: Time to load native libraries: 5 ms (timestamps 9472-9477)
08-16 15:27:08.451  8706  8706 I LibraryLoader: Expected native library version number "",actual native library version number ""
,08-16 15:27:08.458  8706  8706 V WebViewChromiumFactoryProvider: Binding Chromium to main looper Looper (main, tid 1) {2b2eb151}
08-16 15:27:08.461  8706  8706 I LibraryLoader: Expected native library version number "",actual native library version number ""
08-16 15:27:08.462  8706  8706 I chromium: [INFO:library_loader_hooks.cc(106)] Chromium logging enabled: level = 0, default verbosity = 0
08-16 15:27:08.488  8706  8706 I BrowserStartupController: Initializing chromium process, renderers=0
,08-16 15:27:08.489  8706  8706 W art     : Attempt to remove local handle scope entry from IRT, ignoring
08-16 15:27:08.501  8706  8706 W chromium: [WARNING:resource_bundle.cc(315)] locale_file_path.empty()
08-16 15:27:08.502  8706  8706 I chromium: [INFO:aw_browser_main_parts.cc(63)] Load from apk succesful, fd=38 off=46780 len=2953
08-16 15:27:08.502  8706  8706 I chromium: [INFO:aw_browser_main_parts.cc(78)] Loading webviewchromium.pak from, fd:39 off:229536 len:643667
08-16 15:27:08.502   326   326 V AudioPolicyService: registerClient() client 0xb558a800, uid 10093
08-16 15:27:08.503  8706  8755 W AudioManagerAndroid: Requires BLUETOOTH permission
,08-16 15:27:08.519  8706  8706 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 15:27:08.519  8706  8706 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 15:27:08.519  8706  8706 I Adreno-EGL: Build Date: 12/12/14 금
08-16 15:27:08.519  8706  8706 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 15:27:08.519  8706  8706 I Adreno-EGL: Remote Branch: 
08-16 15:27:08.519  8706  8706 I Adreno-EGL: Local Patches: 
08-16 15:27:08.519  8706  8706 I Adreno-EGL: Reconstruct Branch: 
,08-16 15:27:08.550  8669  8685 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 15:27:08.550  8669  8685 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 15:27:08.550  8669  8685 I Adreno-EGL: Build Date: 12/12/14 금
08-16 15:27:08.550  8669  8685 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 15:27:08.550  8669  8685 I Adreno-EGL: Remote Branch: 
08-16 15:27:08.550  8669  8685 I Adreno-EGL: Local Patches: 
08-16 15:27:08.550  8669  8685 I Adreno-EGL: Reconstruct Branch: 
,08-16 15:27:08.597  8706  8706 I NSApplication: Starting up...
,08-16 15:27:08.622  1044  2036 I ActivityManager: Killing 7752:com.lge.lifetracker/u0a37 (adj 15): empty #17
,08-16 15:27:08.642  8669  8685 I Adreno-EGL: <qeglDrvAPI_eglInitialize:410>: EGL 1.4 QUALCOMM build:  ()
08-16 15:27:08.642  8669  8685 I Adreno-EGL: OpenGL ES Shader Compiler Version: E031.25.03.00
08-16 15:27:08.642  8669  8685 I Adreno-EGL: Build Date: 12/12/14 금
08-16 15:27:08.642  8669  8685 I Adreno-EGL: Local Branch: LA.BF.1.1_RB1.05.00.00.002.031_20141212_01821442
08-16 15:27:08.642  8669  8685 I Adreno-EGL: Remote Branch: 
08-16 15:27:08.642  8669  8685 I Adreno-EGL: Local Patches: 
08-16 15:27:08.642  8669  8685 I Adreno-EGL: Reconstruct Branch: 
,08-16 15:27:08.686  1044  1774 W libprocessgroup: failed to open /acct/uid_10037/pid_7752/cgroup.procs: No such file or directory
,08-16 15:27:08.714  2173  2173 D GCM     : GcmService start Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.gcm.GcmService } com.google.android.gms.INITIALIZE
,08-16 15:27:08.731  2173  2173 D AuthorizationBluetoothService: Received GmsCore event: Intent { act=com.google.android.gms.INITIALIZE flg=0x10 pkg=com.google.android.gms cmp=com.google.android.gms/.auth.be.proximity.authorization.bt.AuthorizationBluetoothService$AutoStarter }.
,08-16 15:27:08.732  2173  2173 D c       : Getting all permits...
,08-16 15:27:08.732  2173  2173 D a       : Opening database...
08-16 15:27:08.743  2173  2173 D a       : Opening database auth.proximity.permit_store...
08-16 15:27:08.745  2173  2173 D a       : Closing database...
,08-16 15:27:08.960   321  8772 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1,
08-16 15:27:08.961   321  8772 D libc-netbsd: res_queryN name = android.clients.google.com, class = 1, type = 1
,08-16 15:27:08.993   321  8772 D libc-netbsd: res_queryN name = android.clients.google.com succeed
,08-16 15:27:09.206  1044  1525 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=45.5, 0.0, 0.0  rx=45.2 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1819753322] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 15:27:09.207  1044  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=45.5, 0.0, 0.0  rx=45.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1819753321] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 15:27:09.207  1044  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 15:27:09.219  1803  8646 I CheckinTask: Sending checkin request (7942 bytes)
08-16 15:27:09.402  6974  8540 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 47775
,08-16 15:27:09.402  6974  8540 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-16 15:27:09.404  6974  8540 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
,08-16 15:27:09.410  6974  8779 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 47775
08-16 15:27:09.410  6974  8779 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-16 15:27:09.410  6974  8779 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 15:27:09.410  6974  8540 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 15:27:09.411  6974  8540 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
08-16 15:27:09.413  6974  8782 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 909, name: OutgoingSocketThread/Receiver)
08-16 15:27:09.416  6974  8779 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 15:27:09.417  6974  8779 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-16 15:27:09.419  6974  8781 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 907, name: OutgoingSocketThread/Sender)
08-16 15:27:09.420  6974  8783 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 908, name: IncomingSocketThread/Sender)
,08-16 15:27:09.422  6974  8782 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 909, thread name: OutgoingSocketThread/Receiver)
08-16 15:27:09.422  6974  8782 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-16 15:27:09.423  6974  8782 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 909, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-16 15:27:09.427  6974  8784 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 910, name: IncomingSocketThread/Receiver)
08-16 15:27:09.428  6974  8784 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 910, thread name: IncomingSocketThread/Receiver)
08-16 15:27:09.428  6974  8784 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-16 15:27:09.428  6974  8784 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 910, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
,08-16 15:27:09.504  2173  2195 I art     : Explicit concurrent mark sweep GC freed 9408(566KB) AllocSpace objects, 2(32KB) LOS objects, 52% free, 29MB/61MB, paused 1.738ms total 36.171ms
,08-16 15:27:09.544  1803  8646 I CheckinTask: Checkin success: https://android.clients.google.com/checkin (1 requests sent)
,08-16 15:27:09.557  1803  8646 I CheckinService: active receiver: disabled
,08-16 15:27:09.577  2173  2173 D GCM     : GcmService start Intent { act=com.google.android.checkin.CHECKIN_COMPLETE flg=0x10 cmp=com.google.android.gms/.gcm.GcmService (has extras) } com.google.android.checkin.CHECKIN_COMPLETE
,08-16 15:27:09.591  2173  2173 I GCM     : GCM config loaded
,08-16 15:27:09.604   321  8787 D libc-netbsd: default dns: query_ipv6=0, query_ipv4=1
,08-16 15:27:09.606   321  8787 D libc-netbsd: res_queryN name = mtalk.google.com, class = 1, type = 1
08-16 15:27:09.607   321  8787 D libc-netbsd: res_queryN name = mtalk.google.com succeed
08-16 15:27:09.612  8604  8604 V SetupWizard: Connected to Gservices successfully
,08-16 15:27:09.883  2173  8790 D GCM     : Connected
,08-16 15:27:09.923  2173  8790 D GCM     : Message class com.google.e.a.a.q
,08-16 15:27:12.220  1044  1525 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2447 sc=60 link=72 tx=37.8, 0.0, 0.0  rx=34.6 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1819750308] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 15:27:12.223  1044  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2447 sc=60 link=72 tx=37.8, 0.0, 0.0  rx=34.6 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1819750305] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 15:27:12.223  1044  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 15:27:12.393  6974  7031 D io.jxcore.node.LifeCycleMonitor: onActivityCreated: Bundle[{}]
08-16 15:27:12.394  6974  7031 D io.jxcore.node.LifeCycleMonitor: onActivityResumed
08-16 15:27:12.396  6974  7031 D io.jxcore.node.LifeCycleMonitor: onActivitySaveInstanceState: com.test.thalitest.MainActivity@3a581b60 Bundle[{}]
08-16 15:27:12.397  6974  7031 I io.jxcore.node.LifeCycleMonitor: start: OK
08-16 15:27:12.397  6974  7031 I io.jxcore.node.LifeCycleMonitor: stop: OK
08-16 15:27:12.398  6974  7031 D io.jxcore.node.LifeCycleMonitor: onActivityStarted
08-16 15:27:12.398  6974  7031 D io.jxcore.node.LifeCycleMonitor: onActivityStopped
08-16 15:27:12.399  6974  7031 D io.jxcore.node.LifeCycleMonitor: onActivityDestroyed
08-16 15:27:12.400  6974  7031 D io.jxcore.node.LifeCycleMonitor: onActivityPaused
,08-16 15:27:12.410  6974  7031 I System.out: Running OutgoingSocketThread
08-16 15:27:12.412  6974  8791 D io.jxcore.node.OutgoingSocketThread: Server socket local port: 57775
08-16 15:27:12.412  6974  8791 I io.jxcore.node.OutgoingSocketThread: Now accepting connections...
08-16 15:27:12.719  1044  1525 E WifiStateMachine:  ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-16 15:27:12.720  1044  1525 E WifiStateMachine:  L2ConnectedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-16 15:27:12.720  1044  1525 E WifiStateMachine:  ConnectModeState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-16 15:27:12.720  1044  1525 E WifiStateMachine:  DriverStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-16 15:27:12.721  1044  1525 E WifiStateMachine:  SupplicantStartedState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
08-16 15:27:12.721  1044  1525 E WifiStateMachine:  DefaultState CMD_OBTAINING_IP_ADDRESS_WATCHDOG_TIMER 2 0
,08-16 15:27:13.203  8706  8726 I GAV4    : Thread[GAThread,5,main]: No campaign data found.
,08-16 15:27:13.954  1044  2009 I ActivityManager: Killing 7798:com.lge.settings.easy/1000 (adj 15): empty #17
,08-16 15:27:13.987  1044  1886 W libprocessgroup: failed to open /acct/uid_1000/pid_7798/cgroup.procs: No such file or directory
,08-16 15:27:15.253  1044  1525 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2447 sc=60 link=72 tx=28.4, 0.0, 0.0  rx=24.3 bcn=0 [on:0 tx:0 rx:0 period:3004] from screen [on:0 period:-1819747275] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 15:27:15.266  1044  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-54 f=2447 sc=60 link=72 tx=28.4, 0.0, 0.0  rx=24.3 bcn=0 [on:0 tx:0 rx:0 period:10] from screen [on:0 period:-1819747265] gl rssi=-54 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 15:27:15.266  1044  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 15:27:15.427  6974  8791 I io.jxcore.node.OutgoingSocketThread: Incoming data from address: /127.0.0.1, port: 57775
08-16 15:27:15.427  6974  8791 D io.jxcore.node.OutgoingSocketThread: Setting local streams and starting stream copying threads...
08-16 15:27:15.427  6974  8791 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 15:27:15.427  6974  8791 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 15:27:15.427  6974  8791 I io.jxcore.node.OutgoingSocketThread: startStreamCopyingThreads: OK (thread ID: 1234)
,08-16 15:27:15.434  6974  8794 I io.jxcore.node.IncomingSocketThread: Local host address: localhost/127.0.0.1, port: 57775
08-16 15:27:15.434  6974  8794 D io.jxcore.node.IncomingSocketThread: Setting local streams and starting stream copying threads...
08-16 15:27:15.434  6974  8794 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 15:27:15.435  6974  8794 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 15:27:15.435  6974  8794 I io.jxcore.node.IncomingSocketThread: startStreamCopyingThreads: OK (thread ID: 4321)
08-16 15:27:15.437  6974  8797 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 920, name: OutgoingSocketThread/Receiver)
08-16 15:27:15.438  6974  8797 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 920, thread name: OutgoingSocketThread/Receiver)
08-16 15:27:15.438  6974  8797 I io.jxcore.node.OutgoingSocketThread: The receiving thread is done
08-16 15:27:15.438  6974  8797 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 920, name: OutgoingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 207 and the total number of bytes written 207
08-16 15:27:15.440  6974  8796 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 919, name: OutgoingSocketThread/Sender)
08-16 15:27:15.441  6974  8799 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 922, name: IncomingSocketThread/Receiver)
08-16 15:27:15.441  6974  8799 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 922, thread name: IncomingSocketThread/Receiver)
08-16 15:27:15.441  6974  8799 I io.jxcore.node.IncomingSocketThread: The receiving thread is done
08-16 15:27:15.441  6974  8799 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 922, name: IncomingSocketThread/Receiver), during the lifetime of the thread the total number of bytes read was 192 and the total number of bytes written 192
08-16 15:27:15.443  6974  8798 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 921, name: IncomingSocketThread/Sender)
,08-16 15:27:17.457  1589  1589 I [SystemUI]QPairHandler: onReceive = android.intent.action.PACKAGE_CHANGED
,08-16 15:27:17.514  1044  1419 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 15:27:17.551  1044  1115 I ActivityManager: Start proc com.google.android.talk for broadcast com.google.android.talk/com.google.android.apps.hangouts.phone.PackageReplacedReceiver: pid=8800 uid=10072 gids={50072, 9997, 3003, 1028, 1015, 3002} abi=armeabi-v7a
,08-16 15:27:17.563  1589  1589 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_CHANGED
,08-16 15:27:17.566  1589  1589 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_CHANGED, packageName : com.google.android.gms
08-16 15:27:17.590  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 15:27:17.603  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 15:27:17.607  1044  1044 D administrator: Handling package changes for user 0
,08-16 15:27:17.639  8800  8800 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
,08-16 15:27:17.714  1044  1044 I NotificationService: action=android.intent.action.PACKAGE_CHANGED queryReplace=false
08-16 15:27:17.714  1044  1044 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_CHANGED dat=package:com.google.android.gms flg=0x4000010 (has extras) }
,08-16 15:27:17.733  8800  8800 D LgDataFeature: LgDataFeature() Constructor: none
08-16 15:27:17.733  8800  8800 D LgDataFeature: LgDataFeature() Constructor Done, null
08-16 15:27:17.778  1044  1114 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
,08-16 15:27:17.786  1044  1114 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-16 15:27:17.795  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
08-16 15:27:17.796  2470  2470 V GmsNetworkLocationProvi: DISABLE
,08-16 15:27:17.826  2470  2470 E GCoreFlp: Bound FusedProviderService with LocationManager
,08-16 15:27:17.850  1044  1114 D LocationProviderProxy: applying state to connected service
,08-16 15:27:17.878  8800  8843 I Babel   : MmsConfig: mnc/mcc: 0/0
08-16 15:27:17.879  8800  8843 I Babel   : MmsConfig.loadMmsSettings
,08-16 15:27:17.885  8800  8843 I Babel   : MmsConfig.loadDeviceMmsSettings from API: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-16 15:27:17.885  8800  8843 I Babel   : MmsConfig.loadFromDatabase
,08-16 15:27:17.903  8800  8843 E Babel   : canonicalizeMccMnc: invalid mccmnc 
08-16 15:27:17.903  8800  8843 I Babel   : MmsConfig.loadFromResources
08-16 15:27:17.906  8800  8843 E Babel   : canonicalizeMccMnc: invalid mccmnc nullnull
08-16 15:27:17.906  8800  8843 I Babel   : MmsConfig.loadMmsSettings: mUserAgent=LG-D855 LG-Android-MMS-V4.0/1.2, mUaProfUrl=http://gsm.lge.com/html/gsm/D855-M3-D1.xml
08-16 15:27:17.912  8800  8800 W Settings: Setting airplane_mode_on has moved from android.provider.Settings.System to android.provider.Settings.Global, returning read-only value.
,08-16 15:27:17.921  8800  8842 W AudioCapabilities: Unsupported mime audio/evrc
08-16 15:27:17.922  8800  8842 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 15:27:17.925  8800  8842 W VideoCapabilities: Unrecognized profile 2130706433 for video/avc
,08-16 15:27:17.937  8800  8842 W AudioCapabilities: Unsupported mime audio/amr-wb-plus
,08-16 15:27:17.939  8800  8842 W AudioCapabilities: Unsupported mime audio/qcelp
08-16 15:27:17.941  1803  8846 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_CHANGED and uri=com.google.android.gms
08-16 15:27:17.942  1803  8846 I PackageBroadcastService: Null package name or gms related package.  Ignoreing.
08-16 15:27:17.943  8800  8842 W AudioCapabilities: Unsupported mime audio/evrc
08-16 15:27:17.947  7278  7278 I AppUp4:CustModeStarterReceiver: onReceive
,08-16 15:27:17.956  7278  7278 D AppUp4:CustFacade: Context : android.app.ReceiverRestrictedContext@37a4402e
08-16 15:27:17.956  7278  7278 D AppUp4:CustFacade: isCustomizationCompleted : false
08-16 15:27:17.957  7278  7278 D AppUp4:CustFacade: isPhone : true
08-16 15:27:17.957  7278  7278 D AppUp4:CustModeStarterReceiver: begin check event
08-16 15:27:17.957  7278  7278 I AppUp4:CustModeStarterReceiver: Event For Nothing, skip.
08-16 15:27:17.960  8800  8842 W VideoCapabilities: Unsupported mime video/x-ms-wmv
08-16 15:27:17.962  8800  8842 W VideoCapabilities: Unsupported mime video/divx
08-16 15:27:17.963  8800  8842 W VideoCapabilities: Unsupported mime video/divx311
08-16 15:27:17.964  1803  5203 I Icing   : updateResources: need to parse e{com.google.android.gms}
08-16 15:27:17.965  8800  8842 W VideoCapabilities: Unsupported mime video/divx4
08-16 15:27:17.969  8800  8842 W VideoCapabilities: Unsupported mime video/mp4v-esdp
,08-16 15:27:17.987  1044  2036 I ActivityManager: Start proc com.android.contacts for broadcast com.android.contacts/.quickcontact.PackageIntentReceiver: pid=8849 uid=10019 gids={50019, 9997, 3003, 1028, 1015, 1023, 4002} abi=armeabi-v7a
08-16 15:27:17.988  8800  8842 I VideoCapabilities: Unsupported profile 4 for video/mp4v-es
08-16 15:27:17.995  1044  2009 I ActivityManager: Killing 8426:com.lge.bnr/1000 (adj 15): empty #17
08-16 15:27:17.998  8800  8842 W AudioCapabilities: Unsupported mime audio/eac3
08-16 15:27:17.999  8800  8842 W AudioCapabilities: Unsupported mime audio/ac3
08-16 15:27:18.000  8800  8842 W AudioCapabilities: Unsupported mime audio/g726
08-16 15:27:18.001  8800  8842 W AudioCapabilities: Unsupported mime audio/wma-voice
08-16 15:27:18.001  8800  8842 W AudioCapabilities: Unsupported mime audio/x-ms-wma
08-16 15:27:18.002   353   353 I art     : Explicit concurrent mark sweep GC freed 706(30KB) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 276us total 15.186ms
08-16 15:27:18.002  8800  8842 W AudioCapabilities: Unsupported mime audio/adpcm
,08-16 15:27:18.005  8800  8842 W VideoCapabilities: Unsupported mime video/theora
08-16 15:27:18.006  8800  8842 W VideoCapabilities: Unsupported mime video/mjpg
08-16 15:27:18.014   353   353 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 249us total 12.075ms
08-16 15:27:18.026   353   353 I art     : Explicit concurrent mark sweep GC freed 5(160B) AllocSpace objects, 0(0B) LOS objects, 54% free, 26MB/58MB, paused 223us total 11.840ms
,08-16 15:27:18.086  1044  1977 W libprocessgroup: failed to open /acct/uid_1000/pid_8426/cgroup.procs: No such file or directory
,08-16 15:27:18.126  8849  8849 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 15:27:18.127  8849  8849 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
,08-16 15:27:18.127  8849  8849 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 15:27:18.129  8849  8849 W ResourcesManager: Asset path '/system/framework/lghiddenlibs.jar' does not exist or contains no resources.
08-16 15:27:18.129  8849  8849 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 15:27:18.195  8849  8849 I SystemConfig: BUILD Country: EU
08-16 15:27:18.196  8849  8849 I SystemConfig: BUILD Operator: OPEN
,08-16 15:27:18.235  1044  1916 I ActivityManager: Killing 8397:com.lge.sync/1000 (adj 15): empty #17
,08-16 15:27:18.281  1044  1525 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=14.7, 0.0, 0.0  rx=12.2 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1819744247] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 15:27:18.282  1044  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=14.7, 0.0, 0.0  rx=12.2 bcn=0 [on:0 tx:0 rx:0 period:1] from screen [on:0 period:-1819744246] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
08-16 15:27:18.282  1044  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 15:27:18.327  1044  1907 W libprocessgroup: failed to open /acct/uid_1000/pid_8397/cgroup.procs: No such file or directory
,08-16 15:27:18.338  8849  8869 I SystemConfig: pm.hasSystemFeature(com.lge.ims.rcs) = false
08-16 15:27:18.338  8849  8869 I SystemConfig: existFile = false
,08-16 15:27:18.338  8849  8869 I SystemConfig: canReadFile = false
08-16 15:27:18.339  8849  8869 I SystemConfig: systemFeature RCS result false
08-16 15:27:18.339  8849  8869 D SystemConfig: refreshRcsSupport() :false
,08-16 15:27:18.404  1044  1773 I ActivityManager: Start proc com.android.gallery3d for broadcast com.android.gallery3d/.app.PackagesMonitor: pid=8874 uid=10027 gids={50027, 9997, 3003, 1028, 1015, 1023, 4002, 4003} abi=armeabi-v7a
,08-16 15:27:18.426  6974  7031 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 931)
08-16 15:27:18.427  6974  7031 V io.jxcore.node.SocketThreadBase: close: Closing the localhost socket...
08-16 15:27:18.427  6974  7031 I io.jxcore.node.SocketThreadBase: close: Complete (thread ID: 932)
,08-16 15:27:18.430  6974  7031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 15:27:18.430  6974  7031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b7c5644 added. We now have 3 listener(s)
08-16 15:27:18.431  1044  2018 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:27:18.433  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
,08-16 15:27:18.433  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 15:27:18.433  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 15:27:18.433  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 15:27:18.433  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32d1a32d added. We now have 4 listener(s)
08-16 15:27:18.434  6974  7031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 15:27:18.434  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 15:27:18.436  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 15:27:18.439  6974  7031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 15:27:18.439  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:27:18.439  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:27:18.439  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:27:18.439  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:27:18.439  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:27:18.439  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:27:18.439  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 15:27:18.441  6974  7031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 15:27:18.441  6974  7031 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 15:27:18.441  6974  7031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:27:18.442  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:27:18.442  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:27:18.442  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:27:18.442  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:27:18.442  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 15:27:18.442  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 15:27:18.442  6974  7031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b7c5644 removed from the list
08-16 15:27:18.442  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:27:18.442  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32d1a32d removed from the list
08-16 15:27:18.442  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:27:18.442  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:27:18.443  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:27:18.443  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:27:18.445  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:27:18.445  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:27:18.445  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:27:18.445  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32d1a32d not in the list
08-16 15:27:18.445  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:27:18.445  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:27:18.446  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:27:18.447  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:27:18.447  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:27:18.447  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:27:18.447  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@32d1a32d not in the list
08-16 15:27:18.447  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:27:18.447  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:27:18.447  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:27:18.448  6974  7031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3b7c5644 not in the list
08-16 15:27:18.448  6974  7031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 15:27:18.448  6974  7031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@247b15f3 added. We now have 3 listener(s)
08-16 15:27:18.449  1044  1907 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:27:18.454  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 15:27:18.454  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 15:27:18.454  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 15:27:18.454  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 15:27:18.455  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@360a92b0 added. We now have 4 listener(s)
08-16 15:27:18.455  6974  7031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 15:27:18.455  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 15:27:18.459  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 15:27:18.463  6974  7031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 15:27:18.463  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:27:18.463  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:27:18.463  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:27:18.463  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:27:18.463  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:27:18.463  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:27:18.463  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 15:27:18.469  6974  7031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 15:27:18.469  6974  7031 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 15:27:18.470  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 15:27:18.471  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 15:27:18.471  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 15:27:18.471  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 15:27:18.471  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 15:27:18.472  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:27:18.474  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:27:18.567  1044  1060 I art     : Explicit concurrent mark sweep GC freed 35057(1819KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 2.726ms total 105.112ms
,08-16 15:27:18.575  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 15:27:18.577  1044  1886 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:27:18.578  8874  8874 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 15:27:18.578  8874  8874 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 15:27:18.578  8874  8874 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 15:27:18.579  8874  8874 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 15:27:18.585  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 15:27:18.587  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 15:27:18.589  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 15:27:18.589  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 15:27:18.590  6974  7031 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 15:27:18.590  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:27:18.591  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:27:18.677  8874  8874 I AppConfig: Total System Memory = 2995761152
,08-16 15:27:18.689  8874  8874 D SystemHelper: region [EU], country [EU], operator [OPEN], sub-operator []
,08-16 15:27:18.790  1044  1060 I ActivityManager: Start proc com.android.vending for broadcast com.android.vending/com.google.android.finsky.receivers.PackageMonitorReceiver$RegisteredReceiver: pid=8893 uid=10044 gids={50044, 9997, 3003, 1028, 1015} abi=armeabi-v7a
08-16 15:27:18.792  1044  1060 I ActivityManager: Killing 7831:com.uei.lg.quicksetsdk.maxq616/1000 (adj 15): empty #17
08-16 15:27:18.817  8291  8291 I QRemote : [RemoteControlManager.java:195:onServiceDisconnected()] oooooo start
08-16 15:27:18.817  8291  8291 W System.err: android.os.DeadObjectException
08-16 15:27:18.817  8291  8291 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 15:27:18.817  8291  8291 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
,08-16 15:27:18.817  8291  8291 W System.err: 	at com.uei.control.IControl.unregisterCallback(IControl.java:502)
08-16 15:27:18.817  8291  8291 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:199)
08-16 15:27:18.818  8291  8291 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 15:27:18.818  8291  8291 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 15:27:18.818  8291  8291 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 15:27:18.818  8291  8291 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 15:27:18.818  8291  8291 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 15:27:18.818  8291  8291 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 15:27:18.818  8291  8291 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 15:27:18.818  8291  8291 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 15:27:18.818  8291  8291 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 15:27:18.818  8291  8291 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 15:27:18.818  8291  8291 E UEI.SmartControl: IControl.unregisterCallback error: android.os.DeadObjectException
08-16 15:27:18.818  8291  8291 W System.err: android.os.DeadObjectException
08-16 15:27:18.819  8291  8291 W System.err: 	at android.os.BinderProxy.transactNative(Native Method)
08-16 15:27:18.819  8291  8291 W System.err: 	at android.os.BinderProxy.transact(Binder.java:496)
08-16 15:27:18.819  8291  8291 W System.err: 	at com.uei.control.IControl.unregisterSetupReadyCallback(IControl.java:818)
08-16 15:27:18.819  8291  8291 W System.err: 	at com.lge.qremote.remote.system.RemoteControlManager$1.onServiceDisconnected(RemoteControlManager.java:200)
08-16 15:27:18.819  8291  8291 W System.err: 	at android.app.LoadedApk$ServiceDispatcher.doDeath(LoadedApk.java:1303)
08-16 15:27:18.819  8291  8291 W System.err: 	at android.app.LoadedApk$ServiceDispatcher$RunConnection.run(LoadedApk.java:1317)
08-16 15:27:18.819  8291  8291 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 15:27:18.819  8291  8291 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 15:27:18.819  8291  8291 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 15:27:18.819  8291  8291 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 15:27:18.819  8291  8291 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 15:27:18.819  8291  8291 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 15:27:18.819  8291  8291 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 15:27:18.819  8291  8291 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 15:27:18.819  8291  8291 E UEI.SmartControl: IControl.unregisterSetupReadyCallback error: android.os.DeadObjectException
08-16 15:27:18.820  8291  8291 I QRemote : [RemoteControlManager.java:203:onServiceDisconnected()] oooooo Control unbind before rebinding.
08-16 15:27:19.036  1044  2036 W libprocessgroup: failed to open /acct/uid_1000/pid_7831/cgroup.procs: No such file or directory
08-16 15:27:19.038  1044  2036 W ActivityManager: Scheduling restart of crashed service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service in 1000ms
,08-16 15:27:19.047  8291  8291 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]10
08-16 15:27:19.048  8291  8291 I QRemote : [RemoteControlManager.java:157:onBindIRService()] oooooo bind
08-16 15:27:19.096  1044  1916 I ActivityManager: Start proc com.uei.lg.quicksetsdk.maxq616 for service com.uei.lg.quicksetsdk.maxq616/com.uei.control.Service: pid=8910 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
,08-16 15:27:19.098  8291  8291 D QRemote : [RemoteControlManager.java:441:setStateInt()] oooooo RemoteControl set [State]11
,08-16 15:27:19.178  8910  8910 D UEI.SmartControl: Quickset Services start...
,08-16 15:27:19.180  8910  8910 I UEI.SmartControl: Manufacture = LGE
,08-16 15:27:19.180  8910  8910 D UEI.SmartControl: Id = LGNevo
08-16 15:27:19.182  8910  8910 D UEI.SmartControl: File observer start...
08-16 15:27:19.184  8910  8910 E UEI.SmartControl: IR Port is disabled: false
08-16 15:27:19.184  8910  8910 D UEI.SmartControl: Starting file observer...
08-16 15:27:19.184  8910  8910 D UEI.SmartControl: Extracting JNI libs...
08-16 15:27:19.184  8910  8910 D UEI.SmartControl: --- this system supports 32-bit or 64-bit only
08-16 15:27:19.254  8910  8910 D UEI.SmartControl: --- Build.SUPPORTED_ABIS:->armeabi-v7a<-
08-16 15:27:19.254  8910  8910 D UEI.SmartControl: --- Checking lib: libqs_armeabi-v7a.zip
08-16 15:27:19.254  8910  8910 D UEI.SmartControl: --- Extracting JNI libs: libqs_armeabi-v7a.zip
,08-16 15:27:19.278  8910  8910 I UEI.SmartControl: --- Selecting new region: 6
,08-16 15:27:19.280  8910  8910 I UEI.SmartControl: Model = LG-D855
08-16 15:27:19.282  8910  8910 D UEI.SmartControl: QS Service created
,08-16 15:27:19.292  8910  8910 I UEI.SmartControl: Service initServices...
,08-16 15:27:19.295  8910  8910 D UEI.SmartControl: QS start get config
,08-16 15:27:19.326  8893  8893 D Finsky  : [1] FinskyApp.onCreate: Initializing network with DFE https://android.clients.google.com/fdfe/
,08-16 15:27:19.330  8910  8910 D UEI.SmartControl: Loading JNI Libs...
08-16 15:27:19.396  8893  8893 D LgDataFeature: LgDataFeature() Constructor: none
08-16 15:27:19.396  8893  8893 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 15:27:19.442  8893  8893 D Finsky  : [1] DailyHygiene.goMakeHygieneIfDirty: No need to run daily hygiene.
,08-16 15:27:19.460  8893  8893 W Settings: Setting download_manager_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
08-16 15:27:19.461  8893  8893 W Settings: Setting download_manager_recommended_max_bytes_over_mobile has moved from android.provider.Settings.Secure to android.provider.Settings.Global.
,08-16 15:27:19.487  8893  8893 W Finsky  : [1] FinskyApp.getCurrentAccount: No account configured on this device.
,08-16 15:27:19.488  8893  8893 W Finsky  : [1] FinskyApp.getDfeApi: No account configured on this device.
,08-16 15:27:19.504  1044  2009 I ActivityManager: Killing 7091:com.android.settings/1000 (adj 15): empty #17
,08-16 15:27:19.554  8910  8910 I UEI.SmartControl: Supports setup maps: true
,08-16 15:27:19.556  8910  8910 D UEI.SmartControl: QS start statue = true Error code = 0
08-16 15:27:19.557  8910  8910 I UEI.SmartControl: QS version = v2.7.10.1_RC1
08-16 15:27:19.557  8910  8910 I UEI.SmartControl: QS DB version: LG_Optimus_G2_Phone_Korea_database_v3.14_nevosmart
08-16 15:27:19.557  8910  8910 I UEI.SmartControl: ### init IR Blaster...
08-16 15:27:19.561  8910  8910 D serial_port: Configuring serial port
08-16 15:27:19.563  8910  8910 E UEI.SmartControl: UEIBLaster setting for 616
08-16 15:27:19.564  8910  8910 I UEI.SmartControl: Setting serial record hearder size = 2
08-16 15:27:19.564  8910  8910 I UEI.SmartControl: configuring settings for MAXQ616
08-16 15:27:19.564  8910  8910 I UEI.SmartControl: Get version...
08-16 15:27:19.572  1044  1981 W libprocessgroup: failed to open /acct/uid_1000/pid_7091/cgroup.procs: No such file or directory
,08-16 15:27:19.586  5023  8958 I UpdateIcingCorporaServi: Updating corpora: APPS=com.google.android.gms, CONTACTS=MAYBE
08-16 15:27:19.592  8910  8956 D UEI.SmartControl: serial port data available: 21
08-16 15:27:19.620  8910  8910 D UEI.SmartControl: MAXQ616 A2-X4 software.
08-16 15:27:19.620  8910  8910 I UEI.SmartControl: IR Blaster version: 256702256704300002
08-16 15:27:19.620  8910  8910 I UEI.SmartControl: QS saving settings...
08-16 15:27:19.621  8910  8910 D UEI.SmartControl: IR Blaster version: 25672567
,08-16 15:27:19.635  1044  1638 I ActivityManager: Start proc com.lge.lockscreensettings for broadcast com.lge.lockscreensettings/.PackageIntentReceiver: pid=8960 uid=10080 gids={50080, 9997, 1028, 1015} abi=armeabi-v7a
,08-16 15:27:19.641  8910  8956 D UEI.SmartControl: serial port data available: 4
08-16 15:27:19.643  2826  2931 V DownloadManager: starting query, database is not null; projection[0] is _id; projection[1] is entity; projection[2] is _data; projection[3] is mimetype; projection[4] is visibility; projection[5] is destination; projection[6] is control; projection[7] is status; projection[8] is lastmod; projection[9] is notificationpackage; projection[10] is notificationclass; projection[11] is total_bytes; projection[12] is current_bytes; projection[13] is title; projection[14] is description; projection[15] is uri; projection[16] is is_visible_in_downloads_ui; projection[17] is hint; projection[18] is mediaprovider_uri; projection[19] is deleted; projection[20] is title AS _display_name; projection[21] is total_bytes AS _size; projection[22] is drm_status; projection[23] is external_control; projection[24] is cid; projection[25] is multi; projection[26] is retryinsinglemode; selection is null; selectionArgs is null; sort is null.
08-16 15:27:19.651  2826  2931 V DownloadManager: created cursor android.database.sqlite.SQLiteCursor@c7984a on behalf of 8893
,08-16 15:27:19.683  8910  8978 I UEI.SmartControl: Device manager: loading config....
08-16 15:27:19.683  8910  8978 D UEI.SmartControl: ----------- loading internal config...
,08-16 15:27:19.687  8910  8910 W ContextImpl: Calling a method in the system process without a qualified user: android.app.ContextImpl.bindService:1821 android.content.ContextWrapper.bindService:538 com.uei.control.Service.b:-1 com.uei.control.Service.a:-1 com.uei.control.Service.onCreate:-1 
08-16 15:27:19.689  8910  8910 E UEI.SmartControl: Services init done
08-16 15:27:19.690  8910  8910 D UEI.SmartControl: QS Service init finished
08-16 15:27:19.691  8893  8893 D Finsky  : [1] GmsCoreHelper.cleanupNlp: result=false type=4
08-16 15:27:19.694  8910  8910 D UEI.SmartControl: QS Service version name: 2.1.91
08-16 15:27:19.694  8910  8910 D UEI.SmartControl: QS Service version code: 201091
08-16 15:27:19.695  8910  8910 D UEI.SmartControl: Service requested: Control
08-16 15:27:19.696  8910  8978 E UEI.SmartControl: Loading SETTINGS...
,08-16 15:27:19.701  8910  8910 D UEI.SmartControl: Request IControl service: devices are loaded...
08-16 15:27:19.707  8291  8291 I QRemote : [RemoteControlManager.java:183:onServiceConnected()] oooooo start
08-16 15:27:19.707  8910  8925 I UEI.SmartControl: ------ IControl API: 11
08-16 15:27:19.707  8910  8910 D UEI.SmartControl: Internal service binding...
08-16 15:27:19.708  8910  8925 I UEI.SmartControl: Registering callback...
08-16 15:27:19.710  8910  8982 I UEI.SmartControl: ------ IControl API: 19
,08-16 15:27:19.711  8910  8982 I UEI.SmartControl: Registering Services Ready callback...
08-16 15:27:19.715  8910  8978 D UEI.SmartControl: -- Open brand translation xml: brands_translations_ko
08-16 15:27:19.718  8893  8893 D Finsky  : [1] RestoreTracker.stopServiceIfDone: Restore complete with 0 success and 0 failed.
08-16 15:27:19.720  1044  1949 I ActivityManager: Killing 8291:com.lge.qremote/u0a112 (adj 15): empty #17
08-16 15:27:19.733  8960  8960 I LockScreenSettings: Wallpaper base directory = /data/data/com.lge.lockscreensettings/files/
08-16 15:27:19.736  8910  8977 I UEI.SmartControl: Notify AllClients services are ready: 0
08-16 15:27:19.737  8910  8977 D UEI.SmartControl: -----service ready thread exits
,08-16 15:27:19.787  1044  1562 W libprocessgroup: failed to open /acct/uid_10112/pid_8291/cgroup.procs: No such file or directory
,08-16 15:27:19.821  8960  8960 D LockScreenSettings: Quick window widget present in DB = com.lge.clock.quickcover.QuickCoverSettingActivity  true
08-16 15:27:19.821  8960  8960 D LockScreenSettings: Quick window widget present in DB = com.lge.camera.app.QuickWindowCameraActivity  true
08-16 15:27:19.821  8960  8960 D LockScreenSettings: Quick window widget present in DB = com.android.contacts.activities.QuickCircleActivity  true
08-16 15:27:19.821  8960  8960 D LockScreenSettings: Quick window widget present in DB = com.android.mms.quickcover.QuickCoverActivity  true
,08-16 15:27:19.821  8960  8960 D LockScreenSettings: Quick window widget present in DB = com.lge.music.MusicQuickCircle  true
08-16 15:27:19.821  8960  8960 D LockScreenSettings: Quick window widget present in DB = com.lge.lifetracker.QuickCover  true
08-16 15:27:19.849  1044  1916 I ActivityManager: Killing 8566:com.lge.email/u0a23 (adj 15): empty #17
,08-16 15:27:19.887  1044  1942 W libprocessgroup: failed to open /acct/uid_10023/pid_8566/cgroup.procs: No such file or directory
,08-16 15:27:20.092  1044  1562 V SIM_STK : Menu title from STK is T-Mobile
,08-16 15:27:20.107  5023  8958 I UpdateIcingCorporaServi: UpdateCorporaTask done [took 520 ms] updated apps [took 520 ms] 
,08-16 15:27:21.301  1044  1525 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=7.3, 0.0, 0.0  rx=6.1 bcn=0 [on:0 tx:0 rx:0 period:3005] from screen [on:0 period:-1819741227] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 15:27:21.313  1044  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=7.3, 0.0, 0.0  rx=6.1 bcn=0 [on:0 tx:0 rx:0 period:11] from screen [on:0 period:-1819741216] gl rssi=-55 ag=0 hr ticks 0,0,0 ls-=0 [56,56,60,60,65] brc=0 lrc=0
,08-16 15:27:21.313  1044  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 15:27:21.591  6974  7031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
,08-16 15:27:21.592  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:27:21.592  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 15:27:21.605  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:27:21.605  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:27:21.605  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 15:27:21.605  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 15:27:21.605  6974  7031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@247b15f3 removed from the list
08-16 15:27:21.606  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:27:21.606  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@360a92b0 removed from the list
08-16 15:27:21.606  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:27:21.606  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:27:21.607  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:27:21.607  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:27:21.608  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:27:21.608  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:27:21.611  6974  7031 D BluetoothLeScanner: could not find callback wrapper
08-16 15:27:21.611  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 15:27:21.611  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:27:21.611  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@360a92b0 not in the list
08-16 15:27:21.611  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:27:21.611  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:27:21.612  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 15:27:21.616  6974  7031 D BluetoothLeScanner: could not find callback wrapper
08-16 15:27:21.616  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 15:27:21.616  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:27:21.616  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:27:21.616  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@360a92b0 not in the list
08-16 15:27:21.616  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:27:21.616  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:27:21.616  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:27:21.616  6974  7031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@247b15f3 not in the list
08-16 15:27:21.617  6974  7031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 15:27:21.617  6974  7031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bfe29dc added. We now have 3 listener(s)
08-16 15:27:21.618  1044  1059 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:27:21.621  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 15:27:21.621  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 15:27:21.621  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 15:27:21.621  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 15:27:21.621  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38210ae5 added. We now have 4 listener(s)
08-16 15:27:21.621  6974  7031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 15:27:21.623  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 15:27:21.631  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 15:27:21.634  6974  7031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 15:27:21.634  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:27:21.634  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:27:21.634  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:27:21.634  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:27:21.634  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:27:21.634  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:27:21.634  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 15:27:21.638  6974  7031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
,08-16 15:27:21.640  6974  7031 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 15:27:21.642  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:27:21.645  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:27:21.645  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-16 15:27:21.646  6974  7031 I io.jxcore.node.StartStopOperationHandler: updateBeaconAdExtraInformation: New value: 1
08-16 15:27:21.646  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setBeaconAdExtraInformation: 0 -> 1
08-16 15:27:21.648  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should start/stop everything
08-16 15:27:21.648  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should start/stop everything
08-16 15:27:21.648  6974  7031 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections
08-16 15:27:21.648  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 15:27:21.651  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: startListeningForIncomingConnections: Starting...
,08-16 15:27:21.655  6974  7031 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: true
08-16 15:27:21.655  6974  7031 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: NOT_STARTED -> RUNNING
08-16 15:27:21.656  6974  6974 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: RUNNING
08-16 15:27:21.658  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: startListeningForIncomingConnections: OK
08-16 15:27:21.658  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: false, start advertiser: true
08-16 15:27:21.658  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 15:27:21.658  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 15:27:21.662  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 15:27:21.664  1044  2009 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:27:21.668  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
,08-16 15:27:21.672  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 15:27:21.673  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
08-16 15:27:21.674  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 4 listener(s) left
08-16 15:27:21.677  6974  7031 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 15:27:21.677  1044  1773 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:27:21.680  6974  8999 W BluetoothAdapter: getBluetoothService() called with no BluetoothManagerCallback
,08-16 15:27:21.682  8137  8260 D LGBluetoothServiceAdapter: [BTUI] createSocketChannel FD=84 mFd=82
08-16 15:27:21.683  6974  8999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Waiting for incoming connections...
08-16 15:27:24.338  1044  1525 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1819738190] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 15:27:24.341  1044  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=3.7, 0.0, 0.0  rx=3.0 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1819738187] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 15:27:24.341  1044  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 15:27:24.677  8910  8979 D UEI.SmartControl: Internal timer expired: 1
,08-16 15:27:24.677  8910  8979 D UEI.SmartControl: unbind internal service
,08-16 15:27:24.685  6974  7031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:27:24.687  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:27:24.688  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Stop operation: Should start/stop everything
08-16 15:27:24.688  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: stopListeningForIncomingConnections
08-16 15:27:24.688  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: stopListeningForIncomingConnections: Stopping...
08-16 15:27:24.688  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: shutdown
08-16 15:27:24.691  6974  8999 V org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: closeBluetoothServerSocket: Bluetooth server socket closed
08-16 15:27:24.692  6974  8999 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothServerThread: Exiting thread
08-16 15:27:24.692  6974  8999 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: onServerStopped: Was explicitly stopped: true
08-16 15:27:24.696  6974  6974 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: onIsServerStartedChanged: false
,08-16 15:27:24.699  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 15:27:24.699  6974  7031 D org.thaliproject.p2p.btconnectorlib.ConnectionManager: setState: RUNNING -> NOT_STARTED
08-16 15:27:24.699  6974  6974 I io.jxcore.node.ConnectionHelper: onConnectionManagerStateChanged: NOT_STARTED
08-16 15:27:24.700  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: cancelAllConnectionAttempts
08-16 15:27:24.700  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:27:24.700  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 15:27:24.707  6974  6974 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:27:24.708  6974  6974 D io.jxcore.node.StartStopOperationHandler: checkCurrentOperationStatus: Operation successfully executed
,08-16 15:27:24.711  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:27:24.711  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:27:24.711  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 15:27:24.711  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 15:27:24.711  6974  7031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bfe29dc removed from the list
08-16 15:27:24.711  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:27:24.711  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38210ae5 removed from the list
08-16 15:27:24.711  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:27:24.711  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:27:24.719  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:27:24.719  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:27:24.721  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:27:24.721  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
,08-16 15:27:24.725  6974  7031 D BluetoothLeScanner: could not find callback wrapper
08-16 15:27:24.725  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 15:27:24.725  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:27:24.725  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38210ae5 not in the list
08-16 15:27:24.725  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:27:24.725  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:27:24.726  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:27:24.727  6974  7031 D BluetoothLeScanner: could not find callback wrapper
08-16 15:27:24.727  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 15:27:24.727  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:27:24.727  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:27:24.727  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@38210ae5 not in the list
08-16 15:27:24.727  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:27:24.727  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:27:24.727  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:27:24.727  6974  7031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@3bfe29dc not in the list
08-16 15:27:24.728  6974  7031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 15:27:24.728  6974  7031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c5c7061 added. We now have 3 listener(s)
08-16 15:27:24.729  8910  8910 D UEI.SmartControl: Service.onUnbind: IControl
08-16 15:27:24.730  1044  1638 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:27:24.733  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 15:27:24.733  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 15:27:24.733  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 15:27:24.733  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 15:27:24.733  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99f9786 added. We now have 4 listener(s)
08-16 15:27:24.733  6974  7031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
08-16 15:27:24.736  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
,08-16 15:27:24.743  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 15:27:24.747  6974  7031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 15:27:24.747  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:27:24.747  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:27:24.747  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:27:24.747  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:27:24.747  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:27:24.747  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:27:24.747  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
08-16 15:27:24.750  6974  7031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 15:27:24.750  6974  7031 D io.jxcore.node.ConnectivityMonitor: start: OK
,08-16 15:27:24.754  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:27:24.756  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:27:24.756  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 15:27:24.756  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Executing: Start operation: Should affect listening to advertisements only
08-16 15:27:24.757  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: start: Discovery mode: BLE, start discovery: true, start advertiser: false
08-16 15:27:24.757  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 15:27:24.757  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: bind: Binding a new listener
08-16 15:27:24.760  8910  8910 D UEI.SmartControl: Service.onDestroy
08-16 15:27:24.760  8910  8910 D UEI.SmartControl: Lock is in USE false
08-16 15:27:24.760  8910  8910 D UEI.SmartControl: unbind internal service
08-16 15:27:24.760  8910  8910 W System.err: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@938313a
08-16 15:27:24.760  8910  8910 W System.err: 	at android.app.LoadedApk.forgetServiceDispatcher(LoadedApk.java:1119)
08-16 15:27:24.761  8910  8910 W System.err: 	at android.app.ContextImpl.unbindService(ContextImpl.java:1873)
08-16 15:27:24.761  8910  8910 W System.err: 	at android.content.ContextWrapper.unbindService(ContextWrapper.java:550)
08-16 15:27:24.761  8910  8910 W System.err: 	at com.uei.control.Service.c(Unknown Source)
08-16 15:27:24.761  8910  8910 W System.err: 	at com.uei.control.Service.onDestroy(Unknown Source)
08-16 15:27:24.761  8910  8910 W System.err: 	at android.app.ActivityThread.handleStopService(ActivityThread.java:2901)
08-16 15:27:24.761  8910  8910 W System.err: 	at android.app.ActivityThread.access$2200(ActivityThread.java:148)
08-16 15:27:24.761  8910  8910 W System.err: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1386)
08-16 15:27:24.761  8910  8910 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 15:27:24.761  8910  8910 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 15:27:24.761  8910  8910 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 15:27:24.761  8910  8910 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 15:27:24.761  8910  8910 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 15:27:24.761  8910  8910 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 15:27:24.761  8910  8910 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 15:27:24.761  8910  8910 E UEI.SmartControl: java.lang.IllegalArgumentException: Service not registered: com.uei.control.g@938313a
08-16 15:27:24.765  8910  8910 D serial_port: close(fd = 25)
,08-16 15:27:24.770  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManager: getBlePeerDiscovererInstanceAndCheckBluetoothMacAddress: Constructing...
08-16 15:27:24.770  1044  1886 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:27:24.774  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleAdvertiser: setAdvertiseSettings: Mode: 2, Tx power level: 3, timeout: 0, is connectable: false
08-16 15:27:24.776  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: setScanSettings: Mode: 2, report delay in milliseconds: 500, scan result type: 0
08-16 15:27:24.778  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.wifi.WifiDirectManager: release: No more listeners, de-initializing...
,08-16 15:27:24.779  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 15:27:24.783  6974  7031 E io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: Failed to start the discovery manager
08-16 15:27:24.786  8910  8910 I UEI.SmartControl: Serial port is closed.
08-16 15:27:24.788  8910  8910 I UEI.SmartControl: Serial port is closed.
08-16 15:27:24.788  8910  8910 D UEI.SmartControl: Blaster closed
08-16 15:27:24.788  8910  8910 D UEI.SmartControl: Shut down QS...
08-16 15:27:24.789  8910  8910 D UEI.SmartControl: Stopping QS lib
08-16 15:27:24.789  8910  8910 D UEI.SmartControl: QS lib stop result = true
08-16 15:27:24.789  8910  8910 D UEI.SmartControl: Stopped QS lib
08-16 15:27:24.789  8910  8910 D UEI.SmartControl: Stopped file observer...
08-16 15:27:24.790  8910  8910 D UEI.SmartControl: QS shutdown complete
,08-16 15:27:26.649  1044  1773 D ConnectivityService: reportBadNetwork(NetworkAgentInfo [WIFI () - 102]) by 10005
,08-16 15:27:26.652  1044  8470 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: ValidatedState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:26.652  1044  8470 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: DefaultState{ when=-3ms what=532488 arg1=10005 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:26.652  1044  8470 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Forcing reevaluation
08-16 15:27:26.652  1044  8470 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: EvaluatingState{ when=0 what=532486 arg1=3 target=com.android.internal.util.StateMachine$SmHandler }
08-16 15:27:26.652  1044  8470 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Checking http://clients3.google.com/generate_204 on "NG700"
08-16 15:27:26.687  1044  8470 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: isCaptivePortal: ret=204 headers={null=[HTTP/1.1 204 No Content], Content-Length=[0], Date=[Tue, 16 Aug 2016 13:27:26 GMT], X-Android-Received-Millis=[1471354046686], X-Android-Response-Source=[NETWORK 204], X-Android-Sent-Millis=[1471354046656]}
08-16 15:27:26.687  1044  8470 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Don't send network conditions - lacking user consent.
08-16 15:27:26.687  1044  8470 D NetworkMonitor NetworkAgentInfo [WIFI () - null]: Validated
,08-16 15:27:26.691  1044  1531 D ConnectivityService: Validated NetworkAgentInfo [WIFI () - 102]
,08-16 15:27:26.691  1044  1531 D ConnectivityService: rematching NetworkAgentInfo [WIFI () - 102]
,08-16 15:27:26.691  1044  1531 D ConnectivityService:  network has: [ Transports: WIFI Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN LinkUpBandwidth>=1048576Kbps LinkDnBandwidth>=1048576Kbps]
08-16 15:27:26.691  1044  1531 D ConnectivityService:   checking if request is satisfied: NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 15:27:26.691  1044  1531 D ConnectivityService:     satisfied: NetworkRequest [ id=2, legacyType=-1, [] ], isRequest:false
08-16 15:27:26.691  1044  1531 D ConnectivityService: Network NetworkAgentInfo [WIFI () - 102] was already satisfying request 1. No change.
08-16 15:27:26.691  1044  1531 D ConnectivityService: notifyType AVAILABLE for NetworkAgentInfo [WIFI () - 102]
08-16 15:27:26.691  1044  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=1, legacyType=-1, [ Capabilities: INTERNET&NOT_RESTRICTED&TRUSTED&NOT_VPN] ]
08-16 15:27:26.691  1044  1531 D ConnectivityService:  sending notification for NetworkRequest [ id=2, legacyType=-1, [] ]
08-16 15:27:26.692  1044  1531 D ConnectivityService: sending notification AVAILABLE for NetworkRequest [ id=2, legacyType=-1, [] ]
,08-16 15:27:26.693  1589  2063 D ConnectivityManager.CallbackHandler: CM callback handler got msg 524290
08-16 15:27:27.361  1044  1525 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:3003] from screen [on:0 period:-1819735168] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 15:27:27.364  1044  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=1.8, 0.0, 0.0  rx=1.5 bcn=0 [on:0 tx:0 rx:0 period:4] from screen [on:0 period:-1819735164] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 15:27:27.376  1044  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
08-16 15:27:27.790  6974  7031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:27:27.791  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:27:27.791  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
,08-16 15:27:27.798  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:27:27.798  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:27:27.798  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 15:27:27.798  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 15:27:27.798  6974  7031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c5c7061 removed from the list
08-16 15:27:27.798  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:27:27.798  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99f9786 removed from the list
08-16 15:27:27.798  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:27:27.798  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:27:27.799  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:27:27.799  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:27:27.800  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:27:27.800  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:27:27.801  6974  7031 D BluetoothLeScanner: could not find callback wrapper
08-16 15:27:27.801  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 15:27:27.801  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:27:27.801  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99f9786 not in the list
08-16 15:27:27.801  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:27:27.801  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:27:27.802  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:27:27.803  6974  7031 D BluetoothLeScanner: could not find callback wrapper
08-16 15:27:27.803  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.le.BleScanner: stop: Stopped
08-16 15:27:27.803  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:27:27.803  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:27:27.803  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@99f9786 not in the list
08-16 15:27:27.803  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:27:27.803  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:27:27.803  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:27:27.803  6974  7031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@1c5c7061 not in the list
08-16 15:27:27.804  6974  7031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: load: Already loaded
08-16 15:27:27.804  6974  ,7031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74da612 added. We now have 3 listener(s)
08-16 15:27:27.805  1044  1060 D BluetoothManagerService: checkIfCallerIsForegroundUser: valid=true callingUser=0 foregroundUser=0
08-16 15:27:27.807  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.AbstractBluetoothConnectivityAgent: verifyIdentityString: One or more of the following values are invalid: Peer name: "<no peer name>", Bluetooth MAC address: "58:3F:54:73:BA:17"
08-16 15:27:27.808  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: BluetoothConnector: Bluetooth name: Thali_Bluetooth, service record UUID: fa87c0d0-afac-11de-8a39-0800200c9a66
08-16 15:27:27.808  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: setIdentityString: 
08-16 15:27:27.808  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: load: Already loaded
08-16 15:27:27.808  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: addListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@89561e3 added. We now have 4 listener(s)
08-16 15:27:27.808  6974  7031 D org.thaliproject.p2p.btconnectorlib.utils.PeerModel: addListener: New listener added - the number of listeners is now 1
,08-16 15:27:27.814  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: setDiscoveryMode: Discovery mode BLE is supported
08-16 15:27:27.819  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: bind: Binding a new listener
08-16 15:27:27.822  6974  7031 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: FORCED notification:
08-16 15:27:27.822  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi Direct supported: true
08-16 15:27:27.822  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth LE multiple advertisement supported: NOT_SUPPORTED
08-16 15:27:27.822  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Wi-Fi enabled: true
08-16 15:27:27.822  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is Bluetooth enabled: true
08-16 15:27:27.822  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - BSSID name: f4:f2:6d:22:99:3e
08-16 15:27:27.822  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - is connected/connecting to active network: true
08-16 15:27:27.822  6974  7031 V io.jxcore.node.ConnectivityMonitor:     - active network type is Wi-Fi: true
,08-16 15:27:27.826  6974  7031 D io.jxcore.node.JXcoreExtension: notifyNetworkChanged: BLE: NOT_HERE, Bluetooth: ON, Wi-Fi: ON, cellular: DO_NOT_CARE, BSSID name: f4:f2:6d:22:99:3e
08-16 15:27:27.827  6974  7031 D io.jxcore.node.ConnectivityMonitor: start: OK
08-16 15:27:27.830  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:27:27.831  6974  6974 V io.jxcore.node.ConnectivityMonitor: updateConnectivityInfo: No relevant state changes
08-16 15:27:27.832  6974  7031 I io.jxcore.node.ConnectionHelper: stop: Stopping all activities and killing connections
08-16 15:27:27.832  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: false, is advertising: false - Stop operation: Should start/stop everything
08-16 15:27:27.832  6974  7031 V io.jxcore.node.StartStopOperationHandler: executeCurrentOperation: The current state already matches the desired outcome of this operation, skipping...
08-16 15:27:27.833  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:27:27.833  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:27:27.833  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 3 listener(s) left
08-16 15:27:27.833  6974  7031 I org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothConnector: shutdown: Shutting down...
08-16 15:27:27.833  6974  7031 V org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74da612 removed from the list
08-16 15:27:27.833  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:27:27.833  6974  7031 V org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@89561e3 removed from the list
08-16 15:27:27.833  6974  7031 D io.jxcore.node.ConnectivityMonitor: stop
08-16 15:27:27.833  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:27:27.834  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:27:27.835  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
,08-16 15:27:27.838  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:27:27.838  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:27:27.838  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:27:27.839  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@89561e3 not in the list
08-16 15:27:27.839  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:27:27.840  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:27:27.841  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopDiscovery
08-16 15:27:27.841  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: stopAdvertising
08-16 15:27:27.842  6974  7031 I org.thaliproject.p2p.btconnectorlib.DiscoveryManager: dispose
08-16 15:27:27.842  6974  7031 E org.thaliproject.p2p.btconnectorlib.DiscoveryManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.DiscoveryManager@89561e3 not in the list
08-16 15:27:27.842  6974  7031 I org.thaliproject.p2p.btconnectorlib.ConnectionManager: dispose
08-16 15:27:27.842  6974  7031 W org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: The given listener does not exist in the list - probably already removed
08-16 15:27:27.842  6974  7031 D org.thaliproject.p2p.btconnectorlib.internal.bluetooth.BluetoothManager: release: 2 listener(s) left
08-16 15:27:27.842  6974  7031 E org.thaliproject.p2p.btconnectorlib.ConnectionManagerSettings: removeListener: Listener org.thaliproject.p2p.btconnectorlib.ConnectionManager@74da612 not in the list
08-16 15:27:27.843  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: NOT_STARTED, is discovering: true, is advertising: true - Start operation: Should start/stop everything
08-16 15:27:27.843  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: NOT_STARTED, discovery: RUNNING_BLE, is discovering: false, is advertising: true - Start operation: Should start/stop everything
08-16 15:27:27.843  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Start operation: Should start/stop everything
08-16 15:27:27.843  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: false, is advertising: false - Start operation: Should affect listening to advertisements only
08-16 15:27:27.844  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should affect listening to advertisements only
08-16 15:27:27.844  6974  7031 V io.jxcore.node.StartStopOperation: isTargetState: Connectivity: RUNNING, discovery: RUNNING_BLE, is discovering: true, is advertising: false - Stop operation: Should start/stop everything
08-16 15:27:29.866  6974  9000 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 941, name: My test thread name)
,08-16 15:27:30.395  1044  1525 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=3.4, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:3006] from screen [on:0 period:-1819732133] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
,08-16 15:27:30.398  1044  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=3.4, 0.0, 0.0  rx=1.8 bcn=0 [on:0 tx:0 rx:0 period:3] from screen [on:0 period:-1819732130] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 15:27:30.398  1044  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 15:27:31.863  6974  7031 I io.jxcore.node.StreamCopyingThread: close: Thread ID: 941
,08-16 15:27:31.863  6974  7031 D io.jxcore.node.StreamCopyingThread: closeStreams: Streams closed (thread ID: 941, name: My test thread name)
,08-16 15:27:31.878  6974  9001 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 942, name: My test thread name)
08-16 15:27:31.878  6974  9001 D io.jxcore.node.StreamCopyingThread: The end of the input stream has been reached (thread ID: 942, thread name: My test thread name)
08-16 15:27:31.878  6974  9001 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 942, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 22
08-16 15:27:31.880  6974  7031 I io.jxcore.node.StreamCopyingThread: setBufferSize: Setting buffer size to 4096 bytes
08-16 15:27:31.884  6974  9002 D io.jxcore.node.StreamCopyingThread: Entering thread (ID: 946, name: My test thread name)
08-16 15:27:31.885  6974  9002 E io.jxcore.node.StreamCopyingThread: Failed to write to the output stream (thread ID: 946, thread name: My test thread name): Test exception.
08-16 15:27:31.885  6974  9002 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 946, name: My test thread name), during the lifetime of the thread the total number of bytes read was 22 and the total number of bytes written 0
,08-16 15:27:31.890  6974  7031 I jxcore-log: Total number of executed tests:  82
08-16 15:27:31.890  6974  7031 I jxcore-log: 
08-16 15:27:31.891  6974  7031 I jxcore-log: Number of passed tests:  82
08-16 15:27:31.891  6974  7031 I jxcore-log: 
08-16 15:27:31.891  6974  7031 I jxcore-log: Number of failed tests:  0
08-16 15:27:31.891  6974  7031 I jxcore-log: 
08-16 15:27:31.891  6974  7031 I jxcore-log: Number of ignored tests:  0
08-16 15:27:31.891  6974  7031 I jxcore-log: 
08-16 15:27:31.891  6974  7031 I jxcore-log: Total duration:  96635
08-16 15:27:31.891  6974  7031 I jxcore-log: 
08-16 15:27:31.892  6974  7031 I jxcore-log: ****TEST_LOGGER:[PROCESS_ON_EXIT_FAILED]****
08-16 15:27:31.892  6974  7031 I jxcore-log: 
08-16 15:27:31.906  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 15:27:31.906  6974  7031 I jxcore-log: 
08-16 15:27:31.909  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 15:27:31.909  6974  7031 I jxcore-log: 
,08-16 15:27:31.918  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 15:27:31.918  6974  7031 I jxcore-log: 
08-16 15:27:31.920  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 15:27:31.920  6974  7031 I jxcore-log: 
08-16 15:27:31.921  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 15:27:31.921  6974  7031 I jxcore-log: 
08-16 15:27:31.922  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 15:27:31.922  6974  7031 I jxcore-log: 
08-16 15:27:31.931  6974  6974 I chromium: [INFO:CONSOLE(74)] "UIApp is all set and ready!", source: file:///android_asset/www/js/thali_main.js (74)
,08-16 15:27:31.937  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: discoveryAdvertisingStateUpdateNonTCP: {"discoveryActive":false,"advertisingActive":false}
08-16 15:27:31.937  6974  7031 I jxcore-log: 
08-16 15:27:31.939  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 15:27:31.939  6974  7031 I jxcore-log: 
08-16 15:27:31.940  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 15:27:31.940  6974  7031 I jxcore-log: 
08-16 15:27:31.941  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 15:27:31.941  6974  7031 I jxcore-log: 
08-16 15:27:31.942  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 15:27:31.942  6974  7031 I jxcore-log: 
08-16 15:27:31.943  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 15:27:31.943  6974  7031 I jxcore-log: 
08-16 15:27:31.944  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 15:27:31.944  6974  7031 I jxcore-log: 
08-16 15:27:31.945  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 15:27:31.945  6974  7031 I jxcore-log: 
08-16 15:27:31.946  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 15:27:31.946  6974  7031 I jxcore-log: 
08-16 15:27:31.947  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 15:27:31.947  6974  7031 I jxcore-log: 
08-16 15:27:31.947  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare"}
08-16 15:27:31.947  6974  7031 I jxcore-log: 
08-16 15:27:31.948  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 15:27:31.948  6974  7031 I jxcore-log: 
08-16 15:27:31.949  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 15:27:31.949  6974  7031 I jxcore-log: 
08-16 15:27:31.950  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 15:27:31.950  6974  7031 I jxcore-log: 
08-16 15:27:31.950  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 15:27:31.950  6974  7031 I jxcore-log: 
08-16 15:27:31.951  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 15:27:31.951  6974  7031 I jxcore-log: 
08-16 15:27:31.952  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 15:27:31.952  6974  7031 I jxcore-log: 
08-16 15:27:31.953  6974  7031 I jxcore-log: DEBUG, thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 15:27:31.953  6974  7031 I jxcore-log: 
08-16 15:27:31.953  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 15:27:31.953  6974  7031 I jxcore-log: 
,08-16 15:27:31.958  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 15:27:31.958  6974  7031 I jxcore-log: 
08-16 15:27:31.960  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 15:27:31.960  6974  7031 I jxcore-log: 
08-16 15:27:31.961  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 15:27:31.961  6974  7031 I jxcore-log: 
08-16 15:27:31.961  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"off","wifi":"off","cellular":"doNotCare"}
08-16 15:27:31.961  6974  7031 I jxcore-log: 
08-16 15:27:31.962  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 15:27:31.962  6974  7031 I jxcore-log: 
08-16 15:27:31.963  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 15:27:31.963  6974  7031 I jxcore-log: 
08-16 15:27:31.964  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"off","cellular":"doNotCare"}
08-16 15:27:31.964  6974  7031 I jxcore-log: 
08-16 15:27:31.965  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 15:27:31.965  6974  7031 I jxcore-log: 
08-16 15:27:31.966  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare"}
08-16 15:27:31.966  6974  7031 I jxcore-log: 
08-16 15:27:31.967  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 15:27:31.967  6974  7031 I jxcore-log: 
08-16 15:27:31.968  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 15:27:31.968  6974  7031 I jxcore-log: 
08-16 15:27:31.968  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 15:27:31.968  6974  7031 I jxcore-log: 
08-16 15:27:31.969  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 15:27:31.969  6974  7031 I jxcore-log: 
08-16 15:27:31.970  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 15:27:31.970  6974  7031 I jxcore-log: 
08-16 15:27:31.971  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 15:27:31.971  6974  7031 I jxcore-log: 
08-16 15:27:31.972  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 15:27:31.972  6974  7031 I jxcore-log: 
08-16 15:27:31.972  6974  7031 I jxcore-log: DEBUG thaliMobileNativeWrapper: networkChanged: {"bluetoothLowEnergy":"notHere","bluetooth":"on","wifi":"on","cellular":"doNotCare","bssidName":"f4:f2:6d:22:99:3e"}
08-16 15:27:31.972  6974  7031 I jx,core-log: 
08-16 15:27:32.064  6974  9000 D io.jxcore.node.StreamCopyingThread: Exiting thread (ID: 941, name: My test thread name), during the lifetime of the thread the total number of bytes read was 143 and the total number of bytes written 143
,08-16 15:27:32.233  9003  9003 D AndroidRuntime: 
08-16 15:27:32.233  9003  9003 D AndroidRuntime: >>>>>> AndroidRuntime START com.android.internal.os.RuntimeInit <<<<<<
,08-16 15:27:32.239  9003  9003 D AndroidRuntime: CheckJNI is OFF
08-16 15:27:32.357  9003  9003 D AndroidRuntime: Calling main entry com.android.commands.pm.Pm
,08-16 15:27:32.369  1044  1115 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=-1: uninstall pkg
08-16 15:27:32.369  1044  1115 I ActivityManager: Killing 6974:com.test.thalitest/u0a118 (adj 0): stop com.test.thalitest
,08-16 15:27:32.433  1044  1981 I WindowState: WIN DEATH: Window{10e9eecd u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 15:27:32.434  1044  1530 D WifiService: Client connection lost with reason: 4
,08-16 15:27:32.444  1044  1981 D InputDispatcher: Window went away: Window{10e9eecd u0 com.test.thalitest/com.test.thalitest.MainActivity}
,08-16 15:27:32.528  1044  1115 I ActivityManager:   Force finishing activity ActivityRecord{63ad86e u0 com.test.thalitest/.MainActivity t6}
,08-16 15:27:32.558   347   373 E GBMv2   : DFP En is all cleared set to be enabled
,08-16 15:27:32.561  1044  1125 I ActivityManager: Force stopping com.test.thalitest appid=10118 user=0: pkg removed
,08-16 15:27:32.569  1044  1125 I ActivityManager:   Force finishing activity ActivityRecord{63ad86e u0 com.test.thalitest/.MainActivity t6 f}
08-16 15:27:32.570  1044  1125 W ActivityManager: Duplicate finish request for ActivityRecord{63ad86e u0 com.test.thalitest/.MainActivity t6 f}
,08-16 15:27:32.606  1044  2018 W ActivityManager: Spurious death for ProcessRecord{2e89a5eb 6974:com.test.thalitest/u0a118}, curProc for 6974: null
08-16 15:27:32.607  2019  2019 I [LGHome]EVENT: [Launcher.java:5338:onStart()]onStart
08-16 15:27:32.609  2019  2019 I [LGHome]EVENT: [Launcher.java:903:onResume()]onResume
,08-16 15:27:32.616  1927  4381 D SplitWindowPolicy: updateActivityStateChanged: resumed=false, screenId=0, isScreenFull=false
08-16 15:27:32.617  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1352:startLoader()]startLoader isLaunching=true
08-16 15:27:32.617  1927  4381 D SplitWindowPolicy: topRunningActivity=ActivityInfo{14485598 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-16 15:27:32.618  2019  2058 I [LGHome]Launcher.Model: [LauncherModel.java:1469:loadAndBindWorkspace()]loadAndBindWorkspace=0ms
08-16 15:27:32.618  1927  1944 D SplitWindowPolicy: updateActivityStateChanged: resumed=true, screenId=0, isScreenFull=false
08-16 15:27:32.618  1927  1944 D SplitWindowPolicy: topRunningActivity=ActivityInfo{3870f1f1 co.....Launcher}, taskId=5, activityType=1, bIsSplit=false
08-16 15:27:32.623  1589  1589 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_REMOVED, sendingUserId:0
,08-16 15:27:32.641  1044  1419 I InputReader: Reconfiguring input devices.  changes=0x00000010
,08-16 15:27:32.657  8137  8137 E LGBluetoothAvrcpQcomAdapter: [BTUI] [BTUI] onReceive()... android.intent.action.PACKAGE_REMOVED
08-16 15:27:32.657  8137  8137 D LGBluetoothAvrcpQcomAdapter: [BTUI] [+] updateMediaPlayerInfo
,08-16 15:27:32.660  1982  1982 D LIA_Service_RemotePackageHandler: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-16 15:27:32.660  2470  2610 W GeofencerStateMachine: Ignoring removeGeofence because network location is disabled.
08-16 15:27:32.664  3750  3750 D LIA_MrGDBLogger_PackageInfoDetector: [dreamwood]action: android.intent.action.PACKAGE_REMOVED, package: com.test.thalitest
08-16 15:27:32.674  1044  1114 W InputMethodInfo: Duplicated subtype definition found: , voice
,08-16 15:27:32.687  5023  5023 I art     : Explicit concurrent mark sweep GC freed 15446(886KB) AllocSpace objects, 0(0B) LOS objects, 35% free, 29MB/45MB, paused 534us total 105.271ms
,08-16 15:27:32.714  4919  4919 W System.err: android.content.pm.PackageManager$NameNotFoundException: com.test.thalitest
08-16 15:27:32.714  4919  4919 W System.err: 	at android.app.ApplicationPackageManager.getPackageInfo(ApplicationPackageManager.java:114)
08-16 15:27:32.714  4919  4919 W System.err: 	at com.lge.mlt.MptOnAppWatcher$1.onReceive(MptOnAppWatcher.java:44)
08-16 15:27:32.714  4919  4919 W System.err: 	at android.app.LoadedApk$ReceiverDispatcher$Args.run(LoadedApk.java:956)
08-16 15:27:32.715  4919  4919 W System.err: 	at android.os.Handler.handleCallback(Handler.java:739)
08-16 15:27:32.715  4919  4919 W System.err: 	at android.os.Handler.dispatchMessage(Handler.java:95)
08-16 15:27:32.715  4919  4919 W System.err: 	at android.os.Looper.loop(Looper.java:135)
08-16 15:27:32.715  4919  4919 W System.err: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 15:27:32.715  4919  4919 W System.err: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 15:27:32.715  4919  4919 W System.err: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 15:27:32.715  4919  4919 W System.err: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 15:27:32.715  4919  4919 W System.err: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
,08-16 15:27:32.722  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:306:loadCacheBitmapPostDelayed()]loadCacheBitmapPostDelayed() delay:1
08-16 15:27:32.723  1891  1891 D ActionManagerService: notifyUserLog: 1000003
08-16 15:27:32.724  3750  4914 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000003)
08-16 15:27:32.724  2019  2019 I [LGHome]LGActivityUtil: [LGActivityUtil.java:319:notifyToWeatherWidget()]broadcast to weather widget, intent: Intent { act=com.lge.launcher2.RESUME }
08-16 15:27:32.725  1589  1589 I [SystemUI]QSlideListController: onReceive = android.intent.action.PACKAGE_REMOVED
08-16 15:27:32.726  2019  2019 I [LGHome]EVENT: [Launcher.java:1056:onResume()]onResume end
08-16 15:27:32.729  2019  2019 I [LGHome]EVENT: [Launcher.java:1114:onPause()]onPause
,08-16 15:27:32.730  8444  8444 D PostponalbeReceiver: WSAndroidSystemIntentReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-16 15:27:32.740  1803  1803 I ConfigFetchService: PackageReceiver: Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 cmp=com.google.android.gms/.config.ConfigFetchService$PackageReceiver (has extras) }
08-16 15:27:32.746  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:247:writeCacheBitmapPostDelayed()]writeCacheBitmapPostDelayed() delay: we don't have a change point1
,08-16 15:27:32.748  1891  1891 D ActionManagerService: notifyUserLog: 1000004
08-16 15:27:32.749  3750  4914 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000004)
08-16 15:27:32.752  1044  1774 V SIM_STK : Menu title from STK is T-Mobile
08-16 15:27:32.755  1589  1589 I [SystemUI]AppWidgetPanel(QRemoteWidgetPanel): onReceive = android.intent.action.PACKAGE_REMOVED, packageName : com.test.thalitest
08-16 15:27:32.755  1589  1589 D KeyguardModel: mPackageIntentReceiver, received action: android.intent.action.PACKAGE_FULLY_REMOVED, sendingUserId:0
08-16 15:27:32.756  3750  4912 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 15:27:32.757  1589  1655 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-16 15:27:32.757  1589  1655 D KeyguardModel: createShortcutInfo...
08-16 15:27:32.761  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: mw_initial
08-16 15:27:32.761  2019  2019 I GBoardWebViewUtils: , create_time: 1430832262123
08-16 15:27:32.761  2019  2019 I GBoardWebViewUtils: , expire_time: 0
08-16 15:27:32.761  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyWellness/initial/initial.html?id=mw_initial
08-16 15:27:32.761  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.MYWELLNESS
08-16 15:27:32.761  2019  2019 I GBoardWebViewUtils: , display: false
08-16 15:27:32.761  2019  2019 I GBoardWebViewUtils: , animation: false }
08-16 15:27:32.761  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: dyk000
08-16 15:27:32.761  2019  2019 I GBoardWebViewUtils: , create_time: 1430832262287
08-16 15:27:32.761  2019  2019 I GBoardWebViewUtils: , expire_time: 0
08-16 15:27:32.761  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-16 15:27:32.761  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-16 15:27:32.761  2019  2019 I GBoardWebViewUtils: , display: false
08-16 15:27:32.761  2019  2019 I GBoardWebViewUtils: , animation: false }
,08-16 15:27:32.762  2019  2019 I GBoardWebViewUtils: checkExpiredAndRemoveCard() card: GBoardCard = { id: guide_1111111111116_1471007225619
08-16 15:27:32.762  2019  2019 I GBoardWebViewUtils: , create_time: 1471007226523
08-16 15:27:32.762  2019  2019 I GBoardWebViewUtils: , expire_time: 0
08-16 15:27:32.762  2019  2019 I GBoardWebViewUtils: , raw_uri: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-16 15:27:32.762  2019  2019 I GBoardWebViewUtils: , category: com.lge.intent.category.gboard.DOYOUKNOW
08-16 15:27:32.762  2019  2019 I GBoardWebViewUtils: , display: false
08-16 15:27:32.762  2019  2019 I GBoardWebViewUtils: , animation: false }
08-16 15:27:32.774  2173  2173 I ConfigService: onCreate
,08-16 15:27:32.777  2173  2173 I ConfigService: onBind for Intent { act=com.google.android.gms.config.UPDATE pkg=com.google.android.gms } action com.google.android.gms.config.UPDATE
08-16 15:27:32.778  2019  9036 D WallpaperManager: suggestDesiredDimensions(2880, 2560) by package(com.lge.launcher2)
08-16 15:27:32.779  1803  1803 I ConfigFetchService: onStartCommand Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest cmp=com.google.android.gms/.config.ConfigFetchService (has extras) }
08-16 15:27:32.785  2173  2173 I ConfigService: onBind returning update interface
08-16 15:27:32.786  2173  2173 I ConfigService: onBind for Intent { act=com.google.android.gms.config.START pkg=com.google.android.gms } action com.google.android.gms.config.START
08-16 15:27:32.786  2173  2173 I ConfigService: onBind returning config service
,08-16 15:27:32.792  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-16 15:27:32.793  2019  2019 I [LGHome]GBoardWebView: [GBoardWebView.java:321:loadCacheBitmap()]loadCacheBitmap()
08-16 15:27:32.796  1589  1655 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-16 15:27:32.796  1589  1655 D KeyguardModel: createShortcutInfo...
,08-16 15:27:32.807  2173  2173 I ConfigService: onDestroy
08-16 15:27:32.810  1589  1655 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-16 15:27:32.810  1589  1655 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 15:27:32.810  1589  1655 W ResourcesManager: Asset path '/system/framework/com.lge.telephony.sms.jar' does not exist or contains no resources.
08-16 15:27:32.811  1589  1655 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 15:27:32.811  1856  1856 D SplitUIManager: split_name #11 / not available #0
08-16 15:27:32.811  1589  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 15:27:32.811  1589  1655 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
08-16 15:27:32.811  1856  1856 D SplitUIService: removed split : 
08-16 15:27:32.814  1589  1655 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-16 15:27:32.814  1589  1655 D KeyguardModel: createShortcutInfo...
,08-16 15:27:32.817  1044  1044 I art     : Explicit concurrent mark sweep GC freed 26853(1587KB) AllocSpace objects, 2(32KB) LOS objects, 33% free, 43MB/65MB, paused 4.247ms total 217.131ms
08-16 15:27:32.818  1589  1655 W ResourcesManager: Asset path '/system/framework/com.lge.emoji.jar' does not exist or contains no resources.
08-16 15:27:32.818  1589  1655 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 15:27:32.818  1044  1125 I art     : WaitForGcToComplete blocked for 190.267ms for cause Explicit
08-16 15:27:32.827  1803  9039 D PackageBroadcastService: Received broadcast action=android.intent.action.PACKAGE_REMOVED and uri=com.test.thalitest
,08-16 15:27:32.835  1589  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 15:27:32.835  1589  1655 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-16 15:27:32.841  1589  1655 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-16 15:27:32.841  1589  1655 D KeyguardModel: createShortcutInfo...
,08-16 15:27:32.848  1589  1655 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 15:27:32.848  1589  1655 W ResourcesManager: Asset path '/system/framework/com.google.android.media.effects.jar' does not exist or contains no resources.
08-16 15:27:32.848  1589  1655 W ResourcesManager: Asset path '/system/framework/com.lge.divx.jar' does not exist or contains no resources.
08-16 15:27:32.848  1589  1655 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
08-16 15:27:32.850  1589  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 15:27:32.850  1044  1916 V SIM_STK : Menu title from STK is T-Mobile
08-16 15:27:32.850  1044  1916 V SIM_STK : Menu title from STK is T-Mobile
08-16 15:27:32.850  1589  1655 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-16 15:27:32.857  1589  1655 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-16 15:27:32.857  1589  1655 D KeyguardModel: createShortcutInfo...
08-16 15:27:32.862  1856  1856 D SplitUIManager: split_name #11 / not available #0
08-16 15:27:32.863  1856  1856 I SplitUIService: split app #11
,08-16 15:27:32.875  1589  1589 D KeyguardModel: handleShortcutListChanged...
08-16 15:27:32.875  1589  1589 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
,08-16 15:27:32.881  1589  1655 D KeyguardModel: package = com.android.contacts, class = com.android.contacts.activities.DialtactsActivity
08-16 15:27:32.881  1589  1655 D KeyguardModel: createShortcutInfo...
08-16 15:27:32.889  2019  2019 I [LGHome]EVENT: [Launcher.java:5349:onStop()]onStop
,08-16 15:27:32.903  1044  1907 W ActivityManager: getRecentTasks: caller 1002 does not hold GET_TASKS; limiting output
08-16 15:27:32.904  8137  8137 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Music
08-16 15:27:32.904  8137  8137 D LGBluetoothAvrcpQcomAdapter: [BTUI] installed app name: Google Play Music
08-16 15:27:32.904  8137  8137 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:0) ===
08-16 15:27:32.904  8137  8137 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Music
08-16 15:27:32.904  8137  8137 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.lge.music
08-16 15:27:32.904  8137  8137 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 15:27:32.904  8137  8137 D LGBluetoothAvrcpQcomAdapter: [BTUI] === MediaPlayerInfo (playerId:1) ===
08-16 15:27:32.904  8137  8137 D LGBluetoothAvrcpQcomAdapter: [BTUI]          displayName: Google Play Music
08-16 15:27:32.904  8137  8137 D LGBluetoothAvrcpQcomAdapter: [BTUI]          packageName: com.google.android.music
08-16 15:27:32.904  8137  8137 D LGBluetoothAvrcpQcomAdapter: [BTUI]          playState: 2 (PAUSED)
08-16 15:27:32.904  8137  8137 D LGBluetoothAvrcpQcomAdapter: [BTUI] [-] updateMediaPlayerInfo
08-16 15:27:32.911  1044  1044 D administrator: Handling package changes for user 0
08-16 15:27:32.922  1589  1655 D KeyguardModel: package = com.android.mms, class = com.android.mms.ui.ConversationList
08-16 15:27:32.922  1589  1655 D KeyguardModel: createShortcutInfo...
08-16 15:27:32.923  1589  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 15:27:32.923  1589  1655 W PackageManager: Failure retrieving resources for com.android.mms: Resource ID #0x0
,08-16 15:27:32.924  1589  1655 D KeyguardModel: package = com.lge.qmemoplus, class = com.lge.qmemoplus.ui.main.MainActivity
08-16 15:27:32.924  1589  1655 D KeyguardModel: createShortcutInfo...
08-16 15:27:32.926  1589  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 15:27:32.926  1589  1655 W PackageManager: Failure retrieving resources for com.lge.qmemoplus: Resource ID #0x0
08-16 15:27:32.927  1589  1655 D KeyguardModel: package = com.android.gallery3d, class = com.android.gallery3d.app.Gallery
08-16 15:27:32.927  1589  1655 D KeyguardModel: createShortcutInfo...
08-16 15:27:32.928  1589  1655 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 15:27:32.928  1589  1655 W PackageManager: Failure retrieving resources for com.android.gallery3d: Resource ID #0x0
08-16 15:27:32.930  1589  1655 D KeyguardModel: package = com.lge.camera, class = com.lge.camera.CameraApp
08-16 15:27:32.930  1589  1655 D KeyguardModel: createShortcutInfo...
08-16 15:27:32.933  1044  1774 V SIM_STK : Menu title from STK is T-Mobile
,08-16 15:27:32.941  1589  1589 D KeyguardModel: handleShortcutListChanged...
08-16 15:27:32.941  1589  1589 D com.lge.lockscreen.widget.draglayer.AbsUnlockHandler: onShortcutListChanged...
08-16 15:27:32.945  1803  9046 I PeopleContactsSync: CP2 sync disabled
08-16 15:27:32.948  5856  9047 E SQLiteLog: (284) automatic index on assetrefs(dataitems_id)
08-16 15:27:32.949  1803  5203 I Icing   : doRemovePackageData com.test.thalitest
08-16 15:27:32.953  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2230:run()] LauncherModel bind current page shortcut
,08-16 15:27:32.956  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 15:27:32.957  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Email] in screen 1 [1, 4]
08-16 15:27:32.958  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Play Store] in screen 1 [2, 4]
08-16 15:27:32.959  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Camera] in screen 1 [3, 4]
08-16 15:27:32.960  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Settings] in screen 1 [4, 4]
08-16 15:27:32.970   337   430 I ThermalEngine: Thermal-Server: Thermal received msg from  override
08-16 15:27:32.971  3257  9049 I Thermal-Lib: Thermal-Lib-Client: Client request sent
08-16 15:27:32.979  7278  7278 D AppUp4:PreloadHelper: added Exclude : com.test.thalitest
,08-16 15:27:32.984  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2244:run()] LauncherModel bind current page shortcut
08-16 15:27:32.984  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 15:27:32.984  1044  1120 I Timeline: Timeline: Activity_windows_visible id: ActivityRecord{1c0e4e57 u0 com.lge.launcher2/.Launcher t5} time:414010
08-16 15:27:32.987  2019  2096 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:107:countUnreadItems()]setTotalCount : 0
08-16 15:27:32.987  2019  2096 I [LGHome]NumberBadge.LGUnreadLgeEmailsBadge: [LGUnreadLgeEmailsBadge.java:108:countUnreadItems()]countUnreadItems() ended..
08-16 15:27:32.994  2369  9052 D VoicemailCleanupService: Cleaning up data for package: com.test.thalitest
08-16 15:27:32.999  1044  1044 I NotificationService: action=android.intent.action.PACKAGE_REMOVED queryReplace=false
08-16 15:27:32.999  1044  1044 D BackupManagerService: Received broadcast Intent { act=android.intent.action.PACKAGE_REMOVED dat=package:com.test.thalitest flg=0x4000010 (has extras) }
08-16 15:27:32.999  1044  1044 D JobSchedulerService: Receieved: android.intent.action.PACKAGE_REMOVED
,08-16 15:27:33.005  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Folder [Google] in screen 1 [0, 4]
08-16 15:27:33.005  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-16 15:27:33.006  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 15:27:33.013  1803  9045 I art     : Explicit concurrent mark sweep GC freed 68982(4MB) AllocSpace objects, 26(408KB) LOS objects, 51% free, 30MB/62MB, paused 1.191ms total 73.571ms
08-16 15:27:33.013  2019  2019 I [Concierge]WidgetView: ConciergeWidgetView is instantiated. sIsWidgetAttached : true
08-16 15:27:33.015  1803  1815 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/history_query.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-16 15:27:33.015  1803  1815 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/help_responses.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
,08-16 15:27:33.016  1803  1815 W SQLiteConnectionPool: A SQLiteConnection object for database '/data/data/com.google.android.gms/databases/metrics.db' was leaked!  Please fix your application to end transactions in progress properly and to close the database when it is no longer needed.
08-16 15:27:33.018  1044  1562 I ActivityManager: Start proc com.lge.email for broadcast com.lge.email/.receiver.PackageChangeReceiver: pid=9054 uid=10023 gids={50023, 9997, 3003, 4002, 1023, 1028, 1015, 3001, 3002} abi=armeabi-v7a
08-16 15:27:33.020  1044  1564 D TaskPersister: removeObsoleteFile: deleting file=6_task.xml
08-16 15:27:33.020  2589  2589 D [Concierge]Service: onStartCommand(). Type : 8
,08-16 15:27:33.021  2589  2589 D [Concierge]Service: Update widget. Component : {com.lge.concierge/com.lge.concierge.ConciergeWidgetProvider}
08-16 15:27:33.022  2589  2589 D [Concierge]Service: Update widget ID : 11
08-16 15:27:33.023  2019  2019 D [Concierge]WidgetView: change position of spinner
08-16 15:27:33.023  2019  2019 I [Concierge]WidgetView: initWebView(). Time : 1471354053023
08-16 15:27:33.024  2589  2589 D [Concierge]Service: onStartCommand(). Type : 0
08-16 15:27:33.038  1803  9045 W GmsApplication: Using Auth Proxy for data requests.
,08-16 15:27:33.039  2019  2019 I [Concierge]WebView: Return exist ConciergeWebView. Reuse : 607240109
08-16 15:27:33.039  2019  2019 D [Concierge]WidgetView: State Change : null -> AccInBeforeState
08-16 15:27:33.039  2019  2019 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-16 15:27:33.042  2019  2019 I [LgeWidgetLib]ExtViewHost: [LgeAppWidgetExtViewHost.java:136:setState()]New State = com.lge.lgewidgetlib.extview.NormalState@2f30c32d
08-16 15:27:33.042  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.concierge.ConciergeWidgetProvider] in screen 1 [0, 0]
08-16 15:27:33.043  1803  9045 W GmsApplication: Using Auth Proxy for data requests.
08-16 15:27:33.043  2019  2019 I [LGHome]Launcher.Model: [LauncherModel.java:2256:run()] LauncherModel bind current page widget
08-16 15:27:33.043  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 15:27:33.048  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.google.android.googlequicksearchbox.SearchWidgetProvider] in screen 1 [0, 2]
08-16 15:27:33.049  2019  2019 D [Concierge]WidgetView: isWidgetUpdateSkippable ? true
08-16 15:27:33.049  2019  2019 D [Concierge]WidgetBroadcastReceiver: New receiver registered. Self-unregister old one. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-16 15:27:33.049  2019  2019 W [Concierge]WidgetView: Widget kill message received. Destory myself. My : 1471353666398, New one : 1471354053023
08-16 15:27:33.049  2019  2019 D [Concierge]WidgetView: Unregister all receivers
08-16 15:27:33.049  2019  2019 W [Concierge]WidgetBroadcastReceiver: Tried unregister broadcastReceiver which is not registered. ID : com.lge.concierge.ConciergeWidgetView.CommonReceiver
08-16 15:27:33.050  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
,08-16 15:27:33.051  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Gallery] in screen 2 [0, 4]
08-16 15:27:33.052  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Calendar] in screen 2 [1, 4]
08-16 15:27:33.053  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [QuickMemo+] in screen 2 [2, 4]
08-16 15:27:33.054  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [Quick Remote] in screen 2 [3, 4]
08-16 15:27:33.056  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add Shortcut [FM Radio] in screen 2 [4, 4]
08-16 15:27:33.060  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 15:27:33.060  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 15:27:33.097  9054  9054 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 15:27:33.098  9054  9054 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 15:27:33.098  9054  9054 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 15:27:33.099  9054  9054 W ResourcesManager: Asset path '/system/framework/com.lge.zdi.splitwindow.jar' does not exist or contains no resources.
,08-16 15:27:33.100  2019  2019 I [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:121:initExtManager()]mExtViewHost created
08-16 15:27:33.108  2019  2019 E [LgeWidgetLib]LgeAppWidgetHostView: [LgeAppWidgetHostView.java:124:initExtManager()]Cannot setExtViewHost, mExtViewHost --> null
08-16 15:27:33.108  2019  2019 I [LGHome]EVENT: [Workspace.java:918:addInScreen()]Add AppWidget [com.lge.sizechangable.musicwidget.widget.MusicAppWidgetProvider4x1] in screen 2 [0, 0]
08-16 15:27:33.110  2019  2019 I [LGHome]Launcher: [Launcher.java:4127:setLoadOnResume()]setLoadOnResume
08-16 15:27:33.133  2019  2019 I Timeline: Timeline: Activity_idle id: android.os.BinderProxy@1857cb9e time:414158
,08-16 15:27:33.161  9054  9054 I LGEmail : [lifecycle]--onCreate() (at EmailMainApp.java onCreate 179)[v:null]
,08-16 15:27:33.169  9054  9054 D LGEmail : user build Type == true (at Util.java isUserModeBuildType 3507)[v:6.41.18]
08-16 15:27:33.172  1044  1125 I art     : Explicit concurrent mark sweep GC freed 11300(724KB) AllocSpace objects, 1(16KB) LOS objects, 33% free, 43MB/65MB, paused 1.628ms total 338.855ms
08-16 15:27:33.188  9054  9054 W ResourceType: No package identifier when getting value for resource number 0x00000000
08-16 15:27:33.207  9054  9054 D LgDataFeature: LgDataFeature() Constructor: none
08-16 15:27:33.207  9054  9054 D LgDataFeature: LgDataFeature() Constructor Done, null
,08-16 15:27:33.230  9003  9003 D AndroidRuntime: Shutting down VM
,08-16 15:27:33.236  1044  1114 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 15:27:33.240  1044  1114 W ResourceType: Failure getting entry for 0x7f0a0079 (t=9 e=121) (error -75)
08-16 15:27:33.260  2019  2019 I chromium: [INFO:CONSOLE(0)] "'window.webkitStorageInfo' is deprecated. Please use 'navigator.webkitTemporaryStorage' or 'navigator.webkitPersistentStorage' instead.", source:  (0)
,08-16 15:27:33.262  1044  1125 I ActivityManager: Start proc com.android.defcontainer for service com.android.defcontainer/.DefaultContainerService: pid=9076 uid=10004 gids={50004, 9997, 1028, 1015, 1023, 2001, 1035} abi=armeabi-v7a
08-16 15:27:33.271  2019  2019 I [LGHome]EVENT: [LauncherModel.java:1141:onReceive()]onReceive intent=Intent { act=android.search.action.SEARCHABLES_CHANGED flg=0x24000010 }
,08-16 15:27:33.299  1044  1942 I ActivityManager: Killing 8376:com.lge.formmanager/u0a26 (adj 15): empty #17
,08-16 15:27:33.301  2019  2910 I GBoardtInterface: onReloaded()
08-16 15:27:33.303  2019  2019 I GBoardWebViewClient: onPageFinished url:file:///android_asset/www/main.html
08-16 15:27:33.304  9054  9054 I PackageChangeReceiver: intent action : android.intent.action.PACKAGE_REMOVED (at PackageChangeReceiver.java onReceive 20)
08-16 15:27:33.325  1044  1981 W libprocessgroup: failed to open /acct/uid_10026/pid_8376/cgroup.procs: No such file or directory
,08-16 15:27:33.325  3750  4912 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 15:27:33.329  3750  3765 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 15:27:33.334  1891  1891 D ActionManagerService: notifyUserLog: 1000001
08-16 15:27:33.335  3750  4914 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-16 15:27:33.335  3750  4914 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-16 15:27:33.337  1044  1059 I ActivityManager: Killing 8629:com.android.chrome/u0a57 (adj 15): empty #17
,08-16 15:27:33.355  1982  1982 D LIA_Service_NativeEventReceiver: onReceive action : android.intent.action.PACKAGE_REMOVED = package:com.test.thalitest
08-16 15:27:33.355  1982  1982 I LIA_Service_PlatformUtil: startLIAService() : Trying to start LIA service ...
08-16 15:27:33.355  1891  1891 D ActionManagerService: notifyUserLog: 1000001
,08-16 15:27:33.356  1982  1982 D LIA_Service_LIAService: onStartCommand() : LIAService started! - id :4, intent : Intent { act=com.lge.ia pkg=com.lge.ia (has extras) }
08-16 15:27:33.357  3750  4914 D LIA_Informant_ActionManagerMessageHandler: handleMessage: what(1000) actionID(0x1000001)
08-16 15:27:33.357  3750  4914 D LIA_Informant_Tips_SmartTipsActionManager: onEvent() : ACTION_BOARD_ENABLED
08-16 15:27:33.357  3750  4914 D LIA_Informant_Tips_FormEventRepository: getSize() : size - 0
08-16 15:27:33.357  3750  4914 D LIA_Informant_Tips_SmartTipsActionManager: onSettingEvent() : GBoard On - add scheduler - 0
08-16 15:27:33.357  3750  4912 V BoardContentProvider: query(): uri(content://com.lge.mrg.boardcontent/gboard) projection(null) order(null)
08-16 15:27:33.359  1044  2018 W libprocessgroup: failed to open /acct/uid_10057/pid_8629/cgroup.procs: No such file or directory
08-16 15:27:33.359  8444  8444 D PostponalbeReceiver: OasPackageInstalledReceiver is processing the broadcast action 'android.intent.action.PACKAGE_REMOVED'.
08-16 15:27:33.362  2019  2019 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial return true
08-16 15:27:33.362  2019  2019 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyWellness/initial/initial2.html?id=mw_initial
08-16 15:27:33.364  2019  2019 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc] return true
08-16 15:27:33.364  2019  2019 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/Initial/initial2.html?id=dyk000&appname=[@string/sp_smart_tips_text]&desc=[@string/gboard_st_initialcard_desc]
08-16 15:27:33.365  2019  2019 D GBoardUriUtils: fileExists: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay return true
08-16 15:27:33.365  2019  2019 D GBoardWebViewUtils: changeCardUriByCategoryNum() chard uri is changed. return: file:///system/etc/mrg_default_forms/MyGuide/GBoard/UserGuideCard/4/userguide2.html?id=guide_1111111111116_1471007225619&desc=[@string/gboard_ugc_desc_single]&appname=[@string/sp_smart_tips_text]&display_type=overlay
08-16 15:27:33.390  1044  1562 I ActivityManager: Start proc com.lge.lifetracker for broadcast com.lge.lifetracker/.core.receiver.CoreEventReceiver: pid=9095 uid=10037 gids={50037, 9997, 3003, 3002, 3001, 1028, 1015} abi=armeabi-v7a
,08-16 15:27:33.424  1044  1525 E WifiStateMachine:  ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:3002] from screen [on:0 period:-1819729104] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 15:27:33.424  1044  1525 E WifiStateMachine:  L2ConnectedState CMD_RSSI_POLL 5 0 "NG700" f4:f2:6d:22:99:3e rssi=-55 f=2447 sc=60 link=72 tx=1.7, 0.0, 0.0  rx=0.9 bcn=0 [on:0 tx:0 rx:0 period:0] from screen [on:0 period:-1819729104] gl rssi=-55 ag=0 hr ls-=0 [56,56,56,56,61] brc=0 lrc=0
08-16 15:27:33.424  1044  1525 D WifiNative-wlan0: doString: [SIGNAL_POLL]
,08-16 15:27:33.446  9095  9095 E ActivityThread: Failed to find provider info for com.lge.lgaccount.provider
08-16 15:27:33.446  9095  9095 W LG Account v2.2: No ProfileInfo entries
08-16 15:27:33.446  9095  9095 I LG Account v2.2: isEnabled: false
08-16 15:27:33.446  9095  9095 I Feature : [Lifetracker]ver: 4.21.112(40211120)
08-16 15:27:33.446  9095  9095 I Feature : [Lifetracker]Country: EU
08-16 15:27:33.446  9095  9095 I Feature : [Lifetracker]Operator: OPEN
08-16 15:27:33.446  9095  9095 I Feature : [Lifetracker]Ranking support: false
,08-16 15:27:33.446  9095  9095 I Feature : [Lifetracker]Comfort support: false
08-16 15:27:33.446  9095  9095 I Feature : [Lifetracker]Accessory: true
08-16 15:27:33.446  9095  9095 I Feature : [Lifetracker]Health device: true
08-16 15:27:33.446  9095  9095 I Feature : [Lifetracker]Extra Pedometer: false
08-16 15:27:33.447  9095  9095 I Feature : [Lifetracker]Blood glucose device: false
08-16 15:27:33.447  9095  9095 I Feature : [Lifetracker]Device Number: 3
08-16 15:27:33.447  9095  9095 D CoreEventReceiver: [onReceive] Action=android.intent.action.PACKAGE_REMOVED
,08-16 15:27:33.477  1044  1949 I ActivityManager: Start proc com.android.settings for broadcast com.android.settings/.hotkey.PackageIntentReceiver: pid=9114 uid=1000 gids={41000, 9997, 1000, 1028, 1015, 2001, 3002, 3001, 1007, 3003, 1023, 1021, 3004, 3005, 3009, 1010, 1004, 2002, 3008, 1026, 1009, 1027, 1003, 1014, 4002, 1002} abi=armeabi-v7a
08-16 15:27:33.478  1044  1949 I ActivityManager: Killing 8652:com.lge.drmservice/u0a62 (adj 15): empty #17
,08-16 15:27:33.525  1044  2018 W libprocessgroup: failed to open /acct/uid_10062/pid_8652/cgroup.procs: No such file or directory
,08-16 15:27:33.538  9114  9114 W ResourcesManager: Asset path '/system/framework/com.google.android.maps.jar' does not exist or contains no resources.
08-16 15:27:33.538  9114  9114 W ResourcesManager: Asset path '/system/framework/cneapiclient.jar' does not exist or contains no resources.
08-16 15:27:33.538  9114  9114 W ResourcesManager: Asset path '/system/framework/com.lge.mdm.jar' does not exist or contains no resources.
08-16 15:27:33.539  9114  9114 W ResourcesManager: Asset path '/system/framework/com.lge.bluetooth.jar' does not exist or contains no resources.
08-16 15:27:33.539  9114  9114 W ResourcesManager: Asset path '/system/framework/qcrilhook.jar' does not exist or contains no resources.
08-16 15:27:33.540  9114  9114 W ResourcesManager: Asset path '/system/framework/com.broadcom.bt.jar' does not exist or contains no resources.
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: Failed to open database '/data/data/com.android.settings/databases/vibrateuserpattern.db'.
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: android.database.sqlite.SQLiteException: not an error (code 0): Could not open the database in read/write mode.
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.nativeOpen(Native Method)
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:209)
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnection.open(SQLiteConnection.java:193)
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.openConnectionLocked(SQLiteConnectionPool.java:463)
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:185)
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: 	at android.database.sqlite.SQLiteConnectionPool.open(SQLiteConnectionPool.java:177)
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openInner(SQLiteDatabase.java:907)
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.open(SQLiteDatabase.java:892)
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: 	at android.database.sqlite.SQLiteDatabase.openDatabase(SQLiteDatabase.java:795)
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: 	at android.app.ContextImpl.openOrCreateDatabase(ContextImpl.java:1213)
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: 	at android.content.ContextWrapper.openOrCreateDatabase(ContextWrapper.java:267)
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getDatabaseLocked(SQLiteOpenHelper.java:223)
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: 	at android.database.sqlite.SQLiteOpenHelper.getWritableDatabase(SQLiteOpenHelper.java:163)
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: 	at com.android.settings.vibratecreation.VibrateUserPatternProvider.onCreate(VibrateUserPatternProvider.java:243)
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1714)
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: 	at android.content.ContentProvider.attachInfo(ContentProvider.java:1683)
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: 	at android.app.ActivityThread.installProvider(ActivityThread.java:5014)
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: 	at android.app.ActivityThread.installContentProviders(ActivityThread.java:4609)
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: 	at android.app.ActivityThread.handleBindApplication(ActivityThread.java:4549)
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: 	at android.app.ActivityThread.access$1500(ActivityThread.java:148)
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: 	at android.app.ActivityThread$H.handleMessage(ActivityThread.java:1344)
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: 	at android.os.Handler.dispatchMessage(Handler.java:102)
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: 	at android.os.Looper.loop(,Looper.java:135)
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: 	at android.app.ActivityThread.main(ActivityThread.java:5274)
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Native Method)
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: 	at java.lang.reflect.Method.invoke(Method.java:372)
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit$MethodAndArgsCaller.run(ZygoteInit.java:909)
08-16 15:27:33.564  9114  9114 E SQLiteDatabase: 	at com.android.internal.os.ZygoteInit.main(ZygoteInit.java:704)
08-16 15:27:33.565  9114  9114 D AndroidRuntime: Shutting down VM

```
